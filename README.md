## Ola! Eu sou o Gregori Barreto


- 🖥️ Cursando Desenvolvimento de sistemas ...
- 💬 Finalizando 2º Grau ...
- 😄 Vivendo e aprendendo ...
- 💪 Sempre abraçando as oportunidades ...





<div> 

  <a href="https://www.instagram.com/gregikk/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 
  <a href="https://www.youtube.com/@GregiBut/" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>



  # Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: camilamaraschin
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
