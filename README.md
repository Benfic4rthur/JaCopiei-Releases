# JáCopiei? — Instaladores

Repositório público de instaladores e atualizações do JáCopiei? para macOS. O código-fonte do app permanece privado.

O JáCopiei? confere cópias pelo conteúdo e permite copiar os arquivos sem cópia encontrada, preservando os originais e verificando o resultado após a gravação.

## Download

Baixe o [instalador experimental 0.3.0](https://github.com/Benfic4rthur/JaCopiei-Releases/releases/tag/v0.3.0) ou consulte todas as [Releases](https://github.com/Benfic4rthur/JaCopiei-Releases/releases). O pacote universal é destinado a macOS 14 ou superior, em Apple Silicon e Intel.

A primeira disponibilização 0.3 é **experimental**: assinatura local ad hoc, sem notarização da Apple e sem atualização automática ativa. O macOS pode bloquear a instalação após o download. A distribuição de produção exige assinatura Developer ID e notarização. Compilação universal não substitui validação em um Mac Intel físico.

`latest.json` informa a versão, link real do instalador, SHA-256, arquiteturas e o estado da distribuição. O site deve respeitar `channel` e `automaticUpdatesAvailable` antes de apresentar o download como estável.

## Atualizações

O feed `appcast.xml` está reservado para versões de produção autenticadas. Permanece vazio enquanto não houver instalador de produção assinado e notarizado. O build experimental não consulta nem instala atualizações.

Este repositório não contém fontes do app, servidores, dados de clientes ou chaves privadas. Não utiliza GitHub Actions.
