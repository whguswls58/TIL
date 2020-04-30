### 확률분포 클래스
|종류|명령|확률분포|
|-------|---------|------|
|이산|bernoulli|베르누이분포|
|이산|binom|이항분포|
|이산|multinomial|다항분포|
|연속|uniform|균일분포|
|연속|norm|정규분포|
|연속|beta|베타분포|
|연속|gamma|감마분포|
|연속|t|스튜던트 t분포|
|연속|chi2|카이 제곱분포|
|연속|f|F분포|
|연속|dirichlet|디리클리분포|
|연속|multivariate_normal|다변수정규분포|

### 모수 지정
|인수(모수) 이름|의미|
|-------|-------|
|loc|일반적으로 분포의 기대값|
|scale|일반적으로 분포의 표준편차|

### 확률분포 메서드
|메서드|기능|
|-------|--------|
|pmf|확률질량함수(probability mass function)|
|pdf|확률밀도함수(probability density function)|
|cdf|누적분포함수(cumulative distribution function)|
|ppf|누적분포함수의 역함수(inverse cumulative distribution function)|
|sf|생존함수(survival function) = 1 - 누적분포함수)|
|isf|생존함수의 역함수(inverse survival function)|
|rvs|랜덤 표본 생성(random variable sampling)|