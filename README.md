<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:ec4899&height=200&section=header&text=Hi,%20I'm%20Selina&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineering%20%40%20CODE%20Berlin%20%C2%B7%20AI%20agents%20and%20automation&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Header" />

<a href="https://github.com/meuselina">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=640&lines=I+build+AI+agents+and+automations;Code+%C3%97+Design+%C3%97+Psychology;Head+of+Marketing+%40+mitJulia;Open+to+a+summer+2027+internship" alt="Typing SVG" />
</a>

<p>
  <a href="https://selinameusel.com"><img src="https://img.shields.io/badge/Portfolio-selinameusel.com-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/selinameusel"><img src="https://img.shields.io/badge/LinkedIn-selinameusel-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://selinameusel.com/assets/Selina_Meusel_CV.pdf"><img src="https://img.shields.io/badge/CV-Download%20PDF-22c55e?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Download CV" /></a>
  <a href="mailto:selina.meusel@icloud.com"><img src="https://img.shields.io/badge/Email-Say%20hi-ec4899?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Open%20to-Summer%202027%20Internship-22c55e?style=flat-square" alt="Open to internship" />
  <img src="https://img.shields.io/badge/Available-May%20to%20Sept%202027-0ea5e9?style=flat-square" alt="Available" />
  <img src="https://img.shields.io/badge/Based%20in-Berlin-f59e0b?style=flat-square" alt="Berlin" />
</p>

</div>

---

## 👩‍💻 About me

Software Engineering student at **CODE University of Applied Sciences** in Berlin.
I build things that make complex information easier to understand, right where **code, design and psychology** meet.

- 🎓 Started coding at 15 in an advanced computer science course at school
- 🌉 Spent a year in **San Francisco**: AI & operations internship at a psychology coaching practice, au pair, and a **Stanford Continuing Studies** program in technology leadership
- 🏆 **2nd place** at the CODE Hackathon with Vibolingo
- 🌍 German · English · Chinese (HSK 3)

## 🔭 What I'm working on

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏛️ AIchitect</h3>
      A Python pipeline that turns an architect's DWG files and floor plans into a 3D model, V-Ray and Veras renders and a print-ready magazine for client presentations. It runs end to end and takes <b>about a week instead of three months</b>. I did the analysis, research, automation and the first version of the code.
      <br/><br/><a href="#aichitect">See the roadmap ↓</a>
    </td>
    <td width="50%" valign="top">
      <h3>📞 Head of Marketing @ <a href="https://friseurtelefon.de">mitJulia</a></h3>
      An AI receptionist that picks up the phone for hair salons. I own content strategy, video scripts and Meta Ads on our way to <b>1M ARR</b>.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💡 Focus display</h3>
      Built with my Software Engineering professor: a small hardware screen next to your computer that shows whether your code is still running and whether you're heads-down or free to talk.
    </td>
    <td width="50%" valign="top">
      <h3>🤖 My own AI agents on Claude</h3>
      A morning briefing from my inbox and calendar, an agent that turns emails into calendar events, a weekly bilingual newsletter and an evening Chinese vocab tutor.
    </td>
  </tr>
</table>

<a id="aichitect"></a>

## 🏛️ AIchitect: from floor plan to sales brochure

An 11 stage pipeline that turns an architect's plans into a millimetre accurate 3D model, verified floor plans and living areas, photoreal renderings and a finished brochure layout. Built for residential developers in Germany, Austria and Switzerland. The code is private, so here is the architecture instead.

<p align="center">
  <img src="https://github.com/meuselina/meuselina/raw/main/media/aichitect-overview.png" width="100%" alt="AIchitect roadmap: 11 pipeline stages from intake to deliver" />
</p>

- **One source of truth:** the 3D model is never edited by hand, it is always rebuilt from the building plan
- **Independent stages:** every stage has a fixed input and output contract and can be rerun on its own
- **Selective rebuild:** change a wall color and only the stages that depend on it run again
- **Verified geometry:** the model is measured back to 2D and compared with the plan, max deviation 0.3 mm on the sample house

<a id="medics"></a>

## 🧴 Medics: a skin analysis that explains itself

Group project at CODE University (Group 23, with Mario, Larissa and Nikolas). An app that reads your skin from three guided photos and a short quiz, explains in plain words what it sees, and suggests one safety-checked cream made by a certified lab. The code lives in a private group repo, so here is the overview instead.

<p align="center">
  <img src="https://github.com/meuselina/meuselina/raw/main/media/medics-overview.png" width="100%" alt="Medics overview: ten steps from three photos to one safety-checked cream" />
