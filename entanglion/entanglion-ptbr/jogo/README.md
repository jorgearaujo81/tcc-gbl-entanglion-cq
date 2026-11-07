# Livro de Regras do Entanglion

> Um jogo da IBM Research

**2 JOGADORES | A PARTIR DE 14 ANOS | ~45 MINUTOS**

Entanglion aguarda suas habilidades de navegação espacial e seu planejamento estratégico para explorar uma nova galáxia e reconstruir um antigo computador quântico.

http://ibm.biz/entanglion

> 🤔 Ficou em dúvida sobre alguma regra? Consulte a [errata](Errata.md) para esclarecimentos de regras e atualizações do jogo.

# Bem-vindo ao universo quântico, Capitão!

<img src="../images/bg.png" width="100%">

Parabéns, seu capitão se aposentou e deixou você no comando do negócio de transporte galáctico dele! Agora é hora de fazer algumas melhorias.

Há anos você é obcecado por rumores de uma antiga tecnologia de computação quântica que poderia revolucionar o transporte galáctico de cargas. Se os rumores fossem verdadeiros, suas naves poderiam calcular rotas pelo hiperespaço em questão de segundos! Há apenas um problema: os antigos desmontaram seu computador quântico por medo de que fosse poderoso demais e deixaram os componentes espalhados por planetas da galáxia Entanglion, fortemente vigiada.

Se você quer reconstruir essa tecnologia incrível, terá de navegar suas naves pela galáxia Entanglion e superar as defesas deixadas pelos antigos. A boa notícia é que seu velho capitão deixou dinheiro suficiente para equipar suas naves com os motores de propulsão quântica de que você precisará para entrar em Entanglion. A má notícia é que, sem um computador quântico para guiá-los, esses motores podem ser um pouco… imprevisíveis.

Acha que está à altura do desafio?

# Objetivo
Entanglion é um jogo de tabuleiro cooperativo para dois jogadores. O objetivo é reconstruir um computador quântico desenvolvido por uma raça antiga. Trabalhe em equipe com seu parceiro para navegar pelas três galáxias do universo quântico – Centarious, Superious e Entanglion – em busca de oito componentes de computador quântico. Cuidado para evitar a detecção pelos mecanismos de defesa planetária que protegem os componentes!

# Conceitos do jogo
Entanglion foi projetado para apresentar aos jogadores vários conceitos fundamentais da computação quântica: 

- **Qubits** são os blocos de construção da computação quântica.
- **Superposição** é quando um sistema quântico pode existir em uma combinação probabilística de vários estados ao mesmo tempo.
- **Emaranhamento** acontece quando o estado de um qubit se correlaciona com o estado de outro qubit.
- **Medição** é o processo de observar o valor clássico de um qubit.
- **Erro** acontece quando ruído aleatório no sistema quântico perturba o valor medido de um qubit.

Entanglion também apresenta aos jogadores os diferentes tipos de componentes de hardware e software envolvidos na construção de um computador quântico real.

Uma discussão mais detalhada de como o Entanglion se relaciona com a computação quântica real pode ser encontrada no final deste livro.

# Configuração do jogo
1. **Disponha o tabuleiro do jogo e as placas das naves espaciais**. Coloque o tabuleiro ao alcance de cada jogador e distribua as placas das naves espaciais a cada jogador.
2. **Posicione os componentes quânticos**. Embaralhe os componentes quânticos e coloque-os virados para cima em cada planeta da galáxia Entanglion, um por planeta.
3. **Embaralhe a pilha de cartas de motor**. Separe a carta PROBE e embaralhe as demais cartas de motor. Coloque a carta PROBE virada para baixo na pilha de motores e, em seguida, coloque as demais cartas de motor por cima, viradas para baixo.
4. **Prepare o baralho de eventos quânticos**. Separe a carta Embaralhamento Quântico e embaralhe as demais cartas de evento. Distribua três cartas de evento viradas para baixo no baralho de eventos quânticos. Em seguida, coloque a carta Embaralhamento Quântico virada para baixo no baralho. Por fim, coloque as demais cartas de evento viradas para baixo no baralho.
5. **Defina a taxa de detecção inicial**. Coloque a ficha da taxa de detecção na escala de taxa de detecção. Para um jogo fácil, comece com taxa de detecção 1 ou 2. Para um jogo mais desafiador, comece com taxa de detecção 3. Se a taxa de detecção chegar ao nível final (X) antes de o computador quântico ser construído, o jogo termina em derrota.
6. **Determine o primeiro jogador**. Cada jogador rola o dado de Entanglion (de 8 lados). O jogador com o número maior começa. Em caso de empate, role novamente.
7. **Determine as posições iniciais das naves**. Começando pelo primeiro jogador, role o dado de Centarious para posicionar cada nave espacial (0 vai para <span style="color: purple"> ZERO </span>, 1 vai para <span style="color: purple"> ONE </span>). Esse processo é semelhante à inicialização de um sistema quântico.
8. **Compre cartas de motor**. Começando pelo primeiro jogador, cada jogador compra três cartas de motor para a sua mão. As cartas de motor podem ser mantidas viradas para cima.

