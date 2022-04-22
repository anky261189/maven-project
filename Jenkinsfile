pipeline{
agent any
stages{
stage('Git Clone'){
steps{
  git branch: 'main', url: 'https://github.com/anky261189/maven-project.git'
}

}
  stage('Test'){
steps{
  sh 'mvn test'
}

}
  stage('package'){
steps{
  sh 'mvn package'
}

}


}
}
