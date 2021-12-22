    //def app
    stage('Cloning Git') {
        /* Let's make sure we have the repository cloned to our workspace */
       checkout scm
    }  
    stage('Build-and-Tag') {
        sh 'echo Build-andTag'
    /* This builds the actual image; synonymous to
         * docker build on the command line */
        //app = docker.build("amrit96/snake")
    }
    stage('Post-to-dockerhub') {
        sh 'echo Post to-dockerhub'
     }
   stage('Post-to-dockerhub') {
        sh 'echo Post to-dockerhub'
   }
   stage('Pull-image-server') {
       sh 'echo pull image server'
      }
}
