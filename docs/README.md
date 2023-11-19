# SwiftSend

* [**SwiftSend**](README.md)
  * [SwitfSend](SwitfSend/README.md)
    * [API Application](SwitfSend/API%20Application/README.md)
    * [Single Page Application](SwitfSend/Single%20Page%20Application/README.md)
      * [Dynamic Diagram](SwitfSend/Single%20Page%20Application/Dynamic%20Diagram/README.md)
      * [Extended Docs](SwitfSend/Single%20Page%20Application/Extended%20Docs/README.md)

---

- [SwitfSend](SwitfSend/README.md)

---

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