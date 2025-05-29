# 전략 (strategy)

이 저장소는 [nb-runner](https://github.com/NeoMatrixAI/nb-runner) 저장소에서 사용하는 전략 모듈과 설정 파일들을 포함하고 있습니다.

---

### 📁 구조

각 전략은 별도의 폴더로 구성되어 있으며 다음 파일들을 포함합니다:
- `strategy_name.py`: 전략의 핵심 로직
- `strategy_name_config.py`: 해당 전략의 설정 파일

예시:

```
strategy/
└── momentum_v1/
├── momentum_v1.py
└── momentum_v1_config.py
```

이 레포지토리는 저희가 개발하고 정기적으로 업데이트하는 전략 및 설정 파일들을 담고 있습니다.  
실행 가능한 노트북이나 API 모듈은 포함되어 있지 않습니다.

하지만 `nb-runner` 환경에서는 여기에 포함된 것뿐 아니라  
사용자 맞춤형 전략과 설정 파일을 자유롭게 사용할 수 있습니다.

---

### 📦 사용 방법

이 저장소의 전략을 사용하려면:
1. 저장소를 클론하거나 최신 버전으로 업데이트하세요.
2. 사용하고 싶은 전략을 선택하세요.
3. 로컬 `nb-runner` 환경에 로드하세요.
4. `strategy_verify_test.ipynb`, `backtest.ipynb`, `trade.ipynb` 같은 노트북을 통해 사용하세요.

반드시 실행 환경인 [nb-runner](https://github.com/NeoMatrixAI/nb-runner) 저장소도 함께 사용해야 합니다.

---

### 🧩 나만의 전략 만들기

초보자도 쉽게 따라 할 수 있는 전략 모듈 및 설정 작성 가이드도 제공합니다.

> 📘 자세한 내용은 [strategy_guide.md](./strategy/README_KOR.md) 참고 –  
> `strategy()` 함수 작성법, 입출력 형식, 필수 구조, 설정 방법 및 예제 코드가 단계별로 설명되어 있습니다.

---

### ❓ 문의 및 지원

질문이나 도움이 필요하신 경우 [**NeoMatrix Discord**](https://discord.gg/n6tMdrse)를 통해 문의해 주세요.
