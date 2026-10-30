# Processo de Release

## Preparacao

1. Confirme que as mudancas foram revisadas e que os testes aplicaveis passaram.
2. Atualize `CHANGELOG.md` com impacto e referencias relevantes.
3. Verifique que nao ha dados sensiveis no historico da mudanca.

## Publicacao

1. Crie uma tag versionada seguindo `vMAJOR.MINOR.PATCH`.
2. Publique notas curtas com mudancas, compatibilidade e instrucoes necessarias.

## Apos o release

Monitore relatos, corrija regressões e documente qualquer ajuste em uma nova pull request.