pipeline {                                      // Defines the start of the Jenkins pipeline block
    agent any                                  // Specifies the pipeline can run on any available agent
    environment {                              // Defines environment variables for the pipeline
        PATH = "/opt/maven/bin:$PATH"          // Adds Maven's path to the system's PATH variable
    }                                          // Ends the environment block
    
        stage('build') {                       // Creates a stage named 'build'
            steps {                            // Defines the steps that will be executed in this stage
                sh 'mvn clean package'         
            }                                  // Ends the steps block for 'build' stage
        }                                      // Ends the 'build' stage
    }                                          // Ends the stages block
                                               // Ends the pipeline block

