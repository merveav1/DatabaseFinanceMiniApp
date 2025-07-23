# Veri Tabanı ve Finansal Modelleme Projesi | Database and Financial Modeling Project

## Proje Açıklaması | Project Description

**TR:**  
Bu proje, Python dili kullanılarak hazırlanmış çok bileşenli bir uygulamadır. Proje iki temel bölüme ayrılmıştır:  
1. SQL Server veritabanı ile temel veritabanı işlemleri (CRUD)  
2. Avrupa tipi bariyer opsiyon fiyatlaması (finansal simülasyon)

**EN:**  
This project is a multi-component application developed using Python. It includes two main modules:  
1. Basic database operations (CRUD) with SQL Server  
2. Pricing of European barrier options (financial simulation)

---

## Kullanılan Teknolojiler | Technologies Used

| Teknoloji | Açıklama |
|-----------|----------|
| Python 3.x | Ana programlama dili |
| pypyodbc | SQL Server veritabanına bağlantı için |
| SQL Server | Veritabanı yönetim sistemi |
| NumPy | Finansal simülasyonlar ve hesaplamalar için |
| Matplotlib | Finansal veri görselleştirme için |

---

## Özellikler | Features

**TR:**
- SQL Server ile bağlantı kurulması
- Veritabanında tablo oluşturma, veri ekleme, güncelleme ve silme işlemleri
- Avrupa tipi bariyer opsiyonu için Monte Carlo simülasyonu
- Sonuçların grafiksel olarak görselleştirilmesi

**EN:**
- Connection to SQL Server database
- Table creation, data insertion, update and deletion
- Monte Carlo simulation for European barrier option pricing
- Visualization of simulation results

---

## Kurulum ve Kullanım | Setup and Usage

**TR:**
1. Gerekli Python kütüphanelerini yükleyin (`pypyodbc`, `numpy`, `matplotlib`)
2. SQL Server'ınızda `TestDB` adlı bir veritabanı oluşturun
3. Jupyter Notebook ortamında dosyayı açarak hücreleri sırayla çalıştırın

**EN:**
1. Install required Python libraries (`pypyodbc`, `numpy`, `matplotlib`)
2. Create a database named `TestDB` in your SQL Server
3. Open the notebook in Jupyter and run the cells sequentially

---

## Veritabanı Yapısı | Database Structure

**Tablo:** Personel  
Alanlar:  
- ID (int, PRIMARY KEY)  
- Name (nvarchar)  
- Age (int)

---

## Geliştirici Notu | Developer's Note

**TR:**  
Bu proje, hem veritabanı uygulamaları hem de finansal analiz modelleri hakkında temel bir anlayış sunar. Akademik veya eğitim amaçlı kullanılabilir, aynı zamanda iş başvurularında destekleyici proje olarak değerlendirilebilir.

**EN:**  
This project provides a basic understanding of both database applications and financial analysis models. It can be used for educational purposes or as a supporting portfolio project for job applications.