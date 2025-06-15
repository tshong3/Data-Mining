<h3>2025년 1학기 데이터마이닝 A분반 B조</h3> 
<h4>주제 : 유튜브 악성댓글 탐지 및 필터링</h4>
<hr>
<ul>
  <li>실험 환경</li>
  <ul>
    <li>python 3.9.12</li>
  </ul>
  <li>실행방법</li>
  <ol>
    <li>anaconda를 이용해서 가상환경 만들기 : conda create -n dm python=3.9.12</li>
    <li>가상환경 활성화 : conda activate dm</li>
    <li>visual code에서 동작할 수 있도록 ipyknernel 설치 : pip install ipykernel</li>
    <li>setup.ipynb 실행 후 커널 재시작</li>
    <li>main.ipynb 실행</li>
  </ol>
  <li>code</li>
  <ul>
    <li>main.ipynb : 데이터 전처리, 특성 추출, 모델 정의 및 학습</li>
    <li>setup.ipynb : 필요 라이브러리 설치 및 hanspell passport_key 설정</li>
    <li>youtube_comment_parser.ipynb : 유튜브 댓글 크롤링</li>
  </ul>
  <li>data</li>
  <ul>
    <li>github_kohate_data.csv : github에 공개되어 있는 한국어 혐오 발언 데이터셋</li>
    <li>https://github.com/kocohub/korean-hate-speech</li>
    <li>youtube_comment.csv : 백종원 관련 영상에서 크롤링하여 추출한 댓글 데이터</li>
    <li>youtube_comments_pred.csv : dense 모델로 유튜브 댓글을 예측한 결과 파일</li>
  </ul>
  <li>font</li>
  <ul>
    <li>NaumGothic.ttf : matplotlib, wordcloud 사용 시 한글 깨짐 현상을 방지하기 위한 한글 폰트</li>
  </ul>
  <br>
</ul>
