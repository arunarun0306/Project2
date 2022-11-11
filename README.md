# Project2
package string;

public class OnetoHundredwithoutforlooping {
	
	
	
	public static void  withoutloop (int startsfrom, int endfrom)
	
	{
		
		if(startsfrom<endfrom)
			
		{
			System.out.println(startsfrom);
			
			startsfrom++;
			
			withoutloop (startsfrom, endfrom);
			
		}
	}
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		withoutloop(34, 56);
		
	}

}
