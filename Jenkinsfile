node {
  checkout scm
  sh "mvn -B clean install"
  junit testResults:'target/tests.xml', testRunName: 'foo bar'
}  
