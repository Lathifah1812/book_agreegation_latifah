# Bookstore README

Repositori ini berisi implementasi sederhana dari sebuah Toko Buku menggunakan Python. Kelas Bookstore memungkinkan Anda untuk menambahkan buku dan menampilkan buku-buku yang tersedia di toko.

## Penggunaan

1. Buat objek Bookstore dengan memberikan sebuah nama:

   ```python
   bookstore = Bookstore("Toko Buku ABC")
   ```

2. Buat objek Book dan tambahkan ke dalam Bookstore:

   ```python
   book1 = Book("Harry Potter and the Philosopher's Stone", "J.K. Rowling", 150000)
   book2 = Book("To Kill a Mockingbird", "Harper Lee", 120000)
   book3 = Book("1984", "George Orwell", 90000)

   bookstore.add_book(book1)
   bookstore.add_book(book2)
   bookstore.add_book(book3)
   ```

3. Tampilkan daftar buku yang tersedia di toko:

   ```python
   bookstore.display_books()
   ```

Hal ini akan mencetak judul, penulis, dan harga buku-buku yang tersedia di toko.

## Rincian Kelas

### Book

Kelas Book merepresentasikan sebuah buku dengan atribut-atribut berikut:

- `title`: Judul buku.
- `author`: Penulis buku.
- `price`: Harga buku.

### Bookstore

Kelas Bookstore merepresentasikan sebuah toko buku dengan atribut-atribut dan metode-metode berikut:

#### Atribut

- `name`: Nama toko buku.
- `books`: Sebuah list untuk menyimpan buku-buku yang ada di toko.

#### Metode

- `__init__(self, name)`: Menginisialisasi sebuah objek Bookstore baru dengan nama yang diberikan.
- `add_book(self, book)`: Menambahkan sebuah buku ke dalam toko buku.
- `display_books(self)`: Menampilkan daftar buku yang tersedia di toko buku.

