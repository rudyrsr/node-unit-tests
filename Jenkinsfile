pipeline{
    agent none;
    environment {
      myUsername = "RUDYRSR"
    }
    stages{
        stage("Test")
        {
            steps{
                script{
                    node{
                        print"Mi primer stage esta en ejecucion !!!"
                        echo "mi nombre es :${myUsername}"
                    }
                }
            }
            
            
        }
        stage("Test2")
        {
            steps{
                script{
                    node{
                        print"Mi segundo stage esta en ejecucion !!!"
                    }
                }
            }
            
            
        }
        stage("Test3")
        {
            steps{
                script{
                    node{
                        print"Mi tercer stage esta en ejecucion !!!"
                    }
                }
            }
            
            
        }
    }
    
    
}
