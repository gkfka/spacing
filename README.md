# 양방향 LSTM-CRF를 이용한 자동띄어쓰기

양방향 LSTM-CRF를 세종말뭉치를 이용하여 학습한다.
세종말뭉치에서 임의로 추출한 문장을 학습과 평가말뭉치로 이용한다.
문장의시작과 끝을 나타내는 $가 포함되며 입력은 3-그램으로 입력의 예는 다음과 같다.


나는 학교에 간다.

3-그램: $나는/B 나는학/I 는학교/B 학교에/I 에간다/B 간다./I .다$/I


