
# REQUISITOS DE SISTEMAS — REVISÃO FINAL PARA PROVA

## 1. Conceitos e Tipos de Requisitos

- **Requisitos:** necessidades e condições que o software deve atender.
- **Requisitos de Usuário:** descrição geral, em linguagem simples.
- **Requisitos de Sistema:** descrição detalhada e técnica.

### Tipos
- **Funcionais (RF):** O QUE o sistema faz. Ex.: cadastrar produtos, criar tarefas e gerar relatórios.
- **Não Funcionais (RNF):** COMO o sistema funciona. Ex.: segurança, velocidade, usabilidade e compatibilidade.
- **Regras de Negócio (RN):** restrições que o sistema deve respeitar. Ex.: impedir saque maior que o saldo.

### Principais RNF
- **Usabilidade:** facilidade de uso.
- **Desempenho:** velocidade de resposta.
- **Segurança:** proteção das informações.
- **Portabilidade:** funcionamento em diferentes plataformas, como Android e iOS.
- **Confiabilidade:** funcionamento estável.
- **Manutenibilidade:** facilidade de realizar alterações.

## 2. Stakeholders e Elicitação

**Stakeholders:** pessoas ou grupos interessados ou afetados pelo sistema.

- **Usuários finais:** informam necessidades e dificuldades.
- **Gerentes:** planejam e acompanham o projeto.
- **Desenvolvedores:** implementam as funcionalidades.
- **Patrocinadores:** financiam o projeto.
- **Testadores:** verificam o atendimento aos requisitos.

**Elicitação:** descobrir e compreender as necessidades reais dos usuários.

### Técnicas importantes
- **Entrevista:** conversa direta com usuários.
- **Questionário:** ideal para muitos usuários.
- **Etnografia:** observar a rotina dos usuários.
- **Brainstorming:** geração coletiva de ideias.
- **Prototipagem:** modelo inicial para receber feedback.
- **JAD/Workshops:** reuniões colaborativas.
- **Análise documental:** estudo dos documentos existentes.

### Problemas da Elicitação
- **Escopo:** dificuldade em definir limites do sistema.
- **Compreensão:** informações confusas ou incompletas.
- **Volatilidade:** requisitos que mudam constantemente.

## 3. Engenharia de Requisitos

Processo de identificar, analisar, documentar e validar as necessidades de um sistema.

### Principais etapas
1. **Viabilidade:** verificar se o projeto é possível e vantajoso.
2. **Elicitação:** descobrir necessidades dos stakeholders.
3. **Análise:** avaliar, organizar e definir requisitos.
4. **Especificação:** documentar os requisitos.
5. **Validação:** verificar se atendem às necessidades.
6. **Gerenciamento:** controlar alterações nos requisitos.

**Importante:** o processo é iterativo, podendo retornar às etapas anteriores.

### Estudo de Viabilidade
- **Técnica:** existem recursos e tecnologias?
- **Econômica:** os benefícios justificam os custos?
- **Operacional:** atende aos objetivos da organização?
- **Temporal:** é possível concluir dentro do prazo?

## 4. Documento de Requisitos (SRS)

- Documento oficial que descreve o que o sistema deve implementar.
- Orienta desenvolvimento, testes e manutenção.
- Deve ser claro, completo, consistente e compreensível.

### Utilização
- **Clientes:** verificam se atende às necessidades.
- **Gerentes:** planejam o desenvolvimento.
- **Engenheiros de sistemas:** compreendem o funcionamento.
- **Testadores:** elaboram testes de validação.
- **Manutenção:** consulta para futuras alterações.

## 5. Validação de Requisitos

**Objetivo:** verificar se os requisitos estão corretos e atendem às necessidades do cliente.

### Critérios
- **Completude:** não faltam requisitos.
- **Consistência:** não existem contradições.
- **Clareza:** requisitos sem ambiguidades.
- **Viabilidade:** possibilidade de implementação.
- **Testabilidade:** possibilidade de verificar os resultados.
- **Conformidade:** atendimento aos padrões definidos.

### Técnicas
- **Revisão:** analisar documentos e encontrar inconsistências.
- **Prototipagem:** permitir avaliação antecipada pelos usuários.
- **Testes de requisitos:** verificar se os requisitos podem ser testados.

**Importante:** identificar erros antes da implementação reduz custos e retrabalho.

## 6. Gerenciamento de Requisitos

**Objetivo:** acompanhar, avaliar e controlar alterações nos requisitos.

- **Baseline:** versão de referência dos requisitos.
- **Rastreabilidade:** identificar relações e dependências entre requisitos.
- **Controle de mudanças:** registrar, analisar e acompanhar alterações.
- **Identificação única:** código exclusivo para cada requisito.

### Gerenciamento de Mudanças
1. **Análise do problema:** identificar a necessidade de mudança.
2. **Análise da mudança:** avaliar impactos, custos e aprovação.
3. **Implementação:** atualizar os requisitos e o sistema.

**Importante:** mudanças podem afetar custos, prazos e outros requisitos. Não devem ser implementadas sem avaliação.

## 7. Casos de Uso e UML

- **Caso de Uso:** funcionalidade do sistema vista pelo usuário.
- **Ator:** pessoa ou outro sistema que interage com o software.
- **UML:** linguagem padronizada para modelar sistemas.

### Elementos do Diagrama
- **Boneco:** ator.
- **Elipse:** caso de uso.
- **Linha:** associação.
- **Retângulo:** limite do sistema.

### Relacionamentos
- **Include:** comportamento obrigatório.
- **Extend:** comportamento opcional ou condicional.
- **Generalização:** herança de funcionalidades.

## 8. Qualidade de Software

- **Qualidade:** atender aos requisitos e necessidades do cliente.
- **Garantia da Qualidade:** prevenir erros por meio de processos.
- **Controle da Qualidade:** identificar erros com testes e inspeções.
- **ISO 9000:** conceitos e fundamentos da qualidade.
- **ISO 9001:** requisitos para gestão da qualidade.

---

## PEGADINHAS IMPORTANTES PARA A PROVA

- Criar tarefas, cadastrar produtos e emitir relatórios = **FUNCIONAIS**.
- Segurança, rapidez, acessibilidade e compatibilidade = **NÃO FUNCIONAIS**.
- Muitos usuários para consultar = **QUESTIONÁRIOS**.
- Observar usuários trabalhando = **ETNOGRAFIA**.
- Testar ideias com modelo inicial = **PROTOTIPAGEM**.
- Descobrir necessidades = **ELICITAÇÃO**.
- Documentar requisitos = **ESPECIFICAÇÃO**.
- Conferir se os requisitos atendem ao cliente = **VALIDAÇÃO**.
- Avaliar se o projeto compensa = **VIABILIDADE**.
- Avaliar impacto de alterações = **GERENCIAMENTO DE MUDANÇAS**.
- Stakeholders mal identificados = **REQUISITOS INADEQUADOS E RETRABALHO**.
- Include = **OBRIGATÓRIO**; Extend = **OPCIONAL**.