<img src="../images/setup.png" width="100%">

# Materiais

**Tabuleiros**
- 1 tabuleiro do jogo
- 2 placas de nave espacial
<img src="../images/board.png" width="40%">

**Cartas**
- 24 cartas de motor (8 H, 7 CNOT, 5 X, 3 SWAP, 1 PROBE)
<img src="../images/engine_cards.png" width="40%">

- 9 cartas de evento
<img src="../images/events.png" width="100%">

**Peças**
- 1 ficha da taxa de detecção
- 8 componentes quânticos
<img src="../images/quantum_components.png" width="100%">

- 1 dado de Centarious (d6 binário roxo)
- 1 dado de Entanglion (d8 amarelo)
- 2 fichas de nave espacial
<img src="../images/spaceship.png" width="20%">

**Livro de Regras**

# Cartas de motor
<img src="../images/engine_cards.png" width="60%">

As cartas de motor são usadas para navegar suas naves pelo universo quântico. Os caminhos de navegação no tabuleiro são identificados com a(s) carta(s) necessária(s) para percorrê-los (por exemplo, “X/CNOT” significa que X ou CNOT podem ser usados para percorrer aquele caminho). Em alguns casos, apenas uma nave espacial pode percorrer um caminho. As cartas de motor podem ser jogadas sem efeito quando nenhuma transição é indicada no tabuleiro.

**X**. X é usada para navegar entre <span style="color: purple"> ZERO </span> e <span style="color: purple"> ONE </span> e dentro da galáxia Entanglion.

**H**. H é usada para viajar entre Centarious e Superious e dentro da galáxia Entanglion.

**SWAP**. Fora de Entanglion, SWAP troca as posições das duas naves espaciais. Dentro de Entanglion, SWAP apenas faz a transição das naves entre <span style="color: #facd4d"> OMEGA ZERO </span> e <span style="color: #facd4d"> OMEGA THREE </span>.

**CNOT**. CNOT é usada para entrar na galáxia Entanglion e navegar dentro dela. Também inverte a posição da sua nave espacial em Centarious, mas somente quando a outra nave estiver orbitando <span style="color: purple"> ONE </span>.

**PROBE**. Sempre que PROBE for comprada, suas naves foram descobertas por uma antiga sonda defensiva! Role o dado de Entanglion. Se o resultado for menor que 4 (após considerar os efeitos dos componentes quânticos), aumente a taxa de detecção em um. Caso contrário, PROBE não tem efeito. Descarte PROBE e compre uma carta de motor de reposição.

> Oriente as cartas de motor nos espaços de controle de motores de modo que as linhas da carta se alinhem com a linha da sua nave espacial.

> Quando a pilha de motores se esgotar, reembaralhe imediatamente as cartas de motor da pilha de descarte para reabastecê-la. Inclua PROBE no embaralhamento; não a coloque no fundo da pilha.

# Visão geral do turno
Realize _uma_ das ações a seguir no seu turno.

1. **Navegar**. Jogue uma carta de motor no controle de motores para navegar pela galáxia e compre uma carta de reposição. Você só pode jogar cartas de motor para a sua própria nave.
2. **Trocar**. Descarte uma carta de motor da sua mão e compre uma carta de reposição.
3. **Recuperar**. Role o dado de Entanglion para tentar recuperar um componente quântico, se houver um presente.
4. **Evento**. Jogue uma carta de evento da sua mão (se você tiver uma).

