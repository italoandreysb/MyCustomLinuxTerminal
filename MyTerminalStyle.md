### Instalado ZSH 

1. Instalar zsh

```# sudo apt-get install zsh```

2. Instalar o oh-my-zsh via wget:

```sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"```

3. Edite o arquivo de configuração abaixo: (home/<user>/)

```sudo vim ~/.zshrc```
  
4. Na linha **"ZSH_THEME"** selecione seu tema, ex:

ZSH_THEME="fino"

[Link com alguns temas](https://github.com/ohmyzsh/ohmyzsh/wiki/themes)

Referências:
  
  - [Medium.com](https://medium.com/@rgdev/como-instalar-oh-my-zsh-c0f96218fd90#:~:text=Para%20mudar%20de%20tema%20%C3%A9,robbyrussell%22%20pelo%20tema%20que%20preferir.&text=%C3%89%20interessante%20que%20no%20terminal,hor%C3%A1rio%20(nesse%20tema%20espec%C3%ADfico).)

### Como remover o ZSH:

Antes de remover o ZSH torne o bash como padrão:
	
```$ chsh -s /bin/bash```

Removendo o Zsh:
  
```# sudo apt-get --purge remove zsh```

[Fonte](https://askubuntu.com/questions/958120/remove-zsh-from-ubuntu-16-04)