</p>

- **Research first:** 18 interviews with 21 people and a survey with 37 answers led to seven insights, for example "Trust is the product" and "Custom reads as pricier, not better"
- **Model with guardrails:** a three-photo pipeline with clinical image filters, the ABCD rule and the 7-point checklist, and a multi-view ConvNeXt. Low confidence becomes "uncertain", red flags send you to a dermatologist
- **Fair by design:** balanced sampling over skin tones, every metric split by Fitzpatrick skin type, and a biopsy-proven test set kept untouched
- **Safe formula:** allergies and reactions become a never-in-your-formula list, actives stay within EU limits and conflicting combinations are blocked

<details>
<summary><b>The app prototype (36 screens)</b></summary>
<br/>
<p align="center">
  <img src="https://github.com/meuselina/meuselina/raw/main/media/medics-app-screens.png" width="90%" alt="mira app prototype screens: welcome, photo guide, camera, results, safety profile, ingredients, formula, order" />
</p>
</details>

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,ts,html,css,mysql,git,github,githubactions,vscode,cloudflare&perline=12" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude-LLM%20Agents-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/AutoCAD-DWG-E51050?style=for-the-badge&logo=autocad&logoColor=white" alt="AutoCAD" />
  <img src="https://img.shields.io/badge/V--Ray-Rendering-1f2937?style=for-the-badge" alt="V-Ray" />
  <img src="https://img.shields.io/badge/TypeScript-learning-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript (learning)" />
</p>

## 📂 Featured projects

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="#medics">🧴 Medics</a></h3>
      AI skin analysis from three photos that explains what it sees and suggests one safety-checked cream. Group project at CODE University, with user research, a 36-screen app prototype and a skin analysis pipeline in Python. <a href="#medics">See the overview ↓</a><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
      <img src="https://img.shields.io/badge/Prototype-HTML%20%2F%20JS-1f2937?style=flat-square" alt="Prototype" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/Vibolingo">🏆 Vibolingo</a></h3>
      2nd place at the CODE Hackathon. "Duolingo for vibe coding": five minute lessons that teach people how to direct AI to build real apps.<br/><br/>
      <a href="https://meuselina.github.io/Vibolingo/"><img src="https://img.shields.io/badge/Live%20demo-22c55e?style=flat-square&logo=githubpages&logoColor=white" alt="Live demo" /></a>
      <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/My-personal-website-and-CV">🌐 Personal website</a></h3>
      Trilingual portfolio (EN / DE / ZH) with newsletter and an AI agents section.<br/><br/>
      <a href="https://selinameusel.com"><img src="https://img.shields.io/badge/Live-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Live" /></a>
      <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" />
      <img src="https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white" alt="CSS" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/image-simplifier">🎨 Image Simplifier</a></h3>
      Command line tool that shrinks PNG files by merging similar colors (color quantization).<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/CLI-1f2937?style=flat-square" alt="CLI" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/Shop-coded-with-Java">🛍️ Fashion shop</a></h3>
      Desktop shop app with categories, search and price sorting, built with inheritance.<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/Swing-1f2937?style=flat-square" alt="Swing" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/binary-trees">🌳 Binary Trees</a></h3>
      Binary tree algorithms: traversals, height, search and insert.<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/tests-19%20passing-22c55e?style=flat-square" alt="19 tests" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/meuselina/java-calculator">🧮 Calculator</a></h3>
      Console calculator with input validation and big number support.<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/tests-15%20passing-22c55e?style=flat-square" alt="15 tests" />
    </td>
  </tr>
</table>

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/meuselina/meuselina/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/meuselina/meuselina/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/meuselina/meuselina/output/github-snake.svg" />
  </picture>
</p>

## 📫 Let's connect

I'm looking for a **summer 2027 internship** (free from May to September) in **AI engineering or full stack**, ideally at an early-stage startup where I can ship real things. If that sounds like your team, I'd love to hear from you.

<p align="center">
  <a href="https://selinameusel.com"><img src="https://img.shields.io/badge/Portfolio-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/selinameusel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://selinameusel.com/assets/Selina_Meusel_CV.pdf"><img src="https://img.shields.io/badge/CV-Download%20PDF-22c55e?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Download CV" /></a>
  <a href="mailto:selina.meusel@icloud.com"><img src="https://img.shields.io/badge/selina.meusel%40icloud.com-ec4899?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:8b5cf6,100:ec4899&height=120&section=footer" width="100%" alt="Footer" />
