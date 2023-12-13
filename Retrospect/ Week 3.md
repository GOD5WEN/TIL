# 교육 3주차 진행후 나아가야할 방향성 정리

일단 오늘 까지 강의 를 듣고 과제를 수행하면서 느낀점은
설명을 이해가기 까지 오래걸리는 이유가 기본적인 **명칭** 이나 동작법을 인지 하지 못하고 있음에 있다는것을 깨닳았다.

아직은 튜터님들 보다는 GPT에게 많은 질문을 대체하고 있는데 
이또한 명칭의 혼선 때문이기도 하다.

## 문제점 1
예를 들어 "초기화" 하다 라는 말은 강의내내 계속들었지만 익숙한 단어이기때문에 
그냥 추상적으로 넘어갔다.
하지만 코딩에서의 초기화는 전혀 다른 의미였다.

(현재 내가 이해한것이 맞다면 존재자체를 인지시켜주기위한 초기화 작업? 되돌리는 초기화의 의미가 아닌 초기 설정을 해준다는 의미 인것으로 이해했다.)

이런 추상적으로 넘어간 부분들이 자꾸 쌓여서 결국 지금은 강의를 들어도 아무것도 이해할 수 없는 상태가 되었다.

## 문제점 2
문법 관련해서 사용되는 상황, 즉 의미와 

문법의 생김새, 즉 구성요소 

그후 활용이 있을것이다.

여기서 나의 문제점을 찾을 수 있었다. 
코드를 쓰다보면 문법의 생김새는 쉽게 익을 수 있겠지라는 안일한 생각으로 생김새(구성요소)를 조금 쉽게 생각하고 가볍게 인지하고 넘어갔다. 
구성요소는 찾아보면 바로 나오는 것이니 사용되는 상황과 의미에 더큰 초점을 맞추면서 교육을 진행하고 있었다. 

하지만 실제로 과제를 진행해보니 Swift Standard Library 나 import Foundation 의 함수들을 활용하며 기본적인 문법에서 계속 더 길어지는 추가요소가 생기기 시작했고, 모르는 함수들이 나오자 그나마 익숙했던 문법들이 무엇을 의미하는지 모를정도로 보이지않았다. 

예를들어 for _ in 1...3  이런 전형적인 생김새에서 
```
for i in 0..<3 {
    if answer [i] == uesrGuess % 10
}
```
이렇게 만 바뀌어도 코드가 읽히지 않는 문제...
물론 이 예시는 이해하고 넘어갔기 때문에 현재는 잘 읽히지만
처음에는 정말 '반복문인데... 이게 뭐지? i는 왜 [] 쌓여있는 거지? % 연산자는 뭐였지? 하면서 멘붕 상태가 오는것. 

이런부분을 해결하기 위해 문법이 사용되는 상황, 의미도 중요하지만 
문법의 구성요소 생김새에 대해서 조금더 디테일하게 봐야할 것 같다는 생각을 하게 되었다.

애초에 강의에서는 이정도로 쪼개서 하나하나 코드를 설명해주진 않아서 강의내용이 산으로 간다..

# 다음주차의 방향성 

오늘이 3주차 마지막이였고 어찌저찌 진행은 했지만. 다시 처음으로 돌아가 
확실한 명사의 이해를 먼저 숙지해야 할것 같으며,
기본적인 문법들의 구성요소를 디테일하게 인지하는것을 목표로 **복습**의 시간을 늘릴 생각이다.

아직 3주차 강의도 완강 하지 못했기떄문에 더 많은 시간을 들여야 한다.
알고리즘도 많이 못하고 있고..
아무런 도움없이 과제를 진행하기에는 턱없이 부족하다.
머리에 계속 정보를 때려 밖기만 해도 진전될 기미가 보이지않아서 답답하다.
문제점이 있는것같아서 개인적으로 회고를 진행했다.
스스로 생각할 수 있는 문제점으로는 이 두가지 문제점이 압도적인것 같다.
해결할 수 있도록 노력할 것.

주차를 거듭할수록 속도가 너무 빨라서 버거운 느낌인데..
어떻게든 이겨내고 싶다.
생각되는 문제점 먼저 고쳐나가면서 느리더라도 진행 하는것이 목표인데 
쿼리큘럼 속도에 불안해지는것과 팀과제의 압박이 생기고있다. 

