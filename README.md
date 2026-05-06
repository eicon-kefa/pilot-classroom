# pilot-classroom

## 오늘의 목표

오늘은 AI Agent를 활용해서 간단한 웹페이지를 만들고, GitHub에 저장해보는 연습을 합니다.

오늘의 핵심은 완벽한 앱을 만드는 것이 아니라,

> AI에게 시켜서 가져오고, 만들고, 저장해보기

입니다.

---

## 오늘 사용할 도구

- **Slack**: 질문하고 소통하는 곳
- **GitHub Classroom**: 우리 팀의 코드 저장소를 받는 곳
- **GitHub**: 코드를 저장하는 곳
- **VSCode**: 코드를 열고 실행하는 곳
- **AI Agent**: 코딩을 도와주는 AI

---

## 오늘 할 일

### 1. Slack에서 인사하기

이름을 보기좋게 한글로 재설정하고(예. 홍길동),

Slack의 `#all-수다방`에 들어가서 간단히 인사해주세요.

가능하면 오늘 만든 이모지도 공유해보세요.

1) 이름 설정하기
2) #all-수다방 들어가기
3) makeemoji.com에서 이모지 만들기
4) Slack에 올리기
5) 다른 팀 이모지에 리액션 달기

---

### 2. GitHub Classroom 링크 접속하기

아래 GitHub Classroom 링크를 클릭합니다.

https://classroom.github.com/a/swbwxFBO

그다음 본인의 GitHub 계정으로 로그인합니다.

---

### 3. 우리 팀 선택하기

1) 본인의 팀명을 확인합니다.
2) (지원 학생) 10210, 10209, 10214, 20216 학생은 “Create a new team”을 선택하고 아래와 같이 팀명을 입력합니다.
예시:

```text
team-01
team-02
team-03
```
3) 팀원은 “Join an existing team”을 선택하고 우리 팀명을 찾아 참여합니다.
4) 팀 참여가 완료되면 우리 팀 repository가 자동으로 생성됩니다.

---

### 4. 팀 Repository 열기

팀 선택이 끝나면 우리 팀의 repository가 생성됩니다.

repository는 우리 팀의 코드 저장소입니다.

---

### 5. Repository 주소 복사하기

GitHub repository 화면에서 다음 순서로 진행합니다.

1. 초록색 **Code** 버튼 클릭
2. **HTTPS** 선택
3. 주소 복사

---

### 6. VSCode에서 AI Agent에게 요청하기

VSCode를 열고, Github에 로그인합니다.

그 다음, 우측의 AI Agent에게 아래 문장을 그대로 입력합니다.

```text
나는 GitHub Classroom 팀 repository를 내 컴퓨터로 가져오고 싶어.

아래 repository URL을 사용해서 clone해줘.
그리고 폴더를 열어줘.

repository URL:
[여기에 GitHub에서 복사한 URL 붙여넣기]

오류가 나면 내가 쉽게 이해할 수 있게 설명해줘.
```

---

### 7. Agent로 30초만에 html 간단 웹앱 만들기

repository가 열리면 Agent를 활용해 각자 자기 파일을 새로 만듭니다.

파일명은 아래 규칙을 사용합니다.

```text
team번호-이름.html

예시: team-01-sumin.html
```

프롬프트:
```text
새 HTML 파일을 만들어줘.

파일명은 team01-myname.html 이야.

조건:
- 제목은 "My First e-ICON Web App"
- 버튼 하나를 만들어줘
- 버튼을 누르면 배경색이 바뀌게 해줘
- HTML, CSS, JavaScript를 하나의 HTML 파일 안에 넣어줘
- 초보자가 이해할 수 있게 코드에 짧은 주석을 달아줘

주의:
- example.html은 수정하지 마.
- 다른 파일도 수정하지 마.
- 새 파일만 만들어줘.
```
---

### 8. 웹페이지 실행해보기

파일을 저장한 뒤, 브라우저에서 열어봅니다.

```text
내가 만든 HTML 파일을 브라우저에서 열어줘.

가능하면 기본 브라우저에서 열어줘.
만약 직접 열 수 없다면, 내가 어떤 버튼을 눌러야 하는지 단계별로 알려줘.
```

확인할 것:

- 제목이 보이나요?
- 버튼이 보이나요?
- 버튼을 누르면 배경색이 바뀌나요?

---

### 9. GitHub에 저장하기

AI Agent에게 아래 문장을 그대로 입력합니다.

```text
지금 수정한 파일을 GitHub에 저장하고 싶어.

다음 작업을 해줘:
1. 변경된 파일 확인
2. commit 만들기
3. GitHub에 push하기

commit message는 "Create first e-ICON web page"로 해줘.
오류가 나면 내가 이해하기 쉽게 설명해줘.
```

---

## 오늘 꼭 기억할 말

```text
Clone = GitHub 코드를 내 컴퓨터로 가져오기
Commit = 저장 기록 만들기
Push = GitHub에 올리기
```

---

## 문제가 생기면

문제가 생기면 Slack의 `#help` 채널에 질문해주세요.

질문할 때는 아래 형식으로 작성합니다.

```text
팀명:
어디에서 막혔는지:
화면에 나온 오류:
```

예시:

```text
팀명: team-01
어디에서 막혔는지: VSCode에서 repository를 가져오는 단계
화면에 나온 오류: authentication failed
```

---

## 오늘 성공 기준

오늘은 아래 3가지를 완료하면 성공입니다.

- Slack에 메시지 남기기
- GitHub Classroom 팀 repository 들어가기
- AI Agent로 `html` 파일 생성하고 GitHub에 저장하기

---

## 다음 시간 예고

다음 시간에는 SDGs 3, 건강과 웰빙 문제를 바탕으로 팀별 작은 웹앱 아이디어를 만들고, AI Agent를 활용해 더 발전시켜볼 예정입니다.
