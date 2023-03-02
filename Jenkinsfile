node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H2project'
  }
  stage ('compile and deploy'){
  sh 'javac TestMain.java'
  sh 'java TestMain'
  }
}
