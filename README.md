<h1 align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java Logo" width="50">
  <br>
  FIRMA — Sistema de Cadastro de Clientes
</h1>

<p align="center">
  <strong>Gerenciamento de Pessoas Físicas e Jurídicas com Orientação a Objetos em Java.</strong>
</p>

<hr>

## 🚀 Sobre o Projeto

O **FIRMA** é um sistema de cadastro de clientes desenvolvido em Java, com foco na aplicação prática dos pilares da **Orientação a Objetos**: abstração, herança e polimorfismo.

A estrutura do projeto utiliza uma classe abstrata `Pessoa` como base, estendida por `Pessoafisica` e `Pessoajuridica`, demonstrando reutilização de código e organização hierárquica de entidades do mundo real.

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=java,git" height="45" alt="Tech Stack" />
</p>

---

## 📂 Estrutura do Projeto

| Arquivo | Tipo | Responsabilidade |
|:--------|:-----|:-----------------|
| `Main` | Classe Principal | Menu interativo e fluxo da aplicação |
| `Pessoa` | Classe Abstrata | Atributos e comportamentos comuns (nome, telefone, e-mail) |
| `Pessoafisica` | Subclasse | Dados específicos: CPF e Data de Nascimento |
| `Pessoajuridica` | Subclasse | Dados específicos: CNPJ e Razão Social |

---

## 🧩 Conceitos Aplicados

- **Herança** — `Pessoafisica` e `Pessoajuridica` estendem `Pessoa`
- **Polimorfismo** — sobrescrita do método `exibirDados()` em cada subclasse
- **Abstração** — classe `Pessoa` define o contrato via método abstrato
- **Encapsulamento** — atributos privados acessados via getters e setters

---

## 👨‍💻 Autor

<p align="center">
  <img src="https://github.com/iggorhenri-tech.png" width="100px;" alt="Igor H." style="border-radius: 50%; border: 2px solid #5d2f8e;"/>
  <br />
  <sub><b>Igor H.</b></sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/igor-henrique-26b149218/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:iggorhenri@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>
