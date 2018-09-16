pipeline {
    agent {
        label 'compiler'
    }
    stages {
        stage('Compiler') {
            steps {
                echo "Start to compiling sourcecode."
                sh 'ip a'
                sh 'bash'
                sh 'python -m py_compile sources/add2vals.py sources/calc.py'
            }
        }
    }
}
