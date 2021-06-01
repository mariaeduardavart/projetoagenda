# projetoagenda
Projeto de uma agenda simples.

Este projeto se trata de um sistema de agenda telefônica, na qual é possível salvar os seguintes dados: nome, telefone e endereço. Foi desenvolvido na IDE Eclipse, utilizando a linguagem Java (Web).
Todos os passos para o desenvolvimento:
- Ao abrir o eclipse foi criado um projeto.
- Na pasta “Java Resources” > scr/main/resources está o arquivo xml hibernate.cfg.xml na qual é feito a conexão com o banco de dados.
- Foi usando o MySQL Workbench.
- Ainda na pasta “Java Resources” > scr/main/java foi criado 5 pacotes, pacote bean, dao, domain, util e main.
Dentro do pacote Bean foi criado a classe AgendaBean.
Dentro do pacote Dao foi criado as classes AgendaDao e GenericDao.
Dentro do pacote Domain foi criado as classes Agenda e GenericDao.
Dentro do pacote Util foi criado as classes HibernateUtil e JsfUtil.
Dentro do pacote Main foi criado a classe HibernateUtilTeste.

- Ainda na pasta “Java Resources” > scr/test/java foi criado o pacote daotest. Dentro deste pacote foi criado a classe AgendaDaoTest
Na pasta “Deployed Resources” > webapp > pages onde estão as páginas xhtml.
-agendaCadastro
-agendaPesquisa
-principal
Na pasta “Deployed Resources” > templates está o arquivo de template xhtml. 
No arquivo pom.xml foram passadas todas as dependências e primefaces.
Na classe AgendaDaoTest está declarado todas as informações para salvar, editar, listar e excluir no BD. Para a execução da página, deve-se executar a página xhtml Principal.
