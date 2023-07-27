# XHealth Gym App

Bem-vindo ao aplicativo da Academia XHealth, uma plataforma projetada para exibir e fornecer
informações sobre nossa diversa gama de modalidades e serviços de fitness.

## Requisitos Funcionais (RFs)

- [ ] Registro de Usuário: Os usuários devem poder criar uma conta na plataforma.
- [ ] Autenticação de Usuário: Os usuários devem poder fazer login com segurança.
- [ ] Perfil do Usuário: Uma vez logados, os usuários podem visualizar e gerenciar seus perfis.
- [ ] Histórico de Check-in: Os usuários podem acessar o histórico de check-ins.
- [ ] Academias Próximas: Os usuários podem procurar por academias próximas.
- [ ] Busca de Academias por Nome: Os usuários podem pesquisar academias pelo nome.
- [ ] Check-in na Academia: Os usuários podem fazer check-in em uma academia.
- [ ] Registro de Academia: Administradores podem registrar novas academias.

## Regras de Negócio (RNs)

- [ ] Email Único: Os usuários não podem se registrar com um endereço de email duplicado.
- [ ] Validação Oportuna: Os check-ins só podem ser validados dentro de 20 minutos após a criação.
- [ ] Registro de Academia: Apenas administradores podem registrar novas academias.

## Requisitos Não Funcionais (RNFs)

- [ ] Armazenamento Seguro de Senhas: As senhas dos usuários devem ser criptografadas para maior segurança.
- [ ] Persistência de Banco de Dados: Os dados do aplicativo serão armazenados e gerenciados em um banco de dados PostgreSQL.
- [ ] Paginação: Todas as listas de dados serão paginadas, exibindo 20 itens por página.
- [ ] Autenticação JWT: Os usuários serão identificados e autenticados usando JSON Web Tokens.

## Tema: Projeto para Academia XHealth

🏋️‍♂️ **Requisitos do Cliente:**

Nossa academia, Academia XHealth, oferece uma ampla variedade de modalidades de fitness,
incluindo musculação, esportes de combate, dança, treinamento HIIT, ciclismo indoor,
treinamento funcional e muito mais.

O cliente busca uma página atraente que exiba todas as modalidades e serviços disponíveis
para clientes em potencial.

A página deve apresentar depoimentos de ex-alunos que alcançaram resultados positivos em nossa academia. 
Além disso, queremos destacar nossos instrutores profissionais, que são atletas reconhecidos e especialistas na área.

Outros serviços que oferecemos incluem:

- Avaliação física personalizada com medições de bioimpedância.
- Fisioterapia para tratamento e prevenção de lesões.
- Sessões de treinamento personalizado.

Esses serviços podem ser contratados separadamente e não estão inclusos na mensalidade.

A página deve permitir que clientes em potencial enviem perguntas para esclarecimentos,
e os alunos atuais devem poder acessar informações de suas contas e visualizar detalhes de seus treinos.

Nossas cores principais são **Preto e Amarelo**, e queremos que a página siga esse esquema de cores.
O design deve ser moderno, elegante e refletir a alta qualidade dos serviços que oferecemos.
Todos os nossos equipamentos são novos e nossos instrutores são profissionais altamente conceituados,
que guiam os alunos em sua jornada de fitness.

🎖️ **Requisito Adicional:**

Incorporar um dos exercícios do curso ao projeto. Você tem a liberdade de escolher qualquer exercício
de qualquer módulo e integrá-lo criativamente ao projeto do cliente.