1. buat file index.php > di folder tugas-sesi-04
2. buat html //emmet
3. code (sample) :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tugas sesi 4</title>
</head>
<body>
    <h1>
        Belajar Java Script AlgorFitma
    </h1>
    <script>
        // belajar membuat algoritma perhitungan nilai
        var nilai = 60
        if (nilai >= 60) console.log("mahasiswa dinyatakan lulus")
        else if (nilai < 60) console.log("mahasiswa dinyatakan tidak lulus")
        else console.log("tidak sesuai")
        
        // membuat algoritma luas persegi
        // this code
        var sisi = 5
        var luas = sisi * sisi
        console.log("luas persegi = " + luas)

        // membuat algoritma jika kita lapar
        // this code
        var lapar = "lapar"
        if (lapar === "lapar") console.log("makan")
        else  console.log("tidak makan")

        // menerapkan looping

        // 1. while
        // this code
        var i = 0
        while (i < 10) {
        console.log ("while " + i)
        i++;
        }

        // 2. do while
        // this code
        var angka = 0
        do {
        console.log("do while " + angka)
        angka++;
        }
        while (angka < 10);

        // 3. for
        // this code
        for (var i = 0; i < 10; i++) {
        console.log("for " + i) 
        }
        // menggunakan nilai 0 s.d 10
    </script>

</body>
</html>

----------
1. googling/searching
2. w3school : https://www.w3schools.com/java/java_for_loop.asp