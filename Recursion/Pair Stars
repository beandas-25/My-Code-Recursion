//To add a "*" between each repeating characters in the string.
//From line 2 to 20 is my code.
public static String addStars(String s,int si){
        if(si==s.length()-1){
            return s;
        }
        if(s.charAt(si)==s.charAt(si+1)){
            s=s.substring(0,si+1)+"*"+s.substring(si+1);
        }
        s=addStars(s,si+1);
        return s;
    }
    

	// Return the updated string
	public static String addStars(String s) {
        String res=addStars(s,0);
        return res;
		// Write your code here

	}
  //This below is the solution code provided by CN
    /*public static String addStars(String s){
        if(s.length()<=1){
            return s;
        }
        String out=addStars(s.substring(1));
        if(s.charAt(0)==s.charAt(1)){
            out=s.charAt(0)+"*"+out;
        }
        else
            out=s.charAt(0)+out;
    
   		 return out;
    }*/