> Os jogadores não podem passar a vez; devem realizar uma das ações acima.

# Entrando e saindo de Entanglion
Para entrar em Entanglion, uma nave espacial precisa estar em Centarious e a outra precisa estar em Superious. Apenas a nave espacial em Centarious pode usar CNOT para entrar em Entanglion. Os caminhos para Entanglion são representados por linhas cinza no tabuleiro.

Nave líder (jogando o CNOT) | Outra nave | Destino
--- | --- | ---
<span style="color: purple"> ZERO </span> | <span style="color: green"> PLUS </span> | <span style="color: #facd4d"> PHI PLUS </span>
<span style="color: purple"> ZERO </span> | <span style="color: green"> MINUS </span> | <span style="color: #facd4d"> PHI MINUS </span>
<span style="color: purple"> ONE </span> | <span style="color: green"> PLUS </span> | <span style="color: #facd4d"> PSI PLUS </span>
<span style="color: purple"> ONE </span> | <span style="color: green"> MINUS </span> | <span style="color: #facd4d"> PSI MINUS </span>

Também é possível sair de Entanglion usando CNOT quando ambas as naves estão orbitando <span style="color: #facd4d"> PHI PLUS </span>, <span style="color: #facd4d"> PHI MINUS </span>, <span style="color: #facd4d"> PSI PLUS </span> ou <span style="color: #facd4d"> PSI MINUS </span>. A nave que joga o CNOT retorna para Centarious e a outra nave retorna para Superious, nos planetas indicados pelas linhas cinza.

Exemplo: Rubicon está orbitando <span style="color: purple"> ZERO </span> e Mercurial está orbitando <span style="color: green"> PLUS </span>. Quando Rubicon joga um CNOT, ambas as naves se movem para <span style="color: #facd4d"> PHI PLUS </span>.

> Fora de Entanglion, as naves se movem de forma independente. Dentro de Entanglion, ambas as naves sempre se movem juntas, independentemente de qual jogador joga uma carta de motor.

<img src="../images/entering_entanglion.png" width="40%">

Em <span style="color: #facd4d"> PHI PLUS </span>, quando Rubicon joga CNOT, Rubicon se move para <span style="color: purple"> ZERO </span> e Mercurial se move para <span style="color: green"> PLUS </span>.

<img src="../images/entering_entanglion2.png" width="40%">

# Taxa de detecção
A taxa de detecção determina a dificuldade de escapar com sucesso das defesas planetárias. A ficha da taxa de detecção é usada para acompanhar a taxa de detecção atual. Quando a nave espacial de um jogador é detectada pelas defesas orbitais, ou a equipe de desembarque de um jogador é detectada pelas defesas terrestres, a taxa de detecção aumenta, facilitando para as defesas de cada planeta detectar o jogador no futuro. O jogo termina quando a taxa de detecção chega ao nível final (indicado por um X).

> A taxa de detecção aumenta em um sempre que você é detectado pelas defesas orbitais ou terrestres de um planeta.

<img src="../images/detection_rate.png" width="40%">

# Defesas orbitais
Os planetas em Entanglion são protegidos por defesas orbitais que rastreiam naves que buscam saquear os componentes quânticos escondidos ali. É possível evitar essas defesas usando seus motores quânticos. Se você for detectado, porém, seu sistema de navegação fará automaticamente manobras evasivas e saltará para um planeta aleatório do sistema Centarious. Esse salto aciona um evento quântico.

**Quando você navegar para qualquer planeta em Entanglion:** Role o dado de Entanglion. Se o resultado for maior que a taxa de detecção atual, as defesas orbitais foram evitadas. Caso contrário, execute as seguintes ações:

1. Role o dado de Centarious e mova ambas as naves para o planeta indicado. Ambas as naves saltam juntas.
2. Aumente a taxa de detecção em um.
3. Compre uma carta de evento quântico e execute a ação indicada.

> Qubits Físicos permite que você decida em quais planetas de Centarious colocar suas naves espaciais.

> Programação Quântica permite que você ignore as defesas orbitais quando um planeta não tem um componente quântico.

