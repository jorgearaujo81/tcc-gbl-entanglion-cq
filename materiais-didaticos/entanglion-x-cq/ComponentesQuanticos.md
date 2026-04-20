# Componentes Quânticos — Entanglion x Computação Quântica

> Este material é um guia didático de apoio ao jogo Entanglion. Ele conecta cada componente quântico ao seu equivalente real em um computador quântico, ajudando professores e alunos a aprofundar o aprendizado além do jogo.

---

## Qubits Físicos

**No jogo:** Quando detectado pelas defesas orbitais, você pode escolher para qual planeta em Centarious suas naves vão.

**O que representa:**  
Os processadores quânticos são implementados por meio de qubits de hardware. Existem diversas abordagens físicas, incluindo junções Josephson (supercondutores), armadilhas de íons e pontos quânticos. Cada abordagem tem vantagens e desafios diferentes em termos de coerência, escalabilidade e temperatura de operação.

**Conexão com o jogo:**  
O controle sobre o destino das naves após a detecção representa a capacidade dos qubits físicos de serem manipulados e reposicionados — mesmo após sofrer interferência do ambiente externo, o sistema pode ser reinicializado para um estado conhecido.

---

## Interconexão de Qubits

**No jogo:** Permite trocar uma carta de motor com o outro jogador quando as naves estão no mesmo planeta.

**O que representa:**  
Para que o emaranhamento quântico ocorra, os qubits precisam estar fisicamente conectados entre si, permitindo a interação necessária para a execução de operações quânticas de dois qubits, como a porta CNOT.

**Conexão com o jogo:**  
A troca de cartas entre jogadores quando as naves estão no mesmo planeta representa a interação entre qubits fisicamente próximos — só é possível trocar informação (cartas) quando há conexão física (mesmo planeta).

---

## Refrigerador de Diluição

**No jogo:** ⚠️ Impedimento — reduz para 2 o número de cartas de motor na mão.

**O que representa:**  
Computadores quânticos baseados em supercondução precisam ser mantidos a temperaturas extremamente baixas — da ordem de 2 mK (milikelvin), próximas ao zero absoluto — para preservar a coerência quântica dos qubits. O refrigerador de diluição é o equipamento responsável por atingir essas temperaturas, mas é uma máquina grande, cara e complexa.

**Conexão com o jogo:**  
O impedimento — menos cartas na mão — representa o custo físico e operacional do refrigerador: ele é essencial para o funcionamento do computador quântico, mas sua presença impõe restrições ao sistema, assim como reduz a flexibilidade de navegação das naves.

---

## Portas Quânticas

**No jogo:** Ao trocar uma carta de motor, compra duas cartas de substituição e escolhe uma.

**O que representa:**  
Portas como X, CNOT, SWAP e Hadamard (H) são os blocos fundamentais de circuitos quânticos, equivalentes às portas lógicas da computação clássica. Elas manipulam os estados dos qubits de forma controlada e reversível.

**Conexão com o jogo:**  
Ter mais opções de cartas para escolher representa a flexibilidade das portas quânticas — com um bom conjunto de portas, é possível construir qualquer operação quântica desejada, assim como escolher a melhor carta de motor para a situação.

---

## Programação Quântica

**No jogo:** Naves contornam automaticamente as defesas orbitais em planetas sem componentes.

**O que representa:**  
Linguagens de programação quântica de alto nível, como IBM Qiskit e OpenQASM, permitem que programadores expressem algoritmos quânticos de forma mais eficiente, abstraindo os detalhes do hardware e otimizando automaticamente os circuitos.

**Conexão com o jogo:**  
O bypass automático das defesas em planetas sem componentes representa a otimização automática — uma boa linguagem de programação quântica identifica quando determinadas operações são desnecessárias e as elimina, tornando a execução mais eficiente.

---

## Correção de Erros Quânticos

**No jogo:** Adiciona +1 ao resultado do dado de Entanglion.

**O que representa:**  
Como qubits físicos são suscetíveis a ruídos durante a medição, a correção de erros quânticos visa mitigar esses problemas empregando múltiplos qubits físicos (qubits lógicos) para detectar e corrigir erros sem colapsar o estado quântico.

**Conexão com o jogo:**  
O bônus no dado representa a maior tolerância a erros — com correção de erros, o sistema quântico tem mais "margem de segurança" para operar corretamente mesmo na presença de ruído, assim como um bônus no dado aumenta a chance de evadir as defesas.

---

## Infraestrutura de Controle

**No jogo:** ⚠️ Impedimento — subtrai 1 do resultado do dado de Entanglion.

**O que representa:**  
A operação de computadores quânticos necessita de um sistema para medir e controlar os estados internos dos qubits. Essa infraestrutura utiliza radiação de micro-ondas para realizar leituras, convertendo o estado quântico em um valor binário (0 ou 1). No entanto, os próprios sinais de controle podem introduzir ruído no sistema.

**Conexão com o jogo:**  
O impedimento — penalidade no dado — representa o ruído inevitável introduzido pelos sinais de controle. Quanto mais sofisticada a infraestrutura de controle, maior a interferência potencial, tornando o sistema mais vulnerável à detecção.

---

## Blindagem Magnética

**No jogo:** Permite rolar o dado de Entanglion novamente e ignorar o primeiro resultado.

**O que representa:**  
A blindagem magnética protege os qubits de interferências externas, como campos magnéticos aleatórios e radiação eletromagnética do ambiente, garantindo a estabilidade e a coerência do sistema quântico por mais tempo.

**Conexão com o jogo:**  
A capacidade de ignorar o primeiro resultado do dado representa a proteção contra interferências externas — com blindagem magnética, o sistema quântico tem uma "segunda chance" de operar sem ser perturbado pelo ambiente externo.

---

*Este material foi desenvolvido como parte da pesquisa de TCC sobre o uso do Entanglion no ensino de Computação Quântica. Para o livro de regras completo, consulte [jogo/README.md](../../jogo/README.md).*