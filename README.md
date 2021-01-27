# vb-wrangle

- The assigned play was Tragedy part 2.

- The file data.txt contans the data on which the bash commands are used.


## The command used to find the Speaker 1:
```Powershell
grep -i 'MENENIUS' data.txt -c
```
- This returns the MENENIUS count present in the data.

## The command used to find the Speaker 2:
```Powershell
grep -i 'MARCIUS' data.txt -c
```
- This returns the MARCIUS count present in the data.

- The above results are stored respectively in the meneniusCount.txt and marciusCount.txt files.

- The sum of both the counts is stored in the result.txt file.

## Commands to add the meneniusCount and marciusCount:
```Powershell
read a< 'marciusCount.txt'
read b< 'menenniusCount.txt'
printf "%d\n" $(( $a + $b )) > result.txt
```
- The above commands will store the sum of the both the counts of the file and return the result to the file named result.txt.