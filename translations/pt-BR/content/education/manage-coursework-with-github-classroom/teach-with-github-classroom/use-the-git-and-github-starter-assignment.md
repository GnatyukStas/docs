---
title: Use a atividade do Git e GitHub starter
intro: 'Você pode usar a atividade inicial do Git & {% data variables.product.company_short %} para dar aos alunos uma visão geral do Git e dos princípios básicos do {% data variables.product.company_short %}.'
versions:
  fpt: '*'
permissions: 'Organization owners who are admins for a classroom can use Git & {% data variables.product.company_short %} starter assignments. {% data reusables.classroom.classroom-admins-link %}'
redirect_from:
  - /education/manage-coursework-with-github-classroom/use-the-git-and-github-starter-assignment
shortTitle: Atribuição inicial
---

A atividade inicial do Git & {% data variables.product.company_short %} é um curso pré-fabricado que resume os conceitos básicos do Git e {% data variables.product.company_short %} e vincula os alunos a recursos para aprender mais sobre tópicos específicos.

## Pré-requisitos

{% data reusables.classroom.assignments-classroom-prerequisite %}

## Criando a atividade inicial

### Se não houver recomendações na sala de aula

1. Efetue o login em {% data variables.product.prodname_classroom_with_url %}.
2. Acesse uma sala de aula.
3. Na aba {% octicon "repo" aria-label="The repo icon" %} **Atividades**, clique em **Usar a atividade inicial**.

<div class="procedural-image-wrapper">
  <img alt="Criando sua primeira atividade" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignments-create-first-assignment.png">
</div>

### Se já existirem recomendações na sala de aula

1. Efetue o login em {% data variables.product.prodname_classroom_with_url %}.
2. Acesse uma sala de aula.
3. Na aba {% octicon "repo" aria-label="The repo icon" %} **Atividades**, clique no link do banner azul.

<div class="procedural-image-wrapper">
  <img alt="Botão &quot;Nova atividade&quot;" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignments-click-new-starter-assignment-button.png">
</div>

## Configurar os fundamentos para uma atividade

Importe o curso introdutório para a sua organização, nomeie sua atividade, decida se deseja atribuir um prazo e escolha a visibilidade dos repositórios de tarefas.

- [Pré-requisitos](#prerequisites)
- [Criando a atividade inicial](#creating-the-starter-assignment)
  - [Se não houver recomendações na sala de aula](#if-there-are-no-existing-assignments-in-the-classroom)
  - [Se já existirem recomendações na sala de aula](#if-there-already-are-existing-assignments-in-the-classroom)
- [Configurar os fundamentos para uma atividade](#setting-up-the-basics-for-an-assignment)
  - [Importando a tarefa](#importing-the-assignment)
  - [Nomeando a atividade](#naming-the-assignment)
  - [Atribuir um prazo para uma atividade](#assigning-a-deadline-for-an-assignment)
  - [Escolher uma visibilidade para repositórios de atividades](#choosing-a-visibility-for-assignment-repositories)
- [Convidar alunos para uma atividade](#inviting-students-to-an-assignment)
- [Próximas etapas](#next-steps)
- [Leia mais](#further-reading)

### Importando a tarefa

Primeiro, você precisa importar a atividade inicial do Git & {% data variables.product.product_name %} para a sua organização.

<div class="procedural-image-wrapper">
  <img alt="O botão &quot;Importar a atividade&quot;" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignments-import-starter-assignment.png">
</div>

### Nomeando a atividade

Para uma atividade individual, {% data variables.product.prodname_classroom %} nomeia os repositórios pelo prefixo do repositório e pelo nome de usuário de {% data variables.product.product_name %} do aluno. Por padrão, o prefixo do repositório é o título da atividade. Por exemplo, se você nomear uma atividade como "assignment-1" e o nome de usuário do aluno em {% data variables.product.product_name %} for @octocat, o nome do repositório de atividade para @octocat será `assignment-1-octocat`.

{% data reusables.classroom.assignments-type-a-title %}

### Atribuir um prazo para uma atividade

{% data reusables.classroom.assignments-guide-assign-a-deadline %}

### Escolher uma visibilidade para repositórios de atividades

Os repositórios de uma atividade podem ser públicos ou privados. Se você usar repositórios privados, apenas o aluno poderá ver o feedback que você fornecer. Em "Visibilidade do repositório" selecione uma visibilidade.

Ao terminar, clique em **Continuar**. {% data variables.product.prodname_classroom %} criará a atividade e direcionará você para a página da atividade.

<div class="procedural-image-wrapper">
  <img alt="Botão &quot;Continuar&quot;" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignments-click-continue-button.png">
</div>

## Convidar alunos para uma atividade

{% data reusables.classroom.assignments-guide-invite-students-to-assignment %}

Você pode ver se um aluno juntou-se à sala de aula e aceitou ou enviou uma atividade na aba **Todos os alunos** da atividade. {% data reusables.classroom.assignments-to-prevent-submission %}

<div class="procedural-image-wrapper">
  <img alt="Atividade individual" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignment-individual-hero.png">
</div>

A atividade inicial do Git & {% data variables.product.company_short %} só está disponível para alunos individuais, não para grupos. Depois de criar a atividade, os alunos poderão começar a trabalhar nela.

## Próximas etapas

- Faça recomendações adicionais personalizadas para seu curso. For more information, see "[Create an individual assignment](/education/manage-coursework-with-github-classroom/create-an-individual-assignment)," "[Create a group assignment](/education/manage-coursework-with-github-classroom/create-a-group-assignment)," and "[Reuse an assignment](/education/manage-coursework-with-github-classroom/teach-with-github-classroom/reuse-an-assignment)."

## Leia mais

- "[Use {% data variables.product.prodname_dotcom %} na sua sala de aula e pesquisa](/education/explore-the-benefits-of-teaching-and-learning-with-github-education/use-github-in-your-classroom-and-research)"
- "[Conecte um sistema de gerenciamento de aprendizagem para {% data variables.product.prodname_classroom %}](/education/manage-coursework-with-github-classroom/connect-a-learning-management-system-to-github-classroom)"
