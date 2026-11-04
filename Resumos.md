# Aula 1 — Introdução a Requisitos de Sistemas

## 1. Requisitos de Sistemas
- São as necessidades e funcionalidades que um software deve atender.
- Devem ser identificados antes do desenvolvimento.
- Requisitos mal definidos causam erros, retrabalho, atrasos e custos adicionais.

## 2. Qualidade de Software
- É desenvolver um software que atenda aos requisitos e às necessidades do cliente.
- A qualidade deve estar presente em todas as etapas, não apenas nos testes.
- **Qualidade do processo:** como o software é desenvolvido.
- **Qualidade do produto:** se o software funciona conforme o esperado.

## 3. Garantia × Controle da Qualidade
- **Garantia da Qualidade:** busca prevenir erros, melhorando os processos.
- **Controle da Qualidade:** busca identificar erros no produto por meio de testes e inspeções.
- **Importante:** testes de software fazem parte do Controle da Qualidade.

## 4. Gerenciamento da Qualidade (PMBOK)
- **Planejamento:** define os padrões de qualidade.
- **Garantia:** assegura que os processos sejam seguidos.
- **Controle:** verifica se os resultados atendem aos padrões.

## 5. Normas ISO
- **ISO 9000:** fundamentos e conceitos de gestão da qualidade.
- **ISO 9001:** requisitos para sistemas de gestão da qualidade.


<br>
<br>
<br>


# Aula 2 — Níveis de Requisitos

## 1. Requisitos de Usuário
- Descrevem **o que o sistema deve fazer**, sem explicar como será implementado.
- Utilizam linguagem simples, acessível a clientes e usuários.
- Não envolvem detalhes técnicos ou tecnologias.

**Exemplo:** O sistema deve permitir que o cliente realize pagamentos.

## 2. Requisitos de Sistema
- Descrevem os requisitos de forma mais detalhada e técnica.
- São voltados principalmente para desenvolvedores e profissionais de TI.
- Especificam comportamentos, regras e condições necessárias para o funcionamento do sistema.

**Exemplo:** O sistema deve validar os dados do pagamento e registrar a transação no banco de dados.

## 3. Diferença Principal
- **Requisito de Usuário:** visão geral, linguagem simples, foco nas necessidades.
- **Requisito de Sistema:** visão detalhada, linguagem técnica, foco nas especificações.

<br>
<br>
<br>

  # Aula 3 – Requisitos de Sistemas

## Tipos de Requisitos

- **Requisitos Funcionais (RF):** definem O QUE o sistema deve fazer. Ex.: cadastrar usuários, consultar saldo e emitir relatórios.
- **Requisitos Não Funcionais (RNF):** definem COMO o sistema deve funcionar. Ex.: desempenho, segurança e acessibilidade.
- **Regras de Negócio (RN):** condições e restrições que o sistema deve respeitar. Ex.: impedir saques acima do saldo disponível.

## Características dos Requisitos Não Funcionais

- **Usabilidade:** facilidade de uso.
- **Confiabilidade:** estabilidade e recuperação de falhas.
- **Eficiência:** velocidade e desempenho.
- **Segurança:** proteção dos dados.
- **Manutenibilidade:** facilidade de manutenção e atualização.
- **Portabilidade:** funcionamento em diferentes ambientes.

## Exemplo Prático

Sistema bancário:
- **RF:** permitir consultar o saldo.
- **RNF:** exibir o saldo em até 3 segundos.
- **RN:** não permitir saques superiores ao saldo.

## Resumo para a Prova

- **RF = O QUE o sistema faz.**
- **RNF = COMO o sistema funciona.**
- **RN = REGRAS que devem ser respeitadas.**
- Requisitos devem ser **claros, completos, consistentes e verificáveis**.
- Requisitos não funcionais devem possuir **métricas mensuráveis**, como tempo de resposta.

  <br>
<br>
<br>

# Aula 4 – Identificação de Stakeholders

## 1. O que são Stakeholders?

São todas as pessoas, grupos ou entidades que possuem interesse ou são afetados direta ou indiretamente por um sistema.

### Exemplos:
- **Gerente de Projeto:** organiza e supervisiona o projeto.
- **Analista de Sistemas:** identifica e analisa os requisitos.
- **Programador:** desenvolve o software.
- **Patrocinador:** financia o projeto.
- **Cliente/Usuário:** solicita ou utiliza o sistema.

**Importante:** identificar incorretamente os stakeholders pode gerar requisitos incompletos, retrabalho e prejuízos.

## 2. Levantamento de Requisitos

Processo de identificar as necessidades dos usuários e definir o que o sistema deve fazer.

### Principais Técnicas

- **Etnografia:** observação do ambiente e da rotina dos usuários.
- **Entrevistas:** conversas para identificar necessidades e expectativas.
- **Questionários:** coleta de informações de vários usuários, especialmente em locais diferentes.
- **Brainstorming:** geração coletiva de ideias.
- **Prototipagem:** criação de versões simplificadas do sistema para validar requisitos.
- **JAD (Joint Application Design):** reuniões estruturadas entre usuários e desenvolvedores para definir requisitos em conjunto.
- **Workshops:** encontros colaborativos para discutir necessidades do sistema.

## 3. Pontos Importantes para a Prova

