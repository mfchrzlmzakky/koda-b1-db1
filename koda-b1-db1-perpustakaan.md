```mermaid
erDiagram

BUKU ||--o{ KATEGORI : mempunyai
BUKU {
  int id PK
  string name
  int category_id FK
  int bookshelf_id FK
}

KATEGORI {
 int id PK
 string name
}

```
