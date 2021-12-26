import javax.swing.JFrame;
import java.awt.Graphics;
import java.awt.Color;

public class Man extends JFrame{
	public Man(){
		setTitle("Man");
		setSize(1000,1000);
		setVisible(true);
		setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

	}
	public void paint(Graphics g){
		Color c1= new Color(255,51,153);
		Color c2=  new Color(18,11,16);
		Color c3= new Color(240,38,7);
		Color c4 = new Color(18,11,16);
		Color c5= new Color(255,255,0);
		Color c6= new Color(0,0,255);
		Color c7 = new Color(0,255,0);
		Color c8=new Color(0,255,0);
		Color c9= new Color(240,38,7);
		
		  g.setColor(c1);
		  g.fillOval(400,100,150,150);  
		  
          g.setColor(c2);
		  g.fillOval(425,150,25,25);
		  
		  g.setColor(c3);
		  g.drawArc(420,120,100,100,240,70);
		  
		  g.setColor(c4);
		  g.fillOval(500,150,25,25);;
		  
		  g.setColor(c5);
		  g.fillRect(445,245,55,60);
		  
		  g.setColor(c6);
		  g.fillRect(360,273,230,260);
		  
		  g.setColor(c7);
		  g.fillRect(360,534,55,160);
		 
		  g.setColor(c8);
		  g.fillRect(530,534,55,160);
		   
		  g.setColor(c9);
		  g.drawLine(360,270,200,400);
		  
		  g.setColor(c9);
		  g.drawLine(360,525,200,390);
		  
		  g.setColor(c9);
		  g.drawLine(600,280,750,400);
		  
		  g.setColor(c9);
		  g.drawLine(589,530,750,400);

		}
		 
		public static void main(String[]args){
			Man n= new Man();
		}
	
	
	
}
