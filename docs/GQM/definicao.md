# Definição do GQM para o Projeto Agromart

## Objetivo de Negócio do **AgroMart**

A solução tecnológica denominada Agromart foi desenvolvida para facilitar a relação entre os pequenos agricultores e os consumidores. A solução engloba uma interface web para os agricultores e um aplicativo mobile multiplataforma para os consumidores, com o propósito de proporcionar ao pequeno agricultor uma maior garantia para o escoamento de sua produção e ajudar pessoas que buscam uma alimentação mais saudável e de qualidade a encontrar seus produtos.

Conectar agricultores familiares diretamente a consumidores e co-agricultores, facilitando a comercialização de seus produtos, fortalecendo a agricultura sustentável e o consumo consciente. A plataforma visa otimizar a logística de CSAs (Comunidade que Sustenta a Agricultura), promover a autonomia dos produtores, reduzir o desperdício de alimentos, e contribuir para a segurança alimentar, o desenvolvimento econômico local e a redução das desigualdades, utilizando tecnologia acessível e fomentando um ecossistema open source.

## Conexão com os Objetivos de Desenvolvimento Sustentável (ODS)

O AgroMart está alinhado com os seguintes ODS:

- **ODS 1 (Erradicação da Pobreza)** e **ODS 8 (Trabalho decente e crescimento Econômico)**: Promover o desenvolvimento econômico local e reduzir as desigualdades, proporcionando aos agricultores familiares uma plataforma para comercializar seus produtos diretamente aos consumidores.
- **ODS 2 (Fome Zero e Agricultura Sustentável)**: Contribuir para a segurança alimentar, reduzindo o desperdício de alimentos e promovendo práticas agrícolas sustentáveis.
- **ODS 10 (Redução das Desigualdades)**: Fomentar a autonomia dos produtores e fortalecer a agricultura familiar, reduzindo as desigualdades no acesso ao mercado.
- **ODS 12 (Consumo e Produção Responsáveis)**: Promover o consumo consciente e a produção responsável, conectando consumidores a co-agricultores e incentivando práticas sustentáveis.

## Objetivos de Medição

| Objeto | Objetivo | Enfoque de Qualidade | Ponto de Vista | Contexto |
| :------------ | :------------ | :------------ | :------------ | :------------ |
| AgroMart | Melhorar | Usabilidade | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |
| AgroMart | Garantir | Compatibilidade | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento/Testes | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |
| AgroMart | Avaliar | Funcionalidade | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento/Qualidade | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |

## Questões Objetivos de Medição

### Usabilidade

> **Questão 1:** O AgroMart oferece uma experiência de uso agradável, acessível e intuitiva para usuários com diferentes níveis de habilidade tecnológica?
>
> **Hipótese 1:** Pelo menos 90% dos usuários, independentemente do nível de familiaridade com tecnologia, conseguem concluir as principais tarefas na plataforma em menos de 2 minutos, sem assistência externa. A pontuação no questionário de atratividade e estética da interface é superior a 80%.
>
> **Métricas Relacionadas a Questão 1:**
>
> - Tempo médio para conclusão de tarefas essenciais.
> - Percentual de usuários que conseguem concluir tarefas sem solicitar ajuda (FAQ ou suporte).
> - Pontuação SUS (System Usability Scale).
> - Taxa de erro em tarefas essenciais.
> - Percentual de sessões que requerem consulta à documentação.

### Compatibilidade

