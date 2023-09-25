
# Project Title

A brief description of what this project does and who it's for


    #login Nama, NIM
    print("-"*36)
    print("Silahkan Login")
    nama = input("Masukkan Nama : ")
    nim = input("Masukkan NIM : ")
    print("Login Sukses")
    print("-"*36)

    #konversi nilai tukar Rp1.000 ke dolar,yen,ringgit
    nilai_tukar_usd = 0.07 
    nilai_tukar_jpy = 9.66
    nilai_tukar_myr = 0.31

    # Menampilkan menu pilihan mata uang
    print("\nPilih mata uang untuk konversi:")
    print("1. USD")
    print("2. JPY")
    print("3. MYR")

    # Meminta pengguna untuk memilih mata uang
    pilihan = int(input("Masukkan nomor pilihan Anda (1/2/3): "))

    # Menentukan mata uang berdasarkan pilihan
    if pilihan == 1:
        mata_uang = "USD"
        nilai_tukar = nilai_tukar_usd
    elif pilihan == 2:
        mata_uang = "JPY"
        nilai_tukar = nilai_tukar_jpy
    elif pilihan == 3:
        mata_uang = "MYR"
        nilai_tukar = nilai_tukar_myr
    else:
        print("Pilihan tidak valid. Program Berakhir.")
    exit()

    #memasukkan jumlah IDR
    print(" Contoh Nominal Seperti 1.000 IDR")
    jumlah_idr = float(input(f"Masukkan jumlah IDR yang ingin dikonversi ke {mata_uang}: "))

    # Konversi mata uang dipilih
    jumlah_mata_uang = jumlah_idr * nilai_tukar

    #hasil Konversi
    print(f"{jumlah_idr} IDR setara dengan {jumlah_mata_uang:.2f} {mata_uang}")

    print("-"*36)
    print("Program Berakhir")

<img width="257" alt="hasil pos tes" src="https://github.com/hiskyaharsyalkila/hiskyaharsyalkilaPOSTEST-1-NIM-GANJIL-/assets/144862428/5fb50065-211c-4815-8dcf-9c875423891b">

![nilai tukar rupiah drawio](https://github.com/hiskyaharsyalkila/hiskyaharsyalkilaPOSTEST-1-NIM-GANJIL-/assets/144862428/cca4af78-fd93-4923-a24b-34262499775f)
