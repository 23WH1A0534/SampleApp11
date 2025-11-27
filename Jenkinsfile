pipeline{
  agent any
  stages{
    stage('GitHub Checkout'){
      steps{
        git 'https://github.com/23WH1A0534/SampleApp11/new/main';
      }
    }
    stage('Build'){
      steps{
        echo 'Hello from jenkins';
      }
    }
  }
}
