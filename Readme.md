# RFs (Requisitos funcionais)
- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o numero de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter o seu historico de check-ins;
- [ ] Deve ser possível o usuário buscar academias proximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário
- [ ] Deve ser possível cadastrar academias

# RNs (Regras de negócio)
- O usuário não pode se cadastar com um email duplicado;
- O usuário não pode fazer mais de um check-in no mesmo dia;
- O usuário não pode fazer checkin se não tiver perto (100m) da academia;
- O check-in só pode ser validado até 20 minutos após ser criado;
- O check-in só pode ser validado por administradores;
- Academias só podem ser cadastradas por administradores;

# RNFs (Requisitos não funcionais)
- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);