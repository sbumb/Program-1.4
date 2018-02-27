# Program-1.4
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

(Print a table) Write a program that displays the following table:
a      a^2    a^3 
1      1      1 
2      4      8 
3      9      27 
4      16     64

    public class oneFour {//open class
	
	    public static void main (String args[]){//open main
		
		    int a, b;
		    System.out.println("a       b       pow(a,b)");
		
		    a = 1;
		    b = 2;
		
		    for(int i = 0; i <=4; i++ ){//open for
		    System.out.println((int)a + "       " + (int)b + 
		  		"        " + (int)Math.pow(a,b));
		    a++;
		    b++;
		
		    }//close For 
	    }//close main
    }//close class
