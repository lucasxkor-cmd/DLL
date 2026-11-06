# Drive Tennessee · 한국어 운전 학습

Tennessee Driver License Manual을 한국어로 학습하는 반응형 웹앱입니다.

**GitHub Pages:** https://lucasxkor-cmd.github.io/DLL/

## 주요 기능

- 17개 Chapter와 175개 세부 단원의 핵심 이론
- 영어 용어 유지, 한국어 설명과 222개 원본 그림
- Chapter Sample Test Question 27문항, 채점과 해설
- 자동 오답 노트, 메모, 오답 재풀이와 복습 완료
- 학습 진도, 북마크, 검색, 큰 글자
- 학습 기록 JSON 내보내기와 가져오기

## 실행

GitHub Pages에서 열거나 `index.html`을 브라우저로 직접 열면 됩니다.
HTML에 모든 콘텐츠, 코드, 그림이 포함되어 있으며 외부 라이브러리나 별도 서버가 필요하지 않습니다.

GitHub Pages의 Settings → Pages에서 `Deploy from a branch`, `main`, `/(root)`를 선택하면 배포됩니다.

## 학습 기록

기록은 현재 브라우저의 localStorage에 저장됩니다. 서버로 전송하거나 계정 간 동기화하지 않습니다.
기존 Sites 주소나 다른 기기의 기록은 앱의 **학습 기록 → 기록 내보내기 / 가져오기**로 이전할 수 있습니다.
브라우저 데이터 삭제 전에는 필요한 기록을 내보내세요.

## 자료 기준

제공된 DL_Manual.pdf 판본을 토대로 구성했습니다. 법률, 날짜, 수수료와 처벌 수치는 해당 판본의 기준입니다.
원본 Section B의 27개 예시 시험 문제를 포함하며, Section A와 C에는 원본 예시 문제가 없어 이론 학습을 제공합니다.
