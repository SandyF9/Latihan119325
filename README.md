# Latihan119325

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>latihan 1 - HTML5</title>
</head>
<body>
    <header>
        <h1>Selamat Datang</h1>
        <p>Belajar element semantik HTML5</p>
    </header>
    <!-- bagian untuk latihan berikutnya -->
    <nav>
        <a href="#tentang">Tentang</a> |
        <a href="#kursus">Kursus</a> |
        <a href="#kontak">Kontak</a>
    </nav>
    <Section id="tentang">
        <h2>Tentang Halaman Ini</h2>
        <p>Ini merupakan section untuk menu Tentang</p>
    </Section>
    <section id="kursus">
        <h2>Daftar Kursus</h2>
        <table border="1">
        <tr>
            <th>No</th>
            <th>Nama Kursus :</th>
            <th>Durasi</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Dasar HTML & CSS</td>
            <td>4 minggu</td>
            </tr>
            <tr>
            <td>2</td>
            <td>JavaScript Fundamental</td>
            <td>6 Minggu</td>
            </tr>
        </table>  
    </section>
    <h2>html Forms </h2>
        <form action="/action_page.php">
            <label for="fname">First name:</label>
        <br>
            <input type="text" id="fname"
            name="fname" value="Sandy"> <br>
            <label type="iname">Last name:</label>
            <br>
                <input type="text" id="iname"
            name="iname" value="Febrianto"><br><br>
            <input type="submit" value="Submit">
            </form>
        <p>Jika anda mengeklik tombol "Submit", maka akan selesai </p>
     <footer>
        <p>&copy; 2025 oleh Sandy Febrianto </p>
     </footer>
</body>
</html>

