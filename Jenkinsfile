pipeline{
    agent any
    triggers{
      githubPush()
     }
     stages{
        stages('Checkout'){
          steps{
            checkout scm
          }
        }
    }
}
