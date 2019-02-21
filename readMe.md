<h1>ETU TVL Language</h1>
<p>Javacc yardımı ile üç değerli mantık dili için tercuman uygulaması geliştirilmiştir. <br>
Projenin detayları Assignment.pdf içerisinde mevcuttur.</p>

<p>Windows işletim sistemi için çalıştırma klavuzu aşağıdaki gibidir.</p>
<p>NOT: JDK 1.5 kullanılması javacc için tavsiye edilir.</p>

1. javacc-6.0.jip dosyasını yerel disk C nin içerisine çıkartın. 
2. C:\javacc-6.0\bin\lib yoluna girin. 
3. Bu klasörün içerisine javacc.bat dosyasını yerleştirin.
4. Path yolu olarak C:\javacc-6.0\bin\lib ekleyin.
5. Çalıştırmak için aşağıdaki yolu izleyin.

```bash
cd src
javacc ETUTVL.jj
javac *.java
java ETUTVL example.tx

```