# Automação do Site Cooperativa Unimed

Verificar suas habilidades em elaborar cenários de testes e em programação necessárias para automatização dos testes no site Cooperativa Unimed.

## Desafio

1 - No site https://www.unimed.coop.br/ validar a seguinte sequência de ações: 

    • Acessar Guia Médico 
    • Realizar uma pesquisa de médicos no Rio de Janeiro.
    • Validar a apresentação dos resultados com a Especialidade e Cidade.

2 - No mesmo site, validar: 
    
    • Acessar Guia Médico 
    • Realizar uma pesquisa de médicos no Rio de Janeiro. 
    • Validar nas páginas 1, 2, e 3 do resultado, NÃO apresentação do resultado com cidade São Paulo  

### Regras:

- Criar um projeto de automação utilizando BDD e Java conforme os cenários das funcionalidades acima. 

## Método

Os procedimentos adotados foi o uso de algumas ferramentas como suporte para o desenvolvimento do projeto. Um computador com Sistema Operacional Windows 10 home Single Language (Desktop) foi utilizado e nele foram instalados algumas ferramentas:


1. IntelliJ IDEA Community Edition 2020.2
2. Dependências do Maven
    - Cucumber Java 1.2.5
    - Cucumber Junit 1.2.5
    - Selenium Java 3.141.59
    - Commons IO 2.7
3. Versão [ChromeDriver 85.0.4183.87](https://chromedriver.chromium.org/downloads)

## Instalação :floppy_disk:

### **1.** Para instalar IntelliJ IDEA Community Edition 2020.2
No site da [Jetbrains.com](https://confluence.jetbrains.com/pages/viewpage.action?pageId=54920165) você encontra os passos necessário para instalar o _IntelliJ IDEA Community Edition 2020.2_ em seu computador.

### **2.** Dependências Maven do Projeto
**_Cucumber Java:_**
```sh
<dependency>
    <groupId>info.cukes</groupId>
    <artifactId>cucumber-java</artifactId>
    <version>1.2.5</version>
</dependency>
```

**_Cucumber Junit:_**
```sh
<dependency>
    <groupId>info.cukes</groupId>
    <artifactId>cucumber-junit</artifactId>
    <version>1.2.5</version>
    <scope>test</scope>
</dependency>
```

**_Selenium Java:_**
```sh
<dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>3.141.59</version>
</dependency>
```

**_Commons IO:_**
```sh
<dependency>
    <groupId>commons-io</groupId>
    <artifactId>commons-io</artifactId>
    <version>2.7</version>
</dependency>
```        
 
## Como abrir o projeto e executar!
- O projeto deve ser clonado da forma simples do Github de como [Clonar um repositório](https://docs.github.com/pt/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

- Ou pode ser clonado e executado no [IntelliJ IDEA Community Edition 2020.2](https://www.jetbrains.com/help/idea/import-project-or-module-wizard.html#open-project) como exemplificado no tutorial.



## Histórico de lançamentos

* 0.1.0
    * O primeiro lançamento adequado

## Meta
Raul Batalha 

[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2Fraulbatalha)](https://twitter.com/raulbatalha) [![GitHub stars](https://img.shields.io/github/stars/RaulBatalha?tab=stars)](https://github.com/RaulBatalha?tab=stars)