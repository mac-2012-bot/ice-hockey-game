# Ice Hockey Mobile Game 🏒

Um jogo de hóquei no gelo visto de cima para dispositivos móveis!

## 📱 Como jogar

### Controles:
- **Jogador Vermelho (esquerda):**
  - ↑ - Mover para cima
  - ↓ - Mover para baixo

- **Jogador Azul (direita):**
  - ↑ - Mover para cima
  - ↓ - Mover para baixo

### Objetivo:
Tenta marcar golos no adversário!
- Disco na baliza esquerda = Golo para o jogador Azul
- Disco na baliza direita = Golo para o jogador Vermelho

### Regras:
- 3 minutos de jogo
- Primeiro a 5 golos ganha
- Se empate após 3 minutos, jogo termina em empate

## 🎮 Funcionalidades

✅ **Design responsivo** - Perfeito para telemóvel
✅ **Controles touch** - Botões grandes e fáceis de usar
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
- **JavaScript** - Lógica do jogo
- **Touch events** - Controles para mobile

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

### Alterar tempo de jogo:
Edita a linha 180 no JavaScript:
```javascript
timeLeft: 180, // 3 minutos (180 segundos)
```

### Alterar pontuação para vitória:
Edita a linha 230 no JavaScript:
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