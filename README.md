# 📌 AikoAC (AntiCheat) - Guia Completo

## 🚀 Introdução

O **AikoAC** é um sistema avançado de anticheat desenvolvido para **FiveM**, garantindo a segurança e integridade do servidor. Ele fornece ferramentas poderosas para **monitoramento**, **detecção** e **mitigação** de trapaças, além de funcionalidades administrativas para um gerenciamento eficiente.

O comando `/aiko` é a interface principal do AikoAC, permitindo que administradores e moderadores executem ações diretamente no jogo.

---

## 🎮 Uso do Comando

O comando segue a seguinte sintaxe:

```bash
/aiko [subcomando] [parâmetros]
```

Cada subcomando possui uma função específica e pode exigir parâmetros adicionais.

---

## 🔹 Subcomandos Disponíveis

### 🎯 1. **info**
Exibe informações detalhadas sobre o jogador que executou o comando.

```bash
/aiko info
```

### 📋 2. **menu**
Abre o menu do sistema AikoAC para o jogador (necessita permissão adequada).

```bash
/aiko menu
```

### 🛡️ 3. **wall**
Ativa ou desativa a função de "wallhack" no AikoAC para o jogador (necessita permissão adequada).

```bash
/aiko wall
```

### 👑 4. **setowner [playerId]**
Define um jogador como dono do servidor (requer permissão).

```bash
/aiko setowner 123
```

### ⚙️ 5. **setperm [permissão] [playerId]**
Modifica a permissão de um jogador. Permissões disponíveis: `owner`, `administrator`, `moderator`, `support`, `user`.

```bash
/aiko setperm administrator 123
```

### 🔨 6. **ban [playerId]**
Bane um jogador do servidor (requer permissão).

```bash
/aiko ban 123
```

### 🎫 7. **unban [playerId]**
Desbane um jogador do servidor (requer permissão).

```bash
/aiko unban 123
```

### ✨ 8. **tp [playerId]**
Teletransporta o jogador que executou o comando até outro jogador.

```bash
/aiko tp 123
```

### 🔄 9. **pull [playerId]**
Puxa um jogador até a posição do jogador que executou o comando.

```bash
/aiko pull 123
```

### 🏙️ 10. **deleteAllPeds**
Remove todos os NPCs do servidor (requer permissão).

```bash
/aiko deleteAllPeds
```

### 🚗 11. **deleteAllVehicles**
Remove todos os veículos do servidor (requer permissão).

```bash
/aiko deleteAllVehicles
```

### 📦 12. **deleteAllObjects**
Remove todos os objetos do servidor (requer permissão).

```bash
/aiko deleteAllObjects
```

### 🔄 13. **update**
Atualiza a configuração do servidor (requer permissão de `owner`).

```bash
/aiko update
```

### ⚖️ 14. **applyPunishment [playerId]**
Aplica uma punição a um jogador conforme as regras do AikoAC.

```bash
/aiko applyPunishment 123
```

### 🛑 15. **playerSpawned**
Verifica se um jogador está banido ao entrar no servidor e toma as devidas ações de segurança.

### 🔍 16. **setWallInfos**
Registra informações do jogador para o sistema de "wallhack" e detecção de anomalias.

### ❌ 17. **uninstall**
Desinstala dependências do AikoAC (somente no console do servidor).

```bash
/aiko uninstall
```

---

## 🔑 Permissões

Cada subcomando possui um nível de permissão necessário:

- **👑 owner** - Dono do servidor
- **🔧 administrator** - Administrador
- **🛡️ moderator** - Moderador
- **📞 support** - Suporte
- **🎮 user** - Usuário comum

---

## 📌 Observações

✔️ O AikoAC **detecta atividades suspeitas em tempo real** e pode tomar ações automáticas para impedir trapaças.
✔️ Alguns comandos **não podem ser executados pelo console do servidor**.
✔️ Caso um jogador **não tenha permissão** para executar um comando, ele receberá uma mensagem de erro.
✔️ O comando `/aiko` sem parâmetros exibirá os comandos disponíveis.

---

## 🎯 Conclusão

O **AikoAC** é uma solução **completa e eficiente** para garantir um ambiente de jogo **seguro e livre de trapaças**. Com suas diversas funcionalidades, ele oferece **controle total** sobre o servidor, protegendo a integridade do jogo e facilitando a administração.

🔹 **Proteção avançada** contra cheaters.
🔹 **Ferramentas administrativas** para um gerenciamento eficiente.
🔹 **Sistema de permissão robusto** para maior segurança.

➡️ **Mantenha seu servidor seguro com AikoAC!** 🚀

