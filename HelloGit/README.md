형상관리 | 버젼관리

* SCM software Configuration Management
* 프로젝트 전반에 대한 관리
* vcs, source code build, packaging, deploy 까지 포함

* vcs version control system
* scm의 하위개념 
* versioning에 집중
* subversion, git 프로그램등을 사용

 ---
 
 # 버젼 되돌리기
 
 * reset : 특정 버젼으로 돌아간다.
 	* -- hard : 특정버젼 이후 내역은 모두 삭제
 	* -- mixed : 특정버젼 이후 내역은 staging area에 보관
 	* -- soft : 특정버젼 이후 내역은 uncommited changes에 보관
 
 * revert : 특정 버젼을 취소한 새로운 버젼으로 생성 