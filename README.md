# Projeto - IP
Projeto de Introdução à Programação do semestre [2025.1], nosso objetivo era criar um sistema interativo em um ambiente 2D no qual o usuário controla um personagem que deveria procurar e coletar, dentro de um labirinto, três objetos (chaves) para desbloquear uma saída e, após encontrá-la, conseguir sair do labirinto e vencer o jogo. Além disso, pensamos em adicionar um temporizador no qual o jogador deveria sair do labirinto antes que o tempo chegasse a 0, tornando o jogo mais desafiador. Visando cumprir a exigência mínima dos três tipos distintos de objetos coletáveis, pensamos em adicionar: as chaves necessárias para desbloquear a saída, um coletável que aumentasse a velocidade no jogador e um coletável que aumenta o tempo no temporizador para que o jogador tivesse mais tempo para vencer o labirinto, mantendo registro da quantidade coletada e exibindo ao usuário.
---

## **Título do Projeto:**
[CIn Saída] 

## **Link do repositório no GitHub:**
[https://github.com/LuKS0302/CIn-Saida]

---

## **Organização técnica do código:**
O código foi dividido em módulos, cada um com responsabilidades específicas:

- **Main**: [Arquivo principal, onde será executado a tela do jogo]
- **[Código]**: [Seguindo as instruções do documento do pygame, delegar uma pasta exclusivamente para o software e suas classes.]
- **[Música]**: [Pasta com Jingles e Sons que poderiam vir a ser usados]
- **[Imagens]**: [Galeria de sprites e mapa, organizada e setorizada para melhor manutenção]


---

## **Ferramentas utilizadas no projeto:**

O jogo foi desenvolvido em **[Python]** utilizando as bibliotecas:
- [Pygame]
- [Random]
 
### Instalação das bibliotecas
**[Pygame]**
```bash
[pip install pygame]
```

O mapa foi feito no Inkarnate, escolhemos um mapa disponibilizado na comunidade e alteramos o mesmo conforme as nossas necessidades.

## **Sobre o projeto:**
Inspirado no formato de exploração do jogo Shattered Pixel Dungeon, nosso projeto coloca o jogador em um labirinto desafiador com o objetivo de escapar. A narrativa é minimalista de forma intencional, focando na experiência do personagem que se encontra aprisionado. Para alcançar esse objetivo, a mecânica central exige que o jogador explore o mapa em busca de três chaves. Apenas com a posse desses três itens é possível desbloquear a porta de saída. Dessa forma, a jogabilidade se resume a um ciclo de exploração e coleta de itens-chave, com o objetivo de desbloquear e encontrar a porta que levará o jogador à saída.

---

## **Conceitos vistos na disciplina e usados no código:**
- **Listas**: [Armazenar posições válidas para a geração do personagem e dos coletáveis]
- **Condicionais**: [Selecionar dificuldade, verificação da posição, verificação de colisão etc]
- **Laços**: [Loop principal do jogo, geração dos coletáveis, etc]
- **Funções**: [Permitiu maior estruturação do código]
- **Programação Orientada a Objetos**: [Como foi usado]

---

## **Como jogar:**
- **Movimento**: [WASD ou setas]
- **Menu**: [ESC]




## **Contribuidores e funções no projeto:**
- **[João Augusto]** [GitHub](https://github.com/joaoa09)
  - Design do Mapa
  - Colisões

- **[Vinicius Façanha]** [GitHub](https://github.com/fustvini)
  - Coletáveis
  - Contador

- **[Vinicius Amorim]** [GitHub](https://github.com/voa3hub)
  - Design do Mapa

- **[Lucas de Moura]** [GitHub](https://github.com/LuKS0302)
  - Câmera do personagem
  - Menu e dificuldades

- **[Guilherme Véras]** [GitHub](https://github.com/DrVerax)
  - Sons
  - Colisões
  - Menu

- **[Luis Henrique]** [GitHub](https://github.com/luishbm1550)
  - Coletáveis
  - Contador

## **Desafios e erros:**
- **Maior erro do projeto**: [Pensar inicialmente em uma criação de mapas gerados aleatoriamente, o que seria inviável devido ao curto tempo de realização do projeto, então foi feito usando apenas um mapa.]
- **Maior desafio técnico**: [Aprender as mecânicas e comandos do pygame que foram usados nesse projeto em tão pouco tempo mostrou-se um grande desafio.]
- **Lições aprendidas**: [Nosso grupo conseguiu entender que o ideal de um projeto é começar com um roteiro básico e adicionar funcionalidades à medida que o projeto avançar.]

