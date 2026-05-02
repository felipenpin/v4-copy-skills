# V4 Copy Skills — Guia de uso para o time

> Coordenação: Ueliton Pereira | Copywriter responsável: Felipe Nascimento Pinheiro

---

## O que é isso

Este repositório contém as skills de copywriting da coordenação. Com ele, qualquer account consegue gerar copies brutas para os clientes usando o Claude Code — mesmo sem o Felipe disponível.

As copies geradas são **rascunhos profissionais**. O account revisa e refina antes de publicar.

---

## Como usar — passo a passo

### 1. Instale o Claude Code (se ainda não tiver)

```bash
npm install -g @anthropic-ai/claude-code
```

Você vai precisar de uma conta na Anthropic com acesso ao Claude Code.

### 2. Clone este repositório

```bash
git clone https://github.com/[seu-usuario]/v4-copy-skills.git
```

### 3. Prepare a pasta do cliente

Crie uma pasta para o cliente com os documentos disponíveis:

```
/meu-cliente/
  DCC_[cliente].pdf (ou .docx)   ← se existir
  UCM_[cliente].pdf (ou .docx)   ← se existir
```

Copie os arquivos deste repositório para dentro da pasta do cliente:

```bash
cp -r v4-copy-skills/* meu-cliente/
```

### 4. Abra o Claude Code na pasta do cliente

```bash
cd meu-cliente
claude
```

### 5. Peça o que você precisa

Basta falar em português, de forma natural:

**Para gerar copy:**
> "Gera um anúncio de Meta para [cliente] de topo de funil para gerar leads"

> "Cria um roteiro de reels de 30 segundos para [cliente] — objetivo é mostrar o diferencial de entrega"

> "Faz uma mensagem de WhatsApp de reengajamento para [cliente]"

**Para revisar um hook:**
> "Revisa esse hook: [cole o hook aqui]"

> "Gera 3 opções de hook para um vídeo sobre [tema] para [cliente]"

**Para humanizar um briefing:**
> "Humaniza esse briefing antes de eu gerar a copy: [cole o briefing]"

---

## O que fazer quando não tem DCC ou UCM

**Não trava.** O Claude vai te pedir as informações mínimas:
- Produto/serviço
- Público-alvo
- Maior dor que o cliente resolve
- Tom de voz (formal ou descontraído)

Responde essas 4 perguntas e ele gera a copy.

---

## Estrutura do repositório

```
v4-copy-skills/
  CLAUDE.md                        ← Instruções principais (lido automaticamente)
  README.md                        ← Este arquivo
  contexto/
    boa_copy.md                    ← O que é uma boa copy — referência permanente
  skills/
    gerador_copy.md                ← Skill principal: gera copy por formato
    revisor_hook.md                ← Skill: revisa e melhora hooks
    humanizador_briefing.md        ← Skill: humaniza briefings antes de gerar copy
```

---

## Dúvidas e suporte

Durante a licença paternidade do Felipe, fale com:
- **Ueliton Pereira** — para dúvidas sobre o processo
- **Rafa** — para dúvidas técnicas sobre Claude Code e as skills

---

> *As copies geradas por este sistema são rascunhos profissionais. Sempre revise antes de publicar.*
