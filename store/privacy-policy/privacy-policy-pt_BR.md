# Política de privacidade — Hilitely

**Última atualização:** 7 de novembro de 2026

Esta política descreve como a extensão do Chrome **Hilitely** (“a Extensão”) lida com informações.

## Quem fornece a Extensão

A Extensão é publicada por **PeterShift**.
Contato: **petershift.dev@gmail.com**

## O que a Extensão faz

Em um site que você ativa, a Extensão destaca um trecho que você seleciona e encontra esse destaque de novo depois de recarregar ou de uma mudança na página, pelas palavras e não pelo lugar no layout. Notas, tags e a biblioteca de citações ficam neste computador.

## O que a Extensão guarda

Quando você destaca um texto, a Extensão salva um registro neste computador:

- o texto citado e cerca de 100 caracteres antes e depois, para o destaque poder ser encontrado de novo;
- o endereço da página, o endereço canônico se a página declarar um, e o título da página;
- a cor, e a nota e as tags se você as escrever;
- quando o destaque foi criado e alterado, e se ele foi encontrado na página da última vez.

As configurações também ficam neste computador: a última cor escolhida, se o cursor vai para o campo da nota, como a biblioteca ordena os sites e quais sites ativados você desligou.

## Para onde os dados vão

Para lugar nenhum. Os destaques ficam no navegador, no banco de dados próprio da Extensão neste computador. A Extensão não tem servidor, nem conta, nem análise. Ela não faz requisições de rede. Nós não recebemos seus destaques, suas notas nem os endereços das páginas que você lê.

## Quais sites ela pode ler

A Extensão não pede para ler todos os sites. Ela só funciona nos sites que você ativa pelo ícone da barra, um site de cada vez, pelo diálogo de permissão do Chrome. Até você fazer isso, ela não acrescenta nada à página.

Desligar um site o coloca em pausa. Os destaques somem das abas abertas desse site, e o script não volta a iniciar ali até você ligá-lo de novo. A permissão do Chrome permanece, então ligar de novo não pede acesso outra vez. “Remove access to this site” retira a permissão. Na próxima vez que você ativar esse site, o Chrome pergunta de novo. As citações salvas continuam na biblioteca nos dois casos.

## Backups

O arquivo de backup só é criado quando você escolhe Download backup. Ele é salvo onde o navegador salva os downloads. A importação lê um arquivo que você escolhe. Nenhum dos dois é enviado para lugar nenhum.

## Apagar seus dados

Apague um destaque na página ou na biblioteca, ou use Delete all on this site na biblioteca. Remover a Extensão apaga todos os dados locais dela com a limpeza habitual do navegador.

## Permissões

| Permissão | Por que é pedida |
| --- | --- |
| `storage` | Guarda configurações neste computador: a última cor de destaque, se o cursor vai para a nota, quais sites ativados você desligou e como a biblioteca ordena os sites. As citações ficam no banco próprio da Extensão; esta permissão não as guarda. |
| `activeTab` | Quando você clica no ícone da barra, a janela lê o endereço da aba atual para mostrar o interruptor daquele site e percorrer os destaques da página. |
| `scripting` | Inicia o destaque na aba atual logo depois que você ativa o site, e nas abas daquele site que já estão abertas, sem recarregar a página. Ao desligar o site, remove os destaques dessas abas. |
| Acesso a sites | Não é concedido na instalação. O Chrome pede um site de cada vez, na primeira vez que você o ativa. O destaque só funciona nos sites que você permitiu e não desligou. Desligar interrompe o destaque naquele site e mantém a permissão. “Remove access to this site” a remove. |

## Código remoto

A Extensão executa apenas os arquivos locais incluídos no pacote. Ela não baixa nem executa JavaScript remoto.

## Uso limitado

Os dados são usados apenas para mostrar de novo os seus destaques e listá-los na biblioteca. Não são vendidos, não são repassados a ninguém, não são usados para publicidade nem para avaliar crédito, e ninguém os lê. Esse uso está em conformidade com a Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), inclusive os requisitos de Limited Use.

## Alterações

Se uma versão posterior passar a enviar dados para algum lugar, esta política dirá isso antes do lançamento dessa versão, e a Extensão perguntará a você primeiro.

## Contato

Dúvidas sobre esta política: **petershift.dev@gmail.com**
