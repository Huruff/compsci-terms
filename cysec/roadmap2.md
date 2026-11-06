# Roadmap lengkap belajar Cybersecurity dari nol

Untuk kondisi teman Anda — pemula total, belum memiliki pengetahuan IT/cybersecurity, dan ingin memulai dengan anggaran Rp0 — strategi terbaik adalah:

1. Memahami semua cabang cybersecurity terlebih dahulu.
2. Membangun fondasi IT yang bisa digunakan di semua cabang.
3. Mencoba beberapa bidang melalui lab gratis.
4. Memilih satu atau dua spesialisasi.
5. Mengerjakan proyek yang bisa dimasukkan ke portfolio.
6. Baru mempertimbangkan kursus berbayar, sertifikasi, atau perangkat tambahan.

Saya akan membagi cybersecurity menjadi 12 jalur spesialisasi. Ini merupakan pengelompokan praktis untuk belajar dan berkarier, bukan daftar eksklusif jabatan resmi. NIST NICE juga mengelompokkan pekerjaan cybersecurity berdasarkan fungsi, tugas, pengetahuan, dan keterampilan, bukan sekadar nama jabatan.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.nist.gov\&sz=32)

NIST+1

# 1. Cybersecurity bisa ke bidang apa saja?

## Peta spesialisasi

<img width="518" height="459" alt="image" src="https://github.com/user-attachments/assets/a943d965-7c08-49f7-bfc1-0f329786280b" />

## Perbandingan karakteristik bidang

| Bidang              | Aktivitas pekerjaan                         | Coding        | Matematika    | Dominan             |
| ------------------- | ------------------------------------------- | ------------- | ------------- | ------------------- |
| SOC / Blue Team     | Memonitor dan menganalisis serangan         | Sedang        | Rendah–sedang | Analisis            |
| Red Team / Pentest  | Menguji kelemahan sistem                    | Sedang–tinggi | Rendah–sedang | Teknis              |
| AppSec              | Mengamankan aplikasi                        | Tinggi        | Rendah        | Programming         |
| Cloud Security      | Mengamankan infrastruktur cloud             | Sedang–tinggi | Rendah        | Infrastruktur       |
| Network Security    | Melindungi jaringan                         | Rendah–sedang | Rendah–sedang | Infrastruktur       |
| Malware Research    | Membongkar dan memahami malware             | Tinggi        | Sedang–tinggi | Analisis teknis     |
| DFIR                | Menyelidiki insiden dan bukti digital       | Sedang        | Rendah–sedang | Investigasi         |
| GRC                 | Mengelola risiko, kebijakan dan audit       | Rendah        | Rendah–sedang | Dokumentasi         |
| IAM                 | Mengelola identitas dan hak akses           | Sedang        | Rendah        | Administrasi        |
| DevSecOps           | Mengintegrasikan keamanan dalam development | Tinggi        | Rendah        | Programming         |
| Threat Intelligence | Menganalisis informasi ancaman              | Rendah–sedang | Rendah–sedang | Riset               |
| OT / IoT Security   | Mengamankan perangkat dan sistem industri   | Sedang–tinggi | Sedang        | Hardware & jaringan |

Coding dan matematika di atas merupakan gambaran relatif, bukan syarat mutlak untuk setiap pekerjaan.

## Bagaimana membedakan bidang-bidangnya?

Contoh kasus: sebuah perusahaan mengalami serangan ransomware.

| Tim / bidang        | Apa yang dikerjakan?                                                        |
| ------------------- | --------------------------------------------------------------------------- |
| SOC Analyst         | Menemukan aktivitas mencurigakan dari log dan alert                         |
| Network Security    | Memeriksa bagaimana lalu lintas jaringan dapat menjadi jalur serangan       |
| Incident Response   | Menghentikan penyebaran dan memulihkan sistem                               |
| Digital Forensics   | Mencari bukti bagaimana serangan terjadi                                    |
| Threat Intelligence | Mengidentifikasi pola serangan dan kemungkinan kelompok pelaku              |
| Malware Analyst     | Menganalisis file ransomware                                                |
| Red Team            | Menguji apakah kelemahan serupa masih dapat dieksploitasi                   |
| Cloud Security      | Memeriksa apakah infrastruktur cloud ikut terdampak                         |
| GRC                 | Memastikan pelaporan, kebijakan, risiko, dan kewajiban perusahaan ditangani |
| IAM                 | Memeriksa penyalahgunaan akun dan hak akses                                 |
| DevSecOps / AppSec  | Memperbaiki kelemahan aplikasi dan pipeline yang mungkin dimanfaatkan       |

Jadi, satu insiden keamanan dapat melibatkan banyak spesialisasi sekaligus.

# 2. Fondasi umum: materi yang harus dipelajari semua jalur

Karena teman Anda benar-benar pemula, jangan langsung memilih Kali Linux atau melakukan penetration testing. Fondasi ini akan membuatnya lebih mudah berpindah bidang.

Tahap A — Computer Fundamentals

Materi:

- Hardware, software, RAM, CPU, storage.
- Sistem operasi dan file system.
- Cara kerja aplikasi, browser, dan server.
- Command Prompt dan PowerShell dasar.

Platform: Cisco Networking Academy dan Microsoft Learn.

Tahap B — Networking Fundamentals

Materi:

- IP address dan subnetting.
- TCP, UDP, port.
- DNS, DHCP, HTTP, HTTPS.
- Router, switch, firewall.
- Client-server communication.

Platform: Cisco Networking Academy dan Cisco Packet Tracer.

Tahap C — Operating System Fundamentals

Materi:

- Linux dan Windows.
- Terminal dan Linux command line.
- User, group, permission.
- Process, service, file system.
- Basic system administration.

Platform: OverTheWire Bandit dan Linux lab.

Tahap D — Programming Fundamentals

Materi:

- Python dasar.
- Variabel, kondisi, perulangan, fungsi.
- Membaca dan memproses file.
- JSON, CSV, log.
- SQL dasar dan Bash.

Platform: Python tutorial dan VS Code.

Tahap E — Security Fundamentals

Materi:

- Confidentiality, Integrity, Availability (CIA).
- Authentication dan Authorization.
- Encryption dan hashing.
- Vulnerability dan exploit.
- Risk, threat, attack surface.
- Backup, patching, dan access control.
- Etika serta batasan hukum pengujian.

Platform: Cisco Introduction to Cybersecurity dan Microsoft Learn.

Platform fondasi yang sebaiknya dipakai pertama kali:

