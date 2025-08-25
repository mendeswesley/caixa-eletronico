# Caixa Eletrônico em C

Programa desenvolvido em **linguagem C** que simula as operações básicas de um caixa eletrônico, incluindo autenticação e manipulação de cédulas.

---

## 🚀 Funcionalidades
- Definição de saldo inicial
- Saque de valores
- Cálculo automático das cédulas necessárias
- Validação de entradas inválidas (valores negativos, notas inexistentes como R$1 e R$3, etc.)
- Tratamento para valores incompatíveis com as cédulas disponíveis
- Possibilidade de realizar múltiplos saques até o saldo acabar

---

## 🛠 Tecnologias Utilizadas
- **C**
- **Compilador GCC**

---

## ▶️ Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/mendeswesley/caixa-eletronico.git
   ```
2. Entre na pasta do projeto:
   ```bash
   cd caixa-eletronico
   ```
3. Compile o programa:
   ```bash
   gcc src/caixa.c -o caixa
   ```
4. Execute:
   ```bash
   ./caixa
   ```

---

## 💻 Exemplo de execução
```
Seja bem vindo(a) a nossa agência!
----------------------------------
Digite o seu saldo: 200

Quanto você quer sacar?: 87
Você recebeu 1 nota de R$50.
Você recebeu 1 nota de R$20.
Você recebeu 1 nota de R$10.
Você recebeu 1 nota de R$5.
Você recebeu 1 nota de R$2.

Saldo restante: R$113.
```

---

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE.md).

---

## 👨‍💻 Autor
Desenvolvido por [Wesley Mendes](https://github.com/mendeswesley).
