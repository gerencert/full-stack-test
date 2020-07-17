# Teste Desenvolvedor Full Stack

Esse é um teste para que possamos avaliar algumas de suas habilidades e conhecimentos.
Não necessáriamente é preciso terminar a atividade por completo, caso não consiga terminar todo o teste, iremos levar em consideração o que foi feito. Vamos avaliar a lógica, organização do projeto e qualidade de código.

# Sobre Nós
Somos uma startup que chegou para inovar! Mudamos a forma que as empresas de autoridade de registro gerenciam certificado digital.

- [x] Contrato PJ
- [x] Home Office (Trabalhe anywhere, anytime)
- [x] Salário, a combinar
- [x] Participação nos lucros e resultados

# Proposta
Desenvolver uma aplicação simples para controle de clientes.

## Back-end
Desenvolva uma API seguindo o padrão RESTFul contendo rotas para:
- Consultar clientes
- Cadastrar novo cliente
- Consultar cliente por ID
- Editar cliente por ID
- Remover cliente

Os dados devem ser armazenados em uma base dados Mongodb.

## Frond-end
Desenvolva uma interface contendo um botão para cadastro de novo cliente, e uma listagem dos clientes cadastrados.
O botão novo, deve direcionar o usuário para uma nova tela contendo um formulário com os seguintes campos:

<table>
  <tr>
    <th>Field</th>  
    <th>Type</th>  
  </tr>
  <tr>
    <td>fullName</td>  
    <td>String</td>  
  </tr>
  <tr>
    <td>cpf</td>  
    <td>String</td>  
  </tr>
  <tr>
    <td>birthday</td>  
    <td>Date</td>  
  </tr>
  <tr>
    <td>contact.phone</td>  
    <td>String</td>  
  </tr>
  <tr>
    <td>contact.email</td>  
    <td>String</td>  
  </tr>
  <tr>
    <td>status</td>  
    <td>boolean</td>  
  </tr>
</table>

Na tela de listagem de clientes, o usuário deve conseguir clicar em algum cliente da lista, para poder editar, a mesma ação deve direcionar o usuário para uma tela com o mesmo formulário de cadastro, porém com as informações já preenchidas.
A tela deve possibilitar que o usuário altere alguma informação e salve.
A tela também deve conter um botão para remover o cliente.

# Requisitos

* Angular 1.6
* Node
* HapiJS ou Koa2
* Mongodb
* Git

# Diferenciais

* Docker
* Testes automatizados

# Conclusão

Encaminhe um email com o link de acesso ao projeto, lembre-se de subir em um repositório de código fonte publico, para que possamos ter acesso e avaliar seu teste.
Também no email, conte um pouco sobre você e seus objetivos ;)

Encaminhar email para: robson.costa@gerencert.com.br

** Todos os candidatos seram respondidos, então não se preocupe.
