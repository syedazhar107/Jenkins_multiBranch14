node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/syedazhar107/Jenkins_multiBranch14.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
