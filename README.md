

# 1. 회귀분석 정의

회귀분석(regression analysis)는 변수들간의 함수관계를 추구하는 통계적 방법이다. <br>
회귀분석은 독립변수와 종속변수 간의 함수관계를 규명하는 통계적 방법입니다. 그렇다면 독립변수와 종속변수는 무엇일까요? <br>
독립변수(independent variable)는 입력값이나 원인을 나타내며, 종속변수(dependent variable)은 결과물이나 효과를 나타낸다. <br>

<br>
독립변수는 설명변수(explanatory variable)이라고도 하며, 종속변수는 반응변수(response variable)이라고도 합니다. <br>
독립변수와 종속변수는 (xi,yi)(xi,yi) 쌍으로 표현하고 독립변수의 집합을 대문자 XX, 종속변수의 집합을 대문자 YY로 표현합니다. <br>
결국 회귀분석이란 독립변수 XX의 분포를 분석한 후, 종속변수 YY의 값을 예측하는 것입니다. <br>
다른 말로하면 다양하게 분포된 XX가 존재할 때, YY의 분포를 알아내는 것입니다.<br>
회귀분석(regression)은 가장 넓은 의미로는 독립변수(x)로 종속변수(y)를 예측하는 것을 의미한다. <br>

<br>
회귀 분석을 하는 이유
관찰이나 실험으로 얻은 샘플자료(적은 수의 자료)를 분석하고 설명하기 위해서는 그 자료를 잘 표현할 수 있는 '방정식'을 예측해야 합니다. <br>
자료를 가장 잘 설명하는 방정식이란, 원래 자료와의 오차(error)를 가장 적게 만든 식 입니다.<br>
아래 그림의 x와 y의 분포도에 있는 저 선(Regression line)이 바로 '자료를 가장 잘 설명하는 방정식'이 됩니다.
회귀분석에서는 이 선을 '회귀선'이라고 하며, 이 회귀선의 '회귀(방정)식'을 이용하면 독립변수로 종속변수를 예측할 수 있게 됩니다. <br>

상관관계 분석 VS 회귀분석<br>
연속형 또는 순위자료로 이뤄진 두 변수의 상호관계만(선형 관계가 존재하는지 아닌지)을 보려면 상관관계 분석(Correlation analysis)을 이용한다. <br>
즉, 상관관계 분석은 변수들 간의 선형성의 강도에 대한 통계적 분석이라 할 수 있다.<br> 

그러나 한 변수의 값으로부터 다른 변수의 값을 예측하고자 하는 경우에는 회귀분석(Regression analysis)을 이용한다. <br>
회귀분석은 변수들 간의 구체적인 함수관계를 파악하고자 할 때 즉, <br>
인과관계라던지 한 변수가 다른 변수에 주는 영향력을 알아보고자 할 때 사용한다.<br>
<br>
3.  회귀분석의 특징<br>
3.1.  장점
1)  실제성과 친밀성
-  예측 문제 해결에 있어서 가장 많이 사용되고 있는 방법론으로써 분석 및 해석방법 다수 존재
2)  해석 및 설명력
-  결과에 대한 근거, 이유, 활용방안 등의 유용한 정보 얻는 데 용이
3)  적절한 변수 선택
-  목표변수와 관련 있는 설명변수(i.e., 영향인자) 선택 방법 존재
3.2.  단점
-  기본 가정이 어긋나면 회귀분석 사용 불가
-  비선형성 확인을 위한 적절한 방법론이 없어 반복적인 검토 필요
-  결측치는 반드시 분석에서 제외되기 때문에 분석결과의 신뢰성 문제될 수 있음
<br>
회귀분석의 다양한 유형<br>
·         선형 회귀(Linear regression) ...<br>
·         로지스틱 회귀(Logistic regression) ...<br>
·         리지 회귀(Ridge regression) ...<br>
·         라쏘 회귀(Lasso regression) ...<br>
·         다항 회귀(Polynomial regression) <br><br>

회귀분석의 다양한 유형<br>
·         선형 회귀(Linear regression) ...<br>
·         로지스틱 회귀(Logistic regression) ...<br>
·         리지 회귀(Ridge regression) ...<br>
·         라쏘 회귀(Lasso regression) ...<br>
·         다항 회귀(Polynomial regression)  <br><br>

단순 선형 회귀를 통한 회귀 이해<br>

단순 선형 회귀는 독립변수도 하나, 종속변수도 하나인 선형 회귀이다. C
예를 들어, 주택 가격이 주택의 크기로만 결정된다고 하면 <br>
2차원 평면에 직선(선형)형태의 관계로 표현할 수 있다. <br>
X축이 주택의 크기이고, Y축이 가격이라할 경우 1차 함수식으로 모델링할 수 있다.
 
