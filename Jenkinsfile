pipeline{
    agents any
    tools {
	  terraform 'myterraform'
	}
    stages{
       stage('initializing teraform'){
         steps{
            sh"terraform init"
         }
       }

   }
}
