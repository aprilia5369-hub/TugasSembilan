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
      <img width="577" height="414" alt="image" src="https://github.com/user-attachments/assets/cd2229cb-459c-4a69-9aac-954ad3dde0c1" />
2. nama dan lokasi sesuai dengan data base
      <img width="667" height="486" alt="image" src="https://github.com/user-attachments/assets/3bd2da30-b4fd-467c-892f-cde615264ec6" />
3. isi query (SELECT * From [DATABASEMU])
      <img width="681" height="498" alt="image" src="https://github.com/user-attachments/assets/baa08912-cc92-4e6c-8688-09d3f639deef" />
4. Pindahkan field ke sisi kanan
      <img width="669" height="481" alt="image" src="https://github.com/user-attachments/assets/3324e97f-b7c4-41d7-b2c1-30ba8be17942" />
5. Langsung klik Next saja
      <img width="705" height="511" alt="image" src="https://github.com/user-attachments/assets/0eb32287-4956-4460-848e-b00bf21be873" />
6. Finish
      <img width="701" height="497" alt="image" src="https://github.com/user-attachments/assets/01f4645a-3059-4460-97c5-5110f56b3efb" />
8. Sediakan Lib berisi : PostgreSQL JDBC DRIVER, Commons – collection, Groovy, Jasperreports, Absolutelayout, Commons – digester, Commons – logging, Itext – pdfa,Itext - pdf
      <img width="528" height="515" alt="image" src="https://github.com/user-attachments/assets/261e4fd5-5ee8-4a83-b1bd-6f8d67753406" />
9. Tambahkan Import :
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperCompileManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperPrint;
import net.sf.jasperreports.engine.JasperReport;
import net.sf.jasperreports.engine.util.JRLoader;
import net.sf.jasperreports.view.JasperViewer;
      <img width="939" height="707" alt="image" src="https://github.com/user-attachments/assets/5c017943-8c07-4042-9c7b-8b8132351410" />
09 Tambahkan Button Cetak
      <img width="940" height="614" alt="image" src="https://github.com/user-attachments/assets/6087e32e-6677-4a55-849e-724a9f98a784" />
10. Run
      <img width="940" height="689" alt="image" src="https://github.com/user-attachments/assets/dddd9e51-ffe6-4145-9613-7ead1f61b4e0" />