! $Y^ = ω_0 + ω_1 ∗ $X <br>
<br>![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
위 설명의 모델링과는 별개로 선형 회귀 모델을 보이기 위한 자료 <br><br>
 
독립 변수가 1개인 단순 선형 회귀에서는 기울기인 ω1과 절편인 ω0을 회귀 계수로 지칭한다. <br>
위와 같은 1차 함수로 모델링했다면 실제 주택 가격은 이러한 1차 함수 값에서 실제 값만큼의 오류 값을 빼거나 더한 값이 된다.<br>
 
이렇게 실제값과 회귀 모델의 차이에 따른 오류값을 남은 오류, 즉 잔차라 부른다. <br>
최적의 회귀 모델을 만든다는 것은 전체 데이터의 잔차(오류값) 합이 최소가 되는 모델을 만든다는 의미이며, <br>
동시에 오류값 합이 최소가 될 수 있는 최적의 회귀 계수를 찾는다는 의미이다.
 
오류값은 +나 -가 될 수 있기에 전체 데이터의 오류합을 구하기 위해 단순히 더할경우 뜻하지 않게 오류합이 줄어들 수 있다. <br>
따라서 보통 오류합을 계산할 때는 절대값을 취해서 더하거나, <br>
오류값의 제곱을 구해서 더하는 방식(RSS, Residual Sum of Square)를 취한다. <br>
일반적으로 미분 등의 계산을 편리하게 하기 위해서 RSS(Residual Sum of Square) 방식으로 오류합을 구한다. <br>
즉, Error2=RSS이다.<br>
 
RSS는 이제 변수가 ω0,ω1인 식으로 표현할 수 있으며, 이 RSS를 최소로 하는 ω0,ω1, 즉 <br>
회귀 계수를 학습을 통해서 찾는 것이 머신러닝 기반 회귀의 핵심 사항이다. <br>
RSS는 회귀식의 독립변수 X, 종속변수 Y가 중심 변수가 아니라 <br>
ω 변수(회귀 계수)가 중심 변수임을 인지하는 것이 매우 중요하다(학습 데이터로 입력되는 독립변수와 종속변수는 RSS에서 모두 상수로 간주한다. <br>
일반적으로 RSS는 학습 데이터의 건수로 나누어서 다음과 같이 정규화된 식으로 표현된다.<br>
 
RSS(ω0,ω1)= 1N ∑i=1N(yi−(ω0+ω1∗xi))2
 
회귀에서 RSS는 비용(Cost)이며 ω 변수(회귀 계수)로 구성되는 RSS를 비용 함수라고 한다. <br>
머신러닝 회귀 알고리즘은 데이터를 계속 학습하면서 이 비용 함수가 반환하는 값(즉, 오류값)을 지속해서 감소시키고 <br>
최종적으로는 더 이상 감소하지 않는 최소의 오류값을 구하는 것이다. <br>
비용 함수를 손실 함수(loss function)라고도 한다.<br>
 
회귀 평가 지표<br>

회귀의 평가를 위한 지표는 실제값과 회귀 예측값의 차이값을 기반으로 한 지표가 중심이다. 실제값과 예측값의 차이를 단순히 더하면 +와 -가 섞여서 오류가 상쇄된다. 예를 들어 데이터 두 개의 예측 차이가 하나는 -3, 다른 하나는 +3일 경우 단순히 더하면 오류가 0으로 나타나기 때문에 정확한 지표가 될 수 없다. 따라서 오류의 절대값 평균이나 제곱, 또는 제곱한 뒤 다시 루트를 씌운 평균값을 구한다. 일반적으로 회귀의 성능을 평가하는 지표는 다음과 같다.
 
평가 지표
설명
수식
MAE
Mean Absolute Error이며 실제값과 예측값의 차이를 절대값으로 변환해 평균한 것
MAE= 1n ∑i=1n|Yi−Y^i|
MSE
Mean Squared Error이며 실제값과 예측값의 차이를 제곱해 평균한 것
MSE= 1n ∑i=1n(Yi−Y^i)2
RMSE
MSE 값은 오류의 제곱을 구하므로 실제 오류 평균보다 더 커지는 특성이 있으므로 MSE에 루트를 씌운 것이 RMSE.
RMSE= 1n∑i=1n(Yi−Y^i)2
R2
분산 기반으로 예측 성능을 평가한다. 실제값의 분산 대비 예측값의 분산 비율을 지표로 하며, 1에 가까울수록 예측 정확도가 높음
예측값실제값R2=예측값Variacne실제값Variance

 
이외에도 MSE나 RMSE에 로그를 적용한 MSLE(Mean Squared Log Error)와 RMSLE(Root Mean Squared Log Error)도 사용한다. 사이킷런은 RMSE를 제공하지 않는다. 따라서 RMSE를 구하기 위해서는 MSE에 제곱근을 씌워서 계산하는 함수를 직접 만들어야 한다. 다음은 각 평가 방법에 대한 사이킷런의 API 및 cross_val_score나 GridSearchCV에서 평가 시 사용되는 scoring 파라미터의 적용값이다.
 
평가 방법
사이킷런 평가 지표 API
Scoring 함수 적용 값
MAE
metrics.meam_absoulte_error
'neg_mean_absolute_error'
MSE
metrics.mean_squared_error
'neg_mean_squared_error'
R2
metrics.r2_score
'r2'



선형 회귀법에 대한 간단항 예시.

y=ax + b 에 있어서 <br>
x=(2, 4, 6, 8) 이고 <br>
y=(81, 93, 91, 97) 인 <br>
<br>
집합 X, Y 가 있다면 <br>
X, 와 Y의 상관 관계를 수식 으로 표현할수 있는데 <br><br>
y=ax +b 에서 a 와 b 를 구할수 있다.<br>
a=(x-x의 평균)*(y-y의 평균)을  (x-x의 평균)제곱의 합  으로 나눈 값이 된다.<br><br>
계산 하면 2.3 이나오고.<br><br>
! $b = $y의 평균 - ($x의 평균 * 기울기a) 가된다.<br>
계산하면 79 가 나와서<br>
! $y = 2.3x + 79 라는 그래프를 얻을수 있다.<br>

위의 집합을 기울기와 절편이 있는 선형 그래프를 그릴수 있고,<br>
만약에 x가 3.5 이면 y의 값이  87 정도 되는 것을 예측 할수 있다.<br>
결국 Linear Regression에 의해 분석 예측을 할수 있는 한 방법이다. <br>





