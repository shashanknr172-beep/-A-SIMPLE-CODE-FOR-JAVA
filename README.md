/its the simple code which represents the concept of nested loop in java programming

/Say "hi" once → then say "bye" twice

 class Simple {
    public static void main(String[] args) 
    {
    for (int i = 1; i <= 1; i++) 
    {
    System.out.println("hi " + i);

for (int j = 1; j <= 2; j++) 
{
  System.out.println("bye " + j);
            }
        }
    }
}



Output will be:
hi 1
bye 1
bye 2

