# Ice Hockey Mobile Game 🏒

Um jogo de hóquei no gelo visto de cima para dispositivos móveis!

## 📱 Como jogar

### Controles (Swipe/Touch) - MULTI-TOUCH:
- **Toca no lado ESQUERDO** da tela → Move o jogador VERMELHO (cima/baixo)
- **Toca no lado DIREITO** da tela → Move o jogador AZUL (cima/baixo)
- **Podes tocar em AMBOS os lados** → Controla os DOIS jogadores ao mesmo tempo!
- **Desliza para CIMA/BAIXO** → Move o jogador respetivo na vertical

**Multi-touch suportado!** 👆👆

**Experiência mobile perfeita!** 👆📱

### Objetivo:
Tenta marcar golos no adversário!
- **Disco já começa em movimento!** 🔥
- **Disco ricocheteia nas paredes!** 🔄
- **Balizas em cima e em baixo** como num jogo de hóquei real!
- Golo no topo = Jogador Vermelho marca
- Golo na base = Jogador Azul marca

### Regras:
- Primeiro jogador a 5 golos ganha
- Jogo continua até alguém atingir 5 golos
- Empate possível se ambos atingirem 5 golos ao mesmo tempo

## 🎮 Funcionalidades

✅ **Design responsivo** - Perfeito para telemóvel
✅ **Controles touch** - Swipe para mover jogadores
✅ **Disco em movimento** - Começa já a mover-se desde o início! 🔥
✅ **Física de ricochete** - Disco ricocheteia nas paredes! 🔄
✅ **Balizas em cima/baixo** - Como num jogo de hóquei real! 🏒
✅ **Física realista** - Disco move-se com inércia
✅ **Colisões** - Jogadores batem no disco
✅ **Sistema de pontuação** - Mostra gols de ambos os jogadores
✅ **Timer** - 3 minutos de jogo
✅ **Tela de fim de jogo** - Mostra vencedor e permite reiniciar

## 🚀 Como jogar

1. **Abrir no telemóvel:**
   - Acede a este link: [https://ice-hockey-game.vercel.app](https://ice-hockey-game.vercel.app)
   - Ou faz download dos ficheiros e abre o `index.html` num navegador

2. **Jogar:**
   - Usa os botões de controlo para mover os jogadores
   - Tenta marcar golos no adversário
   - O jogo termina quando:
     - Alguém fizer 5 golos
     - O tempo acabar

## 🛠️ Tecnologias usadas

- **HTML5** - Estrutura do jogo
- **CSS3** - Estilos e animações
- **JavaScript** - Lógica do jogo e controles por swipe
- **Touch events** - Controles para mobile
- **Event listeners** - Para deteção de swipe/touch

## 🎨 Design

- **Tema:** Hóquei no gelo com cores vibrantes
- **Cores:** Vermelho vs Azul
- **Fundo:** Gradiente azul e vermelho
- **Elementos:** Pista de gelo, jogadores circulares, disco preto

## 📱 Responsive Design

O jogo adapta-se automaticamente a:
- Telemóveis (tamanho padrão)
- Tablets
- Desktop (com controles de rato)

## 🔧 Personalização

Para personalizar o jogo:

### Alterar pontuação para vitória:
Edita a linha 200 no JavaScript:
```javascript
if (gameState.scoreRed >= 5 || gameState.scoreBlue >= 5) {
```

### Alterar velocidade do disco:
Edita a linha 181 no JavaScript:
```javascript
puckSpeed: 2,
```

### Alterar cores dos jogadores:
Edita o CSS na secção `.player` e `.player.blue`

## 📁 Estrutura do projeto

```
ice-hockey-game/
├── index.html          # Página principal do jogo
└── README.md           # Documentação
```

## 🌐 Publicação

### Opção 1: Vercel (Recomendado)
1. Cria uma conta em [Vercel](https://vercel.com)
2. Faz upload dos ficheiros
3. O jogo será publicado automaticamente

### Opção 2: GitHub Pages
1. Cria um repositório no GitHub
2. Faz upload dos ficheiros
3. Ativa o GitHub Pages nas settings

### Opção 3: Servidor web
1. Faz upload dos ficheiros para o teu servidor
2. Acede ao jogo via URL

## 🎯 Dicas para melhorar

- Adicionar sons (gol, colisão, whistle)
- Adicionar animações para golos
- Adicionar power-ups
- Adicionar modo multiplayer (2 jogadores no mesmo dispositivo)
- Adicionar níveis de dificuldade
- Adicionar high scores

## 📝 Notas

- O jogo usa touch events para controles móveis
- O disco move-se com física simples
- Os jogadores movem-se verticalmente
- O jogo é 100% client-side (não precisa de servidor)

## 🔗 Links úteis

- [Vercel](https://vercel.com) - Hospedagem gratuita
- [GitHub](https://github.com) - Controlo de versão
- [MDN Web Docs](https://developer.mozilla.org) - Referência web

## 📧 Contacto

Para questões sobre o jogo:
- Email: mac.2012.bot@outlook.pt

---

**Desenvolvido por Mac Bot** 🏒🔥

Game criado em: Maio 2026