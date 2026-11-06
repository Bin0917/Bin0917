<h1 align="center">Bin0917</h1>

<p align="center">
  <code>Fintech</code> · <code>Backend</code> · <code>AI Security</code>
</p>

<p align="center">
  <a href="mailto:leesd132@naver.com"><img src="https://img.shields.io/badge/leesd132%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white" alt="leesd132@naver.com"></a>
  <a href="mailto:leesd365@gmail.com"><img src="https://img.shields.io/badge/leesd365%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="leesd365@gmail.com"></a>
  <a href="https://solved.ac/profile/shfur132"><img src="https://img.shields.io/badge/solved.ac%20Gold%205-1F8ACB?style=flat-square" alt="solved.ac Gold 5"></a>
</p>

---

## About Me

금융 IT 서비스를 만듭니다. 요즘은 서비스에 들어간 LLM을 안전하게 쓰는 방법에 관심이 많습니다.

- **관심 분야**: 금융 서비스 백엔드, MSA, LLM 보안
- **최근 작업**: LLM 챗봇 가드레일 구축과 garak 레드티밍 검증
- **자격증**: SQLD, ADsP

---

## Projects

<table>
  <tr>
    <th align="left">프로젝트<br/><img width="190" height="0"></th>
    <th align="left">내용<br/><img width="400" height="0"></th>
    <th align="left">기술 / 링크<br/><img width="210" height="0"></th>
  </tr>
  <tr>
    <td valign="top"><b>Pray for Hana</b><br/><sub>디지털하나로 8기 최종 · 2026.04</sub><br/><sub>우수상 (1등)</sub></td>
    <td valign="top">시니어 종교인 헌금·연금 금융 서비스<br/>• MSA 분리, OpenFeign·Kafka 통신 분리<br/>• 보상 트랜잭션<br/>• 담당: ERD 설계, S3 업로드(FE·BE)</td>
    <td valign="top"><code>Spring Boot</code> <code>Next.js</code> <code>Kafka</code> <code>AWS</code><br/><br/><a href="https://github.com/PrayForHanaro/Backend">Backend ↗</a> · <a href="https://github.com/PrayForHanaro/Frontend">Frontend ↗</a></td>
  </tr>
  <tr>
    <td valign="top"><b>PayCycle</b><br/><sub>외국인 근로자 임금 검증 챗봇 · 2026.09</sub><br/><sub>풀스택 · AI 보안 단독</sub></td>
    <td valign="top">챗봇 API AI 보안 계층 구축<br/>• NeMo Guardrails + Presidio 보안 서버<br/>• garak 공격 707건 적용 전후 비교<br/>• LLM 도달률 <b>82.4% → 23.8%</b> (p &lt; 0.001)</td>
    <td valign="top"><code>Spring Boot</code> <code>Python</code> <code>FastAPI</code><br/><br/><a href="https://github.com/Foreign-In-One/Backend/tree/feature/ai-guardrail-baseline">Backend ↗</a> · <a href="https://github.com/Foreign-In-One/Front/tree/feature/ai-chat-guardrail">Frontend ↗</a><br/><a href="https://github.com/Foreign-In-One/Backend/blob/feature/ai-guardrail-baseline/security-server/redteam/results/summary.md">레드티밍 결과 ↗</a></td>
  </tr>
  <tr>
    <td valign="top"><b>아이앞으로</b><br/><sub>디지털하나로 8기 1차 · 2026.01</sub><br/><sub>챗봇 · 화면 개발</sub></td>
    <td valign="top">미성년 자녀 증여 플랜 서비스<br/>• 세법 조건(증여세 한도·유기정기금) 프롬프트 규칙화<br/>• 자녀·계좌 생성 Prisma 트랜잭션</td>
    <td valign="top"><code>Next.js</code> <code>TypeScript</code> <code>Prisma</code> <code>OpenAI API</code><br/><br/><a href="https://github.com/F1-FamilyOne/foryouhana-mobileweb-ui">Frontend ↗</a></td>
  </tr>
</table>

---

## Open Source

