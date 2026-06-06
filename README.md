            const y = Math.random() * 80; 
            
            btnGa.style.position = 'absolute';
            btnGa.style.left = x + 'px';
            btnGa.style.top = y + 'px';
        }

        function cekGerbang2() {
            alert("✨ SURPRISE!! Gak ada rekomendasi kafe, adanya orang yang sayang banget sama kamu! Selamat ulang tahun yang ke-22! 🎉💖");
            document.getElementById('gate2').style.display = 'none';
            document.getElementById('status').innerText = "💖 HAPPY BIRTHDAY";
            document.getElementById('status').style.background = "#d4edda";
            document.getElementById('status').style.color = "#155724";
            
            const titleWeb = document.getElementById('title-web');
            titleWeb.innerText = "Selamat Ulang Tahun, Sayang! ✨";
            titleWeb.style.color = "#ff477e";
            
            document.getElementById('surat-utama').style.display = 'block';
        }
    </script>
    </body>
    </html>
