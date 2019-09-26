##Confirmação de Categoria

#### Regras

* Deverá ter um webhook para que o sistema consiga receber, da Greenpass, o evento de Confirmação de Categoria de um veículo da EcoTaggy;
* Neste momento, os veículos só poderão ser do tipo Cat 1 (veículo de passeio), constante no Termo de Adesão, assinado pelo usuário;
* Como Cat 1 devemos considerar que o veículo poderá estar nas seguintes categorias quando passar por um pedágio:

    * **Cat 1 (Geral)**: Automóveis, Caminhonetes e Furgões de rodagem simples;
    * **Cat 7 (Artesp) ou Cat 3 (ANTT)**: Automóvel com Semireboque e Caminhonete com Semireboque;
    * **Cat 8 (Artesp) ou Cat 5 (ANTT)**: Automóvel com reboque e Caminhonete com reboque.

* Se a Confirmação de Categoria violar estas categorias e portanto o Cluster específico (Cluster 1), este veículo deve ser **bloqueado**;
* O usuário deverá ser informado **por e-mail** do ocorrido e também, no Client do EcoTaggy deverá constar este alerta para o usuário quando ele acessar a área logada.

