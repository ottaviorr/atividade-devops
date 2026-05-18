# 🚀 Laboratório de DevOps I - Aula 10

Repositório dedicado à centralização de anotações, comandos práticos e experimentos realizados no laboratório da disciplina de **DevOps I**.

---

## 📌 Sobre

O foco principal deste material é documentar a base fundamental de controle de versão e segurança em ambientes de desenvolvimento, servindo como um guia rápido de consulta para as práticas executadas durante a **Aula 10**.

## 🗂️ Conteúdo Abordado

- 🌿 **Controle de Versão:** Práticas essenciais com Git e sincronização remota via GitHub.
- 🔑 **Segurança & SSH:** Criação e configuração de chaves criptográficas para autenticação segura (Passwordless).
- 🛡️ **Boas Práticas:** Organização de fluxo de trabalho e implementação de Autenticação Multifator (MFA).

---

## 🛠️ Referência Rápida de Comandos

### 1. Essencial do Git
Comandos de rotina para manter seu código versionado e sincronizado.

```bash
git init                      # Inicializa um novo repositório local
git status                    # Verifica o estado dos arquivos (modificados/untracked)
git add .                     # Adiciona todas as mudanças ao Stage
git commit -m "feat: resumo"  # Cria um commit com mensagem descritiva e semântica
git push origin main          # Envia os commits locais para o repositório remoto
