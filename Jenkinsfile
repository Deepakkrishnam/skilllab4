pipeline{
   agent any
   
   stages{
      stage('Checkout'){
          steps {
              git branch: 'main',url:
'https://github.com/Deepakkrishnam/SkillLab01.git' 
          } 
      }
      stage('Hello'){
           steps {
                echo "Hello from Jenkins Pipeline!"
           }
      }
      stage('Goodbye'){
         steps{
             echo "pipeline finished successfully"
          }       
         }  
        } 
       }
