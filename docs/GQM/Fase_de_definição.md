# Fase Definição

## Objetivo de negócio do Agromart
Garantir que a aplicação Agromart funcione de maneira eficaz em diferentes ambientes de hardware, sistemas operacionais, navegadores e dispositivos móveis, promovendo uma experiência consistente para todos os usuários.

## Questões Objetivo de Medição 1

### **Q1:** O aplicativo apresenta comportamento consistente em diferentes navegadores móveis?

#### Hipótese Q1:
O aplicativo é testado e ajustado para compatibilidade com os principais navegadores móveis modernos (Chrome, Firefox, Safari, Edge), garantindo que os usuários tenham a mesma experiência independente do navegador utilizado.

#### Métricas para Q1:

- **M1.1:** Número de bugs específicos por navegador encontrados nos testes.
- **M1.2:** Número de sucessos na execução de fluxos principais em cada navegador.
- **M1.3:** Frequência de testes cross-browser realizados durante o desenvolvimento.

---

## Abstraction Sheets

### Tabela 1 – Perspectiva da Análise

| **Objeto**     | **Propósito**                          | **Foco de Qualidade**              | **Ponto de Vista**         |
|----------------|-----------------------------------------|------------------------------------|-----------------------------|
| Aplicativo     | Avaliar consistência de funcionamento   | Compatibilidade entre navegadores  | Equipe de desenvolvimento   |

---

### Tabela 2 – Foco e Fatores de Variação

| **Foco de Qualidade**                                                                   | **Fatores de Variação**                                                 |
|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| ● O aplicativo deve funcionar de forma consistente nos principais navegadores móveis.   | ● Diferenças nos motores de renderização (Blink, Gecko, WebKit).        |
| ● Fluxos principais devem ser executáveis em todos os navegadores suportados.          | ● Nível de padronização do código HTML/CSS/JS.                          |
| ● Testes de compatibilidade devem ser frequentes e bem distribuídos.                   | ● Frequência e cobertura dos testes cross-browser realizados.           |

---

### Tabela 3 – Hipóteses Base e Impacto dos Fatores de Variação

| **Hipóteses Base (estimativas)**                                                                                   | **Impacto dos Fatores de Variação**                                                                    |
|---------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| ● O aplicativo segue padrões web responsivos e é testado nos navegadores móveis mais importantes. (**Q1**)          | ● Bugs não tratados por navegador podem prejudicar a experiência do usuário.<br>● Falta de testes regulares pode gerar inconsistências entre navegadores. |
| ● Os fluxos principais (cadastro, login, navegação) funcionam em todos os navegadores móveis modernos. (**M1.2**)  | ● Incompatibilidades de renderização podem ocultar ou falhar funcionalidades essenciais.               |
| ● Testes cross-browser são planejados durante o ciclo de desenvolvimento. (**M1.3**)                                | ● Baixa frequência de testes pode permitir a propagação de falhas específicas por navegador.           |

---

## Relação entre Objetivos de Medição – Questões e Métricas

| **Questão**                                                                 | 📏 **Métricas Relacionadas**                                      |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------|
| Q1: O aplicativo apresenta comportamento consistente em diferentes navegadores móveis? | M1.1 – Bugs por navegador<br>M1.2 – Sucesso em fluxos<br>M1.3 – Frequência de testes cross-browser |

---


## Tabela de contribuições

| Matrícula       | Nome Completo                          | Contribuição (%) |
|-----------------|----------------------------------------|------------------|
|    | Carlos Eduardo |              |
|     |        Eric Akio             |              |
|       |     Gabriela Tiago      |              |
|        |      Mateus Villela  |               |
|   221035077     |   Raissa Andrade    |               |
|        |     Rodrigo Mattos      |               |

## Histórico de Versões


| Data       | Versão | Descrição                                 | Autor             | Data de revisão |Revisor           | 
| :--------: | :----: | :----------:                              | :---------------:|:----: | :---------------: |
| 27/05/2025 |  1.0   | GQM - Fase de definição  | [Raissa](https://github.com/RaissaAndradeS)|  | |
