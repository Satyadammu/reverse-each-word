# reverse-each-word
import java.util.*;

public class reverseeachword {

public static void main(String[] args) {

String str;

Scanner sc=new Scanner(System.in);

System.out.println("Enter String");

str=sc.nextLine();

String strWords[] = str.split("\\s");

String rev = "";

for(String sw : strWords) {

StringBuilder sb = new StringBuilder(sw);

sb.reverse();

rev += sb.toString() + " ";

}

System.out.println( rev.trim());

}

}
