# LiberacaoGitProxyETECAB
### Configuração para liberação dos comandos git no proxy através do cmd

Quando o github não está liberado no proxy, fica impossível realizar o upload de seus arquivos para o repositório desejado. Para resolver este problema, é necessário realizar um comando essencial diretamente no prompt de comando, e após a realização já será possível fazer o upload de seus arquivos para o repositório desejado.

## Comando de liberação
```
git config --global http.proxy http://etecadolphoberezin@17.1.0.1:3128
```

Lembre-se também de realizar todos os comandos e logar sua credencial, [clicando aqui](https://github.com/ermogenes/aulas-programacao-csharp/blob/master/content/github-login.md) você será direcionado à um repositório específico, de autoria do [Professor Ermogenes Palácio](https://github.com/ermogenes), onde contém as devidas informações de como realizar os comandos e logar sua credencial.