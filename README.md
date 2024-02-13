# Cena 3D de múltiplas janelas usando Three.js

## Introdução
Este projeto demonstra uma abordagem única para criar e gerenciar uma cena 3D em várias janelas do navegador usando Three.js e localStorage. Ele foi projetado para desenvolvedores interessados ​​em gráficos avançados da web e técnicas de gerenciamento de janelas.

## Características
- Criação e renderização de cenas 3D com Three.js.
- Sincronização de cenas 3D em múltiplas janelas do navegador.
- Gerenciamento dinâmico de janelas e sincronização de estado usando localStorage.

## Instalação
Clone o repositório e abra `index.html` em seu navegador para começar a explorar a cena 3D.

```
clone do git https://github.com/Yawked/JanelasMultiplas3D.git
```
## Uso
A lógica principal do aplicativo está contida em `main.js` e `WindowManager.js`. A cena 3D é renderizada em `index.html`, que serve como ponto de entrada da aplicação.

## Estrutura e Componentes
- `index.html`: Ponto de entrada que configura a estrutura HTML e inclui a biblioteca Three.js e o script principal.
- `WindowManager.js`: classe principal que gerencia a criação de janelas, sincronização e gerenciamento de estado em várias janelas.
- `main.js`: Contém a lógica para inicializar a cena 3D, manipular eventos de janela e renderizar a cena.
- `três.r124.min.js`: Versão reduzida da biblioteca Three.js usada para renderização de gráficos 3D.

## Funcionalidade detalhada
- `WindowManager.js` lida com o ciclo de vida de várias janelas do navegador, incluindo criação, sincronização e remoção. Ele usa localStorage para manter o estado nas janelas.
- `main.js` inicializa a cena 3D usando Three.js, gerencia os eventos de redimensionamento da janela e atualiza a cena com base nas interações da janela.

## Contribuindo
Contribuições para melhorar ou expandir o projeto são bem-vindas. Sinta-se à vontade para bifurcar o repositório, fazer alterações e enviar solicitações pull.

## Licença
Este projeto é de código aberto sob a licença MIT.

## Agradecimentos
- A equipe Three.js por sua abrangente biblioteca 3D.
- x.com/didntdrinkwater para este leia-me.

## observação
Esse projeto é uma releitura alterada de um projeto já existente, o criador pelo repositório original e seu git, está aqui >> https://github.com/bgstaal
