# big-data-shell
Shell commands for processing data

- ls - to list files in the directory
- ls -a - to list all file in the directory
- mkdir - to create a file in the directory
- cd .. - to move back to parent
- code . - to open with vs code
- touch - to create file
- curl - to open an url

## Bash Commnads

- tr ' ' '\12' < input.txt
=> To transform the space character into a return character.
- tr ' ' '\12' < returnedfile | sort
 => pipe the output to sort
- tr ' ' '\12' < returnedfile | sort | uniq -c
  => Pipe the sorted output to uniq -c to count
- tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr
   => pipe the reduced output to sort with -nr flag
