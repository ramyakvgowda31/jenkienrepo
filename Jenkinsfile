pipeline {
    agent any
    stages {
        stage ("check conditions choice 1"){
            when {
                expression {choice == '1'}
             }
              steps{
                    echo "hello,choice1!"
                }
        }
        stage ("check the condition choice 2"){
            when {
                expression {choice == '2'}
               }
                 steps {
                    echo "hello,choice2"
                }
        }
    }
}
