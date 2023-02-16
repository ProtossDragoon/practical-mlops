# 실전 MLOps 번역 소스코드 길라잡이

<table>
<thead align="center">
  <tr>
    <th>원서</th>
    <th>번역서</th>
  </tr>
</thead>
<tbody align="center">
  <tr>
    <td><img width="" src="https://user-images.githubusercontent.com/58792/121539559-c6787e80-c9d3-11eb-9f48-5d25924fad25.png"></td>
    <td><img width="" src="https://user-images.githubusercontent.com/58792/121539559-c6787e80-c9d3-11eb-9f48-5d25924fad25.png"></td>
  </tr>
  <tr>
    <td>Practical MLOps<br>노아 기프트, 알프레도 데자</td>
    <td>실전 MLOps<br>이장후, 이일섭</td>
  </tr>
</tbody>
</table>


이 저장소는 한빛미디어의 <실전 MLOps> (원: Noah Gift & Alfredo Deza, \<Practical MLOps\>, O'Reilly) 한국 독자들을 위해 번역과 설명이 추가된 저장소들로 향하는 길라잡이입니다.

## 목차

| 책 | 실습내용 | 저자 | 역자 |
| --- | --- | --- | --- |
| 2.8 | 잔돈 반환 방식을 통해 그리디와 머신러닝의 개념을 이해합니다. | [깃허브](https://github.com/noahgift/greedy_coin) | [깃허브](https://github.com/ProtossDragoon/greedy-change) |
| 2.8 | 외판원 순회 문제를 통해 그리디와 머신러닝의 개념을 이해합니다. |[깃허브](https://github.com/noahgift/or) | [깃허브](https://github.com/ProtossDragoon/greedy-tsp) |
| 2.11 | 주어진 머신러닝 모델과 애저 파이프라인을 이용하여 애저 앱 서비스에 플라스크 머신러닝 애플리케이션을 배포합니다. | [깃허브](https://github.com/noahgift/flask-ml-azure-serverless) | [깃허브](https://github.com/ProtossDragoon/flask-ml-azure) |
| 3.1 | 최소한의 의존성, 애플리케이션 소스코드, 머신러닝 모델을 포함하는 컨테이너 이미지를 빌드합니다. | - | [깃허브](https://github.com/ProtossDragoon/flask-docker) |
| 4.1 | 깃허브 액션을 이용해 ONNX 모델을 애저 모델 레지스트리에서 다운로드받고 컨테이너화하여 여러 컨테이너 레지스트리에 푸시합니다. | - | [깃허브](https://github.com/ProtossDragoon/flask-docker-onnx-azure) |
| 5.6 | 오픈소스 AutoML 프레임워크 Ludwig 을 이용하여 간단한 머신러닝 모델을 학습시킵니다. | - | [깃허브](https://github.com/ProtossDragoon/ludwig-quickstart/blob/main/notebook/Ludwig.ipynb) |
| 7.1 | S3와 휴고를 이용해 정적 웹 사이트를 배포합니다. | [깃허브](https://github.com/noahgift/dukehugofeb1) | - |
| 7.1 | AWS 코드빌드와 AWS Elastic Beanstalk을 이용해 플라스크 웹 애플리케이션을 배포합니다. | [깃허브](https://github.com/noahgift/Flask-Elastic-Beanstalk) | [깃허브](https://github.com/ProtossDragoon/flask-elastic-beanstalk) |
| 7.2 | 다양한 프로젝트에 범용적으로 사용 가능한 파일들과 이들의 역할을 이해하고, AWS 앱러너에 머신러닝 모델이 포함된 플라스크 웹 애플리케이션을 배포합니다. | [깃허브](https://github.com/noahgift/Python-MLOps-Cookbook) | [깃허브](https://github.com/ProtossDragoon/mlops-recipe) |
| 7.3 | AWS SAM을 이용하여 머신러닝 모델이 포함된 플라스크 웹 애플리케이션을 배포합니다. | [깃허브](https://github.com/noahgift/Python-MLOps-Cookbook/tree/main/recipes/aws-lambda-sam) | [깃허브](https://github.com/ProtossDragoon/aws-sam) |

## 원칙

저자의 소스코드는 역자에 의해 아래와 같은 원칙으로 재구성되었습니다.

- 작동하지 않는 소스코드 리팩터링
- 오탈자 수정과 주석 깃허브
- 최대한 간결한 코드, 핵심적인 코드만을 작성
- 이해에 불필요한 소스코드, 미사여구, 주석, 파일 제거

구체적으로 [어떻게 수정되었나요?](./EX.md)

## 인용

본 저장소나 <실전 MLOps>의 내용을 인용하실 때에는 아래 내용을 사용하시면 편리합니다.

```
@book{noahgift2021practical,
    TODO
}
```