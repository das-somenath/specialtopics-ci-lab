
node {
  stage('checkout sources') {
        // You should change this to be the appropriate thing
        git url: 'https://github.com/das-somenath/specialtopics-ci-lab'
  }

  stage('Build') {
    // you should build this repo with a maven build step here
    echo "hello"
    withMaven (maven: 'maven3') {
      sh "mvn package"
    }

  }
  // you should add a test report here
}
