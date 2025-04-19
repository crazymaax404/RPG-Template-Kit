# 🏜️ Template de RPG em Blueprints - Unreal Engine 5.3.2

Este é um **template gratuito de RPG** desenvolvido inteiramente em **Blueprints**, utilizando como base o template padrão de Third Person da Unreal Engine **5.3.2**.

> ⚠️ **Importante:**  
> Criado com o intuito de auxiliar desenvolvedores em seus estudos e experimentações com mecânicas de jogos.
> Este projeto é voltado para **fins educacionais** e **não é recomendado** como base direta para jogos comerciais, pois, mesmo contando com várias funcionalidades interessantes, ele ainda é um template básico e **pode conter bugs ou limitações**.

---

![image](https://github.com/user-attachments/assets/58e7342a-7654-4564-b6a3-7463bae66229)


## 🚀 Funcionalidades Principais

### 🎮 Sistema de Locomoção Avançado
- Baseado em **Blendspaces** para uma movimentação fluida.
- Movimentos incluídos:  
  **Idle, Andar, Correr, Agachar, Pular, Escalar, Nadar, Dodge Roll (rolamento de esquiva), Bloquear ataques, Jogar Pedra para distração**.
- Sistema de **Salto** com:
  - **Motion Warping**
  - Cálculos matemáticos para detectar estruturas "puláveis"

---

### 🗡️ Combate e Stealth
- **Sistema de Assassinato**:
  - Instakill pelas costas do inimigo
  - Widget propondo o ataque
- **Sistema de Combos** com:
  - 4 ataques diferentes
  - Timers individuais para sequência de combo
  - Detecção com **Traces**
  - Animações sincronizadas, **efeitos de sangue** e reação ao dano
- Sistema de **Target Lock**
- **Bloqueio e Dodge** integrados à stamina
- Inimigos também realizam **combos**

---

### 🧬 Status e Progressão
- Atributos do jogador:
  - **Vida / Vida Máxima**
  - **Stamina / Stamina Máxima**
  - **EXP / EXP Máxima**
  - **Level**
- Sistema de **Level Up** com efeitos Niagara
- Interface completa de status do jogador

---

### 🛡️ Sistema de Equipamentos
- Equipamentos disponíveis:
  - **Espadas, Escudos, Arcos, Armaduras**
- Sistema utilizando:
  - **Data Tables**
  - **Enumerations (Enums)**
  - **Structures (Structs)**
- Interface para **equipar e desequipar** itens

---

### 🧠 Inteligência Artificial
- **Inimigos** com:
  - **Behavior Tree**
  - Patrulham, caçam e investigam
  - Sistema de **audição e visão**
- **Bosses** com:
  - HUD personalizada
  - Aumentam a dificuldade
- **Civis** que:
  - Não atacam
  - Não causam perigo

---

### 🗺️ Mundo Aberto
- Ambiente com tema de **Deserto com Oasis e Cidades**
- Fauna com IA:
  - **Elefantes**
  - **Hipopótamos**
  - **Rinocerontes** (podem ser montados)

---

### 🧾 Sistema de Quests
- NPCs com:
  - **Objetivos e Recompensas**
  - **Diálogo e Missões**
- Interface de **missão ativa**

---

### 🎁 Interações e Extras
- **Baús interativos** com recompensas (itens e/ou EXP)
- **Sistema de Save/Load**:
  - Armazena todos os dados do jogador
- **Ciclo de Dia e Noite**
- Animações de **morte e respawn**
- **Sistema de pausa e menu**
- **Mensagens de localização** ao entrar em áreas específicas
- Suporte completo para:
  - **Teclado e Mouse**
  - **Controles**

---

## 🧩 Estrutura do Projeto

Este projeto foi desenvolvido **inteiramente em Blueprints**, com foco educacional.  
A estrutura está organizada para facilitar o estudo e a compreensão de cada sistema.

---

## 📝 Considerações Finais

Este template foi criado como ferramenta de **estudo e aprendizado** para desenvolvedores iniciantes e intermediários na Unreal Engine.  
A ideia é que você possa explorar os sistemas, entender como foram feitos e **recriar algo ainda melhor no seu próprio jogo**.

> 🎓 **Aprenda com o template, mas crie algo seu.**

![image](https://github.com/user-attachments/assets/935db8a2-3432-48d5-b67e-9adeebba1e8b)

