with open("README.md", "w", encoding="utf-8") as file:
  )
    
    file.write("## 📁 Dosya Yapısı\n\n")
    file.write("```\n")
    file.write("├── coordinates.csv  \n")
    file.write("├── point.py#    \n")
    file.write("└── README.md     \n")
    file.write("```\n\n")
    
    file.write("## 🛠 Kullanılan Git Komutları\n\n")
    file.write("```bash\n")
    file.write("git init                  # Depo oluşturma\n")
    file.write("git add .                 # Değişiklikleri ekleme\n")
    file.write("git commit -m \"İlk commit\" # Değişiklikleri kaydetme\n")
    file.write("git push -u origin main   # GitHub’a gönderme\n")
    file.write("```\n\n")
    
    file.write("## 📝 Açıklamalar\n\n")
    file.write("- GitHub’a yüklemek için yukarıdaki komutlar kullanılmıştır.\n\n")

##  Yerel Git İş Akışı ile GitHub İş Akışı Arasındaki Farklar

| Özellik            | Yerel Git İş Akışı | GitHub İş Akışı |
|--------------------|--------------------|-----------------|
| **Çalışma Ortamı**  | Bilgisayardaki yerel depo | GitHub’daki uzak depo |
| **Değişiklik Kaydetme** | `git commit` ile yerelde kaydedilir | `git push` ile GitHub’a gönderilir |
| **Erişim** | Sadece bilgisayarda çalışır | İnternet üzerinden erişilebilir |
