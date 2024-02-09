using System;

namespace CalculatorApp
{
    internal class Program
    {
        static void Main(string[] args)
        {
            decimal firstNumber, secondNumber, result = 0;
            char operation;

            Console.Write("Enter The First Number: ");
            while (!decimal.TryParse(Console.ReadLine(), out firstNumber)) 
            {
               Console.Write("Please Enter aNumber: ");
            }

            Console.WriteLine("Enter (+) or (-) or (*) or (/)");
            while (!char.TryParse(Console.ReadLine(), out operation))
            {
                Console.Write("Please Enter Valid Operator: ");
            }

            Console.Write("Enter The Second Number: ");
            while (!decimal.TryParse(Console.ReadLine(), out secondNumber))
            {
                Console.Write("Please Enter aNumber: ");
            }

            if(operation == '+')
            {
                result = firstNumber + secondNumber;
            }
            else if(operation == '-')
            {
                result = firstNumber - secondNumber;
            }
            else if(operation == '*')
            {
                result = firstNumber * secondNumber;
            }
            else if(operation == '/')
            {
                if(secondNumber != 0)
                {
                    result = firstNumber / secondNumber;
                }
                else
                {
                    Console.WriteLine("You Can not Dividing by zero");
                }
            }

            Console.Write($"Reasult is = {result}");
        }
    }
}
