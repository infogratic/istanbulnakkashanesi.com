---
title: "İcra Heyeti"
permalink: "/icraheyeti"
comments: false
---

    <style>
        /* Sayfa stili */
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            transition: background-color 5s; /* Ekran kararırken yavaş geçiş */
        }
        h1 {
            color: #333;
        }
        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0); /* Başlangıçta sayfa şeffaf */
            z-index: 9999;
            transition: background-color 5s ease-in-out; /* Geçiş efekti */
        }
        /* Ekran kararınca arka plan rengi değişecek */
        .darken {
            background-color: rgba(0, 0, 0, 0.8);
        }
    </style>

<img src="/assets/images/posts/icraheyeti.png" alt="">

    <div class="overlay" id="overlay"></div>

    <script>
        // Sayfa yüklendikten 1 saniye sonra overlay katmanını karartmaya başla
        setTimeout(function() {
            document.getElementById('overlay').classList.add('darken');
        }, 1000); // 1 saniye sonra kararacak

        // Yönlendirme için 5 saniye sonra sayfayı değiştirme
        setTimeout(function() {
            window.location.href = "https://www.istanbulmushafi.com";
        }, 5000); // 5 saniye sonra yönlendirme
    </script>