| Platform                                                                                                                    | Biaya           | Fungsi                            | Alasan dipilih                                        |
| --------------------------------------------------------------------------------------------------------------------------- | --------------- | --------------------------------- | ----------------------------------------------------- |
| [Cisco Introduction to Cybersecurity](https://www.netacad.com/courses/introduction-to-cybersecurity?utm_source=chatgpt.com) | Gratis          | Dasar cybersecurity               | Tersedia bahasa Indonesia                             |
| [Cisco Networking Academy](https://www.netacad.com/?utm_source=chatgpt.com)                                                 | Gratis          | Jaringan dan IT                   | Dasar untuk hampir semua spesialisasi                 |
| [OverTheWire Bandit](https://overthewire.org/wargames/bandit/?utm_source=chatgpt.com)                                       | Gratis          | Linux dan terminal                | Belajar dengan menyelesaikan tantangan                |
| [Microsoft Learn](https://learn.microsoft.com/en-us/training/?utm_source=chatgpt.com)                                       | Gratis          | Security, cloud, Windows, dan IAM | Materi resmi dan terstruktur                          |
| [TryHackMe](https://tryhackme.com/?utm_source=chatgpt.com)                                                                  | Gratis terbatas | Praktik cybersecurity             | Memperkenalkan aktivitas hacking dalam lab terkontrol |

Cisco menyediakan kursus pengantar cybersecurity yang mencakup konsep dasar dan tersedia dalam bahasa Indonesia. OverTheWire Bandit dirancang secara khusus untuk pemula yang belum terbiasa dengan Linux.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.netacad.com\&sz=32)

netacad.com+2



Hasil yang harus dicapai sebelum memilih spesialisasi: teman Anda sudah bisa menjelaskan bagaimana komputer berkomunikasi melalui jaringan, menggunakan terminal, mengenali fungsi port dan protokol, serta memahami konsep dasar keamanan.

# 3. Analisis platform: gratis dahulu, berbayar kemudian

Berikut platform yang menurut saya paling berguna untuk membangun keterampilan nyata.

| Platform                                                                             | Fokus                                     | Akses gratis                                       | Kapan membayar?                                                |
| ------------------------------------------------------------------------------------ | ----------------------------------------- | -------------------------------------------------- | -------------------------------------------------------------- |
| [TryHackMe](https://tryhackme.com/?utm_source=chatgpt.com)                           | Praktik lintas bidang                     | Room gratis dan akses AttackBox terbatas           | Ketika ingin membuka learning path dan lab premium             |
| [HTB Academy](https://academy.hackthebox.com/?utm_source=chatgpt.com)                | Pentesting, SOC, Linux, dan infrastruktur | Tier 0 gratis dan akun baru mendapat 200 Cubes     | Ketika ingin modul khusus dan jalur lanjutan                   |
| [PortSwigger Academy](https://portswigger.net/web-security?utm_source=chatgpt.com)   | Web & API Security                        | Seluruh materi dan lab akademi gratis              | Tidak perlu membayar untuk memulai; Burp Professional opsional |
| [CyberDefenders](https://cyberdefenders.org/blue-team-labs/?utm_source=chatgpt.com)  | SOC, DFIR, threat hunting                 | Memiliki lab gratis                                | Ketika ingin akses materi atau fitur tambahan                  |
| [AWS Training](https://www.aws.training/?utm_source=chatgpt.com)                     | Cloud Security                            | Banyak materi digital gratis melalui Skill Builder | Ketika membutuhkan lab immersive dan persiapan tertentu        |
| [Microsoft Learn](https://learn.microsoft.com/?utm_source=chatgpt.com)               | Azure, IAM, security                      | Materi self-paced gratis                           | Ketika membutuhkan sertifikasi atau layanan praktik tertentu   |
| [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/?utm_source=chatgpt.com) | Web App Security                          | Gratis dan open source                             | Tidak perlu membayar                                           |
| [OWASP SAMM](https://owaspsamm.org/?utm_source=chatgpt.com)                          | Secure Software Development               | Gratis                                             | Tidak perlu membayar untuk mempelajari modelnya                |
| [NIST CSF](https://www.nist.gov/cyberframework?utm_source=chatgpt.com)               | GRC dan risk management                   | Gratis                                             | Kursus sertifikasi profesional bisa dipertimbangkan kemudian   |
| [REMnux](https://docs.remnux.org/?utm_source=chatgpt.com)                            | Malware analysis                          | Gratis dan open source                             | Tidak perlu membayar untuk toolkit-nya                         |

Beberapa batasan yang perlu dipahami:

- TryHackMe Free memiliki akses room terbatas dan batas AttackBox satu jam sehari. Premium menyediakan akses lebih luas.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://tryhackme.com\&sz=32)

  Premium Plans

- HTB Academy memberikan Tier 0 gratis dan 200 Cubes saat akun baru dibuat.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://academy.hackthebox.com\&sz=32)

  Hack The Box Academy

- PortSwigger Web Security Academy benar-benar gratis, termasuk interactive labs. Burp Suite Community Edition cukup untuk memulai.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://portswigger.net\&sz=32)

  portswigger.net+1

- CyberDefenders menyediakan latihan Blue Team langsung dari browser tanpa perlu menyiapkan lab sendiri.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://cyberdefenders.org\&sz=32)

  CyberDefenders

- AWS Skill Builder menawarkan lebih dari 1.000 sumber belajar gratis, sementara sebagian fitur lab dan pembelajaran immersive memerlukan langganan.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://aws.amazon.com\&sz=32)

  AWS



Strategi biaya: jangan membayar beberapa platform sekaligus. Mulai dari Cisco + OverTheWire + TryHackMe Free. Setelah tahu minatnya, tambahkan hanya satu platform spesialisasi berbayar.

# 4. Persyaratan perangkat, RAM, aplikasi, dan resource

Ini penting karena beberapa bidang membutuhkan perangkat yang jauh lebih kuat dibandingkan bidang lain.

## A. Spesifikasi laptop

Rekomendasi praktis berdasarkan jenis lab, bukan persyaratan resmi universal setiap platform.

| Komponen       | Minimum untuk mulai     | Rekomendasi            | Advanced lab         |
| -------------- | ----------------------- | ---------------------- | -------------------- |
| CPU            | 4-core                  | 6-core                 | 8-core atau lebih    |
| RAM            | 8 GB                    | 16 GB                  | 32 GB                |
| Storage        | SSD 256 GB              | SSD 512 GB             | SSD 1 TB             |
| GPU            | Integrated              | Integrated             | Tidak wajib          |
| OS             | Windows / Linux / macOS | Windows 11 atau Ubuntu | Linux dan Windows VM |
| Virtualization | Opsional                | Aktif                  | Aktif                |
| Internet       | Stabil                  | Stabil                 | Stabil               |

### Mengapa RAM menjadi penting?

Bayangkan komputer menjalankan beberapa mesin sekaligus:

Contoh penggunaan RAM saat praktik

<img width="778" height="370" alt="image" src="https://github.com/user-attachments/assets/09a1de5e-1ac3-4ffd-b893-ed116f7aaf8d" />

Perkiraan alokasi, bukan benchmark atau penggunaan RAM yang dijamin. Host membutuhkan ruang tambahan untuk cache dan proses lain.

Dengan RAM 8 GB, teman Anda masih dapat belajar melalui browser, cloud lab, dan beberapa aplikasi ringan. Tetapi menjalankan beberapa VM sekaligus akan terbatas.

## B. Aplikasi yang sebaiknya disiapkan

| Aplikasi             | Fungsi                         | Kegunaan bidang              |
| -------------------- | ------------------------------ | ---------------------------- |
| Chrome / Firefox     | Browser dan pengujian web      | Semua bidang                 |
| VS Code              | Editor kode                    | AppSec, DevSecOps, scripting |
| Git                  | Version control                | AppSec, DevSecOps            |
| Python               | Automation dan analisis        | Hampir semua bidang teknis   |
| Ubuntu / WSL2        | Linux environment              | SOC, Red Team, DevOps        |
| VirtualBox           | Menjalankan virtual machine    | Pentest, malware, DFIR       |
| Wireshark            | Analisis traffic jaringan      | Network, SOC, DFIR           |
| Nmap                 | Network discovery dan scanning | Network, Red Team            |
| Burp Suite Community | Pengujian web security         | AppSec, Pentest              |
| Docker               | Container dan aplikasi lab     | AppSec, DevSecOps            |
| Wazuh                | Security monitoring dan SIEM   | SOC, Blue Team               |
| Autopsy              | Digital forensics              | DFIR                         |

Tidak perlu menginstal semuanya pada hari pertama. Instal berdasarkan proyek yang akan dikerjakan.

## C. Resource khusus berdasarkan spesialisasi

| Bidang              | RAM laptop ideal | Storage bebas yang disarankan | Kebutuhan tambahan                          |
| ------------------- | ---------------- | ----------------------------- | ------------------------------------------- |
| SOC / Blue Team     | 16–32 GB         | 150–300 GB                    | Wazuh, Sysmon, beberapa VM                  |
| Red Team            | 16 GB            | 100–200 GB                    | Kali dan target VM                          |
| AppSec              | 8–16 GB          | 50–150 GB                     | Docker, Burp, aplikasi vulnerable           |
| Cloud Security      | 8 GB             | 30–50 GB                      | Akun cloud atau sandbox                     |
| Network Security    | 8–16 GB          | 50–100 GB                     | Wireshark, Packet Tracer                    |
| DFIR                | 16–32 GB         | 200–500 GB                    | Disk images, memory dumps                   |
| Malware Research    | 16–32 GB         | 200–500 GB                    | REMnux, isolated VM                         |
| GRC                 | 8 GB             | 20–50 GB                      | Spreadsheet, document editor                |
| IAM                 | 8–16 GB          | 50–100 GB                     | Linux, Entra atau Keycloak                  |
| DevSecOps           | 16 GB            | 100–200 GB                    | Docker, Git, CI/CD                          |
| Threat Intelligence | 8–16 GB          | 50–100 GB                     | Browser, data analysis tools                |
| OT / IoT            | 16 GB            | 100–200 GB                    | Simulator, jaringan lab, perangkat opsional |

Angka di atas adalah perkiraan ruang kerja untuk lab pribadi, bukan angka minimum dari produsen software.

Beberapa contoh kebutuhan resmi:

- Kali Linux dengan desktop standar direkomendasikan minimal 2 GB RAM dan 20 GB disk.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://www.kali.org\&sz=32)

  Kali Linux Documentation

- REMnux VM umumnya cukup dialokasikan 4 GB RAM dan 100 GB disk.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://github.com\&sz=32)

  GitHub

- Wazuh untuk instalasi server quickstart bagi 1–25 endpoint merekomendasikan 4 vCPU, 8 GiB RAM, dan 50 GB storage untuk retensi 90 hari.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://documentation.wazuh.com\&sz=32)

  Wazuh documentation

- Security Onion untuk instalasi standalone mencantumkan minimal 4 CPU core, 24 GB RAM, 200 GB storage, dan dua network interface. Ini sudah masuk lab yang lebih berat.&#x20;

  [image](https://www.google.com/s2/favicons?domain=https://docs.securityonion.net\&sz=32)

  Security Onion Documentation





Saran pembelian

&#x20;Mulai dengan laptop RAM 16 GB dan SSD 512 GB bila memang sedang memilih perangkat baru. Jika laptop saat ini hanya 8 GB, belum perlu upgrade sebelum mencoba browser-based labs.



# 5. Roadmap setiap spesialisasi dan proyek yang bisa dikerjakan

Bagian ini menjadi inti pembelajaran. Setiap jalur memiliki urutan keterampilan, platform gratis, alternatif berbayar, dan tiga tingkat proyek portfolio.

## 5.1 SOC Analyst / Blue Team

[The Wise Guy | Consulenza IT, Sviluppo Web & Integrazione AI](https://images.openai.com/static-rsc-4/Ov-sxlQJuhyYtEDSErvjmgYDUUJo7C0gUVEqpyjGkUWCmAR2UL9dx9OHaH_trXsKHxiJ4_P2tzm8qAchGqDdDwe2mGdu2JsdzvjsOZVJQeS7UZyhGMT3wyhgf-MZ2k4X6JOyfczI-4F6dqvbmz0M-FvpfP7oAdPBrHbCqpCZEWg?purpose=inline)

Cocok untuk pemula

Melindungi dan memonitor sistem

Pekerjaan: SOC Analyst, Security Analyst, Detection Engineer, Threat Hunter.

Apa yang dilakukan?

Menganalisis log dan alert keamanan untuk menemukan aktivitas mencurigakan, menyelidiki indikasi serangan, dan membantu menghentikan insiden.

Roadmap keterampilan:

1. Networking dan Linux/Windows fundamentals.
2. Memahami log Windows Event dan Linux Authentication.
3. Belajar SIEM (Security Information and Event Management).
4. Belajar memahami alert, false positive, dan incident triage.
5. Mengenal MITRE ATT&CK.
6. Detection engineering dan incident response.

Platform dan tools:

| Gratis               | Berbayar kemudian        |
| -------------------- | ------------------------ |
| CyberDefenders       | HTB Academy SOC Analyst  |
| TryHackMe free rooms | TryHackMe Premium        |
| Wazuh                | Kursus SOC profesional   |
| MITRE ATT&CK         | Sertifikasi spesialisasi |

Proyek portfolio:

| Tingkat   | Proyek                                                                                                                            | Hasil akhir                                  |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| Sederhana | Analisis file log login dan identifikasi login gagal                                                                              | Laporan aktivitas mencurigakan               |
| Menengah  | Membuat mini SIEM menggunakan Wazuh dan Sysmon                                                                                    | Dashboard dan aturan deteksi                 |
| Kompleks  | Membangun mini SOC dengan beberapa VM, membuat simulasi insiden aman, mendeteksi aktivitas dan membuat incident response playbook | Mini SOC environment dan laporan investigasi |

Resource: RAM 16 GB disarankan, 32 GB untuk mini SOC multi-VM.

Rekomendasi saya: ini salah satu bidang yang bagus untuk dicoba pertama karena memberikan pemahaman tentang bagaimana serangan terlihat dari sisi pertahanan.

## 5.2 Ethical Hacker / Penetration Tester / Red Team

[The Best Pen Testing Courses to Hack Your Way into a New Career - DSDT College](https://images.openai.com/static-rsc-4/HBfZk88rjqK50aqptRjKv1YAbeb33iUGWD8_SGpsA7AEeOkHbAs6IOP4l8WqiXEhQcMUVAcfcVHlRxBevGJxzPZZz2CSfk6cck_g_qP4Y5jQ-ErvyeuMD5DrEGtltItPHaeduPgKixjG57kjgTmKa4RXNQheCoNWBEHKHXcxp28?purpose=inline)

Banyak praktik teknis

Menguji kelemahan sistem secara legal

Pekerjaan: Penetration Tester, Red Team Operator, Vulnerability Analyst.

Roadmap keterampilan:

1. Networking, TCP/IP, DNS dan port.
2. Linux dan Windows administration.
3. Command line dan scripting Python.
4. Reconnaissance dan vulnerability scanning.
5. Web vulnerabilities dan OWASP Top 10.
6. Exploitation dalam lab yang diizinkan.
7. Privilege escalation dan post-exploitation.
8. Membuat penetration testing report.

Platform dan tools:

| Gratis                           | Berbayar kemudian                            |
| -------------------------------- | -------------------------------------------- |
| OverTheWire Bandit               | HTB Academy                                  |
| TryHackMe Free                   | TryHackMe Premium                            |
| HTB Academy Tier 0               | Modul HTB lanjutan                           |
| PortSwigger                      | Kursus penetration testing                   |
| Nmap, Kali Linux, Burp Community | Burp Suite Professional, sertifikasi terkait |

Proyek portfolio:

| Tingkat   | Proyek                                                                                                                                          | Hasil akhir                              |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| Sederhana | Memetakan port dan service pada mesin lab pribadi                                                                                               | Network scanning report                  |
| Menengah  | Menyelesaikan mesin vulnerable di HTB/THM dan mendokumentasikan penyebab kerentanannya                                                          | Pentest report dan rekomendasi perbaikan |
| Kompleks  | Melakukan penetration testing pada lingkungan virtual multi-mesin, dengan scope, rules of engagement, bukti, severity, dan rekomendasi mitigasi | Laporan penetration testing lengkap      |

Resource: RAM 8 GB untuk browser labs, 16 GB untuk Kali dan satu target VM, 32 GB untuk lingkungan Active Directory multi-VM.

Catatan: Red Team bukan sekadar mengetahui cara membobol sistem. Kemampuan membuat laporan yang dapat membantu perusahaan memperbaiki sistem sama pentingnya.

## 5.3 Application Security (AppSec)

[Shift Left in Practice: SAST, DAST, and SCA with GitHub Actions | by mjmarc.life | Medium](https://images.openai.com/static-rsc-4/bMua-ry6XHZqIKEsyIX-nb_e_Bm57tOle-pK82_VVpIbZPs88JAmduTV1iyENhb-WnuSyEJNADJuGXT8X6x-wD-gD0rtCjiLchmt9HipozrqzCB2STtRJefdcJo15HAo7PRAfxYlW5xVJRVtYr5pbvjVjlxKvve8q5EX9iJQT44?purpose=inline)

Membutuhkan programming

Mengamankan aplikasi dan website

Pekerjaan: Application Security Engineer, Product Security Engineer, Security Code Reviewer.

Roadmap keterampilan:

1. HTML, CSS, JavaScript.
2. HTTP request/response dan cookies.
3. Backend, database dan API.
4. Authentication, authorization dan session.
5. OWASP Top 10.
6. SQL Injection, XSS, SSRF, CSRF dan broken access control.
7. Secure coding dan threat modeling.
8. Security testing dengan SAST, DAST, dan SCA.
9. Secure software design menggunakan OWASP ASVS.

Platform dan tools:

| Gratis                    | Berbayar kemudian                  |
| ------------------------- | ---------------------------------- |
| PortSwigger Academy       | Burp Suite Professional            |
| OWASP Juice Shop          | Kursus AppSec lanjutan             |
| OWASP WebGoat             | HTB Academy                        |
| Semgrep Community Edition | Platform AppSec komersial          |
| GitHub                    | Fitur keamanan enterprise tertentu |

PortSwigger memberikan lab untuk banyak jenis kelemahan aplikasi web. OWASP Juice Shop merupakan aplikasi yang sengaja dibuat rentan sehingga cocok sebagai target latihan.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://portswigger.net\&sz=32)

PortSwigger+2



Proyek portfolio:

| Tingkat   | Proyek                                                                                                            | Hasil akhir                                          |
| --------- | ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Sederhana | Menganalisis tiga kerentanan dalam OWASP Juice Shop                                                               | Vulnerability report                                 |
| Menengah  | Membuat aplikasi login sederhana dan memperbaiki kelemahan autentikasi, session, dan SQL query                    | Aplikasi yang telah diperbaiki beserta security test |
| Kompleks  | Membuat aplikasi dengan CI/CD dan mengintegrasikan static scan, dependency scan, secret scan, serta pengujian web | Secure application pipeline dan security assessment  |

Resource: 8 GB cukup untuk lab online; 16 GB disarankan untuk Docker dan aplikasi lokal. Perlu kemampuan coding lebih baik daripada GRC atau Threat Intelligence.

## 5.4 Cloud Security

[Sophos Cloud Optix: Cloud Security Posture Management](https://images.openai.com/static-rsc-4/uoSM3CW9KE6bGpr1hEW-DxRDixivAwzglwPFHgdvz_W-vASFLEbCRNVQtaIGYX3MrDMaZYCZswpVyaG2HDwsOS7f8omX1818g9EwV-ybRW4vlaAg6hMpK_OeZKNqv353tvog6GscQnow8CdNiztbwJ6LGMgND42fjwAO-0x_cC0?purpose=inline)

Infrastruktur cloud

Melindungi sistem yang berjalan di cloud

Pekerjaan: Cloud Security Engineer, Cloud Security Architect, Cloud Security Analyst.

Roadmap keterampilan:

1. Networking dan Linux dasar.
2. Konsep cloud computing dan shared responsibility.
3. Belajar satu provider terlebih dahulu: AWS atau Azure.
4. Identity and Access Management (IAM).
5. Network security dan cloud firewall.
6. Storage security dan encryption.
7. Logging, monitoring dan cloud incident response.
8. Secure cloud architecture dan Infrastructure as Code.

Platform dan tools:

| Gratis             | Berbayar kemudian                 |
| ------------------ | --------------------------------- |
| AWS Skill Builder  | AWS Skill Builder subscription    |
| Microsoft Learn    | Azure lab berbayar                |
| Google Skills      | Cloud labs berbayar               |
| AWS Educate        | AWS certification exams           |
| Dokumentasi vendor | Kursus cloud security profesional |

AWS dan Microsoft menyediakan materi belajar mandiri, tetapi jangan samakan materi gratis dengan penggunaan semua resource cloud secara gratis.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://aws.amazon.com\&sz=32)

AWS+1



Proyek portfolio:

| Tingkat   | Proyek                                                                                                                                                | Hasil akhir                                |
| --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| Sederhana | Membuat diagram arsitektur cloud dan mengidentifikasi risiko storage yang terbuka                                                                     | Cloud threat model                         |
| Menengah  | Membuat lingkungan cloud dengan role-based access, private/public network, logging dan pembatasan akses                                               | Secure cloud lab                           |
| Kompleks  | Membangun secure cloud architecture dengan least privilege, centralized logging, network segmentation, backup, encryption dan infrastructure scanning | Cloud security architecture dan assessment |

Resource: RAM 8 GB cukup untuk materi dan browser lab. Tidak membutuhkan komputer kuat karena sebagian besar komputasi berada di cloud.



Perhatian biaya

&#x20;Pastikan menghapus resource cloud setelah eksperimen. VM, storage, IP publik, dan layanan lain dapat menimbulkan biaya meskipun kursus pembelajarannya gratis.



## 5.5 Network Security

[Network Security and Firewall Management: 10 Expert Tips](https://images.openai.com/static-rsc-4/nywKuJ3TYvFX-39fzZZGRiCvlfjl91zY_DjVtC6zem_I-7SsqP6cGdeHDQNakvR80R3qXtCbokZ5QEDT_1x5b7WWmn4k0g9--QnzQLaFwbcCg5484ShitZYRVzkpuV0msgs41COfD_JrocYlNOlDjNcUHFHqauKD_wjpyGgrraQ?purpose=inline)

Fondasi jaringan kuat

Melindungi komunikasi dan infrastruktur jaringan

Pekerjaan: Network Security Engineer, Firewall Engineer, Network Security Analyst.

Roadmap keterampilan:

1. Networking fundamentals.
2. IP addressing dan subnetting.
3. Routing dan switching.
4. VLAN dan network segmentation.
5. Firewall dan VPN.
6. IDS/IPS.
7. Packet capture menggunakan Wireshark.
8. Network monitoring dan troubleshooting.

Platform dan tools:

- Gratis: Cisco Networking Academy, Packet Tracer, Wireshark, Nmap.
- Berbayar kemudian: kursus CCNA, pelatihan firewall vendor, dan sertifikasi network/security.

Proyek portfolio:

| Tingkat   | Proyek                                                                                                         | Hasil akhir                      |
| --------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------- |
| Sederhana | Menganalisis file PCAP dengan Wireshark dan menemukan protokol yang digunakan                                  | Network traffic report           |
| Menengah  | Mendesain jaringan kantor virtual dengan VLAN, ACL dan firewall rules                                          | Network topology dan konfigurasi |
| Kompleks  | Membuat jaringan perusahaan virtual dengan segmentasi, IDS, monitoring, dan prosedur respons serangan jaringan | Enterprise network security lab  |

Resource: RAM 8 GB untuk Packet Tracer dan Wireshark; 16 GB jika ingin menjalankan banyak virtual machine.

## 5.6 Digital Forensics & Incident Response (DFIR)

[How to use FTK Imager and Autopsy for digital forensics | Kulbhashkar D. posted on the topic | LinkedIn](https://images.openai.com/static-rsc-4/owGoVKansQRnhngXKBBgG7jFk6Gp-Hami-vb7Qmdd44gltGx1BgQNNMjZrjCz964LpNeB3wQ0JiDiWpiFVSgZqqcBO12KPXpmjxUU2X6pdydZeNGcUKZhCpuPfkH6-o8EO92xEfrxpDvLMkqDkt9QP5CQA6FH22je63-lRSCmnI?purpose=inline)

Investigasi

Mencari bukti dan merekonstruksi insiden digital

Pekerjaan: Digital Forensic Analyst, DFIR Analyst, Incident Responder.

Roadmap keterampilan:

1. Memahami sistem operasi dan file system.
2. Memahami Windows Event Logs dan Linux logs.
3. Belajar file metadata, timestamps dan hashes.
4. Disk imaging dan evidence preservation.
5. Memory forensics.
6. Network forensics.
7. Timeline reconstruction.
8. Chain of custody dan incident reporting.

Platform dan tools:

- Gratis: CyberDefenders, Wireshark, Autopsy, Volatility.
- Berbayar kemudian: kursus DFIR, sertifikasi forensics dan platform investigasi profesional.

Autopsy dapat digunakan sebagai alat digital forensics dan menyediakan versi unduhan untuk Windows, Linux, dan macOS.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.autopsy.com\&sz=32)

Download



Proyek portfolio:

| Tingkat   | Proyek                                                                              | Hasil akhir                                             |
| --------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------- |
| Sederhana | Membuat timeline dari file log yang disediakan dalam lab                            | Timeline report                                         |
| Menengah  | Menganalisis disk image latihan menggunakan Autopsy                                 | Digital forensic investigation report                   |
| Kompleks  | Menggabungkan analisis disk, memory, dan network log dari kasus simulasi ransomware | Full incident reconstruction dan evidence documentation |

Resource: RAM 16 GB disarankan, 32 GB lebih nyaman. Storage besar penting karena disk image dan memory dump dapat memakan banyak ruang.

## 5.7 Malware Analysis & Reverse Engineering

[마이크로소프트, 최근 확산되는 러스트 악성코드 분석 도구 ‘RIFT’ 공개 - 데일리시큐](https://images.openai.com/static-rsc-4/OIxXxOvP2e6GUxdSmQOUiinz12SJ-MPe2N8ng-ZX2galhnBEtOvfwbQGOPp1H9wdELE779lHNVBPQbEOJ8tkWTKs4ch_hmwBdsNUmSD77wkzj_eTt-YGmlGmv2-mgs_Ei0M9NKrcw1VTQzxvwKqUmANzoAwh5Akq4YX3WTWq-lM?purpose=inline)

Teknis dan kompleks

Menganalisis bagaimana malware bekerja

Pekerjaan: Malware Analyst, Reverse Engineer, Threat Researcher.

Roadmap keterampilan:

1. Computer architecture dasar.
2. Linux dan Windows internals.
3. Python dan C dasar.
4. Process, memory, executable files.
5. Static analysis.
6. Dynamic analysis.
7. Assembly dan reverse engineering.
8. YARA rules dan behavior analysis.

Platform dan tools:

- Gratis: REMnux, CyberDefenders, TryHackMe malware analysis labs.
- Lanjutan: FLARE-VM, Ghidra, YARA.
- Berbayar kemudian: kursus reverse engineering dan malware analysis profesional.

REMnux menyediakan toolkit open source untuk static analysis, dynamic analysis, memory forensics, dan investigasi malware.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://docs.remnux.org\&sz=32)

REMnux Documentation+1



Proyek portfolio:

| Tingkat   | Proyek                                                                                                                    | Hasil akhir                                |
| --------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| Sederhana | Mengambil hash, metadata, dan strings dari file sampel yang aman                                                          | File analysis report                       |
| Menengah  | Menganalisis sampel edukasi yang telah disediakan oleh lab dan membuat aturan deteksi YARA                                | Static analysis report dan YARA rule       |
| Kompleks  | Membangun lab isolasi REMnux, menganalisis sampel khusus pelatihan, dan menggabungkan hasil static serta dynamic analysis | Malware behavior report dan detection rule |

Resource: 16 GB minimum yang disarankan untuk mulai menggunakan beberapa alat, 32 GB ideal untuk dua atau lebih VM. Storage 500 GB atau lebih akan membantu.



Keamanan wajib

&#x20;Jangan pernah menjalankan sampel malware di laptop pribadi atau perangkat utama. Gunakan VM terisolasi, snapshot, tanpa shared folder, dan jaringan simulasi yang sesuai. Mulailah dengan sampel edukasi yang dikurasi oleh lab.



## 5.8 Governance, Risk & Compliance (GRC)

[How to Organize Your Compliance Program When the Structure Is Not There](https://images.openai.com/static-rsc-4/xBYp0VQvoGaNgp-qI_3lB2y85yS4Nko-pu5VRaAmJqFMyi12pPfhoYgdVxyzc3vnn2i3iJFdrduyy-iIOAcW42i9YwR_zR3HQpaQzHRBIj2cDquZWU4doVcqlcFYPZBIatiyuFf3VpM07qMCaZkck161a6YadwlmWzB6bu3Mn5Y?purpose=inline)

Tidak harus jago coding

Memastikan keamanan dikelola sebagai risiko organisasi

Pekerjaan: GRC Analyst, IT Auditor, Risk Analyst, ISO 27001 Consultant.

Roadmap keterampilan:

1. Memahami cybersecurity dan risiko perusahaan.
2. Asset inventory dan data classification.
3. Risk assessment dan risk treatment.
4. Security policies dan procedures.
5. Control assessment.
6. NIST Cybersecurity Framework.
7. ISO 27001 dan ISMS.
8. Internal audit dan compliance reporting.
9. Business continuity dan disaster recovery.

Platform dan tools:

- Gratis: NIST CSF 2.0, NIST NICE, dokumentasi ISO terkait yang tersedia secara publik, spreadsheet.
- Berbayar kemudian: kursus ISO 27001 Foundation, Internal Auditor, Lead Implementer, atau sertifikasi profesional GRC.

NIST CSF 2.0 menggunakan enam fungsi utama: Govern, Identify, Protect, Detect, Respond, dan Recover. Framework ini cocok digunakan sebagai landasan proyek GRC pertama.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.nist.gov\&sz=32)

NIST+1



Proyek portfolio:

| Tingkat   | Proyek                                                                                                                | Hasil akhir                            |
| --------- | --------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| Sederhana | Membuat daftar aset perusahaan fiktif dan mengidentifikasi risiko                                                     | Asset register dan risk register       |
| Menengah  | Membuat cybersecurity policy dan melakukan gap assessment terhadap NIST CSF 2.0                                       | Policy document dan control assessment |
| Kompleks  | Mendesain ISMS perusahaan fiktif, menentukan scope, risk treatment, kontrol, audit plan, dan incident response policy | Simulasi dokumentasi implementasi ISMS |

Resource: RAM 8 GB, laptop standar, spreadsheet, dokumen dan akses internet sudah cukup. Tidak membutuhkan VM atau komputer khusus.

## 5.9 Identity & Access Management (IAM)

Administrasi dan kontrol akses

Mengelola siapa yang boleh masuk dan mengakses apa

Pekerjaan: IAM Analyst, Identity Administrator, Privileged Access Management Specialist.

Roadmap keterampilan:

1. User, group, dan permission.
2. Authentication dan authorization.
3. Password policy dan MFA.
4. RBAC dan least privilege.
5. SSO dan federation.
6. Active Directory dan Microsoft Entra.
7. Privileged Access Management (PAM).
8. Identity lifecycle dan access review.

Platform dan tools:

- Gratis: Microsoft Learn, Linux user/group management, Keycloak.
- Berbayar kemudian: vendor identity training dan sertifikasi cloud/identity.

Microsoft Learn menyediakan jalur pengenalan Microsoft Entra dan identitas, termasuk authentication, access management dan identity governance.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://learn.microsoft.com\&sz=32)

Microsoft Learn+1



Proyek portfolio:

| Tingkat   | Proyek                                                                               | Hasil akhir                                          |
| --------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------- |
| Sederhana | Membuat akun Linux dengan perbedaan hak akses                                        | User dan permission documentation                    |
| Menengah  | Mendesain sistem user dan role untuk perusahaan fiktif, dengan MFA dan access review | IAM role matrix                                      |
| Kompleks  | Membangun sistem IAM dengan SSO, MFA, RBAC, lifecycle provisioning dan audit access  | Identity management architecture dan konfigurasi lab |

Resource: RAM 8–16 GB. Dapat menggunakan mesin virtual atau layanan identity cloud. Untuk pemula tidak diperlukan hardware khusus.

## 5.10 DevSecOps / Security Engineering

[Building an End-to-End DevSecOps CI/CD Pipeline with Azure DevOps - 0x70ssAM](https://images.openai.com/static-rsc-4/NqmQkB_vazX6I04JpgtRHv3hP0MgRjMt9bx16D_GguTd7ZKPm9OHT0H2l3_hqddyUZNETDSnWnB36we-x_XYnWwbjOvaL422EzhEbyv_XZ-EXQGFODqjs9uIEsV0hMvCq9ExNvP8j58PIQC_0pBnGTMgLf8FlSYS1I7SQGt0rRQ?purpose=inline)

Programming dan automation

Mengintegrasikan keamanan dalam proses pengembangan software

Pekerjaan: DevSecOps Engineer, Security Automation Engineer, Product Security Engineer.

Roadmap keterampilan:

1. Python dan programming.
2. Git dan GitHub.
3. Linux dan command line.
4. Docker dan container.
5. CI/CD pipeline.
6. SAST, DAST dan SCA.
7. Secrets management.
8. Container security dan IaC scanning.
9. Pipeline security dan automation.

Platform dan tools:

- Gratis: GitHub, GitHub Actions, Semgrep Community Edition, Trivy.
- Berbayar kemudian: GitHub Code Security untuk fitur enterprise pada repository privat, platform CI/CD dan security scanning komersial.

Semgrep Community Edition menyediakan scanning source code gratis. GitHub juga menyediakan sejumlah fitur keamanan gratis untuk repository publik, sedangkan fitur tertentu pada repository privat membutuhkan paket tambahan.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://semgrep.dev\&sz=32)

Semgrep+2



Proyek portfolio:

| Tingkat   | Proyek                                                                                                                            | Hasil akhir                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| Sederhana | Memindai source code untuk menemukan pola kode berisiko                                                                           | Code scanning report                          |
| Menengah  | Menambahkan security scan otomatis ketika programmer melakukan push ke GitHub                                                     | CI security pipeline                          |
| Kompleks  | Membuat pipeline lengkap dengan SAST, dependency scanning, secret detection, image scanning, IaC checks, dan kebijakan deployment | Secure CI/CD project dan dokumentasi mitigasi |

Resource: RAM 16 GB disarankan; Docker dan beberapa container akan menggunakan resource cukup besar. Storage 512 GB lebih nyaman.

## 5.11 Cyber Threat Intelligence

[Aayush Raj | Cybersecurity Analyst](https://images.openai.com/static-rsc-4/nv_Df0FSZRCrcy2VaL_NSIuZ8EsFEuJYVH_vtLjaX_CM-YP7XMo-nScU0wZp2kx1hNn5pfctPIGoynn1DQAoP5Ek7yZj7l12UXf5mCyZAjEf84TCESFjaHKrW-j_kGiWgT0jsFuvpVS18-uHfIhpb29-EGgZe-fQbg7efOQD5mY?purpose=inline)

Riset dan analisis

Memahami ancaman dan perilaku penyerang

Pekerjaan: Threat Intelligence Analyst, CTI Analyst, Threat Researcher.

Roadmap keterampilan:

1. Cybersecurity fundamentals.
2. OSINT (Open Source Intelligence).
3. Indikator kompromi: IOC.
4. Threat actor dan attack patterns.
5. MITRE ATT&CK.
6. Threat hunting dan intelligence lifecycle.
7. Analisis laporan ancaman.
8. Membuat threat intelligence brief.

Platform dan tools:

- Gratis: MITRE ATT&CK, CISA advisories, CyberDefenders, browser research tools.
- Lanjutan: MISP, OpenCTI.
- Berbayar kemudian: platform threat intelligence komersial dan kursus khusus.

MITRE ATT&CK dapat digunakan untuk memahami taktik, teknik, dan prosedur yang digunakan penyerang berdasarkan observasi nyata.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.mitre.org\&sz=32)

MITRE+1



Proyek portfolio:

| Tingkat   | Proyek                                                                                                                                        | Hasil akhir                          |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| Sederhana | Mengidentifikasi IOC dalam laporan ancaman publik                                                                                             | IOC list                             |
| Menengah  | Memetakan sebuah laporan serangan ke MITRE ATT&CK                                                                                             | ATT&CK mapping dan threat brief      |
| Kompleks  | Menganalisis beberapa laporan publik tentang satu kampanye serangan dan menggabungkan IOC, TTP, tingkat keyakinan, serta rekomendasi mitigasi | Cyber threat intelligence assessment |

Resource: RAM 8 GB cukup, 16 GB jika menggunakan platform analisis data lokal. Fokus utama lebih pada kemampuan riset, validasi sumber, dan penulisan.

## 5.12 OT / IoT Security

[OT Network Segmentation: A Guide for Beginners l Dragos](https://images.openai.com/static-rsc-4/dec1HVNEGQ367I2qTDHoD1nEEx67Qc9N_jji6U07ZNCwLBJzXbeDp8dIDu7ZCnDejHz2mHZ4N3HFzZ6bb6h90nsB23BDHjazbfqZdCUDWgOGn7C-0l7kPn_K6Rdqp_nvdWYwKvKgAoPEvImFC2Izs1y4Z2w00YNaNB8TAGT0qWc?purpose=inline)

Spesialisasi khusus

Mengamankan sistem industri dan perangkat terkoneksi

Pekerjaan: OT Security Engineer, ICS Security Analyst, IoT Security Researcher.

Roadmap keterampilan:

1. Networking fundamentals.
2. Basic electronics dan embedded systems.
3. IoT architecture.
4. Industrial control system dan SCADA.
5. Protokol seperti Modbus dan MQTT.
6. Network segmentation.
7. Asset discovery dan vulnerability management.
8. Monitoring dan incident response untuk lingkungan industri.

Platform dan tools:

- Gratis: Wireshark, simulator, dokumentasi NIST dan CISA, perangkat lunak lab seperti OpenPLC.
- Berbayar kemudian: pelatihan ICS/SCADA security serta perangkat simulasi industri.

Proyek portfolio:

| Tingkat   | Proyek                                                                                                          | Hasil akhir                                         |
| --------- | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| Sederhana | Membuat threat model perangkat smart home                                                                       | IoT security diagram                                |
| Menengah  | Menganalisis komunikasi perangkat milik sendiri di jaringan terisolasi dengan Wireshark                         | IoT network analysis                                |
| Kompleks  | Membangun simulasi jaringan industri dengan pembagian zona, pemantauan komunikasi, dan skenario deteksi insiden | OT security architecture dan incident response plan |

Resource: RAM 16 GB ideal. Perangkat IoT, Raspberry Pi, atau hardware industri adalah tambahan opsional, bukan syarat untuk memulai.

Penting: jangan melakukan pengujian terhadap perangkat industri atau sistem kontrol yang benar-benar beroperasi tanpa otorisasi dan pengawasan yang tepat.

# 6. Perbandingan akhir: jalur mana yang cocok berdasarkan minat?

Karena teman Anda belum mempunyai pengalaman, saya tidak menyarankan memilih bidang berdasarkan gaji atau popularitas saja. Lebih baik berdasarkan jenis pekerjaan yang disukai.

| Jika teman Anda suka...                                 | Coba bidang ini          | Coding        |
| ------------------------------------------------------- | ------------------------ | ------------- |
| Memecahkan teka-teki dan mencari aktivitas mencurigakan | SOC Analyst              | Sedang        |
| Mencari kelemahan sistem                                | Penetration Testing      | Sedang–tinggi |
| Membuat aplikasi dan memperbaiki kode                   | AppSec                   | Tinggi        |
| Mengelola server dan infrastruktur                      | Network / Cloud Security | Sedang        |
| Menginvestigasi kejadian                                | DFIR                     | Sedang        |
| Membedah program dan file                               | Malware Analysis         | Tinggi        |
| Mengelola kebijakan dan risiko                          | GRC                      | Rendah        |
| Mengatur akun dan hak akses                             | IAM                      | Rendah–sedang |
| Membuat automation dan pipeline                         | DevSecOps                | Tinggi        |
| Membaca laporan, pola serangan, dan OSINT               | Threat Intelligence      | Rendah–sedang |
| Mengamankan mesin dan perangkat industri                | OT / IoT Security        | Sedang–tinggi |

## 7. Platform berbayar: kapan dan ke mana?

Saya menyarankan pola pembayaran berikut.

| Kebutuhan               | Pilihan                                          | Kapan layak dibayar?                                                         |
| ----------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------- |
| Belajar praktik terarah | TryHackMe Premium                                | Ketika materi gratis sudah cukup dan ingin learning path lengkap             |
| Lab penetration testing | HTB Academy                                      | Ketika ingin mempelajari modul lanjutan                                      |
| Web security            | Burp Suite Professional                          | Ketika sudah serius melakukan pengujian web                                  |
| SOC dan Blue Team       | HTB Academy, kursus SOC profesional              | Ketika sudah menguasai log, jaringan, dan dasar SIEM                         |
| Cloud Security          | AWS/Azure training dan sertifikasi               | Ketika sudah memilih ekosistem cloud                                         |
| GRC                     | ISO 27001 Foundation / Internal Auditor training | Ketika sudah memahami risk management dan ingin belajar implementasi standar |
| AppSec dan DevSecOps    | Kursus secure development dan platform security  | Ketika butuh pembelajaran spesialisasi dan praktik tambahan                  |
| DFIR / Malware          | Kursus forensics dan reverse engineering         | Ketika sudah memiliki fondasi OS dan investigasi                             |

Urutan pengeluaran yang saya sarankan:

1. Rp0: gunakan semua platform gratis.
2. Pengeluaran pertama: berlangganan satu platform sesuai spesialisasi.
3. Pengeluaran kedua: sertifikasi yang relevan dengan pekerjaan tujuan.
4. Pengeluaran ketiga: perangkat atau cloud lab tambahan apabila benar-benar diperlukan.

Tidak perlu membeli sertifikat untuk setiap platform. Sertifikat penyelesaian kursus tidak sama dengan sertifikasi kompetensi profesional.

# 8. Cara membuat portfolio yang benar

Satu proyek sebaiknya menghasilkan bukti keterampilan, bukan sekadar screenshot bahwa sebuah room berhasil diselesaikan.

Untuk setiap proyek, gunakan format berikut:

## Template portfolio cybersecurity

1\. Project Overview

Apa masalah keamanan yang ingin diselesaikan?

2\. Objective

Apa tujuan proyek?

3\. Tools & Environment

Tools, OS, VM, dan versi software yang dipakai.

4\. Architecture

Diagram jaringan, aplikasi, atau sistem.

5\. Implementation

Langkah pengerjaan, konfigurasi dan metode pengujian.

6\. Findings

Masalah yang ditemukan, bukti, dan tingkat risikonya.

7\. Remediation

Bagaimana cara memperbaiki masalah?

8\. Final Result

Bukti sebelum dan sesudah serta kesimpulan.

Simpan di GitHub atau portfolio pribadi. Jangan mengunggah password, API key, data sensitif, atau informasi sistem yang tidak diizinkan untuk dipublikasikan.

# 9. Rekomendasi rute paling efektif untuk teman Anda

Saya merekomendasikan tiga kelompok eksplorasi sebelum memilih spesialisasi.

Kelompok 1 — Defensive Security

Mulai di sini

Kenali bagaimana perusahaan mendeteksi dan menangani serangan.

- Cisco Networking Academy
- TryHackMe
- CyberDefenders
- Wazuh

Target proyek: membuat mini security monitoring dan menganalisis log.

Kelompok 2 — Offensive & Application Security

Kenali cara menemukan kelemahan sistem dan aplikasi.

- OverTheWire
- HTB Academy Tier 0
- TryHackMe
- PortSwigger
- OWASP Juice Shop

Target proyek: vulnerability assessment dan security testing report.

Kelompok 3 — Governance & Infrastructure

Kenali bagaimana perusahaan membangun dan mengelola keamanan.

- NIST Cybersecurity Framework
- Microsoft Learn
- AWS Skill Builder
- Cisco Networking Academy

Target proyek: security risk assessment dan secure infrastructure design.

Setelah ketiga kelompok dicoba, teman Anda dapat menentukan bidang yang paling menarik dan melanjutkan proyek tingkat menengah dan kompleks pada bidang tersebut.

## 10. Kesimpulan investasi dan prioritas

| Prioritas    | Keputusan                                       |
| ------------ | ----------------------------------------------- |
| Laptop       | Gunakan perangkat saat ini jika masih memadai   |
| RAM          | 8 GB cukup memulai, 16 GB target ideal          |
| Software     | Mulai dari aplikasi gratis dan open source      |
| Kursus       | Cisco, Microsoft Learn, TryHackMe Free          |
| Praktik      | CyberDefenders, PortSwigger, HTB Tier 0         |
| Sertifikasi  | Ditunda sampai memiliki kemampuan dan portfolio |
| Spesialisasi | Dicoba dulu sebelum menentukan pilihan          |
| Portfolio    | Wajib mendokumentasikan proyek                  |

Kesimpulan saya: teman Anda tidak perlu mengeluarkan uang untuk mulai belajar cybersecurity. Bahkan dengan laptop RAM 8 GB, ia sudah dapat mempelajari fondasi, mencoba banyak bidang, dan membuat proyek sederhana.

Investasi pertama seharusnya bukan sertifikat atau laptop baru, melainkan waktu untuk membangun kemampuan dan proyek nyata.

Untuk tahap berikutnya, pendekatan yang paling bermanfaat adalah membuat starter project pack berisi satu proyek pemula untuk masing-masing dari 12 spesialisasi tersebut, lengkap dengan tujuan, tools, dataset/lab, langkah pengerjaan, dan kriteria keberhasilannya.
