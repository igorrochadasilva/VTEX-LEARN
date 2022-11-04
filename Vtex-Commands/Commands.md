## Visão geral

* Verifique a seguir uma breve descrição dos principais comandos da CLI do VTEX IO.

* Nome do Comando || Funcionalidade

- browse || Abre a URL relativa à sua área de trabalho e conta atuais em uma nova janela do navegador.

- deploy || Publica um aplicativo como uma versão estável. Funciona apenas para aplicativos publicados anteriormente como uma versão candidata a lançamento.

- deprecate || Obsoleta o aplicativo especificado, desinstalando e fazendo o downgrade para a versão estável mais recente em cada conta VTEX.

- deps diff	 || Exibe as diferenças entre as dependências de duas áreas de trabalho distintas.

- deps list	 ||  Exibe a árvore de dependência completa do espaço de trabalho atual.

- deps update  ||  Atualiza uma dependência do espaço de trabalho atual. Se não for especificado qual, ele atualiza todas as dependências.

- edition get  ||  Exibe a versão do Edition App instalada na conta atual.

- help  ||  	Exibe ajuda para comandos VTEX CLI.

- init  ||  	Copia arquivos e pastas iniciais de boilerplates VTEX para seus diretórios locais.

- install  ||  	Instala um aplicativo no espaço de trabalho atual. Se não for especificado qual, o padrão é o aplicativo no diretório atual.

- link  ||  	Sincroniza o aplicativo no diretório atual com o espaço de trabalho de desenvolvimento em uso.

- list  ||  	Lista os aplicativos instalados no espaço de trabalho e conta atuais.

- local  ||  token	Imprime o token de autenticação do usuário e o copia para a área de transferência.

- login  ||  	Efetua login em uma conta VTEX.

- logout   ||  	Sai da conta VTEX atual.

- publish  ||  	Publica o aplicativo no diretório atual como uma versão candidata a lançamento.

- release  ||  	(Apenas para usuários git.) Bump a versão do aplicativo, confirma e empurra para o aplicativo remoto no diretório atual.

- setup  ||  	Configura tipificações e ferramentas para o ambiente de desenvolvimento atual.

- switch  ||  	Muda para outra conta VTEX.

- undeprecate  ||  	Restabelece uma versão obsoleta de um aplicativo como uma versão estável.

- uninstall  ||  	Desinstala um aplicativo da conta e do espaço de trabalho atuais.

- unlink  ||  	Desvincula um aplicativo do espaço de trabalho atual.

- update  ||  	Atualiza todos os aplicativos instalados para a versão mais recente (secundária ou patch). Não atualiza para outra versão principal.

- whoami  ||  	Imprime a conta atual, área de trabalho, ambiente e detalhes de login.

- workspace  ||   delete	Exclui um ou vários espaços de trabalho da conta atual.

- workspace  ||   list	Lista todos os espaços de trabalho da conta atual.

- workspace   ||  promote	Promove a área de trabalho atual a master. Funciona apenas para espaços de trabalho de produção

- workspace   ||  reset	Limpa todas as configurações do espaço de trabalho especificado e o recria com as configurações do mestre.

- workspace   ||  status	Exibe informações sobre o espaço de trabalho especificado.

- workspace   ||  use	Cria e muda para um novo espaço de trabalho ou simplesmente muda para um existente.