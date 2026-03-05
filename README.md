# claude-skill-set

LLM 에이전트 환경(Claude Code)에서 사용할 스킬을 생성·큐레이션하고, 프로젝트와 분리된 프레임워크 레벨로 관리하기 위한 저장소입니다.

## 구조

```
claude-skill-set/
├── back/v1/          # Java 백엔드 스킬
└── workflow/         # 워크플로우 커맨드 (git 등)
```

## 스킬 목록

### back/v1

| 스킬 | 설명 |
|------|------|
| `api-contract-review` | REST API 설계 감사 |
| `architecture-review` | 프로젝트 아키텍처 분석 |
| `clean-code` | Clean Code 원칙 적용 및 리팩토링 |
| `concurrency-review` | 동시성 코드 검토 |
| `design-patterns` | 디자인 패턴 적용 |
| `java-code-review` | Java 코드 리뷰 |
| `jpa-patterns` | JPA/Hibernate 패턴 및 안티패턴 |
| `logging-patterns` | 로깅 모범 사례 |

### workflow/git

| 커맨드 | 설명 |
|--------|------|
| `commit` | 커밋 메시지 작성 |
| `create-pr` | PR 생성 |

## 라이선스

이 저장소는 [MIT License](LICENSE) 하에 배포됩니다.
외부 출처 스킬은 [CREDITS.md](CREDITS.md)를 참고하세요.
