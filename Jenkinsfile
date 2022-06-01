pipeline {

agent any

stages {

stage('Build') {

steps {

// echo "HelloWorld"
bat 'javac file.java'
  bat 'java -version'
}

}

stage('Run') {

steps {

// echo "HelloWorld"
  bat 'java file'
}
}
}
}
