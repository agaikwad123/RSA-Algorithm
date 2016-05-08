# RSA-Algorithm
RSA Algorithm

#include&lt;stdio.;

#include&lt;conio.h&gt;

#include&lt;math.h&gt;

void main()

{

Int p,q,n,e=7,m,fi,c,i,temp,j,c1=1;

clrscr();

printf(&quot;Enter the value of p&quot;);

scanf(&quot;%d&quot;,&amp;p);

printf(&quot;Enter the value of q&quot;);

scanf(&quot;%d&quot;,&amp;q);

printf(&quot;calculating value of n:\n&quot;);

n=p*q;

printf(&quot;%d&quot;,n);

printf(&quot;Calculating value of fi:&quot;);

fi=(p-1)*(q- 1);

printf(&quot;\n&quot;);

printf(&quot;%d&quot;,fi);

printf(&quot;So public key Pk=(e,n=\n)&quot;);

printf({%d,%d},e,n);

printf(\n&);

printf(****Performing Encryption ****\);

printf(Enter the value of plain text m:\);

scanf(&quot;%d&quot;,&amp;m);

for(i=1;i&lt;=e;i++)

c1=c1*(m)%n;

c=c1%n;

printf(&quot;cipher text c=%d&quot;,c);

getch();

}
