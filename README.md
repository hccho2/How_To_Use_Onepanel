# onepanel 사용법(Windows환경)
### https://c.onepanel.io/
 * onepanel 사이트에 가서 ID를 만든다.
 
### Projects & Datasets

 * project만들기: 상단의 Projects --> +Create 버튼을 눌러, projects Name입력, private/public 선택
 * dataset만들기: 상단의 Datasets --> +Create 버튼을 눌러, Dataset Name입력, private/public 선택
 * project에는 source code, data 등을 올려 놓고, 실행시킬 수 있다. 
 * datasets에서는 대용량 data를 관리한다. 저 용량의 data는 그냥 project 아래에 올려 놓을 수도 있다.


### project에 소스코드(+data) 올리기
 * onepanel 사이트에서 project를 하나 만든다(예: myproject)
 * onepanel 설치
	``` js
	> pip install onepanel	
	``` 
 * cmd창에서 local pc에 project를 만들기를 원하는 곳으로 이동
	``` js
	> onepanel clone 본인ID/projects/프로젝트이름
	> onepanel clone hccho/projects/myproject
	``` 
 * 위와 같이 실행하면, 프로젝트이름과 동일한 디렉토리가 생성된다.
