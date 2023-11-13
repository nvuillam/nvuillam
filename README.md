# Nicolas Vuillamy

  * [Who am I](#who-am-i)
  * [Open-source projects](#open-source-projects)
  * [Latest articles](#latest-articles)
  * [Speaker activities](#speaker-activities)
    * [Agenda](#agenda)
    * [Past Events](#past-events)
  * [Webinars & Podcasts](#webinars--podcasts)
  * [Some stats](#some-stats)

## Who am I

- **CTO** during the day at [Cloudity](https://www.cloudity.com/)
- [**Open-Sourcerer**](#open-source-projects) during nights and week-ends (and also sometimes during the day thanks to Cloudity's [sfdx-hardis initiative](https://sfdx-hardis.cloudity.com/) !)
- Sometimes [**Writer on Medium**](#latest-articles)
- Sometimes [**Speaker**](#speaker-activities)
- Sometimes participant to [**Webinars & Podcasts**](#webinars---podcasts)

> I love to teach what I know and to learn what I don't know :)

> The only stupid questions are the ones you're too shy or too proud to ask !

You can follow and contact me on:

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-vuillamy)
[![](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://nicolas.vuillamy.fr/)
[![](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/NicolasVuillamy)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@nicolasvuillamy)
[![Stack Exchange](https://img.shields.io/badge/StackExchange-%23ffffff.svg?style=for-the-badge&logo=StackExchange)](https://stackexchange.com/users/8652527)

To support my open-source work, you can **star my repositorie**s, **follow me on github** or even [**sponsor me**](https://github.com/sponsors/nvuillam) :)

---

## Open-source projects

I created and still maintain several open-source projects:

- [MegaLinter](#megalinter)
- [sfdx-hardis](#sfdx-hardis)
- [vscode-sfdx-hardis](#vscode-sfdx-hardis)
- [npm-groovy-lint](#npm-groovy-lint)
- [vscode-groovy-lint](#vscode-groovy-lint)
- [sfdx-essentials](#sfdx-essentials)
- [java-caller](#java-caller)
- [node-sarif-builder](#node-sarif-builder)
- [markdown-table-formatter](#markdown-table-formatter)
- [github-dependents-info](#github-dependents-info)

I also contribute to many others :)

---

### [MegaLinter](https://github.com/oxsecurity/megalinter)

[![MegaLinter Banner](https://github.com/oxsecurity/megalinter/raw/main/docs/assets/images/megalinter-banner.png)](https://megalinter.io)

![GitHub release](https://img.shields.io/github/v/release/megalinter/megalinter?sort=semver)
[![Docker Pulls](https://img.shields.io/badge/docker%20pulls-3.1M-blue)](https://megalinter.github.io/flavors/)
[![Downloads/week](https://img.shields.io/npm/dw/mega-linter-runner.svg)](https://npmjs.org/package/mega-linter-runner)
[![GitHub stars](https://img.shields.io/github/stars/megalinter/megalinter?cacheSeconds=3600)](https://github.com/megalinter/megalinter/stargazers/)
[![GitHub contributors](https://img.shields.io/github/contributors/oxsecurity/megalinter.svg)](https://gitHub.com/oxsecurity/megalinter/graphs/contributors/)
[![MegaLinter](https://github.com/megalinter/megalinter/workflows/MegaLinter/badge.svg?branch=main)](https://github.com/megalinter/megalinter/actions?query=workflow%3AMegaLinter+branch%3Amain)

MegaLinter is an **Open-Source** tool for **CI/CD workflows** that analyzes the **consistency of your code**, **IAC**, **configuration**, and **scripts** in your repository sources, to **ensure all your projects sources are clean and formatted** whatever IDE/toolbox is used by their developers, powered by [**OX Security**](https://www.ox.security/?ref=megalinter).

Supporting [**55** languages](https://megalinter.io/latest/supported-linters/#languages), [**24** formats](https://megalinter.io/latest/supported-linters/#formats), [**20** tooling formats](https://megalinter.io/latest/supported-linters/#tooling-formats) and **ready to use out of the box**, as a GitHub action or any CI system **highly configurable** and **free for all uses**.

- Online documentation: <https://megalinter.io/>
- Repository: https://github.com/oxsecurity/megalinter

---

### [sfdx-hardis](https://github.com/hardisgroupcom/sfdx-hardis)

[![sfdx-hardis Banner](https://raw.githubusercontent.com/hardisgroupcom/sfdx-hardis/main/docs/assets/images/sfdx-hardis-banner.png)](https://sfdx-hardis.cloudity.com)

[![Version](https://img.shields.io/npm/v/sfdx-hardis.svg)](https://npmjs.org/package/sfdx-hardis)
[![Downloads/week](https://img.shields.io/npm/dw/sfdx-hardis.svg)](https://npmjs.org/package/sfdx-hardis)
[![Downloads/total](https://img.shields.io/npm/dt/sfdx-hardis.svg)](https://npmjs.org/package/sfdx-hardis)
![Docker Pulls](https://img.shields.io/docker/pulls/hardisgroupcom/sfdx-hardis)
[![GitHub stars](https://img.shields.io/github/stars/hardisgroupcom/sfdx-hardis?cacheSeconds=3600)](https://github.com/hardisgroupcom/sfdx-hardis/stargazers/)
[![GitHub contributors](https://img.shields.io/github/contributors/hardisgroupcom/sfdx-hardis.svg)](https://gitHub.com/hardisgroupcom/sfdx-hardis/graphs/contributors/)
[![Mega-Linter](https://github.com/hardisgroupcom/sfdx-hardis/workflows/Mega-Linter/badge.svg?branch=main)](https://github.com/hardisgroupcom/sfdx-hardis/actions?query=workflow%3AMega-Linter+branch%3Amain)

Salesforce DX plugin with lots of useful commands allowing to:

- Do with simple commands what could be done manually in minutes/hours
- [Define a complete CI/CD Pipeline for your Salesforce project](https://sfdx-hardis.cloudity.com/salesforce-ci-cd-home/)
- [Backup Metadatas and monitor any Salesforce org](https://sfdx-hardis.cloudity.com/salesforce-monitoring-home/)

- Online documentation: <https://hardisgroupcom.github.io/sfdx-hardis/>
- Repository: <https://github.com/hardisgroupcom/sfdx-hardis>

---

### [vscode-sfdx-hardis](https://github.com/hardisgroupcom/vscode-sfdx-hardis)

[![](https://github.com/hardisgroupcom/vscode-sfdx-hardis/raw/main/resources/extension-demo.gif)](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-sfdx-hardis)

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/NicolasVuillamy.vscode-sfdx-hardis)](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-sfdx-hardis)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/NicolasVuillamy.vscode-sfdx-hardis)](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-sfdx-hardis)
[![Mega-Linter](https://github.com/hardisgroupcom/vscode-sfdx-hardis/workflows/Mega-Linter/badge.svg?branch=master)](https://github.com/nvuillam/mega-linter#readme)
[![GitHub stars](https://img.shields.io/github/stars/hardisgroupcom/vscode-sfdx-hardis.png?label=stars&cacheSeconds=3600)](https://github.com/hardisgroupcom/vscode-sfdx-hardis/stargazers/)

[Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-sfdx-hardis) embedding sfdx-hardis but also other plugins

- Repository: <https://github.com/hardisgroupcom/vscode-sfdx-hardis>

---

### [npm-groovy-lint](https://nvuillam.github.io/npm-groovy-lint/)

[![Version](https://img.shields.io/npm/v/npm-groovy-lint.svg)](https://npmjs.org/package/npm-groovy-lint)
[![Downloads/week](https://img.shields.io/npm/dw/npm-groovy-lint.svg)](https://npmjs.org/package/npm-groovy-lint)
[![Downloads/total](https://img.shields.io/npm/dt/npm-groovy-lint.svg)](https://npmjs.org/package/npm-groovy-lint)
[![Mega-Linter](https://github.com/nvuillam/npm-groovy-lint/workflows/Mega-Linter/badge.svg?branch=master)](https://nvuillam.github.io/mega-linter)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/npm-groovy-lint?label=stars&cacheSeconds=3600)](https://github.com/nvuillam/npm-groovy-lint/stargazers/)
[![Docker Pulls](https://img.shields.io/docker/pulls/nvuillam/npm-groovy-lint)](https://hub.docker.com/r/nvuillam/npm-groovy-lint)

Groovy linter, formatter and auto-fixer

- Online documentation: <https://nvuillam.github.io/npm-groovy-lint/>
- Repository: <https://github.com/nvuillam/npm-groovy-lint/>

---

### [vscode-groovy-lint](https://github.com/nvuillam/vscode-groovy-lint/)

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/NicolasVuillamy.vscode-groovy-lint)](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-groovy-lint)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/NicolasVuillamy.vscode-groovy-lint)](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-groovy-lint)
[![Mega-Linter](https://github.com/nvuillam/vscode-groovy-lint/workflows/Mega-Linter/badge.svg?branch=master)](https://github.com/nvuillam/mega-linter#readme)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/vscode-groovy-lint.png?label=stars&cacheSeconds=3600)](https://github.com/nvuillam/vscode-groovy-lint/stargazers/)

[Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-groovy-lint) embedding npm-groovy-lint

- Online documentation: <https://nvuillam.github.io/vscode-groovy-lint/>
- Repository: <https://github.com/nvuillam/vscode-groovy-lint/>

---

### [sfdx-essentials](https://github.com/nvuillam/sfdx-essentials/)

[![Version](https://img.shields.io/npm/v/sfdx-essentials.svg)](https://npmjs.org/package/sfdx-essentials)
[![Downloads/week](https://img.shields.io/npm/dw/sfdx-essentials.svg)](https://npmjs.org/package/sfdx-essentials)
[![Downloads/total](https://img.shields.io/npm/dt/sfdx-essentials.svg)](https://npmjs.org/package/sfdx-essentials)
[![Mega-Linter](https://github.com/nvuillam/sfdx-essentials/workflows/Mega-Linter/badge.svg?branch=master)](https://github.com/nvuillam/mega-linter#readme)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/sfdx-essentials?label=stars&cacheSeconds=3600)](https://github.com/nvuillam/sfdx-essentials/stargazers/)

Toolbox to ease the use of Salesforce DX for development and deployment

- Repository: <https://github.com/nvuillam/sfdx-essentials/>

---

### [java-caller](https://github.com/nvuillam/node-java-caller/)

[![Version](https://img.shields.io/npm/v/java-caller.svg)](https://www.npmjs.com/package/java-caller)
[![Downloads/week](https://img.shields.io/npm/dw/java-caller.svg)](https://npmjs.org/package/java-caller)
[![Downloads/total](https://img.shields.io/npm/dt/java-caller.svg)](https://npmjs.org/package/java-caller)
[![Mega-Linter](https://github.com/nvuillam/node-java-caller/workflows/Mega-Linter/badge.svg)](https://github.com/nvuillam/mega-linter#readme)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/node-java-caller?label=stars&cacheSeconds=3600)](https://GitHub.com/nvuillam/node-java-caller/stargazers/)

Library to easily deliver and execute java applications using node/npm

- Repository: <https://github.com/nvuillam/node-java-caller/>

---

### [node-sarif-builder](https://github.com/nvuillam/node-sarif-builder)

[![Version](https://img.shields.io/npm/v/node-sarif-builder.svg)](https://npmjs.org/package/node-sarif-builder)
[![Downloads/week](https://img.shields.io/npm/dw/node-sarif-builder.svg)](https://npmjs.org/package/node-sarif-builder)
[![Downloads/total](https://img.shields.io/npm/dt/node-sarif-builder.svg)](https://npmjs.org/package/node-sarif-builder)
[![Mega-Linter](https://github.com/nvuillam/node-sarif-builder/workflows/MegaLinter/badge.svg?branch=main)](https://megalinter.github.io/)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/node-sarif-builder?label=stars&cacheSeconds=3600)](https://github.com/nvuillam/node-sarif-builder/stargazers/)

Module to easily build SARIF logs within a javascript / typescript application

- Repository: https://github.com/nvuillam/node-sarif-builder

---

### [markdown-table-formatter](https://github.com/nvuillam/markdown-table-formatter)

[![](https://raw.githubusercontent.com/nvuillam/markdown-table-formatter/master/docs/assets/images/banner.jpg)](https://github.com/nvuillam/markdown-table-formatter)

[![Version](https://img.shields.io/npm/v/markdown-table-formatter.svg)](https://npmjs.org/package/markdown-table-formatter)
[![Downloads/week](https://img.shields.io/npm/dw/markdown-table-formatter.svg)](https://npmjs.org/package/markdown-table-formatter)
[![Downloads/total](https://img.shields.io/npm/dt/markdown-table-formatter.svg)](https://npmjs.org/package/markdown-table-formatter)
[![MegaLinter](https://github.com/nvuillam/markdown-table-formatter/workflows/Mega-Linter/badge.svg)](https://github.com/nvuillam/mega-linter#readme)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/markdown-table-formatter?label=stars&cacheSeconds=3600)](https://github.com/nvuillam/markdown-table-formatter/stargazers/)

Utility to automatically format markdown tables in files

- Repository: https://github.com/nvuillam/markdown-table-formatter

---

### [github-dependents-info](https://github.com/nvuillam/github-dependents-info/)

[![PyPI](https://img.shields.io/pypi/v/github-dependents-info)](https://pypi.org/project/github-dependents-info/)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/github-dependents-info)](https://pypi.org/project/github-dependents-info/)
[![GitHub stars](https://img.shields.io/github/stars/nvuillam/github-dependents-info?cacheSeconds=3600)](https://github.com/nvuillam/github-dependents-info/stargazers/)
[![Build status](https://github.com/nvuillam/github-dependents-info/workflows/build/badge.svg?branch=main&event=push)](https://github.com/nvuillam/github-dependents-info/actions?query=workflow%3Abuild)
[![MegaLinter](https://github.com/nvuillam/github-dependents-info/workflows/MegaLinter/badge.svg?branch=main)](https://oxsecurity.github.io/megalinter)
[![License](https://img.shields.io/github/license/nvuillam/github-dependents-info)](https://github.com/nvuillam/github-dependents-info/blob/master/LICENSE)

Collect information about dependencies between a github repo and other repositories. Results available in JSON, markdown and badge

- Repository: https://github.com/nvuillam/github-dependents-info/

---

## Latest articles

[![image](https://github.com/nvuillam/nvuillam/assets/17500430/9c280b00-a3bd-4417-9c0c-f1605c22fa8b)]((https://www.programmez.com/magazine/article/megalinter-votre-meilleur-allie-pour-du-code-clean-et-securise)) 

_(paper, in [Programmez Magazine (FR)](https://www.programmez.com/))_

[![image](https://github.com/nvuillam/nvuillam/assets/17500430/6420fb3a-0da2-48f2-be80-6f32b0b3236a)](https://salesforcedevops.net/index.php/2023/03/01/sfdx-hardis-open-source-salesforce-release-management/)

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/0"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/0" alt="Recent Article 0">
  
<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/1"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/1" alt="Recent Article 1">
    
<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/2"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/2" alt="Recent Article 2">
  
<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/3"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/3" alt="Recent Article 3">
  
<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/4"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/4" alt="Recent Article 4">

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/5"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/5" alt="Recent Article 5">

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/6"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/6" alt="Recent Article 6">  

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/7"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/7" alt="Recent Article 7">  

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/8"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/8" alt="Recent Article 8">  

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/9"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@nicolasvuillamy/9" alt="Recent Article 9">  

---

## Speaker activities

### Agenda

- 2023-11-30: [Automate the Monitoring of your Salesforce orgs with open-source tools only !](https://frenchtouchdreamin.com/index.php/schedule/) at [French Touch Dreamin](https://frenchtouchdreamin.com/)
- 2023-11-30: [Aim for Flow Excellence with the Lightning Flow Scanner](https://frenchtouchdreamin.com/index.php/schedule/) at [French Touch Dreamin](https://frenchtouchdreamin.com/)
- 2023-12-14: [DevCon #20, 100% Sécurité et qualité du code (FR)](https://www.programmez.com/page-devcon/devcon-20-100-securite-qualite-du-code) at [ESGI School](https://www.esgi.fr/)

### Past events

- Dreamforce 2023, San Francisco: [_**Easy Salesforce CI/CD with open-source and clicks only thanks to sfdx-hardis!**_](https://reg.salesforce.com/flow/plus/df23/sessioncatalog/page/catalog/session/1684196389783001OqEl), with Jean-Pierre Rizzi

[![Video](https://img.youtube.com/vi/o0Mm9F07UFs/0.jpg)](https://www.youtube.com/watch?v=o0Mm9F07UFs)

- Dreamforce 2023, San Francisco: [_**Build Innovative Tools With CLI Plug-Ins, the sf Way**_](https://reg.salesforce.com/flow/plus/df23/sessioncatalog/page/catalog/session/1684196389689001O7uD), with Andres Catalan and Shane Mc Laughlin

[![image](https://github.com/nvuillam/nvuillam/assets/17500430/8756b4fc-3796-4aa3-a165-e435b58e51cf)](https://www.linkedin.com/posts/nicolas-vuillamy_how-to-install-sfdx-hardis-for-an-enhanced-activity-7114908492812963840-mQR0?utm_source=share&utm_medium=member_desktop)

- Yeur Dreamin' 2023, Brussels: _**An easy and complete Salesforce CI/CD release management with open-source only !**_, with Angélique Picoreau

[![image](https://github.com/nvuillam/nvuillam/assets/17500430/6470df20-7449-444b-a0a5-7dc22f5f6188)](https://www.linkedin.com/posts/nicolas-vuillamy_cicd-opensource-trailblazercommunity-activity-7076859027321704448-F1g-?utm_source=share&utm_medium=member_desktop)

- French Touch Dreamin' 2022, Paris: _**Simplify your trailblazer life with open source**_

[![Video](https://github.com/nvuillam/nvuillam/assets/17500430/a5e6b58a-5156-4951-9ef1-6723135df171)](https://www.youtube.com/watch?v=WE46LL6kRBY)

## Webinars & Podcasts

- SalesforceBen, 2023: _**Ask Us Anything - Salesforce DevOps & CI/CD**_

[![Video](https://img.youtube.com/vi/-1UTUzMfHzI/0.jpg)](https://www.youtube.com/watch?v=-1UTUzMfHzI)

- Salesforce Developers Podcast, by Josh Birk, 2023: [_**Episode 182: SFDX-Hardis with Nicolas Vuillamy**_](https://developer.salesforce.com/podcast/2023/06/sfdx)

[![image](https://github.com/nvuillam/nvuillam/assets/17500430/998bcf0e-e977-4831-8b3d-66b10dc9ecf8)](https://developer.salesforce.com/podcast/2023/06/sfdx)

- Cloudity Webinar, 2023: _**Fluidifier le parcours des assureurs avec Profideo**_ , avec Guillaume Hedon (FR)

[![Video](https://img.youtube.com/vi/tR_DzQQ3XTk/0.jpg)](https://www.youtube.com/watch?v=tR_DzQQ3XTk)

- SalesforceDevOps.net, by Vernon Keenan, 2023: _**SFDX-HARDIS – A demo with Nicolas Vuillamy from Cloudity**_

[![Video](https://img.youtube.com/vi/qP6MaZUGzik/0.jpg)](https://www.youtube.com/watch?v=qP6MaZUGzik)

---

## Some stats

[![committers.top badge](https://user-badge.committers.top/france_public/nvuillam.svg)](https://user-badge.committers.top/france_public/nvuillam)

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=nvuillam&theme=dark&show_icons=true)

[![trophy](https://github-profile-trophy.vercel.app/?username=nvuillam&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)  
  
![nvuillam's Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nvuillam&langs_count=8&theme=radical&layout=compact&card_width=445)

[![Stackexchange profile](https://stackexchange.com/users/flair/8652527.png)](https://stackexchange.com/users/8652527)

![Profile views](https://komarev.com/ghpvc/?username=nvuillam&color=green)
