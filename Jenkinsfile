pipeline{
agent any 

  stages{
  
  stage('testread properties')
    {
     steps{
    echo "Testing read properties done.."
        script{
          def d=[Name: 'Ankit', Last_Name: 'Grover', phoneNO: 'xxxxxxxxxx']
          def props= readProperties defaults: d, file: 'dir/my.properties', text: 'other=Override'
        props.each{k,v->
          prinltn "The key is ${k} and value is ${v}" 
        }
        }
    }
      
      
      
      
      
      
    }
  
  
  
  
  }


}
