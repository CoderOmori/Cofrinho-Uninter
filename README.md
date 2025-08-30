## 📂 Estrutura de Arquivos

# 💰 Projeto Cofrinho em Java

Este projeto implementa um **Cofrinho virtual** em Java, utilizando os conceitos de **Programação Orientada a Objetos (POO)**:  
**Herança, Polimorfismo, Encapsulamento e Abstração**.  

---

## 🚀 Funcionalidades
O programa permite ao usuário:

- ✅ **Adicionar moedas** de diferentes valores e países (Real, Dólar, Euro)  
- ✅ **Remover moedas específicas** do cofrinho  
- ✅ **Listar todas as moedas** armazenadas  
- ✅ **Calcular o total convertido para Reais (R$)**  

---

## 📂 Estrutura de Arquivos


- `Moeda.java` → classe abstrata base  
- `Real.java`, `Dolar.java`, `Euro.java` → subclasses que herdam de `Moeda`  
- `Cofrinho.java` → gerencia a lista de moedas  
- `Principal.java` → contém o menu interativo e o método `main`

---

## 🛠️ Conceitos de POO Aplicados

- **Herança** → `Real`, `Dolar` e `Euro` **herdam** de `Moeda`.  
- **Polimorfismo** → métodos `info()` e `converterParaReal()` são sobrescritos e chamados dinamicamente.  
- **Encapsulamento** → atributos protegidos/privados com acesso via métodos.  
- **Abstração** → a classe `Moeda` é **abstrata**, não pode ser instanciada diretamente.  

---

## ▶️ Como Compilar e Executar

1. **Abrir um terminal** na pasta do projeto.  
2. **Compilar todos os arquivos Java**:
   ```sh
   javac *.java

