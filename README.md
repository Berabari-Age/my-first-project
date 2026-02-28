input: mkdir projects

output: cd projects

input: mkdir week1 week2

output: cd week1

input: touch hello.txt

ls week1 output: hello.txt

input: cp hello.txt /c/Users/USER/projects/week2/hello_copy.txt

ls week2 hello_copy.txt

cd week1 input: rm hello.txt

ls week1

output: "empty" cd ..

ls week2 hello_copy.txt

cd ..

cd projects

input: vim about_me.txt

output: My motivations for learning Node.js is because with Node.js, I can build website fast for my startup, manage web packages and also automate tasks.