node {
  stage('Nmap Scan') {
     sh "nmap -sV -T4 -A -v -Pn --script vuln 192.168.1.2 "              

        }
  
stage('SQLMap Scan') {
            sh "sqlmap -u http://192.168.1.2:8089/getAllBooks --batch --dbs"

            
        }  
}
