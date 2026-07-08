md
     <div align="center">
     👋 Olá, eu sou o João Lucas
     🚚 Logística • ⚙️ Automações • 📊 Dados • 💻 Desenvolvimento

     <img
     src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=900&color=00F7FF&center=true&vCenter=true&width=800&lines=Transfor
     mando+problemas+operacionais+em+sistemas;Log%C3%ADstica+%2B+Automa%C3%A7%C3%A3o+%2B+IA;ADS+%7C+Python+%7C+JavaScript+%7C+BI+%7C+SAP"
     alt="Typing SVG" />

     </div>
     💫 About Me

     yaml
     nome: João Lucas
     área: Logística, processos e automações
     empresa: C.Vale
     formação: Análise e Desenvolvimento de Sistemas
     foco: Soluções reais para problemas operacionais
     interesses:
       - Python
       - JavaScript / Node.js
       - Excel / VBA
       - SAP
       - BI / Power BI
       - SQLite
       - IA aplicada
       - Automações
     ambiente:
       - Windows
       - WSL
       - GitHub
       - Obsidian

     🚀 O que eu gosto de construir

     - ⚙️ Automações para reduzir trabalho manual
     - 📊 Dashboards e indicadores para tomada de decisão
     - 🧠 Sistemas com IA aplicada ao mundo real
     - 🗄️ Soluções locais com banco de dados
     - 🚚 Ferramentas para logística, pátio, operação e controle
     - 🧩 Projetos simples, úteis e evolutivos

     > “Menos teoria parada, mais solução funcionando.” ⚡
     💻 Tech Stack

     <div align="center">

     Python
     JavaScript
     Node.js
     HTML5
     SQLite
     Power BI
     Excel
     VBA
     SAP
     Git
     WSL

     </div>
     🧠 Minha linha de evolução

     txt
     Operação real
        ↓
     Problema repetitivo
        ↓
     Automação simples
        ↓
     Indicador confiável
        ↓
     Sistema útil
        ↓
     Melhoria contínua

     🐍 Snake Game

     <div align="center">

     Snake animation

     </div>
     📊 GitHub Stats

     <div align="center">

     <img height="165"
     src="https://github-readme-stats.vercel.app/api?username=joaolucas2018com-design&theme=tokyonight&hide_border=true&show_icons=true&count_p
     rivate=true" />
     <img height="165"
     src="https://github-readme-stats.vercel.app/api/top-langs/?username=joaolucas2018com-design&theme=tokyonight&hide_border=true&layout=compa
     ct" />

     <br>

     <img src="https://streak-stats.demolab.com?user=joaolucas2018com-design&theme=tokyonight&hide_border=true" />

     </div>
     📈 Activity Graph

     <div align="center">

     <img src="https://github-readme-activity-graph.vercel.app/graph?username=joaolucas2018com-design&theme=tokyo-night&hide_border=true" />

     </div>
     🏆 GitHub Trophies

     <div align="center">

     <img src="https://github-profile-trophy.vercel.app/?username=joaolucas2018com-design&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8"
     />

     </div>
     🧰 Projetos e foco atual

     - 🚚 Sistema de controle operacional / pátio
     - 📊 BI com indicadores auditáveis
     - 🤖 Automações com IA
     - 🗃️ Organização técnica com Obsidian
     - ⚙️ Integrações entre operação, dados e sistemas
     🌐 Onde me encontrar

     <div align="center">

     GitHub
     LinkedIn

     </div>

     <div align="center">
     ⚡ Sempre aprendendo, testando e criando soluções úteis.

     Profile Views

     </div>

     Para a cobrinha funcionar, crie este arquivo também:

     .github/workflows/snake.yml

     yml
     name: Generate Snake

     on:
       schedule:
         - cron: "0 0 * * *"
       workflow_dispatch:

     permissions:
       contents: write

     jobs:
       generate:
         runs-on: ubuntu-latest

         steps:
           - name: Generate snake animation
             uses: Platane/snk/svg-only@v3
             with:
               github_user_name: joaolucas2018com-design
               outputs: |
                 dist/github-contribution-grid-snake.svg
                 dist/github-contribution-grid-snake-dark.svg?palette=github-dark

           - name: Push snake to output branch
             uses: crazy-max/ghaction-github-pages@v4
             with:
               target_branch: output
               build_dir: dist
             env:
               GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
