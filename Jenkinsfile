node {
  
stage('SQLMap Scan') {
            steps {
                script {
                    def targetUrl = "http://192.168.1.2:8089/getAllBooks"
                    def sqlmapOptions = "--batch --dbs"
 
                    sh "sqlmap -u ${targetUrl} ${sqlmapOptions}"
                }
            }
        }  
}
