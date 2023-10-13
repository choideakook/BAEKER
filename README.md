![bk - info](https://github.com/BAEKER-230522/.github/assets/115536240/026be1d0-57b7-4e19-bd0d-48dc0cba035c)

<br>

<div align="center">- 개요 -</div>

<div align="center">
  BAEKER 는 취업 준비 중인 상황에서 시작된 프로젝트입니다.

  소득이 없는 상황에서 진행된 프로젝트인 만큼 비용 문제를 무시할 수 없었고  
  과금이 발생되지 않는 방향으로 개발이 진행되었습니다.


  BAEKER 는 처음부터 MSA 로 개발되지 않았습니다.  
  백엔드 개발자 2명이 SSR 방식의 모놀리식 아키택처로 시작되어  
  다양한 시행착오 해결과 더 나은 서비스를 구현하기 위해  
  고난과 역경을 견디며 지금의 형태가 되었습니다.  
</div>

<br>

<div align="center">- 서비스 중 -</div>

<div align="center"><a href=https://github.com/BAEKER-230522/Gateway>
  🔗 1. Gateway Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/Member>
  🔗 2. Member Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/Study>
  🔗 3. Study Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/SolvedAc>
  🔗 4. Solved Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/ChatService>
  🔗 5. Chat Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/Community>
  🔗 6. Community Server
</a></div>

<br>

<div align="center">- 서비스 종료 -</div>

<div align="center"><a href=https://github.com/BAEKER-230522/Monolith_Baeker>
  🔗 1. Monolith Service Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/View_Server>
  🔗 2. View Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/Eureka-Server>
  🔗 3. Eureka Server
</a></div>

<div align="center"><a href=https://github.com/BAEKER-230522/Config_Server>
  🔗 4. Config Server
</a></div>




<br>

## 기술 스택

![bk skill](https://github.com/BAEKER-230522/.github/assets/115536240/3e93dfda-d931-46d3-8364-5537c46a00d4)

<br>

## 마이크로 서버 관계도

[🔗 Member server ERD](https://github.com/BAEKER-230522/Member#erd)

[🔗 Study server ERD](https://github.com/BAEKER-230522/Study#erd)

[🔗 Community server Data model](https://github.com/BAEKER-230522/Community#%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%AA%A8%EB%8D%B8)

<img width="830" alt="스크린샷 2023-10-13 오후 2 25 49" src="https://github.com/BAEKER-230522/Community/assets/115536240/6e0d9f51-e88a-4c48-bc90-a627630864a5">

<br>

## 소프트웨어 아키택처 - MSA

![bk-msa](https://github.com/BAEKER-230522/.github/assets/115536240/94283765-5753-4bb8-88b7-35028b7a3404)

<br>

## 시스템 내부 아키택처 - 핵사고날 아키텍처

![hex](https://github.com/BAEKER-230522/.github/assets/115536240/d73fd646-fa9a-4205-befc-13732d950085)

<br>

## Test case 아키텍처

![test](https://github.com/BAEKER-230522/.github/assets/115536240/cd74c1b0-c95f-43d4-b987-7de5d94a194a)

<br>

## 트러블 슈팅

[01 서론](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#1%EF%B8%8F%E2%83%A3-%EC%84%9C%EB%A1%A0)

<br>

[02 민감정보 관리와 CI / CD](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#2%EF%B8%8F%E2%83%A3-%EB%AF%BC%EA%B0%90%EC%A0%95%EB%B3%B4-%EA%B4%80%EB%A6%AC%EC%99%80-cicd)

- 어떻게 공개되면 안되는 민감 정보를 보호했는가?
- CI / CD 를 적용할 때 어떻게 환경변수를 전달했는가

<br>

[03 Solved 서버의 분리](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#3%EF%B8%8F%E2%83%A3-solved-%EC%84%9C%EB%B2%84%EC%9D%98-%EB%B6%84%EB%A6%AC)

- 모놀리식 아키텍처 내의 도메인중 하나인 Solved 를 
왜 분리하게 되었는가?

<br>

[04 SSR 방식의 모노레포](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#4%EF%B8%8F%E2%83%A3-ssr-%EB%B0%A9%EC%8B%9D%EC%9D%98-%EB%AA%A8%EB%85%B8%EB%A0%88%ED%8F%AC)

- 왜 모노레포로 전환하게 되었는가?
- 왜 CSR 방식이 아닌 SSR 방식을 유지했는가?
- 어떻게 모노레포를 구축했는가?

<br>

[05 본격적인 MSA 시작](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#5%EF%B8%8F%E2%83%A3-%EB%B3%B8%EA%B2%A9%EC%A0%81%EC%9D%B8-msa-%EC%8B%9C%EC%9E%91)

- 왜 MSA 로 전환하게 되었는가?
- 어떻게 MSA 로 구축했는가?

<br>

[06 GCP 의 GKE 로 정착 그리고 Solved 서버의 분리](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#6%EF%B8%8F%E2%83%A3-gcp-%EC%9D%98-gke-%EB%A1%9C-%EC%A0%95%EC%B0%A9-%EA%B7%B8%EB%A6%AC%EA%B3%A0-solved-%EC%84%9C%EB%B2%84%EC%9D%98-%EB%B6%84%EB%A6%AC)

- 왜 EC2 와 NCP 를 계속 사용할 수 없었는가?
- 왜 GCP 를 선택했는가?
- 왜 GKE 를 선택했는가?
- 왜 다시 Solved 서버를 분리했는가?

<br>

[07 GKE 계정 이동시 세팅의 간소화](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#7%EF%B8%8F%E2%83%A3-gke-%EA%B3%84%EC%A0%95-%EC%9D%B4%EB%8F%99%EC%8B%9C-%EC%84%B8%ED%8C%85%EC%9D%98-%EA%B0%84%EC%86%8C%ED%99%94)

- 왜 주기적으로 Google 계정을 바꿔야 했는가?
- 어떻게 최소한의 리소스 투입으로 계정을 바꿔 인프라를 세팅했는가?

<br>

[08 핵사고날 아키텍처로 리팩토링 시작](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#8%EF%B8%8F%E2%83%A3-%ED%95%B5%EC%82%AC%EA%B3%A0%EB%82%A0-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%EB%A1%9C-%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81-%EC%8B%9C%EC%9E%91)

- 왜 레이어드 아키텍처에서 핵사고날 아키텍처로 리팩토링을 하는가?
- 어떻게 패키지 구조를 변경했는가?
- 리팩토링을 할동안 어떤 브랜치 전략을 사용했는가?
- 테스트는 어떻게 개선했는가?

<br>

[09 GCP 할당량 초과 문제](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#9%EF%B8%8F%E2%83%A3-gcp-%ED%95%A0%EB%8B%B9%EB%9F%89-%EC%B4%88%EA%B3%BC-%EB%AC%B8%EC%A0%9C)

- 할당량이 무엇인가?
- 왜 할당량 초과 문제가 발생했는가?
- 어떻게 문제를 해결했는가?

<br>

[10 마치며](https://github.com/BAEKER-230522/Gateway/wiki/Troubleshooting#-%EB%A7%88%EC%B9%98%EB%A9%B0)

<br>

## 팀원

<table>
    <tr>
      <td align="center"><img src="https://github.com/PARKPARKWOO.png" width="160"></td>
      <td align="center"><img src="https://github.com/choideakook.png" width="160"></td>
    </tr>
    <tr>
      <td align="center">박우영</td>
      <td align="center">최대국</td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/PARKPARKWOO" target="_blank" width="160">@PARKPARKWOO</a></td>
      <td align="center"><a href="https://github.com/choideakook" target="_blank">@choideakook</a></td>
    </tr>
  </table>
