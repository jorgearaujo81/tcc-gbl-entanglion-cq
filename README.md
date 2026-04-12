# Aprendizagem Baseada em Jogos e Computação Quântica

> Repositório de materiais acadêmicos e didáticos sobre o uso do jogo de tabuleiro **Entanglion** como estratégia para o ensino dos fundamentos da Computação Quântica.

---

## Sobre este repositório

Este repositório reúne os materiais produzidos no contexto do Trabalho de Conclusão de Curso (TCC) defendido na **CESAR School** (Recife/PE) em 2025, que investigou o potencial do jogo de tabuleiro Entanglion como recurso didático para introduzir conceitos fundamentais da Computação Quântica a estudantes do Ensino Médio e da graduação.

Como contribuição adicional, este repositório inclui a **primeira tradução completa do Entanglion para o português (pt-BR)**, tornando o jogo acessível a professores e alunos de escolas públicas brasileiras que não dominam o inglês.

---

## Estrutura do repositório

```
tcc-gbl-entanglion-cq/
├── pesquisa/                          Materiais da pesquisa acadêmica
│   ├── tcc/                           Trabalho de Conclusão de Curso
│   ├── artigo-base/                   Artigo original do Entanglion (IBM, 2018)
│   ├── dados/                         Dados coletados, notebook e formulário
│   └── referencias/                   Referências complementares
├── materiais-didaticos/               Materiais para uso em sala de aula
│   ├── planos/                        Plano de ensino
│   └── slides/                        Slides (Ensino Médio e Graduação)
└── entanglion/                        Tudo relacionado ao jogo Entanglion
    └── entanglion-ptbr/               Tradução completa para o português (pt-BR)
        ├── jogo/                      Livro de regras, história e referência das cartas
        ├── recursos/                  Arquivos para montar e jogar o Entanglion
        │   ├── livro-de-regras/       Manual de regras em PDF para impressão
        │   ├── tabuleiro/             Tabuleiro traduzido (em produção)
        │   └── modelos-3d/            Modelos STL para impressão 3D das peças
        ├── expansoes/                 Guia para criar expansões do jogo
        └── images/                    Imagens utilizadas na documentação
```

---

## Pesquisa

### TCC
**ARAÚJO, Jorge Alexandre de.** Aprendizagem baseada em jogos como estratégia didática para a introdução dos princípios da computação quântica usando o jogo de tabuleiro Entanglion. 2025. 84 p. TCC (Graduação em Ciência da Computação) — CESAR School, Recife, 2025. Orientadora: Profa. Pamela Thays Lins Bezerra.

📄 [TCC_Jorge-Alexandre-de-Araujo-2025.pdf](pesquisa/tcc/TCC_Jorge-Alexandre-de-Araujo-2025.pdf)

