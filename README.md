Why Explore? 
- mlflow의 한계
    - langgraph등의 새로운 framework와의 통합이 부족
    - ml project와는 다른 특성
    - 더 많은 model 지원할 필요성 !
- GAI 발표를 들으면서 더욱 필요성을 느낌
- 앞으로 분명 AI 프로젝트가 매우~ 많아질 것

LLMOps의 역할 
- 모델 배포 및 유지 관리: 클라우드 플랫폼 또는 온프레미스 인프라에 LLM 배포 및 관리
- 데이터 관리: 학습 데이터 준비 및 품질 유지
- 모델 학습 및 미세 조정: 특정 작업에서 성능을 향상시키기 위해 LLM 학습 및 조정
- 모니터링 및 평가: LLM 성능 추적, 오류 식별 및 모델 최적화
- 보안 및 규정 준수: LLM 운영의 보안 및 규정 준수 보장

LLMOps와 MLOps 차이점
- LLMOps는 MLOps의 하위 집합으로, LLM 관리에 특화된 문제와 요구 사항을 다룸.
- MLOps는 일반적인 머신러닝 모델 관리를 다루는 반면, LLMOps는 LLM의 큰 크기, 복잡한 학습 요구 사항 및 높은 계산 요구를 다룸.

LLMOps 작동 방식
- 데이터 수집 및 준비: LLM 학습을 위한 대규모 데이터 수집 및 준비
- 모델 개발: 비지도 학습, 지도 학습, 강화 학습 등의 방법으로 LLM 개발
- 모델 배포: LLM을 실제 환경에 배포하고 필요한 인프라 설정
- 모델 관리: 성능 모니터링, 재학습, 보안 유지


Langsmith vs Langtrace vs Langfuse 
![스크린샷 2024-09-25 오후 3 32 49](https://github.com/user-attachments/assets/e0080ba9-ba4a-4dec-a379-5cea708932ab)


오픈소스에 k8s 배포가 쉬워보여서 langfuse 선택  


Reference 
* https://cloud.google.com/discover/what-is-llmops 
