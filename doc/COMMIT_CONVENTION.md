# Commit Convention

## 커밋 메시지 형식

```
<type> subject

<body>

<footer>
```

---

## Type 종류

| Type | 설명 |
|------|------|
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `docs` | 문서 수정 |
| `style` | 코드 포맷 변경 (기능 변경 없음) |
| `refactor` | 코드 리팩토링 |
| `test` | 테스트 코드 추가 또는 수정 |
| `chore` | 빌드 설정, 패키지 관리 등 기타 변경 |

---

## 규칙

- `subject`는 50자 이내로 작성
- 첫 글자는 소문자로 시작
- 마침표(`.`) 사용 금지
- 명령형 어조 사용 (예: "add feature" not "added feature")
- `body`는 선택 사항이며, 변경 이유와 내용을 설명
- `footer`는 이슈 번호 참조 시 사용 (예: `Closes #123`)
- **커밋 메시지는 한글로 작성**
- **헤더의 type은 `< >` 형식으로 감싸서 표기** (예: `<fix> 긴급Fix`)

---

## 예시

```
<feat> Google OAuth 로그인 기능 추가

사용자가 Google 계정으로 로그인할 수 있도록 OAuth 2.0 연동 추가

Closes #42
```

```
<fix> 긴급Fix
```

```
<docs> README 설정 방법 업데이트
```
