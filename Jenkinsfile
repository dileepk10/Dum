pipeline{
 agent any
   stages{
     stage('DownloadCode'){
      steps{
          git branch: 'main', credentialsId: '1e77fc21-90f3-4349-be02-dc1b04fd5f1c', url: 'https://github.com/dileepk10/Dum.git'
      }
     }
   }
}
