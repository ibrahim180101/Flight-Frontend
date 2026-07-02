pipeline {
agent any

```
stages {
    stage('Clone Repository') {
        steps {
            git branch: 'main', url: 'https://github.com/ibrahim180101/Flight-Frontend.git'
        }
    }

    stage('Deploy to Nginx') {
        steps {
            sh '''
            sudo cp -r * /usr/share/nginx/html/
            '''
        }
    }
}
```

}

