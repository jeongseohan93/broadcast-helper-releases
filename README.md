# 방송도우미 설치 파일

치지직 스트리머용 방송 도우미(윈도우 앱)의 **설치 파일과 자동 업데이트 정보**만 두는 곳이에요. 코드는 비공개예요.

## 설치

1. 오른쪽 [Releases](https://github.com/jeongseohan93/broadcast-helper-releases/releases/latest)에서 `broadcast-helper_x.y.z_x64-setup.exe`를 받아 실행해요.
2. 한 번 설치하면 그다음부터는 앱을 켤 때 "새 버전이 있어요 [지금 업데이트]"가 떠요. 누르면 알아서 받아서 설치하고 다시 켜져요.

업데이트 파일은 서명돼 있고, 앱은 서명이 맞을 때만 설치해요.

## 처음 쓸 때

1. [치지직 개발자 센터](https://developers.chzzk.naver.com)에서 애플리케이션을 등록해요.
   - 로그인 리디렉션 URL: `http://localhost:8080/login`
   - Scope: 유저·채널 조회, 방송 설정 조회/변경, 채팅 메시지 조회/쓰기, 채팅 공지 쓰기, 채팅 설정 조회/변경, 활동제한 쓰기/조회, 후원 조회, 구독 조회 (스트림키 조회는 켜지 않기)
2. 앱에 Client ID·Client Secret을 넣고 [네이버로 로그인].

키는 이 PC의 윈도우 자격 증명 관리자에만 저장돼요.
