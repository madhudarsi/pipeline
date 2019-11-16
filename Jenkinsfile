pipeline {
   agent any
  
   stages {
      stage ("build"){
         steps {
         input message: 'pls select number', parameters: [[$class: 'ChoiceParameter', choiceType: 'PT_CHECKBOX', description: '', filterLength: 1, filterable: false, name: '', randomName: 'choice-parameter-6408924691709', script: [$class: 'GroovyScript', fallbackScript: [classpath: [], sandbox: false, script: ''], script: [classpath: [], sandbox: false, script: 'return[\'1\',\'2\',\'3\']']]]]
         echo "Hello World!"
      }
   }
   }
}