> **Questão 2:** O AgroMart é capaz de coexistir de forma eficiente com outros sistemas e aplicativos que possam estar em uso no dispositivo ou no ambiente tecnológico do usuário, sem gerar conflitos, lentidão ou falhas? Além disso, o aplicativo apresenta comportamento consistente em diferentes navegadores móveis e se adapta adequadamente a diferentes tamanhos e resoluções de tela?
>
> **Hipótese 2:** O AgroMart apresenta taxa de ocorrência de conflitos, falhas ou degradação de desempenho inferior a 3% quando executado simultaneamente com outros aplicativos comuns (navegadores, apps de mensagens, planilhas, etc.) ou em ambientes com múltiplas aplicações. Não há quebras de layout significativas, perda de funcionalidade ou conteúdo sobreposto em 95% das telas ao variar a resolução entre as mais comuns de desktops (ex: 1366x768 a 1920x1080) e as de smartphones populares (ex: 360x640 a 414x896). O aplicativo é testado e ajustado para compatibilidade com os principais navegadores móveis modernos (Chrome, Firefox, Safari, Edge), garantindo que os usuários tenham a mesma experiência independente do navegador utilizado.
>
> **Métricas Relacionadas a Questão 2:**
>
> - Número de incidentes relacionados a conflitos de software reportados durante o uso simultâneo com outros sistemas/aplicativos.
> - Variação média no uso de recursos (CPU, memória, rede) quando o AgroMart é executado junto com outros aplicativos comuns.
> - Percentual de telas sem quebras de layout.
> - Taxa de funcionalidade preservada em diferentes resoluções.
> - Percentual de usuários que relatam boa legibilidade e apresentação visual em diferentes dispositivos.
> - Número de bugs específicos por navegador encontrados nos testes.
> - Número de sucessos na execução de fluxos principais em cada navegador.
> - Frequência de testes cross-browser realizados durante o desenvolvimento.

### Funcionalidade

> **Questão 3:** As funcionalidades essenciais do AgroMart (como cadastro de produtos, gestão de pedidos e comunicação entre co-agricultores e consumidores) estão completas, corretas e adequadas às necessidades dos usuários, sem apresentar erros críticos ou limitações significativas? As integrações do AgroMart com sistemas externos (como gateways de pagamento, sistemas de logística e APIs de comunicação) funcionam de forma correta e confiável?
>
> **Hipótese 3:** 95% das funcionalidades críticas estão implementadas e operacionais, com menos de 2% de erros críticos relatados em produção. As funcionalidades atendem às necessidades dos usuários sem limitações significativas. 100% das integrações críticas (pagamento, logística, comunicação) estão funcionando corretamente, com taxa de falhas inferior a 1% nas operações realizadas em ambiente de produção.
>
> **Métricas Relacionadas a Questão 3:**
>
> - Percentual de funcionalidades críticas implementadas.
> - Taxa de erros críticos relatados em produção.
> - Percentual de usuários que consideram as funcionalidades adequadas às suas necessidades.
> - Taxa de sucesso das operações realizadas via integrações externas.
> - Tempo médio de resposta das APIs externas utilizadas pela plataforma.

## Relação entre Objetivos de Medição – Questões e Métricas

| **Questão** | 📏 **Métricas Relacionadas** |
| :---------- | :--------------------------- |
| Q1: O AgroMart oferece uma experiência de uso agradável, acessível e intuitiva para usuários com diferentes níveis de habilidade tecnológica? | Tempo médio para conclusão de tarefas essenciais, Percentual de usuários que conseguem concluir tarefas sem solicitar ajuda, Pontuação SUS, Taxa de erro em tarefas essenciais, Percentual de sessões que requerem consulta à documentação. |
| Q2: O AgroMart é capaz de coexistir de forma eficiente com outros sistemas e aplicativos que possam estar em uso no dispositivo ou no ambiente tecnológico do usuário, sem gerar conflitos, lentidão ou falhas? Além disso, o aplicativo apresenta comportamento consistente em diferentes navegadores móveis e se adapta adequadamente a diferentes tamanhos e resoluções de tela? | Número de incidentes relacionados a conflitos de software, Variação média no uso de recursos, Percentual de telas sem quebras de layout, Taxa de funcionalidade preservada em diferentes resoluções, Percentual de usuários que relatam boa legibilidade e apresentação visual, Número de bugs específicos por navegador, Número de sucessos na execução de fluxos principais, Frequência de testes cross-browser. |
| Q3: As funcionalidades essenciais do AgroMart (como cadastro de produtos, gestão de pedidos e comunicação entre co-agricultores e consumidores) estão completas, corretas e adequadas às necessidades dos usuários, sem apresentar erros críticos ou limitações significativas? As integrações do AgroMart com sistemas externos (como gateways de pagamento, sistemas de logística e APIs de comunicação) funcionam de forma correta e confiável? | Percentual de funcionalidades críticas implementadas, Taxa de erros críticos relatados em produção, Percentual de usuários que consideram as funcionalidades adequadas, Taxa de sucesso das operações realizadas via integrações externas, Tempo médio de resposta das APIs externas. |

