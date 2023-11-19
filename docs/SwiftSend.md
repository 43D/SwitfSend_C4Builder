# SwiftSend

* [SwiftSend](#SwiftSend)
  * [SwiftSend](#SwiftSend)
    * [API Application](#API-Application)
    * [Database](#Database)
    * [Mobile App Cliente](#Mobile-App-Cliente)
    * [Mobile App Prestador](#Mobile-App-Prestador)
    * [Single Page Application](#Single-Page-Application)
    * [Web Application](#Web-Application)

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

## SwiftSend

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

`\SwiftSend\API Application`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Diagrama componente**

**Escopo**: Contêiner de API Application.

**Elementos primários**:
* Tokens Controller
* Perfil Controller
* Serviços SwiftSend Controller
* Camada de segurança
* Sistema de pagamento Facade
<br>

**Elementos de suporte:**:
* Single Page Application
* Mobile App Cliente
* Mobile App Prestador
* Database
* Sistema de cobraças
<br>

**Público-alvo**: arquitetos e desenvolvedores de software.

## Database

`\SwiftSend\Database`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

## Mobile App Cliente

`\SwiftSend\Mobile App Cliente`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

## Mobile App Prestador

`\SwiftSend\Mobile App Prestador`

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

`\SwiftSend\Single Page Application`

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

## Web Application

`\SwiftSend\Web Application`

[SwiftSend](#SwiftSend)

![diagram](container.svg)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.