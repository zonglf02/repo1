node {
   stage 'build'
   def whatThe = someFunc('build')
   def whatThe2 = someFunc2('build2')
}

node {
   stage 'test'
   def whatThe = someFunc('test')
   def whatThe2 = someFunc2('test2')
}

node {
   stage 'deploy'
   def whatThe = someFunc('deploy')
   def whatThe2 = someFunc2('deploy2')
}

def someFunc(String text){
    echo text
    text
}
def someFunc2(String text2){
    echo text2
    text2
}
