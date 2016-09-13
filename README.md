//# Homework Num 2
// my argument values are: [2.5] & [2.5]
public class Area {
	public static void main(String[] w){
		String length = w[0];
		String width = w[1];
		double newlength = Double.parseDouble(length);
		double newwidth = Double.parseDouble(width);
		double area = newlength*newwidth;
		System.out.print(area+" Inches");
	}
}
