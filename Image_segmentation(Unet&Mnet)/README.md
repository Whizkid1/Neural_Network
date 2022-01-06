# Image segmentation
대부분의 공부는 Template을 활용하는 쪽으로 수업이 진행됬다.
너무 재밌는 부분이라 폴더를 나누어 개인 공부를 하기로 했다.

-기초 개념 공부 \
https://devkor.tistory.com/entry/%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%84-%ED%86%B5%ED%95%9C-Image-Segmentation-%EC%9E%85%EB%AC%B8

1. 기본 틀 : ENcoder + Decorder
2. Encorder : CNN 처럼 분석을 통해 픽셀 값들을 분류
3. Decorder : 분류된 값을 원래 사이즈의 사진으로 복원(up sampling+skip combining)
즉, Convolution과 pooling을 거치고, dense층에서 flatten과 기법을 통해 잃어버린 위치정보를 유지하기 위해서 1x1 ConvLayer로 유지시키는 기법

  - 추가 개념공부
    - Up-sampling with Transposed Convolution
  : https://zzsza.github.io/data/2018/06/25/upsampling-with-transposed-convolution/
  
  - 추가로 공부할 개념
  https://blog.naver.com/PostView.naver?blogId=laonple&logNo=220643128255&categoryNo=22&parentCategoryNo=0&viewDate=&currentPage=7&postListTopCurrentPage=1&from=postList&userTopListOpen=true&userTopListCount=10&userTopListManageOpen=false&userTopListCurrentPage=7 \
  위의 사이트를 기반으로 주요 아키텍쳐 논문을 공부 및 repository에 작성
  
