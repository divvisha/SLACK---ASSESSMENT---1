# SLACK---ASSESSMENT---1
# Divyashree B S
# Register no-212221040044
## 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
```java  
  import java.util.Scanner;
  public class Main
  {
       public static void main(String[] args)
       {

          Scanner s=new Scanner(System.in);
          int a=s.nextInt();
          int b=s.nextInt();
          System.out.println("Sum of the input number:"+(a+b));
          System.out.println("Difference of the input number:"+(a-b));
          System.out.println("Product of the input number:"+(a*b));
          System.out.println("Quotient of the input number:"+(a/b));
          System.out.println("Remainder of the input number:"+(a%b));
       }
  }
  ```
 ## Output
 ![1st pgrm](https://user-images.githubusercontent.com/127508123/224499104-a3e2e934-e440-44db-b6a6-038fb0e00be3.jpeg)
    
    
## 2. Write a Java program to compare two numbers
```java   
  import java.util.Scanner;
  public class Main
  {
        public static void main(String[] args)
        {
           Scanner s=new Scanner(System.in);
           int x=s.nextInt();
           int y=s.nextInt();
           if(x>y)
           {
              System.out.println(x+" is greater than "+y);
           }
           else if(x<y)
           {
              System.out.println(y+" is greater than "+x);
           }
           else
           {
              System.out.println("Both inputs are equal");
           }
        }
  }
  ```
## Output
![2nd pgrm](https://user-images.githubusercontent.com/127508123/224499212-811e846b-0134-4fa7-9258-97026c0c0d69.jpeg)


## 3. Write a Java program to convert a string to an integer
```java
   public class Main 
   {
       public static void main(String[] args)
       {
          String sc="200";
          int i=Integer.parseInt(sc);
          System.out.println(i);
       }
   }
   ```
## Output
![3rd pgrm](https://user-images.githubusercontent.com/127508123/224499637-da46c563-ab1f-4649-94fd-c520a5167934.jpeg)
    
    
## 4. Java Program to find area of rhombus 
```java
   import java.util.Scanner;
   public class Main
   {
       public static int rhombus(int p,int q)
       {
          return ((p*q)/2);
       }
          public static void main(String[] args)
       {
          Scanner s=new Scanner(System.in);
          int dia1=s.nextInt();
          int dia2=s.nextInt();
          System.out.print("Area of Rhombus=");
          System.out.println(rhombus(dia1,dia2));
       }
   }
   ```
## Output
![4th pgrm](https://user-images.githubusercontent.com/127508123/224499980-7b481527-7cf8-4b29-baa6-b38c16db97d6.jpeg)
    
    
 ## 5. Write a Java program to find the number of days in a month
 ```java
    import java.util.Scanner;
    public class Main
    {
        public static void main(String[] args)
        {
           Scanner s=new Scanner(System.in);
           int month=s.nextInt();
           int year=s.nextInt();
           if((month==1)||(month==3)||(month==5)||(month==7)||month==8||month==10||month==12)
           {
              System.out.println("This month has 31 Days.");
           }
           else if((month==4)||(month==6)||(month==9)||(month==11))
           {
              System.out.println("This month has 30 Days.");
           }
           else
           {
              if ((year % 400 == 0) || ((year % 4 == 0) && (year % 100 != 0)))
              {
                 System.out.println("This month has 29 Days.");
              }
              else
              {
                 System.out.println("This month has 28 Days.");
              }
           }
        }
   }
   ```
## Output
![5th pgrm](https://user-images.githubusercontent.com/127508123/224500774-3bd70237-10d7-45b2-91fe-4338f2a36ebf.jpeg)
    
    
## 6. Write a Java program to print the even numbers from 1 to 20
```java
  import java.util.Scanner;
  public class Multiplication_Table 
  {
       public static void main(String[] args) 
       {
          Scanner s = new Scanner(System.in);
	        System.out.print("Enter number:");        
	        int n=s.nextInt();
          for(int i=1; i <= 10; i++)
          {
             System.out.println(n+" * "+i+" = "+n*i);
          }
       }
  }
  ```
## Output
![6th pgrm](https://user-images.githubusercontent.com/127508123/224501052-d52a430e-57ac-4de2-80cc-3ab2c9fa800c.jpeg)

    
## 7. Write a Java program to create a simple calculator
```java
  import java.util.Scanner;
  class Main 
  {
       public static void main(String[] args) 
       {
           char operator;
           Double number1, number2, result;
           Scanner input = new Scanner(System.in);
           System.out.println("Choose an operator: +, -, *, or /");
           operator = input.next().charAt(0);
           System.out.print("Enter first number=");
           number1 = input.nextDouble();
           System.out.print("Enter second number=");
           number2 = input.nextDouble();
           switch (operator)
           {
              case '+':
               result = number1 + number2;
               System.out.println(number1 + " + " + number2 + " = " + result);
               break;
              case '-':
               result = number1 - number2;
               System.out.println(number1 + " - " + number2 + " = " + result);
               break;
              case '*':
               result = number1 * number2;
               System.out.println(number1 + " * " + number2 + " = " + result);
               break;
              case '/':
               result = number1 / number2;
               System.out.println(number1 + " / " + number2 + " = " + result);
               break;
              default:
               System.out.println("Invalid operator!");
               break;
            }
            input.close();
        }
  }
  ```
## Output
![7th pgrm](https://user-images.githubusercontent.com/127508123/224501213-af8cba8c-e05f-409b-8fe0-db3591db8391.jpeg)

    
## 8. Write a Java program to print multiplication table of given number  
```java
  import java.util.Scanner;
  public class Multiplication_Table 
  {
       public static void main(String[] args) 
       {
          Scanner s = new Scanner(System.in);
	        System.out.print("Enter number:");        
	        int n=s.nextInt();
          for(int i=1; i <= 10; i++)
          {
             System.out.print(n+" * "+i+" = "+n*i+"\n");
          }
       }
  }
  ```
## Output
![8th pgrm](https://user-images.githubusercontent.com/127508123/224501385-a69fd6cd-df0e-4424-9c3e-99306f67451e.jpeg)

