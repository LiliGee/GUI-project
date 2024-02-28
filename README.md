import javax.swing.JOptionPane;
public class GUI {
public static void main(String[] arg){

	String name = JOptionPane.showInputDialog("Enter your name:");
	JOptionPane.showInternalMessageDialog(null, "Hello " + name);

	int age = Integer.parseInt(JOptionPane.showInputDialog("Enter your age:"));
	JOptionPane.showInternalMessageDialog(null, "WOW, You are " + age + "!!! You look gorgeous for your age!");
	
	double height = Double.parseDouble(JOptionPane.showInputDialog("Enter your height:"));
	JOptionPane.showInternalMessageDialog(null, "You are " + height + "cm tall? Girl, you are definitely a model!");
}
}
