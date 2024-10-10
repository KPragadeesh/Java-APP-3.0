@Library('my-shared-library') _

pipeline{

    agent any
    stages{
        stage('Git Checkout'){
            steps{
            gitCheckout(
                branch: "master",
                url: "https://github.com/KPragadeesh/Java-APP-3.0.git"
            )
            }
        }

}
}
