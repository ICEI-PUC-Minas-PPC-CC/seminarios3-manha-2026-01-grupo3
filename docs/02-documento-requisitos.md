# 02 — Documento de Requisitos do Software

> **Grupo:** Gabriel Fernandes de Sá Andrade / Gabriel de Oliveira Maziero / Gabriel Oliveira de Souza / Hans Carlos Cunha

> **Aplicação:** Aplicação interativa para prática de cálculos matemáticos básicos com foco em acessibilidade visual

> **Comunidade:** Instituição Tarso de Coimbra (pessoas com deficiência auditiva/surdez)

---

## 1. Visão Geral

 A aplicação consiste em um protótipo simples de sistema de cálculos matemáticos básicos, como adição (ex: 1+1, 5+5), com o objetivo de auxiliar no 
aprendizado e prática de operações simples.
 O sistema é destinado à instituição Tarso de Coimbra, atendendo usuários que podem possuir deficiência auditiva/surdez. Por isso, a aplicação foi 
projetada com foco em uma interface altamente visual, intuitiva e de baixa complexidade.
 O principal problema que a aplicação busca resolver é a dificuldade que pessoas com deficiência auditiva podem ter ao utilizar sistemas que dependem 
excessivamente de textos longos e explicações verbais. Isso pode dificultar o entendimento e o aprendizado de conteúdos básicos, como operações 
matemáticas simples.
 Dessa forma, a aplicação propõe uma solução baseada em recursos visuais, utilizando cores, ícones e elementos gráficos para facilitar a compreensão,
tornando o aprendizado mais acessível, inclusivo e eficiente.

## 2. Público-Alvo

| Campo | Informação |
| ------- | ----------- |
| Perfil dos usuários | Estudantes |
| Faixa etária | 10 anos + |
| Necessidades de acessibilidade | Internet e um computador ou celular e provavel interprete para surdos|
| Nível de familiaridade com tecnologia | Baixa |

> **Lembrete (Tarso de Coimbra):** Os usuários podem ter deficiência auditiva/surdez. A interface deve ser **visual, intuitiva e de baixa complexidade**. Priorize elementos visuais (imagens, ícones, cores) sobre texto extenso.

## 3. Requisitos Funcionais

| ID | Requisito | Prioridade | Origem da demanda |
| ---- | ---------- | :----------: | ------------------ |
| RF01 | Calculos matemáticos básicos| Alta| Objetivo da aplicação|
| RF02 |Permitir interação do usuário por meio de botões, ícones e elementos visuais intuitivos| Alta | Necessidades de acessibilidade|
| RF03 | Exibir resultados dos cálculos de forma clara e visual (números grandes, cores ou feedback visual)| Alta | Necessidades de acessibilidade|

## 4. Requisitos Não Funcionais

| ID | Requisito | Categoria |
| ---- | ---------- | ----------- |
| RNF01 | A aplicação deve ser acessível via navegador web | Acessibilidade |
| RNF02 | A interface deve ser simples e intuitiva | Usabilidade |
| RNF03 | A aplicação deve funcionar em dispositivos móveis | Compatibilidade |
| RNF04 | A aplicação deve utilizar elementos visuais (cores, ícones) em vez de textos longos| Usabilidade |
| RNF05 | O sistema deve responder rapidamente às interações do usuário | Desempenho |

## 5. Requisitos de Acessibilidade

- [x] Interface predominantemente visual (ícones, cores, imagens)
- [x] Textos curtos e objetivos
- [x] Botões grandes e identificáveis
- [x] Contraste adequado de cores
- [ ] Compatível com Libras (se aplicável: vídeos, sinais, glossário)
- [x] Sem dependência de áudio para funcionalidades essenciais
- [x] Uso de cores para indicar acerto (verde) e erro (vermelho)
- [x] Layout simples e de fácil compreensão

## 6. Tecnologias Escolhidas

| Componente | Tecnologia |
| ----------- | ----------- |
| Front-end | HTML, CSS, Java Script |
| Back-end (se houver | |
| Banco de dados (se houver) | |
| Hospedagem | Github Pages |
| Outras ferramentas | |

## 7. Protótipo / Wireframes

(Inclua esboços das telas principais ou links para protótipos — mesmo rascunhos simples em papel são válidos. Salvem imagens dos wireframes em `evidencias/prints/`.)

## 8. Escopo Mínimo Viável (MVP)

As funções mínimas do software, para que ja possa ser entregue para a comunidade sâo: As perguntas de artimética, botões de escolha, marco de acertou ou erro (EM CASO DE ERRO, MOSTRAR A ALTERNATIVA CORRETA)

As funcionalidades mínimas para a primeira versão do sistema incluem:

- [x] Exibição de operações matemáticas simples (ex: 1+1, 2+2)
- [x] Seleção de resposta por meio de botões visuais (múltipla escolha)
- [x] Feedback visual imediato (cor verde para acerto e vermelho para erro)
- [x] Interface simples e intuitiva com foco em elementos visuais
- [x] Navegação básica entre exercícios
- [x] Sequência de exercícios progressivos (nível fácil)
- [x] Destaque visual da resposta correta

## 9. Funcionalidades Desejáveis (se houver tempo)

O software tem como funcionalidades desejáveis: questões sobre a materia de matemática, no qual ao acertar deve se contabilizar com uma caixinha verde na alternativa. Ao final de cada questao, deve-se explicar porque aquela alternativa esta correta. Deve apresentar também um contador, para que o jogador saiba quantas ele acertou
