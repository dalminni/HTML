# HTML-summary

<html>
  <head>
    <title>summary</title>
    <meta charset="utf-8">
  </head>
<body>
<p>
<font size="+2" color="#0101DF">Atom 작동 순서</font><br>
Atom : html 에디터<br>
1. 바탕화면에 <u>디렉토리(폴더)</u> 생성<br>
2. 메뉴 -> File -> Add project folder<br>
3. Project 아래의 폴더 오른쪽 클릭해서 New File 선택<br>
4. 확장자 <u>xx.<strong>html</strong></u> 입력.<br>
   &nbsp;&nbsp;&nbsp;ex) 웹페이지-html, MS워드-doc, PDF-pdf<br>
5. xx.html 웹브라우저로 웹페이지 열기<br>
   &nbsp;&nbsp;&nbsp;단축키 Ctrl + O -> 파일 선택<br>
6. 단축키 Ctrl + S  : 파일저장<br>
</p>

<p>
  <br>
<font size="+2" color="#0101DF">HTML 기본문법 : tag <>, <&#47;></font><br>
  &nbsp;&nbsp;<> 열리는 태그 / <&#47> 닫히는 태그<br>
  &nbsp;&nbsp;cf)<br>
  &nbsp;&nbsp;tag 검색: HTML __tag (추천 사이트: w3school)<br>
  &nbsp;&nbsp;이미지 검색 사이트: <a href="https://unsplash.com/" target="_blank">
  unsplash</a> - 저작권X<br>
<br>
strong : 텍스트 강조<br>
u : 텍스트 밑줄<br>
h1~h6 : 텍스트 크기<br>
  &nbsp;&nbsp;텍스트 크기 1 >>> 6<br>
  &nbsp;&nbsp;h1: heading tag - 제목 태그<br>
p : 단락(문단) 구분<br>
br : 줄바꿈(한줄)  ** <&#47;> 사용 X<br>
  &nbsp;&nbsp;태그 수 만 큼 줄 간격↑<br>
img src="__" : 이미지 첨부  ** <&#47;> 사용 X<br>
img src="__" width="__%" : 이미지 크기 조절<br>
  &nbsp;&nbsp;img - image<br>
  &nbsp;&nbsp;src - source : 속성<br>
  &nbsp;&nbsp;__: 1. 이미지 주소<br>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. 이미지 이름.확장자(ex: xx.jpg)<br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;이미지 바탕화면 폴더에 추가 (Atom Project 폴더에 자동 업로드)<br>
xmp : 태그 <br>
&amp;&#35;&#52;&#56;&#59; : &#47;<br>
&amp;nbsp; : 공백 <br>
font : 텍스트 사이즈, 색깔, 폰트<br>
  &nbsp;&nbsp;size="" : 사이즈<br>
      &nbsp;&nbsp;&nbsp;&nbsp;1. 0~7, 기본값 3  ex)&lt;font size="1"&gt;___&lt;&#47;font&gt;
&#47; "+1" 기본 사이즈에서 +1<br>
      &nbsp;&nbsp;&nbsp;&nbsp;2. px 픽셀값      ex)&lt;font size="10px"&gt'___&lt;&#47;font&gt;<br>
      &nbsp;&nbsp;&nbsp;&nbsp;3. pt 한글프로그램 글씨포인트  ex)&lt;font size="10pt"&gt'___&lt;&#47;font&gt;<br>
  &nbsp;&nbsp;color="": 색깔<br>
      &nbsp;&nbsp;&nbsp;&nbsp;1. red, yellow, blue 등 이름<br>
      &nbsp;&nbsp;&nbsp;&nbsp;2. 16진 색상코드<br>
  &nbsp;&nbsp;face="" : 폰트종류<br>
<br>

a : 문서 링크 태그<br>
  &nbsp;&nbsp;href="" : 링크 참조(연결 주소 지정)<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;제작한 웹페이지로 연결시<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;project -> 폴더 우 클릭 -> New file ->xx.html<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ex) <a hret="1.html">html</a><br>
  &nbsp;&nbsp;target="" : 링크 클릭 시 창 열기 설정<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_self: 링크 클릭한 해당 창에서 열기<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_blank: 링크 새창으로 열기<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_parent: 부모 창에서 열기<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;_top: 전체 브라우저 창에서 가장 상위의 창에서 열기<br>
  &nbsp;&nbsp;title="" : 링크 도움말<br>
ex) &lt;a href="___" target="_blank" title="___"&gt;________&lt;&#47;a&gt;<br>
<br>
title : 웹페이지 제목<br>
&nbsp;검색엔진 웹페이지 분석 시 가장 중요한 태그<br>
meta charset="utg-8" : 문자 인식 태그  ** <&#47;> 사용 X<br>
body : 본문<br>
head : 본문에 대한 정보<br>
html : html 문서의 루트<br>
!DOCTYPE html : 웹문서 html 작성 버전 선언  ** <&#47;>사용 X<br>
ex) &lt;!DOCTYPE html&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp; &lt;html><br>
    &nbsp;&nbsp;&nbsp;&nbsp; &lt;head><br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;title>___<&#47;title><br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;meta charset="utf-8"><br>
  &nbsp;&nbsp;&nbsp;&nbsp;   <&#47;head><br>
    &nbsp;&nbsp;&nbsp;&nbsp; &lt;body><br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--------<br>
    &nbsp;&nbsp;&nbsp;&nbsp; <&#47;body><br>
    &nbsp;&nbsp;&nbsp;&nbsp; <&#47;html><br>
