# accessmodifers
package com.delegation;

public class RealPrinter {
	void display()
    {
        System.out.println("Hello World!");
    }
}
package com.delegation2;

import com.delegation.RealPrinter;

public class Printer{
	
	public static void main(String args[])
    {  
       //accessing class Geek from package p1
       RealPrinter obj = new RealPrinter();

       obj.display();
    }
}
package com.delegation;

class RealPrinter {
	private void display()
    {
        System.out.println("Hello World!");
    }
}
package com.delegation;



public class Printer{
	
	public static void main(String args[])
    {  
       //accessing class Geek from package p1
       RealPrinter obj = new RealPrinter();

       obj.display();
    }
}
