Pipeline
       {
       agent any
             stages
                  {
                  stage("Git")
                      {
                     steps
                         {
                      git "https://github.com/Nagaraju118/jenkins_practice.git"
                         }
                  stage("Run")
                      {
                     steps
                         {
                         sh "java demo.java"
                         sh "main.py"
                          }
                        }
                    }
          }
}
                     
                  
