# Agile Final Project Kit

## Judul Proyek

Sistem Manajemen Produk Sederhana

## Deskripsi Singkat

Proyek ini adalah aplikasi sederhana untuk mengelola data produk. Fitur utamanya mencakup menambah, melihat, memperbarui, dan menghapus produk. Proyek ini dibuat untuk memenuhi tugas akhir Agile dengan user story, acceptance criteria Gherkin, label backlog, sprint backlog, milestone, dan technical debt.

## Struktur Repository

```text
agile-final-project/
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── user_story.md
├── README.md
└── docs/
    └── sprint-plan.md
```

## File `.github/ISSUE_TEMPLATE/user_story.md`

````md
---
name: User Story
about: Template untuk user story Agile final project
title: "[USER STORY] "
labels: "Product Backlog"
assignees: ""
---

## User Story
**As a** [role]  
**I need** [function]  
**So that** [benefit]  

## Acceptance Criteria
```gherkin
Given ...
When ...
Then ...
````

## Estimasi

* Story Points: [1/2/3/5/8]

````

## Isi `README.md`

```md
# Sistem Manajemen Produk Sederhana

Repositori ini dibuat untuk tugas akhir Agile. Proyek menggunakan pendekatan Agile dengan Kanban board, backlog, sprint backlog, milestone, dan burndown chart.

## Fitur
- Menambahkan produk
- Melihat daftar produk
- Memperbarui data produk
- Menghapus produk
- Mencari produk berdasarkan nama

## Agile Workflow
- Semua issue dibuat dalam format user story
- Acceptance criteria menggunakan Gherkin
- Label yang digunakan: Product Backlog, Sprint Backlog, Technical Debt
- Sprint/Milestone digunakan untuk mengelompokkan pekerjaan
````

## User Stories yang Bisa Langsung Dibuat di GitHub Issues

### 1. Create Product

**Title:** Create product record
**Labels:** Product Backlog, Sprint Backlog
**Story Points:** 3

**User Story**
As a admin
I need to create a new product
So that I can add items to the catalog

**Acceptance Criteria**

```gherkin
Given I am on the product management page
When I enter valid product details and click save
Then a new product record should be created successfully
```

---

### 2. View Product List

**Title:** View product list
**Labels:** Product Backlog, Sprint Backlog
**Story Points:** 2

**User Story**
As a admin
I need to view the product list
So that I can monitor all available products

**Acceptance Criteria**

```gherkin
Given product data already exists
When I open the product list page
Then I should see all saved products displayed in a list
```

---

### 3. Update Product

**Title:** Update product information
**Labels:** Product Backlog, Sprint Backlog
**Story Points:** 3

**User Story**
As a admin
I need to update product information
So that I can keep product data accurate

**Acceptance Criteria**

```gherkin
Given an existing product is displayed
When I edit the product details and click update
Then the product information should be saved with the new values
```

---

### 4. Delete Product

**Title:** Delete product record
**Labels:** Product Backlog, Sprint Backlog
**Story Points:** 2

**User Story**
As a admin
I need to delete a product
So that I can remove products that are no longer needed

**Acceptance Criteria**

```gherkin
Given an existing product is available in the list
When I choose delete for that product
Then the product should be removed from the system
```

---

### 5. Search Product

**Title:** Search product by name
**Labels:** Product Backlog, Sprint Backlog
**Story Points:** 2

**User Story**
As a admin
I need to search a product by name
So that I can find product data faster

**Acceptance Criteria**

```gherkin
Given multiple product records exist
When I enter a product name in the search field
Then matching products should be displayed
```

---

### 6. Technical Debt - Board Setup

**Title:** Improve issue workflow and board configuration
**Labels:** Technical Debt
**Story Points:** 1

**User Story**
As a developer
I need to improve the board workflow configuration
So that issue tracking is more consistent during sprint execution

**Acceptance Criteria**

```gherkin
Given the project board is already created
When I review the workflow settings
Then the issue status columns should match the sprint process
```

---

### 7. Technical Debt - Burndown Tracking

**Title:** Improve burndown data tracking
**Labels:** Technical Debt
**Story Points:** 1

**User Story**
As a developer
I need to maintain burndown tracking properly
So that sprint progress can be monitored clearly

**Acceptance Criteria**

```gherkin
Given a sprint milestone is active
When issues are estimated and assigned correctly
Then the burndown chart should reflect the sprint progress
```

## Sprint / Milestone

Gunakan milestone berikut:

**Sprint 1 - Product Management Features**

## Cara Set Up Board Kanban

Buat kolom berikut di GitHub Project:

* New
* Product Backlog
* Sprint Backlog
* In Progress
* Done

## Penempatan Issue

* Semua user story awalnya beri label **Product Backlog**
* Story yang masuk sprint tambahkan label **Sprint Backlog**
* Assign semua story sprint ke akun kamu
* Pindahkan story aktif ke **In Progress**
* Setelah selesai pindahkan ke **Done**
* Untuk requirement 9 dan 10, gunakan label **Technical Debt** pada dua issue terakhir
