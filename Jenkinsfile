pipeline{
    agent{
        label "any"
    }
    stages{
        stage("Echo") {

            steps{
                echo "Jaya Guru Datta"
            }
            
        }
    }
    post{
        always{
            echo "Finished Posting"
        }
        
    }
}