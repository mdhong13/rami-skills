---
name: product-hero-image
description: 내 상품 실물 사진과 사람 모델이 한 장에 함께 나오는 대표 이미지(쇼핑라이브 썸네일, 상세페이지 첫 장, SNS 사진)를 이미지 AI로 만듭니다. 상품은 실물과 똑같이, 이미지 안에 글자는 넣지 않습니다. 트리거 — "대표 이미지 만들어 줘", "썸네일 사진", "모델이 상품 든 사진", "상세페이지 첫 장 사진", "상품이랑 사람 같이 나오는 사진", "라이브 커버 이미지".
---

# 상품 대표 이미지 — 모델과 내 상품을 한 장에

## 무엇을 하나

- 사람 모델 한 명과 **내 상품 실물**이 함께 나오는 사진을 만듭니다.
- 쓰는 곳: 쇼핑라이브 썸네일, 상세페이지 맨 위 첫 장, 인스타그램 같은 SNS 게시물.
- 그리는 도구는 학생 본인의 이미지 AI입니다. claude.ai 에 Higgsfield 커넥터를 붙였다면 Claude가 그 안의 모델(Nano Banana Pro, Seedream 5.0, GPT-Image 2.5 등)로 그립니다. ChatGPT 이미지 생성도 같은 방식으로 씁니다.
- 이미지 안에는 **글자를 넣지 않습니다.** 가격, 문구, 배지는 나중에 디자인 도구에서 얹습니다.

## 준비물

| 준비물 | 설명 |
|---|---|
| 상품 실물 사진 1장 | 글자, 로고 스티커, 다른 물건이 없는 깨끗한 사진. 정면보다 비스듬한 3/4 각도가 좋습니다. 흰 배경이면 더 좋습니다 |
| 상품 정보 | 색, 모양, 크기(cm), 꼭 보여야 할 부분(예: 손잡이, 뚜껑, 밑창) |
| 모델 | 둘 중 하나: ① AI가 새로 만든 가상 인물 ② 내가 쓸 권리가 있는 얼굴 사진(본인, 동의서를 받은 모델) |
| 가입 | claude.ai + Higgsfield 커넥터 연결, 또는 ChatGPT 유료 플랜 |
| 돈 | 이미지 AI는 장마다 크레딧이 듭니다. 한 장면에 후보 2~4장을 뽑는다고 생각하고 크레딧을 준비합니다 |

## 첫 한마디 예시

> 이 텀블러 사진으로 쇼핑라이브 대표 이미지 만들어 줘. 20대 여성 모델이 카메라 보고 웃으면서 텀블러를 가리키는 장면, 밝은 주방 배경, 세로로.

> 운동화 상세페이지 첫 장 사진. 모델은 AI 가상 인물로, 신발은 선반 위에 한 켤레.

사진은 꼭 같이 붙여 주세요. 사진 없이 글로만 설명하면 상품이 실물과 다르게 나옵니다.

## 절차

1. **사진 받기.** Claude가 상품 사진을 보고 색, 모양, 눈에 띄는 부분을 글로 정리해 학생에게 보여 줍니다. 틀린 곳이 있으면 학생이 고칩니다.
2. **크기와 용도 정하기.**

   | 용도 | 비율 |
   |---|---|
   | 쇼핑라이브 썸네일, 세로 영상 커버 | 9:16 세로(720×1280 정도) |
   | 상세페이지 첫 장 | 4:5 또는 1:1 |
   | SNS 피드 | 4:5 또는 1:1 |

3. **장면 정하기.** 장면은 한 번에 하나. 처음엔 아래 «기본 장면»으로 시작합니다.
4. **지시문 쓰기.** 아래 «지시문 짜는 법» 순서로 Claude가 영어 지시문을 쓰고 한국어 뜻과 함께 보여 줍니다.
5. **크레딧 확인.** Claude가 쓸 모델, 뽑을 장 수, 들 크레딧을 먼저 알려 주고 **학생이 «좋아»라고 할 때까지 기다립니다.**
6. **생성.** 상품 사진을 참조 이미지로 넣고 후보 2장을 뽑습니다.
7. **판정.** 아래 점검표로 한 장씩 봅니다. 확대해서 손, 상품 가장자리, 옷을 봅니다.
8. **고치기.** 틀린 것이 있으면 «자주 망가지는 것» 표에서 원인을 찾아 **문장 하나만** 바꾸고 다시 뽑습니다. 여러 개를 한꺼번에 바꾸면 무엇이 고쳤는지 모릅니다.
9. **마무리.** 통과한 한 장을 내려받습니다. 글자와 가격은 디자인 도구(미리캔버스, 캔바 등)에서 얹습니다.

### 기본 장면 두 가지

