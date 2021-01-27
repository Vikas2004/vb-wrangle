# vb-wrangle

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

- The sum of both the counts is stored in the output.txt file.