# project1
class Prime1
{
	public static void main(String[] args)
	{
		int n=203;
		int count=0;
		if(n==1)
		 System.out.println("it is not prime");
		else
		{
		for(int i=1;i<=n;i++)
		{
			if((n%i)==0)
				count++;
		}
		if(count==2)
		{
			System.out.println("number is prime");
		}
		else
			System.out.println("number is not prime");
		}
		
	}
	
}