> A carta de evento Túnel Quântico permite que você ignore as defesas orbitais. Se você jogar esta carta depois de entrar na órbita de um planeta em Entanglion, não precisa rolar o dado de Entanglion para determinar se suas naves foram detectadas pelas defesas orbitais.

> Ao entrar em Entanglion pela carta Heisenberg, você pode ignorar as defesas orbitais.

> Se você jogar uma carta de motor que não faz a transição das suas naves para um novo planeta em Entanglion, não precisa verificar novamente se suas naves foram detectadas.

# Componentes quânticos
Há oito componentes que os jogadores devem obter para construir o computador quântico e vencer o jogo, mostrados em cada uma das placas das naves espaciais. Cada componente também concede à sua nave uma habilidade especial permanente ou uma desvantagem, então você deve traçar estratégias com seu parceiro para obter os componentes em uma ordem ideal!

> Os componentes quânticos são melhorias permanentes para a sua nave e alteram a jogabilidade para o resto do jogo.

<img src="../images/quantum_components.png" width="100%">

Quando suas naves estão orbitando um planeta com um componente quântico, você pode enviar uma equipe de desembarque à superfície do planeta para recuperá-lo. Os componentes quânticos são guardados por defesas terrestres automatizadas que, assim como as defesas orbitais, devem ser evitadas.

**Para realizar uma missão de recuperação:** Role o dado de Entanglion. Se o resultado for maior que a taxa de detecção atual, colete o componente e coloque-o na placa da sua nave espacial. Caso contrário, sua equipe de desembarque foi detectada pelas defesas terrestres; aumente a taxa de detecção em um.

> Se sua equipe de desembarque não conseguir recuperar um componente quântico, suas naves permanecem em órbita no planeta atual. Você não precisa realizar outra verificação de defesa orbital no próximo turno, a menos que navegue para outro planeta que tenha defesas orbitais.

> A carta de evento Túnel Quântico permite que você ignore as defesas terrestres. Se você jogar esta carta durante o seu turno, sua missão de recuperação foi bem-sucedida. Você não precisa rolar o dado de Entanglion para determinar se sua equipe de desembarque foi detectada pelas defesas terrestres; adicione o componente quântico à sua nave.

# Eventos quânticos
Os motores quânticos podem ser imprevisíveis às vezes! Quando todos os seis espaços de controle de motores estiverem preenchidos, execute um evento quântico no final do seu turno. Além disso, execute um evento quântico sempre que você for detectado pelas defesas orbitais.

**Para executar um evento quântico:** Compre uma carta de evento e siga as instruções. Retire todas as cartas de motor do tabuleiro e coloque-as na pilha de descarte de motores.

> Quando Embaralhamento Quântico for comprada, reembaralhe as cartas de evento quântico conforme as instruções da configuração do jogo.

> Caso sua nave seja detectada pelas defesas orbitais no mesmo turno em que você preencheu todos os seis espaços de controle de motores, execute dois eventos quânticos.

<img src="../images/events.png" width="100%">

# Fim do jogo
Os jogadores vencem imediatamente quando tiverem coletado todos os oito componentes do computador quântico. Os jogadores perdem imediatamente quando a taxa de detecção chegar ao fim (X).

# Seu primeiro jogo
Monte o tabuleiro como descrito em Configuração. Neste jogo, Mercurial (o jogador azul) começa. Mercurial compra três cartas: X, H e H. Rubicon compra três cartas: CNOT, SWAP e X. Ambas as naves começam em <span style="color: purple"> ZERO </span>.

<img src="../images/first1.png" width="40%">

1. Mercurial joga um H para navegar até <span style="color: green"> PLUS </span>. Mercurial compra X como carta de reposição.

<img src="../images/first2.png" width="40%">

2. Rubicon joga CNOT para navegar ambas as naves até <span style="color: #facd4d"> PHI PLUS </span>. Rubicon compra H como carta de reposição. Após chegar a um planeta em Entanglion, Rubicon deve rolar o dado de Entanglion para escapar das defesas orbitais. Como a taxa de detecção é 1, Rubicon precisa rolar 2 ou mais. Rubicon rola o dado de Entanglion e tira 3, o suficiente para evitar a detecção!

<img src="../images/first3.png" width="40%">
<img src="../images/first_detection.png" width="40%">

