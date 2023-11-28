# resumoApiREST
 # Api REST e RESTFul

   A arquitetura de APIs (Interface de Programação de Aplicações) desempenha um papel crucial na comunicação entre sistemas distribuídos. A API Rest (Representational State Transfer) criada pelo cientista da computação Roy Fielding é um estilo arquitetônico que utiliza uma abordagem leve e baseada em padrões para facilitar a comunicação entre diferentes sistemas. A principal ideia por trás da API Rest é tratar os recursos da aplicação como objetos acessíveis por URLs. Isso proporciona uma abordagem flexível e escalável para integração de sistemas.Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação. O formato JSON é a linguagem de programação mais usada porque, apesar de seu nome, é independente de qualquer outra linguagem e pode ser lido por máquinas e humanos. 
Para uma API ser considerada do tipo RESTFul, ela precisa seguir alguns critérios. Sendo eles:

• Ter uma arquitetura cliente/servidor formada por clientes, servidores e recursos, com solicitações gerenciadas por HTTP. ...
... • Estabelecer uma comunicação stateless entre cliente e servidor. Isso significa que nenhuma informação do cliente é armazenada entre solicitações **GET** e toda as solicitações são separadas e desconectadas.
• Armazenar dados em cache para otimizar as interações entre cliente e servidor.
• Ter um sistema em camadas que organiza os tipos de servidores envolvidos na recuperação das informações solicitadas em hierarquias que o cliente não pode ver.

    ## Diferenças entre REST e RESTFul

    O termo "RESTful" é frequentemente utilizado para descrever APIs que aderem aos princípios e práticas da arquitetura REST. As principais diferenças entre REST e RESTFul são mais relacionadas à conformidade e aderência rigorosa aos princípios REST. Uma API RESTful segue os princípios de Stateless (sem estado), Cacheable (cachável), Uniform Interface (interface uniforme) e Client-Server (cliente-servidor), entre outros.

     ##HTTP verbs

     Os verbos HTTP desempenham um papel fundamental na comunicação entre o cliente e o servidor em uma arquitetura RESTful. Alguns dos principais verbos HTTP utilizados são:

 **GET**: Solicita a representação de um recurso.
**POST**: Envia dados para serem processados a um recurso especificado.
**PUT**: Atualiza um recurso existente ou cria um novo recurso se não existir.
**DELETE**: Remove um recurso específico.
**CONNECT**: Estabelece um túnel para o servidor identificado pelo recurso de destino.
**OPTIONS**: É usado para descrever as opções de comunicação com o recurso de destino.
**TRACE**: Executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
**Patch**: É utilizado para aplicar modificações parciais em um recurso.

Esses verbos permitem que as operações sejam realizadas de maneira uniforme e previsível, contribuindo para a simplicidade e eficácia da arquitetura REST.

    ## HTTP Status Code
    O Status code é é um número inteiro de 3 dígitos onde o primeiro dígito do Status-Code define a classe de resposta e os dois últimos dígitos não têm nenhuma função de categorização. Existem 5 valores para o primeiro dígito:
| S.N. | Code and Description                                     |
|------|----------------------------------------------------------|
| 1    | **1xx: Informational**                                   |
|      |Isso significa que a solicitação foi recebida e o processo continua. |
| 2    | **2xx: Success**                                         |
|      | Significa que a ação foi recebida, compreendida e aceita com sucesso.|
| 3    | **3xx: Redirection**                                     |
|      | Isso significa que outras ações devem ser tomadas para concluir a solicitação.|
| 4    | **4xx: Client Error**                                    |
|      | Isso significa que a solicitação contém sintaxe incorreta ou não pode ser atendida. |
| 5    | **5xx: Server Error**                                    |
|      | Isso significa que o servidor não atendeu a uma solicitação aparentemente válida. |

    Os códigos de status HTTP indicam o resultado de uma operação solicitada. Alguns códigos comuns incluem:

**200 OK**: Indica que a requisição foi bem-sucedida.
**201 Created**: Indica que a requisição foi bem-sucedida e resultou na criação de um novo recurso.
**400 Bad Request**: Indica que a requisição foi malformada ou não pôde ser processada pelo servidor.
**404 Not Found**: Indica que o recurso solicitado não foi encontrado no servidor.
**500 Internal Server Error**: Indica que ocorreu um erro no servidor durante o processamento da requisição.
 
    Autor do resumo: Levi Souza Alves - 01529075
