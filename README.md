# magazine-in-lapidem

매거진 페이지를 구현하고, AWS를 통해 배포한 서비스 입니다.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fkyeongseo90%2Fmagazine-in-lapidem&count_bg=%23D8A5FF&title_bg=%234B0668&icon=github.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## Introduction

배포 주소: https://d3p8thwnimt9c5.cloudfront.net/index.html

## Tech Stacks

### Front-End

![html5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Distribution

![amazons3](https://img.shields.io/badge/amazon%20s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![amazonaws](https://img.shields.io/badge/amazon%20CloudFront-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![amazonaws](https://img.shields.io/badge/amazon%20Certificate%20Manager-4053D6?style=for-the-badge&logo=amazonaws&logoColor=white)

### Communication

![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)
![Visual Studio Code - Live Share](https://img.shields.io/badge/Live%20Share-008ED2?style=for-the-badge&logo=slideshare&logoColor=white)

### Environment

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)

## Screens

|                             메인 페이지                             |                          서비스 페이지                           |
| :-----------------------------------------------------------------: | :--------------------------------------------------------------: |
| <img width="329" src="./assets/image-for-readme/Frontpage.jpeg"  /> | <img width="329" src="./assets/image-for-readme/Services.svg" /> |

|                         스튜디오 페이지                         |                         블로그 페이지                         |
| :-------------------------------------------------------------: | :-----------------------------------------------------------: |
| <img width="329" src="./assets/image-for-readme/Studio.svg"  /> | <img width="329" src="./assets/image-for-readme/Blog.jpeg" /> |

## Cloud Architecture

- AWS CloudFront
- Amazon S3
- AWS Certificate Manager

<img src="./assets/image-for-readme/frontend-cloud-architecture.png">

## Others

### Period

2024.04.22 - 23 (2 days)

### Members

|                                      최경서                                      |                                      김현아                                       |
| :------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: |
| <img width="160px" src="https://avatars.githubusercontent.com/u/59429729?v=4" /> | <img width="160px" src="https://avatars.githubusercontent.com/u/122499274?v=4" /> |
|                  [@kyeongseo90](https://github.com/kyeongseo90)                  |                     [@hyuna333](https://github.com/hyuna333)                      |

### Coworking Rules

- commit 자주 날리기
- commit convention
  - feat: 새로운 기능
  - fix: 버그 수정
  - docs: 문서 변경
  - style: EOL, 세미콜론 등 코드에 대한 변경이 아닌 컨벤션에 관련된 변경
  - refactor: 프로덕션 코드 리팩토링
  - test: 테스트 추가, 리팩토링 테스트 ( 프로덕션 코드 변경 없음 )
  - chore: 빌드, 릴리즈, 설정 등의 변경 ( 프로덕션 코드 변경 없음 )
- CC: 한국말 설명
- 함수명(클래스, 아이디) : 케밥 케이스
- 브랜치명: feat/페이지 명
- 상대방 PR comments 달아주기
