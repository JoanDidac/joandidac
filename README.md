name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v2
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<h1 align="left">Hello World !</h1>

###

<h4 align="left">About me</h4>

###

<p align="left">I'm Joan Didac Hernandez 👋<br>I'm a full-stack web developer, leveraging my past experience in Facilities Management and the culinary industry to bring a unique perspective to tech solutions. I graduated from Ironhack Barcelona's web development bootcamp and have a strong grasp of the MERN stack.</p>

###

<h3 align="center">Tools/Lenguages/Stack</h3>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=joandidac&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=joandidac&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" width="52" alt="javascript logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" width="52" alt="react logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" width="52" alt="html5 logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" width="52" alt="css3 logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" width="52" alt="mongodb logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" width="52" alt="nodejs logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" width="52" alt="express logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/codepen/codepen-plain.svg" height="40" width="52" alt="codepen logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="40" width="52" alt="canva logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" height="40" width="52" alt="tailwindcss logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" width="52" alt="figma logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" width="52" alt="git logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/handlebars/handlebars-original.svg" height="40" width="52" alt="handlebars logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jasmine/jasmine-plain.svg" height="40" width="52" alt="jasmine logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" height="40" width="52" alt="jira logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/trello/trello-plain.svg" height="40" width="52" alt="trello logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" height="40" width="52" alt="visualstudio logo"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=joandidac.joandidac&left_color=darkviolet&right_color=rebeccapurple"  />
</div>

###

<div align="center">
  <img height="900" src="https://img.freepik.com/free-vector/abstract-colorful-transparent-polygonal-background_1055-5149.jpg?w=740&t=st=1683196070~exp=1683196670~hmac=d559a3db37290140f1ce2cd776878914fc7066e326dcb0c57699c27a831cd7be"  />
</div>

###

<img src="https://raw.githubusercontent.com/joandidac/joandidac/output/snake.svg" alt="Snake animation" />

###

<h3 align="center">Reach me at :</h3>

###

<div align="center">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/visualstudio/default.svg" width="52" height="40" alt="visualstudio logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitch/default.svg" width="52" height="40" alt="twitch logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/slack/default.svg" width="52" height="40" alt="slack logo"  />
</div>

###
