🎬 Film Türü Yönetim Uygulaması
🧩 Proje Hakkında

Bu proje, film türlerini yönetmek, yeni türler eklemek, listelemek ve düzenlemek için geliştirilmiş bir web uygulamasıdır.
Ayrıca uygulama içerisinde Home (Ana Sayfa), Provisy ve Film Türü sayfaları bulunmaktadır.

🚀 Özellikler

🎞️ Yeni film türü ekleme

🗂️ Var olan türleri listeleme

✏️ Film türlerini düzenleme veya silme

🏠 Home sayfası: genel tanıtım veya yönlendirme ekranı

⚙️ Provisy sayfası: yönetim veya yapılandırma işlemleri için kullanılır

🛠️ Kullanılan Teknolojiler

C# / ASP.NET Core MVC (veya kullandığın teknoloji neyse buraya yaz)

Entity Framework Core – veri tabanı işlemleri için

SQL Server / SQLite – veritabanı yönetimi

HTML, CSS, JavaScript / Razor Pages – arayüz tasarımı

📂 Proje Yapısı
/Controllers
    HomeController.cs
    FilmTuruController.cs
    ProvisyController.cs

/Models
    FilmTuru.cs

/Views
    /Home
        Index.cshtml
    /FilmTuru
        Index.cshtml
        Create.cshtml
        Edit.cshtml
    /Provisy
        Index.cshtml

💡 Kurulum ve Çalıştırma

Bu projeyi bilgisayarına klonla:

git clone https://github.com/<kullanici-adin>/<repo-adin>.git


Visual Studio ile projeyi aç.

Gerekli bağımlılıkları yükle (NuGet üzerinden).

Uygulamayı çalıştırmak için:

Ctrl + F5


Tarayıcıda açılan sayfadan Home, Provisy veya Film Türü sayfalarına gidebilirsin.

🧠 Geliştirici Notları

Film türleri veritabanında saklanır.

Uygulama MVC mimarisi ile geliştirilmiştir.

Yeni tür eklemek için Film Türü → Ekle sayfasını kullanabilirsin.


🎬 Movie Genre Management Application
🧩 About the Project

This project is a web application developed to manage movie genres — allowing users to add, list, edit, and delete genres.
The application includes Home, Provisy, and Movie Genre pages.

🚀 Features

🎞️ Add new movie genres

🗂️ List existing genres

✏️ Edit or delete genres

🏠 Home Page: general introduction or navigation page

⚙️ Provisy Page: used for administration or configuration purposes

🛠️ Technologies Used

C# / ASP.NET Core MVC

Entity Framework Core – for database operations

SQL Server / SQLite – for database management

HTML, CSS, JavaScript / Razor Pages – for the user interface

📂 Project Structure
/Controllers
    HomeController.cs
    FilmTuruController.cs
    ProvisyController.cs

/Models
    FilmTuru.cs

/Views
    /Home
        Index.cshtml
    /FilmTuru
        Index.cshtml
        Create.cshtml
        Edit.cshtml
    /Provisy
        Index.cshtml

💡 Installation and Usage

Clone this project to your local machine:

git clone https://github.com/<your-username>/<your-repository>.git


Open the project with Visual Studio.

Install the required dependencies (via NuGet).

Run the application:

Ctrl + F5


From the browser, navigate to the Home, Provisy, or Movie Genre pages.

🧠 Developer Notes

Movie genres are stored in the database.

The project follows the MVC architecture.

To add a new genre, use the Movie Genre → Add page.

