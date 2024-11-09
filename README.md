# Stack

## Building medium in the following stack

- Proyek ini bertujuan untuk membangun platform seperti Medium dengan React di frontend dan Cloudflare Workers di backend, menawarkan performa tinggi dan pengelolaan API di edge. TypeScript digunakan di seluruh kode untuk meningkatkan konsistensi tipe, dan Zod menyediakan validasi skema serta inferensi tipe antara frontend dan backend. Prisma sebagai ORM terhubung ke Postgres dengan connection pooling untuk efisiensi database, sementara JWT menyediakan sistem autentikasi yang aman. Kombinasi ini memastikan aplikasi yang scalable, type-safe, dan efisien di seluruh arsitektur.

- React in the frontend
- Cloudflare workers in the backend
- Zod as the validation library, type inference for the frontend types (schema untuk be, type untuk fe)
- Typescript as the language
- Prisma as the ORM, with connection pooling
- Postgres as the database
- JWT for authentication
