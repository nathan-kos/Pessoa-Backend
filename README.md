# Pessoa Back end

- [Sobre](#sobre)
- [Requisitos](#requisitos)
- [Modelagem](#modelagem)
- [Tecnologias](#tecnologias)
- [Autor](#autor)

---

## Sobre
Projeto de um sistema de cadastro de pessoas, tanto físicas quanto jurídicas, com o intuito de praticar e aprimorar meus conhecimentos em back end.

---

## Requisitos
### Requisitos Funcionais
- RF01 - Cadastro de clientes: O sistema deverá realizar cadastro de clientes
que sejam pessoa física ou jurídica.
- RF02 - Atualização de clientes: O sistema deve possibilitar a alteração de dados
cadastrais do cliente.
- RF03 - Inativação de clientes: O sistema deve possibilitar que clientes sejam
inativados.
- RF04 - Listagem de clientes: O sistema deve possibilitar que todos os clientes
sejam listados e que seja feito um filtro por documento(CPF/CNPJ).
- RF05 - Visualizar cliente: O sistema deve possibilitar a seleção de um cliente
para visualização de todos os seus dados.

### Requisitos Não Funcionais
- RNF01 - Banco de dados: O sistema deverá utilizar um banco de dados
PostgreSQL
- RNF02 - Auto completar: O sistema deverá auto completar os dados de endereço
do cliente após a entrada do CEP.
- RNF03 - Aplicação web: Deverá ser um sistema WEB.
- RNF04 - Back/Front: Deverá ser um sistema com back-end e um front-end
comunicando-se através de uma arquitetura REST.
- RNF05 - Garantia de funcionamento: Deverá ter testes de unidade em todas as
regras de negócio, garantindo assim o seu funcionamento de forma correta.

### Regras de Negócio
- RN01 - Dados obrigatórios para o cadastro de um cliente pessoa física: Para
todo cliente pessoa física é obrigatório o cadastro dos seguintes dados: nome, data
de nascimento,CPF, telefone, e-mail, gênero e endereço(logradouro, número,
complemento, bairro, cep, cidade e estado).
- RN02 - Dados obrigatórios para o cadastro de um cliente pessoa jurídica: Para
todo cliente pessoa jurídica é obrigatório o cadastro dos seguintes dados: nome
fantasia, razão social, CNPJ, telefone, e-mail e endereço(logradouro, número,
complemento, bairro, cep, cidade e estado).
- RN03 - Dados únicos para cliente: Não é permitido o cadastro de cliente com o
mesmo documento (CPF/CNPJ) ou e-mail já cadastrado.

---

## Modelagem
### Diagrama de Classes

### Modelo de Dados

---

## Tecnologias
- Java 19
- Spring Boot
- PostgreSQL
- JPA

---

## Autor
Feito por [Nathan Kosmalski]() 🚀
