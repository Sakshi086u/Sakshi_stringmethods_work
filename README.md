# Sakshi_stringmethods_work
public class String_methods {
    public static void main(String[] args) {
       
        //lenght()method//
    String name= new String("Harry");
    int value= name.length();
    System.out.println(value);
    
    //tolowercase method//
   String lString=name.toLowerCase();
   System.out.println(lString);
   
   //touppercase method//
   String uString=name.toUpperCase();
    System.out.println(uString);

    //trim method//
    String nontrimmString ="hello";
    System.out. println(nontrimmString);
    String trimmString =nontrimmString.trim();
    System.out.println(trimmString);

    //substring method//
    String node= "Harry";
    System.out.println(node.substring(1));
    
    //charat mathod//
     String myStr = "Hello";
    char result = myStr.charAt(0);
    System.out.println(result);
}
}
