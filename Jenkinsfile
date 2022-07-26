pipeline {
   agent any 
   Stages { 
     Stage("Stage1") { 
	   steps { 
	     echo "on stage "
		   sleep 5
	   } 
	 }   
	 stage("parallel stage") {
	 parallel {
	   Stage("Stage2") { 
	     steps { 
	       echo "on stage 2"
		   sleep 5
	     } 
	   }
	   Stage("Stage3") { 
	     steps { 
	       echo "on stage 3"
		   sleep 5
	     } 
	   }
	 }
     }	 
   } 
 }
