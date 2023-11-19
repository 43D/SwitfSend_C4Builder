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
* Cliente (Passageiro/Remetente)
* Prestadores de serviço (encomendas/transporte)
* SwiftSend
<br>

**Elementos de suporte**: 
* Sistema Cobraças
* Sistema geolocalização
* Destinatário
<br>

**Público-alvo**: Clientes e Prestadores de serviço

## SwitfSend

`\SwitfSend`

[SwiftSend](#SwiftSend)

![diagram](system.svg)

**Nível 2: Diagrama de contêiner**

**Escopo**: Sistema de software da SwiftSend.

**Elementos primários**: 
* Web Application
* Single Page Application
* Mobile App Cliente
* Mobile App Prestador
* Database
* API Application
<br>

**Elementos de suporte**:
* Passageiro
* Remetente
* Prestadores de serviço de transporte
* Prestadores de serviço de encomendas
* Sistema de cobraças
* Sistema de mapa e geolocalização
<br>

**Público-alvo**: Técnicos dentro e fora da equipe de desenvolvimento de software; incluindo arquitetos de software, desenvolvedores e equipe de operações/suporte.

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
