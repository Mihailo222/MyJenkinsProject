pipeline {

agent any

stages {
  stage("build"){
	steps {
	     echo "Building ..."
	     script {
		def test = 2+2 > 3 ? 'cool'":'not cool'
		echo test
	     }

	}
  }
}


}
