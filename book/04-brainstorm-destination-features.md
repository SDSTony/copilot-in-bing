# 연습4: 목적지 특징들에 대한 브레인스토밍

원본: https://learn.microsoft.com/ko-kr/training/modules/explore-generative-ai-copilot-bing/5-exercise-brainstorm-destination-features

## 첫번째 프롬프트 예시

```
이제 프로젝트의 '특징' 부분을 작업할 예정입니다.
이 목적지에 대해 알고 있는 내용을 바탕으로, 사람들이 방문하거나 시간을 보내거나 즐길 수 있는 독특한 실내 또는 실외 특징이나 공간 5가지를 제안해 주시겠어요? 이름과 설명을 다음 형식에 따라 나열해 주세요:

## 이름 ## 
설명
```

## Microsoft Copilot 답변 예시
```
물론입니다! 이 목적지의 독특한 실내 및 실외 공간을 다음과 같이 제안해 드립니다:

## 1. 숲속 도서관 ##
설명: 나무로 만든 책장과 편안한 의자가 배치된 숲속 도서관입니다. 자연의 소리와 함께 독서를 즐길 수 있는 이 공간은, 방문객들에게 평화롭고 조용한 시간을 제공합니다. 창문을 통해 들어오는 자연광이 따뜻한 분위기를 더해줍니다.

## 2. 고공 다이닝 ##
설명: 나무 가지 위에 지어진 고공 레스토랑으로, 숲의 전경을 한눈에 내려다볼 수 있습니다. 자연과 어우러진 인테리어와 신선한 재료로 만든 요리가 특징입니다. 저녁에는 별빛 아래에서 로맨틱한 식사를 즐길 수 있습니다.

## 3. 비밀의 정원 ##
설명: 숲속 깊은 곳에 위치한 비밀의 정원입니다. 다양한 꽃과 식물들이 가득한 이 정원은, 방문객들에게 자연의 아름다움을 감상하며 산책할 수 있는 기회를 제공합니다. 곳곳에 놓인 벤치에서 휴식을 취할 수 있습니다.

## 4. 자연 스파 ##
설명: 숲속에 위치한 자연 스파로, 나무와 돌로 만든 욕조에서 온천을 즐길 수 있습니다. 자연의 소리와 함께 몸과 마음을 힐링할 수 있는 이 공간은, 방문객들에게 특별한 휴식을 제공합니다. 아로마 테라피와 마사지 서비스도 이용할 수 있습니다.

## 5. 숲속 극장 ##
설명: 나무로 만든 무대와 좌석이 있는 숲속 극장입니다. 자연을 배경으로 다양한 공연과 영화 상영이 이루어지며, 방문객들은 자연 속에서 문화와 예술을 즐길 수 있습니다. 밤에는 별빛 아래에서 특별한 공연을 감상할 수 있습니다.

이 다섯 가지 공간은 방문객들에게 다양한 경험을 제공하며, 이 목적지의 독특한 매력을 한층 더 돋보이게 할 것입니다. 어떤 공간이 가장 마음에 드시나요? 😊
```

## 두번째 프롬프트 예시
```
그 중 몇 가지 아이디어를 시각화하는 작업을 하고 싶습니다. 네 번째 아이디어인 자연 스파에 대해 먼저 작업해보고자 합니다. 자연 스파에 대한 설명을 여행 출판물의 어조로 다시 작성해 주시고, 텍스트 길이는 비슷하게 유지해 주세요.
또한 자연 스파를 대체 할 수 있는 이름 세 가지를 제안해 주시겠어요?
```

## Microsoft Copilot 답변 예시
```
자연 스파 설명

숲속 깊은 곳에 위치한 자연 스파는 진정한 힐링의 오아시스입니다. 나무와 돌로 만든 욕조에서 온천을 즐기며, 자연의 소리와 함께 몸과 마음을 치유할 수 있습니다. 이곳에서는 아로마 테라피와 마사지 서비스도 제공되어, 방문객들에게 특별한 휴식을 선사합니다. 자연의 품에서 느끼는 따뜻한 온천수와 향기로운 아로마는 일상의 피로를 말끔히 씻어줍니다. 자연 스파에서의 시간은 마치 자연과 하나가 되는 마법 같은 경험을 선사합니다.

자연 스파 대체 이름 제안

1. 에코 리트리트
2. 포레스트 온천
3. 힐링 하이브

이 설명과 이름들이 마음에 드시나요? 추가로 더 필요한 부분이 있으면 언제든지 말씀해 주세요! 😊
```

## 세번째 프롬프트 예시
```
포레스트 온천 이름이 마음에 듭니다. 위 설명을 바탕으로 포레스트 온천을 시각화한 이미지를 만들어 주세요.
```

## Microsoft Copilot 답변 예시
![](img03.jpeg)

## 핵심 개념 복습

- 얻고자 하는 결과물의 형식을 프롬프트에 미리 제시함으로써 생성되는 결과물의 형식을 조절할 수 있음 

- 브레인스토밍을 할 때 Micrsoft Copilot이 유용함: `~ 특징이나 공간 5가지를 제안 ~`

- 지속적인 대화를 통해 아이디어 확장이 가능: `네 번째 아이디어인 ~ 먼저 작업 ~`

- 하나의 프롬프트에 여러 개의 작업을 동시에 요구해도 Microsoft Copilot은 각각의 작업별 필요한 내용들을 식별하여 순차적으로 작업 실시 (단, 상황에 따라서는 작업을 분할해서 제공하는 것이 결과물의 정확도 및 품질이 좋은 경우가 있음)