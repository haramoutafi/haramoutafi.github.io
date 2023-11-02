bandit1
ls 
cat readme

bandit2
ls
cat ./-

bandit3
ls 
cat"spaces in this filename"
 bandit4
 ls -a
 cat./.hidden

 bandit5 
 ls
 cat inhere
 ls
 cat./-file00
 cat./-file01
  cat./-file02
   cat./-file03
    cat./-file04
     cat./-file05
      cat./-file06
       cat./-file07
 bandit6
 ls
 cd inhere
 find -size 1033c
 cat ./maybehere07/.file2

 bandit7
 ls
 ls -a
 find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
 cat /var/lib/dpkg/info/bandit7.passsword


bandit8
ls
cat data.txt | grep millionth

bandit9
ls
cat data.txt | sort | uniq -u

bandit10
ls
cat data.txt | strings | grep=

bandit11
ls
cat data.txt | base64 --decode
