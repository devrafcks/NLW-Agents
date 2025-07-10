# NLW Agents - Assistente de Meta para Jogos


<img width="1663" height="854" alt="image" src="https://github.com/user-attachments/assets/b91004f1-85ca-4d8b-bd08-e8db1eb97b79" />

 
[Projeto online](https://devrafcks.github.io/NLW-Agents/)

Projeto desenvolvido durante o evento **NLW Agents** da Rocketseat — trilha iniciante. 

---

##  Sobre o projeto

O **NLW Agents** funciona como um assistente de meta para jogos.  
A aplicação permite:

- Escolher um jogo entre os disponíveis
- Inserir uma pergunta sobre o jogo (estratégia, build, dica etc.)
- Obter uma resposta direta da IA (em Markdown convertido para HTML)
- Usar a própria chave de API da Gemini para evitar limitações

---

## 🕹️ Jogos suportados

| Nome               | Identificador (`value`)   |
|--------------------|---------------------------|
| Valorant           | `valorant`                |
| CS:GO              | `cs`                      |
| Fortnite           | `fortnite`                |
| Elden Ring         | `elden-ring`              |
| Lies of P          | `lies-of-p`               |
| Sekiro             | `sekiro`                  |
| Celeste            | `celeste`                 |
| Minecraft          | `minecraft`               |
| Hollow Knight      | `hollow-knight`           |
| Undertale          | `undertale`               |

---

##  Inteligência Artificial

A IA utiliza o modelo **Gemini 2.0 Flash** com um prompt estruturado para guiar as respostas.  
Ela é instruída a:

- Responder com objetividade (máximo 500 caracteres)
- Ser direta, sem saudações ou rodeios
- Não inventar respostas
- Ignorar perguntas que não tenham relação com o jogo selecionado
- Considerar a data atual para manter relevância com o patch do jogo

---

##  Principais recursos técnicos

- HTML semântico
- CSS organizado e responsivo
- JavaScript com `fetch`, `async/await` e validação de formulário
- Conversão de Markdown para HTML com `showdown.js`
- API Gemini com modelo configurável

---

