pipeline{
   agent any
   stages{
       stage('saludo'){
           steps{
             echo 'hola'
           }
       }
       stage('version'){
           steps{
             echo 'version'
 
           }
       }
       stage('despedida'){
           steps{
             echo 'adios'
           }
       }
   }
   post{
       always{
           echo 'salgo siempre'
       }
       success{
           echo 'todo ok'
       }
       failure{
           echo 'xxxxplosion'
       }
       changed{
           echo 'ha cambiado'
       }
   }
}
