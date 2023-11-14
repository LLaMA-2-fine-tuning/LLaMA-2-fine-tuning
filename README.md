# LLaMA-2-fine-tuning

### 프로젝트 목표

- [ ] 1. vicuna 모델 불러오기 : [vicuna-7b-v1.5](https://huggingface.co/lmsys/vicuna-7b-v1.5)
- [ ] 2. 데이터셋 : huggingface에서 한국어 번역본(****[sharegpt_deepl_ko](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko))** 62 만개 데이터 로딩 (api키 인증)
- [ ] 3. fine-tuning : 62만개 데이터 -> 3만~5만개로 줄이는 epoch 조절 (feat. LoRa)
- [ ] 4. weight 값 저장 코드 필요 (끊기더라도 다시 학습 시킬 수 있도록)
- [ ] 5. 테스트
