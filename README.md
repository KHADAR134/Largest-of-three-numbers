# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers
## Algorith:
### Step1:
Start<br/>
### Step2:
Create a class and declare three variable with integer datatype<br/>
### Step3:
Use if condition to check whether num1 is largest than num2 and num3<br/>
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3<br/>
### Step5:
Use else condition to display that third variable is largest among all the variables<br/>
### Step6:
stop<br/>

## Program:
```
using System;
namespace vijay
{
    class program
    {
            static void Main(string[] args)
            {
                int num1, num2, num3;
                Console.WriteLine("Enter Three integer");
                num1 = Convert.ToInt32(Console.ReadLine());
                num2 = Convert.ToInt32(Console.ReadLine());
                num3 = Convert.ToInt32(Console.ReadLine());
            if ((num1 > num2) && (num1 > num3))
                Console.WriteLine(num1 + " is Greater");
            else if ((num2 > num1) && (num2 > num3))
                Console.WriteLine(num2 + " is Greater");
            else
                Console.WriteLine(num3 + " is Greater");
        }
    }
}
```

## Output:

![ol(1)](https://user-images.githubusercontent.com/75235233/164294940-0d00069f-6580-4e04-869c-6acd643e3d53.png)


## Result:
Thus the C# program to find the largest of three numbers is executed successfully
