# Basic-Calculator
Compute the sum, difference, mulpication and division of any two numbers
import java.awt.*;

import javax.swing.*;
import java.awt.event.*;





public class calculator extends JFrame {


private JTextField textField1 = null;
private JTextField textField2 = null;
private JTextField textField3 = null;
private JLabel label1 = null;
private JLabel label2 = null;
private JLabel label3 = null;
GridBagConstraints layoutConstraints = null;
JButton button1 = null;
JButton button2 = null;
JButton button3 = null;
JButton button4 = null;
JButton button5 = null;
JButton button6 = null;
JButton button7 = null;

public calculator() {
	
	this.setLayout(new GridBagLayout());
	label1 = new JLabel("1st Value");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 0;
	layoutConstraints.gridy = 0;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(label1, layoutConstraints);
	
	textField1 = new JTextField(15);
	textField1.setText("0");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 1;
	layoutConstraints.gridy = 0;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(textField1, layoutConstraints);
	
	label2 = new JLabel("2nd Value");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 0;
	layoutConstraints.gridy = 1;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(label2, layoutConstraints);
	
	textField2 = new JTextField(15);
	textField2.setText("0");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 1;
	layoutConstraints.gridy = 1;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(textField2, layoutConstraints);
	
	
	label3 = new JLabel("Answer");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 0;
	layoutConstraints.gridy = 2;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(label3, layoutConstraints);
	
	textField3 = new JTextField(15);
	textField3.setText("0");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 1;
	layoutConstraints.gridy = 2;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	this.add(textField3, layoutConstraints);
	

	button1 = new JButton("+");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 0;
	layoutConstraints.gridy = 3;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button1.addActionListener(new ActionListener() {
		@Override
		public void actionPerformed(ActionEvent e) {
			
			int val1 = Integer.parseInt(textField1.getText());
			int val2 = Integer.parseInt(textField2.getText());
			textField3.setText(Integer.toString(val1 + val2));
		}
	});
	this.add(button1, layoutConstraints);
	
	button2 = new JButton("-");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 1;
	layoutConstraints.gridy = 3;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button2.addActionListener(new ActionListener() {
		@Override
		public void actionPerformed(ActionEvent e) {
			
			int val1 = Integer.parseInt(textField1.getText());
			int val2 = Integer.parseInt(textField2.getText());
			textField3.setText(Integer.toString(val1 - val2));
		}
	});
	this.add(button2, layoutConstraints);
	
	button3 = new JButton("/");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 2;
	layoutConstraints.gridy = 2;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button3.addActionListener(new ActionListener() {
		@Override
		public void actionPerformed(ActionEvent e) {
			
			int val1 = Integer.parseInt(textField1.getText());
			int val2 = Integer.parseInt(textField2.getText());
			textField3.setText(Integer.toString(val1 / val2));
		}
	});
	this.add(button3, layoutConstraints);
	
	button4 = new JButton("*");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 2;
	layoutConstraints.gridy = 3;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button4.addActionListener(new ActionListener() {
		@Override
		public void actionPerformed(ActionEvent e) {
			
			int val1 = Integer.parseInt(textField1.getText());
			int val2 = Integer.parseInt(textField2.getText());
			textField3.setText(Integer.toString(val1 * val2));
		}
	});
	this.add(button4, layoutConstraints);
	
	button5 = new JButton("=");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 2;
	layoutConstraints.gridy = 1;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button5.addActionListener(new ActionListener() {
		@Override
		public void actionPerformed(ActionEvent e) {
			
			int val1 = Integer.parseInt(textField1.getText());
			int val2 = Integer.parseInt(textField2.getText());
			///textField3.setText(Integer.toString(val1 * val2));
		}
	});
	this.add(button5, layoutConstraints);
	
	button7 = new JButton("Reset");
	layoutConstraints = new GridBagConstraints();
	layoutConstraints.gridx = 2;
	layoutConstraints.gridy = 0;
	layoutConstraints.insets = new Insets(10, 10, 10, 10);
	button7.addActionListener(new ActionListener() {
		public void actionPerformed(ActionEvent e) {
			textField1.setText("0");
			textField1.setText("");
			textField2.setText("0");
			textField2.setText("");
			textField3.setText("0");
			textField3.setText("");
		}
	});
	this.add(button7, layoutConstraints);
}

public static void main(String[] args) {
	
	calculator frame = new calculator();
	
	frame.pack();
	frame.setVisible(true);
	frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
}
}
