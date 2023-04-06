pipeline {
agent any
stages {	
    stage ('stage-print-first-message')
    {steps { sh "job-is-building"}}

    stage ('stage-print-second-message')
    {steps { sh "package -is-deploying"}}
    
    stage ('stage-final-stage')
    {steps { sh "echo deploy-to-prod"}} 
}
}
