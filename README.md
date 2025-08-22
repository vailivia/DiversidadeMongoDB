# DiversidadeMongoDB
Projeto ESG de governança
Ana Lívia Silva Barros RM558929
Georgia Correa RM554405
Raissa Yoneda RM557408

Nosso grupo optou por se basear em uma entrega anterior que fizemos em PL-SQL para desenvolver um banco de dados utilizando MongoDB com foco ESG. O projeto abrange o tópico de governança, social e ambiental dos dados.
A aplicação permite armazenar e analisar informações relacionadas a colaboradores, treinamentos, avaliações de engajamento, iniciativas de inclusão e indicadores consolidados de diversidade e sustentabilidade.
No contexto Ambiental, a aplicação possibilita o registro e acompanhamento de treinamentos e iniciativas que incentivem práticas mais sustentáveis, como workshops e programas de conscientização ambiental. Já no aspecto Governança, a utilização de relatórios (reporting) garante transparência e rastreabilidade dos dados, oferecendo métricas claras que podem ser utilizadas pela liderança para tomada de decisão baseada em evidências.
O uso do MongoDB como banco de dados NoSQL traz benefícios importantes para a gestão ESG:
•	Flexibilidade de esquema: permite armazenar informações variadas de colaboradores (como pronomes, necessidades especiais e diferentes tipos de feedbacks), refletindo melhor a diversidade real das pessoas.
•	Escalabilidade: possibilita o crescimento da aplicação sem perda de desempenho, o que é essencial em grandes corporações que monitoram milhares de colaboradores e iniciativas ESG.
•	Centralização e análise de dados: as collections projetadas (colaboradores, treinamentos, avaliacoes, iniciativas e reporting) permitem tanto a visão detalhada (nível individual) quanto a visão consolidada (indicadores e KPIs), alinhando-se às boas práticas de governança.
Assim, a migração do projeto de diversidade corporativa para o MongoDB não apenas moderniza a estrutura de dados, como também fortalece a capacidade da organização de medir, acompanhar e aprimorar suas práticas em ESG, promovendo transparência, inclusão e responsabilidade socioambiental.

Detalhes sobre as Collections:
 colaboradores → dados de pessoas (nome, idade, gênero, etnia, cargo, etc.).
treinamentos → registros de capacitações em diversidade, ESG, etc.
 avaliacoes → avaliações de engajamento / satisfação dos colaboradores.
 iniciativas → projetos de diversidade & inclusão da empresa.
 reporting → indicadores consolidados (KPIs, métricas ESG).

 
Dentro de cada Collection, adicionamos 10 documentos, através da própria plataforma do Atlas, e iniciamos o CRUD dentro de cada um deles.