## Abstraction Sheets

### Abstraction Sheet: Usabilidade

| Header (GQM Goal) | Detalhes |
| :---------------- | :------- |
| **Objeto** | AgroMart |
| **Propósito** | Melhorar (visando facilitar a adoção e o uso eficiente por todos os perfis de usuário) |
| **Foco de Qualidade** | Usabilidade (Compreensibilidade, Apreensibilidade, Operabilidade, Atratividade, Proteção contra erro do usuário, Estética da Interface do Usuário, Acessibilidade) |
| **Ponto de Vista** | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento |
| **Contexto** | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |

| Quadrante II: Foco de Qualidade | Quadrante I: Fatores de Variação |
| :------------------------------- | :------------------------------- |
| - Compreensibilidade <br> - Apreensibilidade <br> - Operabilidade <br> - Atratividade <br> - Estética da Interface <br> - Proteção contra Erros <br> - Acessibilidade | - Nível de familiaridade tecnológica dos usuários <br> - Complexidade das tarefas <br> - Qualidade do design da interface <br> - Disponibilidade e clareza da documentação/ajuda |

| Quadrante III: Hipótese Base | Quadrante IV: Impacto dos Fatores de Variação |
| :--------------------------- | :-------------------------------------------- |
| - Maioria dos usuários conseguem concluir tarefas em menos de 2 minutos sem ajuda. <br> - Pontuação de atratividade da interface acima de 80%. <br> - Consulta à documentação é inferior a 5% das sessões. | - Plataforma intuitiva, acessível e agradável para diferentes perfis de usuário. <br> - Reduz erros operacionais e necessidade de suporte. <br> - Melhora a adoção e a eficiência no uso da plataforma. <br> - Dificuldade de uso pode levar à baixa adoção e insatisfação. |

### Abstraction Sheet: Compatibilidade

| Header (GQM Goal) | Detalhes |
| :---------------- | :------- |
| **Objeto** | AgroMart |
| **Propósito** | Garantir (a operação adequada em diferentes ambientes tecnológicos e a interoperabilidade com sistemas externos relevantes) |
| **Foco de Qualidade** | Compatibilidade (Coexistência, Interoperabilidade, Conformidade de Plataforma) |
| **Ponto de Vista** | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento/Testes |
| **Contexto** | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |

| Quadrante II: Foco de Qualidade | Quadrante I: Fatores de Variação |
| :------------------------------- | :------------------------------- |
| - Coexistência <br> - Interoperabilidade <br> - Conformidade de Plataforma <br> - Consistência em navegadores móveis <br> - Adaptação a diferentes tamanhos/resoluções de tela | - Diferenças nos motores de renderização (Blink, Gecko, WebKit). <br> - Nível de padronização do código HTML/CSS/JS. <br> - Frequência e cobertura dos testes cross-browser realizados. <br> - Variações de hardware e software nos dispositivos dos usuários. <br> - Conflitos com outros aplicativos em execução. |

| Quadrante III: Hipótese Base | Quadrante IV: Impacto dos Fatores de Variação |
| :--------------------------- | :-------------------------------------------- |
| - Taxa de conflitos, falhas ou degradação de desempenho ao usar com outros aplicativos. <br> - Funciona corretamente nos principais SOs (Windows, macOS, Android, iOS) e navegadores (Chrome, Firefox, Edge, Safari). <br> - Mantém desempenho aceitável com tempo de carregamento inferior a 2 segundos. <br> - O aplicativo segue padrões web responsivos e é testado nos navegadores móveis mais importantes. <br> - Os fluxos principais (cadastro, login, navegação) funcionam em todos os navegadores móveis modernos. | - Garante operação sem falhas, conflitos ou lentidão em diversos ambientes. <br> - Assegura interoperabilidade com sistemas externos e dispositivos variados. <br> - Melhora a satisfação do usuário em diferentes contextos tecnológicos. <br> - Bugs não tratados por navegador podem prejudicar a experiência do usuário. <br> - Falta de testes regulares pode gerar inconsistências entre navegadores. <br> - Incompatibilidades de renderização podem ocultar ou falhar funcionalidades essenciais. |

