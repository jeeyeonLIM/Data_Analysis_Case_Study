# 데이터 분석 사례 Case Study 
- 분석 사례를 많이 보는 것은 중요하다. Reference로 활용하기에 좋고, 기존 방법을 변형하여 사용하기도 좋다. 분석할 때 어떤 방법 활용해서 어떻게 시작할지조차 막막하기 마련인데 사례를 많이 알면 어느정도 해소되지 않을까.

|num|제목|링크|설명|
|:---:|:---:|:---:|:---:| 
|1|데이터 분석 시작하기 |[link](https://www.slideshare.net/leoyang991/ss-90038927)|네웹 인턴할 때 데이터 분석 과정 관련해서 재밌게 봤던 자료|
|2|포스트 코로나 시대 Insight|[link](https://dacon.io/competitions/official/235618/codeshare/1448)|너무너무 재밌었다. 카드 소비 데이터를 기준으로 업종별 결제건수를 Clustering하고, 군집별로 외부데이터 활용하며 설명해 놨다. |
|2|코로나19와의 전쟁에서 생명 구하기 - '사망'에 대한 insights 도출|[link](https://dacon.io/codeshare/949)||

### 기타 느낀점.
2. 포스트 코로나 시대 Insight  
- Trend가 존재하는 군집화 방법에 대해 알았다. 많이 사용되는 방법인지는 잘 모르겠으나 참신하게 다가왔다.
- 시계열 데이터 분해 방법으로 Trend(추세) + Seasonal(계절성) + Random(잔차) 로 나누고, Trend를 추출한 후 :point_right: Trend를 기준으로 Corr 계산한다.  :point_right: 이렇게 구한 Corr을 바탕으로  계층 군집(Hierarchical cluster)을 ward연결법으로 시행하는 방법.
- 참고링크 : https://eat-toast.tistory.com/15
- 관련해서 시간 여유 있을 때 아래 분석도 볼 것이다
https://dacon.io/competitions/official/235618/codeshare/1434?page=1&dtype=vote&ptype=pub

