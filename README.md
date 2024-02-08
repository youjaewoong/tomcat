# tomcat

#### apache
- bin : 실행관련 파일
- conf : 설정관련 파일
  - Listen : 포트설정
  - SaverName : localhost 또는 ip
  - Include conf/extra/modjk.vhosts.conf : Aparch와 Tomcat을 연동 할떄 해당 모듈로 설정 합니다.
- htdocs: 정적인 파일
- logs : 로그파일
- extra : 외부 모듈 설정 파일
  - modjk.vhosts.conf
    - 정적 동적 구성 처리
    - 포트 설정
    - 서버명 설정
    - 메소드 설정
    - SSL 설정
- modules : 모듈 관련 파일 (Tomcat 연동을 위한 모듈 포함)

#### tomcat
- conf : 설정관련 파일
  - server.xml : 
