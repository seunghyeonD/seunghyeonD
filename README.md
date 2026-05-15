<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a3a4a,100:2a5a6a&height=220&section=header&text=Daniel&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Frontend%20Engineer&descSize=20&descAlignY=55&descColor=ffffff" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=1A3A4A&center=true&vCenter=true&random=false&width=720&lines=React+%7C+TypeScript+%7C+B2B+SaaS;Reports+%7C+Dashboards+%7C+WebView+%7C+Validation+UI;ESG+%2F+Carbon-domain+Frontend+Engineering)](https://git.io/typing-svg)

</div>

<br/>

## About

Frontend engineer building ESG/carbon-domain B2B SaaS with React and TypeScript.

I work on report, dashboard, WebView, calculation, and validation-heavy UI for enterprise products. Recently, I have focused on AI report generation UX for long-running async jobs, frontend quality improvements, migration work, and test foundations.

```ts
const daniel = {
  role: "Frontend Engineer",
  company: "Livit / Tansolution",
  experience: "3+ years",
  focus: [
    "ESG/carbon-domain B2B SaaS",
    "Report and dashboard UI",
    "Calculation and validation flows",
    "AI report generation UX",
    "Frontend quality and migration"
  ],
  publicLinks: {
    blog: "https://velog.io/@seunghyeond",
    linkedin: "https://www.linkedin.com/in/seunghyeon-dong/"
  }
};
```

<br/>

## Current Work

**Frontend Engineer @ Livit / Tansolution**  
`2023.04 - Present`

Tansolution is a B2B SaaS product for carbon emissions management, ESG reporting, reduction simulation, and monitoring.

- Build report, dashboard, WebView, calculation, and validation UI with React/TypeScript.
- Implement MACC simulation flows for 5 carbon-reduction measures.
- Develop ESG/reduction-project report screens and PDF/Excel output flows.
- Design frontend UX for AI report generation: progress/status UI, SSE subscription, validation feedback, retry, partial regeneration, and successful-section reuse.
- Improve frontend quality through MUI v5 to v7 migration, Webpack to Vite migration, moment.js to dayjs migration, and Vitest/RTL/jsdom test setup.

<br/>

## Selected Contributions

### AI Report Generation UX

- Designed UX for long-running AI report generation jobs.
- Implemented progress/status flows, SSE-based updates, validation feedback, retry, partial regeneration, and reuse of successful sections.
- Worked with async/backend integration context such as BullMQ, Redis, NestJS, Prometheus, and vLLM/Gemma-based generation.

### MACC Carbon Reduction Simulation

- Implemented input, validation, calculation, and result dashboard flows for 5 reduction measures: solar power, high-efficiency inverter, eco-friendly vehicles, high-efficiency lighting, and LNG conversion.
- Connected key calculation outputs such as marginal reduction cost, total carbon reduction, total reduction cost, and NPV discount logic to frontend UI.
- Added defensive UI logic for unit conversion, missing data, and operational edge cases.

### ESG / Reduction Project Reports

- Built frontend flows for ESG and reduction-project reports across screen, PDF, and Excel output.
- Improved consistency of number formatting, units, decimals, totals, dynamic sheet formulas, and multilingual report output.
- Worked with ExcelJS and jsPDF for report generation and export workflows.

### Frontend Quality Improvements

- Improved React component stability across 300+ changes.
- Migrated MUI v5 to v7, Webpack/react-app-rewired to Vite, and moment.js to dayjs.
- Set up Vitest + React Testing Library + jsdom and wrote 30+ utility tests.

<br/>

## Tech Stack

<div align="center">

### Frontend

![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white)

### Data, Forms, and Testing

![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Apollo Client](https://img.shields.io/badge/Apollo_Client-311C87?style=for-the-badge&logo=apollographql&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white)

### Reports and Visualization

![ExcelJS](https://img.shields.io/badge/ExcelJS-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![jsPDF](https://img.shields.io/badge/jsPDF-FF0000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)
![ApexCharts](https://img.shields.io/badge/ApexCharts-00A3E0?style=for-the-badge)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3dotjs&logoColor=white)

### Integration Context

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

</div>

<br/>

## Blog

More posts: [velog.io/@seunghyeond/posts](https://velog.io/@seunghyeond/posts)

<!-- BLOG-POST-LIST:START -->
- [AI report UX: Redis/BullMQ queue and SSE real-time updates](https://velog.io/@seunghyeond/RedisBullMQ%EB%A1%9C-%EB%B9%84%EB%8F%99%EA%B8%B0-%EB%A6%AC%ED%8F%AC%ED%8A%B8-%ED%81%90-SSE-%EC%8B%A4%EC%8B%9C%EA%B0%84-%EC%95%8C%EB%A6%BC-%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%9D%84-%EB%A7%8C%EB%93%A0-%EC%9D%B4%EC%95%BC%EA%B8%B0-zek62911)
- [Frontend perspective on a vLLM/Gemma-based AI report pipeline](https://velog.io/@seunghyeond/%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-vLLMGemma-4%EB%A1%9C-AI-%EB%B3%B4%EA%B3%A0%EC%84%9C-%EC%83%9D%EC%84%B1-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8%EC%9D%84-%EB%A7%8C%EB%93%A0-%EC%9D%B4%EC%95%BC%EA%B8%B0)
- [Introducing Vitest to a legacy frontend project](https://velog.io/@seunghyeond/4%EB%85%84%EC%B0%A8-%EB%A0%88%EA%B1%B0%EC%8B%9C-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%97%90-Vitest-%ED%85%8C%EC%8A%A4%ED%8A%B8-%ED%99%98%EA%B2%BD%EC%9D%84-%EC%B2%98%EC%9D%8C-%EB%8F%84%EC%9E%85%ED%95%9C-%EC%9D%B4%EC%95%BC%EA%B8%B0)
<!-- BLOG-POST-LIST:END -->

<br/>

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/dww7541@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dww7541@gmail.com)
[![GitHub](https://img.shields.io/badge/seunghyeonD-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seunghyeonD)
[![Velog](https://img.shields.io/badge/velog-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@seunghyeond)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seunghyeon-dong/)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a3a4a,100:2a5a6a&height=120&section=footer" width="100%" />

</div>
