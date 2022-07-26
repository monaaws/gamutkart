pipeline {
   agent any 
   stages { 
     stage("Stage1") { 
	   steps { 
	     echo "on stage 1"
		   sleep 5
	   } 
	 }   
	 stage("parallel stage") {
	 parallel {
	   stage("Stage2") { 
	     steps { 
	       echo "on stage 2"
		   sleep 5
	     } 
	   }
	   stage("Stage3") { 
	     steps { 
	       echo "on stage 3"
		   sleep 5
	     } 
	   }
	 }
     }	 
   } 
 }
