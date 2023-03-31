## Minhas Configurações Dotfiles

Este repositório contém minhas configurações personalizadas para vários aplicativos e sistemas operacionais. Para usá-las em sua própria máquina, siga as instruções abaixo.

### Instruções

1. Clone o repositório em sua máquina local usando o seguinte comando no terminal:

```
git clone https://github.com/moouro/my-dotfiles.git
```

2. Navegue até o diretório onde você acabou de clonar o repositório:

```
cd ~/caminho/para/o/dotfiles/
```

3. Escolha os arquivos de configuração que deseja usar e crie links simbólicos para eles na pasta home do seu usuário. Por exemplo, se quiser usar meu arquivo `.zshrc`, execute o seguinte comando:

```
ln -s ~/caminho/para/o/dotfiles/.zshrc ~/.zshrc
```

Isso criará um link simbólico para o arquivo `.zshrc` em sua pasta home (`~`).

4. Repita o passo 3 para qualquer outro arquivo de configuração que desejar.

5. Teste se as configurações foram aplicadas corretamente executando os programas correspondentes. Por exemplo, abra o ZSH para testar suas configurações do `zshrc`.

6. Para manter suas configurações atualizadas, faça as alterações desejadas nos arquivos:

```
git add .
git commit -m "Descreva suas alterações aqui"
git push origin main
```

Isso enviará suas mudanças para o repositório clonado, que você pode acessar a partir de qualquer máquina.

### Mais Detalhes

Aqui estão alguns detalhes adicionais sobre as configurações contidas neste repositório:

- Para usar minhas fontes:

```
ln -s ~/dotfiles/fonts ~/.local/share/fonts
```
