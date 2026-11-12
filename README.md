# animacao2DII

Projeto Final da Disciplina **Animação 2D II**

## Descrição do Projeto

Criação do conjunto de animações de um personagem bípede para jogos 2D, desenhado e animado no **Krita** e implementado na **Unity 6**.

O personagem escolhido é um **pequeno cavaleiro**: baixinho, com armadura simples, elmo que cobre o rosto e uma espada curta. Ele foi pensado para funcionar bem no estilo gráfico **Thumbnail – silhueta**, em que o personagem é lido apenas pela forma preenchida em uma cor sólida. Por isso, ele tem elementos de silhueta bem marcados: a pluma no topo do elmo, a espada e o formato arredondado do corpo, que deixam cada pose fácil de reconhecer mesmo sem detalhes internos.

## Estilo Gráfico

- **Thumbnail – silhueta:** personagem desenhado como uma forma sólida, sem linhas internas.
- Todas as poses precisam ser legíveis só pelo contorno, então braços, pernas e espada devem ficar afastados do corpo sempre que possível.
- Fundo neutro para destacar a silhueta.

## Animações

### Idle1
- **Descrição:** o cavaleiro parado, em posição de guarda, respirando.
- **Movimento:** o corpo sobe e desce levemente; a pluma do elmo balança com um pequeno atraso.
- **Loop:** sim.

### Idle2
- **Descrição:** variação do parado, usada quando o jogador fica um tempo sem se mexer.
- **Movimento:** o cavaleiro apoia a espada no ombro, olha para os lados e volta à posição de guarda.
- **Loop:** não (toca de vez em quando e volta para o Idle1).

### Walk
- **Descrição:** caminhada normal, com passos curtos e firmes por causa da armadura.
- **Movimento:** ciclo de passos com contato, recuo, passagem e elevação; os braços balançam opostos às pernas.
- **Loop:** sim.

### Run
- **Descrição:** corrida rápida.
- **Movimento:** corpo inclinado para frente, passadas mais longas, um momento em que os dois pés ficam fora do chão; a pluma fica para trás com o vento.
- **Loop:** sim.

### Jump
- **Descrição:** pulo completo.
- **Movimento:** dividido em três partes:
  1. **Impulso:** agacha antes de pular (antecipação).
  2. **No ar:** pernas encolhidas, braços abertos para equilíbrio.
  3. **Aterrissagem:** agacha ao tocar o chão e volta à posição normal.
- **Loop:** não.

### Attack
- **Descrição:** golpe de espada.
- **Movimento:** levanta a espada para trás (antecipação), corta em arco para frente com um rastro de movimento e volta para a guarda.
- **Loop:** não.

### Hit
- **Descrição:** reação ao levar dano.
- **Movimento:** o corpo é jogado para trás, o elmo inclina e a pluma chacoalha; depois ele se recupera e volta à guarda.
- **Loop:** não.

### Dead
- **Descrição:** morte do personagem.
- **Movimento:** cambaleia, deixa a espada cair, cai de joelhos e depois tomba no chão; a pluma é a última coisa a parar de balançar.
- **Loop:** não (para no último quadro).

## Entregas

1. **Sprite sheet** de todos os movimentos.
2. **GIFs animados** de cada ação.
3. **Arquivos originais** de cada animação no formato do Krita (`.kra`).
4. **Estilo gráfico** Thumbnail – silhueta.
5. **Implementação** das animações na Unity 6.
6. **Repositório no GitHub** com o nome `animacao2DII`, contendo toda a documentação e os arquivos do projeto.

## Etapas do Processo

### 1. Pré-produção
- Definir o conceito do personagem.
- Desenhar thumbnails de silhueta para testar formas e escolher a mais legível.
- Listar as poses-chave de cada animação.

### 2. Produção (Krita)
- Animar as poses-chave (keyframes) de cada animação.
- Adicionar os quadros intermediários (in-betweens).
- Revisar o timing e os loops.
- Finalizar a silhueta e a cor.
- Salvar os arquivos originais `.kra` de cada animação.

### 3. Exportação
- Exportar cada animação como sequência de imagens.
- Montar os sprite sheets.
- Exportar os GIFs animados de cada ação.

### 4. Implementação (Unity 6)
- Importar os sprite sheets e fatiar os quadros com o Sprite Editor.
- Criar os Animation Clips de cada ação.
- Montar o Animator Controller com as transições entre os estados (Idle, Walk, Run, Jump, Attack, Hit, Dead).
- Criar um script simples de controle para testar as animações.
