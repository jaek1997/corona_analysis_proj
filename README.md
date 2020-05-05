#  대한민국 코로나 데이터 분석: 프로젝트

* 2019년 12월, 중국 우한 지역에서 발생한 신종 '코로나 바이러스'
* 대한민국의 코로나-19 실태 파악 위해 프로젝트 진행 



## 코드, 리소스

**Python 버젼:** 3.7
**Packages:** pandas, numpy, sklearn, matplotlib, plotly, datetime, collections
**참고 사이트:** https://plotly.com/python/getting-started/?utm_source=mailchimp-jan-2015&utm_medium=email&utm_campaign=generalemail-jan2015&utm_term=bubble-chart


## 데이터 분석

테이블과 plot을 만들어 상관 관계 분석.

환자 성별:

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/gender_corona%20graph.png)

감염 분포도: 

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/corona_korea_map.png)

도 별 감염자 수: 

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/province_corona.png)

감염자 연령 그래프: 

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/infected_age.png)
 

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/rid_graph.png)


사망자 연령 그래프: 

![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/age_decease.png)


 
![alt text](https://github.com/jaek1997/corona_analysis_proj/blob/master/jan_feb_march.png)


# 데이터 분석 정리 

* 감염자 성별을 확인해보니 여성이 남성보다 조금 많았습니다. 하지만 눈에 띄게 비율이 다르지 않아 성별이 감염에 영향을 주진 않는다고 판단했습니다. 

* 감염자 연령 비율을 분석해보니 20대, 50대, 40대, 30대, 60대, 70대, 80대, 10대, 아동, 90대 순으로 많았습니다. 가장 활동적인 20대가 감염자 수가 가장 많은 것은 예상하였지만 50대가 30대, 10대보다 감염자 수가 많다는 것이 의아 했습니다. 중국 연구진이 발표한 내용을 보니 만성질환을 앓고 있는 50대 남성의 감염 확률이 높다는 연구 결과를 발표하면서 순위를 이해할 수 있었습니다. 

* 우리나라의 격리, 격리해제, 사망자 비율을 확인해보니 2.04%를 웃도는 수준이였습니다. 전세계적으로 평균 사망자 비율이 3.36%대 인 것을 감안한다면 대처를 잘하고 있다는 평가를 내릴 수 있었습니다. 

* 연령별 사망률을 분석해보니 60대 이상의 환자가 사망률이 압도적으로 높았습니다. 20대이하의 감염자중에는 사망자가 나오지 않아 연령에 따른 사망 확률을 확실히 확인할 수 있었습니다.  

* 우리나라의 바이러스 검사 수(1,2,3월)를 확인해보니 대처를 정말 잘했다는 것을 알 수 있습니다. 감염자 수가 폭등한 2,3월에 검사 수가 기하급수적으로 증가한 것을 알 수 있습니다.  

# 프로젝트 하면서 느낀점

* 우선 pyplot을 처음 사용해보니 보기 좋은 visualization이 너무 많았습니다. 이 프로젝트에서 pyplot, matplotlib, iplot 을 골고루 사용해 보았지만, 다음 프로젝트에서는 통일 해볼까 합니다. 여러가지 디자인을 쓰다보니 보기 쉽지 않고, 리포트를 보는 사람 입장에서는 해석하기 좋지 않은듯 합니다. 파이썬의 라이브러리를 더욱 많이 사용하며 연습하려고 합니다. 

* 이 프로젝트를 하며 우리나라가 얼마나 잘 대처하고 있는지 느껴집니다. 한국의 수많은 데이터들이 이 바이러스를 더욱 잘 파악할 수 있도록 돕는 것 같습니다. 미래에도 신종 바이러스가 생긴다면 제가 앞장서서 데이터 분석을 하고 싶은 마음이 생겼습니다. 대한민국 화이팅. 
