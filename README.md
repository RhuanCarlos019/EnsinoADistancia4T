# Documentação do Projeto: Plataforma de Cursos Online

## Escopo
Desenvolver uma plataforma de cursos online que permita aos professores criar cursos e gerenciar o conteúdo, e aos alunos matricularem-se, assistirem às aulas e realizarem atividades.

## Objetivos SMART

1. **Específico (Specific):**
   - Criar uma plataforma que permita a criação, gerenciamento e inscrição de cursos.
   - Implementar sistemas de autenticação e autorização para professores e alunos.

2. **Mensurável (Measurable):**
   - A plataforma deve suportar, no mínimo, 100 professores e 1.000 alunos.
   - Cada curso deve poder conter até 50 módulos de conteúdo e atividades.

3. **Atingível (Achievable):**
   - Utilizar o framework Laravel e PostgreSQL para garantir uma solução escalável.
   - Garantir que a plataforma seja desenvolvida e testada dentro do prazo de 6 meses.

4. **Relevante (Relevant):**
   - Atender à demanda crescente por educação online, oferecendo uma solução robusta e de fácil uso.

5. **Temporal (Time-bound):**
   - Completar o desenvolvimento e a implementação da plataforma em 6 meses, com marcos mensais para revisão e ajustes.

## Cronograma de 6 Meses

| Mês  | Atividade                                                   |
|------|--------------------------------------------------------------|
| 1    | **Análise de Requisitos e Planejamento:** <br> - Definição do escopo detalhado <br> - Reunião inicial com a equipe <br> - Estruturação das funções principais |
| 2    | **Desenvolvimento Inicial:** <br> - Configuração do ambiente de desenvolvimento <br> - Implementação inicial do CRUD de cursos <br> - Configuração do banco de dados e migrations |
| 3    | **Autenticação e Autorização:** <br> - Implementação do sistema de autenticação para professores e alunos <br> - Testes iniciais de autenticação <br> - Integração com o sistema de cursos |
| 4    | **Gerenciamento de Cursos:** <br> - Desenvolvimento de funcionalidades para criação e gestão de cursos <br> - Implementação da inscrição de alunos nos cursos <br> - Testes de usabilidade das interfaces de curso |
| 5    | **Testes e Otimização:** <br> - Testes de integração e unidade <br> - Otimização do desempenho da plataforma <br> - Ajustes de UI/UX conforme feedback dos testes |
| 6    | **Documentação e Entrega:** <br> - Finalização da documentação do projeto <br> - Preparação e execução da entrega final <br> - Treinamento da equipe de suporte e manutenção |

## Recursos

### 1. **Tecnologia:**
   - **Framework:** Laravel
   - **Banco de Dados:** PostgreSQL
   - **Ambiente de Desenvolvimento:** Visual Studio Code
   - **Servidores:** Servidor web para deployment, preferencialmente com suporte a PHP e banco de dados PostgreSQL

### 2. **Recursos Humanos:**
   - **Gerente de Projeto:** Responsável pela coordenação do projeto, comunicação entre a equipe e stakeholders, e controle do cronograma.
   - **Desenvolvedores Back-end (2):** Especializados em Laravel, para desenvolver a lógica do servidor e a conexão com o banco de dados.
   - **Desenvolvedores Front-end (2):** Responsáveis pelo design e implementação da interface do usuário.
   - **Engenheiro de DevOps:** Cuida da integração contínua, deployment e monitoramento do ambiente de produção.
   - **Designer de UI/UX:** Desenvolve o layout e a experiência do usuário.
   - **Tester/QA:** Conduz testes de unidade, integração e usabilidade, garantindo a qualidade do software.
   - **Suporte Técnico:** Oferece suporte pós-lançamento e manutenção da plataforma.

## Análise de Riscos

1. **Problemas com a Disponibilização de Conteúdos:**
   - Mitigação: Implementação de um sistema robusto de upload e gerenciamento de arquivos, com suporte a diferentes formatos de mídia.

2. **Desafios na Implementação da Interface de Usuário:**
   - Mitigação: Colaboração constante entre os desenvolvedores e o designer de UI/UX, com testes de usabilidade em cada fase do desenvolvimento.

3. **Segurança de Dados e Controle de Acesso:**
   - Mitigação: Implementação de autenticação baseada em tokens e criptografia de dados sensíveis, além de testes de penetração regulares.

## Diagramas

### 1. **Diagrama de Classe:**
   - **Entidades:** Cursos, Professores, Alunos

### 2. **Diagrama de Caso de Uso:**
   - **Cenários:** 
     - Professor gerencia cursos
     - Aluno acessa conteúdo e se inscreve em cursos

### 3. **Diagrama de Fluxo:**
   - **Processo:** 
     - Login → Dashboard do Curso → Gestão de Atividades → Avaliações → Logout
