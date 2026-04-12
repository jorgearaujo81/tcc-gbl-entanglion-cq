# Livro de Regras do Entanglion

> Um jogo da IBM Research

**2 JOGADORES | A PARTIR DE 14 ANOS | ~45 MINUTOS**

---

🤔 Ficou confuso com alguma regra? Consulte as [errata](Errata.md) para esclarecimentos e atualizações do jogo.

---

## Bem-vindo ao universo quântico, Capitão!

Parabéns, seu capitão se aposentou e deixou você no comando dos negócios de transporte galáctico dele! Agora é hora de fazer algumas melhorias.

Durante anos, você ficou obcecado por rumores sobre uma antiga tecnologia de computação quântica que poderia revolucionar o transporte de cargas galácticas. Se os rumores fossem verdadeiros, permitiria que suas naves calculassem trajetórias no hiperespaço em poucos segundos! Só há um problema: os antigos desmontaram seu computador quântico por medo de que fosse muito poderoso e deixaram os componentes espalhados pelos planetas da galáxia Entanglion, fortemente protegida.

Se quiser reconstruir essa tecnologia incrível, você terá que navegar com suas naves pela galáxia de Entanglion e superar as defesas deixadas pelos antigos. A boa notícia é que seu antigo capitão deixou dinheiro suficiente para equipar suas naves com os motores quânticos necessários para entrar em Entanglion. A má notícia é que, sem um computador quântico para guiá-los, esses motores podem ser um pouco… imprevisíveis.

---

## Objetivo

Entanglion é um jogo de tabuleiro cooperativo projetado para dois jogadores. O objetivo é reconstruir um computador quântico desenvolvido por uma raça ancestral. Trabalhe em conjunto com seu colega de equipe para navegar pelas três galáxias do universo quântico — Centarious, Superious e Entanglion — em uma jornada para coletar oito componentes do computador quântico. Tome cuidado para não ser detectado pelos mecanismos de defesa planetária que protegem os componentes!

---

## Conceitos de jogo

Entanglion foi projetado para expor os jogadores a vários conceitos fundamentais em computação quântica:

**Qubits** são os blocos de construção da computação quântica.

**Superposição** é quando um sistema quântico pode existir em uma combinação probabilística de vários estados ao mesmo tempo.

O **Emaranhamento** ocorre quando o estado de um qubit se correlaciona com o estado de outro qubit.

**Medição** é o processo de observação do valor clássico de um qubit.

**Erro** ocorre quando ruído aleatório no sistema quântico perturba o valor medido de um qubit.

Entanglion também expõe os jogadores aos diferentes tipos de componentes de hardware e software envolvidos na construção de um computador quântico real.

Uma discussão adicional de como Entanglion se relaciona com a computação quântica real pode ser encontrada no final deste livro.

---

## Componentes

| Componente | Quantidade |
|---|---|
| Tabuleiro do jogo | 1 |
| Tabuleiros das naves espaciais (Mercurial e Rubicon) | 2 |
| Cartões de motor | 24 (8 H, 7 CNOT, 5 X, 3 SWAP, 1 PROBE) |
| Cartões de evento quântico | 9 |
| Componentes quânticos | 8 |
| Tokens de nave espacial | 2 |
| Token de taxa de detecção | 1 |
| Dado de Entanglion (d8 amarelo) | 1 |
| Dado de Centarious (d6 binário roxo) | 1 |

---

## Configuração do jogo

**1. Coloque as placas do jogo e da nave espacial**
Coloque o tabuleiro do jogo ao alcance de cada jogador e distribua as placas da nave espacial para cada jogador.

**2. Coloque os componentes quânticos**
Embaralhe os componentes quânticos e coloque-os face a cima em cada planeta na galáxia Entanglion, um por planeta.

**3. Embaralhe a pilha de cartões do motor**
Guarde o cartão PROBE e misture os restantes cartões do motor. Coloque o cartão PROBE virado para baixo na pilha do motor; em seguida, coloque os restantes cartões do motor em cima, virados para baixo.

