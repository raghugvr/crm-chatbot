pipeline {
    agent any
    parameters {
        string(name: 'name of the persion', defaultValue: '', description: 'Enter your name')
        choice(name: 'github url', choices: ['githuburl', 'gitlab url'], description: 'Select the url')
    }
    stages{
        stage("Param Demo"){
            steps{
                echo "Hi ${params.name}"
            }
        }
    }
}
