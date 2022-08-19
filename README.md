BANCO DE DADOS – SQL (RELACIONAL):
Um banco de dados relacional é uma coleção de itens de dados com relacionamentos predefinidos entre si. Esses itens são organizados como um conjunto de tabelas com colunas e linhas. As tabelas são usadas para reter informações sobre os objetos a serem representados no banco de dados. Cada coluna da tabela retém um determinado tipo de dado e um campo armazena o valor em si de um atributo. As linhas na tabela representam uma coleção de valores relacionados de um objeto ou de uma entidade. Cada linha em uma tabela pode ser marcada com um único chamado de chave principal. Já as linhas entre as várias tabelas podem ser associadas usando chaves estrangeiras. Esses dados podem ser acessados de várias maneiras diferentes sem reorganizar as próprias tabelas do banco de dados.

• Banco de dados relacionais são projetados para aplicativos transacionais e fortemente consistentes de processamento de transações online (OLTP) e são bons para processamento analítico online (OLAP);

• O modelo relacional normaliza dados em tabelas, compostas por linhas e colunas. Um esquema define estritamente tabelas, colunas, índices, relações entre tabelas e outros elementos do banco de dados. O banco de dados impõe a integridade referencial nos relacionamentos entre as tabelas;

• A performance normalmente depende do subsistema do disco. A otimização de consultas, índices e estrutura de tabela é necessária para alcançar máxima performance;
• Os bancos de dados relacionais geralmente escalam verticalmente o tamanho ao aumentar os recursos de computação do hardware, ou escalam horizontalmente o tamanho ao adicionar réplicas para cargas de trabalho somente leitura;

• As solicitações para armazenar e recuperar dados são comunicadas usando consultas compatíveis com uma Structured Query Language (SQL – Linguagem de consultas estruturadas). Essas consultas são analisadas e executadas pelo banco de dados relacional.

Bancos de dados relacionais fornecem propriedades de atomicidade, consistência, isolamento e durabilidade (ACID):
• A atomicidade exige uma transação para executar completamente ou não é executada de formada alguma;

• A consistência exige que, quando uma transação é confirmada, os dados devem estar em conformidade com o esquema do banco de dados;

• O isolamento exige que as transações simultâneas sejam executadas separadamente uma das outras;

• A resiliência exige a capacidade de se recuperar de uma falha do sistema ou falta de energia inesperada para o último estado conhecido.

BANCO DE DADOS – NoSQL (NÃO RELACIONAL):
Bancos de dados NoSQL não criados para modelos de dados específicos e têm esquemas flexíveis para a criação de aplicativos modernos. São amplamente reconhecidos por sua flexibilidade de desenvolvimento, funcionalidade e performance em escala. 

• Os bancos de dados do NoSQL são projetados para vários padrões de acesso aos dados que incluem aplicativos de baixa latência. Os dados de pesquisa NoSQL são projetados para análise de dados semiestruturados;

• Os bancos de dados NoSQL fornecem uma variedade de modelos de dados, como chave-valor, documento e gráfico, que são otimizados para performance e escala;

• Os bancos de dados NoSQL geralmente fazem compensações relaxando algumas das propriedades ACID dos bancos de dados relacionais para um modelo de dados mais flexível que pode ser escalado horizontalmente. Isso torna os bancos de dados NoSQL uma excelente opção para os casos de uso de baixa latência e alta taxa de transferência que precisam ser escalados horizontalmente além das limitações de uma única instância;

• A performance geralmente é uma função do tamanho do cluster do hardware subjacente, da latência de rede e do aplicativo que faz a chamada;

• Os bancos de dados NoSQL normalmente são particionáveis porque os padrões de acesso podem escalar horizontalmente o tamanho usando arquitetura distribuída para aumentar a taxa de transferência que fornece performance consistente em escala quase ilimitada;

• APIs baseadas em objetos permitem que desenvolvedores de aplicativos armazenem e restaurem facilmente estruturas de dados. As chaves de participação permitem que os aplicativos procurem pares de chave-valor, conjuntos de colunas ou documentos semiestruturados que contenham objetos e atributos de aplicativos serializados.

TIPOS DE BANCOS DE DADOS NoSQL:
Chave-valor: são altamente particionáveis e permitem escalabilidade horizontal em escalas que outros tipos de bancos de dados não conseguem alcançar. Casos de uso, como: jogos e tecnologia de publicidade e IoT.

Documento: no código do aplicativo, os dados costumam ser apresentados como um objeto ou um documento do tipo JSON porque esse é um modelo de dados eficiente e intuitivo para os desenvolvedores. Os bancos de dados de documentos facilitam para que os desenvolvedores armazenem e consultem dados usando o mesmo formato de modelo de documento que usam no código do aplicativo. A natureza flexível, semiestruturada e hierárquica dos documentos e dos bancos de dados de documentos permite que eles evoluam conforme as necessidades dos aplicativos. O modelo de documentos funciona bem com catálogos, perfis de usuários e sistemas de gerenciamento de conteúdo, onde cada documento é único e evolui com o passar do tempo.

Gráfico: Finalidade de um banco de dados gráfico é facilitar a criação e execução de aplicativos que funcionam com conjuntos de dados altamente conectados. Os casos típicos de um banco de dados gráfico incluem redes sociais, mecanismos de recomendação, detecção de fraudes e gráficos de conhecimento. 

Em memória: Aplicações de jogos e tecnologia de publicidade têm casos de uso como placares de líderes, armazenamentos de sessões e análises em tempo real que exigem tempos de resposta em microssegundos e podem ter grandes picos de tráfego a qualquer momento.

Pesquisar: Muitos registros de saída de aplicativos ajudam os desenvolvedores a solucionar problemas.

SOBRE ENGENHEIRO DE DADOS:
Um engenheiro de dados entenderá a estrutura de um banco de dados, mas se concentrará nos dados desse banco de dados. Pedirá para melhorar a consulta ou procedimento armazenado para reduzir melhor os problemas com os dados retornados, por exemplo, para remover linhas duplicadas no conjunto de dados devido a um possível erro humano. 
Uma tarefa comum para os engenheiros de dados é converter dados em um formato que outros possam analisar facilmente. Pode ser responsável por identificar tendência em conjuntos de dados e desenvolver algoritmos para ajudar a tornar os dados brutos mais úteis para colegas e clientes.

FONTES UTILIZADAS:

https://aws.amazon.com/pt/nosql/

https://aws.amazon.com/pt/relational-database/
