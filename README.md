# 20242R0136COSE37302
서론
최근 대규모 언어 모델의 급속한 발전은 자연어 처리(NLP) 분야에 지대한 영향을 미치고 있습니다. GPT-3와 GPT-4와 같은 모델은 텍스트 생성부터 질의응답, 번역에 이르기까지 다양한 작업에서 놀라운 성능을 보여주고 있습니다. 이러한 모델의 능력을 최대한 활용하기 위해서는 원하는 출력을 도출하도록 입력을 설계하는 프롬프트 엔지니어링이 핵심적인 역할을 합니다.

개별 모델에서 프롬프트 엔지니어링이 효과적임이 입증되었지만, 아직 충분히 탐구되지 않은 중요한 질문이 있습니다: 프롬프트는 다른 언어 모델 간에 얼마나 전이될 수 있는가? 프롬프트의 전이 가능성을 이해하는 것은 여러 면에서 중요합니다. 이는 새로운 모델에 애플리케이션을 적용하는 데 필요한 노력을 줄이고, NLP 시스템의 견고성을 향상시키며, 언어 모델의 일반화 능력에 대한 통찰력을 제공합니다.

본 논문에서는 다양한 사전 학습된 언어 모델 간에 프롬프트의 전이 가능성을 조사합니다. 한 모델에 맞춰 설계된 프롬프트가 다른 모델에 적용되었을 때 어떻게 동작하는지 살펴보고, 그 효과에 영향을 미치는 요인을 식별합니다. 우리는 다양한 크기와 아키텍처의 모델에 초점을 맞춰 포괄적인 분석을 제공합니다. 체계적인 실험을 통해 효과적일 뿐만 아니라 모델 간에도 높은 전이성을 가진 프롬프트를 생성하기 위한 가이드라인을 수립하고자 합니다.

다음의 내용이 포함될 예정입니다.

여러 언어 모델 간의 프롬프트 성능에 대한 심층 분석을 제공합니다.
프롬프트 전이 가능성에 영향을 미치는 주요 특성을 식별합니다.
실무자들이 전이 가능한 프롬프트를 설계하는 데 도움이 되는 가이드라인과 코드를 공개합니다.

