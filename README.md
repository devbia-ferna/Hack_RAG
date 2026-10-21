rascunho para implementação prática:
escrever código python (utilizando google colab - jupyter notebook, facilitando interação com os colegas de projeto) para:
- ingerir dados da camara municipal (formularios, documentaçao, etc., ...);
- modelação de dados (ID, categorização, ...);
- criar modelo rag para comunicação base de dados <-> utilizador;
- modelar front-end minimalista e escalável.
- recolher dados de interação para devolver futuramente ao utilizador ou para KPIs da camara...

desafio "Falar com a Câmara sem burocracia".
No portal identificamos que o menu "https://www.cm-guimaraes.pt/servicos-online/formularios" poderá ser um ponto crítico e relevante para atuar.
Em traços gerais, a ideia passaria por substituir este processo de interação por um assistente de navegação dos serviços municipais baseado em intenções reais dos cidadãos.
A estrutura do nosso produto seria algo aproximado a:
Camada 1 - ingestão de dados como formulários, documentação, legislação...
Camada 2 - modelação da base de dados
Camada 3 - modelo LLM para comunicação entre o utilizador final e a base de dados
Camada 4 - user interface minimalista e escalável