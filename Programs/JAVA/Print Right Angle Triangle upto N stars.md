# Problem
## Question
>WAP to print right angle triangle upto N stars

## Solution
>import java.util.* ;
>
>class Solution
>
>{
>
>    public static void main(String[] args)
>    
>    {
>    
>        Scanner sc = new Scanner(System.in);
>        System.out.println("Enter the number of rows");
>        int n = sc.nextInt();
>        int i, j;
>        for (i = 1; i <= n; i++) 
>        {
>            for (j = 1; j <= i; j++) 
>            {
>                System.out.print(" * ");
>            }
>            System.out.println();
>        }
>        
>    }
>    
>}
