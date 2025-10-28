# Aplicativo de Carros Elétricos
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
