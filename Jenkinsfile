pipeline {
		agent {
		node {
		label ('172.31.38.170')
			}
		}
		stages {
		stage ('install-httpd') {
			steps {
			sh "yum install httpd -y"
			}
			}
			stage ('install-tree') {
			steps {
			sh "yum install tree -y"
			}
			}

	
	}


}
