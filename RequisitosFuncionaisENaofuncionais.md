## 6. Requisitos funcionais

Os requisitos funcionais descrevem as operações que o sistema deverá realizar.

- **RF01:** cadastrar, consultar, atualizar e desativar o cadastro de bombeiros.
- **RF02:** registrar a entrada e a saída dos bombeiros.
- **RF03:** consultar os bombeiros registrados como estando em serviço.
- **RF04:** cadastrar e organizar equipes.
- **RF05:** cadastrar turnos e escalas de serviço.
- **RF06:** registrar novas ocorrências de emergência.
- **RF07:** consultar e atualizar o status das ocorrências.
- **RF08:** designar equipes e viaturas para ocorrências, considerando a disponibilidade registrada.
- **RF09:** cadastrar e consultar viaturas e equipamentos.
- **RF10:** gerar relatórios de horários, escalas, ocorrências e utilização de recursos.
- **RF11:** manter histórico de alterações importantes nos registros.

## 7. Requisitos não funcionais

- **Segurança:** controlar o acesso às informações por meio de autenticação e permissões.
- **Integridade:** evitar registros duplicados e informações inconsistentes.
- **Disponibilidade:** buscar manter o sistema acessível durante as atividades administrativas.
- **Usabilidade:** apresentar telas simples e objetivas, facilitando a consulta das informações.
- **Rastreabilidade:** registrar quem realizou alterações importantes e quando elas aconteceram.
- **Proteção de dados:** limitar o acesso a informações pessoais e manter cópias de segurança.

## 8. Regras de negócio preliminares

1. Cada bombeiro deverá possuir uma matrícula única.
2. Um bombeiro não poderá registrar uma segunda entrada enquanto houver um turno em aberto, salvo procedimento autorizado para correção.
3. A saída deverá estar relacionada a um registro de entrada.
4. Uma ocorrência deverá possuir identificação própria e registrar sua situação atual.
5. Uma viatura em manutenção não deverá ser considerada disponível para designação.
6. Alterações em horários e ocorrências deverão ser rastreáveis.
7. A designação de equipes deverá respeitar as regras operacionais e a autorização dos responsáveis.
