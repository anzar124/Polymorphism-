# Primeno-

class prime {
    public static void main(String[] args) {
boolean prime;

int i,last,n;

System.out.println("Prime numbers between 3 to 100:"); for(n=3;n<100;n=n+2) 

{

if (n<4)

{

prime=true;

System.out.println(n);

continue;

}

prime=true;

i=3;

last=(int)Math.sqrt(n);

do

{

if (n%i==0)

{

prime=false;

break;

}

i=i+2;

}while (prime && (i<last));

if (prime) System.out.println (n);

} 

}

}

    


