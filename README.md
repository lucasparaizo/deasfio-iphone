# Desafio POO JAVA Backend DIO

Neste módulo foi passados os conceitos e pilares do paradigma orientado a objetos. 
O desafio proposto consiste em criar um diagrama de classes UML e simular de maneira básica algumas funções do iphone, sendo elas :

1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`
   - 

## Ferramentas e tecnologias utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Diagrama UML

Conforme sugerido, foi utilizada a plataforma Mermaid (mermaid.js.org), a qual utiliza de um código compatível com o Markdown.

```mermaid
classDiagram
  SistemaOperacional <|-- Iphone
  Iphone <|-- ReprodutorMusical
  Iphone <|-- AparelhoTelefonico
  Iphone <|-- NavegadornaInternet
  class ReprodutorMusical{
        +selecionarMusica(string musica)
        +tocar()
        +pausar()
  }
  class AparelhoTelefonico{
        +ligar(string numero)
        +atender()
        +iniciarCorreioVoz()
  }
  class NavegadornaInternet{
        +exibirPagina(string url)
        +adicionarNovaAba()
        +atualizarPagina()
  }

```

### Controles e funcionamento

O dispositivo será controlado através de um menu de opções, aonde cada número representará uma opção, sendo eles :
 - Comandos :
   - 1 - Reprodutor Musical
   - 2 - Aparelho Telefonico
   - 3 - Navegador na Internet
   - 4 - Sair





