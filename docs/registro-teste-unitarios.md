# Registro de Testes Unitários

**Aluno:** Beatriz
**Grupo:** 01
**Data:** 24/09/2026

## Testes escritos

| # | Arquivo            | O que o teste verifica                                                   | Tipo    |
| - | ------------------ | ------------------------------------------------------------------------ | ------- |
| 1 | validators.test.js | Verifica se um e-mail válido não retorna erro                            | sucesso |
| 2 | validators.test.js | Verifica se um e-mail sem @ retorna a mensagem "E-mail inválido"         | falha   |
| 3 | validators.test.js | Verifica se um nome com exatamente 3 letras é aceito quando o mínimo é 3 | borda   |
| 4 | parseId.test.js    | Verifica se um id "12abc" deveria lançar ValidationError                 | falha   |

## Resultado

**Passaram:** 5 testes

**Falharam:** 1 teste

## Defeito encontrado

**Teste:** parseId("12abc")

**Esperado:** ValidationError

**Obtido:** A função não lançou nenhum erro.

## Cobertura

**% Lines da linha "helpers":** 55,55%

**Em uma frase, o que esse número significa:**
Significa que 55,55% das linhas de código dos helpers foram executadas pelos testes.