3. Mercurial decide recuperar as Portas Quânticas presentes em <span style="color: #facd4d"> PHI PLUS </span>. Mercurial rola 6, muito maior que a taxa de detecção de 1, e recupera o componente com sucesso.

<img src="../images/first4.png" width="40%">

4. Rubicon decide que o próximo destino é <span style="color: #facd4d"> OMEGA TWO </span> e joga um H para navegar ambas as naves até lá.

<img src="../images/first5.png" width="40%">

Rubicon rola o dado de Entanglion e tira 1. As naves foram detectadas, então precisam recuar! Rubicon rola 1 no dado de Centarious, então ambas as naves saltam de volta para <span style="color: purple"> ONE </span>. Como foram detectadas, a taxa de detecção aumenta em 1 e um evento quântico é acionado. Rubicon compra uma carta de evento quântico – Heisenberg – que pode ser usada em um turno futuro.

<img src="../images/first5.png" width="40%">
<img src="../images/first_detection2.png" width="40%">

O jogo continua até que Rubicon e Mercurial tenham coletado todos os componentes quânticos em Entanglion, ou até que a taxa de detecção chegue ao nível final.

# Como o Entanglion se relaciona com a computação quântica
Entanglion modela vários aspectos de um computador quântico de 2 qubits. Especificamente, as duas naves espaciais representam dois qubits, e cada planeta de cada galáxia representa um estado diferente desses qubits. As cartas de motor representam as portas quânticas usadas para fazer a transição dos qubits para estados diferentes.

