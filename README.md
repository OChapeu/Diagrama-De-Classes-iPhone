# Diagrama-De-Classes-iPhone

classDiagram
    class ReprodutorMusical {
        +tocar(): void
        +pausar(): void
        +selecionarMusica(): void
        +avancarMusica():void
        +voltarMusica():void
    }

    class AparelhoTelefonico {
       +Ligar(numero: String): void
       +Atender(numero: String): void
    }

    class NavegadorInternet {
        +exibirPagina(url: String):void
        +criarNovaPagina(url: String):void
        +atualizarPagina():void
        +fecharPagina():void
    }

    class iPhone {
        +tocar(): void
        +pausar(): void
        +selecionarMusica(): void
        +avancarMusica():void
        +voltarMusica():void
        +Ligar(numero: String): void
        +Atender(numero: String): void
        +exibirPagina(url: String):void
        +criarNovaPagina(url: String):void
        +atualizarPagina():void
        +fecharPagina():void

    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