| 장면 | 모습 |
|---|---|
| 소개 | 상품은 가슴 높이 선반이나 테이블 위. 모델은 옆에 서서 빈손을 펴서 상품 쪽을 가리키고 카메라를 보며 웃습니다 |
| 가리키기 | 상품은 화면 한쪽 절반에 통째로. 모델은 다른 절반에서 손가락으로 상품을 가리키고 다른 팔은 옆으로 내립니다 |

- 처음엔 **상품을 손에 쥐지 않는 장면**을 권합니다. 손에 쥐면 AI가 상품 모양을 바꾸거나 손가락이 엉키는 일이 많습니다.
- 들고 있는 장면이 꼭 필요하면 작은 상품만, 두 손으로 가슴 높이에서 카메라 쪽으로 살짝 기울여 듭니다.
- 구도는 **가슴 위**가 기본입니다. 전신으로 가면 얼굴과 상품이 작아져 썸네일에서 안 보입니다.

## 지시문 짜는 법

다섯 덩어리를 이 순서로 씁니다. 영어로 쓰면 대부분의 이미지 AI가 더 잘 따릅니다.

| 순서 | 덩어리 | 적는 것 |
|---|---|---|
| 1 | 참조 안내 | 몇 번째 이미지가 상품인지(얼굴 사진도 넣었다면 그것이 몇 번째인지) |
| 2 | 상품 | 정확한 모양, 색, 크기, 꼭 보일 부분 + «똑같이 유지, 다시 디자인하지 말 것» |
| 3 | 사람과 동작 | 몇 명, 나이대, 옷, 손 위치, 시선, 표정 |
| 4 | 구도 | 가슴 위, 상품 위치(왼쪽 절반 등), 세로 비율 |
| 5 | 배경과 빛, 마무리 | 깨끗한 배경, 밝은 스튜디오 조명, 실사, 선명, 글자 없음, 위쪽 여백 |

### 예시 한 벌 (텀블러, 소개 장면)

```
The reference image is the product: the EXACT matte sage-green stainless steel
tumbler with a clear flip lid and a silver handle on one side, about 9 cm wide
and 20 cm tall. Keep its shape, color and proportions identical. Do not redesign it.
No logo or text on it.

Exactly one woman in her late 20s with a natural, friendly face, wearing a plain
cream knit sweater. The tumbler stands on a light wood shelf at chest height,
right beside her face. Her open hand is raised beside the shelf, palm facing the
tumbler, fingers pointing toward it, a little away from it. Both of her hands are
empty. She looks straight at the camera with a bright smile.

Close-up photo from the chest up: her face is large in the frame and the whole
tumbler is fully visible, top to bottom. Vertical 9:16.

Bright clean kitchen studio, soft warm-white wall, soft-box studio lighting,
photorealistic commercial photograph, real skin texture, sharp focus.
All clothing is plain solid fabric with no printed letters, numbers or logos.
Exactly one tumbler appears in the whole picture. No text anywhere.
Breathing room at the top.
```

### 잘 듣게 쓰는 요령

- **긍정문으로 씁니다.** «만지지 마»보다 «손은 상품에서 조금 떨어져 있다»가 잘 먹힙니다. 부정어는 오히려 그 낱말 쪽으로 끌려갑니다.
- **숫자를 박습니다.** «Exactly one woman», «Exactly one tumbler». 사람이나 상품이 둘로 늘어나는 걸 막습니다.
- **실루엣을 비유로.** 낮고 넓은 상품은 «low, wide, flat … much wider than it is tall»처럼 생김새를 직접 적습니다.
- **글자 옷 낱말은 쓰지 않습니다.** varsity, college, logo tee 같은 말은 옷에 글자를 불러옵니다.
- **한 바퀴에 한 문장만 바꿉니다.** 그래야 무엇이 효과가 있었는지 압니다.

## 결과 판정 점검표

한 장씩, 확대해서 봅니다. 하나라도 걸리면 탈락입니다.

| # | 볼 것 | 통과 |
|---|---|---|
| 1 | 사람 수 | 모델 한 명뿐 |
| 2 | 상품 모양 | 실물 사진과 나란히 놓고 봤을 때 모양, 색, 비율이 같음. 없는 무늬, 점, 구멍, 손잡이 없음 |
| 3 | 상품 개수 | 상품이 하나(신발은 한 켤레) |
| 4 | 상품 잘림 | 위, 아래, 좌우 다 화면 안 |
| 5 | 상품 크기 | 사람과 비교해 실물 크기만 함(텀블러가 얼굴보다 크면 탈락) |
| 6 | 손 | 손가락 수 정상, 엉킴 없음, 가리키는 손끝이 상품에 붙지 않음 |
| 7 | 얼굴 | 정면 또는 거의 정면, 화면에서 충분히 큼, 머리 위가 안 잘림 |
| 8 | 글자 | 옷, 가구, 벽, 상품 어디에도 지어낸 글자, 숫자, 로고 없음 |
| 9 | 썸네일 크기에서 | 작게 줄여 봐도 상품이 뭔지 한눈에 보임 |
| 10 | 위쪽 여백 | 나중에 제목 글자를 얹을 빈 공간이 있음 |

