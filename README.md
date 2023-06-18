# Implementasi Algoritma Random Forest Pada Klasifikasi Kematangan Buah Pisang Berdasarkan Fitur Warna

## Kelompok 1 Paralel 1 Mata Kuliah Pengolahan Citra Digital

<table>
    <tr>
        <th>Nama</th>
        <th>NIM</th>
    </tr>
    <tr>
        <td>Ahmad Bintang Arif</td>
        <td>G6401201025</td>
    </tr>
    <tr>
        <td>Surya F Helmiyanto</td>
        <td>G6401201036</td>
    </tr>
    <tr>
        <td>Faiz Byputra</td>
        <td>G6401201056</td>
    </tr>
    <tr>
        <td>Daffa Fikri</td>
        <td>G6401201086</td>
    </tr>
</table>

## Deskripsi

Mengklasifikasikan kematangan buah pisang menggunakan dataset dari kaggle dengan link "https://www.kaggle.com/datasets/jackshiels1/bananai?select=Banana_Condensed_Three_Cat" dengan menggunakan algoritma Random Forest.

## Abstrak

Penelitian ini bertujuan mengimplementasikan algoritma Random Forest yang akan mengklasifikasikan kematangan buah pisang berdasarkan fitur warna-warnanya atau color space. Dataset yang digunakan terdiri dari sampel pisang yang telah diklasifikasikan menjadi tiga kategori: overripe, underripe, dan ripe. Lalu kami gunakan metode resize dan di-segmentasi untuk mempermudah proses pelatihan modelnya. Model yang digunakan sebenarnya melakukan identifikasi pola warna pada buah pisang dan memprediksi tingkat kematangannya. Hasil penelitian yang kami lakukan memperoleh akurasi sebesar 74% untuk pisang yang disegmentasi dan 84% untuk pisang yang tidak disegmentasi. Hal ini terjadi karena saat proses segmentasi pola warna berkurang namun dengan angka akurasi yang tinggi fitur warna saja sudah cukup baik dalam melakukan klasifikasi kematangan pada buah pisang. Oleh karena itu, menggunakan fitur warna sebagai satu-satunya kriteria dan model dari Random Forest dapat dianggap sebagai pendekatan yang efektif dan efisien dalam klasifikasi kematangan buah pisang.

---

## Development

Clone the repository:
```bash
git clone https://github.com/Katchuushaa/banana-ripe-classification.git
```

Change to directory:
```bash
cd banana-ripe-classification
```

**This repo is using Python virtual environment.**

Installing venv package:
```py
pip install virtualenv
```

Create venv:
```py
python -m venv env
```

To activate the venv:
```bat
env/Scripts/activate.bat //In CMD
env/Scripts/Activate.ps1 //In Powershell
```

> Make sure you're inside the virtual environment. Marked with `(env)` before the shell.

If you install a new package, regenerate the list of packages in `requirements.txt`
```py
pip freeze > requirements.txt
```

Installing packages
```py
pip install -r requirements.txt
```

Full venv tutorial [here](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)
