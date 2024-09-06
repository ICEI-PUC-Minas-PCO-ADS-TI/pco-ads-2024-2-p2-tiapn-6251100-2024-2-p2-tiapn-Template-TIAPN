# Especificação do projeto

<span style="color:red">Pré-requisitos: <a href="01-Contexto.md"> Documentação de contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

## Personas

Exemplo: _Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente por meio de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros._

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links úteis**:
> - [Rock content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuários que são relevantes para o projeto da sua solução. As histórias de usuários consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuários por contexto, para facilitar consultas recorrentes a esta parte do documento.

> **Links úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (user stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 common user story mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas a seguir apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. A prioridade dos requisitos foi determinada no julgamento da equipe de desenvolvimento, levando em base as principais funções da aplicação

### Requisitos funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que novos parceiros se registrem e forneçam informações sobre seus locais de doação	|ALTA|
|RF-002| Facilitar o registro de voluntários que desejam contribuir com os parceiros e usuários da plataforma	|ALTA|
|RF-003| Exibir uma lista ou mapa de todos os locais disponíveis para doação, com informações detalhadas sobre cada um	|ALTA|
|RF-004| Permitir que os doadores deixem comentários e avaliem os locais de doação após utilizá-los	|MÉDIA|
|RF-005| Enviar notificações para parceiros e doadores sobre atividades relevantes	|MÉDIA|
|RF-006| Oferecer uma barra de pesquisa e filtros avançados para ajudar os usuários a encontrar locais de doação específicos	|ALTA|
|RF-007| Facilitar a edição e manutenção das informações dos perfis de usuários registrados na plataforma	|ALTA|
|RF-008| Permitir que os parceiros atualizem suas informações de perfil, como detalhes do local de doação e horários de funcionamento	|ALTA|
|RF-009| Proporcionar um sistema de comunicação direta entre parceiros e doadores para discutir detalhes das doações	|ALTA|
|RF-010| Utilizar geolocalização para mostrar aos usuários os locais de doação mais próximos	|ALTA|
|RF-011| Permitir que os parceiros registrem os tipos específicos de doações que aceitam, como roupas, alimentos, eletrônicos, etc.	|ALTA|
|RF-012| Oferecer a opção de filtrar os locais de doação com base na proximidade em relação à localização atual do usuário	|MÉDIA|
|RF-013| Permitir que os usuários marquem locais de doação como favoritos para fácil acesso no futuro	|MÉDIA|
|RF-014| Manter um registro de doações que foram rejeitadas pelos parceiros, incluindo os motivos para tal	|MÉDIA|
|RF-015| Registrar todas as doações que foram aceitas pelos parceiros, facilitando o acompanhamento das atividades de doação do usuário	|ALTA|
|RF-016| Permitir que os doadores deixem comentários sobre os parceiros, ajudando a manter a qualidade dos serviços oferecidos	|MÉDIA|
|RF-017| Fornecer uma funcionalidade para os doadores avaliarem os parceiros com base na experiência de doação	|MÉDIA|
|RF-018| Permitir que doadores enviem fotos das doações diretamente no chat com os parceiros, facilitando a comunicação e verificação do estado dos itens doados	|ALTA|

### Requisitos não funcionais

| ID       | Descrição do Requisito                                                                                  | Prioridade |
|----------|---------------------------------------------------------------------------------------------------------|------------|
| RNF-001  | O site deve responder rapidamente às interações do usuário, com tempos de carregamento mínimos e processamento ágil, mesmo sob condições de alta carga. | ALTA       |
| RNF-002  | A interface do site deve ser intuitiva, fácil de entender e de navegar, permitindo que usuários de todos os níveis técnicos possam utilizá-lo sem dificuldades. | ALTA       |
| RNF-003  | O site deve proteger as informações dos usuários e parceiros contra ameaças como acessos não autorizados, ataques cibernéticos e vazamentos de dados. | ALTA       |
| RNF-004  | O sistema deve estar disponível e funcional de forma consistente, com mínima ocorrência de falhas ou períodos de inatividade. | ALTA       |
| RNF-005  | O design do site deve se adaptar a diferentes dispositivos e tamanhos de tela, proporcionando uma boa experiência de uso tanto em desktops quanto em dispositivos móveis. | MÉDIA      |
| RNF-006  | O site deve funcionar corretamente em diferentes navegadores e sistemas operacionais, garantindo que todos os usuários tenham uma experiência consistente. | MÉDIA      |
| RNF-007  | O código do site deve ser bem organizado, modular e documentado, facilitando a manutenção, correção de bugs e adição de novas funcionalidades. | ALTA       |
| RNF-008  | O site deve garantir que os dados pessoais dos usuários sejam coletados, armazenados e processados de acordo com as regulamentações de privacidade aplicáveis. | ALTA       |

Com base nas histórias de usuários, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos não funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).

Lembre-se de que cada requisito deve corresponder a uma e somente uma característica-alvo da sua solução. Além disso, certifique-se de que todos os aspectos capturados nas histórias de usuários foram cobertos.

> **Links úteis**:
> - [O que são requisitos funcionais e requisitos não funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [Entenda o que são requisitos de software, a diferença entre requisito funcional e não funcional, e como identificar e documentar cada um deles](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Restrições

O projeto está restrito aos itens apresentados na tabela a seguir.

| ID  Restrição                                                                                  |
|-----|--------------------------------------------------------------------------------------------|
| 01  | O projeto deve seguir os prazos de entrega estipulados para cada sprint.                   |
| 02  | O projeto precisa necessariamente ser intuitivo para todas as idades diante de níveis tecnológicos. |
| 03  | Todos os colaboradores do projeto precisam conhecer todas as etapas do projeto.            |
| 04  | Todos os colaboradores do projeto precisam participar efetivamente de todas as etapas do projeto. |
| 05  | O projeto precisa necessariamente ser de fácil entendimento para todos os tipos de usuários. |
| 06  | O projeto deve cumprir com excelência todos os requisitos de cada sprint.                  |
| 07  | As entregas intermediárias devem ser revisadas e validadas por todas as partes interessadas antes de avançar para a próxima fase. |
| 08  | As atualizações e revisões no escopo devem ser aprovadas por todos os desenvolvedores antes de serem implementadas. |
| 09  | A documentação do projeto deve ser atualizada e mantida em todas as fases de desenvolvimento. |
| 10  | O código-fonte deve ser versionado adequadamente e estar disponível em repositórios acessíveis para a equipe. |
| 11  | O projeto deve atender a todas as métricas de qualidade acordadas, incluindo desempenho e segurança. |

## Diagrama de casos de uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos. Ele utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. O diagrama contempla a fronteira do sistema e o detalhamento dos requisitos funcionais, com a indicação dos atores, casos de uso e seus relacionamentos.

As referências abaixo irão auxiliá-lo na geração do artefato “diagrama de casos de uso”.

> **Links úteis**:
> - [Criando casos de uso](https://www.ibm.com/docs/pt-br/engineering-lifecycle-management-suite/design-rhapsody/10.0?topic=cases-creating-use)
> - [Como criar diagrama de caso de uso: tutorial passo a passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)