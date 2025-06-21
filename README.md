🟡 Pac-Man Clone com Pygame
Este projeto é uma recriação do clássico Pac-Man, desenvolvida com Python e a biblioteca Pygame, com o objetivo de praticar conceitos de programação de jogos, manipulação gráfica e estruturação de projetos.

🕹️ Sobre o Jogo
O jogo simula a jogabilidade do Pac-Man original, com labirinto, pontos, quatro fantasmas (vermelho, azul, rosa e laranja), sistema de vidas, modo de invencibilidade e animações personalizadas. Os movimentos dos personagens são realizados com base em coordenadas e colisões no mapa.

Funcionalidades
✅ Movimento fluido do Pac-Man com animação de 17 sprites
👻 Quatro fantasmas com sprites e direções independentes
🧠 Sistema de inteligência rudimentar com cálculo de distância ao Pac-Man
🍒 Modo de invencibilidade temporária (fantasmas ficam "inofensivos")
🧱 Mapa labiríntico inspirado no original
💯 Sistema de pontuação e vidas
🎨 Visual retro com sprites personalizados carregados via pygame.image.load()

🛠️ Tecnologias e Recursos
Python 3
Pygame
Sprites PNG personalizados
Fonte: Courier New para a pontuação e vidas
Lógica baseada em vetores, distâncias e orientação

📁 Estrutura do Projeto
css
Copiar
Editar
pacman/
│
├── img/
│   ├── Pac_Man_1.png ... Pac_Man_17.png
│   ├── Blue_Ghost_Down_Right_0.png ...
│   ├── Harmless_Ghost_0.png ...
│
├── pacman.py
├── README.md
└── requirements.txt
🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/pacman-clone.git
cd pacman-clone
Instale as dependências:

bash
Copiar
Editar
pip install pygame
Execute o jogo:

bash
Copiar
Editar
python pacman.py
⚠️ Certifique-se de que a pasta img/ com os sprites esteja no mesmo diretório do script.

🎯 Objetivos de Aprendizado
Este projeto tem como objetivo:
Aplicar programação orientada a objetos
Trabalhar com sprites e eventos gráficos
Implementar lógica de movimentação e colisão
Criar um jogo 2D funcional e interativo em Python

📌 Próximos Passos
🧠 Melhorar a inteligência artificial dos fantasmas
📱 Adicionar tela de menu, som e sistema de níveis
💾 Adicionar placar de recordes
🌐 Gerar uma versão executável (.exe)

📄 Licença
Este projeto é de código aberto e livre para uso educacional.
