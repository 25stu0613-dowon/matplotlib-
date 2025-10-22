# matplotlib-
# Matplotlib 가이드북

## 1. Matplotlib란?

Matplotlib은 파이썬에서 데이터 시각화를 위해 가장 널리 사용되는 라이브러리 중 하나로, 다양한 그래프와 차트를 그릴 수 있는 기능을 제공합니다.

## 2. 설치 방법

```bash
pip install matplotlib
```

## 3. 기본 사용 예시

```python
import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [1, 4, 9])
plt.title("기본 선 그래프")
plt.show()
```

## 4. 주요 기능

* 선 그래프(Line Plot)
* 산점도(Scatter Plot)
* 막대 그래프(Bar Chart)
* 히스토그램(Histogram)
* 파이 차트(Pie Chart)

## 5. pyplot vs 객체 지향 방식

Matplotlib은 간단한 경우에는 pyplot 방식, 복잡한 경우에는 객체 지향 방식으로 그래프를 그릴 수 있습니다.

## 6. 그래프 꾸미기 옵션

* `title()`: 그래프 제목 추가
* `xlabel()`, `ylabel()`: 축 이름
* `legend()`: 범례 표시
* `grid()`: 격자 표시

## 7. 예제 확장 예정

추가 예시, 스타일 적용, 3D 플롯 등 다음 섹션에서 이어집니다.
