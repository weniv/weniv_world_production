# 상한 당근을 골라내자!

## 상한 당근을 골라내자! `컴프리헨션` `삼항 연산자`

빙키는 파이와 썬의 심복이었으며, 소울곰과 함께 보물을 지키고 있었습니다. 라이캣이 여러 도전을 극복해 나갈 때, 빙키는 알게 모르게 조언을 건넸어요. 라이캣이 보석을 차지하자, 빙키는 이것이 파이와 썬이 남긴 마지막 임무임을 깨달았습니다.

'도끼에 발을 찍혀 다시는 도끼를 사용하지 않겠다는 자, 도끼에 발을 찍혀도 신뢰하고 포용하며 도끼의 능력을 인정하고 곁에 둘 수 있는 자.'

이것은 왕관의 무게와도 같은 것이었습니다. 빙키는 라이캣이 여러 난관을 극복한 이들에게 나누어줄 믿음과 신뢰, 포용력을 지켜보았습니다. 만약 라이캣이 보물을 혼자 차지하려 한다면, 빙키는 그 보물을 회수할 생각이었습니다. 마음을 정리하고 있을 때, 빙키는 라이캣의 부름을 받았습니다. 

> '빙키, 받아라냥! 빙키가 아니었다면 여기까지 오지 못했을 거야냥!'

스톤을 받을 것이라고는 생각지 못했던 빙키는 당황했습니다. 그리고 운명이 이끄는 이 상황이 재미있다고 느꼈습니다. 파이와 썬은 빙키에게 합당한 자가 나올 때까지 보물을 지켜달라 부탁했고, 이제 합당한 자로부터 보물을 다시 받았습니다. 이제 빙키가 합당한 자임을 증명할 때입니다.

![리얼리티 스톤을 가진 빙키](18_1.webp)

* 리얼리티 스톤 : 사람들의 시각을 조작하여 현실과 같은 허상을 만들어낼 수 있음.

빙키는 오랜 시간 떠나있던 고향으로 발걸음을 옮겼습니다. 돌아가는 동안 리얼리티 스톤을 사용할 역량을 키우기 위해 노력했습니다. 또, 이것으로 어떤 힘을 모을지도 고민했습니다.

![](18_2.webp)

고향에 도착한 빙키는 많이 변한 마을을 발견했습니다. 산업화로 인해 옛 동산들은 사라지고, 높은 건물들만 남아 있었습니다.

길가에는 굶주린 토끼들이 쓰러져 있었고, 밭에는 상한 당근들이 널려있었습니다. 높은 건물에는 잘 차려입은 사자와 하이에나들이 들어가고 있었으며, 토끼들은 공사 현장에서 일하고 있었습니다.

"내가 기억하는 마을을 보여주겠어요. 아니, 더 맑은 물이 흐르고, 쉴 수 있는 동산이 있고, 언제든 먹을 수 있는 싱싱한 당근이 있던 마을을 재현하겠어요. 공기는 맑고, 사람들은 나와서 뛰어놀죠. 그러면, 사람들은 자신이 잃어버렸던 것이 얼마나 귀한지 알 것입니다. 되돌아보고, 결심하여 삽이 아니라 철퇴를 들도록 하겠습니다."

### 임무
주어진 리스트에서 신선도가 떨어진 당근과 당근이 아닌 것들을 제외하고, 당근만을 선별하여 터미널에 출력하세요. 리스트는 각 항목별로 ['항목 이름', 신선도 점수]의 형태로 구성되어 있습니다. 신선도 점수가 5 이상인 '당근'만을 선택해야 합니다. 이 임무는 리스트 컴프리헨션과 삼항 연산자를 사용하여 해결할 수 있습니다.

### 기본 데이터
```python
items = [['당근', 3], ['사과', 5], ['당근', 6], ['포도', 4], ['당근', 7]]
```

### 결과값
```python
['당근', 6], ['당근', 7]
```

## 사용 코드
아래 제시된 코드를 활용하여 문제를 해결해 주세요.

```python
result = [item for item in items]
result = 'hello' if True else 'world'
if item[0] == '당근' and item[1] >= 5
```