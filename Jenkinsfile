node('built-in')

{

stage('ContinuousDownload_master') 
   
	 {
	
    git 'https://github.com/GPRAKASHG/multiBranch-mb.git'
    
	}

stage('Continuousbuild_master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}


}


