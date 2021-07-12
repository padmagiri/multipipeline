node('master')
{
    stage('Continuous Download_master')
        {
    git 'https://github.com/sunildevops7'
        }
    stage('Continuous Build_master')
        {
    sh label: '', script: 'mvn package'
        }

}
