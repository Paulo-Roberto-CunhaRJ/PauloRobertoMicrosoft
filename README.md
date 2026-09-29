# PauloRobertoMicrosoft


## Microsoft, Identidade, Dispositivos e Suporte N2

Este repositório reúne estudos, laboratórios e experimentos relacionados ao ecossistema Microsoft, com foco em **identidade, acessos, dispositivos, aplicações e operações de TI**.

A iniciativa parte de experiências práticas no suporte técnico em ambientes Microsoft, especialmente em **Windows, Microsoft 365, Entra ID, Intune, Active Directory e PowerShell**.

A proposta é transformar conhecimentos já utilizados na operação em **estudos estruturados, experimentos e evidências**, aprofundando a compreensão sobre como os componentes se relacionam e em quais condições produzem determinado comportamento.

> **Experiência prática como ponto de partida; investigação e estudo como forma de aprofundamento.**

---

## Experiência prática

Durante minha atuação em **Suporte N2**, trabalhei com ambientes Microsoft e situações envolvendo usuários, identidades, acessos, dispositivos e aplicações.

Entre os contextos explorados estão:

* suporte a usuários em ambientes Windows e Microsoft 365;
* análise de contas, identidades e acessos;
* suporte relacionado a Microsoft Entra ID, Intune e Active Directory;
* investigação de problemas envolvendo aplicações e dispositivos;
* utilização de PowerShell para consultas, validações e obtenção de evidências;
* suporte a Microsoft Teams e recursos de colaboração;
* atendimento presencial e remoto;
* escalonamento de incidentes para equipes de infraestrutura e desenvolvimento, com evidências e acompanhamento até a resolução.

O objetivo deste repositório é **aprofundar e sistematizar conhecimentos que já fazem parte da experiência profissional**, além de explorar novos cenários por meio de laboratórios.

---

## O problema

Uma solicitação de suporte pode envolver diferentes componentes:

```text
Usuário
   ↓
Identidade
   ↓
Autenticação
   ↓
Autorização
   ↓
Dispositivo
   ↓
Aplicação
   ↓
Serviço
```

A investigação começa pelo **contexto**.

---

## A pergunta

A pergunta central deste repositório é:

> **“Se X está relacionado a Y, em quais condições essa relação produz determinado comportamento?”**

Ela pode ser aplicada a diferentes situações:

* identidade × autenticação;
* autenticação × autorização;
* usuário × dispositivo;
* dispositivo × conformidade;
* identidade × aplicação;
* política × acesso;
* licença × serviço;
* configuração × comportamento.

A intenção é compreender a relação antes de executar uma ação.

---

## Raciocínio aplicado à computação

Utilizo relações, condições e comportamento como elementos para estruturar o raciocínio técnico.

```text
Comportamento
      ↓
Variáveis
      ↓
Condições
      ↓
Relações
      ↓
Hipótese
      ↓
Evidência
      ↓
Validação
```

Essa abordagem pode ser aplicada ao desenvolvimento, suporte, administração e investigação de ambientes Microsoft.

---

## Relações, responsabilidades e investigação

O projeto também utiliza conceitos de **grafos** e princípios de **Clean Code** como referências para estruturar o raciocínio.

Em um grafo, elementos podem ser representados como nós e suas relações como conexões. Essas conexões podem possuir atributos ou pesos que representam características da relação.

Essa ideia pode ser utilizada para pensar problemas operacionais:

```text
Identidade
    │
    ├── autentica → Usuário
    │
    ├── acessa → Aplicação
    │
    └── pertence → Grupo
                    │
                    └── recebe → Permissão
```

Em uma investigação, nem todas as relações possuem a mesma relevância. O contexto ajuda a identificar **quais relações precisam ser analisadas primeiro**, quais evidências são necessárias e quais hipóteses devem ser consideradas.

O conceito de responsabilidade segue uma lógica semelhante.

No software, o **Clean Code** ajuda a questionar:

> **“Qual é a responsabilidade deste componente?”**

Em uma investigação de suporte, a pergunta pode ser:

> **“Qual componente é responsável por este comportamento e qual é o limite da minha atuação?”**

Isso também se aplica ao trabalho em equipe.

Conhecer o ambiente não significa resolver pessoalmente todos os problemas. Significa compreender o suficiente para:

* identificar o componente envolvido;
* reunir evidências;
* validar o que está sob sua responsabilidade;
* reconhecer quando o problema pertence a outra camada;
* acionar a equipe responsável com informações relevantes;
* acompanhar a investigação até a resolução.

Dessa forma, **conhecimento técnico também ajuda a definir quando investigar, quando atuar e quando escalar**.

