# dau
웹프로그래밍 학습을 위한 레포지토리

### 1일차
- vscode 및 git 설치
- html 생성
- git 과 vscode 연동
- html, web site 주소 얻는법
- setting -> pages -> none을 main 으로 변경후 save
- https://withdatastory.tistory.com/19
- www.w3schools.com
### 2일차 필기
- html 구조
  - 계층적인 구조
  - element의 모임(집합)
  - < > 내용 </ > => element

![image](https://user-images.githubusercontent.com/97490561/190095663-9605aacb-d24d-42ba-8e50-23b6a9f5fa3f.png)
![image](https://user-images.githubusercontent.com/97490561/190095700-ac93137c-e7de-4060-95e9-c2590e9f455c.png)
![image](https://user-images.githubusercontent.com/97490561/190095831-4f91d8fa-ef5b-4049-88cd-e64996b7df7c.png)
![image](https://user-images.githubusercontent.com/97490561/190096523-26161330-c0b0-4289-bba8-348a7e6f0c7f.png)

- Document -> html -> head -> meta, title
-                  -> body -> h1, ul
-                                 ul -> li
### 3일차 필기
- html : element의 모임
  - <tag 속성 = "값" .. > 내용 </tag> : element
  - 내용이 없으면 종료 테그가 없음 (empty tag) : <br> <hr> <img><meta>
  - 계층적 구조
- emmet : (자식)+ (형제)^ (부모)*(반복){} 텍스트 $ {일련숫자}
- 컨테이이너 : 콘텐츠를 담는
  - header, nav , section, article ,aside, footer --> 레이아웃(sementic)
- div : 공간분할
- #: id(이름이 유니크해야함)     . : class (동일한 이름 사용가능)

 span

- 글꼴: b,i,h1~h6,p,br ~~~

- 이미지 : <img src=" "/>
- 목록태그 : ul ,ol , dl
             li

- table 테그 : tr(행),th(제목열), td(내용열)
- table>te>th*3^tr*3>td*3
- 멀티미디어 : <audio src=""> <video src="">
  유튜브 삽입 : 오른쪽 -> 소스코드복사 -> html문서에 
### 4일차 필기
![image](https://user-images.githubusercontent.com/97490561/191920135-daa06036-ee05-43e7-85f8-4a7f597d4de8.png)


![image](https://user-images.githubusercontent.com/97490561/191919710-fde0d4ad-16f8-4226-b767-546a90513232.png)

  
![image](https://user-images.githubusercontent.com/97490561/191920255-d2e64da0-4a90-4f06-9f03-323c97f7120a.png)
  
  
![image](https://user-images.githubusercontent.com/97490561/191920645-2c624f3e-2f2e-44c4-87dd-772561b81b64.png)


### 5일차 필기
- CSS
< css3 >
문서의내용과 구조는 html5
문서의 디자인은 css3


스타일에 선언하는 형식이 중요
selector=선택자 {

}

선택자에는 * , 태그명 ,  .클래스명 , #아이디명 


!!! css은 레이아웃(flex,grid) 잡아주는게 제일 중요하고
1.형식(css어떻게 구조 잡는지) 2.박스 3.단위(px,%,rm,rem) 4.레이아웃 만 할 줄 알면 된다.

<css 계층구조 해당범위>
> : 자식 ( 부모의 바로 밑에 자식만 해당 )      {자식선택자 ,  자손선택자는 차이가 있음}
스페이스 : 자손( 내 손주도 자손으로 해당 )


### 11월 11일 (기말 시험 공부)
- beck-end: .net ASP, PHP, jsp&Servlet , 파이썬의 디장고
- MVC : django dhl
  M : Model (데이터베이스)
  V : View는 django의 Templates(화면에 보여주는 내용)
  C : Controller을 의미
- MVT : django
  M : Model (데이터베이스)
  V : View.py => 처리함수
  T : Templates => 화면에 보여주는 내용
