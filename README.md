# Skills

내려받아 사용할 수 있는 에이전트 스킬 모음입니다.

## service-proposal — 서비스 아이디어 사업성 검토

짧은 서비스 아이디어를 고객·시장 근거, MVP, 수익 가설, 고객 확보 전략, 검증 실험을 포함한 제안서로 구체화합니다. 시간과 돈을 투입할지 판단하는 데 초점을 둡니다.

- 고객·시장 조사 후 PM, 창업가, 투자자, 디자인/기술, 그로스 관점에서 검토합니다.
- 확인된 사실과 미검증 가정을 구분하고 출처를 남깁니다.
- 다음 행동, 투자 범위, 성공·중단 조건이 있는 검증 계획을 제안합니다.
- 실제 개발·출시·광고·고객 연락은 별도 요청으로 다룹니다.

[스킬 본문](service-proposal/SKILL.md) · [역할별 작업 계약](service-proposal/references/agents.md) · [제안서와 검증 계획](service-proposal/references/proposal.md)

## 설치

### Codex에서 요청하기

다음 문장을 Codex에 입력하세요.

```text
$skill-installer https://github.com/sera-lim/skills/tree/main/service-proposal 스킬을 설치해줘.
```

### 직접 내려받기

1. 저장소의 **Code → Download ZIP**으로 내려받거나 `git clone https://github.com/sera-lim/skills.git`을 실행합니다.
2. `service-proposal` 폴더 전체를 개인용 `~/.agents/skills/` 또는 사용할 프로젝트의 `.agents/skills/` 아래에 복사합니다.
3. 최종 경로가 `~/.agents/skills/service-proposal/SKILL.md` 또는 `<프로젝트>/.agents/skills/service-proposal/SKILL.md`인지 확인합니다. 기존 같은 이름의 스킬이 있다면 먼저 백업하세요.
4. 새 스킬이 표시되지 않으면 Codex를 재시작합니다.

`SKILL.md`만 복사하지 말고 `references/`와 `agents/`도 함께 설치하세요.

설치 경로와 호출 방식은 [OpenAI 공식 스킬 문서](https://learn.chatgpt.com/docs/build-skills)를 참고하세요.

## 사용 예시

```text
$service-proposal
혼자 사는 사람을 위한 냉장고 식재료 소진 추천 서비스를 검토해줘.
주말에 혼자 개발할 수 있고, 먼저 소규모 수익 사업으로 검증하고 싶어.
```

아이디어만 입력해도 시작할 수 있습니다. 목표 고객, 해결할 문제, 시간·예산·팀 역량을 알려주면 판단에 도움이 됩니다.

## 실행 환경

- 최신 시장·경쟁 정보 확인에는 웹 검색 또는 연결된 자료 조회 도구가 필요합니다. 접근할 수 없는 자료는 확인 불가로 표시합니다.
- 별도 에이전트 도구가 있으면 독립 검토를 실행하고, 없으면 관점별 순차 검토로 대체합니다.
- Canvas, 커머스 컨텍스트, artifact-magic 관련 문구는 해당 환경에 사용자 지정 규칙이 있을 때 적용하는 조건부 지침입니다. 별도 사내 계정이나 토큰은 포함하지 않습니다. 공유 규칙이 없는 환경에서는 산출물을 로컬로 전달합니다.
