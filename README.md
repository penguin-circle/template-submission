# The Penguin Circle — Template Submission

**github.com/penguin-circle/template-submission**

Fork repo ini sebagai struktur folder buat nyimpen semua project
lo selama 8 segmen The Penguin Circle.

## Cara Fork

1. Login ke GitHub
2. Buka repo ini
3. Klik "Fork" (pojok kanan atas)
4. Clone hasil fork ke WSL lo:
   ```bash
   git clone https://github.com/[username-lo]/template-submission.git
   cd template-submission
   mv template-submission the-penguin-circle
   ```
5. Mulai praktik!

## Cara Pake per Segmen

```bash
cd ~/the-penguin-circle
mkdir SEG-01_Navigasi-File
cd SEG-01_Navigasi-File
touch catatan.md
touch explore.sh
# Praktik command. Simpen catatan & script di sini.
```

## Push Tiap Selesai Sesi

```bash
cd ~/the-penguin-circle
git add .
git commit -m "SEG-1: navigasi & file"
git push
```
