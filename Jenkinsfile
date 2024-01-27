pipeline{
agent{
label{
label "slave-1"
customWorkspace "/mnt/workspace-1"
}
}
stages{
stage("stage-1"){
steps{
sh "rm -rf *"
sh "mkdir new-dir-1"
}
}
stage("wsp"){
steps{
dir("/mnt/data"){
sh "rm -rf *"
sh "mkdir wsp-dir-1"
}
}
}
}
}
