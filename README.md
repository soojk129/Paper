# Paper

2022.05.31 

지금 내가 하고싶은거는 

1. 재식별 가능성을 모니터링해서 재식별 가능성이 있는 데이터를 필터링하고싶다는것. 
-> 재식별하는 프로그램을 솔루션 이용하여 필터링 할수 있는 모니터링 시스템을 구축해야할까

아님..

2. 재식별화 하는 알고리즘을 찾아서 거기의 개선을할까  
-> 이걸로 하려고 생각중! (90% 정도)

[이 논문](https://file1.earticle.net/PDF/Direct?key=v+Ly10tYUm8wt7O5kNoLw6nqArNCs+xr4yomiocwa1JCcn0B1fLA+kjGtJbGM66CcfSDvaj7Y5JseRqu/zUUnsLuRyXZhwJMNlvzdRiliF02LiwomVTsFYgbCEC51Z33IRtiOU9byEW+gJTe+8ioPjrjRT2hzATL0YSNLhR1WdiNWVEkMec3/KFzEio5P/11GhCS/K56txR/pr/Q/CF0VBDtbL/9X4W/SXAOYIKQ/u4=) 보다가 모수추청관련하여 알아보려고 빅데이터분석기사에서 개인정보관련 공부 시작!




2022.06.02


알아볼거 -> 재식별알고리즘 찾아보기!

재식별 알고리즘 찾다가 결합관련내용 찾음.
K-익명성 알고리즘을 실행할때 개선 (기존 연구 -> 1:1 구조 N:1구조로 변경 하기)



비식별화를 하는 알고리즘을 찾아보니까 .. 여러가지가있엇다아..
근데 문제점이 비식별화를 한 데이터를 가지고 재식별을 하는문제가 있어서
재식별을 하기위해 제한된 모델일 3가지가 있는데
k-익명성 ,  l-다양성, t-근접성이라고
KLT모델이 있다. 일단 이 모델을 하나씩 구현해보려고한다. (하둡, )
지금 하고 싶은거는 그래서 재식별 가능성이 있는 데이터를 좀 걸러내고 싶다인데..
그래서 재식별할때 적용되는 모델에 대해 하나씩 만들어보려고한다.

근데 이미 구글 클라우드 DLP라고 데이터 손실 방지 해주는 솔루션이 있어서
각각의 프라이버시 모델에 대해 위험성 수치를 계산해주는 솔루션이 있습니다.
그래서 이걸 어떤 방향으로 틀면 좋을지에 대해 고민중입니다.


개선이라고 한다면..

적은 리소스로 대량의 데이터를 처리할 수 있도록..
아니면 기존거 보다 다양하게 처리할 수 있다던가
아니면 기존거보다 성능이 좋다(빠르다/정확도가 높다)
아니면..

일단 이걸 개선하려면 klt 알고리즘에 대해서 알아보고 적용할 수 있는걸 찾아보려고하는데 이게 나을지
아니면 다른 새로운 알고리즘을 찾아보는게 나을지..



2022.06.05

ARX구현

2022.06.06

이어서하기!
