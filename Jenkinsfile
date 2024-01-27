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
  echo "this is 23Q1 branch"
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
