package first;

import javax.swing.JTextField;

public class refresh {
	public static void RefreshReading(JTextField textField,JTextField textField_1) 
			throws InterruptedException {
		String url = textField.getText();
		for(int i=0;i<=Integer.valueOf(textField_1.getText());i++){
			System.out.println(i);
			HttpUtil.sendGet(url, null);
			Thread.sleep(10);
		}
	}
}
