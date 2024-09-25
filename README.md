# 📖 팀 회고 작성 서비스 웹 Past-Forward


![ver1_mainPage](https://github.com/donga-it-club/past-forward-frontend/assets/138123134/b19cc815-677f-42e8-ab35-f7acfa4bf988) <br>

<div align='center'>
[💻 사이트 바로가기](https://www.pastforward.link/)
  <br>
</div>
<br>


## 프로젝트 소개

- Past-Forward는 팀원들과 회고 작성을 할 수 있는 웹페이지입니다.
- 회고 템플릿(총 두가지)에 따라 다른 주제로 회고 카드를 네가지 섹션으로 나누어 작성이 가능합니다.
- 팀원 초대 링크를 통해 팀원들을 초대하고 관리(초대 및 삭제 기능)할 수 있습니다.
- 다양한 유저들을 마음에 드는 회고 카드에 좋아요를 누르거나 댓글을 작성할 수 있습니다.

<br>

## 팀원 구성

<div align="center">

|                                                                **주은진**                                                                 |                                                                 **공아영**                                                                  |                                                            **김보경**                                                            |                                                                  **이가은**                                                                  |                                                                  **권미정**                                                                  
| :---------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars.githubusercontent.com/u/91419384?v=4" height=150 width=150> <br/> @dunedine](https://github.com/dunedine) | [<img src="https://avatars.githubusercontent.com/u/85187658?v=4" height=150 width=150> <br/> @gongboogi](https://github.com/gongboogi) | [<img src="https://avatars.githubusercontent.com/u/103033741?v=4" height=150 width=150> <br/> @BooGyya](https://github.com/BooGyya) | [<img src="https://avatars.githubusercontent.com/u/102865074?v=4" height=150 width=150> <br/> @gaeun0915](https://github.com/gaeun0915) | [<img src="https://avatars.githubusercontent.com/u/84905321?v=4" height=150 width=150> <br/> @kmj-1616](https://github.com/kmj-1616) 

</div>

<br>

## 1. 🛠 기술 스택
- 데이터 분석 도구: GA4, 루커 스튜디오
- 버전 및 이슈 관리: Github, Github Issues, Github Project
- 협업 도구: Discord, Notion, Slack
- 디자인 도구: [Figma](https://www.figma.com/file/zJaBNvTvLlG0d9h5TILICj/Past-Forward-Web-Site?type=design&node-id=1157%3A6652&mode=design&t=eI1Pvgp8EpiHQgEA-1)
<br>
  
## 2. 프로젝트 기간
- (ver1) 1차 프로젝트 기간: 2024-02-01 ~ 2024-05-04
- (ver2) 2차 프로젝트 기간: 2024-05-05 ~ 2024-08-30
<br>

## 3. ver1까지의 프로젝트 진행 내용
- 데이터 수집: GA4 및 구글 태그매니저(GTM)를 통해 사용자 데이터를 수집
- 분석 내용: 사용자 수, 이탈률, 트래픽 소스, 회원가입 경로, 회고 생성 이벤트, 로그인 이벤트 등 다양한 사용자 행동 데이터를 분석하였습니다
  
### 데이터 수집: 사용자 발생 전(서비스 배포 전) 측정 전략 수립 및 데이터 분석 설계 진행
- 측정 전략 수립
  - 분석하고자 하는 핵심 질문을 도출하고 기획
  - 필요한 지표를 정리하여 측정 전략을 체계적으로 수립
- 데이터 분석 설계
  - 주요 질문을 GA 보고서와 연계하여 카테고리화
  - GA와 웹사이트의 연동 방법 및 추가 설정을 정리하여 데이터 수집 체계를 구축
- GA4와 웹사이트 연결 작업
  - GA4 태그 및 트리거 설정을 통해 웹사이트와의 연결을 진행
  - 관리 시트를 작성하여 설정 과정의 체계적으로 관리
  - GA4 연결 관리 시트 링크: [GA 이벤트(태그 및 트리거) 관리 시트](https://docs.google.com/spreadsheets/d/14MOWROUp9OW6DUsmbUVyK9VuWGpBPQ2UsueqGhLjG64/edit?usp=sharing)
<br>

### 데이터 분석: 서비스 배포 이후 데이터 분석 진행
- 분석 보고서 작성 ([분석보고서 링크](https://docs.google.com/document/d/1YIK8ATV6fXiJJOoxQC8R1zgp7KC6C7jnD5GATIa2ESY/edit?usp=sharing))
- 분석 내용
  - GA4 기반 데이터 수집: 실시간으로 웹사이트 사용자 행동 데이터를 수집하여 분석
  - 트래픽 소스 분석: UTM 파라미터로 유입 경로를 추적하고 마케팅 효과를 평가
  - 사용자 행동 분석: 회원가입, 로그인, 회고 카드 기능 분석을 통해 사용자 경험을 분석
    
- 개선사항 제안서 작성 ([제안서 링크](https://docs.google.com/document/d/11Xnw9UDOTaT4WG8D9xlwKhkFWIV3uwUyqdcwq2vawVs/edit?usp=sharing))
- 제안서 내용
  - 배포 관련 마케팅 이벤트 제안 및 활성 사용자 수 증대 방안
  - 팀 회고 내 팀원 초대기능인 QR버튼의 클릭률 분석 제안
  - 페이지 경로 태그 수정 제안
  - 회원가입 페이지 URL 경로 구분 제안
  - 헤더 카테고리 'Template' 명칭 변경 제안
  - 모바일 친화적인 사이트로 개선 제안 (반응형 웹디자인)
<br>

 ## 4. ver2까지의 프로젝트 진행 내용
  ![ver2_mainPage](https://github.com/donga-it-club/past-forward-data/blob/main/img/VER2%20PastForward%20%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8.gif) <br>
- GA4 심층 데이터 분석: 신규 유입자와 재방문자 비율, 이탈률 등 Ver1 데이터를 기반으로 정교한 분석 진행
- A/B 테스트 진행: 회원가입 버튼명에 관한 A/B 테스트를 진행
- 대시보드 구현: 루커 스튜디오로 첫 사용자 소스, 활성 사용자 비율, 반복 방문자 비율 등 주요 지표를 시각화하여 데이터 분석 효율성을 높임.

### A/B 테스트 진행 ([A/B 테스트 보고서 링크](https://docs.google.com/document/d/1vNjZ7-qZNG4lWLMeBRapnKCPuC3rgaj-Dl0zEqLZMh0/edit?usp=sharing))
- 기존 회원가입 버튼 문구가 직관성이 부족해 전환율이 낮을 것이라는 가설에 근거하여 UX 라이팅을 다르게 실험을 진행함
- B안은 A안보다 안정적인 클릭률과 회원가입 전환을 보였으나, 전환율 차이는 크지 않았음을 확인함
<br>

### 대시보드 구현 ([대시보드 링크](https://lookerstudio.google.com/reporting/9e64bca2-9823-49a3-9526-e060142334da))
- GA4를 활용해 수집한 사용자 데이터를 루커스튜디오를 활용하여 주요 지표를 시각화하는 대시보드를 구현함
- 주요지표
  - 첫 사용자 소스/매체(마케팅 유입 분석)
  - 사용자 활성화 및 리텐션 분석
  - 반복방문자 비율
  - 신규 방문자 재방문자 비교 분석
  - 총 방문자 수
  
  ![대시보드화면](https://github.com/donga-it-club/past-forward-data/blob/main/img/%EB%8C%80%EC%8B%9C%EB%B3%B4%EB%93%9C%20%EA%B5%AC%ED%98%84.gif) 
<br>
 
