# 📊 Sales Ops AI Skills

**사업 직무(AM · MD · BD)가 분석가 없이 스스로 분석할 수 있게 돕는 AI 스킬 예제 모음**

목표 대비 실적, 세일즈 퍼널 전환, 목표/전망 갭 분석처럼 영업 조직이 매주 묻는 질문을 AI 에이전트가 일관된 기준으로 답하게 만드는 스킬과, 그 바탕이 되는 데이터 마트 설계 가이드를 담았어요.

> 모든 샘플 데이터는 예시를 위해 무작위로 생성한 가상 데이터예요.

## 구성

| 경로 | 내용 |
|---|---|
| [`skills/target-vs-actual`](skills/target-vs-actual/SKILL.md) | 조직·팀·담당자 단위 목표 대비 실적과 생산성 분석 |
| [`skills/funnel-conversion`](skills/funnel-conversion/SKILL.md) | 퍼널 단계별 전환율, 병목, 정체 딜 찾기 |
| [`skills/forecast-gap-analysis`](skills/forecast-gap-analysis/SKILL.md) | 목표와 전망 차이를 요인별로 분해하고 원인 찾기 |
| [`data-mart/`](data-mart/README.md) | 비분석가와 AI가 쓰기 쉬운 데이터 마트 설계 원칙, 지표 정의 예시 |
| [`sample-data/`](sample-data/) | 바로 실습할 수 있는 가상 데이터 (CSV) |

## 사용 방법

각 스킬은 `SKILL.md` 하나로 되어 있어요. 맨 위 `name`과 `description`으로 언제 쓸지 정하고, 본문에 분석 절차와 출력 형식을 적었어요.

- **Claude Code / Agent Skills**: `skills/` 아래 폴더를 프로젝트의 `.claude/skills/`에 복사하면 질문에 맞는 스킬이 자동으로 쓰여요.
- **다른 AI 도구**: `SKILL.md` 본문을 시스템 프롬프트나 지식베이스에 넣어서 써도 돼요.

### 바로 해보기
1. `sample-data/`의 CSV를 AI 도구에 올려요.
2. 이렇게 물어봐요.
   - "9월 팀별 달성률이랑 갭 알려줘"
   - "퍼널에서 어디가 병목이야? 30일 넘게 멈춘 딜도 뽑아줘"
   - "목표랑 전망 차이를 팀, 담당자 순으로 분해해줘"

## 왜 만들었나요
분석은 **비즈니스 조직이 직접 할 때** 실행으로 이어질 가능성이 가장 크다고 믿어요. 그래서 분석가가 대신 답해주는 대신, 사업 직무가 같은 기준으로 스스로 답을 얻을 수 있는 스킬과 데이터 환경을 만들고 있어요.

## 기여
더 좋은 분석 절차나 새로운 스킬 아이디어가 있다면 Issue나 PR로 알려주세요.

---

## 📢 이런 일을 함께할 Business Analyst를 채용하고 있어요

Revenue Operations Tribe · Business Performance & AX팀에서 **영업 생산성 분석**과 **AI 환경 구축·AX 컨설팅**을 함께할 BA(경력 5년 이상)를 찾아요.

👉 **[JD 보기](https://github.com/hyukjin8251/hiring)** · **[지원하기](https://toss.im/career/job-detail?job_id=6279876003)**
