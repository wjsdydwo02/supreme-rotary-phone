# supreme-rotary-phone

## 목표
소설 "이세계 피크닉"에서 묘사된 "깨진"문자의 모습을 GAN을 이용하여 구현하고자 함.

## 필요한 학습 데이터
- 라틴문자(0041-005A, 0061-007A), 숫자(0030-0039)
- 히라가나(3040–309F)
- 가타카나(30A0–30FF)
- CKJ통합 한자(4E00–9FFC +a) *Kanji만을 분리하는 것을 추후 고려할 것* 
- 위 언급된 문자를 지원하며 사용 용도에 맞는 라이센스가 제공되는 폰트(들)  

(가능할경우 한글까지 확장)

## 방법
1) PIL의 Imagefont 라이브러리를 이용, 폰트를 이미지화한다
2) 이미지를 처리하여 학습 데이터셋을 구성한다.
3) Keras를 이용하여 GAN을 만들어 학습시킨다. 

## 참고
- https://www.unicode.org/charts/
- http://jikasei.me/font/genshin/
- 
