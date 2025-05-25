
## 🚀 Módulo de Operadores em C# - Projeto de Estudo

### 👨‍💻 Desenvolvido por: Paulo Henrique Santana Motta

---

### 🧠 Sobre o projeto

Este repositório apresenta o **conteúdo prático** que desenvolvi durante um módulo de **3 horas** focado em **Operadores em C#**, parte dos meus estudos em desenvolvimento back-end.

> Aqui você encontrará exemplos de uso real com operadores lógicos (`&&`, `||`, `!`), condicionais (`if`, `else`, `switch`) e o controle de fluxo mais comum no dia a dia da programação em C#.

---

### 💡 Conceitos trabalhados



# M-dulo-de-Operadores-em-C---Projeto-de-Estudo
Módulo de Operadores em C# - Projeto de Estudo
```csharp
using System;

bool choveu = false;
bool estaTarde = false;

if (!choveu && !estaTarde)
{
  Console.WriteLine("Vou pedalar");
}
else
{
  Console.WriteLine("Vou pedalar outro dia");
}
```

```csharp
bool possuiPresencaMinima = true;
double media = 5.5;

if (possuiPresencaMinima && media >= 7)
{
  Console.WriteLine("Aprovado!");
}
else
{
  Console.WriteLine("Reprovado");
}
```

```csharp
bool ehMaiorDeIdade = false;
bool possuiAutorizacaoDoResponsavel = false;

if (ehMaiorDeIdade || possuiAutorizacaoDoResponsavel)
{
  Console.WriteLine("Entrada Liberada");
}
else
{
  Console.WriteLine("Entrada Não Liberada");
}
```

```csharp
Console.WriteLine("Digite uma letra");
string letra = Console.ReadLine();

switch (letra)
{
    case "a":
    case "e":
    case "i":
    case "o":
    case "u":
        Console.WriteLine("Vogal");
        break;
    default:
        Console.WriteLine("Não é uma Vogal");
        break;
}
```

---

### 📌 Observações
- Os exemplos são simples e diretos para facilitar o entendimento.
- Este projeto é voltado para iniciantes que estão começando com C#.
- Pode ser usado como base para exercícios e revisão de lógica de programação.

---

### 📚 Tecnologias utilizadas
- Linguagem: **C#**
- Plataforma: **.NET Console App**
- IDE: **Visual Studio / VS Code**

---

### 🌟 Contato e Redes

[![LinkedIn](https://img.shields.io/badge/-Paulo%20Henrique%20Santana%20Motta-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulo-henrique-santana-motta/)  
[![Gmail](https://img.shields.io/badge/-Contato%20por%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seuemail@gmail.com)

---

### ⭐ Dê uma estrela se este projeto te ajudou! 

> **"Estudar operadores é estudar a base da tomada de decisão em qualquer lógica. Um passo de cada vez, um operador por vez!"**
