# Threads - Online Social Media and Networking Service

Threads is an online social media and networking service developed using the Laravel PHP framework along with the TALL (Tailwind CSS, Alpine.js, Laravel, and Livewire) stack. The application enables users to share text-based posts and engage with other users' posts through replies, reposts, and likes.

## Features

- User authentication and authorization
- Text-based post creation and sharing
- Post interaction functionalities, including replies, reposts, and likes
- Real-time updates through Livewire
- Responsive design using Tailwind CSS

## Installation

Follow these steps to get started with Threads:

1. Clone the repository:

   ```bash
   git clone https://github.com/SouvikDas-git/threads.git
   ```
2. Navigate to the project directory:
    ```bash
    cd threads
    ```
3. Install the dependencies:
    ```bash
    composer install
    npm install && npm run dev
    ```
4. Set up the environment variables:
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```
5. Run the database migrations:
    ```bash
    php artisan migrate
    ```
6. Start the development server:
    ```bash
    php artisan serve
    ```
The application will be available at [http://localhost:8000](http://localhost:8000).
## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a pull request or open an issue in the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Laravel - [https://laravel.com](https://laravel.com)
- Tailwind CSS - [https://tailwindcss.com](https://tailwindcss.com)
- Alpine.js - [https://github.com/alpinejs/alpine](https://github.com/alpinejs/alpine)
- Livewire - [https://laravel-livewire.com](https://laravel-livewire.com)

Feel free to use this template as a starting point and customize it according to your specific project details.
