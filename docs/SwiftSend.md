# SwiftSend

* [SwiftSend](#SwiftSend)
  * [SwitfSend](#SwitfSend)
    * [API Application](#API-Application)
    * [Single Page Application](#Single-Page-Application)
      * [Dynamic Diagram](#Dynamic-Diagram)
      * [Extended Docs](#Extended-Docs)

---

## SwiftSend

![diagram](context.svg)

**Nível 1: diagrama de contexto do sistema**

**Escopo**: O SwiftSend tem como objetivo agenciar serviços alternativos de transporte, como serviços de entrega ou transporte de pessoas.

**Elementos primários**: 
* **Cliente** (Passageiro/Remetente):
    Usuário do sistema SwiftSend, ele solícita serviços de entrega e de carona.
    <br>

* **Prestadores de serviço** (encomendas/transporte):
    Usuário do sistema SwiftSend, ele recebe solicitações de trabalhos na sua área.
    <br>

* **SwiftSend:**
    Sistema de intermediação de clientes e prestadores de serviços, abrangendo entrega de objetos e transporte de clientes.
    <br>

* **Sistema Cobraças:**
    Sistema externo de cobraças.
    <br>

* **Sistema geolocalização:**
    Sistema externo de fornecimento de geolocalização .
    <br>

* **Destinatário:**
    Usuário externo, receptor final das encomendas.
    <br>


**Público-alvo**: Clientes e Prestadores de serviço

## SwitfSend

`\SwitfSend`

[SwiftSend](#SwiftSend)

![diagram](system.svg)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.

## API Application

`\SwitfSend\API Application`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

## Single Page Application

`\SwitfSend\Single Page Application`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

> Example of included local image

![](2020-01-10-16-21-41.png)

## Dynamic Diagram

`\SwitfSend\Single Page Application\Dynamic Diagram`

[SwiftSend](#SwiftSend)

![diagram](dynamic.svg)

**Dynamic diagram**

A simple dynamic diagram can be useful when you want to show how elements in a static model collaborate at runtime to implement a user story, use case, feature, etc. This dynamic diagram is based upon a UML communication diagram (previously known as a "UML collaboration diagram"). It is similar to a UML sequence diagram although it allows a free-form arrangement of diagram elements with numbered interactions to indicate ordering.

**Scope**: An enterprise, software system or container.

**Primary and supporting elements**: Depends on the diagram scope; enterprise (see System Landscape diagram), software system (see System Context or Container diagrams), container (see Component diagram).

**Intended audience**: Technical and non-technical people, inside and outside of the software development team.

## Extended Docs

`\SwitfSend\Single Page Application\Extended Docs`

[SwiftSend](#SwiftSend)

![diagram](class.svg)

![diagram](sequence.svg)

Multiple markdowns can be ordered using `<name>.1.md, <name>.2.md .. <name>.<n>.md`

You can choose where to place a certain diagram by using `![name](<diagram name>.puml)`

![diagram](ditaa.png)

Feel free to add any additional details necesary.
