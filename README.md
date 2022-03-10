# singleton-
public class Singleton {
	
	static Singleton instance = new Singleton();
	public static String str;
	
	private Singleton()
	{
		
	}
	
	public static Singleton getSingleInstance()
	{
		return instance;
	}


} 
