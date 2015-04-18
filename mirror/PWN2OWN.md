[미국](%EB%AF%B8%EA%B5%AD.md)의 3Com TippingPoint에서 주최하는
[해킹](%ED%95%B4%ED%82%B9.md) 대회. 이름의 유래는 [leet](leet.md)인 OWNED(캐관광 정도로
번역할 수 있다)에서 왔다. PWN은 OWN의 발전형(?)으로 너무 급해서 OWN을 오타로 PWN이라고 친 데서 유래.

[해킹](%ED%95%B4%ED%82%B9.md) 대회라고는 해도 딱히 해로운 의도는 없고 그냥 보안 컨퍼런스 행사 중 하나. 본
목적은 자주 사용되는 [IT](IT.md) 기기들의 약점과 문제점을 찾아내어 더욱 더 강한 보안수준을 요구하게 한다는 것으로, 업계에서
자기네들이 만든 시스템의 후장이 PWN2OWN에서 서늘하게 털리는 것을 지켜보며 경각심을 일깨우거나 보안에 더욱 심혈을 기울이게끔 만드는
것이다. 미국에서도 내로라 하는 전국구 해커들이 등장해서 어떤 시스템이라도 빠르면 몇분안에 탈탈 털어버린다.

해킹 대상에 따라서 [OS](OS.md) 부문, [웹브라우저](%EC%9B%B9%20%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80.md) 부문,
[스마트폰](%EC%8A%A4%EB%A7%88%ED%8A%B8%ED%8F%B0.md) 부문으로 나뉜다. 특히 OS쪽에서
[애플](%EC%95%A0%ED%94%8C.md)의 맥 시리즈가 순식간에 털리는 것으로도 유명하다. 대회인 만큼 상금과 상품도
주어지는데, 상품으로는 상금과 함께 해킹에 성공한 스마트폰 기기를 증정한다고 한다.

2010, 11년 PWN2OWN은 2번 다 [캐나다](%EC%BA%90%EB%82%98%EB%8B%A4.md)
[밴쿠버](%EB%B0%B4%EC%BF%A0%EB%B2%84.md)에서 3월에 열렸다.  
[구글](%EA%B5%AC%EA%B8%80.md)에서는 PWN2OWN의 첫째날 [구글크롬](%EA%B5%AC%EA%B8%80%20%ED%81%AC%EB%A1%AC.md)을 첫번째로 해킹한 해커에게 2만달러와 부상으로
크롬 운영체제 노트북을 제시했다. 결국 2011년 PWN2OWN 대회에서 [웹브라우저](%EC%9B%B9%20%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80.md)중 크롬만이 해킹되지 않으며
3년연속으로 해킹되지 않은 기록을 세웠다...만 2012년 대회에선 결국 **뚫렸다**(...) <del>괜찮아 같은
[웹키트](%EC%9B%B9%ED%82%A4%ED%8A%B8.md) 쓰는
[사파리](%EC%82%AC%ED%8C%8C%EB%A6%AC.md)는 3초만에 뚫렸는데 뭐</del>

2015년 3월에 열린 pwn2own 에서, 한국의 유명한 해커 이정훈(lokihardt) 이 Chrome, IE11, Safari 최신
버전을 전부 해킹하는데에 성공하여 총 상금 225000$ 를 얻었다! 이는 이 대회 역사상으로도 한 개인이 3가지 메이저 브라우저를 전부
해킹하는 데에 성공한 것은 최초이기 때문에(팀 단위라 해도 사실 없다.) 그야말로 엄청난 사건이다. 이정훈 해커는 이미 이전에도 2014년
mobile pwn2own 에서 iPhone 5S 상의 Safari 브라우저 해킹으로 상금을 받은 적이 있으며, 그 보다 더 이전에도
Chrome 브라우저의 취약점(Sandbox escape를 포함하는 Full exploit)으로 구글에서 3만 달러를 받은 경력이 있다.
물론 그 이전에도 Interet Explorer 취약점을 다수 발견했었고 국내 소프트웨어들(곰플레이어, 한글, V3 Lite, 기타 등등)은
말할 것도 없다. 한마디로 버그 헌팅으로는 현재 독보적인 국내 최고<del>를 넘어 세계 최고</del>라고 해도 무방하다.

