# Tugas praktikum4
Nama : Ro'uf Muhammad Fauzan

NIM : 312410157

Kelas : TI.24.A1

# Flowchart input dan outpu dari Praktikum 4
## Berikut flowchart
![flowchart](Flowchart.png)
## Berikut input
![flowchart](input.png)
## Berikut output
![flowchart](output.png)

# 1. Fungsi hitung_nilai_akhir(tugas, uts, uas):
```
def hitung_nilai_akhir(tugas, uts, uas):
    """Hitung nilai akhir berdasarkan bobot tugas, UTS, dan UAS."""
    bobot_tugas = 0.3
    bobot_uts = 0.35
    bobot_uas = 0.35
    return (tugas * bobot_tugas) + (uts * bobot_uts) + (uas * bobot_uas)
```
Fungsi ini menerima 3 parameter: nilai tugas, UTS, dan UAS
Menghitung nilai akhir dengan bobot:
Tugas: 30% (0.30)
UTS: 35% (0.35)
UAS: 35% (0.35)
Mengembalikan hasil perhitungan nilai akhir
