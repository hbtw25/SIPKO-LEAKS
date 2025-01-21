  
███████╗██╗██████╗ ██╗  ██╗ ██████╗     ██╗     ███████╗ █████╗ ██╗  ██╗███████╗    ██████╗ ██╗   ██╗    ████████╗██╗   ██╗███████╗ █████╗ ██╗     ███████╗
██╔════╝██║██╔══██╗██║ ██╔╝██╔═══██╗    ██║     ██╔════╝██╔══██╗██║ ██╔╝██╔════╝    ██╔══██╗╚██╗ ██╔╝    ╚══██╔══╝╚██╗ ██╔╝╚══███╔╝██╔══██╗██║     ██╔════╝
███████╗██║██████╔╝█████╔╝ ██║   ██║    ██║     █████╗  ███████║█████╔╝ ███████╗    ██████╔╝ ╚████╔╝        ██║    ╚████╔╝   ███╔╝ ███████║██║     ███████╗
╚════██║██║██╔═══╝ ██╔═██╗ ██║   ██║    ██║     ██╔══╝  ██╔══██║██╔═██╗ ╚════██║    ██╔══██╗  ╚██╔╝         ██║     ╚██╔╝   ███╔╝  ██╔══██║██║     ╚════██║
███████║██║██║     ██║  ██╗╚██████╔╝    ███████╗███████╗██║  ██║██║  ██╗███████║    ██████╔╝   ██║          ██║      ██║   ███████╗██║  ██║███████╗███████║
╚══════╝╚═╝╚═╝     ╚═╝  ╚═╝ ╚═════╝     ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝    ╚═════╝    ╚═╝          ╚═╝      ╚═╝   ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝
                                                                                                                                                           

# Riset Kerentanan Sistem Informasi Pengumuman Kelulusan Online 1.0

Repositori ini berisi informasi mengenai kerentanan CSRF (Cross-Site Request Forgery) dan Blind XSS (Cross-Site Scripting) yang ditemukan pada Sistem Informasi Pengumuman Kelulusan Online 1.0. Informasi ini dibagikan untuk tujuan riset keamanan dan pertahanan, guna membantu organisasi memahami kerentanan ini dan mengambil langkah-langkah yang diperlukan untuk mengamankan aplikasi mereka.

## Latar Belakang

Sistem Informasi Pengumuman Kelulusan Online 1.0 adalah aplikasi web _open-source_ yang rentan terhadap CSRF dan Blind XSS. Kerentanan ini dapat dieksploitasi untuk melakukan tindakan yang tidak sah dan menyuntikkan skrip berbahaya yang dapat menyebabkan pelanggaran data atau kompromi akun pengguna.

## Tujuan

Repositori ini berfungsi sebagai sumber daya untuk:

*   Peneliti keamanan yang mempelajari kerentanan CSRF dan Blind XSS.
*   Pengembang yang ingin lebih memahami cara mengamankan aplikasi web mereka.
*   Meningkatkan kesadaran tentang kerentanan aplikasi web umum dalam sistem _open-source_.

## Isi

*   `affected_ips_domains.txt`: Daftar alamat IP dan/atau domain yang ditemukan menggunakan aplikasi yang rentan.
*   `vulnerability_details.md`: Detail teknis kerentanan, termasuk vektor serangan, dampak, dan potensi mitigasi.
*   `REFERENCES.md`: Sumber daya tambahan dan referensi mengenai kerentanan CSRF dan Blind XSS.

## Disclaimer

Informasi ini disediakan hanya untuk tujuan pendidikan dan riset keamanan pertahanan. Informasi yang dibagikan di sini hanya boleh digunakan untuk _ethical hacking_ dan analisis, bukan untuk aktivitas jahat.

## Referensi

*   [OWASP CSRF](https://owasp.org/www-community/attacks/csrf)
*   [OWASP XSS](https://owasp.org/www-community/attacks/xss/)
*   CVE terkait (jika ada)

## Kontak & Dukungan

Jika Anda memiliki pertanyaan, wawasan, atau umpan balik mengenai riset ini atau kerentanannya:

*   🧑‍💻 Github: [Tyzals](https://github.com/yourgithubusername)
*   📧 Email: tyzals@mail.com

Saya tersedia untuk membantu peneliti keamanan:

*   Mendiskusikan detail teknis kerentanan
*   Berbagi strategi mitigasi
*   Berkolaborasi dalam riset dan analisis lebih lanjut.
