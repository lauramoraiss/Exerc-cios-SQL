# Exerc-cios-SQL

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADES NÍVEL 1***

#### - Atividade 2603 → Nível 1
  
  SELECT
	name,
	street
FROM
	customers
WHERE
	city LIKE '%Porto Alegre%';

<img width="1077" height="586" alt="Image" src="https://github.com/user-attachments/assets/8780101e-c81f-4ff6-82d3-ebfddca60907" />


### - Atividade 2607 → Nível 1

  SELECT
	city
FROM
	providers
ORDER BY
	city ASC;

<img width="1085" height="530" alt="Image" src="https://github.com/user-attachments/assets/1d740b8e-ea5d-4778-8ee3-3c6818dbf87b" />


### - Atividade 2608 → Nível 1

  SELECT
	max(price)
	min(price)
FROM
	products;

<img width="1079" height="509" alt="Image" src="https://github.com/user-attachments/assets/ec4781eb-f43b-4a01-bfef-40c73d1c8bdf" />


### - Atividade 2615 → Nível 1

  SELECT
	city
FROM
	customers;

<img width="1084" height="509" alt="Image" src="https://github.com/user-attachments/assets/9439c9c5-5b58-4a09-afa6-396ee6011610" />


### - Atividade 2617 → Nível 1

  SELECT
	products.name,
	providers.name
FROM
	providers
INNER JOIN
	prducts ON products.id_providers = providers.id
WHERE
	providers.name = 'Ajax SA';

<img width="1077" height="603" alt="Image" src="https://github.com/user-attachments/assets/de6c5acc-bc38-48a3-80e8-f38bb7659198" />

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADES NÍVEL 2***

### - Atividade 2604 → Nível 2

  SELECT
	id,
	name
FROM
	products
WHERE
	price < 10 OR price > 100;

<img width="1087" height="576" alt="Image" src="https://github.com/user-attachments/assets/33543059-d691-4115-952b-0da4fb34b6ce" />


### - Atividade 2613 → Nível 2

  SELECT
	movies.id,
	movies.name
FROM
	movies
INNER JOIN
	prices ON movies.id_prices = prices.id
WHERE
	value < 2;

<img width="1082" height="647" alt="Image" src="https://github.com/user-attachments/assets/f6242655-94f6-4715-a7be-ba71cef8b793" />

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADES NÍVEL 3***

### - Atividade 2610 → Nível 3

SELECT
	ROUND(AVG(price), 2) as price
FROM
	products;

 <img width="1087" height="503" alt="Image" src="https://github.com/user-attachments/assets/bd156b51-b3ae-408b-a297-436e9c9a3ca1" />


### - Atividade 2618 → Nível 3

SELECT
	products.name AS name,
	providers.name AS name,
	categories.name AS name
FROM
	products
INNER JOIN
    providers ON products.id_providers = providers.id
    
INNER JOIN
    categories ON products.id_categories = categories.id
WHERE
    providers.name = 'Sansul SA'
    AND categories.name = 'Imported';

<img width="1082" height="741" alt="Image" src="https://github.com/user-attachments/assets/ee76b457-4541-4b78-a322-b9e100804832" />

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADE NÍVEL 4***

### - Atividade 2602 → Nível 4

SELECT
    name
FROM
    customers
WHERE
    state LIKE '%RS%';

<img width="1079" height="546" alt="Image" src="https://github.com/user-attachments/assets/faea5084-4ef2-44e2-b652-2cd0f7dfa065" />

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADE NÍVEL 5***

### - Atividade 2616 → Nível 5

SELECT
    customers.id,
    customers.name
FROM
    customers
LEFT JOIN
    locations ON customers.id = locations.id_customers
WHERE
    locations.id_customers IS NULL
