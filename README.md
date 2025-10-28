# Aplicativo de Carros Elétricos

## Sobre o Autor
Oi, sou o Igor! Estou aqui para contribuir com meu conhecimento nesse aplicativo Android utilizando Kotlin. Espero poder ajudar no desenvolvimento profissional de cada um de vocês.


[![Linkedin Badge](https://img.shields.io/badge/-Igor_Bagliotti-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://br.linkedin.com/in/igor-rotondo-bagliotti-b1612b69)](https://br.linkedin.com/in/igor-rotondo-bagliotti-b1612b69)  [![Gmail Badge](https://img.shields.io/badge/-igor.bagliotti@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:igor.bagliotti@gmail.com)](mailto:igor.bagliotti@gmail.com)

<img src="https://user-images.githubusercontent.com/5827265/188477525-a7211bc6-7384-4f5f-8d49-12a8322892d1.png" width="250">


## <br />Descrição do Projeto

Este é um aplicativo para explorar informações sobre carros elétricos, construído com Kotlin e seguindo práticas modernas de desenvolvimento Android.

### Funcionalidades Implementadas

- **Arquitetura de Atividade Única (Single-Activity):** O app utiliza uma `MainActivity` como ponto de entrada principal que hospeda todos os outros fragmentos.
- **Navegação com BottomNavigationView:** A navegação principal é controlada por uma `BottomNavigationView` que permite ao usuário alternar entre as seções "Carros", "Favoritos" e "Configurações".
- **Android Navigation Component:** O fluxo de navegação entre os fragmentos é gerenciado de forma robusta e visual através do `NavHostFragment` e do gráfico de navegação (`nav_graph.xml`).
- **Cálculo de Autonomia:** Um `FloatingActionButton` na tela principal dá acesso a uma funcionalidade separada (`CalcularAutonomiaActivity`) para que o usuário possa realizar cálculos de autonomia.
- **Networking com Retrofit:** O projeto está configurado com as dependências do Retrofit, preparando o terreno para consumir APIs e buscar dados de carros elétricos de um servidor remoto.

### Tecnologias Utilizadas

- **Linguagem:** Kotlin
- **Arquitetura:** Single-Activity
- **UI:** ViewBinding, ConstraintLayout, Material Design Components
- **Navegação:** Android Navigation Component
- **Rede:** Retrofit & Gson
