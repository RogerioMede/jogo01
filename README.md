# Projeto de Minijogos - Programação 1 (CESUPA)

Este projeto foi desenvolvido como trabalho final para a disciplina de *Programação 1*, no primeiro semestre de Engenharia da Computação. O objetivo foi criar um sistema em C que gerencia três minijogos diferentes através de um menu interativo.

## 🎓 Informações do Projeto
- *Faculdade:* CESUPA ARGO 
- *Disciplina:* Programação 1
- *Professor:* Girotto
- *Equipe:* Rogério Medeiros e Haissam

---

## 🕹️ Os Jogos

### 1. Perguntas e Respostas
Um quiz de múltipla escolha com 5 perguntas que misturam conhecimentos gerais e conceitos básicos de programação. 
- O jogador escolhe as alternativas (a, b, c, d).
- Se errar, o programa avisa qual era a correta.
- Dá para voltar ao menu a qualquer momento digitando '0'.

### 2. Cobra na Caixa
Um jogo de sorte para dois jogadores, inspirado em exploração de tumbas. 
- No começo, cada jogador escolhe um personagem da lista.
- O código sorteia, em segredo, uma caixa com o "botão de saída" (vitória) e outra com uma "cobra" (derrota).
- Os jogadores se alternam abrindo as caixas de 1 a 5. 
- *Lógica:* O jogo impede que você abra uma caixa que já foi revelada.

### 3. Gousmas War (Guerra de Gousmas)
Este é o jogo mais complexo do projeto, focado em estratégia por turnos.
- Cada jogador controla duas criaturas (Gousmas) com fúria inicial 1.
- *Atacar:* Você soma a fúria da sua gousma na gousma do adversário. Se a fúria dele passar de 5, a gousma dele "explode" e sai do jogo.
- *Dividir:* Você pode tirar fúria de uma gousma sua e passar para a outra. Isso serve para diminuir a fúria de uma que está quase explodindo ou até para *reviver* uma gousma que já tinha sido destruída.
- O jogo termina quando um dos jogadores perde as duas criaturas.

---
