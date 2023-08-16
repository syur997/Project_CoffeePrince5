![header](https://capsule-render.vercel.app/api?type=Waving&color=61380B&height=200&text=Project&fontColor=FFFFFF)

<h1 align="center"> ☕ 실제 카페 데이터 기반의 솔루션 제안 프로젝트 ☕ </h1>
<div align='right'>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=Tableau&logoColor=white"/> <img src="https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/> 
</div>
<br>
<br>
<br>
<h2 align="left"> 주제 선정 배경 </h2>
<p align="left">
  1. 현재 오프라인 매장의 한계점<br>
  2. 대표님의 가치관 - 매출보다 원두를 진정으로 알리고 싶으신 마음<br>
  3. 대표님의 노하우 - 대표님만의 '출장'으로 쌓인 경험과 노하우<br>
  * 위 3가지의 이유로 데이터를 기반하여 새로운 솔루션을 도출하고 제안하기로 결정
</p>
<br>
<br>
<br>
<h2 align="left"> 데이터 수집 </h2>
<p align="left">
  1. 실제 카페 매출 전산 데이터(원본 파일과 그래프, 수치 등 대외비는 비공개 처리함)<br>
  2. 기상청의 날씨(기온, 풍속) 데이터(https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36)<br>
  3. 제주관광공사의 제주 관광 입도객 데이터(https://ijto.or.kr/korean/pds_search/search.php?cid=184)<br>
  4. 네이버 리뷰 Crawling
</p>
<br>
<br>
<br>
<h2 align="left"> EDA 진행 </h2>
<h3 align='left'> ** 대외비(정확한 값, 수치, X축, Y축) 비공개 처리 ** </h3>
<p align="left">
  1. 요일별 매출 비교<br>
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/edffec00-e286-4eee-ae8e-2e4fa3996866.png" width="500" height="300"/><br>
  <br>
  2. 시간대별 매출 비교<br>
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/1a368def-3974-4d73-bc5d-de4cde5f7429.png" width="500" height="300"/><br>
  <br>
  3. 메뉴별 매출 점유율 확인<br>
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/775e9e9d-2bbd-4161-9e73-7be54b24f743.png" width="500" height="300"/><br>
  <br>
  4. 평일, 주말, 공휴일의 매출 비교 → 공휴일이 매출에 미치는 영향<br>
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/03f3e1c6-8a4e-4436-9904-d4700d24487e.png" width="500" height="300"/><br>
  <br>
  5. 요일별 제주 관광 월별 입도객 비교<br>
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/17a469ba-7250-4103-8c59-b604715a5a2b.png" width="500" height="300"/><br>
  <br>
  6. 매출과 날씨(기온, 풍속) 비교<br>
  - 시계열 그래프 사용
</p>
<br>
<br>
<br>
<h2 align="left"> 솔루션 도출 및 제안 </h2>
- EDA 및 데이터 분석을 기반으로 솔루션 도출
<p align="left">
  <img src="https://github.com/syur997/Project_CoffeePrince5/assets/110324563/5ff222c2-6b75-4b9a-a3b8-02dfec40e235.png" width="500" height="300"/><br>
</p>
