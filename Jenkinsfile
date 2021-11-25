def ips = ["192.168.0.1","192.168.0.2"]

pipeline {
	agent any
	stages {
		
		build(ips)
		stage("Deploy") {
			steps {
				echo "Deploying..."
			}
		}
	}
}
