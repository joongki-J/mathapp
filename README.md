# mathapp

수학 수업용 웹앱 모음입니다.

| 앱 | 경로 | 내용 |
| --- | --- | --- |
| 퍼셉트론 논리 연산 실험실 | [`perceptron/`](perceptron/) | 인공지능 수학: 퍼셉트론으로 AND·OR·NAND·NOR 만들기, 가중치 학습 규칙, 배타적 논리합(XOR)과 다층 퍼셉트론 |
| 화소별 가중치로 숫자 구분하기 | [`digit-weights/`](digit-weights/) | 인공지능 수학: 3×5 숫자 그림의 칸마다 가중치를 두고 손실함수와 경사하강법으로 분류하기, 가중치 하나에 대한 손실함수 L(w)의 유도, 출력 노드 1개·2개·3개(숫자 1·7·8)와 소프트맥스 판정 |
| 단어별 가중치로 문장 분류하기 | [`word-weights/`](word-weights/) | 인공지능 수학: 문장에 들어 있는 단어마다 가중치를 두고 손실함수와 경사하강법으로 분류하기, 1장 감성 분석(출력 노드 1개), 2장 주제 분류(출력 노드 3개), 가중치 하나에 대한 손실함수 L(w)의 유도 애니메이션 |
| 이한이의 한글 야구장 | [`hangul-baseball/`](hangul-baseball/) | 유아용 한글 놀이: 공격은 글자 공을 골라 타이밍에 맞춰 치고(3스트라이크 삼진, 안타마다 공이 빨라짐), 수비는 글자 공을 골라 슬라이더의 초록 칸에 맞춰 던지는 미니 야구. 모음·자음·가나다·낱말 4단계, 2회부터는 소리만 듣고 찾기, 음성 내장, 글자 쓰기 연습 |

각 앱은 `index.html` 파일 하나로 동작합니다. GitHub Pages를 켜면 `https://joongki-j.github.io/mathapp/perceptron/`, `https://joongki-j.github.io/mathapp/digit-weights/`, `https://joongki-j.github.io/mathapp/hangul-baseball/` 주소로 열 수 있습니다.
