# Corporate Asset & Inventory Management 🏢

A centralized asset tracking platform delivering full lifecycle visibility, condition classification, employee custody/mutation logging, and automated compliance auditing for organizational equipment.

---

## 🌟 Live Demo & Portfolio
- **Author:** Frans Kurniawan
- **Portfolio:** [https://franskur.github.io](https://franskur.github.io)
- **Role:** Full-Stack PHP Web Developer

---

## 🚀 Key Features

- **Comprehensive Asset Lifecycle Tracking:**
  - Complete historical records from asset acquisition, warranty tagging, depreciation calculation, maintenance scheduling, to decommission.
  - Categorization by asset class (IT Hardware, Office Furniture, Operational Vehicles).

- **Employee Custody & Mutation Logging:**
  - Digital lending workflows, handover receipts, and department transfer records.
  - Return date reminders and overdue equipment notifications.

- **Immutable Audit Trails & Maintenance Logs:**
  - Detailed historical audit logs recording every location transfer, repair history, cost, and technician notes.

- **Automated Stock Reconciliation & Exporting:**
  - Real-time inventory variance reports with one-click export to Excel and PDF formats for executive audits.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** Laravel Framework (Eloquent ORM, Custom Observers & Events)
- **Database:** MySQL (Relational schema with soft deletes and audit trail tables)
- **Data Grids:** DataTables.js with server-side pagination and fast filtering
- **Frontend:** Bootstrap 5, Blade, JavaScript (ES6+)

---

## ⚡ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/franskur/corporate-asset-inventory-management.git
   cd corporate-asset-inventory-management
   ```

2. **Install Composer Dependencies:**
   ```bash
   composer install
   ```

3. **Setup Environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Run Migrations & Seed Sample Data:**
   ```bash
   php artisan migrate --seed
   ```

5. **Start Development Server:**
   ```bash
   php artisan serve
   ```

---

## 📄 License & Notes
Designed and developed by **Frans Kurniawan**. Open for enterprise adaptation and portfolio review.
