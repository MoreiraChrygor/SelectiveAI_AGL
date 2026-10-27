
# SelectiveAI_AGL

**Sistema experimental de seleção e classificação de dados utilizando algoritmos desenvolvidos em C.**

O SelectiveAI_AGL é um projeto de software desenvolvido em C, utilizando o TCC (*Tiny C Compiler*), com foco na seleção, análise e classificação de dados por meio de algoritmos simples.

Este documento segue uma estrutura baseada em **Project Charter (Termo de Abertura do Projeto)** e **WBS/EAP (Work Breakdown Structure / Estrutura Analítica do Projeto)**, incluindo objetivos, escopo, entregáveis, riscos, cronograma de marcos e acompanhamento do desenvolvimento.

---

# 1. Project Charter — Termo de Abertura

## 1.1. Identificação do projeto

| Campo | Descrição |
|---|---|
| Nome | SelectiveAI_AGL |
| Categoria | Inteligência Artificial / Software |
| Linguagem | C |
| Compilador | TCC (Tiny C Compiler) |
| Repositório | [GitHub](https://github.com/MoreiraChrygor/SelectiveAI_AGL) |
| Responsável | Mantenedor do repositório |
| Status | Em desenvolvimento |
| Licença | MIT |

## 1.2. Visão do projeto

Desenvolver um sistema leve, implementado em C, capaz de processar informações e executar operações de seleção e classificação de dados por meio de algoritmos próprios.

O projeto busca explorar os fundamentos da inteligência artificial e estabelecer uma base para a implementação e evolução de uma rede neural desenvolvida do zero.

## 1.3. Justificativa

O projeto tem como finalidade explorar os conceitos fundamentais da inteligência artificial sem depender inicialmente de frameworks especializados.

A implementação em C permite trabalhar diretamente com estruturas de dados, operações matemáticas, gerenciamento de memória e organização de algoritmos.

## 1.4. Objetivo geral

Implementar e evoluir um sistema em C capaz de receber dados, processá-los e produzir resultados de seleção ou classificação de acordo com uma lógica algorítmica definida.

## 1.5. Objetivos específicos

- Desenvolver a estrutura básica do sistema em C.
- Definir como os dados serão recebidos, armazenados e processados.
- Implementar algoritmos de seleção e classificação.
- Investigar componentes de redes neurais, conforme a implementação evoluir.
- Criar testes para verificar o comportamento do sistema.
- Documentar a arquitetura e o funcionamento.
- Estabelecer uma base para futuras otimizações.

## 1.6. Escopo do projeto

### Incluído no escopo

- Desenvolvimento de software em C.
- Compilação utilizando o TCC.
- Processamento de dados de entrada.
- Implementação de lógica de seleção e classificação.
- Testes funcionais e validação dos resultados.
- Documentação técnica.
- Evolução incremental do sistema.

### Fora do escopo inicial

- Interface gráfica avançada.
- Treinamento distribuído de modelos.
- Integração obrigatória com serviços externos.
- Dependência de frameworks complexos de inteligência artificial.
- Garantia de desempenho superior a bibliotecas consolidadas.

## 1.7. Entregáveis

| ID | Entregável | Critério de aceitação |
|---|---|---|
| D01 | Estrutura do projeto | Código organizado e compilável |
| D02 | Entrada de dados | Formato de entrada documentado |
| D03 | Algoritmo de seleção | Resultados compatíveis com os critérios definidos |
| D04 | Algoritmo de classificação | Resultados verificáveis |
| D05 | Testes funcionais | Casos de teste executados |
| D06 | Documentação | Instruções de compilação e execução |
| D07 | Validação final | Funcionalidades verificadas |

## 1.8. Critérios de sucesso

- O código pode ser compilado no ambiente documentado.
- Os dados de entrada são processados corretamente.
- A seleção produz resultados coerentes com as regras estabelecidas.
- A classificação pode ser verificada por testes.
- Os erros de entrada conhecidos são tratados adequadamente.
- A documentação permite reproduzir a execução do sistema.

## 1.9. Premissas e restrições

### Premissas

- O desenvolvimento prioriza a linguagem C.
- O TCC é o compilador de referência.
- O projeto será desenvolvido de maneira incremental.
- Os resultados serão avaliados por testes reproduzíveis.

### Restrições

- A compatibilidade depende dos recursos suportados pelo compilador.
- A qualidade da classificação depende dos dados e do algoritmo utilizado.
- O desempenho deverá ser medido antes de qualquer comparação.
- A implementação de uma rede neural deverá ser confirmada pela análise do código.

## 1.10. Riscos do projeto

| ID | Risco | Mitigação |
|---|---|---|
| R01 | Classificações inconsistentes | Criar testes com entradas conhecidas |
| R02 | Erros de gerenciamento de memória | Validar alocações e liberações |
| R03 | Incompatibilidade de compilação | Testar com a versão documentada do TCC |
| R04 | Dados inválidos | Implementar validação das entradas |
| R05 | Escopo excessivo | Priorizar entregas incrementais |
| R06 | Falta de métricas de desempenho | Criar testes e benchmarks reproduzíveis |

---

# 2. WBS/EAP — Estrutura Analítica do Projeto

A WBS (*Work Breakdown Structure*), também conhecida como EAP (*Estrutura Analítica do Projeto*), divide o projeto em componentes menores e organizados hierarquicamente.

## 2.1. Estrutura hierárquica

```text
0. SelectiveAI_AGL
|
+-- 1. Planejamento e requisitos
|   +-- 1.1 Definir objetivos
|   +-- 1.2 Definir escopo
|   +-- 1.3 Especificar entradas e saídas
|   +-- 1.4 Definir critérios de sucesso
|
+-- 2. Arquitetura e estrutura
|   +-- 2.1 Organizar o código-fonte
|   +-- 2.2 Definir estruturas de dados
|   +-- 2.3 Definir fluxo de processamento
|   +-- 2.4 Estabelecer tratamento de erros
|
+-- 3. Processamento de dados
|   +-- 3.1 Receber dados de entrada
|   +-- 3.2 Validar dados
|   +-- 3.3 Preparar dados para processamento
|
+-- 4. Seleção e classificação
|   +-- 4.1 Implementar seleção
|   +-- 4.2 Implementar classificação
|   +-- 4.3 Avaliar resultados
|   +-- 4.4 Investigar componentes de rede neural
|
+-- 5. Testes e validação
|   +-- 5.1 Testar compilação
|   +-- 5.2 Testar entradas válidas
|   +-- 5.3 Testar entradas inválidas
|   +-- 5.4 Validar resultados
|   +-- 5.5 Avaliar desempenho
|
+-- 6. Documentação
|   +-- 6.1 Documentar arquitetura
|   +-- 6.2 Documentar compilação e execução
|   +-- 6.3 Documentar exemplos
|   +-- 6.4 Atualizar README
|
+-- 7. Entrega e evolução
    +-- 7.1 Revisar critérios de aceitação
    +-- 7.2 Consolidar versão funcional
    +-- 7.3 Registrar limitações conhecidas
    +-- 7.4 Planejar próximas versões
```

## 2.2. Dicionário da WBS

| Código | Pacote de trabalho | Resultado esperado |
|---|---|---|
| 1.1 | Definição de objetivos | Objetivos documentados |
| 1.3 | Especificação de dados | Contrato de entrada e saída |
| 2.2 | Estruturas de dados | Representação definida |
| 3.2 | Validação de dados | Entradas inválidas identificadas |
| 4.1 | Seleção | Algoritmo verificável |
| 4.2 | Classificação | Resultados verificáveis |
| 4.4 | Rede neural | Componentes definidos e implementados, se aplicável |
| 5.4 | Validação de resultados | Evidências dos testes |
| 6.2 | Instruções de execução | Guia reproduzível |
| 7.2 | Consolidação | Versão funcional validada |

---

# 3. Status do projeto

## 3.1. Legenda

- [x] Concluído: implementado e verificado.
- [/] Em andamento: trabalho iniciado.
- [ ] Pendente: trabalho previsto.
- [?] A validar: situação que precisa ser verificada.
- [-] Bloqueado: depende de uma condição não resolvida.

## 3.2. Acompanhamento das atividades

| WBS | Atividade | Status inicial | Evidência necessária |
|---|---|---|---|
| 1.0 | Planejamento e requisitos | [/] Em andamento | Objetivos e escopo documentados |
| 2.0 | Arquitetura e estrutura | [?] A validar | Inspeção dos arquivos-fonte |
| 3.0 | Processamento de dados | [?] A validar | Testes de entrada e processamento |
| 4.0 | Seleção e classificação | [?] A validar | Código e resultados de execução |
| 5.0 | Testes e validação | [ ] Pendente | Casos de teste documentados |
| 6.0 | Documentação técnica | [/] Em andamento | README e instruções atualizados |
| 7.0 | Entrega e evolução | [ ] Pendente | Critérios de aceitação atendidos |

**Nota:** os status representam uma proposta inicial de planejamento e não uma auditoria completa do código. Atualize-os com base nas funcionalidades verificadas e nos testes executados.

## 3.3. Marcos do projeto

| Marco | Descrição | Critério de conclusão |
|---|---|---|
| M1 | Requisitos definidos | Objetivos e escopo documentados |
| M2 | Estrutura estabelecida | Código organizado e compilação verificada |
| M3 | Processamento implementado | Entrada e processamento validados |
| M4 | Classificação validada | Resultados conferidos por testes |
| M5 | Documentação consolidada | Instruções reproduzíveis disponíveis |
| M6 | Versão funcional | Critérios de aceitação atendidos |

---

# 4. Plano de execução

## Fase 1 — Planejamento

- [ ] Definir requisitos funcionais.
- [ ] Identificar o formato dos dados.
- [ ] Estabelecer os critérios de classificação.
- [ ] Definir como os resultados serão avaliados.

**Entrega:** especificação inicial do sistema.

## Fase 2 — Implementação

- [ ] Organizar estruturas e funções em C.
- [ ] Desenvolver ou revisar o processamento de dados.
- [ ] Implementar a lógica de seleção e classificação.
- [ ] Avaliar os componentes necessários para uma rede neural.

**Entrega:** funcionalidades implementadas.

## Fase 3 — Verificação

- [ ] Compilar o projeto com o TCC.
- [ ] Executar testes com entradas conhecidas.
- [ ] Verificar resultados incorretos e casos extremos.
- [ ] Corrigir erros identificados.
- [ ] Medir o desempenho, quando aplicável.

**Entrega:** evidências de funcionamento e limitações documentadas.

## Fase 4 — Documentação e entrega

- [ ] Documentar a arquitetura e os algoritmos.
- [ ] Adicionar exemplos de entrada e saída.
- [ ] Registrar instruções de compilação.
- [ ] Revisar os critérios de aceitação.
- [ ] Consolidar o histórico de alterações.

**Entrega:** versão documentada e reproduzível.

---

# 5. Requisitos do sistema

## 5.1. Requisitos funcionais

| ID | Requisito | Prioridade |
|---|---|---|
| RF01 | Receber dados no formato especificado | Alta |
| RF02 | Validar os dados de entrada | Alta |
| RF03 | Processar dados conforme o algoritmo definido | Alta |
| RF04 | Selecionar dados segundo critérios estabelecidos | Alta |
| RF05 | Classificar dados conforme a lógica implementada | Alta |
| RF06 | Apresentar ou registrar resultados | Média |
| RF07 | Permitir a reprodução dos testes | Alta |

## 5.2. Requisitos não funcionais

| ID | Requisito | Critério |
|---|---|---|
| RNF01 | Portabilidade | Compilação no ambiente documentado |
| RNF02 | Manutenibilidade | Código organizado e responsabilidades claras |
| RNF03 | Confiabilidade | Resultados verificáveis em testes |
| RNF04 | Gerenciamento de memória | Alocações e liberações tratadas corretamente |
| RNF05 | Desempenho | Medido por testes reproduzíveis |
| RNF06 | Documentação | Instruções de execução reproduzíveis |

---

# 6. Métricas de acompanhamento

O progresso deve ser avaliado por entregas verificáveis, e não apenas pela quantidade de código escrito.

| Métrica | Forma de avaliação |
|---|---|
| Progresso da WBS | Pacotes concluídos em relação ao total |
| Compilação | Resultado no ambiente documentado |
| Cobertura funcional | Requisitos testados |
| Qualidade da classificação | Métricas adequadas ao problema |
| Confiabilidade | Testes aprovados e falhas identificadas |
| Documentação | Etapas reproduzidas por outra pessoa |

Se houver uma rede neural efetivamente implementada, poderão ser adicionadas métricas como acurácia, precisão, recall, F1-score e tempo de inferência.

---

# 7. Governança e controle de mudanças

- Cada funcionalidade deve possuir um objetivo identificável.
- Alterações relevantes devem ser registradas no histórico do Git.
- Correções devem ser acompanhadas de testes, quando aplicável.
- Mudanças no escopo devem atualizar a WBS e os critérios de aceitação.
- Os status devem refletir evidências reais de implementação e validação.

## 7.1. Critérios para concluir uma tarefa

Uma tarefa poderá ser marcada como concluída quando:

1. A implementação prevista estiver presente.
2. O código compilar no ambiente aplicável.
3. Os testes definidos forem executados.
4. Os resultados atenderem aos critérios de aceitação.
5. A documentação correspondente estiver atualizada, quando necessária.

---

# 8. Próximas etapas

- [ ] Revisar os arquivos-fonte e identificar as funcionalidades existentes.
- [ ] Confirmar o algoritmo utilizado atualmente.
- [ ] Documentar o formato de entrada e saída.
- [ ] Criar testes reproduzíveis de seleção e classificação.
- [ ] Confirmar a compatibilidade com o TCC.
- [ ] Atualizar os status da WBS com base em evidências.
- [ ] Definir uma versão funcional e seus critérios de aceitação.

---

# 9. Licença

Este projeto utiliza a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter informações sobre os termos de uso, modificação e distribuição.

---

# 10. Referências

- [Repositório SelectiveAI_AGL](https://github.com/MoreiraChrygor/SelectiveAI_AGL)
- [Project Management Institute — PMI](https://www.pmi.org/)
- [Tiny C Compiler — TCC](https://bellard.org/tcc/)

---

**SelectiveAI_AGL — desenvolvimento experimental de algoritmos de seleção e classificação em C.**
