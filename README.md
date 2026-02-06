# 📘 GitFlow Lab — Repositório Educacional

🚀 Repositório criado para **aprender, testar e dominar o GitFlow** em um ambiente colaborativo.

Este projeto funciona como um **laboratório prático**, simulando cenários reais de desenvolvimento em equipe, com foco em organização, versionamento e boas práticas usando **Git e GitHub**.

---

## 🎯 Objetivo do Projeto

👥 Proporcionar um ambiente seguro para que colaboradores possam:

* Praticar **GitFlow na prática**
* Trabalhar com **branches organizadas**
* Criar e revisar **Pull Requests**
* Resolver **conflitos de merge**
* Entender fluxos reais de trabalho em equipe

🧪 Este repositório não tem foco em um produto final, mas sim no **processo**.

---

## 🔀 Fluxo Git (GitFlow)

📌 Padrão de branches utilizado:

* `main` → versão estável
* `develop` → base de desenvolvimento
* `feature/nome-da-feature` → novas funcionalidades
* `hotfix/nome-do-hotfix` → correções urgentes
* `release/nome-da-release` (opcional) → preparação de versão

🔁 Todo desenvolvimento deve partir da branch `develop`.

---

## 🛠️ Regras de Contribuição

⚠️ **Antes de começar:**

* Garanta que você tenha Git instalado
* Faça um fork do repositório (se aplicável)
* Mantenha sua branch `develop` atualizada

### 🧩 Passo a passo para contribuir

1️⃣ Crie uma branch a partir de `develop`:

```bash
git checkout develop
git pull origin develop
git checkout -b feature/nome-da-feature
```

2️⃣ Desenvolva sua alteração

3️⃣ Commits claros e objetivos:

```bash
git commit -m "feat: descrição clara do que foi feito"
```

4️⃣ Envie a branch para o repositório remoto:

```bash
git push origin feature/nome-da-feature
```

5️⃣ Abra um **Pull Request** para a branch `develop`

---

## 🧾 Padrão de Commits

📝 Utilize mensagens claras, preferencialmente seguindo o padrão:

* `feat:` nova funcionalidade
* `fix:` correção de bug
* `docs:` documentação
* `style:` formatação (sem impacto lógico)
* `refactor:` refatoração de código
* `test:` testes

📌 Exemplo:

```bash
feat: adiciona validação no formulário de login
```

---

## 👀 Pull Requests & Code Review

🔍 Todo PR deve:

* Ter um título claro
* Explicar **o que foi feito** e **por quê**
* Estar relacionado a uma branch correta
* Ser revisado por pelo menos 1 colaborador (se possível)

💬 Feedbacks devem ser construtivos e objetivos.

---

## 🚨 Resolução de Conflitos

⚔️ Conflitos são esperados e fazem parte do aprendizado.

📌 Em caso de conflito:

* Atualize sua branch com `develop`
* Resolva os conflitos localmente
* Teste antes de commitar
* Peça ajuda se necessário

---

## 📚 Boas Práticas

✅ Sempre puxe as atualizações antes de iniciar uma tarefa
✅ Use nomes de branches claros
✅ Não commite direto na `main`
✅ Documente decisões importantes

---

## 🤝 Colaboradores

👥 Este repositório é colaborativo e aberto ao aprendizado.

Seja respeitoso, colaborativo e curioso. Errar faz parte do processo 🚀

---

## 📢 Observações Finais

🧠 Este projeto é voltado para **treinamento**, **experimentação** e **evolução técnica em equipe**.

Sinta-se à vontade para sugerir melhorias no fluxo, na documentação ou nas regras.

Happy coding! 💻✨
