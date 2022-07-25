 pipeline {
   agent any 
   stages { 
     stage("Stage1") { 
	   steps { 
	     script { 
		   sh "mvn clean install"
		 }
	   } 
	 }   
	 stage("Stage2") { 
	   steps { 
	     script { 
		   sh "mvn clean install"
		 }
	   } 
	 }
   } 
 }
