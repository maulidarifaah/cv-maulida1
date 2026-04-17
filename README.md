<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Maulida</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background: #e9ecef; padding: 30px; }
        .cv { max-width: 900px; margin: auto; background: white; display: flex; box-shadow: 0 0 15px rgba(0,0,0,0.1); }
        
        /* Sidebar Kiri */
        .sidebar { width: 35%; background: #2c3e50; color: white; padding: 30px 20px; text-align: center; }
        .sidebar img { width: 150px; height: 150px; border-radius: 50%; border: 4px solid white; object-fit: cover; margin-bottom: 15px; }
        .sidebar h1 { font-size: 22px; margin-bottom: 5px; }
        .sidebar .job { font-size: 14px; color: #bdc3c7; margin-bottom: 25px; }
        .sidebar h3 { font-size: 16px; text-align: left; border-bottom: 1px solid #bdc3c7; padding-bottom: 5px; margin: 20px 0 10px; }
        .sidebar p, .sidebar li { font-size: 13px; text-align: left; margin-bottom: 8px; line-height: 1.5; }
        .sidebar ul { list-style: none; padding: 0; }
        .contact strong { display: inline-block; width: 60px; }

        /* Konten Kanan */
        .main { width: 65%; padding: 30px; }
        .main h2 { font-size: 18px; color: #2c3e50; border-bottom: 2px solid #2c3e50; padding-bottom: 5px; margin-bottom: 15px; }
        .main .section { margin-bottom: 25px; }
        .item { margin-bottom: 15px; }
        .item .judul { font-weight: bold; color: #34495e; }
        .item .waktu { font-size: 13px; color: #7f8c8d; float: right; }
        .item .desc { font-size: 14px; color: #555; margin-top: 5px; line-height: 1.6; }
    </style>
</head>
<body>
    <div class="cv">
        <!-- SIDEBAR KIRI -->
        <div class="sidebar">
            <!-- Ganti src dengan link foto kamu -->
            <img src="ftku.jpeg" alt="Foto Profil">
            <h1>Maulida Rifa'ah</h1>
            <div class="job">PELAJAR</div>

            <h3>KONTAK</h3>
            <div class="contact">
                <p><strong>HP</strong>: 085840310722</p>
                <p><strong>Email</strong>: milolovers123457@gmail.com</p>
                <p><strong>Alamat</strong>: Kurahan 2 Murtigading Sanden Bantul Yogyakarta</p>
            </div>

            <h3>KEAHLIAN</h3>
            <ul>
                <li>Microsoft Office</li>
                <li>HTML, CSS, PHP</li>
                <li>Database MySQL</li>
                <li>Desain Canva</li>
            </ul>

            <h3>DATA PRIBADI</h3>
            <p>Lahir: Bantul, 08 Maret 2009</p>
            <p>Agama: Islam</p>
            <p>Status: pelajar</p>
        </div>

        <!-- KONTEN KANAN -->
        <div class="main">
            <div class="section">
                <h2>PROFIL SINGKAT</h2>
                <p class="desc">masih pelajar</p>
            </div>

            <div class="section">
                <h2>PENDIDIKAN</h2>
                <div class="item">
                    <div class="judul">SD N PIRING <span class="waktu">2015-2021</span></div>
                    <div class="judul">SMP N 1 SANDEN <span class="waktu">2021-2024</span></div>
                    <div class="judul">SMK N 1 SANDEN <span class="waktu">2024-2027</span></div>
                </div>
                
            </div>
        </div>
    </div>
</body>
</html>
