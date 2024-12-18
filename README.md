<div align="center">*** 프로젝트 구현 세부 기능에 대해서는 담당한 파트 부분만 기재하였습니다. ***</div>
<br>
<br>
<br>

------------------------------------------------------------------------------------------------------------------------------------
<br>
<br>
<br>

<div align="center">
<h2>[2024] DDIT_21기 4조 최종프로젝트</h2>
SaaS형 통합 그룹웨어 플랫폼이며 사용자 친화적 인터페이스와  <br>
조직 내 협업과 소통 극대화가 되는 SaaS형 통합 그룹웨어 플랫폼, <br>
GrouBear입니다.<br>
 

</div>

## 목차
  - 1. [개요](#개요) 
  - 2. [프로젝트 설명](#프로젝트-설명)
  - 3. [ERD Cloud](#ERD-Cloud)
  - 4. [프로젝트 내에서의 역할](#프로젝트-내에서의-역할)
  - 5. [프로젝트 구현 기능 상세](#프로젝트-구현-기능-상세)
    

## 개요
<div align="center">
<h4>프로젝트명</h4>
GrouBear
</div>
<div align="center">
<h4>프로젝트 기간</h4>
2024.09.10-2024.11.18
</div>
<div align="center">
<h4>개발 툴</h4>
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">&nbsp
<img src="https://img.shields.io/badge/dbeaver-82923?style=for-the-badge&logo=DBeaver&logoColor=white">&nbsp
</div>
<div align="center">
<h4>개발 언어</h4>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">&nbsp
<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">&nbsp
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">&nbsp
<img src="https://img.shields.io/badge/openjdk-5586A4?style=for-the-badge&logo=Java&logoColor=white">&nbsp
<img src="https://img.shields.io/badge/jsp-1572B6?style=for-the-badge&logo=JSP&logoColor=white">&nbsp


</div>
<div align="center">
<h4>팀원</h4>
<table>
  <tbody>
    <tr>
      <td align="center"><b> 권기혁 </b><br />PL</td>
      <td align="center"><b> 김연희 </b><br />TA</td>
      <td align="center"><b> 강성연 </b><br />AA</td>
      <td align="center"><b> 윤다빈 </b><br />QA</td>
      <td align="center"><b> 이은재 </b><br />DA</td>
      <td align="center"><b> 이현수 </b><br />BA</td>
    </tr>
  </tbody>
</table>
</div>


## 프로젝트 설명
<br>

▣ 최종프로젝트
프로젝트명 : 그루베어 (SaaS 그룹웨어 시스템)<br>
<br>
*** 그룹웨어 관리자 홈피드
<br>
![image](https://github.com/user-attachments/assets/6a17283f-47b2-42a6-90db-6a13b11961d1)
<br>
<br>

------------------------------------------------------------------------------------------------------------------------------------
<br>
*** 사용자 홈피드
<br>

![image](https://github.com/user-attachments/assets/c8d79330-70b5-42c4-84f5-bef763a68eea)
<br>
<br>


▣ 프로젝트 요약
* ‘그루베어’ 프로젝트의 목표 : SaaS형 통합 그룹웨어 플랫폼 개발.
1. 사용자 정의 기능 
: 개별 기업 및 부서의 필요에 맞춰 자유롭게 편집할 수 있는 커스터마이징 메뉴
2. 직관적인 인터페이스 
: 매뉴얼이 없어도 헤매지 않는 직관적인 사용자 친화적 인터페이스
3. 유기적 연결성 
: 다양한 기능들 간의 유기적인 연계를 통해 조직 내 협업과 소통의 효율성 향상
 이러한 목표를 통해 "이 그룹웨어, 정말 쉽다!"라는 메시지를 실현하고자 하며, 사용자들이 편리하게 소통하고 협력할 수 있는 플랫폼을 구축하는 데 중점을 둠.

* 주요 기능 (*는 프로젝트 담당 파트)
1. 인사 관리
2. 근태 관리
3. 양식 관리 *
4. 증명서 관리 *
5. 전자결재
6. 프로젝트
7. 일정
8. 클라우드 *
9. 시스템 공지 / QnA *
10. 통계
11. 차량예약
12. 시설예약
13. 화상채팅
14. 날씨/메뉴추천 *
15. 커뮤니티
16. 실시간알림

 특히, 직관적인 대시보드와 각 업무 기능의 접근성 강화를 통해 업무의 생산성과 효율성을 높일 것으로 기대하며, 
 이러한 통합 플랫폼을 통해 기존의 복잡한 업무 프로세스 개선 및 직원 만족도를 향상시키는 것을 궁극적인 목표로 함.


|부서별 기능|시설 등록|양식 불러오기|양식 수정|
|---|---|---|---|
|![부서별기능](https://github.com/user-attachments/assets/7e19766a-52be-4c5a-82a5-c0f13193c6ee)|![시설등록](https://github.com/user-attachments/assets/e5327c68-e5c2-44d0-8765-1b62b29141df)|![양식관리1](https://github.com/user-attachments/assets/f7e1a445-319b-4d8c-a46f-b799e672f43f)|![양식관리2](https://github.com/user-attachments/assets/49915d13-9b67-46b7-9398-2aeebe53f47c)

|전자결재|차량등록|클라우드|프로젝트|
|---|---|---|---|
|![전자결재](https://github.com/user-attachments/assets/2736f74d-ce77-4319-ac3c-1a1aed98242a)|![차량등록](https://github.com/user-attachments/assets/05ffcb31-2b07-44b1-b669-95f283041213)|![클라우드](https://github.com/user-attachments/assets/0c9d7302-8fd4-4539-aa51-60ec609c98a4)|![프로젝트](https://github.com/user-attachments/assets/3edc6c4d-20ff-4a4d-b9f5-c683e912dd05)

<br>
<br>

------------------------------------------------------------------------------------------------------------------------------------

<br>
<br>

## ERD Cloud

![image](https://github.com/user-attachments/assets/cd1a63ad-963f-412d-be88-3e2950aade33)

<br>
<br>

------------------------------------------------------------------------------------------------------------------------------------

<br>
<br>

## 프로젝트 내에서의 역할 : TA / 보조업무 : DA

- 담당 파트 : 양식 관리, 증명서 발급, 클라우드, 공지사항, QnA, 오늘의 날씨 및 날씨 메뉴 추천 & 음식점(메뉴) 지도 검색 

- TA로서 프로젝트 개발 중, 팀원들이 기능 구현에 어려움을 겪는 부분에서 아이디어를 제공하고 코드 및 SQL을 함께 작성하는 등의 담당한 역할에 대한 기본적 책임을 충실히 함
- 프로세스 정의서를 작성하면서, 대분류로 구성되어 있던 파트별 기능을 소기능 단위로 세부적으로 명확하게 분류하여 공유함 
- CKEditor를 사용하여 파라미터를 사용해 양식을 등록 및 불러오기를 할 수 있는 기능을 만들고 팀원들에게 배포함
- JSTree를 이용한 양식 목록과 클라우드 폴더 목록을 출력하는 모듈을 만들고 팀원들에게 Jstree의 사용법을 안내하여 전자결재, 증명서 등 다양한 기능에 사용할 수 있도록 함 
- 화면구성 사이드바의 고정과 메뉴 활성화를 위한 공통 css코드와 각 jsp별 공통 페이지 코드를 만들어 배포함으로써 UI의 일관성을 확보함
- 프로젝트에서 공통으로 사용할 Sweetalert2의 성공, 실패, Comfirm별 코드를 구성하여 팀원들에게 배포함으로서 프로젝트 UI의 통일성을 줌
- 기상청 단기예보 API를 사용하여 오늘의 날씨를 구현하고, 날씨에 따라 자동으로 추천되는 메뉴의 이름을 카카오 Map API에 검색하여 회사 주변의 해당 메뉴를 판매하는 음식점의 목록을 띄움으로서 2개의 API를 연계하여 활용함
- 프로젝트에서 사용할 목적으로 구매한 웹페이지 템플릿을 분석하여 가용할 수 있는 아이콘, 클래스, CSS를 제공하는 API, 유용한 컴포넌트 기능, ApexChart 등, 사용 방법과 목록에 대한 정보를 제공함 
- 메인 홈피드에서 사용할 게시판 위젯, 알림 및 카운트 위젯을 만들어 원하는 팀원들이 사용할 수 있도록 공유함
- 클라우드 및 공지사항 파트에서 개별 선택 파일 다운로드 및 폴더와 파일을 포함한 ZIP 파일 다운로드, 이미지 미리보기를 구현함
- 사용자 입장에서의 명확한 정보 전달과 사용자 경험 개선을 위해 모든 생성, 수정, 삭제 기능에 알림창을 추가하여 피드백을 제공함으로써 즉각적으로 확인이 가능하도록 함

* 보조업무 : DA
- 각 기능에 대한 분배를 완료한 뒤, 첨부파일 테이블, 공통코드 테이블, 사용자 권한 테이블 등의 공통 테이블을 구성하고 상의하여 추가함
- 공공데이터 공통 표준 용어를 기반으로 컬럼명을 구성하였으며, 전체적으로 컬럼명이 잘못 작성된 것이 없는지 검수함
- 서로 충돌하는 부분의 컬럼이나 테이블마다 불필요하게 중복되는 컬럼에 대하여 팀원들과 피드백을 나눈 후 수정 반영함
- 클라우드 테이블을 효과적으로 화면 및 다운로드를 구성하기 위하여 클라우드함, 클라우드 폴더, 클라우드 파일 3개의 테이블을 계층형으로 구현함

<br>
<br>

------------------------------------------------------------------------------------------------------------------------------------

<br>
<br>

## 프로젝트 구현 기능 상세
 : 1. 양식 관리, 2. 증명서 발급, 3. 클라우드, 4. 공지사항, 5. QnA, 
   6. 오늘의 날씨 및 날씨 메뉴 추천 & 음식점(메뉴) 지도 검색 
   
<br>
<br>

<h3>▷ 1. 양식 관리</h3>

![image](https://github.com/user-attachments/assets/17066966-fd76-4a06-a34e-b2dff62a16d7)

- 시스템 관리자가 해당 SaaS를 사용하는 모든 기업들에게 공통적으로 사용할 수 있도록 기본적인 형식의 양식을 등록하여 배포할 수 있으며, 기업 관리자도 직원들에게 배포할 수 있는 자사만의 양식을 등록할 수 있음.
- 양식명 오른쪽에 tooltip을 활용하여 선택적으로 주석을 달 수 있도록 하여 사용자에게 해당 양식의 용도에 대한 이해를 돕고 추가 정보를 쉽게 얻어 직관성을 높일 수 있도록 함.

![image](https://github.com/user-attachments/assets/b476872f-9f6e-4459-8524-b5c23abf5457)
![image](https://github.com/user-attachments/assets/05f08cd8-128b-4616-bc0e-a9456e4ef697)
![image](https://github.com/user-attachments/assets/1fa3d462-3dbe-4d69-91e9-8921ce46b950)

   
- 증명서, 전자결재 등 양식을 등록할 때, 표 / 문단 등을 활용하여 양식을 만든 후, 데이터가 들어가야 할 부분에 제공되는 파라미터를 넣으면 추후 증명서를 발급하거나 전자결재를 기안할 때 사용자의 정보가 자동으로 매핑되는 것을 확인할 수 있음. 
- 증명서 및 전자결재 등의 양식의 목록은 JSTree를 사용하여 계층형으로 출력될 수 있도록 함. 
- 양식을 매번 처음부터 만드는 번거로움을 줄이기 위해 양식 불러오기를 통해 기존에 등록한 양식을 불러와서 변형하여 사용할 수 있도록 함. 
- 양식 종류는 상위 양식을 선택하여 해당 상위 양식의 하위에 세부 종류를 추가할 수 있도록 함.

<br>
<br>

<h3>▷ 2. 증명서 발급</h3>

![image](https://github.com/user-attachments/assets/0b4cb401-d9ae-4de2-aef6-028f8d2852b2)

- 사원은 본인의 증명서를 기업의 권한을 가진 관리자 (기업 관리자, 인사팀 등)에게 요청할 수 있음.
- 권한을 가진 관리자 (기업 관리자, 인사팀 등)는 특정인의 증명서를 자체 발급할 수 있음.

![image](https://github.com/user-attachments/assets/c45c3fde-500c-490a-ad06-81fe08e36b4c)

- 요청받은 담당자는 자동으로 매핑되는 정보가 옳게 됐는지 확인 후, 변경 및 추가 정보가 있으면 기존에 매핑된 정보를 변경 후, 증명서를 본인에게 발급할 수 있음. 

![image](https://github.com/user-attachments/assets/d5edb656-9002-432d-bcf1-62c18a1ba24a)

- 발급된 증명서는 회사의 직인이 추가되어 발급되며, 해당 증명서는 인쇄, PDF 저장이 가능함.

- (코드) 불러온 양식과 Ajax로 가져온 사원의 정보를 치환하는 코드
![image](https://github.com/user-attachments/assets/5ab79b0c-eac5-4d6e-83aa-f091778682ed)


- 증명서 또는 전자결재에서 발급 / 기안할 양식을 선택한 후, 정보를 매칭할 사원을 선택하여 요청.
- 다수일 경우 (증명서에 한해) 배열의 0번 인덱스의 사원의 정보만 가져옴.
- 기존에 선택한 양식 내용을 불러온 후, 양식 내에서 정규 표현식으로 #{key} 형식으로 된 문자열을 찾음.
- 해당 문자열 내의 key와 json 형식으로 받아온 객체의 key가 같다면 정보를 치환하도록 구현함.

<br>
<br>

<h3>▷ 3. 클라우드</h3>

![image](https://github.com/user-attachments/assets/905779fd-91a1-4a9a-8b35-1b3d6ce91754)

- 클라우드함을 전사, 부서, 개인 클라우드함으로 세분화하여 구성하고, 기능들이 사용자에게 직관적으로 인식될 수 있도록 간소화된 UI를 구성하여 복잡한 프로세스를 최소화함.
- 기본적인 기능의 구성 : 파일 업로드(Dropzone), 폴더 이동, 새폴더 생성, 선택 다운로드, 전체 다운로드(zip), 삭제, 미리보기

![image](https://github.com/user-attachments/assets/4114d97d-da58-41a8-a26c-b3c12e9d89e2)
![image](https://github.com/user-attachments/assets/2619e61b-bba8-4800-afff-85a3ef38b630)


- 전체 폴더 목록을 JSTree의 계층형 구조로 구현하여, 사용자가 업로드할 파일이나 파일/폴더의 이동 위치를 쉽게 선택할 수 있도록 하였으며, 원하는 위치의 폴더를 클릭하면 해당 폴더 내부로 전환되도록 함.
- 폴더를 생성 / 수정시 직급에 따른 열람 권한을 부여하여 보안성을 높이고, 전체보기에서 열람 권한이 없는 폴더는 자물쇠 아이콘으로 별도 표시함으로써 사용자의 직관성과 가독성을 높임.

<br>
<br>

<h3>▷ 4. 공지사항</h3>

![image](https://github.com/user-attachments/assets/475564a8-0c97-4165-82d0-39ee39f48627)
![image](https://github.com/user-attachments/assets/74bfb586-803a-47ad-8c86-a7a6b718b15c)


- 필수 공지를 만들어 체크박스로 상단 고정을 선택적으로 할 수 있도록 함
- 드롭존을 활용하여 파일 끌어서 추가하기, 템플릿 제공 js를 활용한 전체 파일 삭제를 구현함
- 파일당 최대 파일 크기 2MB와 1회당 업로드 할 수 있는 파일 개수를 10개로 제한하고 드롭존 라이브러리를 활용하여 유효성을 체크함

![image](https://github.com/user-attachments/assets/7d63d880-8943-45be-8c08-ed28fd8ad521)


- 공지 상세 페이지에서 개별 파일 다운로드를 할 수 있도록 하고, 더불어 전체 파일을 한번에 zip으로도 다운받을 수 있도록 구현함
- CKEditor API를 사용하여 글쓰기에 테이블, 문단, 진하기 등의 특정 효과를 줄 수 있도록 함

<br>
<br>

<h3>▷ 5. QnA</h3>

![image](https://github.com/user-attachments/assets/5ab9e01b-78d0-424a-bab6-b3c143c7f098)
![image](https://github.com/user-attachments/assets/f8f35185-2190-4740-af97-7f3ff552cf31)


- 시스템 관리자는 그룹웨어에 대한 QnA 게시글에 댓글의 형식으로 답변을 작성할 수 있음.
- QnA 카테고리별로 구분하여 목록을 표출하고, 상단 카테고리별 키워드를 클릭하면 해당 카테고리의 글만 볼 수 있도록 함.
- 대기중과 답변완료가 섞여있는 목록 중에서, 대기중만 보기를 체크하면 미답변 상태인 게시글만 노출되도록 함.
- 상단 카테고리 키워드에 미답변 게시물의 갯수를 select하여 표시하여 현재 QnA의 상태를 직관적으로 명확하게 알 수 있도록 함. 
- QnA 질문자가 비밀글 여부를 선택할 수 있도록 하였고, 비밀글일 경우 시스템 관리자와 작성자 본인만 상세 페이지를 확인할 수 있도록 함. 


<h3>▷ 6. 오늘의 날씨 및 날씨 메뉴 추천 & 음식점(메뉴) 지도 검색 </h3>

![image](https://github.com/user-attachments/assets/acfad661-0e4b-4bda-bac0-4a6a929d54eb)
![image](https://github.com/user-attachments/assets/afb6719d-445d-478e-a9c3-cc84c4c52ece)

- 로그인한 사용자의 회사 좌표를 기준으로 기상청 단기예보 API 정보를 받아온 뒤, 1일 평균치로 값을 환산하여 3일간의 날씨 아이콘을 표출함.
- 랜덤한 메뉴 추천과 오늘의 날씨에 따른 메뉴추천 2가지를 구성함.
- 날씨메뉴 추천을 누르면 어울리는 날씨에 맞춰 DB에 넣어놓은 메뉴들 중에 랜덤으로 추천되어 모달창으로 뜨도록 함 .

![image](https://github.com/user-attachments/assets/af70dbd2-bc79-4635-8e54-7d54dbbeba1c)

- 모달창을 닫으면 자동으로 하단 스크롤이 내려가며, 추천된 메뉴가 왼쪽에 뜨고 카카오맵에 자동으로 검색되어 추천된 메뉴를 판매하는 회사 주변의 식당 목록을 출력함.
- 마커와 목록을 클릭하면 해당 카카오맵의 상세페이지로 넘어가도록 카카오맵 전용 id를 받아 파라미터로 사용하여 a링크를 구현함.

<br>
<br>

<h3>▷ + 홈피드용 소형 위젯 구현 및 디자인 배포</h3>

![image](https://github.com/user-attachments/assets/f0655712-aaba-4e00-9fdb-5801b37caab9)
![image](https://github.com/user-attachments/assets/ae448fab-dc8f-474b-9677-c35573f19bda)
![image](https://github.com/user-attachments/assets/3295eff6-10bd-4f86-b300-20d9e819e9d5)

- 시스템 관리자의 QnA 미답변 게시물 개수, 기업 관리자의 사원 증명서 요청관리 현황, 전체 Actor의 공지사항 위젯을 만들고, 해당 위젯 디자인 골조를 팀원들이 가져다 쓸 수 있도록 공유함. 

<h3>* 기타</h3>

![image](https://github.com/user-attachments/assets/879f07c9-231e-4c88-867d-2aa96e9c6e2f)

- tiles를 기반으로 구성한 header.jsp에 바로가기 위젯을 추가하여, 사용자들이 좀 더 편리하게 필요한 기능에 접근할 수 있도록 사용자 경험을 개선함.

