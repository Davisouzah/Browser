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

SHA-256 do APK 1.8:

```text
076d59a8b853881102feb649e2087ed3eb6eeaf880605e424edf6732212e53fc
```

O código-fonte não é distribuído neste repositório.
