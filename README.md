# Responsive_Sass

## Useful mixin , function for making responsive Web 


### get-vw
- 매번 vw 값을 계산하는게 번거롭고, 시간이 오래 걸린다 생각하여 디자인 시안 기준 px 값을 함수 안에 넘기면 자동으로 vw 값을 계산해 주는 함수를 만들었다.


### mixin responsive
- get-vw를 만든 후에 유용하게 쓰면서 작업을 하던 중 동료가 css를 버거워 했는데, 그 중에 하나가 가로,세로 버전을 만들어 줘야 할 때였다.
디자인 시안에서는 같은 px을 쓰지만 vw값이 다르기 때문에 가로,세로 모드를 css에 따로 추가해줘야 했는데 get-vw를 만들었을 때처럼 
sass를 이용하면 간단하게 쓸 수 있지 않을까? 해서 만들었다.
기존 css 작성과 비슷하게, 적용할 스타일과 값을 넘기면 자동으로 가로모드 일때와 세로 모드일때의 media-query, 그에 맞는 vw로 계산해준다.  
