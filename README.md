🌐 E‑Mall Guru

*E‑Mall Guru* is a powerful and open-source multi-vendor Laravel eCommerce solution. It is fully customizable and ready to use. It’s the perfect choice for launching your online store with ease and efficiency.

---

## 🚀 Features

- ✅ Built with *Laravel 10+*
- 👥 Multi‑vendor support
- 🌍 Multi‑lingual support (*19 languages*, including Indian regional and global languages)
- 👑 Role‑based dashboards:
  - Admin Panel
  - Seller Panel
  - Customer Panel
- 🧩 Modular & extensible architecture
- 📊 Integrated *Yajra Laravel DataTables* for dynamic tables
- 🔐 Secure API authentication with *Laravel Sanctum*

---

## 🧩 Tech Stack

| Layer         | Technology                            |
|---------------|----------------------------------------|
| *Backend*   | Laravel 10+                            |
| *Database*  | MySQLi                                 |
| *Frontend*  | Blade Templates with Laravel UI        |
| *Auth*      | Laravel Sanctum                       |
| *Tables*    | Yajra Laravel DataTables              |

---

## 🧭 Role-Based System Explained

### 👑 Admin Panel
- Manage sellers, products, categories, orders, customers
- Approve or reject seller registrations
- View platform-wide analytics and earnings
- Control site-wide settings (language, themes, configurations)

### 🏪 Seller Panel
- Register for a vendor account (await admin approval)
- Manage personal storefront
- Add/edit/delete products
- Track and fulfill orders
- Access sales and earnings reports

### 🛍 Customer Panel
- Browse products by category or search
- Multilingual browsing experience
- Add to cart, wishlist, and place orders
- Manage personal details, addresses, and view order history

---

## 🌐 Multilingual Support

🗣 Supports *19+ languages*, including:

- Hindi
- Tamil
- Telugu
- Bengali
- Marathi
- Gujarati
- Kannada
- Malayalam
- Punjabi
- Urdu
- English
- And many more...

> Easily customizable via Laravel’s built-in localization system. Language files are located in resources/lang/.

---

## 🛠 Getting Started (Local Setup)

### 1. Clone the Repository

```bash
git clone https://github.com/Ranaprince19/E-Commerc_Website_with_Laravel_Structure-.git
cd E-Commerc_Website_with_Laravel_Structure-

```
2. Install Dependencies
```bash
composer install
npm install
npm run dev
```

3. Configure Environment
Duplicate
```bash
.env.example → .env
```
Set your database, mail, and app configurations

4. Generate Application Key
```bash
php artisan key:generate
```
5. Run Migrations and Seed Database
```bash
php artisan migrate --seed
```
6. Serve the Application
```bash
php artisan serve
```
Visit: http://127.0.0.1:8000

## 🔐 Access Panels

| **Role**   | **URL**              | **Access Type**                          |
|------------|----------------------|-------------------------------------------|
| Admin      | `/admin/login`       | You can create manually                   |
| Seller     | `/seller/register`   | Register, wait for admin approval         |
| Customer   | `/login` or `/register` | Register normally                        |


📁 <strong>Key Module Directories:</strong>

```text
app/Http/Controllers/Admin/       → Admin operations
app/Http/Controllers/Seller/      → Seller logic
app/Http/Controllers/Customer/    → Customer UI & interaction

resources/views/admin/            → Admin Blade views
resources/views/seller/           → Seller Blade views
resources/views/customer/         → Customer Blade views

routes/web.php                    → All route definitions
```

## 🙋‍♂️ Contact

**Prince Kumar**  
📧 [princebaghal637@gmail.com ](princebaghal637@gmail.com)  
🔗 GitHub: [@Ranaprince19](https://github.com/Ranaprince19)

---

**Made with ❤️ using Laravel**
