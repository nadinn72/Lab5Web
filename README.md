# Praktikum 5

**Pengenalan javascript**

**CODE**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```

**HASIL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/497ca9d5-05be-4738-a820-88d81da4cdbd" />

# Javascript Dasar
## a. Pemakaian Alert Sebagai Properti Window

**CODE**

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Alert Box</title>
</head>
<body>
<script>
window.alert("Ini merupakan pesan untuk Anda");
</script>
</body>
</html>
```

**HASIL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/5891bd7b-9ce7-4435-9e11-56b533bf98ba" />

## b. Pemakaian Method Dalam Objek

**CODE**

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Script JavaScript</title>
</head>
<body>
Percobaan memakai JavaScript:<br>
<script language = "javascript">
<!--
    document.write("Selamat mencoba JavaScript<br>");
    document.write("Semoga sukses!");
-->
</script>
</body>
</html>
```

**Hasil =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/ff9f08ce-6607-4c08-a445-8f930960cf43" />

## c. Pemakaian Prompt

**CODE**

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Pemasukan Data</title>
</head>
<body>
<script>
var nama = prompt("Siapa nama Anda?", "Masukkan nama Anda");
document.write("Hai, " + nama);
</script>
</body>
</html>
```

**HASIL 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/9d8271dc-ccf8-40bc-813d-4432df7f6d22" />

**HASIL 2 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/45cba673-3bfd-427c-a694-464d9cdfd6d1" />

**Hasil 3 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/cb8c7513-751b-4d18-ae68-4d4b7f762200" />


## d. Pembutan Fungsi dan Cara Pemanggilannya
**CODE**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contoh Program JavaScript</title>
    <script>
    function pesan(){
        alert("Memanggil JavaScript lewat body onload");
    }
    </script>
</head>
<body onload="pesan()"> 
</body>
</html>  
```

**HASIL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/1a87567d-9406-43bf-9887-c60cbcededcf" />

# Dasar Pemrograman Di Javascript
## a. Operasi Dasar Aritmatika

**CODE**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contoh Program JavaScript</title>
    <script>
    function test(val1, val2) {
        document.write("<br>Perkalian : " + (val1 * val2) + "<br>");
        document.write("Pembagian : " + (val1 / val2) + "<br>");
        document.write("Penjumlahan : " + (val1 + val2) + "<br>");
        document.write("Pengurangan : " + (val1 - val2) + "<br>");
        document.write("Modulus : " + (val1 % val2) + "<br>");
    }
    </script>
</head>
<body>
    <input type="button" value="Arithmetic" onclick="test(9,4)">
</body>
</html>
```

**HASIL 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/d1f5e1d8-a1c3-4190-a631-0f6ff840e1b5" />

**HASIL 2 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/5128918d-c441-46b1-a085-a5bdff2f5c6d" />


## b. Seleksi Kondisi (IF.ELSE)

**CODE**

```
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil: " + hasil);
    //-->
    </script>
</body>
</html>
```

**HASIL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/6b8ea16f-a617-4801-81de-5f2c3adb232d" />

**HASIL LULUS 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/bee8d78a-3313-4081-9d6a-4f474865ed1f" />

**HASIL LULUS 2 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/ad8f640b-7e14-4723-9dae-89775257ae2a" />

**HASIL TIDAK LULUS 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/7f9afe61-744e-41cf-ae4a-5a96ba9a770d" />


**HASIL TIDAK LULUS 2 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/bedfad7f-28b8-49ad-9c26-fdbda1383efb" />

## c. Penggunaaan Operator Switch Untuk Seleksi Kondisi

**CODE**

```
<html>
<head>
<title>contoh program javascript</title>

<script language="javascript">
function test()
{
    val1 = window.prompt("input nilai (1-5):")
    switch (val1)
    {
        case "1" :
            document.write("bilangan satu")
            break
        case "2" :
            document.write("bilangan dua")
            break
        case "3" :
            document.write("bilangan tiga")
            break
        case "4" :
            document.write("bilangan empat")
            break
        case "5" :
            document.write("bilangan lima")
            break
        default :
            document.write("bilangan lainnya")
    }
}
</script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
```
**HASIL 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/ea07c232-0c2d-477c-b215-0bd7abaa4399" />

**HASIL 2 =**

<img width="177" height="111" alt="image" src="https://github.com/user-attachments/assets/8e61f3cb-471c-4a4c-8926-905266f0872d" />

# Pembuatan Form
## a. Form Input

**CODE**
```
<html>
<head>
    <script language="javascript">
    function test() {
        var val1 = document.kirim.T1.value
        if (val1 % 2 == 0)
            document.kirim.T2.value = "bilangan genap"
        else
            document.kirim.T2.value = "bilangan ganjil"
}
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
```

**HASIL 1 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/129300eb-1933-4de2-8fcb-8df9fe225859" />

**HASIL 2 =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/b6dc4d61-9cc5-42f0-a4ef-ef6524cb319c" />


## b. Form Button

**CODE**

```
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language="javascript">
    <!--
    function ubahWarnaLB(warna) {
        document.bgColor = warna;
    }
    function ubahWarnaLD(warna) {
        document.fgColor = warna;
    }
    //-->
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
    </form>

    <script language="javascript">
    <!--
    document.write("Dimodifikasi terakhir pada " + 
    document.lastModified);
    //-->
</script>
</body>
</html>
```

