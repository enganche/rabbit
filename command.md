# Use for log
node emit "1st task";
node emit "2nd task";
node emit "3rd task";
node emit "4th task";
node emit "5th task";
node emit "6th task";
node emit "7th task";
node emit "8th task";
node emit "9th task"

# Use for worker
node new-task "1st task";
node new-task "2nd task";
node new-task "3rd task";
node new-task "4th task";
node new-task "5th task";
node new-task "6th task";
node new-task "7th task";
node new-task "8th task";
node new-task "9th task"

# use for topic
node receive "*.orange.cat"
node receive "#.cat"
node receive "quick.#"

node emit "lazy.orange.cat" "A lazy and orange cat";
node emit "quick.brown.fox" "A quick and brown fox";
node emit "quick.white.cat" "A  quick and white cat";
node emit "quick.black.dog" "A  quick and white dog";
clear