pipeline{
agent{
label{
label "built-in"
customWorkspace "/mnt/assign-5"
}
environment{
url = https://github.com/mundevjvs/new-repo-123.git
}
stages{
stage("clone-repo"){
steps{
sh "rm-rf *"
sh "git clone $url"
}
}
}
}


}
