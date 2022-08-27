---
title: Contribuição
sidebar_position: 3
slug: /contribution
description: Uma lista de toneladas de recursos e utilitários úteis para todos os tipos de usuários, desde iniciantes até usuários experientes.
---

```mdx-code-block
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
```

# Contribuição

Encontrou uma informação errada ou um erro de digitação? Ou tem um bom recurso que se encaixa nesta lista? Torne-se um colaborador e esteja na gloriosa lista de colaboradores abaixo!<br/>
Para contribuir, você é mais do que bem-vindo para fazer um PR desta wiki ou enviar uma DM para @755792681313108018 para editar a wiki e adicionar você na lista.
Você também pode participar do [Servidor Oficial do Projeto](https://discord.gg/yxbqz9pNxS) para contribuir lá.

## Contribuidores

Este projeto levou mais do que apenas um par de mãos, e estamos orgulhosos de ter essa equipe de colaboradores que nos ajudaram com este projeto!<br/>
Queremos agradecer:<br/>
@795977947558182954 - Mantenedor da Wiki <br/>
@885165099847929887 - <https://dis.wiki/> Dono do Redirecionamento <br/>
@856780995629154305 - Mantenedor do Site <br/>
@347727875266576395 - Arquiteto da Wiki <br/>
@391660873409888277 - Corretor da Wiki<br/>
@363481883369013259 - Gerenciador do GitHub / Organizador de Documentação<br/>
@337654195526303746 - Pesquisador de Recursos / Mantenedor<br/>
@337104786593939456 - Organizador de Documentação<br/>
@135877336804360194 - Mantenedor do Site <br/>
@485676072176713729 - Pesquisador de Recursos / Mantenedor<br/>
@762387276595724308 - Pesquisador de Recursos / Mantenedor<br/>
@378537973215657984 - Gerente do Projeto / Organizador de Documentação<br/>
@287711497118023692 - Pesquisador de Recursos / Organizador de Documentação<br/>
@192060404501839872 - Designer<br/>
@386861188891279362 - Arquiteto do Site / Organizador de Documentação<br/>
@102102717165506560 - Consultoria de Crescimento / Revisor de Recursos<br/>
@755792681313108018 - *Eu tive essa ideia e fiz tudo acima*  <br/>
@480495309491798037 - <http://discord.wiki/> Dono do Redirecionamento <br/>
@421991668556759042 - Criador do [PreMiD Presence](https://premid.app/store/presences/Discord%20Resources)
@427146305651998721 - Mantenedor

## Como testar as alterações localmente

Tem um ótimo PR em andamento, mas não sabe como está ficando? Sem problemas!<br/>

Os requisitos são:<br/>
Versão do Node.js >= ```16.5.0```<br/>

Se estiver usando Yarn:<br/>
Versão do Yarn >= ```1.22.0```

Dê um Fork no repositório do GitHub e clone-o localmente.

```bash
git clone https://github.com/yourusername/Discord-Resources-Wiki
```

Em seguida, abra o diretório `Discord-Resources-Wiki` e execute o seguinte comando:
  
```mdx-code-block
<Tabs>
<TabItem value="npm">
```

```bash
npm install
```

```mdx-code-block
</TabItem>
<TabItem value="yarn">
```

```bash
yarn install
```

```mdx-code-block
</TabItem>
</Tabs>
```

Isso baixa todos os repositórios necessários para nosso sistema de documentação (Docusaurus). Você só precisa executar isso uma vez.

Para ver nomes de usuário como no site, você deve criar um novo aplicativo Discord e torná-lo um Bot.
Siga este [link](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token) para criar um novo aplicativo.

Para obter seu token de bot recém-criado, vá para as configurações do aplicativo e clique na guia "Bot".
Clique no botão "Token" e você verá seu token de bot.

Agora crie um novo arquivo chamado .env no diretório raiz e cole o seguinte:

```env
DISCORD_TOKEN=<tokenhere>
```

Salve o arquivo.

Para testar suas alterações localmente, execute o seguinte comando:

```mdx-code-block
<Tabs>
<TabItem value="npm">
```

```bash
npm start
```

```mdx-code-block
</TabItem>
<TabItem value="yarn">
```

```bash
yarn start
```

```mdx-code-block
</TabItem>
</Tabs>

Este comando inicia o servidor web (```localhost:3000``` por padrão) e deve ser executado toda vez que você quiser ver as alterações.
No entanto, ele não precisa ser executado para cada alteração que você fizer, pois o Docusaurus reiniciará automaticamente o servidor quando detectar alguma alteração!

Assim que tiver uma instância do site em execução localmente, você estará pronto para começar a contribuir!
Notas: Por favor, use ```<br/>``` para quebra de linha.
