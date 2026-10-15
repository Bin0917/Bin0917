<div align="center">

### 금융 IT 서비스를 만드는 개발자입니다

Spring과 Next.js로 백엔드부터 화면까지 직접 만들고,<br/>
요즘은 서비스 안에 들어간 LLM을 어떻게 안전하게 쓸지에 관심이 많습니다.

<br/>

<img src="https://skillicons.dev/icons?i=java,spring,python,ts,nextjs,mysql,kafka,aws,docker" />

</div>

---

### Projects

**1. Pray for Hana** · 디지털하나로 8기 최종 프로젝트 🏆 우수상 (1등)<br/>
시니어 종교인의 헌금·연금을 하나은행과 연결하는 금융 서비스입니다.<br/>
서비스를 MSA로 나누고, 잔액 확인처럼 바로 맞아야 하는 호출은 OpenFeign으로, 헌금 통계처럼 조금 늦어도 되는 처리는 Kafka로 나눴습니다. 포인트 차감에 실패하면 이미 저장된 헌금 기록을 되돌리도록 보상 처리를 넣었습니다. ERD 설계, S3 업로드(FE·BE), 서비스 간 통신을 맡았습니다.<br/>
`Spring Boot` `Next.js` `Kafka` `AWS` `Docker` · [Backend](https://github.com/PrayForHanaro/Backend) · [Frontend](https://github.com/PrayForHanaro/Frontend)

**2. PayCycle** · 외국인 근로자 임금 검증 챗봇<br/>
공모전에서 보안을 놓친 게 아쉬워서 끝난 뒤에 직접 보완한 프로젝트입니다.<br/>
OWASP LLM Top 10 기준으로 빈 곳을 점검하고 NeMo Guardrails와 Presidio로 보안 서버를 붙였습니다. garak으로 같은 공격 707건을 적용 전후에 보내 비교했고, 공격이 LLM까지 닿는 비율을 82.4%에서 23.8%로 줄였습니다 (p < 0.001).<br/>
`Spring Boot` `Next.js` `Python` · [Backend](https://github.com/Foreign-In-One/Backend) · [Frontend](https://github.com/Foreign-In-One/Front)

**3. 아이앞으로** · 디지털하나로 8기 1차 프로젝트<br/>
부모가 미성년 자녀에게 증여할 플랜을 짜주는 서비스입니다.<br/>
증여세 한도, 유기정기금 같은 세법 조건을 시스템 프롬프트에 규칙으로 걸고 JSON으로만 답하게 해서 계산값이 흔들리지 않게 했습니다. 자녀와 계좌 생성은 Prisma 트랜잭션으로 묶어 중간에 실패하면 전부 되돌아가게 했습니다.<br/>
`Next.js` `TypeScript` `Prisma` `MySQL` `OpenAI API` · [Frontend](https://github.com/F1-FamilyOne/foryouhana-mobileweb-ui)

### Awards

- Dear Santa · 멋쟁이사자처럼 대학 10기 단풍톤 최우수상
- 웹스터 · 이니로 우수상

### Contact

- leesd132@naver.com