### Abstraction Sheet: Funcionalidade

| Header (GQM Goal) | Detalhes |
| :---------------- | :------- |
| **Objeto** | AgroMart |
| **Propósito** | Avaliar (a completude, correção e adequação das funcionalidades oferecidas para atender às necessidades dos usuários) |
| **Foco de Qualidade** | Funcionalidade (Adequação Funcional, Exatidão Funcional, Interoperabilidade, Conformidade Funcional) |
| **Ponto de Vista** | Usuário Final (Administrador da CSA; Co-agricultor), Equipe de Desenvolvimento/Qualidade |
| **Contexto** | Projeto AgroMart, considerando o contexto da disciplina de Qualidade de Software |

| Quadrante II: Foco de Qualidade | Quadrante I: Fatores de Variação |
| :------------------------------- | :------------------------------- |
| - Adequação Funcional <br> - Exatidão Funcional <br> - Interoperabilidade <br> - Conformidade Funcional | - Complexidade dos requisitos <br> - Qualidade da especificação <br> - Erros de implementação <br> - Mudanças nos requisitos durante o desenvolvimento <br> - Qualidade das APIs externas e sua estabilidade |

| Quadrante III: Hipótese Base | Quadrante IV: Impacto dos Fatores de Variação |
| :--------------------------- | :-------------------------------------------- |
| - Taxa das funcionalidades críticas implementadas e operacionais. <br> - Baixa porcentagem de erros críticos relatados em produção. <br> - Funcionalidades atendem às necessidades dos usuários sem limitações significativas. <br> - 100% das integrações críticas (pagamento, logística, comunicação) estão funcionando corretamente. | - Assegura que as funcionalidades essenciais sejam completas, corretas e adequadas. <br> - Garante valor aos usuários com baixo risco de falhas críticas. <br> - Promove confiança na plataforma. <br> - Falhas em funcionalidades críticas ou integrações podem inviabilizar o uso da plataforma. <br> - Funcionalidades incompletas ou incorretas geram insatisfação e retrabalho. |

## Tabela de Contribuição

| Matrícula | Nome Completo | Contribuição (%) |
| :--------: | :------------------------------------------------: | :--------------: |
| 190085584 | [Carlos Eduardo](https://github.com/CarlosEduardoMendesdeMesquita) | 16,7%  |
| 190105895 | [Eric Akio](https://github.com/eric-kingu) | 16,7% |
| 190028475 | [Gabriela Tiago](https://github.com/GabrielaTiago) | 16,7%  |
| 221008786 | [Mateus Villela](https://github.com/MVConsorte) | 16,7%  |
| 221035077 | [Raissa Andrade](https://github.com/RaissaAndradeS) | 16,7%  |
| 180108875 | [Rodrigo Mattos](https://github.com/Rodrigomfab88) | 16,7%  |

## Histórico de Versões

| Data | Versão | Descrição | Autor | Revisor |
| :--------: | :----: | :------------------------------------------------: | :---------------: | :-------------: | 
| 26/05/2025 | 1.0 | Cria base do documento de definição | [Gabriela Tiago](https://github.com/GabrielaTiago), [Mateus](https://github.com/MVConsorte) | [Mateus](https://github.com/MVConsorte) | 
| 27/05/2025 | 1.1 | Adiciona objetivos de medição e conexão com ODS | [Gabriela Tiago](https://github.com/GabrielaTiago) | [Mateus](https://github.com/MVConsorte) | 
| 28/05/2025 | 1.2 | Adiciona questões, hipóteses e métricas de medição | [Gabriela Tiago](https://github.com/GabrielaTiago) | [Mateus](https://github.com/MVConsorte) | 
| 27/05/2025 | 1.0 | Incremento do GQM - Fase de definição | [Toda a equipe](ft) |[Mateus](https://github.com/MVConsorte) | 
| 04/06/2025 | 1.3 | Incremento e aperfeiçoamento, unificação e formatação dos Abstraction Sheets e da documentação | [Mateus](https://github.com/MVConsorte) | [Raissa](https://github.com/RaissaAndradeS)  |