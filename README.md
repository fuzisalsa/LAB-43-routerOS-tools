# LAB-43-routerOS-tools
24 agustus 2025 

# RouterOS Tools
RouterOS Tools adalah alat bantu (utility tools) yang tersedia di MikroTik RouterOS untuk melakukan pemantauan, pengujian, dan analisis jaringan.

# A. Alat Monitoring & Analisis Jaringan

1. **Ping:**               Mengirim ICMP echo ke host/IP untuk mengecek konektivitas dan latency.             
2. **Traceroute:**         Melacak jalur yang dilalui paket data hingga ke host tujuan.                      
3. **Torch:**              Memonitor trafik real-time pada interface (menampilkan IP, port, protokol).      
4. **Netwatch:**           Monitor status UP/DOWN dari host (IP/Domain) + eksekusi script.                    
5. **Traffic Monitor:**    Memantau trafik interface, dan bisa menjalankan script saat melebihi batas.        
6. **Graphing:**           Menampilkan grafik statistik penggunaan CPU, memory, interface, queue, dll.        
7. **Profile:**            Menampilkan penggunaan CPU oleh proses aktif (analisa beban CPU).                  
8. **Resource:**           Menampilkan statistik sistem (CPU, RAM, HDD, uptime, temperatur, voltase).         
9. **Interface Monitor:**  Melihat penggunaan TX/RX real-time pada interface tertentu.                        
10. **SNMP:**               Mengaktifkan SNMP agar router bisa dimonitor dengan tool eksternal (Zabbix, PRTG). 

# B. Alat Pengujian (Testing Tools)

1. **Bandwidth Test:**  Menguji throughput antara dua perangkat MikroTik (client-server test).                     
2. **Ping Flood:**      Ping intensif untuk uji kestabilan link.                                                   
3. **IP Scan:**         Mencari perangkat aktif dalam subnet tertentu.                                             
4. **MAC Scan:**        Mencari perangkat aktif berdasarkan alamat MAC di jaringan lokal.                          
5. **Traceroute:**      Melacak jalur trafik (mirip ping + hop).                                                   
6. **Fetch:**           Mengunduh file dari URL tertentu (via HTTP/FTP).                                           
7. **Speed Test:**      Mirip Bandwidth Test, namun menggunakan server MikroTik yang mendukung SpeedTest protocol. 

# C. Alat Penangkapan dan Diagnostik

1. **Packet Sniffer:**        Menangkap paket data di interface tertentu (seperti Wireshark, bisa export ke PCAP).     
2. **Sniffer Protocols:**     Melihat statistik protokol yang lewat (ICMP, TCP, UDP, dll).                            
3. **Ping Tool (Advanced):**  Ping ke host dengan pengaturan lebih lengkap dari ping biasa.
   
# D. Manajemen File dan Backup

1. **File:**              Mengelola file di router (upload, download, backup, export, log).      
2. **Backup / Restore:**  Backup seluruh konfigurasi MikroTik ke file binary (.backup).          
3. **Export / Import:**   Menyimpan/menjalankan konfigurasi dalam format script (.rsc).          
4. **Scheduler:**         Menjadwalkan perintah atau script untuk dijalankan secara otomatis.    
5. **Netinstall:**        Tool eksternal untuk menginstal ulang RouterOS via Ethernet.           
6. **License:**           Menampilkan status lisensi RouterOS.                                   

# E. Tool Keamanan & Akses

1. **Password Recovery:**  Untuk pemulihan password (khusus dalam kondisi tertentu).        
2. **User Management:**    Mengelola user, group, dan hak akses.                       
3. **Watchdog:**           Restart otomatis router jika mengalami hang/freeze.          
4. **System Clock:**       Sinkronisasi waktu (manual/NTP).                             

**Tips Penggunaan:**

Gunakan **Netwatch + Scripts** untuk monitoring otomatis + action.  
Gunakan **Torch & Packet Sniffer** untuk troubleshooting bandwidth.  
Gunakan **Graphing** jika tidak pakai monitoring eksternal seperti Zabbix.   
Gunakan **Scheduler** untuk otomatisasi (restart modem, ping loop, dll).   
Gunakan **Bandwidth Test** hanya untuk test internal (karena menyita CPU).   

# kesimpulan
RouterOS Tools membantu mengelola, memantau, dan menguji jaringan MikroTik secara mudah dan efisien.
# sumber
https://citraweb.com/artikel/81/

