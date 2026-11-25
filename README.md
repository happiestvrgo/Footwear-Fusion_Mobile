# Footwear Fusion Mobile

Aplikasi mobile e-commerce toko sepatu berbasis **Flutter** dan **Dart** yang dikembangkan sebagai proyek pengembangan aplikasi perangkat bergerak di **Politeknik Negeri Jember**.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.3%2B-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Provider](https://img.shields.io/badge/State-Provider-16A34A?style=for-the-badge)

---

## Fitur Utama

- **Autentikasi Pengguna**: Splash screen, login (`sign_in_page.dart`), dan registrasi akun (`sign_up_page.dart`) terhubung ke API via `AuthProvider` & `AuthService`.
- **Katalog & Detail Produk**: Halaman beranda dengan kategori sepatu, carousel gambar produk, halaman detail produk (`product_page.dart`), dan daftar favorit (`wishlist_page.dart`).
- **Keranjang & Checkout**: Pengelolaan keranjang belanja (`cart_page.dart`), halaman checkout (`checkout_page.dart`), konfirmasi transaksi berhasil (`checkout_success_page.dart`), daftar alamat pengiriman (`AddressListScreen.dart`), dan riwayat pembelian (`PurchaseHistoryPage.dart`).
- **Chat & Profil**: Fitur chat dengan penjual (`chat_page.dart`, `detail_chat_page.dart`) serta pengelolaan profil pengguna (`profile_page.dart`, `edit_profile_page.dart`).

---

## Tech Stack & Package Utama

| Komponen | Library / Tools |
| :--- | :--- |
| Framework & Bahasa | Flutter, Dart SDK `>=3.3.2 <4.0.0` |
| State Management | `provider` |
| Networking & Storage | `http`, `shared_preferences` |
| UI & Media | `google_fonts`, `carousel_slider`, `cached_network_image`, `fluttertoast`, `cupertino_icons` |

---

## Cara Menjalankan

```bash
# 1. Clone repository
git clone https://github.com/happiestvrgo/Footwear-Fusion_Mobile.git
cd Footwear-Fusion_Mobile

# 2. Instal dependensi Flutter
flutter pub get

# 3. Jalankan aplikasi di emulator atau perangkat
flutter run
```

> Sesuaikan alamat base URL backend API pada `lib/config.dart` atau `config.json` sebelum menjalankan aplikasi.
