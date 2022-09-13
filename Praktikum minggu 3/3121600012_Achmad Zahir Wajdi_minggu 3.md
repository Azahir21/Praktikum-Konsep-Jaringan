# Laporan Praktikum Konsep Jaringan

### Nama : Achmad Zahir Wajdi

### NRP : 3121600012

### Kelas : 2 D4 Teknik Informatika A

# Analisa cisco packet tracker

## Persiapan Simulasi

![persiapan PC](assets/persiapan.png)

![persiapan ARP](assets/persiapan%20arp.png)

## Kondisi 1, PC0 mengirim ke PC1 untuk pertama kali

![persiapan PC](assets/skenario%201.png)

![persiapan ARP](assets/skenario%201.2.png)

![persiapan PC](assets/skenario%201.3%20PC1.png)

![persiapan ARP](assets/skenario%201.3%20PC2.png)

![persiapan PC](assets/skenario%201.4.png)

![persiapan ARP](assets/skenario%201.4%20PC3.png)

![kondisi arp](assets/skenario%20arp.png)

pada awal ping maka akan terjadi broadcast karena kondisi arp masih kosong sehingga perlu mencari ip yang dicari

## Kondisi 2, PC0 mengirim ke PC1 untuk kedua kali

![persiapan PC](assets/skenario%202.png)

![persiapan ARP](assets/skenario%202.1.png)

![persiapan PC](assets/skenario%202.3%20PC1.png)

![persiapan ARP](assets/skenario%202.3%20PC2.png)

![persiapan PC](assets/skenario%202.4.png)

![persiapan ARP](assets/skenario%202.4%20PC2.png)

![kondisi arp](assets/skenario%20arp.png)

setelah melakukan ping ke-1 maka arp akan tersimpan, pada ping kedua ini tidak terjadi broadcast karenan arp sudah tersimpan dan langsung menuju tujuan.

## Kondisi 3, PC1 mengirim ke PC0

![kondisi arp PC2](assets/skenario%20arp%20PC2.png)

![persiapan PC](assets/skenario%203.png)

![persiapan ARP](assets/skenario%203.1.png)

![persiapan PC](assets/skenario%203.2%20PC0.png)

![persiapan ARP](assets/skenario%203.2%20PC2.png)

![persiapan PC](assets/skenario%203.4.png)

![persiapan ARP](assets/skenario%203.4%20PC2.png)

pada PC1 sudah menyimpan arp PC0 saat PC0 melakukan ping PC1, sehingga saat PC1 melakukan ping pada PC0 maka tidak terjadi broadcast.
