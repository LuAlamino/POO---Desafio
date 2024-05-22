# POO---Desafio
Santander CODERS JAVA
```mermaid
classDiagram
    class iPhone {
        + tocar()
        + pausar()
        + selecionarMusica(String)
        + ligar(String)
        + atender()
        + iniciarCorreioVoz()
        + exibirPagina(String)
        + adicionarNovaAba()
        + atualizarPagina()
    }

    interface ReprodutorMusical {
        + tocar()
        + pausar()
        + selecionarMusica(String)
    }

    interface AparelhoTelefonico {
        + ligar(String)
        + atender()
        + iniciarCorreioVoz()
    }

    interface NavegadorInternet {
        + exibirPagina(String)
        + adicionarNovaAba()
        + atualizarPagina()
    }

    iPhone <|-- ReprodutorMusical
    iPhone <|-- AparelhoTelefonico
    iPhone <|-- NavegadorInternet
```