### Artigo base
**WEISZ, Justin D.; ASHOORI, Maryam; ASHKTORAB, Zahra.** Entanglion: A Board Game for Teaching the Principles of Quantum Computing. In: Proceedings of the 2018 Annual Symposium on Computer-Human Interaction in Play (CHI PLAY '18). ACM, New York, NY, USA, p. 523–534, 2018. DOI: [10.1145/3242671.3242696](https://doi.org/10.1145/3242671.3242696)

📄 [Weisz_Ashoori_Ashktorab_2018_Entanglion_Board_Game_Teaching_Quantum_Computing.pdf](pesquisa/artigo-base/Weisz_Ashoori_Ashktorab_2018_Entanglion_Board_Game_Teaching_Quantum_Computing.pdf)

---

## Materiais didáticos

Os materiais foram desenvolvidos e aplicados em seis intervenções presenciais entre abril e maio de 2025, em três instituições: CESAR School, ETE Porto Digital e Residência Tecnológica Embarque Digital (Porto Digital).

| Material | Público-alvo | Arquivo |
|---|---|---|
| Plano de ensino | Professores | [Plano_de_Ensino_Entanglion.pdf](materiais-didaticos/planos/Plano_de_Ensino_Entanglion.pdf) |
| Slides | Ensino Médio | [Slides-Principios-CQ-Entanglion-EM-2025.pdf](materiais-didaticos/slides/Slides-Principios-CQ-Entanglion-EM-2025.pdf) |
| Slides | Graduação | [Slides-Principios-CQ-Entanglion-Graduacao-2025.pdf](materiais-didaticos/slides/Slides-Principios-CQ-Entanglion-Graduacao-2025.pdf) |

---

## Entanglion em Português (pt-BR)

O [Entanglion](https://github.com/Entanglion/entanglion) é um jogo de tabuleiro cooperativo desenvolvido pela IBM Research para ensinar os princípios da Computação Quântica. Este repositório inclui a tradução completa para o português brasileiro.

### Para jogar
| Material | Arquivo |
|---|---|
| Livro de regras (PDF para impressão) | [Livro-de-Regras.pdf](entanglion/entanglion-ptbr/recursos/livro-de-regras/Livro-de-Regras.pdf) |
| Tabuleiro traduzido | *em produção* |
| Modelos 3D das peças | [modelos-3d/](entanglion/entanglion-ptbr/recursos/modelos-3d/) |

### Para educadores
| Material | Arquivo |
|---|---|
| Livro de regras (texto) | [jogo/](entanglion/entanglion-ptbr/jogo/) |
| História do jogo | [jogo/Historia.md](entanglion/entanglion-ptbr/jogo/Historia.md) |
| Cartas de evento | [jogo/CartasDeEvento.md](entanglion/entanglion-ptbr/jogo/CartasDeEvento.md) |
| Componentes quânticos | [jogo/ComponentesQuanticos.md](entanglion/entanglion-ptbr/jogo/ComponentesQuanticos.md) |
| Guia de expansões | [expansoes/](entanglion/entanglion-ptbr/expansoes/) |

### Sobre a tradução
A tradução mantém todos os termos técnicos em inglês (`qubit`, `CNOT`, `SWAP`, `Hadamard`, nomes dos planetas e galáxias) por serem notação científica padronizada internacionalmente. Apenas os textos de regras, narrativa e descrições foram traduzidos.

**Tradução:** [Gabriel B. de Santana](https://github.com/mpc53199) e [Jorge Alexandre de Araújo](https://github.com/jorgearaujo81)  
**Repositório original:** [github.com/Entanglion/entanglion](https://github.com/Entanglion/entanglion)

---

## Resultados da pesquisa

A pesquisa conduziu seis intervenções presenciais (N = 34 respondentes válidos) com estudantes do Ensino Médio e da graduação. Os principais resultados foram:

- Efeitos estatisticamente significativos (p < 0,05) em quatro das seis turmas
- Tamanhos de efeito fortes (r ≥ 0,99)
- Avaliações Likert com alta clareza (≥ 4,0) e interação (≥ 4,4)
- A sequência **jogo → teoria** mostrou os melhores resultados de aprendizagem

---

## Autor

**Jorge Alexandre de Araújo**  
Bacharel em Ciência da Computação — CESAR School (2025)  
📋 [Currículo Lattes](http://lattes.cnpq.br/0699057913401217) | 💼 [LinkedIn](https://www.linkedin.com/in/jorge-araujo81/)

**Orientadora:** Profa. Dra. Pamela Thays Lins Bezerra — CESAR School  
📋 [Currículo Lattes](http://lattes.cnpq.br/6624770463248795) | 💼 [LinkedIn](https://www.linkedin.com/in/pamelathays/)

---

## Licença

Os materiais de autoria própria (TCC, plano de ensino, slides) estão disponíveis para fins educacionais e de pesquisa, desde que citada a fonte.

A tradução do Entanglion segue a licença original do jogo:  
[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  
[Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional](http://creativecommons.org/licenses/by-nc-sa/4.0/)
