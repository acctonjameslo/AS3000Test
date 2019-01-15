pipeline {
    agent any
    
    stage('Test') {
        parallel {
            stage('Unit Test') {
                                steps {
                                        echo 'Running the unit test . . .'
                                }
            }
            
            stage('Integration test') {
                                steps {
                                    echo 'Running the integration test . . .'
                                }
            
            }
        }
    }            
}        
            
        
