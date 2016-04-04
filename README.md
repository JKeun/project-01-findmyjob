# Find my job
small project in data science school (남지열, 박재근, 신은지)
![wordcloud](https://github.com/JKeun/project-01-findmyjob/blob/master/resource/wordcloud1.PNG)
## Why?
* 내가 하고 싶은 일은 무엇일까?
* 내가 잘 할 수 있는 일은 무엇일까?
* 나는 과연 데이터 사이언티스트로서 적합한 사람일까? 잘할 수 있을까?
 
## Goal
* 내가 가진 역량 및 성격을 입력 **(input)** = > 나에게 적합한 직업을 예측 **(output)**

## How?
* 데이터 수집
    * linkedin 웹사이트에서 키워드 ***'Data Scientist'***로 채용공고 검색 ***(y)***
    * 해당 공고에서 ***requirements & qualifications*** 크롤링 ***(X)***

* 분석 방법
    * Supervised learning
        * **Naive Bayesian**
            * Multinomial Naive Bayes

## < Workflow >
* 데이터수집 => 전처리 => 모델선택 => 계수추정 => 평가 => 개선작업 => 최종 성능평가

## Data & Samples
* **input data** is string of job description(reponsibility&qualification)
* **target** is {class0, class1, class2} -> {***'Data Science', 'Digital Marketing', 'UX/UI Deginger'***}

![linkedin](https://github.com/JKeun/project-01-findmyjob/blob/master/resource/linkedin3.PNG)
