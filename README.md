# POO - Desafio

### Modelagem e Diagramação de um Componente iPhone

Desafio para modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### Funcionalidades a Modelar

1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo

- Criar um diagrama UML que represente as funcionalidades descritas acima.

### Diagrama UML

```mermaid
classDiagram
    class ReproduzirMusica {
        + tocar() 
        + pausar() 
        + selecionarMusica(String musica) 
    }

    class AparelhoTelefonico {
        + ligar(String Numero) 
        + atender() 
        + iniciarCorreioVoz() 
    }

    class Navegador {
        + exibirPagina(String url) 
        + adicionarNovaAba() 
        + atualizarPagina() 
    }

    class Iphone {
    }
    Iphone --> ReproduzirMusica
    Iphone --> AparelhoTelefonico
    Iphone --> Navegador
```
