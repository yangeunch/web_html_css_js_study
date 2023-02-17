<h1>반응형 웹디자인&웹퍼블리셔 양성과정 버전기록</h1>
<p>ex) 날짜 - 제목 -요약</P>
<h2>23.02.13 시작 - HTML</h2>
<p>H1~H6, P , br, inline, block</p>
<p>H1~H3은 검색키워드로 활용가능하다. H4~H6 꼭 필요한 경우만 이용하거나 권장안함</P>
<p>block과 inline태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다. (의미 중첩되지 않도록)</p>
<hr>
<h2>23.02.14 시작 - 문서태그</h2>
<p><strong>strong</strong>, <em>em</em>, hr, blockquote, q, code, address, sub, sup, del,</p>
<p>gnb, lnb, snb, fnb, breadcrumbs</p>
<blockquote cite="https://ynweb.notion.site/UI-UX-A-23-1-27-6-2-cada53e4cda44b9ab4f417fc8eb9ecab">유나쌤 블로그 참고 - https://ynweb.notion.site/UI-UX-A-23-1-27-6-2-cada53e4cda44b9ab4f417fc8eb9ecab</blockquote>
<h2>23.02.15 - ul,ol</h2>
<ul>
  <li>ul, ol, li 순서있는 목록 없는 목록 구분 확실히 해야함</li>
  <li>li의 형제태그는 li만 올 수 있으니 나머지 태그는 그 자식, 자손태그에 삽입해야한다</li>
  <li>p,태그를 사용할 때 ul과li의 사이가 아닌 li안에 넣어서 사용해야 한다</li>
</ul>
<dl>
  <dt>dl,dt,dd</dt>
  <dd>dt는 제목 dd는 내용이다 항상 dt가 먼저오고 그다음 dd가 와야 한다 </dd>
  <dd>최소 1:1 비율</dd>
  <dd>dl 안에는 dt와 dd만 올 수 있다</dd>
  <dd>다른 태그들을 쓰려면 dt와 dd안에 써야한다</dd>
</dl>
<div class="study">
  <h2>23.02.16 - HTML - 시맨틱태그, 그룹태그 </h2>
  <ul>
    <dt><strong>div, section, aside, article, main</strong></dt>
    <dd>div는 2개 이상 묶어주는 그룹태그이다</dd>
    <dd>section은 문서의 독립적인 구획을 나타낸다</dd>
    <dd>aside는 사이드에 배치되어있다</dd>
    <dd>article은 독립적으로 다른곳에 배치해놔도 어떤것인지 알 수 있다</dd>
    <dd>main은 화면 전체를 </dd>
  </ul>
  </div>
  <h2>23.02.17</h2>
  <p>하이퍼링크-문서와 문서를 연결하여 이동할 수 있는 모든 링크를 뜻한다</p>
  <p>절대경로와 상대경로 링크를 제작하기 위해서는 문서에서다른문서(파일, 이미지, 동영상)로 이동하는 방법을 정의하는절대경로와 상대경로에 대해서 알아야 합니다</p>
  <dl>
    <dt>절대경로</dt>
    <dd>최초의 시작점, 파일이 존재하기 위해서 있어야 하는 시발점, http://</dd>
    <dt>상대경로</dt>
    <dd><기준경로를 기준으로 경로를 구성/dd>
    <dd>상대경로에는 같은위치/하위경로/상위경로가 있는데 상대경로에서'기준위치'를 정했다면 찾고자 하는 파일이 '기준위치'에서 어디에 있는지 확인해야 </dd>
  </dl>
