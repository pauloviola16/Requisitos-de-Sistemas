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

- 
<br>
<br>
<br>

# Aula 7 – Elicitação de Requisitos

## 1. O que é Elicitação de Requisitos?

- Processo de descobrir e compreender as reais necessidades dos usuários e stakeholders.
- Busca identificar requisitos explícitos e necessidades que o cliente ainda não conseguiu expressar.
- Seu objetivo é entender **O QUE o cliente realmente precisa**.
- É mais abrangente que o simples levantamento de requisitos.

## 2. Etapas da Elicitação

1. **Preparação:** planejar as atividades e identificar os envolvidos.
2. **Condução:** coletar informações e descobrir necessidades.
3. **Documentação:** registrar os requisitos identificados.
4. **Confirmação:** validar as informações com os stakeholders.

**Importante:** a elicitação é um processo iterativo, podendo ocorrer novamente durante o projeto.

## 3. Técnicas de Elicitação

- **Entrevistas:** conversas diretas com usuários.
- **Questionários:** coleta de informações de várias pessoas.
- **Observação/Etnografia:** acompanhar a rotina dos usuários.
- **Brainstorming:** geração coletiva de ideias.
- **Prototipagem:** criar modelos para esclarecer necessidades.
- **Workshops:** reuniões colaborativas.
- **Análise Documental:** estudar documentos e processos existentes.

## 4. Principais Problemas da Elicitação

- **Problemas de Escopo:** dificuldade em definir os limites e funcionalidades do sistema.
- **Problemas de Compreensão:** informações incompletas, dúvidas ou falhas de comunicação.
- **Problemas de Volatilidade:** requisitos que mudam constantemente.

## 5. Resultados da Elicitação

- Identificação das necessidades e objetivos do negócio.
- Definição do escopo do sistema.
- Lista de requisitos e regras de negócio.
- Identificação dos stakeholders envolvidos.
- Criação de cenários de uso e possíveis modelos do sistema.
- Revisão e confirmação das informações coletadas.

## 6. Resumo para a Prova

- **Elicitação = descobrir as necessidades reais do cliente.**
- É mais abrangente que apenas perguntar o que o cliente deseja.
- Envolve **preparação, condução, documentação e confirmação**.
- Utiliza técnicas como entrevistas, observação e prototipagem.
- Principais problemas: **escopo, compreensão e volatilidade**.
- É um processo **iterativo**, pois os requisitos podem mudar.
- Requisitos mal identificados geram retrabalho, custos e falhas no software.
- 
<br>
<br>
<br>

# Aula 8 – Validação de Requisitos

## 1. O que é Validação de Requisitos?

- Processo que verifica se os requisitos identificados realmente atendem às necessidades do cliente.
- Busca encontrar erros, inconsistências e informações incompletas antes do desenvolvimento.
- Garante que os requisitos estejam claros, corretos e bem definidos.
- Corrigir erros nessa etapa é mais barato do que após a implementação.

## 2. O que é Verificado na Validação?

- **Completude:** todos os requisitos necessários foram identificados?
- **Consistência:** existem requisitos contraditórios?
- **Clareza:** os requisitos estão livres de ambiguidades?
- **Viabilidade:** os requisitos são realistas e possíveis de implementar?
- **Conformidade:** seguem os padrões e normas de qualidade?
- **Testabilidade:** é possível verificar se cada requisito foi atendido?

## 3. Principais Técnicas de Validação

### Revisão de Requisitos
- Análise sistemática dos requisitos para identificar erros e inconsistências.
- Envolve representantes do cliente e da equipe de desenvolvimento.
- Utiliza reuniões, documentos e checklists.

### Prototipagem
- Criação de modelos do sistema para demonstrar seu funcionamento.
- Permite que usuários identifiquem problemas antes da implementação.
- Facilita a compreensão e a validação dos requisitos.

### Testes de Requisitos
- Verificam se os requisitos podem ser testados no sistema final.
- Cada requisito funcional deve permitir a definição de um ou mais testes.
- Requisitos difíceis ou impossíveis de testar devem ser revisados.

## 4. Entradas e Saídas da Validação

- **Entradas:** requisitos levantados, normas de qualidade e experiências anteriores.
- **Processamento:** análise e validação dos requisitos.
- **Saídas:** lista de problemas identificados e ações para correção.

## 5. Resumo para a Prova

- **Validação = verificar se os requisitos estão corretos e atendem ao cliente.**
- Identifica erros antes que cheguem ao desenvolvimento.
- Principais técnicas: **revisão, prototipagem e testes de requisitos**.
- Requisitos devem ser **claros, completos, consistentes, viáveis e testáveis**.
- A prototipagem facilita a identificação visual de problemas.
- Quanto mais tarde um erro for identificado, **maior será o custo de correção**.
- A validação reduz retrabalho, custos e riscos no projeto.


<br>
<br>
<br>

# Aula 9 – Gerenciamento de Requisitos

