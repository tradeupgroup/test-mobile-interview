## Teste de Conhecimentos

Será analisado os seguintes items:

- Domínio sobre React-Native
- Capacidade de resolver problemas.
- Capacidade de fazer códigos reutilizável.
- O teste deve ser feito em 24 horas.

#### Pré Requisitos

Para simular um backend, utilize o módulo [JSON-Server](https://github.com/typicode/json-server), utilize o seguinte db.json

```json
{
  "contacts": [
    {
      "id": "1",
      "company": "Nome da Companhia 1",
      "name": "Nome Completo 1",
      "email": "email1@gmail.com",
      "role": "Diretor",
      "phone": "(11)98765-4321",
      "contactAdmin": true
    },
    {
      "id": "2",
      "company": "Nome da Companhia 2",
      "name": "Nome Completo 2",
      "email": "email2@gmail.com",
      "role": "Administrador",
      "phone": "(22)98765-4322",
      "contactAdmin": false
    },
    {
      "id": "3",
      "company": "Nome da Companhia 3",
      "name": "Nome Completo 3",
      "email": "email3@gmail.com",inter
      "role": "Diretor",
      "phone": "(33)98765-4323",
      "contactAdmin": false
    }
  ]
}
```

## Tarefas

- [ ] Deve ser criado um arquivo readme.md e colocado junto ao projeto, deve contar instruções de como compilar o aplicativo para rodar no simulado ou emulador.
- [ ] Deve ser criado uma tela inicial com um botão, que quando pressionado deve navegar para a página de contatos.
- [ ] A página de contatos deve apresentar uma lista com os nomes e cargos dos contatos.
- [ ] Ao clicar em um contato deve ser possível ver todos os dados do contato.
- [ ] Deve ser possível criar, editar, deletar um contato
- [ ] Você pode criar uma maneira de filtrar contatos, sendo possível procurar por nome, email, telefone.
- [ ] Você pode validar os campos de entrada e exibir uma mensagem sobre o motivo pelo qual não passou na validação.
- [ ] Você pode escrever testes unitários.

#### Design

O design pode ser o que você quiser, mas se precisar de ajuda pode levar como base o [Figma](https://www.figma.com/file/T23c41H49ci28oIuuQs83M/Contatos?node-id=3383%3A20363)

**OBS:** De preferência para as funcionalidades

## Diferenciais

- [ ] Typescript
- [ ] Context, Redux, Redux-Thunk ou Redux-Saga
- [ ] Hooks e Hooks Personalizados
- [ ] Tratamento de possíveis erros de API Rest (401, 404, 500)
