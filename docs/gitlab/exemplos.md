# Exemplos de Códigos

## Abas

!!! example "Exemplo"
    ~~~
    === "Comando"
        /ip firewall add 
    
    === "Exmplo de Uso"
        /ip firewall add bla bla
    ~~~
    
!!! done "Resultado"
    === "Comando"
        /ip firewall add 
    
    === "Exmplo de Uso"
         /ip firewall add bla bla

## Adicinando imagens

Use `![texto](link)`

!!! example "Exemplo"
    `![Logo Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)`

!!! done "Resultado"
    ![Logo Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)

## Adicionando links

Use `[texto](link)`

!!! example "Exemplo"
    `[Site Google](https://www.google.com)`

!!! done "Resultado"
    [Site Google](https://www.google.com)

## Bloco de código

!!! example "Exemplo"

    ~~~
    ``` python
    import tensorflow as tf
    ```
    ~~~

!!! done "Resultado"
    ``` python
    import tensorflow as tf
    ```

## Bloco de código com linhas grifadas

!!! example "Exemplo"

    ~~~
    ``` python hl_lines="1 3"
    import tensorflow as tf
    ```
    ~~~

!!! done "Resultado"
    ``` python hl_lines="1 3"
    import tensorflow as tf
    import math
    import rand
    ```

## Bloco de código com linhas numeradas

!!! example "Exemplo"
    ~~~
    ``` python linenums="1"
        def bubble_sort(items):
            for i in range(len(items)):
                for j in range(len(items) - 1 - i):
                    if items[j] > items[j + 1]:
                        items[j], items[j + 1] = items[j + 1], items[j]
    ```
    ~~~

!!! done "Resultado"
    ``` python linenums="1"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```

## Listas

=== "Listas Simples"
    !!! example "Exemplo"
        Use `-` para iniciar a lista
        ```markdown
        - Item 1
        - Item 2
        - Item 3
        ```
    !!! done "Resultado"
        - Item 1
        - Item 2
        - Item 3

=== "Lista Numerada"
    !!! example "Exemplo"
        Use `1.` para iniciar a lista
        ```markdown
        1. Item 1
        1. Item 2
        1. Item 3
        ```
    !!! done "Resultado"
        1. Item 1
        1. Item 2
        1. Item 3

## Notas

Use "!!! <tipo da nota\> "<tirulo\>" <br>
<Texto a ser exibido\>

!!! example "Exemplo"
    ```markdown
    !!! note "Observação"
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.
    ```
!!! done "Resultado"
    !!! note "Observação"
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.

## Notas sem título

!!! example "Exemplo"
    ```markdown
    !!! note ""
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.
    ```
!!! done "Resulado"
    !!! note ""
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.


## Notas expansíveis

=== "Fechadas"
    !!! example "Exemplo"
        ```markdown
        ??? Observação
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
        nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
        massa, nec semper lorem quam in massa.
        ```

    !!! done "Resultado"
        ??? Observação
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
            nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
            massa, nec semper lorem quam in massa.

=== "Abertas"
    !!! example "Exemplo"
        ```markdown
        ???+ Observação
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
            nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
            massa, nec semper lorem quam in massa.
        ```

    !!! done "Resultado"
        ???+ Observação
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
            nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
            massa, nec semper lorem quam in massa.

### Tipos de notas e seus icones

??? tip "Lista com os tipos e seus icones"

    !!! note Nota
        `!!! note `
    
    !!! tldr Tldr
        `!!! tldr `
    
    !!! info
        `!!! info`
    
    !!! tip
        `!!! tip`
    
    !!! done
        `!!! done`
    
    !!! faq
        `!!! faq`
    
    !!! warning
        `!!! warning`    
    
    !!! fail
        `!!! fail`
    
    !!! danger
        `!!! danger`
    
    !!! bug
        ` !!! bug`
    
    !!! example
        ` !!! example`
    
    !!! quote
        `!!! quote`

## Usando emojis

!!! example "Exemplo"
    \:smile:

!!! done "Resultado"
    :smile: 

## Usando icons

Para usar utilize `:<pacote de icone>-<nome do icone>:`

Pacotes existentes: material, fontawesome e octicons

!!! example "Exemplo"
    - :material-arrow-collapse-all\:
    - :fontawesome-regular-laugh-wink\:
    - :octicons-octoface-16\:

!!! done "Resultado"
    - :material-arrow-collapse-all:
    - :fontawesome-regular-laugh-wink:
    - :octicons-octoface-16:

!!! tip "Links para visualizar os nomes e icones"
    - [Material](https://materialdesignicons.com/)
    - [Font Awesome](https://fontawesome.com/icons?d=gallery)
    - [Octicons](https://primer.style/octicons/)


