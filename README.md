# Github-Storage-Abuse-Testing


## Create a 1 MB File Using Bash - This generates a binary file of size 1 MB

bash command
>> dd if=/dev/urandom of=testfile_1mb.bin bs=1M count=1



## Bash Script to Copy File 100 Times
bash command

for i in $(seq -w 1 100); do
  cp testfile_1mb.bin "testfile_1mb_copy_$i.bin"
done
