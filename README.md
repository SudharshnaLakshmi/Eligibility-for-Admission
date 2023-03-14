# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
1. Start the program
2. Declare variables to store physics, chemistry and math marks, total marks and percentage.
3. Ask the user to input the physics, chemistry, and math marks.
4. Read the values of physics, chemistry, and math marks from the user.
5. Calculate the total marks as the sum of physics, chemistry, and math marks.
6. Calculate the total marks as the sum of physics and math marks.
7. Check if the total mark of maths, physics and chemistry is greater or equal to the given condition or total marks of maths and physics is greater then or equal to given condition.
8. If the conditions in step 7 are true, display "You are eligible for admission to an engineering course."
9. If the conditions in step 7 are false, display "You are not eligible for admission to an engineering course."
10. End the program.

## Program:
```
NAME : SUDHARSHNA LAKSHMI S
REG.NO : 212221230110
```
```
using System;
public class EX01
{
    public static void Main()
    {
        int p, c, m;
        Console.Write("Find eligibility for admission :\n");
        Console.Write("Input the marks obtained in Physics :");
        p = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input the marks obtained in Chemistry :");
        c = Convert.ToInt32(Console.ReadLine());
        Console.Write("Input the marks obtained in Mathematics :");
        m = Convert.ToInt32(Console.ReadLine());
        Console.Write("Total marks of Maths, Physics and Chemistry : {0}\n", m + p + c);
        Console.Write("Total marks of Maths and  Physics : {0}\n", m + p);

        if (m >= 65 && p >= 55 && c >= 50)
        {
            if ((m + p + c) >= 180 || (m + p) >= 140)
            {
                Console.Write("The  candidate is eligible for admission.\n");
            }
            else
            {
                Console.Write("The candidate is not eligible.\n\n");
            }
        }
        else
        {
            Console.Write("The candidate is not eligible.\n\n");
        }
            
    }
}

```
## Output:
![o](out.png)

## Result:
The C# program to find the eligibility for admission to an engineering course has been executed successfully.