O objetivo não é transferir uma responsabilidade sem análise, mas realizar um escalonamento com contexto suficiente para que a próxima equipe possa continuar a investigação.

```text
Problema
   ↓
Contexto
   ↓
Relações
   ↓
Responsabilidade
   ↓
Evidências
   ↓
Minha atuação
   ↓
Escalonamento, quando necessário
   ↓
Resolução
```

---

## Microsoft Learn como referência

O **Microsoft Learn** é utilizado como fonte de aprofundamento e atualização dos conhecimentos relacionados ao ecossistema Microsoft.

A abordagem parte de uma experiência ou dúvida técnica e utiliza a documentação para ampliar a investigação:

```text
Experiência
      ↓
Questão técnica
      ↓
Microsoft Learn
      ↓
Hipótese
      ↓
Laboratório
      ↓
Evidência
      ↓
Conclusão
```

O objetivo é relacionar **experiência prática, documentação oficial e experimentação**, evitando que o aprendizado fique restrito à leitura de conteúdos.

Os links para conteúdos específicos serão associados aos respectivos laboratórios, mantendo este README como uma visão geral do projeto.

---

## Trilhas de conhecimento

### Identidade e acesso

* Microsoft Entra ID
* autenticação
* autorização
* métodos de autenticação
* políticas de acesso
* Conditional Access
* Identity Protection

### Dispositivos

* Microsoft Intune
* gerenciamento de dispositivos
* conformidade
* políticas
* configurações
* aplicações
* Microsoft Endpoint

### Microsoft 365

* Exchange Online
* SharePoint Online
* OneDrive for Business
* Microsoft Teams
* licenciamento
* configurações e serviços

### Automação e APIs

* PowerShell
* Microsoft Graph
* REST APIs
* consultas
* validações
* automação operacional

---

## Formação e aprofundamento

A formação Microsoft é organizada de maneira progressiva, partindo de fundamentos e avançando para temas de administração e identidade.

### Fundamentos

**AZ-900 — Microsoft Azure Fundamentals**

Fundamentos de computação em nuvem e conceitos essenciais do Azure.

**SC-900 — Microsoft Security, Compliance, and Identity Fundamentals**

Base conceitual em segurança, conformidade e identidade.

**MS-900 — Microsoft 365 Fundamentals**

Compreensão do ecossistema Microsoft 365 e seus principais serviços.

### Administração e operação

**MD-102 — Microsoft 365 Endpoint Administrator**

Aprofundamento em gerenciamento de dispositivos e endpoints.

### Evolução planejada

**SC-300 — Microsoft Identity and Access Administrator**

Aprofundamento planejado em identidade e gerenciamento de acessos.

**AZ-104 — Microsoft Azure Administrator**

Aprofundamento posterior na administração de recursos e serviços Azure.

**MS-102 — Microsoft 365 Administrator**

Aprofundamento posterior na administração do ambiente Microsoft 365.

As certificações são tratadas como **marcos de formação**, enquanto a experiência profissional e os laboratórios representam a aplicação e consolidação do conhecimento.

---

## ITIL e a visão de operação

A formação também é apoiada por **ITIL Foundation**, utilizada como referência para compreender o contexto de gerenciamento de serviços de TI.

A relação com o estudo Microsoft ocorre principalmente quando conceitos técnicos precisam ser analisados dentro de um contexto operacional:

```text
Tecnologia
    ↓
Serviço
    ↓
Usuário
    ↓
Incidente
    ↓
Investigação
    ↓
Resolução
```

---

## Relação com Suporte N2

Os conhecimentos deste repositório dialogam diretamente com situações encontradas em suporte:

* identidades;
* contas;
* autenticação;
* acessos;
* dispositivos;
* aplicações;
* Microsoft 365;
* políticas;
* configurações;
* evidências técnicas.

A abordagem parte da experiência prática e busca aprofundar a investigação antes da execução da ação.

---

## Registro dos laboratórios

Cada laboratório procura documentar:

* contexto ou origem da questão;
* pergunta técnica;
* hipótese;
* ambiente;
* procedimento;
* evidências;
* conclusão;
* aprendizado.

Dessa forma, o laboratório registra não apenas **o que foi feito**, mas também **por que foi feito e o que foi observado**.

---

## Minha abordagem de aprendizagem

```text
Experiência
   ↓
Estudo
   ↓
Questionamento
   ↓
Experimentação
   ↓
Validação
   ↓
Registro
   ↓
Consolidação
```

> **A experiência é o ponto de partida; a investigação transforma experiência em conhecimento estruturado.**
