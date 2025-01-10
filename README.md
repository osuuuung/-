# 내 옷장 기반 의류 추천 서비스
일명 ‘패션 고자’들을 위한 스타일링 솔루션을 제공하는 프로젝트입니다. 옷장에 이미 있는 의류 정보를 토대로 AI 모델을 활용해 개인 맞춤형 패션 추천을 수행합니다.

<br>
<h2> 프로젝트 목표</h2>
<ul>
<li>사용자의 보유 의류를 효율적으로 파악하고, 상황에 맞는 코디 추천</li>         
<li>세련된 스타일 연출이 어려운 사용자들을 위한 의류·액세서리 매칭 아이디어</li>    
</ul>
<br>
<h2>사용한 모델</h2>   
<h3> Segmentation: U-Net </h3>   
사용자의 옷 이미지에서 영역을 정확히 분할하기 위함   
<br>
<h3> Feature Extraction: VGG-16 </h3>   
분할된 옷 이미지의 특징을 추출하고, 유사 아이템과 비교   
<br>
<br>
<h2> 데이터 </h2> 
<h3> AI-HURB의 K-FASHION </h3>  
국내 패션 데이터셋으로 다양한 스타일에 대한 학습 및 평가에 활용   
<br>
<a href ='https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=51'> 데이터 링크 </a>