**4. Prepare o baralho de eventos quânticos**
Coloque de lado o cartão Quantum Shuffle e misture os cartões de evento restantes. Distribua três cartões de evento virados para baixo no baralho de eventos quânticos. Em seguida, coloque a carta Quantum Shuffle virada para baixo no baralho. Finalmente, coloque as cartas de evento restantes viradas para baixo no baralho.

**5. Defina a taxa de detecção inicial**
Coloque o token de taxa de detecção na escala de taxa de detecção. Para um jogo fácil, comece com uma taxa de detecção de 1 ou 2. Para um jogo mais desafiador, comece com uma taxa de detecção de 3. Se a taxa de detecção atingir o nível final (X) antes que o computador quântico tenha sido construído, o jogo termina em uma perda.

**6. Distribua os cartões do motor iniciais**
Cada jogador compra três cartões do motor da pilha. Os cartões do motor devem ser orientados nos espaços de controle do motor de modo que as linhas no cartão se alinhem com a linha da nave do jogador que o usou.

**7. Posicione as naves espaciais**
Cada jogador rola o dado de Centarious (d6 roxo) para determinar onde começa. Se o resultado for 0, posicione a nave no planeta ZERO. Se o resultado for 1, posicione a nave no planeta ONE. As duas naves começam na galáxia Centarious.

---

## Visão geral do turno

Em seu turno, realize **uma** das seguintes ações. Os jogadores não podem passar a vez — devem realizar uma ação.

### Ações

**Navegar**
Jogue um cartão de motor do controle de motor para navegar pelos planetas. Em seguida, compre uma carta substituta. Somente é possível jogar cartões de motor para a nave do jogador que realiza a ação.

**Trocar**
Descarte uma carta de motor da mão e compre uma carta de motor substituta.

**Recuperar**
Role o dado de Entanglion para tentar recuperar um componente quântico, se houver um presente no planeta visitado.

**Evento**
Jogue uma carta de evento quântico se o jogador possuir alguma na mão.

---

## Cartões do motor

Os cartões do motor são usados para mover as naves pelo universo quântico. Os caminhos de navegação no tabuleiro de jogo estão marcados com o(s) cartão(ões) necessário(s) para atravessá-los. Por exemplo, "X/CNOT" significa que X ou CNOT podem ser usados para atravessar esse caminho. Em alguns casos, apenas uma nave espacial pode atravessar um caminho — indicado pela cor da nave.

Os cartões do motor devem estar orientados nos espaços de controle do motor de modo que as linhas na carta se alinhem com a linha da nave do jogador que a usou. Cada jogador deve ter em suas mãos sempre três cartões de motor. Quando as cartas de motor esgotarem da pilha, deverão ser imediatamente embaralhadas e recolocadas na pilha novamente.

### Descrição dos cartões

**H (Hadamard)**
Coloca ou retira uma nave do estado de superposição. H move uma nave entre a galáxia Centarious (estados clássicos) e a galáxia Superious (estados de superposição).

**X (NOT)**
Inverte o valor de um qubit. X move uma nave entre ZERO e ONE em Centarious, ou entre PLUS e MINUS em Superious.

**CNOT (NOT Controlado)**
Usado para entrar na galáxia Entanglion e navegar dentro dela. Também inverte a posição de sua nave espacial em Centarious, mas somente quando a outra nave espacial está orbitando ONE.

**SWAP**
Troca as posições das duas naves espaciais quando ambas estão na galáxia Centarious ou Superious.

**PROBE**
Sempre que PROBE for comprado, suas naves foram descobertas por uma sonda defensiva ancestral! Role o dado de Entanglion. Se o resultado for menor que 4 (após contabilizar os efeitos dos componentes quânticos), aumente a taxa de detecção em um. Caso contrário, PROBE não tem efeito. Descarte PROBE e compre um cartão de motor substituto.

> **Nota:** Ao embaralhar a pilha de descarte para recompor o baralho, inclua PROBE no embaralhamento — não o coloque no fundo da pilha.

---

