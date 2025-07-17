CODE_CHANGES = getGitChanges()
pipeline {
agent any
stages {
stage('build') {
When {
}
steps {
echo('test') {
when {
expression {
BRANCH_NAME = 'developments'
}
}
steps {
echo 'testing the applications...'
}
}
stage('deploy') {
steps {
echo 'deploying the application...'
}
}
}
