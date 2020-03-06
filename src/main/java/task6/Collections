package task6;
import java.util.*;
public class Collections
{
	static ArrayList<String> a=new ArrayList<String>();
	static void print()
	{
		int n=a.size();
		for (int i=0;i<n;i++)
		{
			System.out.println(a.get(i));
		}
	}
	static void fetch(int x)
	{
		System.out.println("Element is:"+a.get(x));
	}
	static void add(String x )
	{
		a.add(x);
		System.out.println("successfully added");
	}
	static void remove(int n)
	{
		String s=a.get(n);
		a.remove(n);
		System.out.println("successfully removed**    "+s);
	}

	public static void main(String[] z)
	{
		Scanner w=new Scanner(System.in);
		a.add("Apple");
		a.add("Orange");
		a.add("Avacado");
		a.add("Pears");
		a.add("Grapes");
		a.add("Melon");
		a.add("Pineapple");
		a.add("Kiwi");
		a.add("Guava");
		a.add("Pomogranate");
		System.out.println("Initial List");
		print();
		while(true)
		{
			System.out.print("1.print\t2.fetch\t3.remove\t4.add\t5.exit\nEnter operation :");
      int n=w.nextInt();
			if(n==1)
			{
				print();
			}
			else if(n==2)
			{
				System.out.print("enter element index:");
				int x=w.nextInt();
				fetch(x);
			}
			else if(n==3)
			{
				System.out.print("enter element index:");
				int x=w.nextInt();
				remove(x);
			}
			else if(n==4)
			{
				System.out.print("enter element :");
				String x=w.next();
				add(x);
			}
			else
			{
				break;
			}
		}
		System.out.println("exit");
	}
}
