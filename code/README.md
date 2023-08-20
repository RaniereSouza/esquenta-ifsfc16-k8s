[[Esquenta #02][Live #02]](https://www.youtube.com/watch?v=CeDbTplpKl4) Kubernetes:
===================================================================================
## *(Descrição em breve...)*

---

## Como rodar
1. (Passos em breve...)

---

## Problemas conhecidos
* **`kubectl` "Connection Refused":** Quando o devcontainer é parado e iniciado novamente depois (mesmo quando pedimos para buildá-lo novamente), o `kubctl` pode não conseguir se conectar mais com o cluster, é como se não tivesse conexão disponível para isso na porta esperada. Uma das ocasiões em que isso não aconteceu, foi quando o devcontainer buildou e iniciou pela primeira vez. Outra situação em que isso não aconteceu foi quando fechei a conexão remota, fechei o VS Code, encerrei o Docker, iniciei o Docker novamente um tempo depois, abri o VS Code e reabri o devcontainer.
