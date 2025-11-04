# 🍊💛 Introdução ao Git  
### por Caju Code  

> “Guardar, versionar e compartilhar código é cultivar aprendizado.”  
🌱

---

<img width="471" height="576" alt="Screenshot 2025-11-04 at 15 57 56" src="https://github.com/user-attachments/assets/de119f33-da69-42ed-94f5-6d7b55168987" />

### :bookmark: Por que versionar?

- 🧠 **Histórico e rastreabilidade:** cada mudança é registrada — quem fez, quando e por quê.  
  > Facilita entender e aprender com o passado.

- 🕰️ **Voltar no tempo:** errou algo? Sem pânico 😅  
  > Git permite reverter para versões anteriores com segurança.

- 🤝 **Colaboração segura:** várias pessoas podem trabalhar juntas sem sobrescrever código.  
  > Branches e merges tornam o trabalho em equipe possível!

- 🧩 **Organização e clareza:** commits bem descritos contam a história do projeto.  
  > Você entende o que mudou sem abrir os arquivos.

- 🌱 **Aprendizado contínuo:** cada commit mostra sua evolução como dev.  
  > Na **Caju Code**, versionar é cultivar seu aprendizado 🍊

---

# 🧠 O que é o Git?

**Git** é um **sistema de controle de versão distribuído**, criado por **Linus Torvalds** em 2005.  

Ele permite:
- Rastrear mudanças no código  
- Trabalhar em equipe sem sobrescrever o trabalho dos outros  
- Voltar a versões anteriores quando algo dá errado  

---

# 🧰 Por que usar o Git?

💡 **Benefícios principais:**
- Histórico completo do seu projeto  
- Colaboração eficiente  
- Segurança contra perdas  
- Integração com GitHub, GitLab e Bitbucket  

---

# 🏗 Estrutura básica

Um projeto versionado com Git é chamado de **repositório**.

```
📂 meu-projeto/
 ┣ 📁 .git/        ← Pasta oculta com o histórico
 ┣ 📄 index.html
 ┣ 📄 script.js
 ┗ 📄 style.css
```

---

# 🪄 Fluxo básico de trabalho

O ciclo de vida de um arquivo no Git:

```
Untracked → Staged → Committed
```

Ou seja:

1. Criar/modificar um arquivo  
2. Adicionar para a área de *staging*  
3. Registrar (commit) a mudança no histórico  

---

# ⚙️ Comandos essenciais

| Ação | Comando |
|------|----------|
| Criar repositório | `git init` |
| Clonar repositório | `git clone URL` |
| Ver status | `git status` |
| Adicionar arquivos | `git add nome_arquivo` |
| Commitar | `git commit -m "mensagem"` |
| Ver histórico | `git log` |
| Criar branch | `git branch nome` |
| Mudar de branch | `git checkout nome` |
| Unir branches | `git merge nome` |

---

# 🌿 Branches

**Branches** são ramificações independentes do seu código.

Permitem:
- Testar novas ideias sem afetar o código principal  
- Trabalhar em features separadamente  

Exemplo:
```
main
 ┣ feature/login
 ┣ feature/perfil
 ┗ fix/ajuste-layout
```

---

# 🧩 Commit

Cada **commit** é um “snapshot” do seu código — uma fotografia do estado atual.  

💛 **Boas práticas de commit:**
- Use mensagens curtas e descritivas  
- Escreva no imperativo: `add`, `fix`, `update`  
- Evite “commit bagunça” com tudo de uma vez  

Exemplo:
```
git commit -m "add: componente de login"
```

---

# 🤝 GitHub e Git

O **GitHub** é uma plataforma online que hospeda repositórios Git.  

Com ele, você pode:
- Armazenar código remotamente  
- Trabalhar em equipe com *pull requests*  
- Criar *issues*, *releases* e documentações  

---

# 🔄 Enviando para o GitHub

Conecte seu repositório local a um remoto:

```bash
git remote add origin https://github.com/usuario/repositorio.git
git branch -M main
git push -u origin main
```

---

# 🧭 Pull Request (PR)

Um **Pull Request** é uma forma de propor mudanças no repositório remoto.  

💬 Permite que outras pessoas revisem seu código antes do merge.  
🍊 É a base do trabalho colaborativo!

---

# 💡 Boas práticas

✅ Faça commits pequenos e frequentes  
✅ Escreva mensagens claras  
✅ Sempre puxe as mudanças antes de subir (`git pull`)  
✅ Use `.gitignore` para evitar arquivos desnecessários  
✅ Revise antes de dar merge  

---

# 🧃 Dica Caju Code 🍊💛

> “Commitar é como plantar: cada commit é uma semente de aprendizado 🌱”

Seja curioso, experimente, erre e aprenda — o Git está aqui pra te ajudar a **registrar sua evolução** 💻✨

---

# 🎯 Recursos úteis

- [Git - Documentação Oficial](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)
- [Try Git](https://try.github.io/)
- [Oh My Git! (jogo interativo)](https://ohmygit.org/)

---

# 💛 Fim

Obrigada por participar!  
Continue praticando e versionando com carinho 🍊  

> _“Pequenos commits geram grandes frutos.”_
