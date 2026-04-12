# Componentes Quânticos

Os componentes quânticos são os oito elementos que os jogadores devem coletar para construir o computador quântico e vencer o jogo. Eles estão espalhados pelos oito planetas da galáxia Entanglion — um por planeta.

Cada componente quântico concede uma **habilidade especial permanente** (ou um impedimento) à nave do jogador que o coletou. Por isso, é essencial que os jogadores planejem juntos a **ordem de coleta**, buscando primeiro os componentes que oferecem vantagens imediatas.

> **Importante:** Os componentes quânticos são melhorias permanentes. Uma vez coletado, o efeito se aplica pelo resto do jogo para a nave que o obteve.

---

## Lista de componentes

### 1. 🔵 Qubits Físicos
**Planeta:** OMEGA ZERO  
**O que representa:** Os processadores quânticos são implementados por meio de qubits de hardware. Existem diversas abordagens, incluindo junções Josephson (supercondutores), armadilhas de íons e pontos quânticos.  
**Efeito no jogo:** Reduz o limiar de detecção em 1 para sua nave. As defesas orbitais e terrestres ficam um pouco menos sensíveis à sua presença.

---

### 2. 🔗 Interconexão de Qubits
**Planeta:** OMEGA ONE  
**O que representa:** Para que o emaranhamento quântico ocorra, os qubits precisam estar fisicamente conectados entre si, permitindo a interação necessária para a execução de operações quânticas.  
**Efeito no jogo:** Permite que sua nave use a carta SWAP entre as galáxias Centarious e Superious — uma transição que normalmente não é permitida.

---

### 3. ❄️ Refrigeração Criogênica
**Planeta:** OMEGA TWO  
**O que representa:** Computadores quânticos baseados em supercondução (junções Josephson) precisam ser mantidos a temperaturas extremamente baixas — da ordem de 2 mK (milikelvin) — para preservar a coerência quântica dos qubits.  
**Efeito no jogo:** Uma vez por verificação de detecção, você pode relançar o dado de Entanglion e escolher qual resultado usar.

---

### 4. ⚛️ Portas Quânticas
**Planeta:** PHI PLUS  
**O que representa:** Portas como X, CNOT, SWAP e Hadamard (H) desempenham papel semelhante às portas lógicas da computação clássica, possibilitando a manipulação do estado dos qubits.  
**Efeito no jogo:** Reduz o limiar de detecção em 1 para sua nave.

---

### 5. 💻 Programação Quântica
**Planeta:** PHI MINUS  
**O que representa:** Para aumentar a eficiência dos programadores quânticos, são usadas linguagens de programação de alto nível — como IBM OpenQASM e IBM Qiskit, que oferece uma interface em Python para programar circuitos quânticos.  
**Efeito no jogo:** No início de cada turno, você compra um cartão de motor extra (totalizando 4 cartões na mão em vez de 3).

---

### 6. 🛡️ Correção de Erros Quânticos
**Planeta:** PSI PLUS  
**O que representa:** Como qubits físicos são suscetíveis a ruídos durante a medição, a correção de erros visa mitigar esses problemas, empregando múltiplos qubits físicos para garantir maior fidelidade nos cálculos.  
**Efeito no jogo:** Reduz o limiar de detecção em 1 para sua nave.

---

### 7. ⚠️ Infraestrutura de Controle *(impedimento)*
**Planeta:** PSI MINUS  
**O que representa:** Como a operação de computadores quânticos necessita de um sistema para medir os estados internos dos qubits, a infraestrutura de controle realiza essa leitura por meio de radiação de micro-ondas, convertendo o estado quântico em um valor binário (0 ou 1).  
**Efeito no jogo:** ⚠️ **IMPEDIMENTO** — Após cada navegação, você deve descartar um cartão de motor da sua mão. Planeje com cuidado a ordem de coleta para minimizar o impacto desse componente!

---

### 8. 🧲 Blindagem Magnética
**Planeta:** OMEGA THREE  
**O que representa:** A blindagem magnética é utilizada para proteger os qubits de interferências externas, como campos magnéticos aleatórios, garantindo a estabilidade e a coerência do sistema quântico.  
**Efeito no jogo:** Cartões PROBE não têm efeito sobre sua nave. Quando PROBE for comprado durante um evento quântico, a sonda de defesa ancestral não consegue detectar sua nave.

---

## Resumo dos componentes e efeitos

| # | Componente | Planeta | Efeito |
|---|---|---|---|
| 1 | Qubits Físicos | OMEGA ZERO | Reduz limiar de detecção em 1 |
| 2 | Interconexão de Qubits | OMEGA ONE | Permite SWAP entre galáxias |
| 3 | Refrigeração Criogênica | OMEGA TWO | Relança o dado de detecção uma vez |
| 4 | Portas Quânticas | PHI PLUS | Reduz limiar de detecção em 1 |
| 5 | Programação Quântica | PHI MINUS | Compra cartão de motor extra por turno |
| 6 | Correção de Erros Quânticos | PSI PLUS | Reduz limiar de detecção em 1 |
| 7 | Infraestrutura de Controle | PSI MINUS | ⚠️ Descarta 1 cartão após cada navegação |
| 8 | Blindagem Magnética | OMEGA THREE | PROBE não afeta sua nave |

---

## Estratégia de coleta

Como os componentes 1, 4 e 6 reduzem o limiar de detecção, é altamente recomendado coletá-los **antes** do componente 7 (Infraestrutura de Controle), que é um impedimento. O componente 8 (Blindagem Magnética) é especialmente valioso se a pilha de cartões de motor já foi embaralhada várias vezes, aumentando a frequência de PROBE.

---

*Para mais informações sobre o que cada componente representa na computação quântica real, consulte a seção "Entanglion e a computação quântica real" no [Livro de Regras](LivroDeRegras.md).*
