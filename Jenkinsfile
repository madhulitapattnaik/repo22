 pipeline{
 tools{
        jdk 'JAVA_HOME'
        maven 'MVN_HOME'
    }
     agent any
	  
	  stages{
	  
	  stage("checkout"){
	   steps{
	   git 'https://github.com/madhulitapattnaik/repo22.git'
	   }
	                  }
	
	   stage("compile"){
	    steps{
		    echo "test"
		 sh 'mvn compile'
		}
		}
		stage("test"){
	    steps{
		 sh 'mvn test'
		}
		}
		stage("package"){
	    steps{
		 sh 'mvn package'
		}
		}
		stage("deploy"){
	    steps{
		 echo "please deploy my application"
		}
		}
		
	  }
	}
