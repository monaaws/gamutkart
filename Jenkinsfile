 pipeline {
   agent { 
      agent1 {  
        label 'maven' 
      }
   }	   
   stages { 
     stage("Stage1") { 
	   steps { 
	     script { 
		   bat "mvn clean install"
		   echo "stage one completd"
		 }
	   } 
	 }   
	 stage("Stage2") { 
	   steps { 
	     script { 
		   bat "mvn clean install"
		   echo "stage 2 completed"
		 }
	   } 
	 }
   } 
 }
