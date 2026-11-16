# Earlier projects

Full-stack web applications I built before my current work, kept here as code samples. For case studies of my recent work, see **[baselkaffoura.com](https://baselkaffoura.com)**.

| Project | Stack | What it does |
|---|---|---|
| [LMS platform](lms-platform) | Laravel 10 · PHP 8.1 · Vite | E-learning platform with admin, instructor and student roles, course management and enrolment, and checkout for paid courses |
| [E-commerce website](ecommerce-website) | Laravel 10 API with Stripe · Vue 3 · Pinia · Vue Router | Online store with admin, editor and customer roles, product search with dynamic attributes, and payment and shipping options |
| [Task management](task-management) | Laravel 10 · Blade · Alpine.js · Tailwind CSS | Create, assign and update tasks, with roles for admins, managers and team members, deadlines and progress tracking |
| [Real estate system](real-estate-system) | Laravel 11 · PHP 8.3 · Jetstream · Livewire · Octane · Tailwind CSS | Property listings and transactions, with an admin panel and property analytics |
| [Schools online](schools-online) | Laravel 9 · Laravel UI · Tailwind CSS · Alpine.js | Management of students, teachers and classes, with student profiles and unique IDs |

## Running a project

Each folder is a standalone Laravel application. The e-commerce project has a Laravel API in `backend` and a Vue app in `frontend`.

```bash
cd real-estate-system   # or another project folder
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install && npm run dev
php artisan serve
```

## Contact

[baselkaffoura.com](https://baselkaffoura.com) · [LinkedIn](https://www.linkedin.com/in/basel-kaffoura/)
