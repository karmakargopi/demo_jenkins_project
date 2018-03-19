def Globals {
    static String[] regions = ["north-america.ca", "japan-korea.jp", "lodon-spain.eu"]
}
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
