pipeline{
    agent {
        node{
            label: "maven"
        }
    }

    stages{
        stage('Build'){
            steps{
                git branch: 'main', url: 'https://github.com/alok7mishra/tweet-trend-new.git'
            }
        }
    }
}