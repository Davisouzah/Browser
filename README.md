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

A partir da 1.12 o app se declara como navegador para o Android e implementa o serviço Chrome Custom Tabs completo, usado pelo YouTube para abrir links externos. Para abrir links direto nele:

1. Abra **Configurações → Apps → Apps padrão → Navegador**.
2. Escolha **Browser**.
3. Se o aparelho perguntar "Abrir com", escolha **Browser** e toque em **Sempre**.

Links de vídeos do YouTube ainda podem abrir o app do YouTube; isso é comportamento do próprio YouTube. Links externos da descrição agora podem ser entregues ao Browser pelo Custom Tabs.

## Solução de problemas

### O GitHub mostra "Not Found"

Essa mensagem vem do próprio GitHub. Normalmente acontece quando o link aponta para um **repositório privado** e você não está logado no GitHub dentro do Browser, ou quando o repositório foi removido/renomeado. Faça login no GitHub pelo Browser ou teste um link público.

### Link do YouTube não abre

A 1.12 implementa o serviço **Chrome Custom Tabs** completo, que o YouTube usa para abrir links externos da descrição. Se a mensagem "Não é possível abrir este link" continuar:

1. Confirme que a versão instalada é a **1.15**.
2. Reinicie o aparelho após instalar.
3. Em **Apps padrão → Navegador**, escolha **Browser**.
4. Para links de vídeos do YouTube, o próprio YouTube pode abrir o app dele; isso é normal.

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
- Aba ativa com marcador visual e botão de fechar ampliado
- Botão Início ao lado de recarregar
- Favoritos e histórico locais, com ícones redondos, remoção individual e limpeza
- **Apagar dados** com opções: histórico, cookies/cache e abas abertas
- **Apagar ao sair** opcional
- **Contador de anúncios bloqueados por página** no topo do menu
- Menu em seções com ícones e estado dos ajustes, com **Apagar dados** em destaque
- Bloqueio de anúncios e rastreadores com lista local
- Modo econômico sem imagens
- Tradução de páginas para português
- Modo desktop, escurecer sites, JavaScript ligável/desligável e zoom por pinça
- **Transferências** no menu: lista downloads do app, com progresso, abrir, pausar/retomar (retomar recomeça) e remover
- Upload e download de arquivos
- Compatibilidade com Chrome Custom Tabs, usada pelo YouTube para links externos
- Página inicial local, sem abrir uma aba de rede

## Privacidade

- Favoritos e histórico ficam somente no aparelho.
- Não há telemetria, anúncios próprios nem serviços em segundo plano.
- A tradução envia o texto da página ao Google Translate; o restante da navegação continua local.

## Verificação

SHA-256 do APK 1.15:

```text
2e9377b11655b7037c0a9296b0ee524d11d7c3b6ffa00eb93c09ad4fcc4498ef
```

O código-fonte não é distribuído neste repositório.
