 pipeline {
   agent any 
   Stages { 
     Stage("Stage1") { 
	   steps { 
	     script { 
		   sh "mvn clean install"
		 }
	   } 
	 }   
	 Stage("Stage2") { 
	   steps { 
	     script { 
		   sh "mvn clean install"
		 }
	   } 
	 }
   } 
 }
