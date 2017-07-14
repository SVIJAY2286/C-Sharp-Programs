//Simple to Understand for late binding
using System;

namespace late_Binding
{
	class MainClass
	{
		public static void Main (string[] args)
		{
			int a, b;
			int ans1, ans2,ans3,ans4;
			Console.WriteLine ("Enter the A : ");
			a = Convert.ToInt32( Console.ReadLine());
			Console.WriteLine ("Enter the B : ");
			b = Convert.ToInt32( Console.ReadLine ());
			cipher ci = new cipher ();
			ans1=ci.add1 (a, b);
			Console.WriteLine ("ANS 1 :"+ans1);
			ans2=ci.sub (a, b);
			Console.WriteLine ("ANS 2 :"+ans2);
			ci = new sub_ciber ();
			ans3=ci.add1 (a, b);
			Console.WriteLine ("ANS 3 :"+ans3);
			ans4=ci.sub (a, b);
			Console.WriteLine ("ANS 4 :"+ans4);

		}
	}
	class cipher
	{   int c;
		public virtual int add1(int a,int b)
		{
			c = a + b;
			return c;
		}
		public virtual int sub(int a,int b)
		{
			c = a - b;
			return c;
		}

}
	class sub_ciber:cipher{
		int c;
		public override int add1(int a,int b)
		{
			c = a - b;
			return c;
		}
		public override int sub(int a,int b)
		{
			c = a + b;
		return c;
		}
	}
}
