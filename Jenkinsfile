pipeline{
agent any 

  stages{
  
  stage('testread properties')
    {
     steps{
    echo "Testing read properties done.."
        script{
         // def d=[Name: 'Ankit', Last_Name: 'Grover', phoneNO: 'xxxxxxxxxx']
//           def props= readProperties defaults: d, file: 'dir/my.properties', text: 'other=Override'
           def props= readProperties file: './version.tf'
        props.each{k,v->
          println "The key is ${k} and value is ${v}" 
        }
        }
    }
      
      
      
      
      
      
    }
  
  
  
  
  }


}
