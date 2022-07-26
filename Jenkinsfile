
node('master') 
{
    stage('ContinuousDownload-Loans') 
    {
       git 'https://github.com/selenium-saikrishna/maven.git'

    }
    stage('ContinuousBuild-Loans') 
    {
      sh 'mvn package'
    }
   
    
    
 
    
    
    
}

