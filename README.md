# dio-java-telefone
'''mermaid
classDiagram
    Iphone --> ReprodutorMusical
    Iphone --> AparelhoTelefonico
    Iphone --> NavegadorInternet
    class ReprodutorMusical{
      <<interface>>
      +tocar()
      +pausar()
      +selecionarMusica(String musica)
    }
    class AparelhoTelefonico{
        <<interface>>
      +ligar(String numero)
      +atender()
      +iniciarCorreioVoz()
    }
    class NavegadorInternet{
        <<interface>>
      +exibirPagina(String url)
      +adicionarNovaAba()
      +atualizarPagina()
    }
