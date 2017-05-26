node ('master')
{
   stage('init')
   {
      echo "runing job from branch ${BRANCH_NAME}"
      checkout scm
   }
   
   stage('run')
   {
      bat 'run.bat'
   }
}