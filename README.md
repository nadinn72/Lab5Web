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


## Seleksi Kondisi (IF.ELSE)

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

## Penggunaaan Operator Switch Untuk Seleksi Kondisi

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
## Form Input

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


## Form Button

**CODE**








