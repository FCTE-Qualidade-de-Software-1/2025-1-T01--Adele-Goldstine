# Objetivo de Negócio do AgroMart

A solução tecnológica denominada Agromart foi desenvolvida para facilitar a relação entre os pequenos agricultores e os consumidores. A solução engloba uma interface web para os agricultores e um aplicativo mobile multi- plataforma para os consumidores, com o propósito de proporcionar ao pequeno agricultor uma maior garantia para o escoamento de sua produção e ajudar pessoas que buscam uma alimentação mais saudável e de qualidade a encontrar seus produtos.

## Objetivos de Medição

### Usabilidade

| Objeto | Objetivo | Enfoque de Qualidade | Ponto de Vista | Contexto |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| AgroMart | Melhorar  | Usabilidade  | Equipe de Desenvolvimento  | Disciplina de Qualidade de Software  |

### Compatibilidade

| Objeto | Objetivo | Enfoque de Qualidade | Ponto de Vista | Contexto |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| AgroMart | Garantir | Compatibilidade | Equipe de Desenvolvimento | Disciplina de Qualidade de Software |

### Funcionalidade

| Objeto | Objetivo | Enfoque de Qualidade | Ponto de Vista | Contexto |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| AgroMart | Avaliar | Funcionalidade | Equipe de Desenvolvimento | Disciplina de Qualidade de Software |

## Questões Objetivos de Medição

### Usabilidade

**Questão 1:** O AgroMart oferece uma experiência de uso agradável, acessível e intuitiva para usuários com diferentes níveis de habilidade tecnológica?

**Hipótese 1:** Pelo menos 90% dos usuários, independentemente do nível de familiaridade com tecnologia, conseguem concluir as principais tarefas na plataforma em menos de 2 minutos, sem assistência externa. A pontuação no questionário de atratividade e estética da interface é superior a 80%.

**Métricas Relacionadas a Questão 1:**

- Tempo médio para conclusão de tarefas essenciais.
- Percentual de usuários que conseguem concluir tarefas sem solicitar ajuda (FAQ ou suporte).


### Compatibilidade

**Questão 2:** O AgroMart é capaz de coexistir de forma eficiente com outros sistemas e aplicativos que possam estar em uso no dispositivo ou no ambiente tecnológico do usuário, sem gerar conflitos, lentidão ou falhas?

**Hipótese 2:** O AgroMart apresenta taxa de ocorrência de conflitos, falhas ou degradação de desempenho inferior a 3% quando executado simultaneamente com outros aplicativos comuns (navegadores, apps de mensagens, planilhas, etc.) ou em ambientes com múltiplas aplicações.

**Métricas Relacionadas a Questão 2:**

- Número de incidentes relacionados a conflitos de software reportados durante o uso simultâneo com outros sistemas/aplicativos.
- Variação média no uso de recursos (CPU, memória, rede) quando o AgroMart é executado junto com outros aplicativos comuns.


### Funcionalidade

**Questão 3:** As integrações do AgroMart com sistemas externos (como gateways de pagamento, sistemas de logística e APIs de comunicação) funcionam de forma correta e confiável?

**Hipótese 3:** 100% das integrações críticas (pagamento, logística, comunicação) estão funcionando corretamente, com taxa de falhas inferior a 1% nas operações realizadas em ambiente de produção.

**Métricas Relacionadas a Questão 3:**

- Taxa de sucesso das operações realizadas via integrações externas.
- Tempo médio de resposta das APIs externas utilizadas pela plataforma.


## Abstraction Sheets 

### Objetivo 1 - Usabilidade

| **Foco de Qualidade** | **Fatores de Avaliação** |
|-----------------------|---------------------------|
| Usabilidade            | - Compreensibilidade <br> - Apreensibilidade <br> - Operabilidade <br> - Atratividade <br> - Estética da Interface <br> - Proteção contra Erros <br> - Acessibilidade |

| **Hipóteses de Baseline** | **Impacto das Baseline** |
|---------------------------|---------------------------|
| - Maioria dos usuários conseguem concluir tarefas em menos de 2 minutos sem ajuda. <br> - Pontuação de atratividade da interface acima de 80%. <br> - Consulta à documentação é inferior a 5% das sessões. | - Plataforma intuitiva, acessível e agradável para diferentes perfis de usuário. <br> - Reduz erros operacionais e necessidade de suporte. <br> - Melhora a adoção e a eficiência no uso da plataforma. |


### Objetivo 2 - Compatibilidade

| **Foco de Qualidade** | **Fatores de Avaliação** |
|-----------------------|---------------------------|
| Compatibilidade        | - Coexistência <br> - Interoperabilidade <br> - Conformidade de Plataforma |

| **Hipóteses de Baseline** | **Impacto das Baseline** |
|---------------------------|---------------------------|
| - Taxa de conflitos, falhas ou degradação de desempenho ao usar com outros aplicativos. <br> - Funciona corretamente nos principais SOs (Windows, macOS, Android, iOS) e navegadores (Chrome, Firefox, Edge, Safari). <br> - Mantém desempenho aceitável com tempo de carregamento inferior a 2 segundos. | - Garante operação sem falhas, conflitos ou lentidão em diversos ambientes. <br> - Assegura interoperabilidade com sistemas externos e dispositivos variados. <br> - Melhora a satisfação do usuário em diferentes contextos tecnológicos. |


### Objetivo 3 - Funcionalidade

| **Foco de Qualidade** | **Fatores de Avaliação** |
|-----------------------|---------------------------|
| Funcionalidade         | - Adequação Funcional <br> - Exatidão Funcional <br> - Interoperabilidade <br> - Conformidade Funcional |

| **Hipóteses de Baseline** | **Impacto das Baseline** |
|---------------------------|---------------------------|
| - Taxa das funcionalidades críticas implementadas e operacionais. <br> - Baixa porcentagem de erros críticos relatados em produção. <br> - Funcionalidades atendem às necessidades dos usuários sem limitações significativas. | - Assegura que as funcionalidades essenciais sejam completas, corretas e adequadas. <br> - Garante valor aos usuários com baixo risco de falhas críticas. <br> - Promove confiança na plataforma. |






