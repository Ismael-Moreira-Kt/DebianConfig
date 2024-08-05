# DebianConfig
DebianConf é um conjunto de scripts para configurar facilmente vários aspectos de Debian, incluindo a interface gráfica, som, rede, sistema e hardware, pacotes, segurança e backup. Este script é ideal para utilizadores que querem configurar rapidamente um ambiente Debian de acordo com as suas preferências.

<br><br>

## Pré-requisitos
Antes de correr o script, certifique-se que o seu sistema Debian está preparado com os seguintes pacotes:

```bash
sudo apt update -y && sudo apt upgrade -y
sudo apt install -y git
```

Certifique-se de que tem permissões sudo, o script requer privilégios de superutilizador para instalar pacotes e aplicar definições.

<br><br>

## Instalação
Clone o arquivo que contém o script DebianConf:

```bash
git clone https://github.com/Ismael-Moreira-Kt/DebianConfig
cd DebianConfig
```

Dar permissão de execução ao script principal:

```bash
chmod +x dc
```

<br><br>

## Utilização
Para iniciar o processo de configuração, execute o script principal:

```bash
./dc
```

O script irá guiá-lo através de um menu principal onde pode escolher o tipo de configuração que pretende.

### No menu principal, pode escolher entre as seguintes opções:
- **Configurar Interface Gráfica:** Personaliza o estilo da interface gráfica do GNOME.
- **Configurar som e áudio:** Ajusta as configurações de som e áudio do sistema.
- **Configurar rede:** Configura as definições de rede.
- **Configurar Sistema e Hardware:** Ajusta as definições de sistema e hardware.
- **Configurar pacotes:** Instala e configura pacotes adicionais.
- **Configurar sistemas de segurança:** Aplica definições de segurança ao sistema.
- Configurar Backup:** Configura opções de backup para os seus dados.
- **Configurar tudo automaticamente:** Aplica todas as definições automaticamente.
- **Sair:** Sai do script.

### Detalhes da função
#### Funções gerais
- **check_sudo:** Verifica se o script está a ser executado com permissões sudo.
- **Show_menu:** Mostra um menu e trata a entrada do utilizador.
- **Setup:** Configura o ambiente com base na escolha do idioma

#### Configurações específicas
- **Configurar a interface gráfica:** Aplica temas e configurações de ícones para diferentes estilos, incluindo GNOME Dark, GNOME Light, estilo macOS, estilo Windows e estilo Retro.
- **Configurar som e áudio:** Instala e configura pacotes para ajustar o som e o áudio do sistema.
- **Configurar rede:** Ajusta as definições de rede, como IP, DNS e configuração de ligação.
- **Configuração do sistema e do hardware:** Aplica definições e configurações ao sistema e ao hardware.
- **Configurar pacotes:** Instala e configura pacotes adicionais necessários para o sistema.
- **Configurar sistemas de segurança:** Aplica definições e pacotes para melhorar a segurança do sistema.
- **Configurar Backup:** Configura opções e ferramentas para backup de dados.
- **Configurar Tudo Automaticamente:** Aplica todas as definições e ajustes automaticamente sem intervenção adicional.