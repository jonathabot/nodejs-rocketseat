npm run knex -- migrate:make create-documents
npm run knex -- migrate:latest
npm run knex -- migrate:rollback
npm run knex -- migrate:make add-session-id-to-transactions
npm run knex -- migrate:latest
npm install
npm run dev

# RF

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação unica;

# RN

- [x] A transação pode ser do tipo crédio que somará ao valor total, ou débito subtrairá;
- [ ] Deve ser possível identificarmos o usuário entre as requisições;
- [ ] O usuário só pode visualizar transações o qual ele criou;
