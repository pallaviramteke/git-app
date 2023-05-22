pipeline{
agent{
label{
label "slave-2"
customWorkspace "/mnt/pipeline"
}
}
stages{
stage ("stage-3"){
steps{
sh "sudo yum install httpd -y"
sh "sudo service httpd start"
sh "sudo cp -r index.html /var/www/html/"
sh "sudo chmod -R 777 /var/www/html/index.html"
}
}
}
}
