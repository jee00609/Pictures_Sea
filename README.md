## Pictures Sea

![Main Page](https://user-images.githubusercontent.com/31675804/141615048-78f8ccf2-0bf2-4a57-88b4-f089a161c526.PNG)

AWS Rekognition 과 ETRI Open API 를 통해 사용자의 이미지를 분석하여 추출한 오브젝트 단어에 대하여, <br/> **단어에 대한 정의와 사용자의 발음을 평가** 해주는 프로그램 제작

## 목차

* [상세 기능 구현 사항](#상세-기능-구현-사항)
* [UML](#UML)
* [개발 기록](#개발-기록)


## 상세 기능 구현 사항

* 선택한 이미지 S3 에 업로드 후 Rekognition Object 추출 - 완성
* 추출한 Object 에 대해 화면에 동적으로 카드 출력 - 완성
* 출력된 카드들 중에 원하는 카드 클릭 시 상세 카드(Rating) 가 아래에 출력 - 완성
* 녹음 및 녹음 저장 - 완성
* 녹음한 Audio 파일 업로드 - 완성
* 상세카드의 Rating 버튼 클릭 시 업로드한 Audio 파일과 Object 카드를 비교하여 발음 평가 - 완성
* Object 와 Object 에 대한 한국어 정의, 발음 평가 점수 등을 새 탭에서 열리는 페이지에서 출력 - 완성
* 프로젝트를 소개하는 Introduce 페이지 생성 - 완성


## UML

* Class Diagram

<img src="https://github.com/jee00609/Pictures_Sea/blob/master/src/main/resources/static/uml/Class%20Diagram.png"  width="900" height="500"/>

* Floaw Chart

<img src="https://github.com/jee00609/Pictures_Sea/blob/master/src/main/resources/static/uml/Flow%20Chart.png"  width="500" height="600"/>

## 개발 기록

* [Spring Framework 환경 에서의 AWS-S3 업로드 테스팅 프로젝트](https://github.com/jee00609/aws-s3Uplaod-Upgrade-Demo)
* [Spring Framework 환경 에서의 AWS-Rekognition 테스팅 프로젝트](https://github.com/jee00609/aws-rekognition-Demo)
