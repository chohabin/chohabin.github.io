---
layout: page
title: 2023 산학협력프로젝트
description: 바이브컴퍼니
img: assets/img/vaiv.png
importance: 1
category: work
related_publications: false
---

> 산학협력프로젝트_하계집중근로 : 바이브컴퍼니
<br>

*(2023년 6월 12일 ~  2023년 8월 20일 )*

:  GPT3 기반 자연스럽고 윤리적인 한국어 기반 일상 대화형 챗봇 모델 구현 

> 프로젝트 세부 개발 내용
>

base model : KULLM 12.8B

□ Task 1: LLM (Large Language Model)학습 데이터셋 구축 

□ Task 2: SFT(Supervised Fine-tuning)

□ Task 3: Reward Model 학습

□ Task 4: RLHF(Reinforcement Learning from Human Feedback)  강화학습

□ Task 5: 최종 모델 성능 평가

> 프로젝트 기여
> 

__데이터셋 구축__

domain이 다양한 고품질의 데이터셋을 확보하는 것이 챚봇을 개발의 핵심이었습니다. 데이터셋 구축하는 과정에서 많은 시행착오를 겪었습니다. 이 과정에서 데이터의 수집, 필터링, 라벨링, 수정 등 다양한 단계를 통해 양질의 학습용 데이터를 구축 및 생성하였습니다.  이는 모델 학습에 있어서 중요한 역할을 하는 데이터 구축 작업에 대한 깊은 이해를 제공하였으며, 앞으로 챗봇 개발 및 기타 인공지능 프로젝트에서 큰 도움이 될 것이라 기대합니다. 

    

    
__성능평가__

LLM(Large Language Model)의 성능 평가 부분을 담당하여 프로젝트를 진행하였습니다.  *G-Eval: NLG Evaluation using GPT-4 with Better Human Alignment* 논문 기반으로 대규모 언어 모델의 성능을 측정하였습니다. 

G-eval은 GPT-4를 이용하여 LLM(Large language Model)의 답변 품질을 평가하는 성능 평가 방법입니다. GPT-4로 평가하기 때문에, 평가를 자동화할 수 있다는 것이 가장 큰 장점입니다.

G-eval 진행 시, GPT-4가 타당한 평가를 할 수 있도록 적절한 Prompt를 작성하는 것이 가장 어려운 부분이었습니다. Prompt에 따라 GPT-4의 성능은 크게 바뀔 수 있다는 점을 유의하였고, G-eval 성능 평가를 한  KULLM팀의 Prompt를 참고하여 작성하였습니다. 

이 성능 평가는 LLM(Large language Model) 성능 평가에 객관적인 지표가 되어주었습니다. G-eval 점수 기반으로 RLHF 강화 학습한 모델의 성능 저하 원인을 분석하여 취약점 파악하였고 추후 학습 계획을 세웠습니다. 

> 프로젝트 소감 및 결론
> 

이 과제를 통해 GPT-3 기반의 일상대화형 챗봇 구현을 목표로 LLM에 대한 다양한 관점과 논문을 접하게 되었습니다. 처음에는 데이터 준비 과정에서 많은 시행착오를 겪으며 고품질 데이터셋을 찾는데 고민이 크게 쏟아졌지만, 여러 차례의 실험을 통해 데이터셋을 개선하고 적합한 데이터를 추출해 넣으며 보다 나은 결과를 위한 기초를 세웠습니다. 과제 진행 중 논문 리뷰를 통해 가장 최신의 연구방향과 GPT-4를 활용한 성능 평가 방법에 대해 배울 수 있었고, 이를 바탕으로 최적의 방향성을 찾아나갔습니다. 

결과적으로, 과정에서 얻은 통찰력과 소중한 경험을 바탕으로 만들어진 최종 모델은 다른 모델들(ex. KULLM, Koalpaca)에 비해 더 자연스럽고 사람답게 대화하는 일상 챗봇임을 확인할 수 있었습니다.

챗봇 개발에 대해 직접 연구하고 실험해볼 수 있는 소중한 경험이었습니다. 또한, 최신 연구 동향을 반영한 모델 개선 방안을 찾고 적용해보는 과정에서 인공지능 분야에 대한 이론적 기초와 실용적 기술을 함양할 수 있었습니다. 이런 경험과 지식은 앞으로 인공지능 분야에서 더 큰 발전을 이루기 위한 원동력이 될 것이라 확신합니다.