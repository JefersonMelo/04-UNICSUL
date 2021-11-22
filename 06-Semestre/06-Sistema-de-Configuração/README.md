# Gerência de Configuração

## Respostas aos Questionários Gerência de Configuração

### I Gerenciamento de Versões

#### Pergunta 1

Considerando a gerência de configuração de um projeto de software, um item importante a ser considerado são seus baselines, que visam especificar:  

```"
os componentes (incluindo bibliotecas) e suas versões para a definição de um sistema.
```

#### Pergunta 2

O gerenciamento de Configuração de Software trabalha diretamente ligado com os Baselines. De acordo com essa informação, assinale alternativa correta.  

```"
É uma configuração formalmente aprovada, para servir de referência ao desenvolvimento posterior do sistema.
```

#### Pergunta 3

A representação abaixo mostra como uma ferramenta de software realiza o controle de versões.  

![alt](https://github.com/JefersonMelo/04-UNICSUL/blob/master/06-Semestre/06-Sistema-de-Configura%C3%A7%C3%A3o/images/atividade_1_pergunta_3.png)  

Considere a figura acima e analise as seguintes afirmativas sobre gerência de configuração e mudanças:  

I - A figura sugere que cada vez que se modifica o projeto, a ferramenta não registra o estado dos arquivos e armazena uma referência para essa captura. Se um dos arquivos sofre alteração, seu estado não é alterado, apenas é criado um link para a versão anterior que já foi armazenada.  

II - Um Sistema de Controle de Versões combina procedimentos e ferramentas para gerir diferentes versões de objetos de configuração que são criados durante o processo de software. Ele implementa ou está ligado a um banco de dados de projeto (repositório) que guarda os objetos de configuração relevantes.  

III - Um repositório de gestão de configuração de software é um conjunto de estruturas de dados que permite a uma equipe de software gerir as modificações de modo efetivo. Porém, não possui funções que impedem que as informações sejam compartilhadas entre vários desenvolvedores para garantir a integridade dos dados, porém, não consegue detectar diferenças entre arquivos binários.  
Está correto o que consta APENAS em:  

```"
II somente
```

#### Pergunta 4

No processo de desenvolvimento de software, o gerenciamento da configuração de software envolve identificar a sua configuração:

```"
em pontos predefinidos no tempo durante o ciclo de vida.
```

### II Construção de Sistemas com Qualidade

#### Pergunta 1

Assinale a alternativa correta. É uma técnica sistemática para construir a arquitetura do software enquanto, ao mesmo tempo, conduz testes para descobrir erros associados às interfaces. Trata-se, especificamente de:

```"
teste de integração.
```

#### Pergunta 2

Em relação ao teste de software, assinale a alternativa correta a respeito do teste de integração.

```"
Visa testar as falhas decorrentes da coerência das interfaces entre os módulos do sistema
```

#### Pergunta 3

Assinale a alternativa correta. No processo de teste de software, o beta teste é:

```"
realizado por clientes em seu próprio local de uso.
```

#### Pergunta 4

Assinale a alternativa correta. Os testes de software são executados, usando os procedimentos e documentos de script de teste. Para que a fase de execução de teste seja realizada com sucesso, devem ser executados:

```"
os casos de teste
```

### III Gerenciamento de Mudanças

#### Pergunta 1

Os riscos e o processo de implementação desse tipo de mudança são conhecidos de antemão. Houve tempo para planejamento e há rotina de rollback, ou seja, se tudo der errado, dá para voltar. Identifique nas alternativas abaixo qual é o nome desse tipo de mudança e assinale a alternativa correta.

```"
Mudanças-padrão.
```

#### Pergunta 2

O processo de mudança pode ser mapeado de diferentes formas, pois cada empresa busca a sua real necessidade dentro de um controle processual das atualizações tecnológicas. Algumas querem ter um controle maior para as mudanças emergenciais, outras querem que as mudanças rotineiras sigam um fluxo diferenciado que não requer nenhum registro, apenas uma aprovação por e-mail. Enfim, esses são apenas pequenos exemplos dentro de um mundo imenso com outras peculiaridades. Considerando o texto apresentado, avalie as informações a seguir sobre o fluxo do processo de mudança:

I - Criar um formulário de requisição de mudanças é parte fundamental do GMUD.  

II - Analisar o desemprenho da mudança não é fundamental uma vez que colocá-la para funcionar é o que se espera.  

III - Planejar a mudança é algo não essencial, pois, uma vez passado o formulário de pedido de mudança, o planejamento já está embutido.  

IV - Testar a mudança é essencial para eliminar falhas.  

É correto o que se afirma em:  

```"
I e IV somente.
```

#### Pergunta 3

Esse tipo de mudança indica uma crise ou oportunidade que deve ser abordada o mais rápido possível, com o mínimo de risco possível. Identifique, nas alternativas abaixo, qual é o nome desse tipo de mudança e assinale a alternativa correta.

```"
Mudanças urgentes. 
```

#### Pergunta 4

Embora sejam bastante comuns, elas exigem abordagens únicas e inovadoras. Elas precisam passar por um processo regrado de mudança antes de serem aprovadas e implementadas. Identifique, nas alternativas abaixo, qual é o nome desse tipo de mudança e assinale a alternativa correta.

```"
Mudanças normais.
```

### IV Conceitos DevOps

#### Pergunta 1

Qual conceito está associado a cada mudança que é realizada no código-fonte é implantada na produção automaticamente, sem a aprovação explícita de um desenvolvedor? Assinale a alternativa correta.

```"
Implantação Contínua
```

#### Pergunta 2

Qual conceito está associado à capacidade de obter mudanças de todos os tipos, incluindo novas funcionalidades, alterações de configuração, correções de bugs e experimentos em produção, ou nas mãos de usuários, de forma segura e rápida de forma sustentável? Assinale a alternativa correta.

```"
Entrega Contínua
```

#### Pergunta 3

DevOps é um termo criado para descrever um conjunto de práticas para integração entre as equipes de desenvolvimento de softwares, operações (infraestrutura ou sysadmin) e de apoio envolvidas (como controle de qualidade) e a adoção de processos automatizados para produção rápida e segura de aplicações e serviços. Considerando o texto apresentado, avalie as informações a seguir sobre DevOps:

I - Utilizar a comunicação para integrar desenvolvedores de software e profissionais de infraestrutura de TI.  

II - Utilizar a virtualização e a computação em nuvem como prática comum para acelerar a mudança no mundo da infraestrutura moderna.  

III - Não se trata de metodologia, mas de velocidade na entrega somente.  

IV - É ótimo para equipes iniciantes, pois irão aprender na prática de forma incremental.  

É correto o que se afirma em:  

```"
I e II somente.
```

#### Pergunta 4

Das frases abaixo, qual delas melhor responde à pergunta: o que é DevOps?

```"
Filosofia de desenvolvimento de software que prioriza a colaboração e a integração contínua, e busca ferramentas que promovam vantagem para a automação da configuração da infraestrutura e desenvolvimento.
```
