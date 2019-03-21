pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "set/*.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
