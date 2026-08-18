# Ensom · docs

기획·계약·카피·UAT 문서 저장소. 코드는 [BE](https://github.com/14thlikelion-centralthon-mju2team/BE), [FE](https://github.com/14thlikelion-centralthon-mju2team/FE)를 참조.

## 브랜치 규칙

- `main`: 승인 완료된 문서만 병합 (release PR과 동일하게 직접 push 금지)
- `dev`: 문서 통합 기준 — `docs/<feature>` 브랜치는 여기서 분기하고 여기로 PR
- `docs/<feature>`: 기획·계약·카피·UAT 문서 각 1건, 구현 인수 조건과 함께 병합

## 문서 목록 (MILESTONE.md §4~8 기준)

| 브랜치 | 담당 | 마일스톤 | 상태 |
|---|---|---|---|
| `docs/product-contract` | 최수민 | M0 | 작성 중 |
| `docs/plan-acceptance-copy` | 최수민 | M1 | 예정 |
| `docs/notification-policy` | 최수민 | M2 | 예정 |
| `docs/wellness-copy-experiment` | 최수민 | M3 | 예정 |
| `docs/release-uat` | 최수민 | M4 | 예정 |

PRD·TRD·API 문서끼리 서로 다르게 적혀있던 부분들(로그인 방식, 알림 조건 개수, 보정 상한값 등)을 하나로 확정한 문서예요. 각자 담당 파트 관련된 부분만 훑어보고 실제 구현이랑 맞는지 확인해서 Approve 눌러주시면 됩니다.
