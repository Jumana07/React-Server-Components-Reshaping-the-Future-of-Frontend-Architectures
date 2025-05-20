# React-Server-Components-Reshaping-the-Future-of-Frontend-Architectures
# React Server Components: White Paper Dataset

This repository contains the supporting data used in the white paper titled:

**"React Server Components: Reshaping the Future of Frontend Architectures"**  
Author: Jumana Haseen M  
Date: May 2025

The datasets shared here include benchmarking metrics, case study performance improvements, and mock data used in the example implementation.

---

## 📁 Files Included

### 1. `performance_metrics.csv`

This file contains the results of a performance comparison between a traditional React Single Page Application (CSR) and a Next.js 14 application using React Server Components (RSC).

| Metric | React SPA (CSR) | Next.js RSC |
|--------|------------------|-------------|
| JS Bundle Size (KB) | 812 | 301 |
| First Contentful Paint (s) | 2.8 | 1.2 |
| Time to Interactive (s) | 3.4 | 1.5 |
| Lighthouse Score | 74 | 96 |

---

### 2. `case_study_results.csv`

This dataset includes the performance and business metrics from a case study involving the migration of an e-commerce site to a Next.js RSC architecture.

| Metric | Before Migration | After Migration |
|--------|------------------|-----------------|
| Bounce Rate (%) | 49 | 29 |
| Pagespeed Score | 68 | 94 |
| Conversion Rate (%) | - | 8 |
| Core Web Vitals Pass Rate (%) | - | 98 |

---

### 3. `products.json`

This file contains a mock product list used in the server component code example. It simulates data fetched by a Server Component in a Next.js app.

```json
[
  {
    "id": 1,
    "name": "Wireless Headphones",
    "category": "electronics",
    "price": 129.99
  },
  {
    "id": 2,
    "name": "Smart Watch",
    "category": "electronics",
    "price": 199.99
  }
]

