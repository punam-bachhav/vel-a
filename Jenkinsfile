pipeline {
    agent {
	    label {
		   label "built-in"
		   customWorkspace "/data/pipeline"
		}
	}
        satges {
		  stage ('one') {
		    steps {
			 sh "echo 'hello all' > dev.html"
			}
		  }
		    stage ('two') {
			 steps {
			  dir ('/data/pipeline/qa') {
			  sh "echo 'hello all' > qa.html"
			  }
			 }
			}
		}

} 	
