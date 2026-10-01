# Caso fictício: Abelha Operária Melina

Projeto acadêmico que demonstra um fluxo de consulta jurídica assistida por IA com **RAG manual**, verificação de fontes, auditoria independente e revisão humana.

> Caso inteiramente fictício. Pessoas, empresa, fatos, mensagens e documentos foram criados exclusivamente para a atividade. Este material não é parecer jurídico, não substitui consulta profissional e não deve ser usado para decidir caso concreto.

## Finalidade e público

O repositório demonstra como uma pessoa operadora do Direito pode organizar uma consulta inicial sobre jornada, horas extras e justa causa em uma reclamação trabalhista fictícia. Destina-se à avaliação da disciplina e a estudantes que precisem reproduzir o fluxo.

## Fluxo reproduzível

1. Leia `entrada/relato_bruto.md` e `docs/limites_e_sigilo.md`.
2. Use apenas a versão desidentificada em `apoio/caso_sanitizado.md`.
3. Consulte as fontes locais em `apoio/` com a instrução de `prompts/consulta_rag.md`.
4. Compare a resposta em `evidencias/resposta_inicial.md` com `evidencias/verificacao.md`.
5. Execute a auditoria de `prompts/auditoria.md`, registre o resultado e aplique a decisão humana.
6. Entregue somente a orientação revisada de `entrega/orientacao_inicial.md`.

## Estrutura

- `entrada/`: relato fictício bruto.
- `apoio/`: caso sanitizado e corpus fechado de fontes para o RAG manual.
- `docs/`: limites de uso e especificação/contrato da tarefa.
- `prompts/`: instruções da consulta e da auditoria.
- `evidencias/`: resposta, checagem, auditoria e decisão humana.
- `entrega/`: orientação inicial revisada e segura.

## Critérios de aceitação

- A resposta identifica os arquivos e os trechos de fonte usados.
- Não cria fatos, valores, provas ou conclusões definitivas além do corpus.
- Toda afirmação jurídica relevante é conferida e marcada como manter, corrigir ou excluir.
- A entrega final explicita as limitações e a necessidade de revisão humana.

## Repositório

URL pública: https://github.com/M0vero/caso-ficticio-melina

O mesmo link deve ser informado no envio pelo Teams, conforme a atividade.

## Histórico Git esperado

Após inicializar/publicar o repositório, registrar ao menos os commits abaixo (ou equivalentes que descrevam a alteração real):

```text
chore: cria estrutura do caso fictício Melina
docs: conclui fluxo RAG, verificação e revisão humana
```
