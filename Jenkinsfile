pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // This checks out the code from the repository.
                git(url: 'https://github.com/GidSamina/devops_class_6.git', branch: 'main')
            }
        }
        stage('Run Script') {
            steps {
                    echo "Running myapp.py on master branch..."
                    echo  'python BuyMe.py'
                }
            }
        }

}