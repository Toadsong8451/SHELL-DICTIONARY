# db 계획
명령어들을 저장하기 위한 db 구성
DBserver는 115.23.235.135(학교 DB server)의 mariadb를 이용 - Shell 제목의 데이터베이스 제작
라즈베리 파이로 변경 가능
- 한 명령어에 대한 Windows, LacOS, Linux 명령어, 기능을 간단하게 요약한 말, 자세한 기능(옵션), 키워드 1, 2, 3, 사용 빈도(검색 빈도)를 저장
- 검색 빈도를 이용하여 만일 둘 다 존재하는 것에 대해서는 먼저 띄운다. (초기에 중요도에 따라 초기조건을 준 상태에서 서비스 시작)

## 표 구성 계획
- String (Windows 명령어) 
- String (MacOS 명령어)
- String (Linux 명령어)
- String (기능 요약)
- String (자세한 기능 + 옵션들) 
- String (키워드 1)
- String (키워드 2)
- String (키워드 3)
- Int (사용 빈도)
## 제공 방법
- 온라인
    - 115.23.235.135에 접속하여 검색 진행
- 오프라인
    - <https://sgpassion.tistory.com/552>
    - APK 베포 시 DB 정보를 포함하여 저장 후 제공
    - 업데이트 마다 온라인의 DB 를 변환하여 수정 후 제공
## 패키지 
- 패키지를 추가하면 다른 분야도 사전으로 만들 수 있다 . 
- EX - android 함수들을 사전으로? -> db만 추가 요청하면 가능