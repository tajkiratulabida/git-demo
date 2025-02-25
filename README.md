Product Management System (Laravel + AdminLTE + DataTables)

This project is a Product Management System built using Laravel Breeze, AdminLTE for UI styling, and DataTables for dynamic product listings. It provides complete CRUD operations for products with features like multi-step product creation, image upload handling, and responsive product listings.

✨ Key Features:
📝 Create: Multi-step product creation form with image upload support.
📋 Read: Product listing with DataTables integration for search, pagination, and sorting.
✏️ Update: Edit product details using a simple form.
🗑️ Delete: Delete products with confirmation prompts.
🖼️ Image Handling: Secure image upload with dynamic display.
⚡ Modern UI: Integrated AdminLTE for a clean and responsive admin dashboard.

💡 Technologies Used:
⚡ Laravel Breeze for authentication and project scaffolding.
🎨 AdminLTE for responsive UI components.
📊 Yajra DataTables for interactive and dynamic product listing.
🏃 Bootstrap 5 for styling.
🛢️ MySQL for database management.

🚀 Setup & Installation:
1️⃣ Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install dependencies:
composer install
npm install && npm run dev

3️⃣ Configure environment:
cp .env.example .env
php artisan key:generate

4️⃣ Run migrations:
php artisan migrate

5️⃣ Create storage symlink for image access:
php artisan storage:link

6️⃣ Start the development server:
php artisan serve



