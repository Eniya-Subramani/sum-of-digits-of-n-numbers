# sum-of-digits-of-n-numbers
Public class Thesumoftheditsofanumber{
Public static void main(String[] args) {
int num=25,rem=0,sum=0,temp;
temp=num;
while(num&gt;0)
{
rem=num%10;
sum=sum+rem;
num=num/10;
}

System.out.println(&quot; Sum of the digits of &quot; + temp + &quot; is &quot; + sum);
}
}
OUTPUT:
Sum of the digits of 25 is 7
