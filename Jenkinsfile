node{
  stage ('SCM checkout'){
    git 'https://github.com/VishnuRachamallu/H2project'
  }
  stage ('compile and deploy'){
  javac TestMain.java
  java TestMain
  }
}
