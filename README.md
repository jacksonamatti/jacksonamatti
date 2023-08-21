# 💫 About Me:
## Olá! Seja bem-vindo(a) ao meu perfil do GitHub! 👋

Sou um entusiasta da tecnologia com uma paixão ardente pela programação.
Por meio da linguagem Python, minha especialidade, busco constantemente aprimorar processos e alcançar resultados excepcionais.Com uma inclinação a automação e analise de dados. Aqui, você encontrará uma variedade de projetos que refletem meu interesse em aprender e evoluir. Estou sempre aberto a oportunidades de colaboração e adoro trabalhar em equipe para resolver desafios complexos. Vamos codar e inovar juntos! 💻🌟

<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>



## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/https://www.instagram.com/jackson_amatti/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/jackson-amatti-dev/) 


# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=jacksonamatti&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=jacksonamatti&theme=nightowl&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=jacksonamatti&theme=nightowl&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=jacksonamatti&icon=1&color=1)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->


- uses: Platane/snk@v3
  with:
    github_user_name: ${{ https://github.com/jacksonamatti}}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
