pipeline {
  agent any
  tools { 
        maven 'Maven_3_2_5'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=asgbuggywebapp1210_asgbuggywebapp1210 -Dsonar.organization=asgbuggywebapp1210 -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=8da1db165a85672b8c4c6662f708db471c15abbb'
			}
        } 
  }
}
