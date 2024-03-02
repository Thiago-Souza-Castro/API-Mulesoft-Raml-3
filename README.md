API de Eventos Locais
Esta é uma API de Eventos Locais que fornece informações sobre eventos em determinada localidade. Desenvolvida utilizando RAML utiliza MySQL como banco de dados. O design da API foi realizado com MuleSoft, e a configuração dos fluxos foi feita através do Anypoint Studio.

Evento:
Estrutura para representar informações sobre um evento.
Propriedades: id, nome, localização, dataHora, descricao, tipo.
Exemplo: Detalhes de um evento.

Endpoints

/eventos
GET:
Descrição: Obtém os detalhes de um evento específico pelo ID.
Respostas:
200: Detalhes do evento (application/json: Evento).
404: {"message": "Evento não encontrado."}

/eventos/buscar
GET:
Descrição: Obtém os detalhes de um evento específico pelo nome.
Resposta 200: Lista de eventos (application/json: Evento[]).
Explore esta API para obter informações detalhadas sobre eventos locais, seja buscando por ID ou por nome. Utilizando MySQL como banco de dados para eficiência no armazenamento e MuleSoft para o design da API, com a configuração dos fluxos realizada no Anypoint Studio.

Explore esta API para obter informações detalhadas sobre eventos locais, seja buscando por ID ou por nome. Utilizando MySQL como banco de dados para eficiência no armazenamento e MuleSoft para o design da API, com a configuração dos fluxos realizada no Anypoint Studio.
