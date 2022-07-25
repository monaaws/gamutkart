 pipeline {
   agent any 
   stages { 
     stage("Stage1") { 
	   steps { 
	     script { 
		   bat "mvn clean install"
		 }
	   } 
	 }   
	 stage("Stage2") { 
	   steps { 
	     script { 
		   bat "mvn clean install"
		 }
	   } 
	 }
   } 
 }
