# Instalação da Máquina Virtual
<p align="justify">

Primeiramente, para a instalação do [**MINIX 3**](https://www.minix3.org/) recomenda-se o uso de uma máquina virtual. Como máquina virtual usaremos o [**VMware Workstation Player**](https://www.vmware.com/br/products/workstation-player/workstation-player-evaluation.html), para fazer seu download basta clicar em seu nome em azul, bastando escolher conforme sua versão de sistema operacional.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723482-c6d02f00-3194-44f6-af7d-a3d917b7c4e0.png" width="800px"/>

</div>

<p align="justify">

Em seguida prosseguiremos com a instalação do [**VMware Workstation Player**](https://www.vmware.com/br/products/workstation-player/workstation-player-evaluation.html), para isso, basta abrir o executável e seguir os passos para a instalação.

Ao fim da instalação, partiremos para fazer o download da ISO do [**MINIX 3**](https://wiki.minix3.org/doku.php?id=www:download:start), nesse caso, nos usaremos a [**Versão 3.3.0**](http://download.minix3.org/iso/minix_R3.3.0-588a35b.iso.bz2).

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723549-d4a84a1f-3c72-42e3-aea3-c5108b3d786e.png" width="800px"/>

</div>

<p align="justify">

Após o download da ISO do [**MINIX 3**](https://www.minix3.org/) na [**Versão 3.3.0**](http://download.minix3.org/iso/minix_R3.3.0-588a35b.iso.bz2), voltaremos ao [**VMware Workstation Player**](https://www.vmware.com/br/products/workstation-player/workstation-player-evaluation.html) e criareamos nossa máquina virtual clicando no botão **"Create a New Virtual Machine"**.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723599-93a60eec-76cc-467e-8236-0a759cb20e51.png" width="800px"/>

</div>

<p align="justify">

Após a escolha dessa opção abrirá uma caixa pedindo para escolher a ISO que iremos instalar na máquina virtual que estamos tentando criar, então selecionamos a opção **"Browse"** e encontramos o local onde o download da ISO do [**MINIX 3**](https://www.minix3.org/) na [**Versão 3.3.0**](http://download.minix3.org/iso/minix_R3.3.0-588a35b.iso.bz2) baixada.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723744-8ca89d2b-d7b7-420d-ab56-852b1ec75876.png" width="800px"/>

</div>

<p align="justify">

Após a seleção da ISO, passa a escolha do nome da máquina virtual que será criada, esse nome fica a cargo do usuário. Em seguida, passaremos para a alocação do espaço em disco que será usado pela máquina virtual, seguiremos o padrão recomendado e deixaremos 10 GB de espaço em disco, e por fim, finalizamos a criação de nossa máquina virtual, que logo em seguida será aberta e iniciaremos, enfim a instalação do [**MINIX 3**](https://www.minix3.org/).

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723682-c0ca79fa-91f6-4a31-b49e-0f64085bf367.png" width="800px"/>

</div>

# Instalação do MINIX 3 na Máquina Virtual

<p align="justify">

Ao iniciarmos a máquina virtual criada começarão os passos para instalação do [**MINIX 3**](https://www.minix3.org/). Assim, na tela inicial escolheremos a opção **"1. Regular MINIX 3"**, em seguida será pedido um login, basta digitar **"root"**.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194723929-319c82e3-c568-4da6-825d-e1e210fb3052.png" width="800px"/>

</div>

<p align="justify">

Em seguida digitaremos **"setup"** para começar a instalação e em seguida se abrirá um MENU com 4 opções, porém só apertaremos **ENTER** para continuar com a instalação, então escolheremos o idioma que será usado para o teclado.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194724306-eb8d33d6-bb13-4151-8b70-98d1e3321e1f.png" width="800px"/>

</div>

Após isso, confirmamos com um **"ENTER"** para prosseguir automaticamente coma instalação e em seguida escolher o número de identificação do disco que será usado, nesse caso o disco **"0"**.

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194724357-89eeb947-d608-48e3-9eef-8accfbee39de.png" width="800px"/>

</div>

<p align="justify">

Em seguida, confirmamos com **"yes"** para prosseguir na instalação, escolhemos o tamanho usado pelo [**MINIX 3**](https://www.minix3.org/), recomendado de **"1914"**, e por fim confirmamos o tamanho escolhido com um **"Y"**.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194724414-6f7e79bb-845c-461b-8c39-73d6297f189c.png" width="800px"/>

</div>

Após isso, confirmamos o tamanho do bloco de sistema com **"4"** e são carregados alguns arquivos de instalação.

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194724439-ef7dcdd7-3e5f-4844-828b-2e4b7d07c45b.png" width="800px"/>

</div>

<p align="justify">

Por fim, escolhemos o modelo de interface de rede, conforme o hardware do usuário, a ser usado pelo [**MINIX 3**](https://www.minix3.org/) e definimos a configuração automática na opção **"1. Automatically using DHCP"** e então o sistema estará totalmente instalado, precisaremos apenas reiniciar o sistema dando um **"reboot"** e ele estará pronto para uso.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194724475-be16d9f8-ac90-414e-b6f5-9cbb4b559249.png" width="800px"/>

</div>

# Primeiro "Hello World" no MINIX 3

<p align="justify">

Para criarmos nosso primeiro **"Hello World"** em C no MINIX, primeiramente iniciaremos nossa máquina virtual e precisaremos logar no sistema como **"root"**.Em seguida criaremos um arquivo com o comando "**touch + (nome do arquivo).c**", e depois damos o comando **"ls"** para verificar se o arquivo foi realmente criado. Por fim, após confirmação de que o arquivo foi criado inserimos o comando **"mined + (nome do arquivo)"** para podermos abri-lo e edita-lo.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194725976-3384c2d3-8ecd-403c-8881-58d2a2ecaba0.png" width="800px"/>

</div>

<p align="justify">

Já dentro do arquivo digitamos nosso código em **C** para criação do **"Hello World"**. Logo em seguida, utilizamos o atalho **"CTRL + W"** para salvar o que digitamos e então **"CTRL + S"** para voltar ao terminal.

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194726247-45a37bb9-8a3f-4516-a554-8b7fd61d626d.png" width="800px"/>

</div>

<p align="justify">

De volta ao terminal, para compilar o código criado digitamos **"sh + (nome do arquivo)"** e se tudo estiver correto aparecerá logo abaixo o seu primeiro **"Hello World"** feito em **C** no [**MINIX 3**](https://www.minix3.org/).

</p>

<div align="center">

<img src="https://user-images.githubusercontent.com/84411392/194726225-fc4dfef8-b656-476c-a7b9-12541b364130.png" width="800px"/>

</div>
