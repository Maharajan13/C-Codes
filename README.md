using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp2
{
    internal class operators1
    {
        static void Main(string[] args)

        {
            int num1 = 35;

            Console.WriteLine("value of num1 =" + num1);
            Console.WriteLine("pre increment of num =" + (++num1));
            Console.WriteLine();


            Console.WriteLine("value of num =" + num1);
            Console.WriteLine("pre decrement of num =" + (--num1));

            Console.WriteLine();

            int num2 = 20;
            Console.WriteLine("value of num2 =" + num2);
            Console.WriteLine("post increment =" + (num2++));
            Console.WriteLine();

            Console.WriteLine("value of num2 =" + num2);

            Console.WriteLine("value of num2 =" + num2);
            Console.WriteLine("post decrement =" + (num2--));
            Console.WriteLine();

            Console.WriteLine("value of num2 =" + num2);

            Console.WriteLine("------------binary operator---------------");

            arithmetic opertaor

            int x = 15;
            int y = 20;

            Console.WriteLine("addition of value is =" + (x + y));
            Console.WriteLine("subtraction of value is =" + (x - y));
            Console.WriteLine("multiplication of value is =" + (x * y));
            Console.WriteLine("division of value is =" + (x / y));
            Console.WriteLine("modulus of value is =" + (x % y));


            Console.WriteLine();

            int num = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("valu of num is " + num);
            Console.WriteLine("type of value" + num.GetType());

            int k = 15;
            int j = 20;

                Console.WriteLine("value of addition=" + (k + j));
                Console.WriteLine();



                Console.WriteLine("-------------assiganment-----------");

                int t = 100;

                t = t + 1;
                Console.WriteLine("value of t is =" + t);

            t = t - 1;
            Console.WriteLine("value of t is = " + t);

            //relational opertor

            int x = 50;
            int y = 50;

            Console.WriteLine("is x is greater than y=" + (x > y));

            Console.WriteLine("is y is less than x=" + (y < x));

            Console.WriteLine("is x is greater than y=" + (x < y));

            Console.WriteLine("is x is greater than y=" + (x >= y));

            int g = 5;
            int h = 5;

            Console.WriteLine("is g anf h is equal to =" + (g == h));

            Console.WriteLine("is g and h is not eqaul to =" + (g != h));

            Console.WriteLine();//

            Console.WriteLine("--------------------------------");








        }



    }
}
