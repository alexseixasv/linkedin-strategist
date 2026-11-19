# LinkedIn Strategist

Prompt master para otimizar perfis de LinkedIn de engenheiros de software, com foco em mercado internacional, SEO para recrutadores e posicionamento técnico consistente.

## Como usar

1. Abra [`docs/prompt.md`](docs/prompt.md).
2. **Ajuste o prompt** ao seu caso (mercado-alvo, senioridade desejada, restrições pessoais, etc.), se necessário.
3. Preencha a seção **DADOS DO ALUNO** com o conteúdo atual do seu LinkedIn (e informações extras relevantes).
4. **Use o prompt dentro da sua própria LLM** (ChatGPT, Claude, Gemini, Cursor, etc.).

O essencial deste repositório é o prompt. Não há app ou API embutida: você copia o master prompt, personaliza e executa na LLM que preferir.

## O que o prompt entrega

Saída no formato `LINKEDIN OPTIMIZATION — [SEU NOME]`, incluindo:

- Headline, About (até **1.700 caracteres**), Top Skills e Additional Skills
- Experiências e Education reescritas em inglês
- Justificativas do posicionamento e recomendações finais em português

### Regras importantes das Top Skills

As cinco Top Skills devem ser **hard skills** concretas (ex.: Java, Python, C#, TypeScript, Amazon Web Services, Kubernetes).

Não use soft skills nem conceitos abstratos nas Top Skills (ex.: Leadership, Software Architecture, Distributed Systems), **exceto** quando o posicionamento for de arquiteto de software / role de arquitetura.

## Estrutura

```text
docs/prompt.md   ← Master prompt (copie, ajuste e rode na sua LLM)
README.md        ← Este guia
```
