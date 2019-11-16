pipeline {
   agent any
   input {
  message 'please provide input'
  parameters {
    [choiceType: 'PT_CHECKBOX', description: '', filterLength: 1, filterable: false, name: 'pls provide inputs', randomName: 'choice-parameter-5614706189870', script: [$class: 'GroovyScript', fallbackScript: [classpath: [], sandbox: false, script: ''], script: [classpath: [], sandbox: false, script: 'return[\'1\',\'2\',\'3\']']]]
  }
}
   stages {
      stage ("build"){
         echo "Hello World!"
      }
   }
   
}
