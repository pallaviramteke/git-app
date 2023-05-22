pipeline{
agent{
label{
label "slave-2"
customWorkspace "/mnt/pipeline"
}
}
stages{
stage ("stage-2"){
steps{
sh "yum install httpd -y"
sh "service httpd start"
sh "cp -r index.html /var/www/html/"
sh "chmod -R 777 /var/www/html/index.html"
}
}
}
}
