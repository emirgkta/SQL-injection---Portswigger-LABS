# PortSwigger LAB 1 – SQL Injection  
### SQL injection vulnerability in WHERE clause allowing retrieval of hidden data

## 🔗 Bağlantılar
- **YouTube Çözüm Videosu:** [youtube-link.txt](./youtube-link.txt)
- **Orijinal Lab:** [lab-link.txt](./lab-link.txt)
- **Medium Yazısı:** https://medium.com/@emir78.gkta/sql-injection-portswigger-lab-1-sql-injection-vulnerability-in-where-clause-allowing-retrieval-f734c234215d

## 📝 Açıklama
Bu lab, ürün kategorisi filtrelemesinde kullanılan `category` parametresinin SQL sorgusuna doğrudan dahil edilmesi nedeniyle oluşan bir SQL Injection zafiyetini göstermektedir.

Kullanıcı girdisine `'` ekleyerek hata testi yapılabilir, `--` ile filtre devre dışı bırakılabilir ve `OR '1'='1'` kullanılarak tüm ürünlerin görüntülenmesi sağlanabilir.

## 📌 Not
Nuclei template bu lab için daha sonra eklenecektir.
