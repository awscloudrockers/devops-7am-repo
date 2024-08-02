pipeline {
       agent any 
	   stages {
	         stage("1.Creating file and folders") {
			    steps {
				       sh "mkdir declarative"
					   sh "cd declarative"
					   sh "touch myfile.txt"
					   sh "mkdir output"
					   writeFile file:"output/sample.txt",text:"This is the text file created for declarative"
					   }
					   }
			 stage ("2. view date and systeminfo") {
                    steps {
						  sh "date"
						  sh "uname -a"
						  sh "uptime"
						  sh "cal 2025"
						  sh "ls -altrs"
						  
						 }
						 }
				}		
		}		
