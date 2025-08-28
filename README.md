# ATIVIDADE-BEECROWD---FAMILIARIDADE-COM-SQL
## Nível 1

### 2603 - Endereço dos clientes
<img width="458" height="269" alt="image (3)" src="https://github.com/user-attachments/assets/59d4e3cc-cddd-41d5-818f-e8e4d065de69" />

``` sql
SELECT name, street
FROM customers
WHERE city = 'Porto Alegre';
```

### 2607 - Cidade em Ordem Alfabética
<img width="522" height="262" alt="image (4)" src="https://github.com/user-attachments/assets/24e704a3-64b9-4bbd-9543-f11fb9dd4a7f" />

```sql
SELECT DISTINCT city
FROM providers
ORDER BY city;
````

### 2608 - Maior e Menor Preço
<img width="439" height="249" alt="image (5)" src="https://github.com/user-attachments/assets/51cb7918-86ee-4156-a5a1-330433ce8cbb" />

```sql
SELECT MAX(price) AS price, MIN(price) AS price
FROM products
````

### 2615 - Expandindo o Negocio
<img width="457" height="243" alt="image (6)" src="https://github.com/user-attachments/assets/9afede47-aeb6-4942-9d1b-17c2027ebcc3" />

``` sql
SELECT city
FROM customers
```

### 2617 - Fornecedor Ajax SA
<img width="416" height="244" alt="image (7)" src="https://github.com/user-attachments/assets/d23152eb-b0f3-4d62-860c-b399a70d3aef" />

``` sql
SELECT p.name AS product, pr.name AS provider
FROM products p
JOIN providers pr ON p.id_providers = pr.id
WHERE pr.name = 'Ajax SA';
```

## Nível 4
### 2602 - Select Básico

<img width="426" height="256" alt="image (2)" src="https://github.com/user-attachments/assets/61cc0f7d-8e94-42e6-80f9-806a0c2db53c" />

``` sql
SELECT name
FROM customers
WHERE state = 'RS'
```
