
# Oficina: Git e GitHub para Desenvolvimento Colaborativo  
**Centro Universitário de Excelência - UNEX | 17 de Março de 2025**  

---

## Sobre a Oficina
Esta Oficina foi ministrada para graduandos veteranos do curso de **Sistemas de Informação** da UNEX, com foco em práticas modernas de controle de versão e colaboração em equipe usando **Git e GitHub**. 
veja mais no [blog](https://compilando.hashnode.dev/gitgithub-controleversao)
---

## Conteúdo Abordado  

### 1. **Controle de Versão: Por que é essencial?**  
- **Definição**: Sistema que registra mudanças em arquivos, permitindo histórico completo e colaboração.  
- **Tipos**:  
  - **Centralizado (CVCS)**: Ex: SVN, CVS (dependente de rede).  
  - **Distribuído (DVCS)**: Ex: Git, Mercurial (cópia local completa, operações rápidas).  

---

### 2. **Git: O Poder do Versionamento Distribuído**  
- **O que é?**: Sistema criado por **Linus Torvalds** em 2005 para o kernel Linux.  
- **Benefícios**:  
  - Rastreamento detalhado de alterações.  
  - Trabalho offline e segurança com repositórios locais.  
  - Flexibilidade para fluxos de trabalho (branches, merges).  

#### Comandos Essenciais:  
```bash
git init          # Inicializa um repositório  
git clone URL     # Clona um repositório remoto  
git add .         # Adiciona alterações à staging area  
git commit -m "Mensagem"  # Salva mudanças  
git log           # Visualiza histórico  
```

---

### 3. **GitHub: Colaboração em Escala**  
- **Plataforma** para hospedar repositórios, gerenciar projetos e colaborar.  
- **Funcionalidades**:  
  - Issues, Pull Requests, GitHub Pages.  
  - Integração com ferramentas CI/CD.  

#### Comandos para Trabalho Remoto:  
```bash
git remote add origin URL  # Conecta ao repositório remoto  
git push origin main       # Envia alterações  
git pull origin main       # Atualiza repositório local  
```

---

### 4. **Boas Práticas**  
- **Commits atômicos**: Pequenas mudanças com mensagens claras (ex: `feat: adiciona login`).  
- **Branches**: Desenvolva funcionalidades isoladas (ex: `git checkout -b feature/nova-tela`).  
- **.gitignore**: Evite versionar arquivos sensíveis (veja [modelos](https://github.com/github/gitignore)).  

---

### 5. **Recursos Avançados**  
- **Git Flow**: Modelo de branches para projetos complexos (veja [artigo](http://nvie.com/posts/a-successful-git-branching-model/)).  
- **SSH Keys**: Autenticação segura para repositórios remotos (veja [tutorial](https://help.github.com/articles/generating-ssh-keys)).  

---

## Referências Recomendadas  
- Livro: **Pro Git** (Scott Chacon & Ben Straub).  
- Documentação: [Git SCM](https://git-scm.com/doc).  
- Treinamento: [GitHub Skills](https://skills.github.com).  

---

**Contato:**  
- LinkedIn: [Isaque Coelho](https://www.linkedin.com/in/isaquecoelho01)  
- GitHub: [coelhoisaque](https://github.com/coelhoisaque)  
