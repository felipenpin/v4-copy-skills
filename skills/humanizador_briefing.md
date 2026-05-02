# SKILL — Humanizador de Briefing

> Skill de humanização de briefings antes de transformar em copy | V4 Company

---

## O que esta skill faz

Recebe um briefing cru (geralmente preenchido pelo account ou gerado automaticamente) e o transforma em um briefing humanizado — com linguagem real, tensão emocional e contexto de persona — antes de virar copy.

O problema que esta skill resolve: briefings seguidos à risca geram copies robotizadas. Esta skill interpreta o briefing como um copywriter humano faria, adicionando o que está implícito mas não está escrito.

---

## Inputs necessários

- O briefing original (texto cru, formulário preenchido, ou notas do account)
- Nome do cliente
- Formato de destino da copy (para calibrar o tom)

---

## O que é um briefing robotizado vs. humanizado

| Briefing robotizado | Briefing humanizado |
|---|---|
| "Cliente: Vinatex. Produto: tecidos. Objetivo: gerar leads." | "A Vinatex quer atrair lojistas que já foram frustrados por fornecedores que atrasam. O diferencial real é entrega no mesmo dia — isso resolve uma dor concreta e urgente do lojista." |
| "Público: mulheres 30-50 anos, interessadas em saúde." | "Mulheres entre 30 e 50 que já tentaram outros tratamentos e não tiveram resultado. Elas estão céticas, mas ainda esperançosas. A copy precisa respeitar essa desconfiança." |
| "Tom: profissional e acolhedor." | "Tom de quem entende o problema sem ser condescendente — como um especialista que fala com quem já sofreu com o problema, não com quem ainda está descobrindo que tem." |

---

## Protocolo de execução

1. Leia o briefing original
2. Leia o DCC do cliente se disponível — ele vai revelar o que o briefing não disse
3. Identifique o que está implícito mas não escrito:
   - Qual é a dor real por trás do objetivo?
   - Quem é a persona de verdade, além dos dados demográficos?
   - Qual é a tensão emocional que a copy precisa tocar?
   - O que o cliente NÃO quer que a copy faça?
4. Reescreva o briefing com essas camadas adicionadas
5. Entregue o briefing humanizado ao account para validar antes de gerar a copy

---

## Formato de entrega

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
BRIEFING HUMANIZADO — [Nome do Cliente] | [Formato de destino]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

BRIEFING ORIGINAL:
[briefing enviado pelo account]

━━━━━━━━━━━━━━━━━━

BRIEFING HUMANIZADO:

CLIENTE E CONTEXTO:
[Quem é o cliente, o que vende, qual é o diferencial real — não o slogan]

PERSONA REAL:
[Quem é de verdade, além dos dados demográficos — o que sente, o que teme, o que já tentou]

DOR CENTRAL:
[A frustração específica que a copy precisa tocar]

DESEJO REAL:
[O que a persona quer de verdade — não o produto, mas o resultado que o produto entrega]

TOM DE VOZ PARA ESTA PEÇA:
[Como falar com esta persona neste formato — com exemplos de linguagem]

O QUE EVITAR:
[O que soaria falso, genérico ou irritante para esta persona]

━━━━━━━━━━━━━━━━━━

PRÓXIMO PASSO:
Account valida o briefing humanizado. Depois, use a skill gerador_copy.md para gerar a copy.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## Nota importante

Esta skill **não gera a copy final** — ela prepara o terreno para que a copy seja humana desde o início. Depois de validar o briefing humanizado, passe para a skill `gerador_copy.md`.
