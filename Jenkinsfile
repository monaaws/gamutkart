 pipeline {
   agent { any agent
   } 
   Stages { 
     Stage1 { 
	     steps { 
	       script { 
		       sh "mvn clean install"
		     }
	     } 
	   }   
	   Stage2 { 
	     steps { 
	       script { 
		       sh "mvn clean install"
		     }
	     } 
     }
   } 
 }
