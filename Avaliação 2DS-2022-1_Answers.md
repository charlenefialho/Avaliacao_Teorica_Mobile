# Avaliação 2DS-2022-1


## 1)Descreva a arquitetura do sistema operacional Android
    O sistema Operacional android usa como base o kernel do linux sendo a parte mais baixa da estrutura e onde se faz o contato direto com o hardware e drivers.

    Acima do Linux Kernel temos o "HAL" que que seria um tipo de "ponte" entre o software e o hardware quando haver uma chamada do software para fazer o uso de algum componente como por exemplo o bluetooth e  a camera.

    Mais acima temos as camadas android runtime e as nativeC/C++Libraries onde o android runtime contem conjunto de bibiliotecas de tempo de execução e o ART é o sistema de execução padrão para dispositivos que executam android 5.0 e versões superiores

    a nativeC/C++Libraries são bibliotecas nativas progamadas em C eC++ e fazem parte da estrutura pois varios dos componentes do android são implementados(como por exemplo o HAl) por codigo nativo e exige essas bibliotecas.

    Logo acima temos a camda de estrutura da Java Api onde sâo APIs programadas em Java que da a disponibilidade dos recursos do sistema android que são necessarios para a criação de APPs android permitindo de forma simplifica a reutilização de serviços e componentes do sistema.
    Agora o topo da camada o "System Apps" que são os aplicativos principais que ja vem programado   para o usuario utilizar como por exemplo email,calendario,contatos e etc.
## 2)Descreva como desenvolvemos interfaces em aplicações Android nativas em Kotlin
        Primeiramente em Project dentro de Res>layout abrimos o activity_main.xml assim abriremos o layout editor onde temos no Palette com opções paa acrescentar texto,botões, widgets e etc.Em baixo temos o Component Tree onde podemos ver o "historico" do que foi adicionado e temos as constrains e são elas que definem a posição de cada visualização do lado esquerdo mostra-se todos os atributos da vizualização podendo mudar o nome a rotação o tamanho e etc.