## Defesas orbitais e taxa de detecção

Os planetas em Entanglion são protegidos por defesas orbitais que escaneiam por naves procurando saquear os componentes quânticos escondidos lá. É possível evitar essas defesas usando seus motores quânticos.

Quando um jogador navega para qualquer planeta na galáxia Entanglion, deve rolar o dado de Entanglion. Se o resultado for **maior** que a taxa de detecção atual, as defesas orbitais foram evitadas. Caso contrário:

1. Role o dado de Centarious e mova **ambas as naves** para o planeta indicado pelo dado (0 ou 1) em Centarious.
2. Aumente a taxa de detecção em um.
3. Compre uma carta de evento quântico e execute a ação indicada nela.

A **taxa de detecção** aumenta em um sempre que as naves são detectadas pelas defesas orbitais ou terrestres. Ela representa a dificuldade de evadir com sucesso as defesas planetárias de Entanglion.

---

## Eventos quânticos

Os eventos quânticos são executados quando um jogador preenche todos os seis espaços de controle do motor. Também são executados sempre que um jogador é detectado pelas defesas orbitais.

Para realizar um evento quântico:
1. Compre uma carta de evento e execute suas instruções.
2. Limpe os cartões de motor do tabuleiro do jogo e coloque-os na pilha de descarte do motor.

Se dois eventos quânticos forem acionados no mesmo turno, ambos devem ser executados.

### Cartas de evento especiais

Algumas cartas de eventos possuem nomes de cientistas que fizeram contribuições significativas ao campo da física quântica e da ciência da informação quântica, como Werner Heisenberg e Erwin Schrödinger. Uma carta de evento é extra especial, nomeada após o pesquisador da IBM Charles Bennett, um dos fundadores da teoria da informação quântica e um contribuinte-chave para a descoberta do efeito de teletransporte quântico. Outras cartas de eventos são nomeadas após efeitos quânticos — como túnel quântico, erros de inversão de bit, colapso da função de onda e a "ação assustadora à distância" de Einstein. Encorajamos os jogadores interessados a pesquisar essas pessoas e tópicos para aprender mais sobre a física da informação quântica!

---

## Componentes quânticos

Há oito componentes que os jogadores devem obter para construir o computador quântico e vencer o jogo, mostrados em cada um dos tabuleiros das naves espaciais. Cada componente quântico também concede uma habilidade especial permanente ou um impedimento para a nave do jogador — por isso os jogadores devem se esforçar para obter os componentes em uma ordem otimizada. Os componentes quânticos são atualizações permanentes para o jogador que os obteve.

### Recuperando um componente quântico

Quando as naves estão orbitando um planeta que possui um componente quântico, é preciso enviar uma equipe de desembarque à superfície do planeta para recuperá-lo. Esses componentes estão protegidos por defesas terrestres automatizadas que, assim como as defesas orbitais, devem ser evitadas.

Para recuperar um componente quântico, o jogador deve rolar o dado de Entanglion:
- Se o resultado for **maior** que a taxa de detecção atual, o componente é coletado e colocado no tabuleiro da nave do jogador que o obteve.
- Se não, ambas as naves são detectadas pelas defesas terrestres, a taxa de detecção aumenta em um, e as naves permanecem em órbita no planeta atual.

> **Nota:** Após uma detecção terrestre, não é necessário realizar outra verificação de defesa orbital na próxima vez, a menos que navegue para outro planeta.

A carta de evento **Túnel Quântico** permite evitar as defesas terrestres: se for usada durante a jogada, a missão de recuperação é bem-sucedida sem necessidade de rolar o dado.

---

## Entrando e saindo de Entanglion

Para **entrar** em Entanglion:
- Uma nave espacial precisa estar em Centarious **e** a outra precisa estar em Superious.
- Apenas a nave espacial em Centarious pode usar CNOT para entrar em Entanglion.
- Os caminhos para entrar em Entanglion são representados com linhas cinzas no tabuleiro.

