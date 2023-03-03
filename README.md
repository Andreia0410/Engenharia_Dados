## Engenharia_Dados
Engenharia de dados. Conceitos, definições, pipeline de dados e Data modern stack

O que é Big Data ?

Big Data não é um conceito novo, já existe há alguns anos, surgiu em 1997 com o intuito de nomear conjuntos de 
dados não rdenados em rápido crescimento. Big Data é a área do conhecimento computacional que estuda como coletar, tratar, analisar
e obter informações a partir de conjuntos de dados muito grandes.

O que são Data Lakes ?

Data Lakes nada mais é como sugere o nome, um lago ou um único repositório de dados, onde podemos capturar, armazenar e entregar dados de 
diferentes tipos, formatos e volume. Os dados podem ser capturados em batch/ETL(em lote) ou streaming de dados(processo de transmissão de um fluxo contínuo de dados) 
de diferentes data sources(origens). Tais como: Sistemas corporativos(SAP'S, CRM, ERP...), APP's, Databases legado, API's, Cloud Services, Devices, WebIoT,
entre outros. Os Data Lakes podem armazenar dados estruturados(csv, tabelas, xlsx, corporate tables), semi-estruturados(JSON, logs, txt, XML), data stores(ORC, Parquet) e dados não-estruturados(imagens, videos, audio). Os dados armazenados no Lake possuem uma entrega mais rápida de Analytics, Data Science e ML em relação à insights e respostas de negócios que precisam ser entregues em um near real time ou real time, dependendo da necessidade do negócio. Tornando as soluções de negócios mais rápidas
e assertivas.

O que é uma Pipeline de dados em batch ?
![Dilithium_flowchart-diagrams_1_2x ab0945a88b1e911d345fc4f2df94c04300689315](https://user-images.githubusercontent.com/57784654/218838654-3c590f24-284d-4c51-90de-b929c201a9e9.jpeg)

Os pipelines de dados de processamento em lote processam e armazenam dados em grandes volumes ou lotes. Eles são adequados para tarefas ocasionais de alto volume, como contabilidade mensal.

O pipeline de dados contém uma série de comandos sequenciados e cada comando é executado em todo o lote de dados. O pipeline de dados fornece a saída de um comando como entrada para o seguinte comando. Após a conclusão de todas as transformações de dados, o pipeline carrega todo o lote em um data warehouse na nuvem ou em outro armazenamento de dados semelhante.


O que é uma pipeline de dados em Streaming ?
![product-page-diagram_Amazon-Kinesis-Data-Streams 074de94302fd60948e1ad070e425eeda73d350e7](https://user-images.githubusercontent.com/57784654/218844674-4a7c6545-98c0-4fca-aa87-6342f09047cb.png)

Um fluxo de dados é uma sequência contínua e incremental de pacotes de dados de pequeno porte. Geralmente representa uma série de eventos que ocorrem durante um determinado período. Por exemplo, um fluxo de dados pode mostrar dados do sensor contendo medições durante a última hora. Uma única ação, como uma transação financeira, também pode ser chamada de evento. Os pipelines de streaming processam uma série de eventos para análises em tempo real.

A transmissão de dados requer baixa latência e alta tolerância a falhas. Seu pipeline de dados deve ser capaz de processar dados mesmo que alguns pacotes de dados sejam perdidos ou cheguem em uma ordem diferente da esperada.

Qual a diferença entre o processamento em bacth e em streaming ?
![Capturar](https://user-images.githubusercontent.com/57784654/218847087-b3184111-2991-4187-8608-57aa4fd00f92.JPG)


