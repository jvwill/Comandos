# LISTA DE PACOTES DO LINUX
### Descrição
*Este é um sub-repositório de* **[COMANDOS_DEBIAN](https://github.com/jvwill/Comandos/blob/main/COMANDOS%20-%20DEBIAN.md)** *com pacotes, nomes de instalação e seus comandos*

#

Segue uma lista com alguns ```Pacotes``` para instalar no Linux e seus ```Comandos``` ***(digite o nome do pacote que está em parenteses)***
- VIM **(vim)**
- SSH **(ssh openssh-server)**
- Net-tools **(net-tools)**
- DNS **(dnsutils)**
- Apache 2 **(apache2)**
- Apache 2 Doc **(apache2-doc)**
- Bind9 **(bind9)**
- Bind9 Doc **(bind9-doc)**
- W3m **(w3m)**
- DHCP **(isc-dhcp-server)**
- Proftpd **(proftpd)**

### Comandos dos Pacotes
__VIM__:

<div align="center">
     para entrar em edição de texto sem instalar, substituia o <b>"vim"</b> por <b>"vim.tiny"</b>
</div>

1. Configs do VIM:
     ```ruby
     vim /etc/vim/vimrc
     ```
2. Exibir número de linhas:
     ```ruby
     vim /etc/vim/vimrc
     procurar e descomentar "syntax ON"
     escrever "set number" na linha de baixo
     ```
3. Outros comandos:

| Função | Comando |
| --- | --- |
| Entrar no Insert | Tecla "i" |
| Sair do Insert | Tecla "esc" |
| Sair e salvar | "wq" |
| Sair sem salvar | "q!" |
| Copiar ___linhas___ | "y + nº de linhas + y" |
| Colar ___linhas___  | "p" |

__APACHE 2__:
1. Desabilitar site:
  ```ruby
  a2dissite
  ```
2. Habilitar site:
  ```ruby
  a2insite
  ```
3. Configurar arquivo Index de maneira simples:
  ```ruby
  echo "Mensagem Index" > /var/www/[Diretório_do_site]/index.html
  ```

__BIND9__ - ***Alguns comandos necessitam do VIM ou editor de texto***
1. Declarar uma zona 
```ruby
vim named.conf.local
```
2. Ver zonas default
```ruby
vim named.conf.default-zone
```

__PROFTPD__ - ***Alguns comandos necessitam do VIM ou editor de texto***
1. Configurar o proftpd
```ruby
vim proftpd.conf
```

__NGINX__ - ***Alguns comandos necessitam do VIM ou editor de texto***
1. Config. do Nginx
```ruby
vim /etc/nginx/nginx.config
```
