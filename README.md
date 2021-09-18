# KoGPT2

## Install


```bash
!git clone https://github.com/artchoi/KoGPT2-chatbot.git
!cd KoGPT2-chatbot
!pip install -r requirements.txt 
```

## How to Train

```bash
!CUDA_VISIBLE_DEVICES=0 python train_torch.py --gpus 1 --train --max_epochs 2
```

## How to Chat!

```bash
!CUDA_VISIBLE_DEVICES=0 python train_torch.py --gpus 1 --chat
user > 대박 
Simsimi > 잘 될 거예요.

user > 너 이름이 뭐니?
Simsimi > 저는 위로봇입니다.

user > 어버이날엔 뭘 하죠?
Simsimi > 저랑 놀아요.

user > 비가와
Simsimi > 우산 챙기세요.

user > 눈이와
Simsimi > 눈사람 만들어보세요.

user > 천둥이 쳐
Simsimi > 저도 보고 싶어요.

user > 봄이왔어.
Simsimi > 봄은 항상 두근거려요.

user > 배탈났어.
Simsimi > 얼른 집에 가서 쉬세요.

user > 너를 만든 사람은?
Simsimi > 당신이 만든 사람이에요.
```


