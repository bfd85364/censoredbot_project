1.해당 프로젝트는 본인이 운영중인 커뮤니티 서버에서 유저들의 대화내역과 첨부 사진을 검열 하는 앱을 개발, 유저들의 만족도 조사를 진행후
다음 개발 방향성을 찾는 목적으로 진행한 프로젝트 입니다. 
검열 키워드에 해당하는 단어나 검열할 첨부파일 (png, jpeg, jpg)의 픽셀값이 같을 경우 필터 역할을 하는 코드가 이를 인지하고 삭제하도록 설계하였습니다. 

2.해당앱을 개발하고 난후 SVM과 KNN 모델을 활용하여 유저반응을 만족도 조사의 항목별로 부정/긍정 반응으로 분류하였고 이를 바탕으로 앱 개선 반응을 도출하였습니다.  

3.만족도 조사 이후 KNN 모델을 활용하여 처음으로 성능평가를 시도하였을때 훈련 모델과 테스트 모델간 데이터 불균형 문제가 발생
   ---->해당 문제를 해결하기 위해 분류 모델을 KNN->SVM으로 변경후 유저들의 반응을 처음부터 다시 분류함. 
