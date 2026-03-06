# DESAFIO QA - BEEDOO 2026

Este repositório contém a análise e os testes realizados na aplicação disponibilizada para o desafio técnico de Quality Assurance (QA).

---

# 1. Objetivo da aplicação

A aplicação tem como objetivo permitir o gerenciamento de cursos através de um sistema de CRUD (Create, Read, Update e Delete).

Com ela, o usuário pode:

- Criar novos cursos
- Visualizar os cursos cadastrados
- Gerenciar informações relacionadas aos cursos

---

# 2. Exploração da aplicação

Durante a exploração da aplicação, foi possível identificar dois fluxos principais.

## 2.1 Cadastro de curso

Fluxo responsável por registrar um novo curso no sistema.

Passos identificados:

- Acessar a tela de cadastro
- Preencher os campos do formulário:
  - Nome do curso
  - Descrição
  - Instrutor
  - Capa do curso
  - Data de início
  - Data de fim
  - Número de vagas
  - Tipo de curso
- Enviar o formulário

---

## 2.2 Listagem de cursos

Tela responsável por exibir os cursos cadastrados no sistema.

Funcionalidades observadas:

- Visualizar a lista de cursos
- Conferir os dados cadastrados
- Ver cursos adicionados recentemente

---

# 3. Pontos críticos para teste

Os principais pontos críticos identificados no sistema são:

### Validação de campos do formulário

Garantir que os campos obrigatórios sejam preenchidos corretamente e que o sistema impeça dados inválidos, como campos vazios, apenas espaços ou valores fora do padrão esperado.

### Fluxo principal de cadastro de cursos

Verificar se o fluxo principal da aplicação funciona corretamente: preencher o formulário, cadastrar o curso e visualizar o curso na listagem.

### Persistência dos dados cadastrados

Garantir que os cursos cadastrados permaneçam disponíveis mesmo após atualização da página ou navegação entre telas.

### Integridade dos dados (prevenção de duplicidade)

Verificar se o sistema impede ou trata corretamente o cadastro de cursos duplicados, garantindo consistência nas informações exibidas.

### Funcionamento correto da listagem

Confirmar que todos os cursos cadastrados aparecem corretamente na lista e que as informações exibidas estão consistentes.

### Comportamento do sistema em cenários inesperados

Testar situações fora do fluxo normal, como múltiplos cliques no botão de cadastro, atualização da página durante o processo ou envio repetido do formulário.

### Feedback e experiência do usuário

Avaliar se o sistema apresenta mensagens claras de sucesso ou erro após as ações do usuário, garantindo uma boa experiência de uso.
