node(){
    stage("checkout"){
        checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/csenapati12/java-tomcat-maven-docker.git']])
    }
    stage("build"){
       bat 'mvn package'
    }
    stage("compile"){
        echo "compile"
    }
    stage("deploy"){
        echo "deploy"
    }
}
