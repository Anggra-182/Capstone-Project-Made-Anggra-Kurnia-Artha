# Capstone-Project-Made-Anggra-Kurnia-Artha
Capstone project analisis data jumlah penduduk Indonesia 2024 menggunakan Google Colab dan AI tools (IBM Granite).

Project overview: Proyek ini adalah bagian dari Student Development Initiative HACKTIV8 yang bertujuan untuk menganalisis data publik mengenai jumlah penduduk di setiap provinsi Indonesia pada tahun 2024. Tujuannya adalah untuk menggali wawasan bermakna dari data tersebut dengan bantuan AI. Proses analisis dilakukan menggunakan Google Colab, dengan memanfaatkan library Python seperti Pandas untuk manipulasi data dan Matplotlib untuk membuat visualisasi data.

Raw dataset link: https://sulut.bps.go.id/id/statistics-table/2/OTU4IzI=/jumlah-penduduk-menurut-provinsi-di-indonesia.html atau https://github.com/Anggra-182/Capstone-Project-Made-Anggra-Kurnia-Artha/blob/9d352b539e12708453acb23f0af0d39802d3ff0e/Jumlah%20Penduduk%20Menurut%20Provinsi%20di%20Indonesia%2C%202024.xlsx

Insight & Findings:
Berdasarkan analisis data yang telah dilakukan pada notebook Google Colab, ditemukan beberapa wawasan dan temuan kunci sebagai berikut:
Pembersihan Data: Data mentah memerlukan beberapa langkah pembersihan sebelum dapat dianalisis. Langkah-langkah yang dilakukan antara lain:
Melewatkan 2 baris pertama (header yang tidak relevan).
Mengganti nama kolom menjadi "Provinsi" dan "Jumlah Penduduk" agar lebih mudah dibaca.
Mengubah tipe data kolom "Jumlah Penduduk" menjadi numerik (float) untuk memungkinkan kalkulasi matematis.
Peringkat Populasi Provinsi:
5 Provinsi dengan Penduduk Terbanyak:
Jawa Barat: 50.345,2 (ribu jiwa)
Jawa Timur: 41.814,5 (ribu jiwa)
Jawa Tengah: 37.892,3 (ribu jiwa)
Sumatera Utara: 15.588,5 (ribu jiwa)
Banten: 12.553,3 (ribu jiwa)
5 Provinsi dengan Penduduk Paling Sedikit:
Kalimantan Utara: 739,8 (ribu jiwa)
Papua Barat: 1.205,8 (ribu jiwa)
Gorontalo: 1.227,8 (ribu jiwa)
Maluku Utara: 1.355,6 (ribu jiwa)
Sulawesi Barat: 1.503,2 (ribu jiwa)
Konsentrasi Populasi di Pulau Jawa: Temuan paling signifikan adalah populasi Indonesia sangat terkonsentrasi di Pulau Jawa. Tiga provinsi dengan penduduk terbanyak (Jawa Barat, Jawa Timur, dan Jawa Tengah) semuanya berada di Pulau Jawa dan secara total menampung lebih dari 129 juta jiwa.
Adanya Baris Total Agregat: Dataset ini menyertakan satu baris dengan nama provinsi "Indonesia" yang berisi total jumlah penduduk nasional (281.603,8 ribu jiwa). Baris ini harus dikecualikan saat melakukan analisis per provinsi agar tidak menyebabkan perhitungan ganda dan merusak skala visualisasi data.

AI Support Explanation:
Sesuai dengan tujuan proyek, AI (Large Language Model) dari IBM Granite direncanakan untuk digunakan dalam beberapa skenario guna memperkaya analisis:
Summarization (Peringkasan): Model AI akan digunakan untuk membuat ringkasan naratif otomatis dari temuan-temuan kunci di atas. Contohnya, dengan memberikan data 5 provinsi terpadat, LLM dapat menghasilkan paragraf yang menjelaskan tren konsentrasi penduduk di Pulau Jawa secara deskriptif.
Classification (Klasifikasi): LLM dapat diminta untuk mengklasifikasikan setiap provinsi ke dalam beberapa kategori berdasarkan jumlah penduduknya (misalnya: "Sangat Padat", "Padat", "Sedang", "Jarang"). Ini membantu dalam segmentasi dan pemahaman distribusi populasi secara kualitatif.
Insight Generation (Pembuatan Wawasan Lanjutan): Berdasarkan hasil analisis awal, LLM dapat digunakan untuk brainstorming atau mengajukan pertanyaan analitis lebih lanjut. Contoh prompt: "Berdasarkan data bahwa 3 provinsi terpadat ada di Jawa, pertanyaan lanjutan apa yang relevan untuk dianalisis dari sisi ekonomi dan infrastruktur?" Ini membantu mengarahkan eksplorasi data ke tingkat yang lebih dalam.
