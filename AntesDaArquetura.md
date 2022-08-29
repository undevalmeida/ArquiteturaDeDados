># Cenário nas empresas antes do Power BI
* Uso de Excel pelos analistas;
* Tarefas repetitivas e demoradas o tempo todo;
* Demova no processamento das informações;
* Alta dependência da TI para extração de dados;
* Compartilhamento das informações por E-mail (relatório_final.xlsx).

>## Utilizando Power BI na organização
    Nota-se que não há organização(padrão) para criação dos Dashboards, com isso, para fazer uma correção no final dessa segmentação, é preciso refazer todos os outros anteriores. Fazendo com que haja mais dificuldade para fazer a manutenção.

![Utilizando Power BI na organização](SemPadraoDeOrganizacao.png)

>## Problemas comuns encontrados no uso do Power BI
* Trabalhos repetidos: as mesmas transformações de dados presentes em diferentes arquivos PBIX;
* Falta de padronização nos processos: diferentes pessoas realizando ETL de maneiras diferentes;
* Criação de diversos modelos de dados com os mesmos dados e medidas DAX repetidas;
* Troca de arquivos PBIX entre colegas de trabalho
* __Resultado final: dificuldades de manutenção e criação silos de dados totalmente sem padronização! Qualquer mudança precisa ser realizada em inúmeros locais de forma manual e repetitiva.__

>## Governança de Dados
* Antes de mais nada: Self-Service BI não significa fazer as coisas de qualquer jeito, de forma independente. __Cuidado com este termo!__
* Implementar uma solução com Power BI é relativamente simples. Difícil é mantê-la e crescer de forma organizada e sustentável.
* Não é porque estamos utilizando o Power BI que agora teremos a vida fácil.
* Automatizar tarefas repetitivas que antes eram feitas de forma manual no Excel foi apenas o primeiro passo estabelecer uma Cultura de Dados na Organização.
* Se você quiser manter uma solução com pouca manutenção, altamente escalável, consistente e robusta, então será necessário ter a arquitetura correta e a governança adequada.
* É preciso unificar e padronizar todo esse trabalho!

* O Power BI oferece duas funcionalidades muito importantes para isso:
    1. Fluxo de dados(Dataflows)
    2. Conjunto de Dados compartilhados(Shared Datasets)


* [Link da vídeo aula](https://www.youtube.com/watch?v=Ej8bGfbJwUs&list=PLL-6y89GGNdSu9utTLYuzwPGNXQNT0KWm&index=3)