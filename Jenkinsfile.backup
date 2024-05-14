@Library('roboshop-shared-library') _
def configmap = [application: "nodejsvm", component: "catalogue"]
echo "hello true"
if(!(env.branch_name.equalsIgnoreCase('master')))
{
    pieplinedecission.buildpipeline(configmap)
}
else
{
    echo "master branch" 
}