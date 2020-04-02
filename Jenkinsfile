node{
stage('SCM Checkout'){
git 'https://github.com/Devil0730/MVC1'
}
stage('Compile Package'){
def mvnHome= tool name: 'Maven 1', type: 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
