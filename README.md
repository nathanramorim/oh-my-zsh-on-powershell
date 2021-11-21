# oh-my-zsh no powershell

![s](https://i.ibb.co/Qr8dsyD/custom-powershell-git.png)

Sabiam que tem jeito de personalizar o [PowerShell](https://docs.microsoft.com/pt-br/powershell/) similiar a quando utilizamos o oh-my-zsh? Eu nem sabia.

Eu curto bastante uma interface amigável de terminal e senti muita falta de trazer essa experiência para o ambiente [Windows](https://www.microsoft.com/pt-br/windows/) (há... já estou utilizando também a versão do Windows 11 que inclusive estou gostando também) 

Andei pesquisando e cheguei nesse tutorial, quer também estilizar seu PowerShell?

Para começarmos a estilizar nosso powershell será necessário alguns módulos:

então, abra o [PowerShell](https://docs.microsoft.com/pt-br/powershell/), estou utilizando a versão `7.1`.

Execute os comandos abaixo:

```powershell
Install-Module posh-git -Scope CurrentUser
```

```powershell
Install-Module oh-my-posh -Scope CurrentUser
```

```powershell
Install-Module -Name Terminal-Icons -Repository PSGallery
```

```powershell
nodepad $PROFILE
```

Insira os comandos abaixo dentro do bloco de notas:

> Import-Module posh-git
> 
> Import-Module oh-my-posh
> 
> Import-Module -Name Terminal-Icons
> 
> Set-PoshPrompt -Theme bubblesline



Ready! Agora é só abrir o terminal e ser feliz!! :D



Eu utilizei o tema **bubblesline**, mas vocês podem visualizar outros na documentação do [Oh My Posh](https://ohmyposh.dev/docs/themes).



Caso tenham problema com a visualização de icones,  instalei a font [MesloLGM NF Regular](https://github.com/nathanramorim/oh-my-zsh-on-powershell/blob/master/Meslo%20LG%20M%20Bold%20Nerd%20Font%20Complete%20Mono%20Windows%20Compatible.ttf) que está disponível no repositório.