## 1. O que é Gerenciamento de Requisitos?

- Processo responsável por acompanhar, controlar e documentar mudanças nos requisitos de um software.
- Garante que alterações sejam avaliadas antes de serem implementadas.
- Evita inconsistências, retrabalho e problemas no desenvolvimento.
- **Importante:** os requisitos podem mudar durante todo o ciclo de vida do sistema.

## 2. Por que os Requisitos Mudam?

- Novas necessidades identificadas pelos usuários.
- Mudanças nos objetivos e prioridades da empresa.
- Novas tecnologias, equipamentos ou integrações.
- Alterações em leis e regulamentações.
- Melhor compreensão das necessidades do sistema.

## 3. Conceitos Importantes

- **Baseline (Linha de Base):** versão de referência dos requisitos em determinado momento.
- **Rastreabilidade:** permite identificar relações e dependências entre requisitos.
- **Controle de Mudanças:** registra e acompanha alterações realizadas nos requisitos.
- **Identificação Única:** cada requisito possui um identificador exclusivo, mantido para fins de histórico.

## 4. Etapas do Gerenciamento de Mudanças

1. **Análise do Problema:** identificar e avaliar a solicitação de mudança.
2. **Análise da Mudança:** verificar impactos, custos e decidir se a alteração será aprovada.
3. **Implementação:** atualizar os requisitos e, quando necessário, modificar o sistema.

**Importante:** uma mudança em um requisito pode afetar vários outros requisitos.

## 5. Planejamento e Ferramentas

- Definir como os requisitos serão identificados e controlados.
- Estabelecer políticas de rastreabilidade e gerenciamento de mudanças.
- Utilizar ferramentas para armazenar requisitos e acompanhar alterações.
- Podem ser utilizadas planilhas, bancos de dados ou sistemas especializados.

## 6. Resumo para a Prova

- **Gerenciamento = controlar mudanças nos requisitos.**
- **Baseline = versão de referência dos requisitos.**
- **Rastreabilidade = identificar relações e impactos entre requisitos.**
- Toda mudança deve ser **analisada, aprovada e documentada**.
- O custo e os benefícios devem ser considerados antes de aprovar alterações.
- O documento de requisitos deve permanecer atualizado.
- Mudanças sem controle podem gerar inconsistências, custos e retrabalho.


<br>
<br>
<br>

# Aula 10 – Casos de Uso

## 1. O que são Casos de Uso?

- Representam as funcionalidades de um sistema do ponto de vista do usuário.
- Facilitam a comunicação entre clientes, analistas e desenvolvedores.
- Ajudam a identificar e compreender os requisitos do software.
- São independentes da linguagem de programação e das tecnologias utilizadas.

## 2. Elementos do Diagrama de Casos de Uso

- **Atores:** pessoas ou outros sistemas que interagem com o software.
- **Casos de Uso:** funcionalidades ou ações oferecidas pelo sistema.
- **Relacionamentos:** representam as interações e dependências entre os elementos.

### Representação Gráfica

- **Boneco:** representa um ator.
- **Elipse:** representa um caso de uso.
- **Linha:** representa a associação entre ator e caso de uso.
- **Retângulo:** representa os limites do sistema.

## 3. Relacionamentos entre Casos de Uso

- **Include (<<include>>):** inclusão obrigatória de outro caso de uso.
- **Extend (<<extend>>):** comportamento adicional ou opcional, executado sob determinadas condições.
- **Generalização:** permite que um ator herde funcionalidades de outro ator.

### Exemplo

- **Include:** processar pedido inclui obrigatoriamente validar pagamento.
- **Extend:** realizar compra pode incluir opcionalmente aplicar cupom.
- **Generalização:** cliente herda a funcionalidade de login do ator usuário.

## 4. O que é UML?

- **UML (Unified Modeling Language):** linguagem padronizada para modelagem de sistemas.
- Utiliza diagramas para representar a estrutura e o comportamento do software.
- Facilita a compreensão e a comunicação durante o desenvolvimento.
- Foi padronizada pela OMG (Object Management Group).

### Principais Diagramas UML

- **Caso de Uso:** funcionalidades vistas pelo usuário.
- **Classes:** classes e seus relacionamentos.
- **Sequência:** ordem das interações entre objetos.
- **Atividades:** fluxo de atividades e processos.
- **Estados:** estados e transições de um objeto.
- **Componentes:** organização dos componentes do sistema.

## 5. Resumo para a Prova

- **Caso de Uso = funcionalidade do sistema na visão do usuário.**
- **Ator = pessoa ou sistema que interage com o software.**
- **Include = comportamento obrigatório.**
- **Extend = comportamento opcional ou condicional.**
- **Generalização = herança de funcionalidades.**
- **UML = linguagem padronizada para modelagem de sistemas.**
- Diagramas de casos de uso facilitam a comunicação e a identificação de requisitos.
- Os casos de uso representam **O QUE o sistema faz**, não como será programado.



