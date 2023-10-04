<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
title ="JS" width = "50">&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" 
title ="Html" width = "50">&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" 
title ="CSS"  width = "50">&nbsp;
<div id="stat" align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kruleeo&theme=github_dark" alt=""/>
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Kruleeo&theme=github_dark" alt=""/>
     <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Kruleeo&theme=github_dark" alt=""/>
</div> 
steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ KruLeeo }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
