pipeline{
agent any
stages{
stage('clone'){
steps{
git branch:'main',url:'https://github.com/Harshuavadutha1612/Calculator1.git';
}
}
stage('compile'){
steps{
sh'javac Calculator.java'
}
}
stage('build'){
steps{
sh'java calculator 25 5'
}
}
}
}