특이사항이라면 과거에 이정훈 해커가 발견하여 구글에 보고한 Chrome 취약점의 경우 크롬 자체의 취약점을 이용해 Sandbox 를 우회한
반면(이는 즉 운영체제가 Windows 든 Linux 든 관계없이 크롬 샌드박스를 우회할 수 있다는 뜻이다.) 이번 대회에서는 Windows
커널의 취약점을 이용해 우회한 것이 흥미롭다고 할 수 있겠다. 물론 이는 pwn2own 대회에서 IE와 Chrome 은 Windows 위에서
돌아가는 상태로 신규 Windows 커널 취약점을 이용해 샌드박스를 우회해도 인정하기 때문이다. 다만 구글에 직접 보고하는 경우는 커널
취약점으로 샌드박스를 우회한 것은 인정하지 않는다. 당연히 모든 플랫폼에서 해킹이 가능하도록 우회하는 것이 보통 더 어렵다.

부가적으로 브라우저를 해킹한다는 의미에 대해 부연 설명하자면, 어떤 브라우저를 해킹했다는 것은 해커가 미리 만들어놓은 html 과 같은
브라우저가 파싱하는 파일을 웹 서버에 올려놓고 해당 브라우저를 사용하는 유저가 그 웹 페이지에 접속하여 페이지를 보려고 하는 순간 해커가
원하는 코드가 실행된다는 얘기이다. 이는 가령 시스템의 중요 파일을 지우는 코드가 될 수도 있고 원격 쉘을 열어서 해커가 시스템을 조작할 수
있도록 하는 코드일 수도 있고 또는 계산기를 실행하는(...) 코드일 수도 있다. 원래 브라우저 프로그램에 포함되어 있지 않은 임의의 코드가
실행된다는 것이며 이러한 취약점 형태를 Arbitrary Code Execution(임의 코드 실행) 이라고 하며 브라우저의 경우 원격에서
공격이 가능하므로 원격 코드 실행 취약점이라고 부르기도 한다.

예전에는 이러한 코드 실행을 위한 취약점(Buffer overflow, Use-after-free 등)을 이용해서 코드를 실행만 하면
되었지만, 현재는 Internet Explorer 조차 EPM 이라는 이름으로 적용하고 있는 Sandbox 기술로 인해 예전처럼 단순히 코드
실행만으로 악의적인 공격을 할 수는 없게 되었다. 이는 쉽게 말하자면 Sandbox 라는 가상의 박스 안에서 브라우저의 실제 처리를 하는
것으로, 원래 Sandbox 라는 기술은 특정 시스템 콜 호출을 막거나 또는 가상의 파일 시스템을 사용하도록 하는 등의 다양한 종류가 있고,
이 용어 자체는 특정 가상의 상태에 가두는 모든 것을 지칭할 수 있기 때문에 어떤 한 기술을 지칭하는 것은 아니다. 다만 브라우저들이
구현하는 Sandbox 는 대체적으로 유사한 편이다. 기본적으로는 제일 먼저 브라우저를 실행하면 Broker 라 불리는 모든 관리를 중앙에서
담당하는 프로세스가 생성되고, 이 Broker 에서 자식 프로세스를 필요한 만큼 생성을 하게 된다. 이 Broker 프로세스의 자식
프로세스로 있는 모든 프로세스들을 샌드박싱된(Sandboxed) 프로세스라고 부르며 기본적으로 권한 자체가 낮게 되어있다. 또한 이 자식
프로세스들에서 실제로 HTML 파싱, 렌더링, 자바스크립트 실행 등의 모든 일을 처리한다. 따라서 자바스크립트 취약점으로 Memory
Corruption , Code Execution 등이 가능해도 그것은 결국 Sandboxed 프로세스 내에서만 가능한 것일 뿐이다. 모든
권한을 갖고 있는 Broker Process 에서는 실제 브라우저의 동작 관련 처리는 하지 않는다.

Chrome 의 경우 이러한 샌드박스를 진작부터 적용을 하고 있으며, IE 의 경우 10 에서도 선택적으로 "인터넷 옵션 -> 고급" 탭에서
"향상된 보호 모드 사용" 이라는 옵션으로 사용을 할 수 있었고 IE11 부터는 필수 옵션이 되었다. Safari 의 경우 Mac OS X
와 iOS 에서 보통 실행되는데 이 두 운영체제는 모두 커널에서 자체적으로 어플리케이션 샌드박스를 지원하기 때문에 이를 이용하고 있다.
따라서 현재 pwn2own 과 같은 대회에서는 기본적으로 Sandbox 도 우회해야 해킹에 성공한 것으로 인정하고 있다. 이는 일반적으로
기존의 비교적 단순했던 브라우저 해킹을 훨씬 어렵게 만들었다. 따라서 이를 모두 우회하여 3개의 브라우저를 모두 해킹했다는 것은 단지
한국인이라서가 아니라 누가 봐도 대단한 일이라 할 수 있다.

여담으로 여기서 알아낸 취약점은 공개해야된다.
