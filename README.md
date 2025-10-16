# TugasSembilan
# Jasper Report
JasperReport adalah library open-source berbasis Java yang digunakan untuk membuat dan menampilkan laporan dari berbagai sumber data seperti database, XML, JavaBeans, atau file CSV.
Laporan yang dihasilkan dapat diekspor ke berbagai format seperti PDF, HTML, XLS, DOC, RTF, dan lainnya.
Fungsi utama JasperReport:
•	Mengambil data dari database menggunakan query SQL.
•	Menggabungkan data dengan template laporan (.jrxml).
•	Menghasilkan output laporan dalam format yang dapat dicetak atau disimpan
# IReport
iReport Designer adalah alat bantu visual (GUI) untuk mendesain laporan Jasper tanpa perlu menulis XML secara manual.

# STEPS
INSTALL JREPORT DAN IREPORT
1. Pilih Tools --> Plugins
   <img width="1080" height="690" alt="Screenshot 2025-10-14 191250" src="https://github.com/user-attachments/assets/5c55601e-538f-41ef-b867-27d0c0d6edc0" />

2. Downloaded --> Add Plugins  masukkan Ireport - designer, jasperserver – plugin, jasperreport – extensions, jasperreports – components, dan org-jdesktop-layout-RELEASE65.nbm --> instal
<img width="498" height="310" alt="image" src="https://github.com/user-attachments/assets/1ed45827-b972-4db8-8226-09499c2b4a92" />

3. Pilih plugins vesri jasperserver-plugin [1,0] --> install
   <img width="621" height="368" alt="image" src="https://github.com/user-attachments/assets/e9cca58e-21e0-44fe-824e-8f65e4cd568d" />

5. Klik restart IDE Now --> now
 <img width="641" height="391" alt="image" src="https://github.com/user-attachments/assets/aaa52025-ab66-4021-8abf-128b73a30225" />

MENCETAK DATA MENGGUNAKAN JASPER REPORT
1. New --> Report Wizard --> pilih layout --> Finish 
2. nama dan lokasi sesuai dengan data base
3. isi query (SELECT * From [DATABASEMU]) 
4. Pindahkan field ke sisi kanan
5. Langsung klik Next saja 
6. Finish
8. Sediakan Lib berisi : PostgreSQL JDBC DRIVER, Commons – collection, Groovy, Jasperreports, Absolutelayout, Commons – digester, Commons – logging, Itext – pdfa,Itext - pdf 
9. Tambahkan Import :
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperCompileManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.JasperReport;
import net.sf.jasperreports.engine.util.JRLoader;
import net.sf.jasperreports.view.JasperViewer; 
10 Tambahkan Button Cetak
11. Run

    <img width="1897" height="918" alt="Screenshot 2025-10-15 171854" src="https://github.com/user-attachments/assets/d7089238-8b77-4250-ba77-eda75a4473e9" />

