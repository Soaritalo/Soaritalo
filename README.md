<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Italo%20Soares&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Data%20Engineer%20%7C%20Computer%20Engineering%20Student&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Engenharia+da+Computa%C3%A7%C3%A3o+%F0%9F%92%BB;An%C3%A1lise+%26+Ci%C3%AAncia+de+Dados+%F0%9F%93%8A;Python+%7C+SQL+%7C+Pandas+%7C+Power+BI+%E2%9A%A1;Estagiando+na+Unilog+%F0%9F%9A%80;Serra+-+ES+%2C+Brasil+%F0%9F%87%A7%F0%9F%87%B7)](https://git.io/typing-svg)

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Soaritalo&color=7c3aed&style=for-the-badge&label=VISITAS+NO+PERFIL)](https://github.com/Soaritalo)
[![GitHub followers](https://img.shields.io/github/followers/Soaritalo?style=for-the-badge&color=7c3aed&labelColor=1a1a2e&label=SEGUIDORES)](https://github.com/Soaritalo?tab=followers)

</div>

---

## 👨‍💻 Sobre mim

```python
italo = {
    "nome":      "Italo Soares",
    "localização": "Serra - ES, Brasil 🇧🇷",
    "formação":  "Engenharia da Computação",
    "empresa":   "Unilog (Estágio — Eng./Analista de Dados)",
    "foco":      ["Análise de Dados", "Ciência de Dados", "Engenharia de Dados"],
    "interesses":["Visualização de Dados", "Machine Learning", "BI"],
    "status":    "Aprendendo sempre 🚀"
}
```

---

## 🛠️ Tech Stack

<div align="center">

### 🐍 Linguagens & Consulta
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

### 📊 Dados & Análise
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

### 🗄️ Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

### 🔧 Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

</div>

---

## 📈 GitHub Stats

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=Soaritalo&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&border_radius=12&hide_border=true&bg_color=0d1117"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Soaritalo&layout=compact&langs_count=10&theme=tokyonight&border_radius=12&hide_border=true&bg_color=0d1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Soaritalo&theme=tokyonight&hide_border=true&background=0d1117&stroke=7c3aed&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&border_radius=12" alt="GitHub Streak"/>
</div>

---

## 🏆 Troféus

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Soaritalo&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="GitHub Trophies"/>
</div>

---

## 🐍 Contribuições

<div align="center">
  <img src="https://raw.githubusercontent.com/Soaritalo/Soaritalo/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>
</div>

> 💡 *Para ativar a cobrinha, vá em **Settings → Actions → General** e ative o GitHub Actions. Depois crie o workflow abaixo em `.github/workflows/snake.yml`*

<details>
<summary>⚙️ Workflow da cobrinha (clique para expandir)</summary>

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

## 📫 Conecte-se comigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-LINKEDIN-AQUI)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Soaritalo)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEU-EMAIL-AQUI)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" width="100%"/>

*"Transformando dados em decisões."* ✨

</div>
