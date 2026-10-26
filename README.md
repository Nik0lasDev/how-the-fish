# How to Fish — Island Run

Protótipo 3D para navegador inspirado no ciclo de jogo de *How to Fish*: explorar uma ilha, pescar criaturas, lutar, vender capturas, comprar equipamento e liberar novas ilhas.

## Jogar

- Abra **Settings → Pages** no repositório e configure **Build and deployment → Source: GitHub Actions**.
- Depois que o workflow terminar com sucesso, o jogo ficará disponível em:
  **https://nik0lasdev.github.io/how-the-fish/**

## Controles

| Tecla / ação | Função |
| --- | --- |
| WASD | Mover |
| Mouse | Olhar ao redor |
| F | Lançar ou recolher a linha |
| Clique esquerdo | Atacar uma criatura próxima |
| E | Interagir, vender capturas ou usar o NPC |
| Q | Abrir a loja |
| 1 / 2 | Seleção rápida de equipamento |
| Shift | Correr |
| R | Viajar para a próxima ilha já desbloqueada |
| Esc | Pausar / liberar o mouse |

## Sistemas incluídos

- Cena 3D com ilhas, água, vegetação, cais, NPCs e criaturas.
- Pesca com tempo de mordida, variantes raras e captura vendável.
- Combate corpo a corpo e arpão, com criaturas-chefes.
- Dinheiro, inventário de capturas, loja de varas, armas e iscas.
- Progressão de ilhas ligada à derrota dos chefes.
- Interface adaptável para desktop e telas menores.

## Estado do projeto

Esta é a primeira versão jogável, não uma reprodução completa. O protótipo ainda precisa de melhorias em animações, física real da linha e das criaturas, modelos 3D, missões, salvamento, áudio e testes em diferentes navegadores. A cena usa Three.js por CDN, então é necessária conexão com a internet para carregar a biblioteca.

O projeto usa código e formas 3D originais, sem extrair assets do jogo comercial.

## Referência

O jogo que inspira o projeto é [How to Fish, de Dazed Games](https://store.steampowered.com/app/4001890/). Este projeto é um protótipo de fã não oficial e não é afiliado aos desenvolvedores originais.
