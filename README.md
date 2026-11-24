
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=210&section=header&text=Richa%20Sharma&fontSize=54&fontAlignY=36&animation=twinkling&desc=SDET%20%C2%B7%20Test%20Automation%20Engineer&descAlignY=58&descSize=20" alt="Richa Sharma, SDET" />

<a href="https://github.com/richasharma-testcraft">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2F81F7&center=true&vCenter=true&width=820&lines=Software+Development+Engineer+in+Test;I+build+automation+frameworks+teams+trust;Frameworks+integrated+with+Jenkins+CI%2FCD;Playwright+%7C+Selenium+%7C+REST+API;Open+for+freelance+projects" alt="Typing animation" />
</a>

<br/>

[![Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01ddc41dc7980f70ea?mp_source=share)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/richa-sharma-467714388)
[![Status](https://img.shields.io/badge/Status-Open%20for%20freelance-2EA043?style=for-the-badge)](https://www.upwork.com/freelancers/~01ddc41dc7980f70ea?mp_source=share)
![Profile views](https://komarev.com/ghpvc/?username=richasharma-testcraft&label=Profile%20views&color=0e75b6&style=for-the-badge)

<br/><br/>

<img src="./assets/sdet-desk.svg" alt="Animated illustration of an SDET at work while automated tests pass" width="800" />

</div>

---

## 👋 About Me

I'm an **SDET** who treats test automation as real software engineering: clean architecture, version control, code review, and pipelines that give a team fast, trustworthy feedback.

I help startups and small teams replace slow, flaky or missing testing with **maintainable UI and API automation that runs in CI**.

> 🧠 **My approach:** tests are code. They should be readable, reusable, deterministic, and cheap to maintain.

<div align="center">

<img src="./assets/terminal.svg" alt="Animated terminal showing a Playwright test run passing" width="800" />

</div>

---

## 🏗️ What I Can Build

> ⭐ **I design and build automation frameworks from scratch and integrate them with Jenkins CI/CD.**

| Service | What you get |
| --- | --- |
| 🏗️ **Automation framework from scratch** | A clean, scalable framework (Playwright/TypeScript or Selenium/Java/TestNG) with Page Objects, config management, reusable utilities and reporting |
| 🔁 **Jenkins integration** | Your framework wired into a Jenkins pipeline (`Jenkinsfile`) with parameterized suite runs, test reports and archived artifacts |
| 🎭 **Playwright E2E testing** | Cross-browser tests with fixtures, traces, screenshots and HTML reports |
| 🔌 **API test automation** | REST Assured or Postman suites with assertions, schema checks and reusable test data |
| ☕ **Selenium framework work** | Java + TestNG + Maven frameworks built, cleaned up, or migrated toward Playwright |
| 🧪 **Flaky test rescue** | Root-cause analysis of unstable tests and a concrete plan to stabilize them |
| ✅ **Regression and smoke suites** | Prioritized, automated coverage of your critical user flows |

### 📦 Ways to Work Together

| Package | Best for |
| --- | --- |
| 🔍 **Test Automation Audit** | A review of your current tests and CI, with a clear prioritized improvement plan |
| 🚀 **Framework Starter** | A new, well-structured automation framework set up for your app |
| 🔗 **Framework + Jenkins Setup** | A framework delivered together with its Jenkins pipeline, ready for your team to run |
| 🔧 **Rescue and Stabilize** | An existing flaky or slow suite made reliable and faster |

> 💬 Scope and pricing are tailored to your project. Tell me what you're testing and I'll suggest a first step.

---

## 🧱 Framework Architecture I Build

```mermaid
flowchart TB
    T["Test layer<br/>specs, scenarios, test data"] --> P["Page Objects / API clients"]
    P --> C["Core layer<br/>driver, fixtures, config, utilities"]
    C --> R["Reporting<br/>HTML, traces, screenshots, logs"]
    C --> E["Environments<br/>local, staging, CI"]
```

## 🔁 Framework to Jenkins, End to End

<div align="center">

<img src="./assets/pipeline.svg" alt="Animated pipeline: commit, build, API tests, UI tests, Jenkins, report" width="800" />

</div>

<details>
<summary><b>👀 Example of a Jenkins pipeline I set up (illustrative)</b></summary>
<br/>

```groovy
pipeline {
  agent any

  tools {
    maven 'Maven3'
    jdk 'JDK17'
  }

  parameters {
    choice(name: 'SUITE', choices: ['smoke', 'regression'], description: 'Test suite to run')
  }

  stages {
    stage('Checkout') {
      steps { checkout scm }
    }
    stage('Build') {
      steps { sh 'mvn -B clean compile' }
    }
    stage('Test') {
      steps { sh "mvn -B test -Dsuite=${params.SUITE}" }
    }
  }

  post {
    always {
      junit 'target/surefire-reports/*.xml'
      archiveArtifacts artifacts: 'target/**/*.html', allowEmptyArchive: true
    }
  }
}
```

</details>

---

## ⚙️ How I Work

1. **Understand** the product, risks and what actually needs protecting
2. **Design** a framework structure that fits the team and the stack
3. **Build** readable, deterministic tests with stable locators and clean data setup
4. **Integrate** into Jenkins or GitHub Actions with useful reports, traces and failure artifacts
5. **Hand off** with documentation so your team can maintain and extend it

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=playwright,ts,js,java,maven,jenkins,githubactions,postman,git,github,jira&perline=6" alt="Tech stack icons" />

<br/><br/>

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF7F00?style=flat-square)
![REST Assured](https://img.shields.io/badge/REST%20Assured-2C7A39?style=flat-square)
![Page Object Model](https://img.shields.io/badge/Page%20Object%20Model-6E40C9?style=flat-square)
![Cross Browser](https://img.shields.io/badge/Cross--Browser%20Testing-0A66C2?style=flat-square)
![Jenkins CI](https://img.shields.io/badge/Jenkins%20CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white)

</div>

| Area | Tools |
| --- | --- |
| **UI automation** | Playwright, Selenium WebDriver, TestNG, Page Object Model |
| **API testing** | REST Assured, Postman |
| **Languages** | TypeScript, JavaScript, Java |
| **Framework design** | Page Objects, fixtures, config management, reporting |
| **CI/CD and tooling** | Jenkins (Jenkinsfile pipelines), GitHub, Maven, Jira |

---

<!--
## 🚀 Featured Projects
Uncomment and edit this section as each demo repo goes live.

| Project | What it shows | Stack |
| --- | --- | --- |
| [playwright-ts-framework](https://github.com/richasharma-testcraft/playwright-ts-framework) | End-to-end framework with Page Objects, fixtures, reporting and CI | Playwright, TypeScript, GitHub Actions |
| [selenium-testng-jenkins](https://github.com/richasharma-testcraft/selenium-testng-jenkins) | Selenium framework with POM, TestNG and a Jenkinsfile | Java, Selenium, TestNG, Maven, Jenkins |
| [api-automation-restassured](https://github.com/richasharma-testcraft/api-automation-restassured) | API test suite with reusable specs and reports | Java, REST Assured, TestNG, Maven |
-->

<!--
## 📊 GitHub Stats
Uncomment after a few weeks of activity; stat cards look empty on a new profile.

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=richasharma-testcraft&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=richasharma-testcraft&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</div>
-->

<!--
## 🐍 Contribution Snake
Uncomment after adding .github/workflows/snake.yml and running it once.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/richasharma-testcraft/richasharma-testcraft/output/github-snake-dark.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/richasharma-testcraft/richasharma-testcraft/output/github-snake.svg" />
  </picture>
</div>
-->

## 💼 Experience

<details>
<summary><b>QA Automation Engineer, Dilato</b> · June 2026 – Present</summary>
<br/>

UI automation with Playwright, end-to-end workflow coverage, regression support and failure investigation.

</details>

<details>
<summary><b>Software Test Engineer, TEKPYRAMID</b> · November 2025 – May 2026</summary>
<br/>

Manual and automated testing with Selenium (Java), TestNG and Page Object Model.

</details>

<details>
<summary><b>Software QA Trainee, QSPIDERS</b> · January 2025 – October 2025</summary>
<br/>

Manual testing, Core Java, Selenium WebDriver and API testing fundamentals.

</details>

---

<div align="center">

### 📫 Let's build something reliable together

[![Upwork](https://img.shields.io/badge/Upwork-14A800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01ddc41dc7980f70ea?mp_source=share)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/richa-sharma-467714388)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/richasharma-testcraft)

<sub>This profile contains independent demonstration projects created to showcase test automation skills. No employer or client proprietary code, credentials, test data, or confidential information is included.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,20&height=120&section=footer" alt="footer" />
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

</div>
