# TextTransTool
ETRI 이중전사규칙 텍스트 라벨링 작업에 도움이 되는 툴<br>

※ 본 프로그램의 무단수정 및 배포를 금합니다. <br>
※ 문의 시 sjy777star@gmail.com 으로 연락 바랍니다. <br>
※ Ver2.0 Latest Update Date 2020.12.21<br>

<How To Use>
※ '이중전사툴' 은 본인이 만든 프로그램으로 윈도우 디펜더 등의 보안창이 뜰 수 있으나 디펜더 해제 후 사용하시면 됩니다. <br>
※ 이중전사하고자 하는 텍스트를 공백없이 입력 후 Enter 혹은 Enter(변환) 키를 누르시면 변환이 됩니다.<br>
※ 짧은 개발 기간과 발음 전사의 특성상 모든 케이스를 충족하지 못하는 점 양해부탁드립니다.<br>
※ 폴더 압축 해제 후 폴더 내에 존재하는 TxtTransTool-바로 가기 프로그램을 폴더 내에서 사용하시거나,<br>
TxtTransTool.exe의 바로가기를 폴더 내에서 직접 우클릭하여 생성 후, 바탕화면이나 편한 경로에 두시고 사용하시면 됩니다.<br>
<br>
  
## Function
<Ver2.0 Update Function>
* 숫자 처리(기존 Ver1.0 숫자 처리 기능 보완 --> 억 단위까지 가능, 소수 처리 가능, 1의 자리 수에 0이 있을 경우 처리 가능)
  - ex. (12345672.124)/(천 이백 삼십 사만 오천 육백 칠십 이 점 일 이 사)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102712558-83333200-4305-11eb-9d01-95867ad7cba6.png)<br>

* 알파벳 발음 전사(기존 Ver1.0 기능 유지)
  - ex. (EBS)/(이 비 에스)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102716823-9d7b0900-4321-11eb-92fb-c53282651f71.png)<br>

* EBS 강의 보기 등에서 자주 사용되는 한글 자음 ㄱ~ㅎ 처리 가능 
  - ex. (ㄱ)/(기역)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102716850-ca2f2080-4321-11eb-99e2-8a1a493b9ee6.png)<br>
  
* 자음모음 모두 존재하는 한글과 숫자 혼합 처리 가능
  - ex. (1948년)/(천 구백 사십 팔 년)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102718052-6872b480-4329-11eb-9cae-7f413ec7e6f5.png)<br>
  
* 알파벳과 숫자 혼합 처리 가능
  - ex. (C16)/(씨 십 육)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102718696-d1a7f700-432c-11eb-89c1-5709d9da8a5d.png)<br>
  
* 한글과 알파벳, 숫자 혼합 처리 가능
  - ex. (3x명)/(삼 엑스 명)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102718688-c0f78100-432c-11eb-9d78-ab142d155ae7.png)<br>
  
