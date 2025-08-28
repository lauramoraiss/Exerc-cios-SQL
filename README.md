# Exerc-cios-SQL

°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡°‧ 𓆝 𓆟 𓆞 ·｡

### **⟩<^,«⋗ *ATIVIDADES NÍVEL 1***

- Atividade 2603 → Nível 1
  
  SELECT
	name,
	street
FROM
	customers
WHERE
	city LIKE '%Porto Alegre%';

<img width="1077" height="586" alt="Image" src="https://github.com/user-attachments/assets/8780101e-c81f-4ff6-82d3-ebfddca60907" />


- Atividade 2607 → Nível 1

  SELECT
	city
FROM
	providers
ORDER BY
	city ASC;

<img width="1085" height="530" alt="Image" src="https://github.com/user-attachments/assets/1d740b8e-ea5d-4778-8ee3-3c6818dbf87b" />


- Atividade 2608 → Nível 1

  SELECT
	max(price)
	min(price)
FROM
	products;

<img width="1079" height="509" alt="Image" src="https://github.com/user-attachments/assets/ec4781eb-f43b-4a01-bfef-40c73d1c8bdf" />


- Atividade 2615 → Nível 1

  SELECT
	city
FROM
	customers;

<img width="1084" height="509" alt="Image" src="https://github.com/user-attachments/assets/9439c9c5-5b58-4a09-afa6-396ee6011610" />


- Atividade 2617 → Nível 1

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

- Atividade 2604 → Nível 2

  SELECT
	id,
	name
FROM
	products
WHERE
	price < 10 OR price > 100;

