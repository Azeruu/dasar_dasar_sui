# SUI Data Types & Object Ownership

Repository ini berisi pembelajaran tentang tipe data fundamental di SUI blockchain dan konsep Object Ownership beserta implementasi Struct.

## 🔧 Setup Development
- Sui CLI installation dan konfigurasi
- Project Move setup dan struktur dasar

## 📊 Tipe Data di SUI

### Tipe Data Primitif
- **String** - Tipe data teks
- **Numbers** - Tipe data numerik (u8, u32, u64)
- **Boolean** - Tipe data boolean (true/false)
- **Vector** - Array dinamis untuk koleksi data

## 🏗️ Object Ownership & Struct

### Struct
Struct adalah cara untuk mengelompokkan beberapa data menjadi satu kesatuan. Struct memungkinkan kita untuk membuat tipe data custom yang lebih kompleks.

### Object Ownership Model
Di SUI, terdapat 3 jenis object berdasarkan ownership:

#### 1. Owned Objects
- **Kepemilikan**: Dimiliki oleh address tertentu
- **Akses**: Hanya owner yang dapat mengakses dan memodifikasi
- **Use Case**: Asset personal, NFT, token balance

#### 2. Shared Objects
- **Kepemilikan**: Dapat diakses oleh siapa saja
- **Akses**: Public access untuk semua user
- **Use Case**: Smart contract state, public pool, marketplace

#### 3. Immutable Objects
- **Kepemilikan**: Tidak dapat diubah setelah dibuat
- **Akses**: Read-only untuk semua
- **Use Case**: Configuration, constants, reference data

## 🔐 Capabilities Pattern

Capabilities adalah mekanisme untuk memberikan permission dan kontrol akses menggunakan object ownership. Pattern ini memungkinkan:
- Fine-grained access control
- Delegation of authority
- Secure permission management

## 🚀 Fitur Pembelajaran

### Hands-On Project
- **Campus Management System**: Implementasi lengkap sistem manajemen kampus
- Praktik langsung dengan semua konsep yang dipelajari
- Real-world application development


## 🎯 Learning Objectives

Setelah mempelajari repository ini, Anda akan mampu:
- Memahami tipe data dasar di SUI Move
- Mengimplementasikan struct dan object ownership
- Menerapkan capabilities pattern untuk access control
- Membangun aplikasi Move yang aman dan efisien

## 🔗 Resources

- [SUI Documentation](https://docs.sui.io/)
- [Move Programming Language](https://move-language.github.io/move/)
- [SUI Developer Portal](https://sui.io/developers)
