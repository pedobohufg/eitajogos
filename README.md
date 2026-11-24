# EITA! Jogos

Plataforma de jogos do **Lab.EITA – Laboratório de Estudos Inventivos em Tecnologias Assistivas** (Universidade Federal de Goiás).

São jogos para reabilitar, incluir e conscientizar. Funcionam no navegador e no **Meta Quest 3**, com rastreamento das mãos (WebXR).

## Jogos

| Jogo | Arquivo | O que treina |
|---|---|---|
| EITA! Alcance | `eita-alcance.html` | Ombro, cotovelo e tempo de reação: alcançar alvos parados, flutuando ou caindo |
| EITA! Pinça | `eita-pinca.html` | Coordenação fina: pegar objetos pequenos com polegar e indicador |
| EITA! Amplitude | `eita-amplitude.html` | Amplitude de movimento do ombro: seguir guias em arcos, círculos e diagonais |
| EITA! Preensão | `eita-preensao.html` | Força e controle da mão: abrir e fechar a mão para pegar e soltar |
| EITA! Bimanual | `eita-bimanual.html` | Coordenação entre as duas mãos: carregar a bandeja nivelada |
| EITA! Calçada | `eita-calcada.html` | Educação e acessibilidade: um bairro visto da cadeira de rodas, com barreiras da NBR 9050 nos modos "hoje" e "acessível" |

A página inicial (`index.html`) reúne todos os jogos. Nela se escolhe o paciente uma vez, e o código dele segue para cada jogo. A mesma página mostra o histórico de sessões e relatórios de evolução.

## Como usar

- **Online:** publicado pelo GitHub Pages em `https://pedobohufg.github.io/eitajogos/`, quando o Pages estiver ativado.
- **No computador:** abra o `index.html` num navegador recente. Fora do VR, os jogos rodam em modo de teste com mouse e teclado.
- **No Meta Quest 3:** abra o endereço no navegador do Quest e toque em "Entrar em VR". As mãos aparecem translúcidas: azuis normalmente e laranja quando estão segurando algo. A opção "Ver a sala real (passthrough)" vem desligada, para o cenário do jogo aparecer.
- **EITA! Calçada no VR:** segure os aros das rodas, fechando a mão ou apertando o botão lateral do controle, e empurre para a frente. Cada mão move a roda do seu lado. Para virar, empurre um aro mais que o outro. Segurar os aros parados freia a cadeira. O joystick continua funcionando como alternativa.

## Dados

As sessões ficam salvas só no navegador do aparelho (`localStorage`). Nada é enviado a servidores. Para juntar os dados de vários aparelhos, use **Copiar backup** e **Importar backup** na página inicial.

## Tecnologia

São arquivos HTML autocontidos, feitos com [Three.js](https://threejs.org/) (carregado via CDN) e WebXR. Não há etapa de build.

---
Lab.EITA · Universidade Federal de Goiás
