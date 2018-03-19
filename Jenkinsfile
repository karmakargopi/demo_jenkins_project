def regions = new String[3]
    regions[0] = "north-america.ca"
    regions[1] = "japan-korea.jp"
    regions[2] = "lodon-spain.eu"
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //echo 'It is a Develop Branch !!!'
                echo Globals.regions[1]
            }
        }
     }
 }
