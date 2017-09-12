pipeline {
  agent any
  stages {
    stage('greeting') {
      steps {
<<<<<<< HEAD
        sh '''echo "hello moon"
'''
      }
    }
    stage('run test') {
      steps {
        sh '''docker-compose build
docker stop $(docker ps -a -q) && docker rm $(docker ps -a -q)
docker-compose run web ./scripts/setup.sh rails test
'''
      }
    }
  }
}
=======
        sh 'echo "Hello World"'
      }
    }
  }
}
>>>>>>> c7a4e3cd782a905087d748b06b850549e7048e46