* 0~99 범위 내 정수는 한글기수, 영어기수, 한글서수 발음으로 동시 전사 출력하여 용도에 따라 선택 사용 권장
  - ex. (H2O)/(에이치 이 오)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(H2O)/(에이치 투 오) --> 선택
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(H2O)/(에이치 두 오) 
  - ex. (4C2)/(사 씨 이) --> 선택 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(4C2)/(포 씨 투) 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(4C2)/(네 씨 두) 
  - ex. (9개)/(구 개) 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(9개)/(나인 개) 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(9개)/(아홉 개) --> 선택 <br>
  ![image](https://user-images.githubusercontent.com/46860669/102718153-f9499000-4329-11eb-9b0c-dd82829f3d19.png)<br>

 * 날짜 처리 가능한 소수의 경우 점을 기재하지 않은 상태도 동시 전사(한국사의 숫자만으로 이루어진 기념일 등 특정 의미가 있는 텍스트 처리)
   - ex. (10.26)/(십 이 육) 
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(10.26)/(십 점 이 육)<br>
   ![image](https://user-images.githubusercontent.com/46860669/102718205-46c5fd00-432a-11eb-8f3a-b0585f0ca660.png)<br>
        
 * 자주 사용되는 일부 구어체를 표준어화('요', '요게', '요렇게', '요거', '요건', '요런', '요거는', '요기', '고', '그', '고건', '고걸', '고렇게', '그죠', '그쵸','조렇게')
   - ex. (그렇죠)/(그쵸)<br>
  ![image](https://user-images.githubusercontent.com/46860669/102710691-68f25780-42f7-11eb-95fb-e4d4def2cb6d.png)<br>
  
  * 한글 입력 시 영어발음 전사 또는 영어 번역 전사 가능
  - ex. (cloud)/(클라우드) <br>
  ![한영전사](https://user-images.githubusercontent.com/46860669/102710567-7529e500-42f6-11eb-9e8f-4e284e6018aa.PNG)<br>
  
  * 문장 통째로 입력하여 이중전사 가능(이중전사하고자 하는 단어의 앞뒤를 따옴표('')로 감싼 후 단어 맨 뒤에 세미콜론 (;) 입력)
  - ex. 자/ 일단 '요기;' 한 번 볼게요. 'ㄱ;' 은 뭐죠? '그죠;'. '3.45x;'! 맞나요? '굿;'입니다. 자/ 'ㄴ;' 봐볼까요? 이건 '플러스;' '3 분의 1;'이네요. 
  <br>--> 자/ 일단 (여기)/(요기) 한 번 볼게요. (ㄱ)/(기역) 은 뭐죠? (그렇죠)/(그죠). (3.45x)/(삼 점 사 오 엑스)! 맞나요? (good)/(굿)입니다. 자/ (ㄴ)/(니은) 봐볼까요? 이건 (plus)/(플러스) (3 분의 1)/(삼 분의 일) 이네요.<br>
![image](https://user-images.githubusercontent.com/46860669/102718631-7bd34f00-432c-11eb-9bab-1d16e82577a7.png)<br>

  - 숫자 발음 출력 결과는 알맞게 취사 선택하여 필요없는 부분 삭제<br>
  ![image](https://user-images.githubusercontent.com/46860669/102718664-a6250c80-432c-11eb-961a-8b2e0e65ab45.png)
  
<br>
  *  Win키 + 방향키로 창 이동 가능, 창 세로 길이 조정 가능
<br>
------------------------------------------------------------------------------------
* ※ 메모장 형식의 툴로 필요시 출력결과를 삭제, 수정 가능합니다.
* ※ 문의 시 sjy777star@gmail.com 으로 연락 바랍니다.
------------------------------------------------------------------------------------

프로젝트 시작일 : 20.12.15
<br><br>
20.12.17 작업완료분
* 정수 및 소수 처리 완료(억 단위까지)
* 알파벳 전사 처리 완료
* 알파벳 및 숫자 복합 처리 완료
* 0~9 숫자 범위 내 영어발음, 한글 서수발음 출력 구분 처리 완료
* iconbitmap 추가
* exe 파일화 완료
<br><br>

* 영한 번역 처리
<br><br>
20.12.20 update
* 기존에 한글 처리 시 띄어쓰기가 되었던 점을 수정
  - ex. (24시간)/(이십 사 시 간)  --> (24시간)/(이십 사 시간)
* 기존에 0~9 범위까지만 출력 가능했던 부분을 0~99 숫자 범위까지 가능하도록 수정
  - ex. (16)/(십 육) (16)/(식스틴) (16)/(열 여섯) 으로 출력
* 한글 입력 시 영어발음 전사 또는 영어 번역 전사 가능
  - ex. (cloud)/(클라우드)
* 기존에 공백 허용 불가했던 점을 수정하여 공백 포함 입력 가능
  - ex. (4 분의 1)/(사 분의 일)
* 문장 통째로 입력하여 이중전사 가능(이중전사하고자 하는 단어의 앞뒤를 따옴표('')로 감싼 후 단어 맨 뒤에 세미콜론 (;) 입력)
  - ex. 자/ 일단 '요기;' 한 번 볼게요. 'ㄱ;' 은 뭐죠? '그죠;'. '3.45x;'! 맞나요? '굿;'입니다. 자/ 'ㄴ;' 봐볼까요? 이건 '플러스;' 'y;'  네요. 
  <br>--> 자/ 일단 (여기)/(요기) 한 번 볼게요. (ㄱ)/(기역) 은 뭐죠? (그렇죠)/(그죠). (3.45x)/(삼 점 사 오 엑스)! 맞나요? (good)/(굿)입니다. 자/ (ㄴ)/(니은) 봐볼까요? 이건 (plus)/(플러스) (y)/(와이) 네요.<br>
  ![image](https://user-images.githubusercontent.com/46860669/102718317-d79cd880-432a-11eb-8f51-1a1db291a48e.png)


<br><br>
### 미처리분
* 코랩 및 윈도우 환경에서는 잘 되나, macOS  실행 시 인코딩 문제 발생

<br><br>
