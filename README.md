# Análise de Redes Complexas – G96 (sx-askubuntu)

## Descrição

Este projeto foi desenvolvido para a disciplina de Teoria dos Grafos e Redes Complexas, utilizando o dataset **G96 – sx-askubuntu**, obtido do Stanford Network Analysis Project (SNAP).

O objetivo é realizar análises estruturais do grafo, aplicar algoritmos clássicos estudados na disciplina e investigar propriedades características de redes complexas, como:

- Distribuição de graus
- Lei de potência (Power Law)
- Small-World
- Robustez da rede
- Componentes conexas
- Clusterização
- Caminhos mínimos
- Árvores geradoras mínimas

---

## Dataset

**Nome:** sx-askubuntu

**Fonte:** SNAP – Stanford Network Analysis Project

**Link:**
https://snap.stanford.edu/data/sx-askubuntu.html

### Características Originais

| Propriedade | Valor |
|------------|--------|
| Tipo | Direcionado e Temporal |
| Vértices | 159.316 |
| Arestas Temporais | 964.437 |
| Arestas Estáticas | 596.933 |

O dataset representa interações entre usuários da plataforma Ask Ubuntu, incluindo perguntas, respostas e comentários.

---

## Estrutura do Projeto

```text
.
├── data/
│   └── sx-askubuntu.txt
│
├── outputs/
│   ├── output_18_1.png
│   ├── output_21_0.png
│   └── output_36_1.png
│
├── src/
│   └── SNAP-DEF.ipynb
│
└── README.md
