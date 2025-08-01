# Laravel CRUD REST API

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

![Animated Introduction](https://user-images.githubusercontent.com/20955511/199068351-f86c1f32-541f-404e-a9ce-486b5d1b0225.gif)

Welcome to the **Laravel CRUD REST API**. This project is a simple implementation of a RESTful API using Laravel with CRUD (Create, Read, Update, Delete) functionality.

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

