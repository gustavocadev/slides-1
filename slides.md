---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Diapositivas de ejemplo
info: |
  ## Slidev Starter Template
  Presentation slides for developers. 

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

<p class="flex flex-col items-start">

<img src="https://www.astera.com/wp-content/uploads/2019/05/DBI-1.jpg" alt="Slidev" width="200" class="rounded-2xl" />

# Las bases de datos

### Participantes

- Juan
- María
- Pedro

</p>

---

# Tipos de bases de datos

- **Relacionales**
  - Aqui se incluyen las bases de datos SQL como MySQL, PostgreSQL, Oracle, etc.
- **No relacionales**
  - Aqui se incluyen las bases de datos NoSQL como MongoDB, Cassandra, etc.

## Logos de algunas bases de datos:

<br>

<img src="https://skillicons.dev/icons?i=mysql,postgres,mongo,dynamodb,redis&perline=15" />

---

# Ejemplo de código SQL

Consultado registros de una tabla:

````md magic-move
```sql
-- Esta consulta selecciona todos los campos de la tabla users, por ende es menos optima
SELECT * FROM users WHERE id = 1;
```

```sql
-- Esta consulta es mas optima porque solo selecciona los campos que necesitamos
SELECT
  id,
  name,
  email
FROM
  users
WHERE
  id = 2;
```
````

---

<p class="items-center justify-center flex w-full h-full">

# Gracias por su atención 🙌

</p>
