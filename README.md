<img width="479" height="306" alt="image" src="https://github.com/user-attachments/assets/eff88127-8bd8-46f0-a442-c7d5c1957f08" /># TugasSembilan
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
2. Downloaded --> Add Plugins  masukkan Ireport - designer, jasperserver – plugin, jasperreport – extensions, jasperreports – components, dan org-jdesktop-layout-RELEASE65.nbm --> instal
3. Pilih plugins vesri jasperserver-plugin [1,0] --> install
4. Klik restart IDE Now --> now
 
MENCETAK DATA MENGGUNAKAN JASPER REPORT
1. New --> Report Wizard --> pilih layout --> Finish
2. nama dan lokasi sesuai dengan data base
3. isi query (SELECT * From [DATABASEMU])
4. Pindahkan field ke sisi kanan
5. Langsung klik Next saja
6. Finish
7. Sediakan Lib berisi : PostgreSQL JDBC DRIVER, Commons – collection, Groovy, Jasperreports, Absolutelayout, Commons – digester, Commons – logging, Itext – pdfa,Itext - pdf
8. Tambahkan Import :
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperCompileManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.JasperReport;
import net.sf.jasperreports.engine.util.JRLoader;
import net.sf.jasperreports.view.JasperViewer; 
10. Tambahkan Button Cetak
11. Run
 

 













Pindahkan field ke sisi kanan
 

Langsung klik Next saja

