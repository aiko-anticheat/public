# 📌 AikoAc (AntiCheat) - Guia Completo 

## 🚀 Introdução

O **AikoAc** é um sistema anticheat avançado desenvolvido para o **FiveM**, garantindo a segurança e integridade do servidor. Ele oferece ferramentas poderosas para **monitoramento**, **detecção** e **mitigação** de trapaças, além de funcionalidades administrativas para uma gestão eficiente do servidor.

O comando `/aiko` é a principal interface do AikoAc, permitindo que administradores e moderadores executem ações diretamente dentro do jogo.

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
Abre o menu do sistema AikoAc para o jogador (requer permissão adequada).

```bash
/aiko menu
```

### 🛡️ 3. **wall**
Ativa ou desativa a funcionalidade de "wallhack" no AikoAc para o jogador (requer permissão adequada).

```bash
/aiko wall
```

### 👑 4. **setowner [id]**
Define um jogador como dono do servidor (requer permissão).

```bash
/aiko setowner 123
```

### ⚙️ 5. **setperm [permissão] [id]**
Modifica a permissão de um jogador. Permissões disponíveis: `owner`, `admin`, `mod`, `sup`, `user`.

```bash
/aiko setperm admin 123
```

### 🔨 6. **ban [id]**
Bane um jogador do servidor (requer permissão).

```bash
/aiko ban 123
```

### 🎫 7. **unban [id]**
Remove o banimento de um jogador no servidor (requer permissão).

```bash
/aiko unban 123
```

### 👀 8. **spec [id]**
Começa a espectar (assistir) um jogador informado.

```bash
/aiko spec 123
```

### ✨ 9. **tp [id]**
Teletransporta o jogador que executou o comando até outro jogador.

```bash
/aiko tp 123
```

### 🔄 10. **pull [id]**
Puxa um jogador para a posição do jogador que executou o comando.

```bash
/aiko pull 123
```

### 📸 11. **print [id]**
Tira uma captura de tela da tela do jogador informado.

```bash
/aiko print 123
```

### 🏙️ 12. **deleteAllPeds**
Remove todos os NPCs do servidor (requer permissão).

```bash
/aiko deleteAllPeds
```

### 🚗 13. **deleteAllVehicles**
Remove todos os veículos do servidor (requer permissão).

```bash
/aiko deleteAllVehicles
```

### 📦 14. **deleteAllObjects**
Remove todos os objetos do servidor (requer permissão).

```bash
/aiko deleteAllObjects
```

### 🏙️ 15. **deletePedsInArea**
Remove todos os NPCs de uma área especificada (requer permissão).

```bash
/aiko deletePedsInArea
```

### 🚗 16. **deleteVehiclesInArea**
Remove todos os veículos de uma área especificada (requer permissão).

```bash
/aiko deleteVehiclesInArea
```

### 📦 17. **deleteObjectsInArea**
Remove todos os objetos de uma área especificada (requer permissão).

```bash
/aiko deleteObjectsInArea
```

---

## 🔑 Permissões

Cada subcomando exige um nível específico de permissão:

- **👑 owner** - Dono do servidor
- **🔧 admin** - Administrador
- **🛡️ mod** - Moderador
- **📞 sup** - Suporte
- **🎮 user** - Jogador comum

---

## 📌 Observações

✔️ O AikoAc **detecta atividades suspeitas em tempo real** e pode tomar ações automáticas para impedir trapaças.  
✔️ Alguns comandos **não podem ser executados pelo console do servidor**.  
✔️ Caso o jogador **não tenha permissão** para executar um comando, ele receberá uma mensagem de erro.  
✔️ O comando `/aiko` sem parâmetros exibirá os comandos disponíveis.

---

## 🎯 Conclusão

O **AikoAc** é uma solução **completa e eficiente** para garantir um ambiente de jogo **seguro e livre de trapaças**. Com seus diversos recursos, ele oferece **controle total** sobre o servidor, protegendo a integridade do jogo e facilitando a administração.

🔹 **Proteção avançada** contra trapaceiros.  
🔹 **Ferramentas administrativas** para uma gestão eficiente.  
🔹 **Sistema robusto de permissões** para segurança aprimorada.

➡️ **Mantenha seu servidor seguro com o AikoAc!** 🚀
