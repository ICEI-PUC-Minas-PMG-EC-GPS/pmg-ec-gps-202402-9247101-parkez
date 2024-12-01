# Planejamento

# Estrutura do Documento

- [Fase de Planejamento](#planejamento)
- [Escopo do Projeto](#escopo-do-projeto)
- [Estrutura Analítica do Projeto](#estrutura-analítica-do-projeto)
- [Matriz de Responsabilidades](#matriz-de-responsabilidades)
- [Cronograma do Projeto](#cronograma-do-projeto)
- [Orçamento do Projeto](#orçamento-do-projeto)
- [Planos de Gerenciamento](#planos-de-gerenciamento)
  - [Plano de Qualidade](#plano-de-qualidade)
  - [Plano de Aquisição](#plano-de-aquisição)
  - [Plano de Comunicação](#plano-de-comunicação)
  - [Plano de Riscos](#plano-de-riscos)

-----
```diff
+ Tarefa 04:
+ Escopo e Estrutura Analítica do Projeto
```

# Escopo do Projeto

### OBJETIVO DO PROJETO:

   Facilitar a reserva de vagas de estacionamento para usuários, permitindo que pesquisem locais de interesse, visualizem estacionamentos próximos e reservem vagas com pagamento parcial antecipado.

### Requisitos Funcionais:

   | ID     | Descrição do Requisito                                                                                                                                 | Prioridade |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RF-001 | Permitir que o usuário pesquise estacionamentos próximos ao local desejado.                                                                            | ALTA       |
| RF-002 | Permitir que o usuário visualize detalhes do estacionamento, como disponibilidade de vagas, preços e horários de funcionamento.                        | ALTA       |
| RF-003 | Permitir que o usuário faça a reserva de uma vaga de estacionamento através do aplicativo, com pagamento de 30% do valor no ato da reserva.            | ALTA       |
| RF-004 | Implementar uma funcionalidade para cancelamento de reserva até 15 minutos após a confirmação.                                                         | ALTA       |
| RF-005 | Calcular automaticamente o valor a ser pago pelo tempo de permanência no estacionamento, com base em tarifas configuradas.                             | ALTA       |
| RF-006 | Oferecer ao usuário a opção de pagamento do saldo restante ao chegar no estabelecimento.                                                               | ALTA       |
| RF-007 | Implementar um sistema de notificações para avisar o usuário sobre o status da reserva, prazos para cancelamento e promoções.                          | MÉDIA      |
| RF-008 | Fornecer recomendações de locais parceiros próximos ao destino do usuário, destacando ofertas e descontos exclusivos.                                  | MÉDIA      |
| RF-009 | Implementar um clube de assinantes que ofereça benefícios exclusivos, como descontos em estacionamentos, mediante o pagamento de uma mensalidade.       | MÉDIA      |
| RF-010 | Permitir a aplicação de descontos especiais em estacionamentos próximos a eventos, como shows ou eventos esportivos, para usuários do aplicativo.      | MÉDIA      |

### Requisitos Não Funcionais

| ID     | Descrição do Requisito                                                                                                             | Prioridade |
|--------|------------------------------------------------------------------------------------------------------------------------------------|------------|
| RNF-001| O aplicativo deve ser compatível com as plataformas iOS e Android, garantindo uma experiência consistente em ambos os sistemas.     | ALTA       |
| RNF-002| O sistema deve garantir a proteção dos dados do usuário, especialmente as informações de pagamento, utilizando criptografia SSL/TLS.| ALTA       |
| RNF-003| O aplicativo deve apresentar tempo de resposta inferior a 2 segundos para consultas de estacionamentos e reservas.                  | MÉDIA      |
| RNF-004| O aplicativo deve ser escalável, suportando um número crescente de usuários e estacionamentos sem perda significativa de desempenho. | ALTA       |
| RNF-005| O sistema deve garantir alta disponibilidade, com um tempo de atividade (uptime) de 99,9% para evitar interrupções no serviço.      | ALTA       |

### Restrições


| ID     | Descrição da Restrição                                                                                                                |
|--------|---------------------------------------------------------------------------------------------------------------------------------------|
| RES-001| O aplicativo deve ser lançado nas lojas Apple App Store e Google Play Store até o final de dezembro de 2024.                          |
| RES-002| O desenvolvimento deve ser realizado com um orçamento fixo e limitado, não podendo exceder o valor previamente acordado pelo cliente.  |
| RES-003| A integração com os sistemas de pagamento deve seguir as regulamentações locais e internacionais, como PCI-DSS, para proteção de dados.|
| RES-004| As parcerias com estacionamentos e estabelecimentos para recomendações e descontos devem ser formalizadas antes do lançamento do aplicativo. |
| RES-005| O suporte a atualizações e manutenção do aplicativo deve ser garantido por um período mínimo de 12 meses após o lançamento.            |

### Condições para início do Projeto

| ID    | Descrição da Condição para Início do Projeto                  |
|-------|---------------------------------------------------------------|
| CI-001| Aprovação do orçamento e alocação de recursos financeiros     |
| CI-002| Definição e aprovação dos requisitos e especificações do sistema |
| CI-003| Estabelecimento de parcerias e acordos com estabelecimentos    |

## Marcos Agendados e Entregas

| ID   | Marco do Projeto                                                  | Descrição Detalhada                                             | Data Prevista        |
|------|-------------------------------------------------------------------|-----------------------------------------------------------------|----------------------|
| M-1  | Desenvolvimento das páginas principais                           | Implementação das páginas de login, recuperação de senha, e página inicial (home). | 15/10/2024           |
| M-2  | Liberação do sistema para cadastro de informações e configuração. | Finalização da configuração inicial e cadastro de informações. | 22/10/2024           |
| M-3  | Desenvolvimento da funcionalidade de pesquisa e reserva de vagas  | Implementação das funcionalidades de pesquisa de locais e reserva de vagas com processamento de pagamentos. | 05/11/2024           |
| M-4  | Desenvolvimento da funcionalidade de cancelamento de reservas      | Implementação da opção para cancelar reservas e políticas associadas. | 15/11/2024           |
| M-5  | Desenvolvimento da página de perfil e histórico de reservas       | Criação das páginas de perfil do usuário e histórico de reservas. | 22/11/2024           |
| M-6  | Implementação do sistema de notificações                           | Criação de notificações para confirmações de reserva, cancelamento e outras atualizações importantes. | 01/12/2024           |
| M-7  | Disponibilização do clube de assinantes e benefícios               | Lançamento do clube de assinantes com benefícios e descontos exclusivos. | 15/12/2024           |
| M-8  | Ativação da funcionalidade de descontos para eventos               | Implementação de descontos exclusivos para eventos especiais e integração com o sistema. | 01/01/2025           |
| M-9  | Realização de testes finais e ajustes                            | Testes finais do sistema, correção de bugs e ajustes baseados no feedback dos usuários. | 01/03/2025           |
| M-10 | Deploy nas plataformas de download (App Store e Google Play)       | Preparação e lançamento do aplicativo nas principais plataformas de download. | 10/03/2025           |
| M-11 | Permissão para uso do sistema por usuários focais.                | Início da fase de uso real com usuários focais para validar a funcionalidade completa do sistema. | 22/03/2025           |



# Estrutura Analítica do Projeto


# Aplicativo Mobile

## 1. Identificação do problema
   - Dificuldade em encontrar vagas de estacionamento
   - Falta de informações centralizadas sobre disponibilidade de vagas
   - Desperdício de tempo e combustível
     

## 2. Objetivos do Projeto
   - Desenvolver um aplicativo mobile para reserva antecipada de vagas de estacionamento
   - Criar um sistema de busca que exiba vagas disponíveis em tempo real
   - Implementar mecanismos de reserva e pagamento

## 3. Justificativa
   - Otimização de busca por vagas de estacionamento
   - Melhoria na gestão de vagas
   - Criação de um canal de marketing

## 4. Conceituação
   - Público-Alvo
       - Motoristas em áreas urbanas
       - Estabelecimentos que buscam atrair mais clientes
   - Modelo Conceitual
       - O aplicativo deve oferecer praticidade
       - Reserva antecipada de vagas
       - Parcerias com estacionamentos e estabelecimentos para descontos e promoções


## 5. Estruturas Informacional e Visual
   - Arquitetura da Informação
       - Páginas principais do app: login, recuperação de senha, home, pesquisa de estacionamentos, reserva e perfil do usuário
   - Layout
       - Interface intuitiva e responsiva para iOS e Android
       - Visual limpo
       - Destaque para informações de disponibilidade de vagas e promoções

## 5. Atividades
   - Desenvolvimento das principais funcionalidades
   - Validação contínua da experiência do usuário
   - Implementação de funcionalidades avançadas (clube de assinantes, descontos para eventos)
   
![Estrutura Analítica do Projeto](images/exemplo_wbs.png)

> Softwares recomendados: 
> * [WBS Schedule Pro (Demo)](https://www.criticaltools.com/)
> * [Draw.io](https://app.diagrams.net/)
> * [ProjectLibre](https://www.projectlibre.com/)

### Documento Editável

- [Estrutura Analítica do Projeto - Editável](artefatos/estrutura_analitica_projeto.wbs)

```diff
+ Tarefa 04:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 05:
+ Matriz de Responsabilidades (RACI)
```

# Matriz de Responsabilidades


![1](https://github.com/user-attachments/assets/09a19e98-d3a2-404e-99ff-9ed841950b6d)
> 
![2](https://github.com/user-attachments/assets/62f64c8f-a688-43c4-96b1-27c3163b7184)


![Matriz RACI](images/raci.png)


### Documento Editável

- [Matriz de Responsabilidades (RACI) - Editável](artefatos/matriz-raci.docx)

```diff
+ Tarefa 05:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 07:
+ Cronograma do Projeto
```

# Cronograma do Projeto

### Documento

- [[Cronograma e Orçamento do Projeto -(https://docs.google.com/document/d/1m841oEDj8vBRjz5OOj6P9vOlRZj-is4wL6Y765xpEIA/edit?usp=sharing)

```diff
+ Tarefa 07:
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 08:
+ Orçamento do Projeto
```

# Orçamento do Projeto

......  DESCREVA EM LINHAS GERAIS O ORÇAMENTO DO SEU PROJETO AQUI ......
![image](https://github.com/user-attachments/assets/e28a9fd4-71e1-4778-9e50-eeb718394684)

![image](https://github.com/user-attachments/assets/fcae183a-6c57-4d4c-b0da-2fedc43aea92)

### Documento Editável

- [Cronograma e Orçamento do Projeto - Editável](artefatos/cronograma_orcamento.pod)

```diff
+ Tarefa 08:
+ Fim da seção a ser atualizada.
```

# Planos de Gerenciamento

```diff
+ Tarefa 09:
+ Checklist de Qualidade
```

## Plano de Qualidade

### Artefatos a serem verificados

| Artefato   | Tipo Verif. | Data        | Responsável | Métrica     | Data Correção | Ação Não Conform. | Resp. Avaliação | Resp. Correção |
|------------|-------------|-------------|-------------|-------------|---------------|-------------------|-----------------|----------------|
|     Documento de Requisitos       |    Revisão Manual         |      2024-11-25       |        Bruno Henrique     |     Conformidade com padrões        |      2024-11-30         |         Atualizar requisitos          |        Felipe Thomaz         |          Bruno Henrique       |
|    Código-Fonte        |      Teste Automático       |     2024-12-01      |       Raphael Rezende      |      Cobertura > 80%       |       2024-12-05        |         Corrigir testes falhos          |      Mauricio Richthofen           |        Raphael Rezende          |


### Padrões e Normas Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
|    ISO/IEC 25010        |       Norma que define características de qualidade de software.v      |
|    Clean Code        |     Conjunto de boas práticas para escrever código claro e compreensível.        |
|      Padrão IEEE 830      |      Orientações para criação de documentos de especificação de requisitos.       |


### Ambiente das Atividades de Qualidade

| Ambiente   | Descrição   | 
|------------|-------------|
|      Ambiente de Teste      |      Servidor dedicado com acesso a banco de dados isolado.       |
|      Ferramenta CI/CD      |       Jenkins configurado para realizar builds e testes automáticos.      |
|      Ambiente Local      |       Máquinas de desenvolvimento com ferramentas como Visual Studio e JIRA.      |


### Equipe de Qualidade

| Nome       | Responsabilidade | 
|------------|------------------|
|     Bruno Henrique       |         Realizar revisões de documentos e garantir conformidade com padrões.         |
|      Mauricio Richthofen       |        Implementar e monitorar testes automatizados.          |
|      Raphael Rezende       |         Validar correções e emitir relatórios de qualidade.         |


### Metodologias de Qualidade Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
|        Test-Driven Development (TDD)     |      Desenvolvimento orientado a testes para garantir robustez do código.       |
|   Análise de Riscos         |      	Identificação e mitigação de riscos potenciais no software.       |
|     Revisões por Pares       |     	Revisões cruzadas para identificar problemas antes da implementação.        |

```diff
+ Tarefa 09:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 10:
+ Especificação de Produto para Aquisição
```

## Plano de Aquisição

[aquisicao_produtos.docx](https://github.com/user-attachments/files/17853317/aquisicao_produtos.docx)


```diff
+ Tarefa 10:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 11:
+ Plano de Comunicação
```

## Plano de Comunicação

...... DESCREVA SUCINTAMENTE O PLANO DE COMUNICAÇÃO UTILIZADO NO PROJETO ......

> O Plano de Comunicação estabelece estratégias e diretrizes para facilitar a troca de informações entre os membros da equipe e as partes interessadas. 
> Este plano abrange aspectos como os meios de comunicação, a frequência das atualizações, os canais de distribuição de informações e os responsáveis pela comunicação. 
> Uma comunicação eficiente não apenas previne mal-entendidos e conflitos, mas também fortalece o engajamento da equipe e o apoio das partes interessadas. 

[plano_comunicação.docx](https://github.com/user-attachments/files/17882584/plano_comunicacao.docx)

  
### Plano de Gerência de Comunicação

- Ferramentas utilizadas:
- - [GitHub](https://github.com/ICEI-PUC-Minas-PMG-EC-GPS/pmg-ec-gps-202402-9247101-parkez/tree/master)
  - FireBase
  - Flutter
 
- Papéis:
  - Líder do Projeto: Coordena a comunicação geral e valida as entregas comunicadas.
  - Analista de Requisitos: Responsável por compartilhar artefatos técnicos, como o escopo.
  - Especialista em Qualidade: Relata a conformidade com padrões e atualizações de inspeções.
    
- Princípios gerais
  - Clareza: Informações transmitidas de forma objetiva e sem ambiguidade.
  - Impessoalidade: Foco no conteúdo e nos objetivos do projeto, evitando conflitos interpessoais.
  - Cordialidade: Comunicação respeitosa e construtiva.
  - Imparcialidade: Distribuição de informações de maneira justa entre os stakeholders.
  - Objetividade: Comunicação direta e alinhada aos interesses do projeto.
    
```diff
+ Tarefa 11:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 12:
+ Riscos do Projeto
```

## Plano de Riscos

- [Plano de Gerenciamento de Riscos -](https://github.com/user-attachments/files/17882615/plano_riscos.xlsx)


| Probabilidade | Impacto       | Risco         |
|---------------|---------------|---------------|
| Baixo         | Baixo         | Baixo         |
| Médio         | Médio         | Médio         |
| Alto          | Alto          | Alto          |
| Baixo         | Médio         | Médio         |
| Médio         | Baixo         | Médio         |
| Baixo         | Alto          | Médio         |
| Alto          | Baixo         | Médio         |
| Médio         | Alto          | Alto          |
| Alto          | Médio         | Alto          |


```diff
+ Tarefa 12:
+ Fim da seção a ser atualizada.
```

-----