<table>
  <tr>
    <th align="left">프로젝트<br/><img width="190" height="0"></th>
    <th align="left">기여<br/><img width="500" height="0"></th>
    <th align="left">상태<br/><img width="110" height="0"></th>
  </tr>
  <tr>
    <td valign="top"><b><a href="https://github.com/NVIDIA/garak/pulls?q=is%3Apr+author%3ABin0917">NVIDIA/garak</a></b><br/><sub>LLM 취약점 스캐너</sub></td>
    <td valign="top"><a href="https://github.com/NVIDIA/garak/pull/2305">#2305</a> promptinject 프롬프트 중복 생성 수정<br/><a href="https://github.com/NVIDIA/garak/pull/2326">#2326</a> 번역 프로브 공유 페이로드 오염 수정<br/><a href="https://github.com/NVIDIA/garak/pull/2362">#2362</a> 중복 페이로드 항목 제거</td>
    <td valign="top">Merged<br/>Merged<br/>Open</td>
  </tr>
  <tr>
    <td valign="top"><b><a href="https://github.com/data-privacy-stack/presidio">Presidio</a></b><br/><sub>개인정보 비식별화</sub></td>
    <td valign="top"><a href="https://github.com/data-privacy-stack/presidio/pull/2341">#2341</a> 한국어 컨텍스트 매칭 옵션<br/><a href="https://github.com/Bin0917/presidio-ko">presidio-ko</a> 한국 전화번호·계좌번호 인식기 패키지</td>
    <td valign="top">In review<br/>Package</td>
  </tr>
  <tr>
    <td valign="top"><b><a href="https://github.com/NVIDIA-NeMo/Guardrails">NeMo Guardrails</a></b><br/><sub>LLM 가드레일</sub></td>
    <td valign="top"><a href="https://github.com/NVIDIA-NeMo/Guardrails/issues/2415">#2415</a> Presidio 언어·spaCy 모델 설정 제안<br/><a href="https://github.com/NVIDIA-NeMo/Guardrails/issues/2429">#2429</a> 비 UTF-8 환경 설정 로딩 오류</td>
    <td valign="top">Issue<br/>Issue</td>
  </tr>
  <tr>
    <td valign="top"><b><a href="https://github.com/openai/openai-guardrails-python">OpenAI Guardrails</a></b><br/><sub>LLM 가드레일</sub></td>
    <td valign="top"><a href="https://github.com/openai/openai-guardrails-python/issues/151">#151</a> 한·중 텍스트 PII 미탐지</td>
    <td valign="top">Issue</td>
  </tr>
</table>

---

## Skills

<table>
  <tr>
    <th align="left">분야<br/><img width="190" height="0"></th>
    <th align="left">기술<br/><img width="610" height="0"></th>
  </tr>
  <tr>
    <td valign="top"><b>Backend</b></td>
    <td valign="top"><img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java"> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"> <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"></td>
  </tr>
  <tr>
    <td valign="top"><b>Frontend</b></td>
    <td valign="top"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"></td>
  </tr>
  <tr>
    <td valign="top"><b>Infra</b></td>
    <td valign="top"><img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"></td>
  </tr>
  <tr>
    <td valign="top"><b>AI</b></td>
    <td valign="top"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude"></td>
  </tr>
</table>

---

## Awards

<table>
  <tr>
    <th align="left">대회<br/><img width="190" height="0"></th>
    <th align="left">결과<br/><img width="400" height="0"></th>
    <th align="left">프로젝트<br/><img width="210" height="0"></th>
  </tr>
  <tr>
    <td valign="top"><b>디지털하나로 8기</b><br/><sub>최종 프로젝트 · 2026.04</sub></td>
    <td valign="top">우수상 (1등)</td>
    <td valign="top">Pray for Hana</td>
  </tr>
  <tr>
    <td valign="top"><b>멋쟁이사자처럼 대학 10기</b><br/><sub>단풍톤</sub></td>
    <td valign="top">최우수상 (2등)</td>
    <td valign="top">Dear Santa</td>
  </tr>
</table>
