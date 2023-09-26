<img src="https://velog.velcdn.com/images/petergbson/post/f1eaa640-895e-42a5-89db-0a1f6f0ce164/image.png" width="75%">

단어들이 의미가 비슷비슷해서 헷갈린다.
용어를 확실하게 구분하고 넘어가자. (위 고양이 사진으로 예시를 들자.)

Classification : 단순하게 이미지를 분류하는 것
Localization : 위치 정보를 구분하는 것
-> ex) Classification + Localization = 이미지 내에 특정한 cat이라는 object의 위치를 알아내는 것
Object Detection : Localization을 통해 이미지 내에서 여러 object들을 인식하고 구분 하는 것
Segmentation : 이미지 내의 모든 픽셀에 대한 차원에서 class를 분류
+ instance segmentation
+ semantic segmentation

<img src="https://velog.velcdn.com/images/petergbson/post/1d3a0d31-16cb-4937-b9f8-264837d84988/image.png" width="75%">

instance segmentation : 모든 객체에 대한 구별
semantic segmentation : 같은 class라면 그 객체들의 instance는 구분하지 않음. 그 픽셀 자체가 어떤 class에 속하는지만 관심 있음.

<img src="https://velog.velcdn.com/images/petergbson/post/71e7b436-e522-4450-ad0e-5da36840088b/image.png">

왼쪽 : instance segmentation, 오른쪽 : semantic segmentation