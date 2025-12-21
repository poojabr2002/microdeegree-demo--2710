pipeline{    
    agent any

    stages{
        stage['server date']{
            steps{
                sh 'date'
            }
        }
        stage['ip adress']{
            steps{
                sh 'hostname -I'
            }
        }
        stage['cpu details']{
            steps{
                sh 'lscpu'
            }
        }
        stage['Disk usage']{
            steps{
                sh 'du -h'
            }
        }
        stage['memory usage']{
            steps{
                sh 'free -h'
            }
        }
    }
}
