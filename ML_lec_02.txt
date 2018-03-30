Linear regression/n. 선형회귀
180331 ML lec 02 linear regression과 hypothesis와 cost 설명
링크 : https://youtu.be/Hax03rCn3UI
regression/n. x와y의 관계에 적합한 선
score data를 기반으로 한 학생의 점수 예측
training data
세상의 많은 것들이 linear로 설명되는 경우가 많음.
훈련을 많이 할 수록 달리기실력이 올라감
집의 크기와 가격이 비례한다.
hypothesis -> H(x) = wx + b (가설 linear regression)

H(x) - y 는 좋지 않고(음수가 될 수 있기에)
(H(x)-y)^2은 항상 양수이고 큰값에 웨이트를 많이 줄 수 있다.
cost = 1/m*시그마(i=1 to m){(H(xi)-yi)^2}
m : 데이터의 갯수
cost(W,b) W: 기울기 b: y절편
cost(W,b)를 최소화 시켜야 한다!!!

