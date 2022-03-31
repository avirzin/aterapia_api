<img src="https://aterapia.com.br/logo-full.png" alt="drawing" width="200"/> API v0.1


Proposta de API para Aterapia que poderá ser usada para integração com os parceiros que queiram oferecer em suas plataformas a consulta com os psicólogos.

O Swagger está disponível [aqui](aterapia_api.yaml).

## Diagramas

### Diagrama de sequência

![Diagrama de Sequencia - Aterapia](/diagrams/API_Aterapia-SequenceDiagram.drawio.png)

### Diagrama de casos de uso

![Diagrama de caso de uso - Aterapia](/diagrams/API_Aterapia-UseCase.drawio.png)

## Lista de métodos

Abaixo a lista de web methods disponíveis:

### User

- Get Users;
- Create user;
- Get user;
- Update user.

### Psychologist

- Get psychologist;
- Get psychologist by Id.

### Session

- Get available session from psychologist;
- Schedule a session with psychologist;
- Reschedule a session with psychologist.
