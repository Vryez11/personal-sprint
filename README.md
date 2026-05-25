# Personal Sprint

지속적인 성장과 결과물 중심 학습을 위한 개인 스프린트 저장소입니다.

단순히 공부한 내용을 기록하는 것이 아니라,
실제 결과물과 회고를 기반으로 성장 흐름을 추적하는 것을 목표로 합니다.

> **진행 상황은 Notion, 확정 기록은 Git.**
> 실시간 트래킹은 트래커에서, 완료된 목표·결과물·회고는 이 저장소에 남깁니다.

📋 **[Sprint Tracker (Notion)](https://www.notion.so/9798e70ba5ff8236b566815bc4648c8c)**

---

## Sprints

| #    | 기간                | 목표 (한 줄)  | 결과물        | 회고                                 |
|------|-------------------|-----------|---------------|--------------------------------------|
| [01](./sprint-01/) | 2026.05.25 – 05.31 | _기본기 마스터_ | _작성 예정_   | [→](./sprint-01/retrospective.md)    |
| 02   | –                 | –         | –             | –                                    |
| 03   | –                 | –         | –             | –                                    |

> 각 Sprint의 실제 코드/산출물은 별도 Repository에서 관리하고, 여기선 **링크만** 겁니다.

---

## Structure

```text
personal-sprint/
├── README.md            # 이 파일 — 전체 인덱스 (Sprints 표)
└── sprint-NN/
    ├── README.md        # 목표 / 진행 내용 / 결과물·학습 링크
    └── retrospective.md # 회고 (직접 작성)
```

---

## Templates

각 링크는 **집이 하나**입니다. 같은 링크를 두 파일에 중복해서 달지 않습니다.

### `sprint-NN/README.md`

```md
# Sprint NN

기간: YYYY.MM.DD ~ YYYY.MM.DD

## Goals
- 

## Daily Log
하루 한 줄. 결과물은 커밋/PR/repo 링크로. (긴 회고는 retrospective.md에)

| 날짜  | 한 일          | 결과물 |
|-------|----------------|--------|
| MM.DD |                |        |

## Results
스프린트 종료 시, 핵심 산출물만 요약.
- 

## Learned
- 

## Related Links
- GitHub:
- Notion (학습 노트):

> 회고는 [retrospective.md](./retrospective.md) 참고
```

### `sprint-NN/retrospective.md`

```md
# Sprint NN 회고

- 잘한 점:
- 부족했던 점:
- 다음 Sprint 개선 사항:
- 한 줄 정리:
```
