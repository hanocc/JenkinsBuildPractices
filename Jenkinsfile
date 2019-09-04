node('UBUNTU'){
    stage('GIT'){
    git 'https://github.com/hanocc/JenkinsBuildPractices.git'
    }
     stage('package'){
      sh 'mvn package'
     }

}