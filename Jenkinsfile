node {
   stage('Preparation') { // for display purposes
      git 'https://github.com/amict/W.git/'
   }
   stage('Build') {
      // Run the maven build 
    echo "Build" 
    sh "ls -la"   
   }
   stage('Deploy') {
   sh "pwd"
   sh "cat README.md"
   sh "cat Jenkinsfile"
   echo "Done!"    
   }
}
