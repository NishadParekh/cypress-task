node {

  stage ('checkout code from git hub') {

    git 'https://github.com/NishadParekh/cypress-task.git'

  }

  

  stage('install cypress') {

   

    sh "npm install --save -include=dev cypress"

    sh "NO_COLOR=1 npx cypress run "

  }
