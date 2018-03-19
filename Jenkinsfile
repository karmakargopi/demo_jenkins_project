/*def regions = new String[5]
    regions[0] = "north-america.ca"
    regions[1] = "japan-korea.jp"
    regions[2] = "london-spain.eu"
    regions[3] = "インドまだない"
    regions[4] = "インドで欲しいです"*/
String[3] regions = ["north-america.ca", "japan-korea.jp", "london-spain.eu"]
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                //echo 'It is a Develop Branch !!!'
                echo regions[1]
            }
        }
        stage('Test') {
            steps {
                echo regions[3]
            }
        }
     }
 }
