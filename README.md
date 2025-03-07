# rd-132328
 
Este projeto tem como objetivo recriar o Minecraft usando a linguagem C# e a biblioteca OpenTK.

Este é uma continuação da rd-132211:
- https://github.com/Morgs6000/rd-132211

## Ferramentas e Tecnologias
<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" /></code> VS Code

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" /></code> C#

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/opengl/opengl-original.svg" /></code> OpenGL

<code><img height="30" src="https://avatars.githubusercontent.com/u/5914736?s=280&v=4" /></code> OpenTK

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nuget/nuget-original.svg" /></code> StbImageSharp

## Adições
### Mobs
<code><img src="https://minecraft.wiki/images/thumb/Steve_JE1.png/40px-Steve_JE1.png?0814f" /></code> <code><img src="https://minecraft.wiki/images/thumb/Old_human_mob_walking_animation.gif/40px-Old_human_mob_walking_animation.gif?a4465" /></code> Mob
- Corra aleatóriamente pelo mapa agitando os braços sem IA adequada ou animação de movimento.
- O primeiro mob a ser adicionado ao jogo.
- 100 aparecem em posições aleatórias após a geração e carregamento do mundo.
- Não salve no arquivo **level.dat**.
  - Uma vez que o mundo seja fechado e reaberto, todos os mobs anteriores teriam desaparecido e novos apareceriam.
- Reutilizado de Zombie Town, um projeto abandonado feito por Notch antes do Minecraft.
- São chamados de zumbis no código.

### Geral
- O jogador deve subir lentamente até o nível do solo se aparecer sob o mundo. No entanto, isso não é possível aparecer no mundo sem modificação, por isso não é usado.

## Curiosidades
- O "rd" antes do número da versão significa RubyDung, um jogo em que Notch estava trabalhando antes do Minecraft, cuja base de código foi posteriormente reutilizada para o Minecraft.
- O nível mundial mais antigo conhecido publicamente do Minecraft é para esta versão.
- Esta versão marca a primeira aparição de Steve no Minecraft.

## Referencias
- https://minecraft.wiki/w/Java_Edition_pre-Classic_rd-132328

## To-Do

## Progresso
