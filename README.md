# Source-Code
package Latihan1;
import javax.swing.JOptionPane;
public class Latihan1 {
public static void main(String[] args) {
JOptionPane.showMessageDialog(null,"Hello World");
}
}

package Latihan2;
import javax.swing.JOptionPane;
public class Latihan2 {
public static void main(String[] args) {
int input= JOptionPane.showConfirmDialog(null,"Chose One");
System.out.println("value = "+input);
}
}

package Latiha3;
import javax.swing.JOptionPane;
public class Latihan3 {
public static void main(String[] args) {
int input= JOptionPane.showConfirmDialog(null,"Click this if you are 
ok?", "i'm ok",JOptionPane.DEFAULT_OPTION);
System.out.println("value = "+input);
}
}

package Latihan4;
import javax.swing.JOptionPane;
import javax.swing.ImageIcon;
public class Latihan4 {
public static void main(String[] args) {
ImageIcon icon = new ImageIcon("icon-feel.png");
int input= JOptionPane.showConfirmDialog(null,"Are you happy right 
now?", "Your feeling today",JOptionPane.YES_NO_CANCEL_OPTION, 
JOptionPane.QUESTION_MESSAGE, icon);
System.out.println("value = " +input);
}
}

package Latihan5;
import javax.swing.JOptionPane;
public class Latihan5 {
public static void main(String[] args) {
int pilih = JOptionPane.showOptionDialog(null, 
 "Apakah anda menyukasi sate?", 
 "Pilih Makanan", 
 JOptionPane.YES_NO_CANCEL_OPTION, 
 JOptionPane.QUESTION_MESSAGE, null, null, null);
 
 if(pilih == JOptionPane.YES_OPTION){
 JOptionPane.showMessageDialog(null, "Saya menyukai sate");
 }else if(pilih == JOptionPane.NO_OPTION) {
 JOptionPane.showMessageDialog(null, "Saya tidak menyukai sate");
 }else {
 JOptionPane.showMessageDialog(null, "Tidak memilih");
 } 
}
}

package Latihan6;
import javax.swing.JOptionPane;
public class Latihan6 {
public static void main (String[] args){
 String input;
 float n1,n2,pilih,hasil;
 input=JOptionPane.showInputDialog(" Pilih Menu \n 1. Penjumlahan \n 2. 
Pengurangan \n 3. Perkalian \n 4. Pembagian ");
 pilih=Integer.parseInt(input);
 input=JOptionPane.showInputDialog("Masukkan angka pertama");
 n1=Integer.parseInt(input);
 input=JOptionPane.showInputDialog("Masukkan angka kedua");
 n2=Integer.parseInt(input);
 if(pilih==1){
 hasil=n1+n2;
 JOptionPane.showMessageDialog( null,"Hasil : " + hasil
,"Kalkulator", JOptionPane.INFORMATION_MESSAGE );
 }else if(pilih==2){
 hasil=n1-n2;
 JOptionPane.showMessageDialog( null,"Hasil : " + hasil
,"Kalkulator", JOptionPane.INFORMATION_MESSAGE );
 }else if(pilih==3){
 hasil=n1*n2;
 JOptionPane.showMessageDialog( null,"Hasil : " + hasil
,"Kalkulator", JOptionPane.INFORMATION_MESSAGE );
 }else if(pilih==4){
 hasil=n1/n2;
 JOptionPane.showMessageDialog( null,"Hasil : " + hasil
,"Kalkulator", JOptionPane.INFORMATION_MESSAGE );
 }else{
 JOptionPane.showMessageDialog( null,"Kode Yang Anda 
Masukkan Salah" ,"Error!", JOptionPane.INFORMATION_MESSAGE );
 }
}
}
