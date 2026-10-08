# JáCopiei? — Instaladores

Repositório público de instaladores e metadados do JáCopiei? para macOS. O código-fonte do app permanece privado.

O JáCopiei? confere cópias pelo conteúdo e permite copiar os arquivos sem cópia encontrada, preservando os originais e verificando o resultado após a gravação.

## Download

Consulte as [Releases](https://github.com/Benfic4rthur/JaCopiei-Releases/releases) para baixar o instalador. O [manifesto público](https://raw.githubusercontent.com/Benfic4rthur/JaCopiei-Releases/main/latest.json) informa a versão atual e o link exato do download, sem depender de um número fixo neste documento. O pacote universal atende Apple Silicon e Intel, com macOS 14 ou superior.

A distribuição atual é **experimental**: assinatura local ad hoc, sem notarização da Apple e sem atualização automática ativa. O macOS pode bloquear a instalação após o download. A distribuição de produção exige assinatura Developer ID e notarização. A compilação universal não substitui a validação em um Mac Intel físico.

O teste gratuito de **7 dias** começa ao clicar em **Começar meus 7 dias grátis**, sem cartão e sem cobrança automática. Depois do prazo, novas verificações e cópias ficam bloqueadas; o histórico permanece acessível. A área **Contratar licença** apresenta R$ 29,99/mês. A contratação está em preparação: esta versão não recebe pagamentos nem ativa licenças pagas.

`latest.json` informa versão, build, links dos arquivos, SHA-256, arquiteturas e estado da distribuição. O site deve obter a versão e os downloads desse manifesto e respeitar `channel`, `codeSigning` e `automaticUpdatesAvailable`. As notas de cada release descrevem as funcionalidades e limitações da versão.

## Atualizações

O feed `appcast.xml` está reservado para versões de produção autenticadas. Permanece vazio enquanto não houver instalador de produção assinado e notarizado. O build experimental não consulta nem instala atualizações.

Os instaladores são compilados no Mac e enviados diretamente para GitHub Releases, sem GitHub Actions e sem Artifact Storage. Este repositório não contém fontes do app, servidores, dados de clientes ou chaves privadas.
