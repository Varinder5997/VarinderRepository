node{
stage('SCM Checkout'){
git 'https://github.com/Varinder5997/VarinderRepository'
}
stage('Compile Package'){
def mvnHome= tool name: 'Maven 1', type: 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
