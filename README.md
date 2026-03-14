# AWS E-Ticaret Projesi

## Proje Hakkında
AWS üzerinde bir e-ticaret sitesi altyapısı kuruldu.

## Kullanılan Servisler
- VPC: Güvenli ağ altyapısı
- EC2: Web sunucusu, nginx ile çalışıyor
- RDS: MySQL veritabanı
- IAM: Güvenli erişim yönetimi
- Auto Scaling: Yük altında otomatik büyüme
- CloudWatch: İzleme ve alarm

## Mimari
Kullanıcı → EC2 (nginx) → RDS (MySQL)
