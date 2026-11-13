# Store 1 | Customer Data Cleaning

**Customer Data Preparation | E-commerce Loyalty Program**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)

![Store 1 — Customer Data Cleaning](portada.png)

> Practice project developed during a Data Science training program.

**📓 [Open the notebook](notebooks/store1-customer-data-cleaning.ipynb)**

<details>
<summary>Resumen en español</summary>

<br>

**Store 1**, una tienda en línea, prepara un programa de fidelización y necesita datos de clientes confiables. Se escribió una función de limpieza que estandariza nombres, edades y categorías y se aplicó igual a todos los registros. Después se respondieron preguntas básicas de negocio: ingreso total, clientes menores de 30 años, clientes jóvenes con gasto alto y compradores por categoría.

**Aprendizaje clave:** un proceso de limpieza estandarizado en una sola función evita errores que aparecen cuando el mismo código se copia y se ajusta a mano para cada registro.

</details>

---

## 🌎 Business Context

Store 1 is an online store preparing to launch a customer loyalty program. To design personalized campaigns, the marketing team needs customer records that are consistent and reliable. The raw records had extra spaces, underscores, inconsistent capitalization, ages stored as decimals and uppercase categories.

---

## ⚙️ Approach

| Phase | What was done |
|---|---|
| **01 · Data Cleaning** | One reusable function, `clean_user()`, standardizes names, ages and categories and is applied to every record |
| **02 · Customer Analysis** | Total revenue, customers under 30, young high spenders, and a reusable filter by category |

---

## 📈 Key Findings

*Based on a practice sample of 10 customers.*

- **Total revenue recorded: 9,189.**
- **5 of 10 customers are under 30**, but only **2** of them spent more than 1,000. Age alone does not identify the most valuable young customers.
- **Clothes and home** each appear for 5 of the 10 customers, which makes them natural starting points for category campaigns.

**Limitation:** the sample is small and was created for practice, so the results describe this dataset only.

---

## 💡 Key Learnings

- **Standardize the process, not each case.** An earlier version copied the cleaning code by hand for each customer, and one copy missed a step without any visible error. A single function guarantees every record is processed the same way, the same principle as standardizing a process in industrial engineering.
- **Reusable functions scale.** The category filter answers a new question by changing one argument.

---

## 🛠️ Tools

Python (lists, loops, conditionals, functions, f-strings) · Jupyter Notebook

## 📁 Repository Structure

~~~text
store1-customer-analytics/
├── notebooks/
│   └── store1-customer-data-cleaning.ipynb
├── portada.png
└── README.md
~~~

---

## 🤝 Connect

**Abner Álvarez Cabrera** · Industrial Engineer |  Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abner-alvarez-cabrera-44a37b20b)
[![More projects](https://img.shields.io/badge/GitHub-More_projects-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbnerAC)
