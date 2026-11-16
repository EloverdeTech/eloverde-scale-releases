# Eloverde — Downloads e versões

Repositório oficial de distribuição do aplicativo Eloverde para Windows, com instaladores e notas de cada versão.

## Sobre o aplicativo

O Eloverde conecta balanças compatíveis ao computador, exibe o peso em tempo real e gera QR Codes para transferir a leitura para outros aplicativos.

- Leitura de peso por conexão serial.
- Seleção do modelo de balança e da porta de comunicação.
- Geração manual de QR Code ou automática após três segundos de peso estável.
- Configurações salvas no computador.

## Requisitos

- Windows x64.
- Balança compatível, configurada para o protocolo selecionado.
- Cabo e adaptador USB–serial, quando necessários, com o driver instalado.

A disponibilidade de um modelo no aplicativo não substitui a homologação do equipamento e da configuração utilizados.

## Como instalar

1. Acesse **Releases** neste repositório.
2. Escolha a versão publicada e consulte suas notas.
3. Em **Assets**, baixe `Eloverde-<versão>-win-x64-setup.exe`.
4. Execute o instalador e siga o assistente.
5. Abra o Eloverde e configure a conexão da balança.

Encerre outros programas que estejam utilizando a mesma porta de comunicação.

Os instaladores iniciais não possuem assinatura digital. O Windows pode exibir um aviso de editor desconhecido. Em computadores corporativos, siga as orientações da equipe de TI.

## Atualizações

Inicialmente, a atualização é manual: baixe o instalador da nova versão, encerre o aplicativo e execute a instalação.

A atualização automática está em preparação. Sua disponibilidade será informada nas notas da versão correspondente.

## Arquivos das releases

| Arquivo | Finalidade |
| --- | --- |
| `Eloverde-<versão>-win-x64-setup.exe` | Instalador do aplicativo. |
| `SHA256SUMS.txt` | Verificação da integridade do instalador. |
| `build-info.json` | Identificação da versão e da compilação. |
| `INSTALACAO.txt` | Instruções de instalação e verificação. |

Quando a atualização automática estiver disponível, as releases também incluirão `latest.yml` e o arquivo `.blockmap` do instalador. Esses arquivos serão utilizados pelo aplicativo.

## Suporte

Utilize o canal de atendimento da Eloverde e informe:

- Versão do aplicativo e do Windows.
- Modelo da balança e tipo de conexão.
- Descrição do problema e mensagem de erro.

O código-fonte e o desenvolvimento do aplicativo são mantidos em um repositório separado.
