using System;

namespace final1
{
    class Program
    {
        static void Main(string[] args)
        {




            {
                Console.WriteLine("Enter your  name please");
                var firstName = Console.ReadLine();

                Console.WriteLine("Second name Please");
                var secondName = Console.ReadLine();
                Console.WriteLine("Your real name is:" + firstName + secondName);
            }


            {
                Console.WriteLine("Enter your age please");
                var age = Console.ReadLine();

                int newage = int.Parse(age);


                if (newage <= 17)
                {
                    Console.WriteLine("NOT eligible to vote in the system");
                }
                else
                {
                    Console.WriteLine("Congratulations!,You are now eligible to vote, follow the required steps to attain a voting card");
                }

            }



            {

                Console.WriteLine("Enter the first number of your desire to be manipuated in th system Please!");
                var firstNumber = Console.ReadLine();

                Console.WriteLine("Enter your second number please!");
                var secondNumber = Console.ReadLine();

                Console.WriteLine("Enter the operator you could wish to use for the manipulation (+, *, /, -)");
                var operation = Console.ReadLine();

                int firstNum = int.Parse(firstNumber);
                int secondNum = int.Parse(secondNumber);



                if (operation == "+")
                {
                    Console.WriteLine(firstNum + secondNum);
                }
                if (operation == "*")
                {
                    Console.WriteLine(firstNum * secondNum);
                }
                if (operation == "/")
                {
                    Console.WriteLine(firstNum / secondNum);
                }
                if (operation == "-")
                {
                    Console.WriteLine(firstNum - secondNum);
                }
            }
        }
    }
}    
      

