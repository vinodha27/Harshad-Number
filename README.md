# Harshad-Number

int p=353;
            int t,c=0;
            int n=p;
            while(n>0)
            {
                t=n%10;
                c=c+t;
                n=n/10;
            }
            if(p%c==0)
            {
                System.out.println("Harshad Number");
            }
            else
            {
                System.out.println("Not Harshad Number");
            }
