<div align="center">
<img src="./svg/hero.svg" width="100%"/>
</div>

<br/>

<div align="center">
<img src="./svg/terminal.svg" width="560"/>
</div>

<br/><br/>

## About

<img src="./svg/about.svg" width="100%"/>

<br/>

## Tech Stack

<img src="./svg/tech-bars.svg" width="100%"/>

<br/>

## Skills

<img src="./svg/skill-cards.svg" width="100%"/>

<br/>

## Experience Timeline

<img src="./svg/timeline.svg" width="100%"/>

<br/>

## Dashboard

<img src="./svg/dashboard.svg" width="100%"/>

<br/>

## Featured Projects

<img src="./svg/projects.svg" width="100%"/>

<br/>

## GitHub Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=zeeshanhaider&show_icons=true&hide_border=true&hide_title=true&bg_color=161B22&title_color=58A6FF&icon_color=00E5FF&text_color=C9D1D9&ring_color=58A6FF"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zeeshanhaider&layout=compact&hide_border=true&hide_title=true&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&langs_count=6"/>
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=zeeshanhaider&hide_border=true&background=161B22&ring=58A6FF&fire=00E5FF&currStreakLabel=00E5FF&sideLabels=C9D1D9&currStreakNum=F0F6FC&sideNums=F0F6FC&dates=8B949E"/>
</p>

<blockquote>
Replace <code>zeeshanhaider</code> in the URLs above with your real GitHub username, or these will 404.
</blockquote>

<br/>

## Contribution Snake

<p align="center">
<img src="https://raw.githubusercontent.com/zeeshanhaider/zeeshanhaider/output/snake-dark.svg" width="100%"/>
</p>

<details>
<summary>GitHub Action to generate this (add as <code>.github/workflows/snake.yml</code>)</summary>

```yaml
name: snake
on:
  schedule: [{cron: "0 0 * * *"}]
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

<br/>

## Metrics

<p align="center">
<img src="https://metrics.lecoq.io/zeeshanhaider?template=classic&base=header,activity&config.timezone=Asia%2FKarachi&theme=github-dark" width="100%"/>
</p>

<br/>

<div align="center">
<img src="./svg/footer.svg" width="100%"/>
</div>
