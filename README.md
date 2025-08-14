"""# ♟️ Simulação de Movimentos de Peças de Xadrez em C

Este projeto é um exercício de programação em C que simula os movimentos de quatro peças de xadrez — **Torre**, **Bispo**, **Rainha** e **Cavalo** — utilizando **recursividade**, **loops simples**, **loops aninhados** e **controle de fluxo**.

O objetivo é praticar conceitos fundamentais e avançados da linguagem C, como:
- Estruturas de repetição (`for`, `while`, `do-while`)
- Recursividade
- Loops aninhados
- Uso de `break` e `continue`
- Organização e clareza de código

---

## 📋 Funcionalidades

- **Torre**  
  Move-se em linha reta na horizontal.  
  Implementada com **recursividade** para simular 5 casas para a direita.

- **Bispo**  
  Move-se na diagonal (Cima Direita).  
  Implementado com **recursividade** e **loops aninhados** (loop externo para vertical, loop interno para horizontal) para simular 5 casas na diagonal.

- **Rainha**  
  Move-se em linha reta na horizontal.  
  Implementada com **recursividade** para simular 8 casas para a esquerda.

- **Cavalo**  
  Move-se em "L" (duas casas para cima e uma para a direita).  
  Implementado com **loops aninhados complexos**, múltiplas variáveis e uso de `break` e `continue`.

---

## 📂 Estrutura do Código

```plaintext
main.c
└── moverTorre()      // Função recursiva para Torre
└── moverBispo()      // Função recursiva + loops aninhados para Bispo
└── moverRainha()     // Função recursiva para Rainha
└── moverCavalo()     // Loops aninhados complexos para Cavalo
🚀 Como Executar
Clonar este repositório (ou copiar o arquivo main.c):

bash
Sempre exibir os detalhes

Copiar
git clone https://github.com/usuario/simulacao-xadrez-c.git
cd simulacao-xadrez-c
Compilar o programa:

bash
Sempre exibir os detalhes

Copiar
gcc main.c -o xadrez
Executar:

bash
Sempre exibir os detalhes

Copiar
./xadrez
💻 Saída Esperada
plaintext
Sempre exibir os detalhes

Copiar
Movimento da Torre:
Direita
Direita
Direita
Direita
Direita

Movimento do Bispo:
Cima Direita
Cima Direita
Cima Direita
Cima Direita
Cima Direita

Movimento da Rainha:
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda
Esquerda

Movimento do Cavalo:
Cima
Cima
Direita
🛠️ Tecnologias Utilizadas
Linguagem: C

Compilador: GCC ou compatível

Paradigmas utilizados: Programação estruturada e recursiva

📖 Conceitos Praticados
Recursividade: Utilizada para Torre, Bispo e Rainha, substituindo loops tradicionais.

Loops aninhados: Utilizados no Bispo (vertical + horizontal) e Cavalo.

Controle de fluxo (break, continue): Aplicados no movimento do Cavalo.

Organização de código: Funções separadas por peça para melhor legibilidade.

📜 Licença
Este projeto é apenas para fins educacionais e está sob a licença MIT.
"""
