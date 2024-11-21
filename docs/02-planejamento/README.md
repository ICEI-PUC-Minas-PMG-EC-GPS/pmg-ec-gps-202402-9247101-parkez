# Planejamento

> A fase de planejamento na gerência de projetos é um momento onde os detalhes do projeto são minuciosamente definidos para garantir uma execução bem-sucedida. 
> Durante essa etapa, os gerentes de projeto e suas equipes elaboram um plano abrangente que aborda aspectos como cronograma, orçamento, recursos necessários, riscos identificados e métodos de controle. 
> O objetivo é criar uma estrutura que guiará as atividades ao longo do projeto, garantindo que metas sejam alcançadas de maneira eficiente. 
> O plano de projeto não apenas define as tarefas específicas e suas interdependências, mas também estabelece critérios de sucesso e indicadores de desempenho. 
> A qualidade do planejamento influencia diretamente a capacidade da equipe em cumprir prazos, alocar recursos eficientemente e lidar com desafios que possam surgir durante a execução.

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



> O escopo do projeto define os limites, objetivos e entregáveis do projeto, estabelecendo clareza sobre o que será realizado e o que está excluído do escopo. 
> O escopo assegura a alocação adequada de recursos, evita desvios dos objetivos do projeto e garante que as expectativas dos stakeholders sejam atendidas. 
> A definição do escopo inclui documentação detalhada dos requisitos, restrições e premissas do projeto. 
> Ao longo do ciclo de vida do projeto, a gestão do escopo também inclui o controle de mudanças, garantindo que qualquer ajuste seja avaliado quanto ao seu impacto e aprovado de maneira adequada. 
> Utilize como referência a documentação existente na [Fase de Iniciação](/docs/01-iniciacao).

# Estrutura Analítica do Projeto


# Projeto Web Site

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
   

......  COLOQUE AQUI O SEU TEXTO ......

> A Estrutura Analítica do Projeto (EAP) proporciona uma representação hierárquica atividades que compõem um projeto. 
> Organizando o escopo do projeto em componentes gerenciáveis e compreensíveis, a EAP facilita a decomposição do trabalho em partes menores, tornando mais fácil o planejamento, a atribuição de responsabilidades e o monitoramento do progresso. 
> Cada elemento na estrutura representa uma parcela específica do trabalho a ser realizado, proporcionando clareza sobre as inter-relações entre as diferentes partes do projeto. 
> A EAP serve como a base para a criação do cronograma do projeto, a alocação de recursos e a identificação de dependências. 
> Essa abordagem estruturada contribui significativamente para o sucesso do projeto, garantindo uma compreensão abrangente do escopo e uma base sólida para a gestão eficaz do trabalho ao longo do ciclo de vida do projeto.

> Crie uma nova imagem da Estrutura Analítica do Projeto. Não se esqueça de adicionar o documento editável no repositório.

![Estrutura Analítica do Projeto](images/exemplo_wbs.png)

