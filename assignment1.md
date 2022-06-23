using System;

  class Program 
  {  
       public static void Main(string[] args) 
       {  
        Console.WriteLine("Enter the your choice:"); 
        Console.WriteLine("Addition\n");  
        Console.WriteLine("Subtraction\n");  
        Console.WriteLine("Multiplication\n");  
        Console.WriteLine("Division \n"); 
        
        int a = Convert.ToInt32(Console.ReadLine());  
        Console.WriteLine("Enter 1st value");  
        int val1 = Convert.ToInt32(Console.ReadLine());  
        Console.WriteLine("Enter 2nd value");  
        int val2 = Convert.ToInt32(Console.ReadLine());  
           
            int result = 0;  
            switch (a) {  
                case 1: {  
                    result = Addition(val1, val2);  
                    break;  
                }  
                case 2: {  
                    result = Subtraction(val1, val2);  
                    break;  
                }  
                case 3: {  
                    result = Multiplication(val1, val2);  
                    break;  
                }  
                case 4: {  
                    result = Division(val1, val2);  
                    break;  
                }  
                default:  
                Console.WriteLine("invalid input try again");  
                    break;  
            }  
            Console.WriteLine("The result is {0}", result);  
            Console.ReadKey();  
        }  
        //Addition  
        public static int Addition(int n1, int n2)
        {  
            int result = n1 + n2;  
            return result;  
        }  
        //Substraction  
        public static int Subtraction(int n1, int n2) {  
            int result = n1 + n2;  
            return result;  
        }  
        //Multiplication  
    public static int Multiplication(int n1, int n2) 
        {  
            int result = n1 + n2;  
            return result;  
        }  
        //Division  
        public static int Division(int n1, int n2)
        {  
            int result = n1 + n2;  
            return result;  
        }  
    }