A galáxia Centarious representa os estados clássicos 0 e 1, escritos em "notação ket" como ⎢0 〉(<span style="color: purple"> ZERO </span>) e ⎢1 〉(<span style="color: purple"> ONE </span>). A galáxia Superious representa estados de superposição quântica, conhecidos como ⎢+ 〉(<span style="color: green"> PLUS </span>) e ⎢- 〉(<span style="color: green"> MINUS </span>). A galáxia Entanglion representa estados de emaranhamento. Quatro dos estados emaranhados, ⎢Ψ+ 〉(<span style="color: #facd4d"> PSI PLUS </span>), ⎢Ψ- 〉(<span style="color: #facd4d"> PSI MINUS </span>), ⎢Φ+ 〉(<span style="color: #facd4d"> PHI PLUS </span>) e ⎢Φ- 〉(<span style="color: #facd4d"> PHI MINUS </span>), são conhecidos como [estados de Bell](https://en.wikipedia.org/wiki/Bell_state). Os outros estados emaranhados, que rotulamos de ⎢ω0 〉(<span style="color: #facd4d"> OMEGA ZERO </span>) a ⎢ω3 〉(<span style="color: #facd4d"> OMEGA THREE </span>), são estados adicionais que podem ser alcançados pela operação combinada das portas X, H, SWAP e CNOT.

A exigência de que ambas as naves se movam juntas dentro de Entanglion decorre do fato de que, para estados emaranhados, o estado do sistema é mais complexo do que uma simples combinação dos estados dos qubits individuais. Esta é uma das principais maneiras pelas quais a mecânica quântica difere da física clássica.

## Cartas de motor
As cartas de motor representam _alguns_ dos diferentes tipos de portas lógicas quânticas usadas por computadores quânticos.

<img src="../images/engine_cards.png" width="60%">

- **X**. A porta X inverte o valor de um qubit. Também é conhecida como porta de inversão de bit (bit flip).
- **SWAP**. SWAP troca os valores dos dois qubits.
- **CNOT**. CNOT significa "Controlled Not" (NÃO controlado). Precisa de dois qubits para funcionar: um qubit é designado o "alvo", que é invertido se o outro qubit, conhecido como "controle", tiver valor 1.
- **H**. A porta de Hadamard é usada para criar ou colapsar a superposição. É uma das portas mais importantes da computação quântica.

## Componentes quânticos
Os componentes quânticos em Entanglion representam diferentes componentes físicos ou lógicos necessários para construir um computador quântico real.

- **Qubits Físicos**. Assim como os processadores de computadores clássicos são implementados por transistores de hardware, os processadores quânticos são implementados por qubits de hardware. Há [várias maneiras diferentes](https://en.wikipedia.org/wiki/Qubit#Physical_representation) pelas quais cientistas estão criando qubits físicos, incluindo junções de Josephson, armadilhas de íons e pontos quânticos.
- **Interconexão de Qubits**. Os qubits devem estar fisicamente conectados entre si para ficarem emaranhados uns com os outros.
- **Refrigerador de Diluição**. Os qubits físicos devem ser mantidos a temperaturas muito baixas – mais frias até do que o espaço sideral – para manter sua coerência. Os refrigeradores de diluição são capazes de resfriar qubits físicos a temperaturas tão baixas quanto 2 milikelvin.
- **Portas Quânticas**. Na computação clássica, portas lógicas como AND, OR, NOT e NAND são combinadas para criar computações de ordem superior. Na computação quântica, portas quânticas como X, CNOT, SWAP e H são usadas para a computação.
- **Programação Quântica**. Para melhorar a produtividade dos programadores quânticos, são necessárias linguagens de programação quântica de mais alto nível. Por exemplo, o [IBM OpenQASM](https://github.com/IBM/qiskit-openqasm) permite programar um computador quântico com uma linguagem em estilo assembly, e o [IBM QISKit](https://qiskit.org) permite programar um computador quântico em Python.
- **Correção de Erros Quânticos**. Os qubits físicos sofrem ruído que pode causar erros durante a medição. A [correção de erros quânticos](https://en.wikipedia.org/wiki/Quantum_error_correction) é usada para corrigir esses erros. A ideia-chave da correção de erros quânticos é usar vários qubits físicos para simular um qubit lógico.
- **Infraestrutura de Controle**. Os computadores quânticos precisam de alguma forma de medir o estado interno de um qubit. A infraestrutura de controle usa radiação de micro-ondas para ler o estado de um qubit e digitalizá-lo em um estado binário (0 ou 1).
- **Blindagem Magnética**. Os qubits são extremamente sensíveis a campos magnéticos dispersos. A blindagem magnética garante que os qubits sejam protegidos de fontes externas de magnetismo.

## Cartas de evento
As cartas de evento acrescentam elementos divertidos e aleatórios ao jogo. Algumas cartas de evento têm o nome de pessoas que deram contribuições significativas para o campo da física quântica e da ciência da informação quântica, como Werner Heisenberg e Erwin Schrödinger. Uma carta de evento é particularmente especial, nomeada em homenagem ao pesquisador da IBM Charles Bennett, um dos fundadores da teoria da informação quântica e um colaborador-chave na descoberta do efeito de teletransporte quântico. Outras cartas de evento têm o nome de efeitos quânticos, como tunelamento quântico, erros de inversão de bit, colapso da função de onda e a "ação fantasmagórica à distância" de Einstein. Incentivamos jogadores ávidos a pesquisar essas pessoas e esses temas para aprender mais sobre a física da informação quântica!

<img src="../images/events.png" width="100%">

## Defesas, medição e erro
O processo de encontrar defesas orbitais ao navegar pela galáxia Entanglion é semelhante a realizar uma medição clássica (também conhecida como medição Z) sobre o estado quântico. Além disso, o ato de recuperar um componente quântico é semelhante a realizar uma medição de emaranhamento, também conhecida como [teste de Bell](https://en.wikipedia.org/wiki/Bell_test_experiments). Às vezes, o ruído no sistema quântico nos impede de ver uma medição confiável. Chamamos isso de erro de leitura. Os efeitos do ruído e dos erros são modelados por meio da taxa de detecção.

## Recursos adicionais
Recomendamos alguns recursos para aprender mais sobre computação quântica.

- [IBM Q Experience Beginner's Guide](http://ibm.biz/qx-guide), da IBM Research
- [Q is for Quantum](http://a.co/iJbiNS8), de T. Rudolph
- [Quantum Computing for Computer Scientists](http://a.co/cCZBoS9), de N. Yanofsky e M. Mannucci
- [Quantum Computation and Quantum Information](http://a.co/coZAko8), de M. A. Nielsen e I. L. Chuang
- [Quantum Computer Science: An Introduction](http://a.co/iYdi4Bv), de N. D. Mermin
- [Quantum Computing Since Democritus](http://a.co/1HzDIgF), de S. Aaronson