> Softwares recomendados: 
> * [WBS Schedule Pro (Demo)](https://www.criticaltools.com/)
> * [Draw.io](https://app.diagrams.net/)
> * [ProjectLibre](https://www.projectlibre.com/)

### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável de geração da WBS:
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

......  COLOQUE AQUI O SEU TEXTO ......

> A Matriz de Responsabilidades é uma ferramenta para definir e indicar as responsabilidades de cada membro da equipe em relação às atividades do projeto. 
> Também conhecida como RACI (Responsável, Aprovador, Consultado e Informado), essa matriz atribui papéis específicos a cada envolvido, indicando quem é responsável pela execução de uma tarefa, quem deve aprovar, quem precisa ser consultado e quem deve ser mantido informado. 
> Ao criar uma visão visual e estruturada das responsabilidades, a matriz RACI minimiza ambiguidades e conflitos de papel.
> Essa ferramenta não apenas esclarece as expectativas em termos de contribuições individuais, mas também contribui para um ambiente de trabalho mais organizado e transparente, resultando em uma gestão de projeto mais eficaz e bem-sucedida.

> Informações Adicionais:
> * **R**esponsible -> Executor (pessoa(s) que executará(ão)/desenvolverá(ão) a atividade)
> * **A**ccountable -> Responsável (pessoa responsável por aprovar a atividade)
> * **C**onsulted   -> Consultado (especialista consultado sobre a atividade ou parte dela)
> * **I**nformed    -> Informado (pessoas interessadas no projeto que devem ser informadas sobre a execução).
> 
> Link de auxílio: https://www.forbes.com/advisor/business/raci-chart/

> Crie uma nova imagem da Estrutura Analítica do Projeto. Não se esqueça de adicionar o documento editável no repositório.
![1](https://github.com/user-attachments/assets/09a19e98-d3a2-404e-99ff-9ed841950b6d)
> 
![2](https://github.com/user-attachments/assets/62f64c8f-a688-43c4-96b1-27c3163b7184)


![Matriz RACI](images/raci.png)


### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável da Matriz RACI:
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

......  DESCREVA EM LINHAS GERAIS O CRONOGRAMA DO SEU PROJETO AQUI ......

> O cronograma do projeto fornece uma representação temporal detalhada de todas as atividades, marcos e eventos ao longo do ciclo de vida do projeto. 
> Elaborado durante o planejamento, o cronograma é uma ferramenta que oferece uma visão das interdependências entre as tarefas, alocando recursos e definindo prazos para as entregas.
> Utilizando técnicas como a análise de rede (PERT/CPM) e estimativas de duração, o cronograma ajuda na identificação de caminhos críticos, permitindo aos gestores de projeto otimizar recursos, antecipar potenciais atrasos e tomar decisões. 
> Além disso, o cronograma serve como um guia para monitorar o progresso, comunicar efetivamente com a equipe e as partes interessadas, e ajustar estratégias para garantir a conclusão bem-sucedida do projeto dentro dos prazos estabelecidos.


### Documento

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável do Cronograma do Projeto:
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

> O orçamento do projeto envolve a estimativa e alocação de recursos financeiros necessários para a execução bem-sucedida do projeto, abrangendo custos diretos e indiretos, despesas operacionais, investimentos em equipamentos, pessoal, entre outros. 
> O desenvolvimento do orçamento deve considerar variáveis como riscos, imprevistos e mudanças no escopo. 
> Uma vez estabelecido, o orçamento serve como guia para a utilização eficiente dos recursos financeiros ao longo do projeto. 
> A gestão do orçamento não apenas ajuda a controlar os custos, mas também fornece transparência e prestação de contas, permitindo que gestores tomem decisões informadas e evitem surpresas financeiras ao longo do ciclo de vida do projeto. 
> Assim, o orçamento contribui para o sucesso do projeto, garantindo a viabilidade econômica e a entrega dentro das expectativas financeiras estabelecidas.

### Documento Editável

> Você deve atualiza o seguinte link (ou link correspondente), como o arquivo editável do Orçamento do Projeto:
- [Cronograma e Orçamento do Projeto - Editável](artefatos/cronograma_orcamento.pod)

```diff
+ Tarefa 08:
+ Fim da seção a ser atualizada.
```

# Planos de Gerenciamento

> Os planos de gerenciamento do projetos consolidam as diretrizes e estratégias para a execução bem-sucedida de um empreendimento. 
> Ele abrange diversos aspectos, como escopo, cronograma, custos, riscos, qualidade, recursos humanos, comunicação e aquisições, proporcionando uma visão abrangente e integrada do projeto. 
> Este plano funciona como um guia mestre que orienta a equipe de projeto e as partes interessadas ao longo do ciclo de vida do projeto, estabelecendo expectativas, responsabilidades e processos. 
> Além disso, serve como um instrumento de comunicação, alinhando as expectativas entre os membros da equipe e as partes interessadas, mitigando riscos e fornecendo uma estrutura sólida para a tomada de decisões. 

```diff
+ Tarefa 09:
+ Checklist de Qualidade
```

## Plano de Qualidade

...... DESCREVA SUCINTAMENTE O PLANO DE QUALIDADE UTILIZADO NO PROJETO ......

> O Plano de Qualidade auxilia a garantir que as entregas do projeto atendam aos padrões de qualidade definidos. 
> Este plano abrange atividades como definição de padrões, procedimentos de garantia de qualidade, critérios de aceitação e processos de monitoramento e controle da qualidade ao longo do ciclo de vida do projeto. 
> Ao identificar metas de qualidade, responsabilidades da equipe, e métricas de avaliação, o Plano de Qualidade busca assegurar que o projeto atinja ou exceda as expectativas dos stakeholders em termos de desempenho e conformidade. 
> A adoção de políticas de qualidade auxilia a mitigar riscos, promove a confiança nas entregas do projeto e, por fim, aumenta a probabilidade de sucesso do empreendimento. 

> Referência - Conceitual
> * https://www.researchgate.net/publication/230636169_Software_Quality_Assurance

> Normas de Qualidade:
> * https://repositorium.uminho.pt/bitstream/1822/27266/1/Tese_MEI_PG19676_Juliana%20Oliveira.pdf
> * https://cin.ufpe.br/~processos/TAES3/Livro/00-LIVRO/07-Normas%20ISO%20e%20Qualidade%20de%20Software-v6_CORRIGIDO.pdf

> Métricas de software:
> * https://repositorio.unicamp.br/Busca/Download?codigoArquivo=489087
> * https://lume.ufrgs.br/bitstream/handle/10183/66095/000870909.pdf?sequence=1
> * https://www.computerweekly.com/br/tip/23-metricas-de-desenvolvimento-de-software-que-devem-ser-monitoradas

> Processos de Garantia da Qualidade de Software
> * https://ceur-ws.org/Vol-3200/paper22.pdf
> * https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d6bd60206282a2d4449e414e81a703612ef78a0c
> * https://www.testbytes.net/blog/quality-assurance-process-methodology/
> * https://www.projectmanager.com/blog/quality-assurance-and-testing

> Você pode utilizar como referência o seguinte documento:
> [Checklist de Qualidade](artefatos/checklist_qualidade.docx)

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

> O Plano de Aquisições define o processo relacionado à aquisição de bens e serviços necessários para a execução do projeto. 
> Este plano abrange a identificação de necessidades, a seleção de fornecedores, a elaboração de contratos, e a gestão do relacionamento com os fornecedores durante do ciclo de vida do projeto. 
> O Plano de Aquisições visa garantir a aquisição eficiente e eficaz dos recursos necessários, minimizando riscos e custos. 
> Além disso, ele proporciona transparência nas relações com fornecedores, promovendo a conformidade com os prazos estabelecidos e padrões de qualidade. 

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
>
> Você pode utilizar como referência o seguinte documento:
- [Plano de Gerenciamento de Comunicação - Editável](artefatos/plano_comunicacao.docx)

### Plano de Comunicação do Projeto

| Entregável                         | Público Alvo | Met. Comunicação | Frequência  | Responsável | 
|------------------------------------|--------------|------------------|-------------|-------------|
| Ata de reunião                     |              |                  |             |             |
| Declaração de escopo               |              |                  |             |             |
| WBS                                |              |                  |             |             |
| Dicionário da WBS                  |              |                  |             |             |
| Cronograma                         |              |                  |             |             |
| Lista de Riscos                    |              |                  |             |             |
| Plano de qualidade                 |              |                  |             |             |
| Plano de projeto                   |              |                  |             |             |
| Relatório de Progresso             |              |                  |             |             |
| Relatório de Aderência ao Processo |              |                  |             |             |
| Checklists de Inspeção             |              |                  |             |             |
|                                    |              |                  |             |             |
|                                    |              |                  |             |             |
|                                    |              |                  |             |             |

> Legenda:
> - Público: a quem se destina a comunicação.
> - Método de Comunicação: e_mail, reunião presencial, reunião virtual, etc.
> - Freqüência: diária, semanal, quinzenal, mensal, etc.
> - Responsável: pessoa responsável pela comunicação.

### Plano de Gerência de Comunicação

> Indique:
> - Ferramentas utilizadas no projeto - adicionar link de acesso às ferramentas
> - Papéis: responsáveis pelas correspondentes no projeto
> - Princípios gerais: indica quais princípios serão adotados no plano de comunicação, como clareza, objetividade, impessoalidade, imparcialidade e cordialidade. Detalhar.
>
> Plano de Gerência de Configuração: definir, em linhas gerais, como (ferramenta) serão controladas e distribuídas as versões e se haverá algum controle de responsabilidades.

- Ferramentas utilizadas:
- - [Ferramenta 01](https://pucminas.br)
  - [Ferramenta 02](https://pucminas.br)
  - [Ferramenta 03](https://pucminas.br)
- Papéis:
- - ...
  - ...
  - ...
- Princípios gerais
- - ...
  - ...
  - ...
  - ...

```diff
+ Tarefa 11:
+ Fim da seção a ser atualizada.
```

```diff
+ Tarefa 12:
+ Riscos do Projeto
```

## Plano de Riscos

......  COLOQUE AQUI O SEU TEXTO ......


> O plano de riscos busca antecipar, avaliar e mitigar os desafios potenciais que podem surgir ao longo do projeto. 
> Este documento estratégico oferece uma visão global dos riscos, categorizando-os e delineando estratégias para lidar com cada uma das possíveis adversidades. 
> Inicialmente, é realizada a identificação detalhada dos riscos, abrangendo desde ameaças imprevistas até oportunidades que podem ser exploradas. 
> Uma vez catalogados, os riscos são avaliados quanto à sua probabilidade de ocorrência e impacto, permitindo a priorização e foco em áreas críticas.
>
> O plano de riscos não apenas destaca os perigos em potencial, mas também estabelece respostas e estratégias de contingência. 
> Isso inclui a definição de ações preventivas para mitigar riscos antes que se materializem, bem como estratégias de mitigação para minimizar seu impacto se ocorrerem. 
> Além disso, a identificação de pontos de monitoramento contínuo ao longo do projeto permite uma resposta ágil às mudanças nas condições do ambiente.
>
> Você pode utilizar como referência o seguinte documento:
- [Plano de Gerenciamento de Riscos - Editável](artefatos/plano_riscos.xls)

| Categoria do Risco  | Descrição do Risco | Impacto       | Risco         | Medidas de Prevenção (Contramedidas) | Medidas de Contingência (Mitigação) | 
|---------------------|--------------------|---------------|---------------|--------------------------------------|-------------------------------------|
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |
|                     |                    |               |               |                                      |                                     |

> Indique:
> Categoria do Risco: *ex.: Cliente, Cronograma, Orçamento, Aquisição de produtos, etc*
> Descrição do Risco: *ex.: Cliente não aparenta ter muito interesse no projeto*
> Impacto: *Baixo / Médio / Alto*
> Risco: *Baixo / Médio / Alto*
> Medidas de Prevenção: *Medidas que devem ser adotadas para evitar que o risco se concretize*
> Medidas de Contingência: *Medidas que devem ser adotadas caso o risco se concretize*
>
> *Obs.: Para determinar o risco considere a seguinte combinação entre Probabilidade e Impacto:

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






