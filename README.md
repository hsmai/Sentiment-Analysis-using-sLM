# Sentiment-Analysis-using-sLM

NSMC(네이버 영화 리뷰 감성분석 데이터셋)에 대해 llama-3.2-Korean-Bllossom-3B 모델을 LoRA fine tuning하여 데이터셋에 대한 성능을 확인합니다.

[BaseLine]
- IMDB 데이터셋
- 3B 한국어 Llama3.2 모델 (Bllossom)
- 한국어 프롬프트
- 토큰 확률 기반 분류
- zero-shot prompt

---

## 주요 실습 주제

- NSMC에 대해 Fine-tuning
- 다양한 LoRA 설정으로 실험
- Few-shot prompt 적용
- Reasoning 데이터셋 생성 및 학습

---

## 사용 환경

- Python 3.8+
- 필수 라이브러리:  
  `torch`, `sklearn`, `numpy`, `matplotlib`, `pandas`, `scipy` 등

노트북은 [Google Colab](https://colab.research.google.com/) 또는 로컬 Jupyter 환경에서 실행 가능합니다.

---

## 1. 






1. NSMC(네이버 영화 리뷰 감성분석 데이터셋)에 대해 fine-tuning 수행
2. LoRA 설정을 바꿔서 성능 테스트
3. Few-shot 프롬프트 적용
4. Reasoning 데이터셋 생성 및 학습



학습을 전혀 하지 않은 Baseline 모델 결과
r=4로 fine-tuning한 결과
다른 r값으로 fine-tuning한 결과
Few-shot 프롬프트를 적용한 결과(r값은 위의 2,3 둘 중 하나에 해당하면 됨)
Reasoning 데이터셋 생성 결과
Reasoning 데이터셋으로 fine-tuning한 모델 결과
