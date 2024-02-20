# hacker-rank-Print-the-string-.
The included code stub will read an integer, , from STDIN.  Without using any string methods, try to print the following:   Note that "" represents the consecutive values in between.  Example  Print the string .
The included code stub will read an integer, , from STDIN.

Without using any string methods, try to print the following:


Note that "" represents the consecutive values in between.

Example

Print the string .

Input Format

The first line contains an integer .

Constraints
1<=n<-100

Output Format
Print the list of integers from  through  as a string, without spaces.


if __name__ == '__main__':
    n = int(input())
    for i in range(1,n+1):
        print(i,end='')