**HASIL AWAL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/e50274ca-9e0a-43c1-bd90-cd1d91c87b0f" />


**HASIL AKHIR =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/e02d657d-c2ce-4aa8-98ef-fe9e4e89186b" />


# HTML DOM

## Pilihan menggunakan checkBox dengan perhitungan otomatis

**CODE**

```
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
        var total = document.getElementById('total').value;
        total = (total ? parseInt(total) : 0);
        var harga = 0;

        if (ele.checked) {
            harga = ele.value;
            total += parseInt(harga);
        } else {
            harga = ele.value;
            if (total > 0)
                total -= parseInt(harga);
        }

            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onClick="hitung(this);"/> Ayam Goreng Rp. 5.000</label><br/>
    <label><input type="checkbox" value="500" id="menu2" onClick="hitung(this);"/> Tempe Goreng Rp. 500</label><br/>
    <label><input type="checkbox" value="2500" id="menu3" onClick="hitung(this);"/> Telur Dadar Rp. 2.500</label><hr/>
    <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
</body>
</html>
```


**HASIL AWAL =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/d96cebd5-925b-4289-8e6d-c4ab58637892" />

**HASIL AKHIR =**

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/8a391a7e-7441-41d7-90c3-82e6c6b140e4" />



# Pertanyaan dan Tugas

## 1. Buat script untuk melakukan validasi pada isian form.

**CODE**
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Absensi Siswa</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background-color: #e8f0fe;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 500px;
            margin: 50px auto;
            background-color: white;
            padding: 25px 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
        h2 {
            text-align: center;
            color: #1a73e8;
            margin-bottom: 25px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 6px;
        }
        input[type="text"],
        input[type="date"],
        select {
            width: 100%;
            padding: 8px;
            border: 1px solid #cfd8dc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        .error {
            color: #e53935;
            font-size: 12px;
            margin-top: 4px;
        }
        button {
            background-color: #1a73e8;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 0 auto;
            font-size: 15px;
        }
        button:hover {
            background-color: #0b59c8;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Form Absensi Siswa</h2>
        <form id="formAbsensi" onsubmit="return validasiAbsensi()">
            <div class="form-group">
                <label for="nama">Nama Siswa:</label>
                <input type="text" id="nama" name="nama">
                <div class="error" id="errorNama"></div>
            </div>

            <div class="form-group">
                <label for="kelas">Kelas:</label>
                <select id="kelas" name="kelas">
                    <option value="">-- Pilih Kelas --</option>
                    <option value="X">X</option>
                    <option value="XI">XI</option>
                    <option value="XII">XII</option>
                </select>
                <div class="error" id="errorKelas"></div>
            </div>

            <div class="form-group">
                <label for="tanggal">Tanggal Kehadiran:</label>
                <input type="date" id="tanggal" name="tanggal">
                <div class="error" id="errorTanggal"></div>
            </div>

            <div class="form-group">
                <label for="status">Status Kehadiran:</label>
                <select id="status" name="status">
                    <option value="">-- Pilih Status --</option>
                    <option value="Hadir">Hadir</option>
                    <option value="Izin">Izin</option>
                    <option value="Sakit">Sakit</option>
                    <option value="Alpa">Alpa</option>
                </select>
                <div class="error" id="errorStatus"></div>
            </div>

            <button type="submit">Simpan Absensi</button>
        </form>
    </div>

    <script>
        function validasiAbsensi() {
            // reset pesan error
            document.getElementById("errorNama").textContent = "";
            document.getElementById("errorKelas").textContent = "";
            document.getElementById("errorTanggal").textContent = "";
            document.getElementById("errorStatus").textContent = "";

            // ambil nilai
            const nama = document.getElementById("nama").value.trim();
            const kelas = document.getElementById("kelas").value;
            const tanggal = document.getElementById("tanggal").value;
            const status = document.getElementById("status").value;

            let valid = true;

            // validasi nama
            if (nama === "") {
                document.getElementById("errorNama").textContent = "Nama harus diisi";
                valid = false;
            } else if (nama.length < 3) {
                document.getElementById("errorNama").textContent = "Nama minimal 3 karakter";
                valid = false;
            }

            // validasi kelas
            if (kelas === "") {
                document.getElementById("errorKelas").textContent = "Pilih kelas terlebih dahulu";
                valid = false;
            }

            // validasi tanggal
            if (tanggal === "") {
                document.getElementById("errorTanggal").textContent = "Tanggal harus diisi";
                valid = false;
            }

            // validasi status
            if (status === "") {
                document.getElementById("errorStatus").textContent = "Pilih status kehadiran";
                valid = false;
            }

            if (valid) {
                alert("Absensi berhasil disimpan!");
            }

            return false; // supaya tidak reload halaman
        }
    </script>
</body>
</html>
```

**HASIL AWAL=**

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/da9b9ad5-6fc2-45bf-bbd0-6529dbedd6ed" />

**HASIL AKHIR=**

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/92757f93-1d49-403b-a3c5-97523a119352" />