- **Stakeholder:** qualquer interessado ou afetado pelo sistema.
- **Levantamento de requisitos:** deve acontecer antes da programação.
- **Entrevista:** ideal para obter informações diretamente dos usuários.
- **Questionário:** útil quando existem muitos usuários.
- **Etnografia:** baseada na observação.
- **Brainstorming:** geração de ideias.
- **Prototipagem:** ajuda a identificar erros e reduzir riscos.
- **JAD:** colaboração entre usuários e desenvolvedores.
- Requisitos devem ser **claros, consistentes e revisados** para evitar falhas no projeto.



<br>
<br>
<br>

# Aula 5 – Documentação de Requisitos de Software

## 1. O que é o Documento de Requisitos (SRS)?

- **SRS (Software Requirements Specification):** documento oficial que descreve o que o sistema deve implementar.
- Registra os requisitos levantados e orienta o desenvolvimento.
- Serve como referência para desenvolvedores, clientes, testadores e manutenção.
- Ajuda a evitar erros, retrabalho e falhas de comunicação.

## 2. Objetivo e Importância

- Definir claramente o que será desenvolvido.
- Garantir que o software atenda às necessidades do cliente.
- Facilitar a comunicação entre os envolvidos.
- Apoiar o desenvolvimento, os testes e futuras manutenções.

**Importante:** o documento deve ser claro, organizado, compreensível e adequado ao público.

## 3. Quem Utiliza o Documento?

- **Clientes:** verificam se os requisitos atendem às necessidades.
- **Gerentes:** planejam o projeto e seu desenvolvimento.
- **Engenheiros de Sistemas:** compreendem o funcionamento esperado.
- **Engenheiros de Testes:** elaboram testes de validação.
- **Engenheiros de Manutenção:** entendem o sistema para realizar alterações.

## 4. Estrutura do Documento de Requisitos

- **Prefácio:** público-alvo e histórico de versões.
- **Introdução:** objetivos, necessidades e funções do sistema.
- **Glossário:** explicação dos termos técnicos.
- **Requisitos de Usuário:** serviços oferecidos e requisitos não funcionais.
- **Modelos do Sistema:** diagramas e relacionamentos entre componentes.
- **Evolução do Sistema:** possíveis mudanças e melhorias futuras.
- **Apêndices:** informações adicionais, como hardware e banco de dados.
- **Índice:** facilita a localização das informações.

## 5. Resumo para a Prova

- **SRS = Documento oficial de especificação dos requisitos.**
- Define o que deve ser implementado no software.
- Deve ser **claro, organizado, preciso e compreensível**.
- É utilizado por clientes, gerentes, desenvolvedores, testadores e manutenção.
- Serve como referência durante o desenvolvimento e após a entrega.
- Sua estrutura **não é fixa**, podendo ser adaptada conforme o projeto.

- 
<br>
<br>
<br>

# Aula 6 – Engenharia de Requisitos e Estudos de Viabilidade

## 1. Engenharia de Requisitos

- Processo responsável por identificar, analisar, definir e documentar os requisitos de um software.
- Seu objetivo é garantir que o sistema atenda às necessidades dos usuários.
- Foca principalmente em **O QUE o sistema deve fazer**, e não em como será programado.
- Ajuda a evitar erros, retrabalho e desenvolvimento de funcionalidades desnecessárias.

## 2. Etapas da Engenharia de Requisitos

1. **Estudo de Viabilidade:** verifica se o projeto pode e vale a pena ser desenvolvido.
2. **Análise de Requisitos:** identifica as necessidades dos stakeholders.
3. **Definição de Requisitos:** determina quais requisitos serão implementados.
4. **Especificação de Requisitos:** documenta detalhadamente os requisitos definidos.

**Importante:** o processo é iterativo, permitindo retornar às etapas anteriores para corrigir erros ou ajustar requisitos.

## 3. Estudo de Viabilidade

- Avalia se o projeto é possível e se traz benefícios para a organização.
- É realizado antes do desenvolvimento do software.
- Pode resultar na aprovação, alteração ou cancelamento do projeto.

### Principais Tipos de Viabilidade

- **Técnica:** existem tecnologias e recursos para desenvolver o sistema?
- **Econômica:** os custos são justificáveis pelos benefícios?
- **Operacional/Organizacional:** o sistema atende aos objetivos da empresa?
- **Temporal:** é possível concluir o projeto dentro do prazo?

## 4. Stakeholders e Relatório de Viabilidade

- Os stakeholders fornecem informações sobre necessidades, custos, recursos e limitações.
- O estudo gera um **relatório de viabilidade**, apresentando conclusões e justificativas.
- Esse relatório ajuda a decidir se o projeto deve continuar.

## 5. Resumo para a Prova

- **Engenharia de Requisitos = identificar, analisar, definir e documentar necessidades.**
- **Estudo de Viabilidade = verificar se o projeto é possível e vantajoso.**
- A viabilidade deve ser analisada **antes da programação**.
- Um projeto pode ser cancelado ainda na fase de viabilidade.
- O sistema deve contribuir para os **objetivos da organização**.
- O processo de engenharia de requisitos é **iterativo**, permitindo revisões.
- O relatório de viabilidade orienta a decisão de continuar ou não o projeto.