<br>
iframe : 동영상 첨부 - 소스코드 복사<br>
      &nbsp;&nbsp;src="url"<br>
  &nbsp;&nbsp;width="" 너비<br>
  &nbsp;&nbsp;height="" 높이<br>
  &nbsp;&nbsp;frameborder=""<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0: 테두리 X<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1: 테두리 O<br>
  &nbsp;&nbsp;scrolling="" : 스크롤바 유무<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;yes: 표시<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;no: 표시x<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;auto: 자동<br>
  &nbsp;&nbsp;align="" : iframe 정렬<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;top: 맨 위<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;middle: 중앙<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bottom: 아래<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;left: 왼쪽<br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;right: 오른쪽<br>
<br>
<iframe width="320" height="180"
      src="https://www.youtube.com/embed/7T7r_oSp0SE"
      title="YouTube video player" frameborder="1"
      allow="accelerometer; autoplay; clipboard-write;
      encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>
<br>
<<부모-자식 태그>><br>
ul(ol)-li : 목록 구분<br>
ul: 순서가 없는 목록(점 표시)<br>
ol: 순서가 있는 목록<br>
li: 목록의 항목<br>
  &nbsp;&nbsp;ex) &lt;ul><br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li>___<&#47;li><br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<&#47;ul><br>
table- tr, th, td : 도표<br>
tr: 행(row)<br>
  &nbsp;&nbsp;rowspan="(병합할 셀의 수)"  :  세로방향 셀 병합<br>
td: 열(col, 셀)<br>
  &nbsp;&nbsp;colspan="(병합할 셀의 수)"  :  가로방향 셀 병합<br>
th: 셀 제목<br>
  &nbsp;&nbsp;ex) &lt;table><br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tr><br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;th>___<&#47;th><br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<&#47;tr><br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;tr><br>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;td>___<&#47;td><br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<&#47;tr><br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<&#47;table><br>
      <table border="1" width="200">
        <tr>
          <td>
            <ul>
              <li>ul</li>
            </ul>
          </td>
        <td>
          <ol>
            <li>ol</li>
          </ol>
        </td>
      </tr>
    </table>
</p>
<br>
: 댓글기능<br>
<a href="https://blog.disqus.com/" target="_blank">disqus</a> -> get started -> i want to install~ -> creat site<br>
-> 2. install disqus -> select platform 아래 -> i don't see my~<br>
-> 1. place the following~ 코드 복사 -> <&#47;body> 내 코드 붙여넣기<br>
->웹페이지 주소(localhost)127.0.0.1/index.html<br>
<br>
프로필 클릭 -> install on site -> i dont see~ 이하 동일
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://html-summary.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
<br>
: 채팅기능<br>
<a href="https://www.tawk.to/" target="_blank">tawk</a> -> login -> Dashboard Admin -> adminstration -> chat widget<br>
-> </> widget code 복사 -> <&#47;body> 내 코드 붙여넣기<br>
->웹페이지 주소 127.0.0.1/index.html<br>
<!--Start of Tawk.to Script-->
<script type="text/javascript">
var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
(function(){
var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
s1.async=true;
s1.src='https://embed.tawk.to/60f7f948649e0a0a5ccd4069/1fb4abhj9';
s1.charset='UTF-8';
s1.setAttribute('crossorigin','*');
s0.parentNode.insertBefore(s1,s0);
})();
</script>
<!--End of Tawk.to Script-->

<br>
: 방문자 분석<br>
<a href="https://analytics.google.com/" target="_blank">google analytics</a> -> 속성에 url 입력 -> 데이터 스트림 -> 웹/앱 선택 -> 보고서<br>
****수정****
</p>
<br>

<<웹호스팅>>
<a href="https://github.com/" target="_blank">github</a> -> sign in -> repository 클릭 -> public, initialize README 체크<br>
-> upload files -> 파일 다중선택 -> 파일 변경시 변경된 내용 작성 -> commit change<br>
-> settings -> pages -> source main -> save -> 웹페이지 주소 생성<br>
  *repository: 소스코드 저장소<br>
<br>
<br>
<웹서버>
<a href="https://bitnami.com/stack/wamp" target="_blanl">bitnami WAMP stack</a>
-> 설치진행 -> MuSQL 비밀번호 설정<br>
<br>
비트나미 매니저 : 웹서버 on/off<br>
Bitnami -> manager-windows -> Go to Application<br>
<br>
내 컴퓨터의 index.html 파일 요청<br>
Go to Application -> localhost 확인<br>
localhost  -  http://, /index.html 생략<br>
= http://localhost/index.html : 도메인네임(domain name)<br>
= http://127.0.0.1/index.html : ip 주소(ip address)<br>
<br>
index.html파일 경로<br>
윈도우 -> Binami -> wampstack -> apache2 -> htdocs<br>
*htdocs(hypertext documents): 웹페이지 저장된 디렉토리<br>
<br>
웹브라우저에 표시되고 있는 웹페이지 = htdocs 디렉토리에 저장된 웹페이지인지 확인하는
방법<br>
index.html 파일 메모장 열기 -> &lt;body> 아래에 아무글자 작성 후 웹페이지 리로드<br>
-> 웹페이지 수정된 것 확인<br>
<br>
내 project 웹서버 통해 화면 표시하기<br>
htdocs내 파일 삭제 -> 프로젝트 폴더 내 파일 복사 -> 리로드<br>
<br>
웹페이지 열기  ip 주소 vs 파일 열기<br>
ip주소: 웹서버 stop시 웹페이지 로드 X<br>
<br>
<br>
<웹서버-웹브라우저 통신><br>
컴퓨터 ip주소 확인<br>
네트워크와 공유센터 열기 -> 연결(connections) -> 자세히(details) -> IPv4<br>
아이피주소/index.html 접속 -> 웹페이지 작동<br>
컴퓨터, 스마트폰 동일 네트워크에 접속 -> 웹페이지 로드<br>
*작동 안 될 수도 있음
