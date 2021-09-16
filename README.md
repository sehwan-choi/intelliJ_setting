# 인텔리제이 환경설정
File - Setting - gradle 검색후 <br>
Build and run suing : intelliJ IDEA <br>
Run test using : intelliJ IDEA <br>
로 변경 <br>


# Lombok 설치
file - setting - plugin 검색후 - lombok설치 <br>
				 Build, Execution, Deployment 하위 Compiler 하위 Annotation Processors에서  <br>
				 Enable annotation processing 체크 <br>



# html수정후 재시작 하지 않고 소스 반영하도록 설정
build.gradle 에  <br>
	implementation 'org.springframework.boot:spring-boot-devtools' <br>
추가후 서버 재기동 하면 restartedMain으로 나온다면 설정완료 <br>
html 수정후 Build -> recompile 하면 된다 <br>
