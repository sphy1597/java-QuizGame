# Java 퀴즈 게임

## 개요
 Java를 기반으로 개발한 멀티플레이가 가능한 퀴즈게임입니다. Java Swing으로 GUI를 개발했고 jdbc를 통해 DB와 연동했습니다. 소켓통신을 통해 클라이언트들이 서버와 통신하고 서버에서 DB에 저장된 문제들을 클라이언트에 보내 진행됩니다. 
 ip는 localhost, port번호는 60000번으로 개발했습니다.
 속담, 음악가사, 영화제목 등을 맞추는 간단한 채팅 게임입니다.

## 기능 및 특징
 - **클라이언트**: 간단한 로그인기능, 아이디, 비밀번호 찾기, 게임화면, 진행등의 기능이 있습니다. 소켓 통신을 통해 서버와 통신하여 기능이 동작하게 됩니다. 
 - **서버** : 클라이언트의 연결 요청을 기다리며, 연결하게 되면 로그인 기능부터 게임 진행까지의 각 기능을 클라이언트 마다 멀티스레드를 통해 관리하게 됩니다.

## 기술적 정보
- **개발환경**: eclips
- **플랫폼**: windows
- **언어**: Java


## 팀원  
- 심규철 : [GitHub](https://github.com/sphy1597)

## 라이선스
이 프로젝트는 [MIT 라이선스](/path/to/license)를 따릅니다.
