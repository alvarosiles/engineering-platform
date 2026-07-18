# Schemas

Definición de esquemas de base de datos.

## Ejemplo: tabla `users`

```sql
CREATE TABLE users (
  id UUID PRIMARY KEY DEFAULT gen_random_uuid(),
  name VARCHAR(150) NOT NULL,
  email VARCHAR(150) UNIQUE NOT NULL,
  password_hash TEXT NOT NULL,
  created_at TIMESTAMP DEFAULT now()
);
```

> Placeholder de ejemplo. Los esquemas reales se agregarán conforme evolucione el modelo de datos.
