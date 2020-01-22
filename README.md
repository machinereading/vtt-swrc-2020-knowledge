# VTT SWRC Knowledge
카이스트 시맨틱웹첨단연구센터(SWRC)의 VTT 프로젝트 세계지식(인물간 관계) 데이터 입니다. 인물간 관계에 대한 정의 및 데이터에 대한 설명으로 이루어집니다.

## 관계정의

추출하려는 인물간 관계에 대한 정의입니다.  

3개의 대분류(Family Status, Organization, Private)으로 이루어져 있습니다.

- Family Statue membership: 가족 관계
  - 가족 관계 혹은 정주 방식에 따른 가족 분류
    - 핵가족, 결혼, 입양, 관계의 변화(이혼, 사별) 등
- Private relationships: 신체적, 정서적 친밀감과 관련된 대인 관계
  - 친구 관계, 가족, 지인
  - 성적인 관계
  - 비 성적인 관계 등
- Organization relationships: 공적인 관계
  - professional or educational
  - 동료 혹은 상하 관계

 각각 내부에 중분류, 소분류로 나누어져있습니다. 소분류에 해당 관계가 추출될 수 있는 예시가 들어있습니다.

## 인물관계사전

또! 오해영 드라마 주요 20인이 사이에 발생하는 모든 관계에 대한 사전입니다. 

- 인물별로 1~20 까지 id가 부여 되어있습니다.
- 표 내의 내용은 드라마 전체에서 행id 인물, 열id 인물 간 발생하는 관계입니다. 
- 관계는 `관계정의.docx`에서 정의된 관계를 사용합니다.

## rel.tsv

드라마에서 발생하는 관계를 주석한 데이터입니다.

- 4개의 열로 이루어져 있습니다.
  - Relation: 인물들 간 발생한 관계
  - 인물1: 관계를 이루는 주격 인물
  - 인물2: 관계를 이루는 목적격 인물
  - 씬: 해당 관계가 발생한 씬 id

- 범위: 에피소드 1-5