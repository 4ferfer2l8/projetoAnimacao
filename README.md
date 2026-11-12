# animacao2DII

Projeto Final da Disciplina **Animação 2D II**

## Descrição do Projeto

Criação do conjunto de animações de um personagem bípede para jogos 2D, desenhado e animado no **Krita** e implementado na **Unity 6**.

## Contexto

Jogo plataforma 2D de ação curta, em fases (floresta, caverna, ponte e castelo), e um chefe no final. O jogo será desenvolvido para PC e distribuído pela Steam, para um público-alvo de jovens e adultos que gostem de jogos plataforma e jogos de ação curta.

## Personagem

O personagem escolhido é um **pequeno cavaleiro**: baixinho, 25 anos de idade, com armadura simples, elmo que cobre o rosto e uma espada curta. Ele é carismático, educado e romântico, seu único objetivo é salvar e conquistar o coração da princesa. Ele foi pensado para funcionar bem no estilo gráfico **Thumbnail – silhueta**, em que o personagem é lido apenas pela forma preenchida em uma cor sólida. Por isso, ele tem elementos de silhueta bem marcados: a pluma no topo do elmo, a espada e o formato arredondado do corpo, que deixam cada pose fácil de reconhecer mesmo sem detalhes internos.

## Estilo visual

- **Thumbnail – silhueta:** personagem desenhado como uma forma sólida, sem linhas internas.
- Traço: Formas arredondadas, com bordas limpas e firmes. Formas pontudas apenas na espada.
- Paleta de cores:
  - Silhueta do personagem: Azul escuro, quase preto.
  - Pluma: Vermelho.
  - Brilho da espada / rastro do ataque: Branco azulado.

## Animações pedidas

| Animação | Desenhos | Repete? | Descrição |
| --- | --- | --- | --- |
| Idle1 | 6 | Sim | Cavaleiro parado, em posição de guarda, respirando. |
| Idle2 | 10 | Não | Variação do parado, usada quando o jogador fica um tempo sem se mexer. |
| Walk | 6  | Sim | Caminhada normal, com passos curtos e firmes por causa da armadura. |
| Run | 6 | Sim | Corrida rápida. |
| Jump | 9 | Não | Pulo completo. |
| Attack | 8 | Não | Golpe de espada. |
| Hit | 4 | Não | Reação ao levar dano. |
| Dead | 10 | Não | Morte do personagem. |

## Requisitos técnicos

| Item | Pedido | 
| --- | --- | 
| Tamanho | 256 x 256 | 
| FPS | 12 | 
| Formato | Spritesheet |
| Nomes | personagem_acao_01.png | 

## Entregas

1. **Sprite sheet** de todos os movimentos.
2. **GIFs animados** de cada ação.
3. **Arquivos originais** de cada animação no formato do Krita (`.kra`).
4. **Estilo gráfico** Thumbnail – silhueta.
5. **Implementação** das animações na Unity 6.
6. **Repositório no GitHub** com o nome `animacao2DII`, contendo toda a documentação e os arquivos do projeto.
