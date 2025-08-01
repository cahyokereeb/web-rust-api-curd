<div align="center">
  <h1>🚀 Laravel CRUD REST API</h1>
  <p>Complete REST API with Full CRUD Operations for Product Management</p>
  
  ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
  ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
  ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
  ![API](https://img.shields.io/badge/API-REST-blue?style=for-the-badge)
  
  <img src="https://github.com/laravel/art/blob/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel">
</div>

---

## 📖 Tentang Project Ini

**Laravel CRUD REST API** adalah implementasi REST API lengkap yang dibangun menggunakan framework Laravel. Project ini menyediakan operasi CRUD (Create, Read, Update, Delete) untuk manajemen produk dengan fitur pencarian, filtering, sorting, dan pagination.

### 🎯 Apa yang dimaksud dengan REST API?

REST API adalah arsitektur web service yang memungkinkan aplikasi untuk berkomunikasi satu sama lain melalui HTTP. API ini tidak memiliki tampilan website tradisional, melainkan mengembalikan data dalam format JSON yang dapat digunakan oleh aplikasi frontend (mobile app, web app, dll).

LINK DRIVER PROJEK : https://drive.google.com/file/d/1Fb03pn35QHvBfDUYPhQIG49jFFKAt4kx/view?usp=drive_link

## 🚀 Features

- 📦 **CRUD Operations**: Handle products with full CRUD functionality.
- 🔍 **Search and Filter**: Easily search and filter products.
- 🔄 **Sorting and Pagination**: Sort and paginate through your product list.
- ⚡ **Built with Laravel**: Enjoy the robust features of the Laravel framework.

## 📚 Getting Started

### Prerequisites

- [PHP](https://www.php.net/manual/en/install.php) 8.0 or later
- [Composer](https://getcomposer.org/download/)
- [Laravel](https://laravel.com/docs/8.x/installation)

### Installation

1. **Clone the repository**

```bash
  git clone https://github.com/YourUsername/YourRepo.git
  cd YourRepo
```

2. **Install dependencies**

```bash
  composer install
```

3. **Setup environment**

```bash
  copy .env.example .env
  php artisan key:generate
```

4. **Run Migrations and Seeders**

```bash
  php artisan migrate --seed
```

5. **Serve the application**

```bash
  php artisan serve
```

Visit `http://127.0.0.1:8000` to see the Laravel welcome page.

## 📈 API Endpoints

- **Health Check**: `GET /api/health`
- **CRUD Operations**:
  - `GET /api/v1/products`
  - `POST /api/v1/products`
  - `GET /api/v1/products/{id}`
  - `PUT /api/v1/products/{id}`
  - `DELETE /api/v1/products/{id}`

## 🌟 Usage

To test the API, you can use tools like **Postman**, **Insomnia**, or **curl**.

Here's a basic example using curl:

```bash
# Get all products
curl http://127.0.0.1:8000/api/v1/products

# Create a new product
curl -X POST http://127.0.0.1:8000/api/v1/products \
   -H "Content-Type: application/json" \
   -d '{"name":"New Product", "price":123.45}'
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 👏 Acknowledgements

- [Laravel Documentation](https://laravel.com/docs)
- [PHP Documentation](https://www.php.net/manual/en/)

## 🎨 Design Inspiration

The animations and badges make it appealing and engaging for users who visit the repository. Let's keep open-source fun and exciting!

![Animated Illustration](https://user-images.githubusercontent.com/20955511/199068351-f86c1f32-541f-404e-a9ce-486b5d1b0225.gif)

