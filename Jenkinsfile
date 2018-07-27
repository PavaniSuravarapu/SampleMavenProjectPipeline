pipeline {
	agent {
		label "windows"
		}
	tools {
		maven "MAVEN_HOME"
		jdk "JAVA_HOME"
		}
	stages {
		stage ('Initialize') {
			steps {
				bat '''
					echo "PATH = %Path%"
					echo "MAVEN_HOME = %MAVEN_HOME%"
				'''
			}
		}
	}
}