- 후보가 둘 다 탈락하면 원인을 하나 골라 고친 뒤 2장 더 뽑습니다.
- 사람이 예쁜 컷보다 **상품이 맞는 컷**을 고릅니다. 상품이 틀리면 쓸 수 없습니다.

## 자주 망가지는 것과 고치는 말

| 증상 | 지시문에 이렇게 바꿉니다 |
|---|---|
| 얼굴이 작다, 전신으로 나왔다 | 바닥, 마루, 화분 같은 낱말을 빼고 끝에 «Close-up photo from the chest up: her face is large in the frame and the product sits right beside her face; her legs and the floor are out of the frame.» |
| 상품이 다시 디자인됐다 | 상품 문장을 실물과 대조해 낱낱이 다시 씀(색, 모양, 부속 위치) + «Keep it identical» |
| 없는 무늬, 결이 생겼다 | 글로는 잘 안 고쳐집니다. 그 결이 크게 보이는 실물 사진으로 참조를 바꿉니다 |
| 참조 사진 속 다른 물건(테이블, 가방)까지 베꼈다 | 배경을 지운 흰 바탕 상품 사진으로 참조를 바꿉니다 |
| 모델이 둘 나왔다 | «Exactly one woman appears in the picture.» |
| 상품이 하나 더 생겼다(특히 손바닥 위) | 손을 선반 옆에 세워 상품 쪽을 가리키게 + «Exactly one … appears in the whole picture» |
| 가리키는데 다른 손이 상품에 얹혔다 | «Her other arm hangs down at her side.» |
| 손끝이 상품에 닿았다 | «The product fills the LEFT half, she is on the RIGHT half; her fingertip points at it in the air, a little away from it.» |
| 신발을 신어 버렸다 | 신발을 가슴 높이 선반 위에 + «Chest-up framing, legs and feet out of the frame» |
| 신발이 한 짝만 | «one pair placed side by side» |
| 꼭 보여야 할 부분이 안 보인다 | 그 부분이 보이는 각도를 직접: «seen from slightly above, the lid clearly visible» |
| 여러 색이 섞였다 | 셀러 사진에 여러 색이 있으면 한 색만 잘라 참조로 씁니다 |
| 옷, 가구에 글자가 생겼다 | «All clothing is plain solid fabric with no printed letters, numbers or logos.» «plain shelf with no labels or stickers» |
| 눈금, 화면에 엉터리 숫자 | «plain dial, no numbers» |
| 옆얼굴, 어두운 얼굴 | «face fully frontal», «bright soft lighting» |
| 같은 지시문인데 매번 구도가 다르다 | 정상입니다. 비교할 때는 문장 하나만 바꿔 여러 장 봅니다 |
| 세 번 고쳐도 같은 문제 | 다른 이미지 모델로 같은 지시문을 넣어 봅니다. 그래도 안 되면 그 부품을 장면에서 뺍니다 |

## 지키는 것

- **얼굴 권리.** 연예인, 인플루언서, 지인 등 실제 사람의 얼굴은 동의 없이 쓰지 않습니다. 본인 얼굴, 동의서를 받은 모델, 또는 AI가 만든 가상 인물만 씁니다. «○○ 닮은 사람»처럼 실존 인물을 흉내 내는 지시도 하지 않습니다.
- **가짜 표시 금지.** 인증 마크, 수상 배지, «1위» 같은 문구, 남의 브랜드 로고를 이미지에 그려 넣지 않습니다. 이미지 안 글자는 0이 기본입니다.
- **실물과 같게.** 대표 이미지는 손님이 «이걸 받는다»고 믿는 사진입니다. 실물에 없는 기능, 색, 부속을 그리지 않습니다.
- **효능 장면 조심.** 건강, 의학 효과를 단정하는 장면(예: 붙이자 통증이 사라지는 모습)은 만들지 않습니다. 영유아 상품은 안전 수칙에 어긋나는 장면(아기 혼자 높은 곳 등)을 만들지 않습니다.
- **돈은 먼저 묻습니다.** Claude는 생성 전에 쓸 모델, 장 수, 들 크레딧을 보여 주고 학생의 «좋아»를 받은 뒤에만 생성합니다. 다시 뽑을 때도 매번 묻습니다.
- **AI 표시.** 판매 채널에 AI 생성 이미지 표시 규칙이 있으면 따릅니다.
