# 라이캣의 마음, 생선 잡기

## 라이캣의 마음, 생선 잡기 `내장 함수` `정렬`

고향에 돌아온 라이캣은 그동안 (주)캣네 생선의 도움으로 많은 변화를 겪은 동네를 둘러보았습니다. 풍족해진 마을에도 빛과 그림자가 공존하고 있었습니다. 어떤 것을 어떻게, 어디서부터 개선해야 할지 정리가 필요했습니다.

![물고기를 나눠주고 떠나는 라이캣](./17.webp)

라이캣은 길이 없는 산 중턱, 바다가 보이는 곳에 오두막을 지었습니다. 손수 배를 만들고, 집에 들러 가지고 있던 그물과 낚시대를 가져왔습니다. 새벽마다 고기를 잡고 그늘진 곳에 누워있는 그들에 앞에 조용히 고기를 나눠주고 사라지는 일상이 반복되었습니다.

고기를 한 마리 건져 올릴 때마다 자신이 얼마나 작은지, 또 이 작은 자신이 얼마나 큰 일을 할 수 있는지 생각했습니다. 할 수 있는 것과 할 수 없는 것을 분별하고 처음 마음먹었던 마음이 아직도 그 모습 그대로인지 점검했습니다. 또한, 얼마나 험난한 일들이 앞에 있을지를 예상해보고 어떤 자세로 그 일을 마주해야 할지 생각해보았습니다.

'중요한 일을 중요하게, 중요하지 않은 일은 그렇지 않게. 할 수 있는 일에 열을 올리고, 할 수 없는 일에 미련을 두지 않게. 개개인의 마음을 마음을 헤아리면서도 냉철한 상황 판단력도 필요하다냥. 이곳에서 리더의 마음을 먼저 다지겠다냥.'

라이캣의 손목에는 피스 스톤이 빛나고 있었습니다.

라이캣은 그동안에 여정을 돌아봤습니다. 그리고 똑같은 상황에서 더 지혜롭게 대처할 수 있는 방안이 있었는지를 돌아봤어요. 복기할 때마다, 부끄러웠던 순간들을 마주하고 자신의 모습을 더욱 침착하게 돌아볼 수 있었습니다. 또한, 기억 속 함께해준 동료들의 모습도 유심히 살폈습니다.

고기를 많이 잡았지만, 식사하거나 나눠줄 고기를 제외하고는 모두 놓아주었습니다. 라이캣이 진정으로 잡으려 했던 것은 고기가 아니었으니까요.

### 임무
맵에 있는 모든 고기를 잡고 가장 많이 잡은 고기 순서대로 정렬하여 아래와 같이 터미널에 출력하세요. `fish-1`을 가장 많이 잡았기 때문에 가장 앞에 있는 것입니다.

```python
[('fish-1', 7), ('fish-3', 5), ('fish-2', 3)]
```

## 사용 코드
아래 제시된 코드를 활용하여 문제를 해결해 주세요.
```python
sorted(l, key=lambda x:len(x))
d.items()
from modules import turn_right, turn_around
```