node('master')
{
    stage('Continuous Download_loans')
        {
    git 'https://github.com/sunildevops7'
        }
    stage('Continuous Build_loans')
        {
    sh label: '', script: 'mvn package'
        }

}
