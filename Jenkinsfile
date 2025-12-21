pipeline {
    agent any

    stages{
        stage('Server Date'){
            steps{
                sh 'date'
            }
        }
        stage('IP Address'){
            steps{
                sh 'hostname -I'
            }
        }
        stage('CPU Details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Disk Usage'){
            steps{
                sh 'du -h'
            }
        }
        stage('Memory Usage'){
            steps{
                sh 'free -h'
            }
        }
        stage('Partition Details'){
            steps{
                sh 'lsblk'
            }
        }
    }
}