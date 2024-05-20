# Consulta--cep-api-t9
Projeto de consumo de API de CEP do ViaCep.

## APIs

As APIs possuem alguns elementos que servem à sua utilização;

- Ponto de entrada: é o endereço do serviço hospedado e que pode ser acessado através de um navegador ou uma ferramenta de consumo de APIs.Exemplo: <https://dadosabertos.camara.leg.br/api/v2>

- **Recursos**: são os serviços de dados disponíveis para consumo.Exemplo:<https://dadosabertos.camara.leg.br/api/v2/deputados>

- ** Parâmetros**: são informações ou filtros que servem para enviar dados da consulta ou para serem processados pela API.Os parâmetros podem ser passados para a API através da URL ou no corpo (body) da requisição. Exemplo:<https://dadosabertos.camara.leg.br/api/v2/deputados?nome=tiririca>

-**Métodos**: são as formas de consumo de um API,que podem ser:
- POST_: inserção de dados (**c**REATE)
- GET_: obtenção de dados (**R**EAD)
- PUT e PATCH_: atualização (**U**PDATE)
- DELETE_: remoção de dados (**D**ELETE)