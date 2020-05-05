#  대한민국 코로나 데이터 분석: 프로젝트

* 2019년 12월, 중국 우한 지역에서 발생한 신종 '코로나 바이러스'
* 대한민국의 코로나-19 실태 파악 위해 프로젝트 진행 



## 코드, 리소스

**Python 버젼:** 3.7
**Packages:** pandas, numpy, sklearn, matplotlib, plotly, datetime, collections
**참고 사이트:** https://plotly.com/python/getting-started/?utm_source=mailchimp-jan-2015&utm_medium=email&utm_campaign=generalemail-jan2015&utm_term=bubble-chart


## 데이터 분석

테이블과 plot을 만들어 상관 관계 분석.

산업별 평균 연봉: 

![alt text](gender_corona graph)

주(State)별 평균 연봉: 

![alt text](https://github.com/jaek1997/Data-Science-Salary-Project/blob/master/state_avesalary.png)

기업 공고 경력별 평균 연봉: 

![alt text](https://github.com/jaek1997/Data-Science-Salary-Project/blob/master/seniority_avesalary.png)

상관 관계 plot: 

![alt text](https://github.com/jaek1997/Data-Science-Salary-Project/blob/master/correlation%20plot.png)

공고 키워드: 

![alt text](https://github.com/jaek1997/Data-Science-Salary-Project/blob/master/keyword.png)


# 데이터 분석 정리 

* Glassdoor.com 데이터를 분석해보니 산업별 연봉 차이는 예상보다 컸습니다. 테크 산업이 가장 연봉이 높을 것으로 예상하였으나 중개업의 평균 연봉이 많은 차이로 높았습니다. 음악 산업 또한 예상 못했지만 전체 평균보다 높은 수준이였습니다. 그 다음 산업들은 평균치에 가까웠습니다. 

* 주별 평균 연봉도 예상을 벗어났습니다. 미국내 주거비용과 물가가 가장 비싼 뉴욕과 캘리포니아는 각각 18위, 20위에 그쳤고, 평균물가가 전미 평균 이하인 아이다호, 인디애나, 플로리다가 각각 1, 2, 3위 였습니다. 단정 지을순 없지만, 지역과 평균 연봉의 상관 관계가 크지 않다는것을 알 수 있습니다. 이 데이터가 재밌어서 추후에 이 항목에 대해 더욱 깊은 분석을 할 예정입니다.  

* 공고 제목에 요구 경력을 포함한 것을 이유로 시니어, 주니어 데이터사인티스트를 나누어 평균을 내서 분석을 해보았지만 놀랍게도 시니어로 표기한 공고보다 경력 요구 사항이 없거나 주니어인 경우에 평균연봉이 조금 높았습니다. 하지만 공고 제목에 표기를 하지 않은 기업이 많아 단정 짓기에는 데이터포인트가 현저히 적었습니다. 

* 기업 설립연도, 기업 평가, 본사 근무 여부, 경력과 평균 연봉의 상관 관계를 파악하기 위해 seaborn의 plot을 이용해 분석해보았습니다. 놀랍게도 설립연도, 회사 평가, 본사 근무 여부, 경력사항 모두 평균 연봉과 크게 눈에 띄는 상관 관계가 없었습니다. 기업 평가가 높을 수록 연봉이 높게 나왔지만, 이것을 조사해보니 연봉이 높을수록 기업 평가가 높다는것을 확인 할 수 있었습니다. 

* 기업 공고 게시물에 가장 많이 나오는 키워드를 확인해보니 데이터, 머신러닝, 데이터 비주얼라이제이션이였습니다. 

# 프로젝트 하면서 느낀점

* 인터넷과 github에는 수많은 정보들이 있어 참고할 코드가 많아서 정말 좋았습니다. 내것으로 만들기 위해서는 코드를 복사 붙이기 하기 보단 왜 이 코드를 쓰는지 확인하고 또 확인하는 것이 왜 중요한지 느꼈습니다. 

* 데이터 분석을 위해 제가 원하는 결과로 가게끔 하는 제 모습을 발견하였습니다. 좋은 분석을 하기 위해서는 다음 프로젝트는 전혀 사전 지식이 없는 데이터로 분석을 해볼까 합니다. 데이터 분석가는 데이터가 말해주는대로만 알고, bias를 최대한 줄이는 방법을 생각해야 한다고 생각합니다. 
