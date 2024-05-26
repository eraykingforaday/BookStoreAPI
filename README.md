# BookStore Web API

Bu proje, ASP.NET Core kullanarak oluşturulmuş bir kitap yönetim Web API'sidir. Bu API, kitap ekleme, listeleme, güncelleme ve silme işlevlerini sağlar.

## Kurulum

1. Bu repoyu klonlayın:
   ```sh
   git clone https://github.com/kullanici-adi/bookstore-api.git
   ```

2. Proje dizinine gidin:
   ```sh
   cd bookstore-api
   ```

3. Gerekli NuGet paketlerini yükleyin:
   ```sh
   dotnet restore
   ```

4. Veritabanını oluşturun ve migrasyonları çalıştırın:
   ```sh
   dotnet ef database update
   ```

5. Uygulamayı başlatın:
   ```sh
   dotnet run
   ```

## API Endpointleri

- **GET /api/books**: Tüm kitapları listeler
- **GET /api/books/{id}**: Belirli bir kitabı getirir
- **POST /api/books**: Yeni bir kitap ekler
- **PUT /api/books/{id}**: Belirli bir kitabı günceller
- **DELETE /api/books/{id}**: Belirli bir kitabı siler

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