Para **sair** de Entanglion:
- É possível sair usando CNOT quando ambas as naves estão orbitando PHI PLUS, PHI MINUS, PSI PLUS ou PSI MINUS.
- A nave que joga o CNOT retorna para Centarious e a outra retorna para Superious, nos planetas indicados com as linhas cinzas.

> **Exemplo:** A nave Rubicon está orbitando ZERO e a nave Mercurial está orbitando PLUS. Quando Rubicon joga um CNOT, ambas as naves se movem para PHI PLUS.

> **Importante:** Fora de Entanglion, as naves se movem independentemente. Dentro de Entanglion, ambas as naves sempre se movem juntas (emaranhamento), independentemente de qual jogador joga uma carta de motor.

---

## Fim do jogo

**Vitória:** Os jogadores vencem imediatamente quando tiverem coletado todos os oito componentes do computador quântico.

**Derrota:** Os jogadores perdem imediatamente quando a taxa de detecção atingir o nível final (X).

---

## Entanglion e a computação quântica real

Entanglion reproduz um computador quântico de 2 qubits, em que as duas naves espaciais correspondem aos qubits. Cada planeta em cada galáxia representa um estado quântico diferente:

| Elemento do jogo | Conceito de computação quântica |
|---|---|
| Nave espacial | Qubit |
| Planeta ZERO / ONE | Estados clássicos \|0⟩ e \|1⟩ |
| Planeta PLUS / MINUS | Estados de superposição \|+⟩ e \|−⟩ |
| Planetas PHI PLUS, PHI MINUS, PSI PLUS, PSI MINUS | Estados emaranhados de Bell |
| Planetas OMEGA ZERO, ONE, TWO, THREE | Outros estados emaranhados |
| Cartão H (Hadamard) | Porta Hadamard — cria ou colapsa a superposição |
| Cartão X (NOT) | Porta NOT — inverte o valor de um qubit |
| Cartão CNOT | Porta NOT Controlada — emaranha dois qubits |
| Cartão SWAP | Porta SWAP — troca os estados de dois qubits |
| Movimento simultâneo das naves em Entanglion | Natureza não separável dos estados emaranhados |
| Defesas orbitais | Processo de medição clássica (medição Z) |
| Recuperar componente quântico | Teste de emaranhamento (teste de Bell) |
| Taxa de detecção | Erro de leitura / ruído em medições quânticas |
| Componentes quânticos | Componentes físicos de um computador quântico real |

### Componentes quânticos do jogo

Os oito componentes quânticos que os jogadores coletam representam os elementos físicos e lógicos necessários para construir um computador quântico real:

1. **Qubits Físicos** — Implementados em hardware via junções Josephson, armadilhas de íons ou pontos quânticos.
2. **Interconexão de Qubits** — Conexões físicas necessárias para o emaranhamento entre qubits.
3. **Refrigeração Criogênica** — Resfriamento a temperaturas extremamente baixas (~2 mK) para preservar a coerência quântica.
4. **Portas Quânticas** — H, X, CNOT, SWAP e outras portas que manipulam estados dos qubits.
5. **Programação Quântica** — Linguagens de alto nível como IBM Qiskit e OpenQASM para programar circuitos quânticos.
6. **Correção de Erros Quânticos** — Técnicas para mitigar ruídos usando múltiplos qubits físicos.
7. **Infraestrutura de Controle** — Sistema de medição dos estados internos dos qubits via micro-ondas.
8. **Blindagem Magnética** — Proteção contra campos magnéticos externos que perturbam os qubits.

---

## Créditos

**Design:** Maryam Ashoori, Justin D. Weisz  
**Ilustração:** Aaron Cox, Michael L. Kenney  
**Ciência Quântica:** Jay M. Gambetta, Jerry M. Chow, Lev S. Bishop  
**Tradução para o Português (pt-BR):** Gabriel B. de Santana, [Jorge Alexandre de Araújo](https://github.com/jorgearaujo81)

---

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  
Este trabalho está licenciado sob uma [Licença Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional](http://creativecommons.org/licenses/by-nc-sa/4.0/).
