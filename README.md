<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0B5D4B,100:00A88F&height=150&text=Bin0917&fontColor=ffffff&fontSize=46&fontAlignY=40&desc=Fintech%20%C2%B7%20AI%20Security&descSize=16&descAlignY=68&animation=fadeIn" width="100%" />

<p align="center">
  금융 IT 서비스를 만듭니다.<br/>
  요즘은 서비스에 들어간 LLM을 안전하게 쓰는 방법에 관심이 많습니다.
</p>

<p align="center">
  <a href="mailto:leesd132@naver.com"><img src="https://img.shields.io/badge/leesd132@naver.com-161b22?style=for-the-badge&logo=naver&logoColor=00E6A8" /></a>
</p>

<br/>

<p align="center"><img src="assets/title-stack.svg" alt="Tech Stack" width="100%" /></p>

<p align="center">
  <img src="https://img.shields.io/badge/BACKEND-00A88F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-161b22?style=for-the-badge&logo=openjdk&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/Spring_Boot-161b22?style=for-the-badge&logo=springboot&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/Kafka-161b22?style=for-the-badge&logo=apachekafka&logoColor=00E6A8" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/FRONTEND-00A88F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TypeScript-161b22?style=for-the-badge&logo=typescript&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/Next.js-161b22?style=for-the-badge&logo=nextdotjs&logoColor=00E6A8" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/INFRA_·_DB-00A88F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MySQL-161b22?style=for-the-badge&logo=mysql&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/AWS-161b22?style=for-the-badge&logo=amazonwebservices&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=for-the-badge&logo=docker&logoColor=00E6A8" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/AI-00A88F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-161b22?style=for-the-badge&logo=python&logoColor=00E6A8" />
  <img src="https://img.shields.io/badge/OpenAI_API-161b22?style=for-the-badge&logo=openai&logoColor=00E6A8" />
</p>

<br/>

<p align="center"><img src="assets/title-projects.svg" alt="Projects" width="100%" /></p>

<div align="center">

| Project | Highlights |
| :-- | :-- |
| **Pray for Hana**<br/><sub>디지털하나로 8기 최종 · 2026.04</sub><br/><img src="https://img.shields.io/badge/%EC%9A%B0%EC%88%98%EC%83%81-1%EB%93%B1-00A88F?style=flat-square&labelColor=0d1117" /><br/><br/>[Backend ↗](https://github.com/PrayForHanaro/Backend) · [Frontend ↗](https://github.com/PrayForHanaro/Frontend) | 시니어 종교인 헌금·연금 금융 서비스<br/><br/>• MSA 기반 서비스 분리<br/>• 동기(OpenFeign) · 비동기(Kafka) 통신 분리<br/>• 포인트 차감 실패 시 보상 트랜잭션<br/>• ERD 설계 · S3 업로드(FE·BE) 담당<br/><br/>`Spring Boot` `Next.js` `Kafka` `AWS` `Docker` |
| **PayCycle**<br/><sub>외국인 근로자 임금 검증 챗봇 · 2026.09</sub><br/><img src="https://img.shields.io/badge/ROLE-AI_%EB%B3%B4%EC%95%88-00A88F?style=flat-square&labelColor=0d1117" /><br/><br/>[Backend ↗](https://github.com/Foreign-In-One/Backend/tree/feature/ai-guardrail-baseline) · [Frontend ↗](https://github.com/Foreign-In-One/Front/tree/feature/ai-chat-guardrail) | 챗봇 API 대상 AI 보안 계층 구축<br/><br/>• OWASP LLM Top 10 · NIST AI RMF 기준 위협 정의<br/>• NeMo Guardrails + Presidio 보안 서버 분리 (fail-closed)<br/>• 한국어 개인정보 비식별화, 카나리아 토큰 유출 검사<br/>• garak 공격 707건 적용 전후 비교<br/><br/>`Spring Boot` `Python` `FastAPI` |
| **아이앞으로**<br/><sub>디지털하나로 8기 1차 · 2026.01</sub><br/><img src="https://img.shields.io/badge/ROLE-%EC%B1%97%EB%B4%87%C2%B7%ED%99%94%EB%A9%B4_%EA%B0%9C%EB%B0%9C-00A88F?style=flat-square&labelColor=0d1117" /><br/><br/>[Frontend ↗](https://github.com/F1-FamilyOne/foryouhana-mobileweb-ui) | 미성년 자녀 증여 플랜 서비스<br/><br/>• 세법 조건(증여세 한도·유기정기금) 프롬프트 규칙화<br/>• JSON 응답 고정으로 계산값 일관성 확보<br/>• 자녀·계좌 생성 Prisma 트랜잭션 처리<br/><br/>`Next.js` `TypeScript` `Prisma` `MySQL` `OpenAI API` |

</div>

> [!TIP]
> **PayCycle 레드티밍 결과** · garak 0.16.0, 같은 프롬프트로 적용 전후 비교
> - LLM 도달률 **82.4% → 23.8%** (p < 0.001)
> - 설계에 쓰지 않은 인코딩 공격 도달률 **100% → 43.8%**
> - 4개 언어(ko·en·vi·zh) 정상 질문 오탐 **0 / 60**
>
> [상세 결과 보기 ↗](https://github.com/Foreign-In-One/Backend/blob/feature/ai-guardrail-baseline/security-server/redteam/results/summary.md)

<br/>

<p align="center"><img src="assets/title-activity.svg" alt="Open Source · Activity" width="100%" /></p>

<p align="center">
  <a href="https://github.com/Bin0917/presidio-ko">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Bin0917&repo=presidio-ko&border_radius=12&title_color=00E6A8&icon_color=00E6A8&text_color=c9d1d9&bg_color=0d1117&border_color=0B5D4B" />
      <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Bin0917&repo=presidio-ko&border_radius=12&title_color=0B5D4B&icon_color=00A88F&text_color=24292f&bg_color=ffffff&border_color=00A88F" />
    </picture>
  </a>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Bin0917&show_icons=true&hide=stars%2Cissues&hide_rank=true&card_width=400&border_radius=12&title_color=00E6A8&icon_color=00E6A8&text_color=c9d1d9&bg_color=0d1117&border_color=0B5D4B" />
    <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Bin0917&show_icons=true&hide=stars%2Cissues&hide_rank=true&card_width=400&border_radius=12&title_color=0B5D4B&icon_color=00A88F&text_color=24292f&bg_color=ffffff&border_color=00A88F" />
  </picture>
</p>

<br/>

<p align="center"><img src="assets/title-awards.svg" alt="Awards" width="100%" /></p>

<p align="center">
  <img src="https://img.shields.io/badge/%EC%9A%B0%EC%88%98%EC%83%81%20%C2%B7%201%EB%93%B1-00A88F?style=flat-square" />&nbsp;
  <b>디지털하나로 8기 최종 프로젝트</b> · Pray for Hana
</p>
<p align="center">
  <img src="https://img.shields.io/badge/%EC%B5%9C%EC%9A%B0%EC%88%98%EC%83%81%20%C2%B7%202%EB%93%B1-00A88F?style=flat-square" />&nbsp;
  <b>멋쟁이사자처럼 대학 10기 단풍톤</b> · Dear Santa
</p>
<p align="center">
  <img src="https://img.shields.io/badge/%EC%9A%B0%EC%88%98%EC%83%81-00A88F?style=flat-square" />&nbsp;
  <b>이니로</b> · 웹스터
</p>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>
