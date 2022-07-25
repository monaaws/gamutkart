 pipeline {	 
   Stages { 
     Stage (stage1) { 
	     steps { 
	       script { 
		       sh "mvn clean install"
		     }
	     } 
	   }   
	   Stage (stage2) { 
	     steps { 
	       script { 
		       sh "mvn clean install"
		     }
	       } 
         }
    } 
 }
