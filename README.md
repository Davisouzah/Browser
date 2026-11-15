# Browser

Navegador Android leve, em português, baseado no WebView do sistema. Sem motor próprio, sem telemetria e com bloqueio local de anúncios.

**Tamanho:** cerca de 3 MB · **Android:** 8.0 ou superior

## Baixar

[Baixar o APK mais recente](https://github.com/Davisouzah/Browser/releases/latest)

O pacote é assinado com chave própria, então o Android pode exibir um aviso de segurança. Isso é normal para apps fora da Play Store.

## Instalar

1. Baixe o APK.
2. Permita "instalar apps desconhecidos" para o app de arquivos.
3. Toque no arquivo para instalar.
4. Se já tem uma versão anterior, instale **por cima, sem desinstalar**, para manter favoritos, histórico e ajustes.

## Usar como navegador padrão

A partir da 1.10 o app se declara como navegador para o Android. Para abrir links direto nele:

1. Abra **Configurações → Apps → Apps padrão → Navegador**.
2. Escolha **Browser**.
3. Se o aparelho perguntar "Abrir com", escolha **Browser** e toque em **Sempre**.

Para links do YouTube, o próprio YouTube pode abrir o app dele. Se quiser que esses links vão para o Browser, limpe os padrões do YouTube em **Configurações → Apps → YouTube → Abrir por padrão**.

## Solução de problemas

### O GitHub mostra "Not Found"

Essa mensagem vem do próprio GitHub. Normalmente acontece quando o link aponta para um **repositório privado** e você não está logado no GitHub dentro do Browser, ou quando o repositório foi removido/renomeado. Faça login no GitHub pelo Browser ou teste um link público.

### Link do YouTube não abre

O YouTube pode abrir o próprio app para links do YouTube. Para usar o Browser:

1. Abra **Configurações → Apps → YouTube → Abrir por padrão**.
2. Limpe os padrões ou desative a abertura de links compatíveis.
3. Em **Apps padrão → Navegador**, escolha **Browser**.

## Personalizar o mecanismo de busca

O app permite usar **qualquer mecanismo de busca**, inclusive um SearXNG ou outro buscador próprio:

1. Abra o menu.
2. Toque em **Mecanismo de busca**.
3. Escolha **Personalizado…**
4. Digite a URL de busca usando `%s` no lugar do termo pesquisado.

Exemplo:

```text
https://seu-buscador.exemplo/search?q=%s
```

O padrão de uma instalação nova é DuckDuckGo. Também há opções prontas para Google, Bing e Startpage.

## Recursos

- Abas com limite de 3, liberando memória das abas inativas
- Botão Início ao lado de recarregar
- Favoritos e histórico locais, com ícones redondos, remoção individual e limpeza
- Bloqueio de anúncios e rastreadores com lista local
- Modo econômico sem imagens
- Tradução de páginas para português
- Modo desktop, escurecer sites, JavaScript ligável/desligável e zoom por pinça
- Upload e download de arquivos
- Página inicial local, sem abrir uma aba de rede

## Privacidade

- Favoritos e histórico ficam somente no aparelho.
- Não há telemetria, anúncios próprios nem serviços em segundo plano.
- A tradução envia o texto da página ao Google Translate; o restante da navegação continua local.

## Verificação

SHA-256 do APK 1.10:

```text
30f6cec49ba80337f3bdc340a58031299f22cb42162da09e768e0c8d774f9290
```

O código-fonte não é distribuído neste repositório.
