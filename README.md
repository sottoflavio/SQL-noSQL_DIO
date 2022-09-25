#SQL e NoSQL

###Bancos de dados relacional

Banco onde deseja armazenar informações relacionadas entre si.
São normalizadas e padrozinadas, como sistemas de vendas, serviços.
Possuem estrutura de dados mais rígida, garantindo a integridade dos dados no sistema
O sistema de dados é conhecido antes, modelado e possouem relação entre si.


###Banco de dados não relacionais
Surgiram para atender novas necessidades de tratamento e armazenamento de dados.
Computam capacidades adicionais aos bancos relacionais, pois precisam atender um volume maior de informação na horizontalidade e sistemas não rígidos de dados, entre inúmeras outras mídias, fotos, vídios, gráficos.
Ele consegue trabalhar armazenando informações com modelos menos rígidos.

Bancos relacionais nao vieram para substituir os relacionais, mas sim para em determinados cenários complementar funcionalidades em situações determinadas.
Possuem uma escalabilidade de armazenamento e tratamento de dados na horizontalidade muito superior aos bancos relacionais, Reduzindo também a necessidade de joins e consultas, facilitando a pesquisa em grandes volumes de informação.

Trabalhar em uma estrutura sem um esquema rígido requer determinados cuidados para tratar nas consultas posteriormente, então devem ser definidas chaves e formas de consultar essa informação previamente. As chaves devem ser armazenadas de forma mais correta possível para evitar dificuldades posteriores.
Aplicações (API) devem ser pensadas para entender quais informações devem ser ignoradas ou não no tratamento desses dados.
Mesmo não sendo um sistema rigido de modelagem, a modelagem deve ser previamente pensada inclusive prevista até onde essa fleixibilidade pode ou não ser util ao sistema como um todo.

Bancos não relacionais flexibilizam o acesso à informação, sendo menos limitadas à rigidez, sendo contornáveis em incosistências, inclusive em sistemas distribuidos.

Ferramentas de arquitetura Lake ajudam manter a consistência de informações dentro de lakes (grandes volumes de informação, estruturas ou não). e Bancos não relacionais ajudam a manter a consistÊncia dessa informação. Arquiteturas de data lake precisam garantir o acesso, disponibilidade e consistência dessa informação.

A ingestão e processamento dos dados é o ponto mais crítico para poder criar dados que sejam disponíves para serem consumidos posteriormente. Existem ferramentas para automatizar e controlar esses processos.

A escolha do banco determina o tpo de processamento e de informação que será inserida nesse banco, para poder determinar a ingestão dessa informação posteriormente.

Dentro desse escopo, cabe ao engenheiro preparar a informação provendo ela de forma útil para o ciêntista ou analista de dados. Ambas as habilidades são complementares.

Matemática e estatística são fundamentais nesse ambiente de engenharia de dados como skill complementar às ferramentas de tratamento de dados.
