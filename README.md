# Projeto-Integrador
Sistema de Gestão de Dados de Universidade

## Objetivo
Este projeto objetiva desenvolver um sistema de gestão de dados de diferentes pessoas que interagem com o software de uma grande universidade. Sabemos que dados precisos e atualizados são essenciais para tomadas de decisões que visam atingir objetivos com mais eficiência e rapidez. Sendo assim, o sistema foi modelado em UML e prototipado para garantir que a experiência do usuário seja prática e intuitiva, pois, segundo Nelson, 2004

>"Uma boa documentação comunica ideias de forma eficaz. Quem lê o código precisa entender o que você deseja transmitir. Por isso, primeiro, é importante considerar para quem você está escrevendo a documentação... Outro aspecto de boa documentação é a atualização: a documentação não ajuda se não for atualizada. Ela deve ser atualizada ao mesmo tempo que as mudanças no código são feitas. Garanta que seja o mais fácil possível atualizar sua documentação"
>
>NELSON, Catherine. 2004

## Requisitos tecnológicos
- Java, HTML, CSS, MIRO
- IDE

## Funcionalidades
- Tela de boas-vindas ao Sistema de Gestão de dados da Universidade
- Tela de acesso aos formulários de dados específicos de cada ator que alimentará o sistema 
- Cadastro de Pessoa Física
- Cadastro de Pessoa Jurídica
- Cadastro de Professores
- Cadastro de Fornecedores
- Cadastro de Alunos
- Se algum campo dos formulários for preenchidos com erros ou em branco, o sistema deverá notificar o usuário com mensagem de "campo obrigatório" ou "erro"

## Diagrama de Caso de Uso
[Diagrama de Caso de Uso](https://lucid.app/lucidchart/8f33be82-9072-4a7f-9da6-ad7640d5604e/edit?invitationId=inv_06ae33e0-dd34-4e57-9797-ec234b07f78e)

## Diagrama de Classe
[Diagrama de classe](https://lucid.app/lucidchart/27716fd9-ca29-4dbe-a594-6cb441a0b75a/edit?viewport_loc=-97%2C8%2C2208%2C1112%2CHWEp-vi-RSFO&invitationId=inv_79041cf7-876c-4048-a319-6cd81fd4d353)

## Descrição dos Protótipos de Interface de cada uso
**Pré-condição:** Usuário autenticado no sistema

**Cenário Principal:**
1. Usuário seleciona a opção correspondente para o cadastro de sua jornada
2. Sistema exibe formulário de cadastro
3. Usuário preenche os dados
4. Usuário confirma o cadastro
5. Sistema salva os dados e exibe confirmação

**Cenário Alternativo 1:** Dados Incompletos
- Usuário não preenche todos os campos obrigatórios
- Sistema exibe mensagem de erro

**Cenário Alternativo 2:** Dados Inválidos
- Usuário preenche campos com dados inválidos
- Sistema exibe mensagem de erro

***Essa estrutura se repetirá em todos os casos de uso***

### Cadastro de Pessoa Física 
*Campos do Formulário:*
- Campo para inserir foto
- Nome Completo
- CPF
- Data de Nascimento
- Endereço Completo
- Contatos
- Atividade Profissional
- Formação Acadêmica
- Espaço para digitação de informações adicionais
  
*Botões de Ação:*
- Salvar
- Cancelar
- Retornar ao menu principal

### Cadastro de Alunos
*Campos do Formulário:*
- Campo para inserir foto
- Nome Completo do Aluno
- Número de matrícula
- CPF
- Data de Nascimento
- Endereço Completo
- Contatos
- Espaço clicáveis com lista de opções para seleção do curso
- Espaço clicáveis com lista de opções para seleção da Disciplina
  
*se o aluno for menor de idade*
- Nome Completo do Responsável Legal 
- CPF do Responsável Legal
  
*Botões de Ação:*
- Salvar
- Cancelar
- Retornar ao menu principal

### Cadastro de Pessoa Jurídica
*Campos do Formulário:*
- Razão Social
- CNPJ
- Endereço Completo
- Contatos
- Espaço clicáveis com lista de opções para seleção de atividades
- Composição Societária
  
*Botões de ação para:*
- Upload de documentos
- Espaço digitável para assinaturas digital ou eletrônica
  
*Botões de Ação:*
- Salvar
- Cancelar
- Retornar ao menu principal
  
### Cadastro de Professores
*Campos do Formulário:*
- Campo para inserir foto
- Nome Completo
- Número de matrícula
- CPF
- Data de nascimento
- Endereço Completo
- Contatos
- Espaço clicáveis com lista de opções para seleção de grau de formação acadêmica
  
*Botões de ação para:*
- Upload de documentos
- Campo de texto para digitação de informações adicionais
  
*Botões de Ação:*
- Salvar
- Cancelar
- Retornar ao menu principal
 
### Cadastro de Fornecedores
*Campos do Formulário:*
- Razão Social
- CNPJ
- Endereço Completo
- Contatos
- Espaço clicáveis com lista de opções para ramos de atividades
- Nome completo do(s) representante(s) legal(is)
- CPF do Representante Legal
- Botões para Upload de documentos
- Espaço digitável para assinaturas digital ou eletrônica
  
*Botões de Ação:*
- Salvar
- Cancelar
- Retornar ao menu principal
  
## Protótipos
[Cadastro de Pessoa Física](https://miro.com/app/board/uXjVLDNtiZw=/?share_link_id=193656029880) 

[Cadastro de Alunos](https://miro.com/app/board/uXjVLDNtiZw=/?share_link_id=193656029880) 

[Cadastro de Pessoa Jurídica](https://miro.com/app/board/uXjVLDNtiZw=/?share_link_id=193656029880)

[Cadastro de Professores](https://miro.com/app/board/uXjVLDNtiZw=/?share_link_id=193656029880) 

[Cadastro de Fornecedores](https://miro.com/app/board/uXjVLDNtiZw=/?share_link_id=193656029880) 

