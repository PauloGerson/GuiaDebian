# GuiaDebian - Um guia de instalação do debian
<p>&#32;&#32;<em>Alguns passos nesse guia poderá não ser destacado por algumas parte da intalação ser de fácil entedimento.</em><p>

 <br>
 <p>1 - Primeiramente: Você deve baixar um programa para virtualizar o seu sitema operacional. Usaremos aqui o virtual-box por exemplo </p>
 <a href="https://www.virtualbox.org/wiki/Downloads">Dowload Virtual-box</a>
 <br><br>

 <p>2 - Segundo: Baixe a iso do Debian</p>
  <a href="https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/">Download Debian10</a><br><br>

  <p>3 - Crie uma nova maquina virtual clicando em "Novo"</p>
  <img src="virtual1.png">
<br><br>
  
  <p>4 - Adicione o nome da sua maquina, como por exemplo "Debian10".</p>
  <img src="virtual2.png">
  <br><br>

   <p>5 - Coloque uma quantidade de memoria que você veja que não travara. Recomendo colocar de 4GB para frente, mas faça de acordo com o que você possui. </p>
  <img src="virtual3.png">
  <br><br>

   <p>6 - Deixe a opção de "Criar um novo disco..." e depois clique em "Criar"</p>
  <img src="virtual4.png">
  <br><br>

  <p>7 - Deixe a opção de "VDI" e depois clique em "proximo"</p>
  <img src="virtual5.png">
  <br><br>

  <p>8 - Deixe a opção de "Dinamicamente alocado" e depois clique em "proximo"</p>
  <img src="virtual6.png">
  <br><br>

  <p>9 - Defina o tamanho de memoria que ira ser alocada para sua maquina virtual. Requisito minimo recomendado seria de 10GB em diante. </p>
  <img src="virtual7.png">
  <br><br>

  <p>10 - Clique duas vezes sobre sua maquina virtual para iniciar. </p>
  <img src="virtual8.png">
  <br><br>

  <p>11 - Escolha a iso do debian que já esta baixada em seu computador. </p>
  <img src="virtual9.png">
  <br><br>

   <p>11.1 - Caso você não consiga adicionar sua iso atravez do passo "11", Vá nas configurações e tente adicionar pelo menu de armazenamento. </p>
  <img src="virtual9.1.png">
  <br><br>

  <p> 11.2 - Em Rede, marque a opção “Habilitar placa de Rede”, NAT do adaptador 1;
•Em adaptador 2, marque a opção “Habilitar Placa de Rede” e clica em OK.. </p>
  <img src="rede1.png">
  <br><br>

  <p>11.3 - Após adicionando, ira aparecer esse menu em sua tela.  A partir dai você ira escolher o tipo de instalação. No nosso caso iremos instalar o com interface grafica, ou seja a "Graphical Debian".</p>
  <img src="2021-08-24 19_55_01-Window.png">
  <br><br>

  <p>12 - Os opções a seguir serão todas relacionadas a idiomas, escolha de acordo com sua preferência. No meu caso, escolherei todas Português-Brasil.</p>
  <img src="virtual10.png">
  <br><br>

   <p>13 - Se a opção abaixo não estiver selecionada você deve voltar nas configurações
de sua rede e verificar se a opção NAT está ativada;</p>
  <img src="rede2.png">
  <br><br>

  <p>13.1 - Escolha um nome qualquer para sua maquina. Caso você não tenha conhecimento sobre o que fazer na tela seguinte e não quiser também colocar uma senha, você poderá pular, que é o que eu fiz.</p>
  <img src="virtual11.png">
  <br><br>

  

  <p>14 - Escolha um nome de usuario</p>
  <img src="virtual12.png">
  <br><br>

   <p>15 - Use a opção de "Usar o disco inteiro e configurar LVM", para uma instalação mais simplificada.</p>
  <img src="virtual13.png">
  <br><br>

   <p>16 - Escolha a opção de "Partição /home separada", por se tratar de um hambiente de teste.</p>
  <img src="virtual21.png">
  <br><br>

  <p>17 - Aperte em continuar</p>
  <img src="memoria1.png">
  <br><br>

  <p>18 - Sera apresentado uma tela para fazer algumas configurações de particionamento. Clique na opção "Sim" e "Finalizar o particionamento...".</p>
  <img src="memoria2.png">
  <br><br>

  <p>19 - Ler outro CD ou DVD? Não;</p>
  <img src="pacote2.png">
  <br><br>

  <p>20 - Gerenciador de pacotes: Brasil, Continuar;</p>
  <img src="pacote3.png">
  <br><br>


  <p>21 - Confirme marcando a opção "debian.deb.org ou deb.debian.org"</p>
  <img src="virtual18.png">
  <br><br>

<p>22 - Informações sobre proxy HTTP: Deixa em branco, Continuar;</p> <br><br>
<p>23 - Caso o gerenciador de pacotes apresente um erro, escolha a opção: continuar
sem um espelho de rede, Continuar;</p> <br><br>
<p>24- Participar do concurso de utilização de pacotes? Não, Continuar;</p> <br><br>

<p>25 - Deixe marcado a opção: utilitário de sistema padrão, Continuar;</p>
<img src="software1.png">  <br><br>

<p>26 - Instalar o carregador de inicialização GRUB: Sim, Continuar;</p><br><br>

<p>27 - Seleciona o HD principal: /dev/sda ..., Continuar;</p>
<img src="software2.png">  <br><br>

<p>28 - Finaliza a instalação, Continuar.</p>



  
 

