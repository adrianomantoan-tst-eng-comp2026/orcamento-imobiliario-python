# 🧾 Sistema de Orçamento Imobiliário em Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Status-Concluído-success">
  <img src="https://img.shields.io/badge/Projeto-Acadêmico-orange">
  <img src="https://img.shields.io/badge/POO-Aplicado-blueviolet">
</p>

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina **Algorithmic Thinking & Introduction to Object-Oriented Programming (UniFECAF)**.

O sistema simula o cálculo de aluguel de imóveis com base em regras de negócio e gera um **orçamento completo em formato CSV**, aplicando conceitos de **programação orientada a objetos (POO)**.

---

## 🎯 Objetivo

Aplicar lógica de programação e POO na construção de um sistema real, envolvendo:

- Tomada de decisão
- Estrutura condicional
- Modelagem de classes
- Geração de dados estruturados (CSV)

---

## ⚙️ Funcionalidades

✔ Escolha do tipo de imóvel  
✔ Cálculo automático do aluguel  
✔ Aplicação de regras de negócio  
✔ Parcelamento da taxa de contrato  
✔ Geração de planilha CSV com 12 meses  

---

## 🧠 Regras de Negócio

### 🏢 Apartamento
- Base: R$ 700  
- + R$ 200 → 2 quartos  
- + R$ 300 → vaga  
- -5% → sem crianças  

### 🏠 Casa
- Base: R$ 900  
- + R$ 250 → 2 quartos  
- + R$ 300 → vaga  

### 🏙️ Estúdio
- Base: R$ 1.200  
- + R$ 250 → até 2 vagas  
- + R$ 60 por vaga extra  

### 📑 Taxa de Contrato
- Valor fixo: R$ 2.000  
- Parcelamento: até 5x  

---

## 🧩 Tecnologias Utilizadas

- Python 3
- Programação Orientada a Objetos
- Manipulação de arquivos CSV

---

## ▶️ Como Executar

```bash
python main.py