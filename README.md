<h1> Aprendendo a usar esta ferramenta, te faço um tutos rápido de como mexer nessa bagaça de forma mais segura: </h1>
<h2>Configurações Iniciais: Extensões, Atualizações...</h2>
<ul>
<li>Esteja com sua conta do github usada neste repositório conectada ao VStudio Code</li>
<li>Instale as extensões do GitHub como:</li>

  <br> - Github Codespaces
  <br> - Github Repositories
  <br> - Remote Repositories
  <br> - Live Share

<li>(E todas as extensões de sua preferência e necessárias as linguagens utilizadas) </li>
<li>Agora será necessário abrir remotamente a 'árvore principal', eliminando a necessidade de clonar o repositório toda vez no seu computador:</li>
<li>Para isso acesse o explorador de arquivos do VStudio e clique na opção:</li>
<code> Open Remote Repository // "Abrir repositório remoto" </code>
<li>Ou, aperte as teclas <code> Ctrl + Shift + P </code></li>
<li>E em seguida, digite na barra do navegador:</li>
<code> >open remote repository </code>
<li>A partir disso, ficará intuitivo o que deve ser feito: </li>

  <br> - Selecione a opção <code>abrir repositório do github</code>
  <br> - Procure pelo nome do arquivo como <code>zarquells/JavaScript-Started</code>

<li>Com o procedimento correto, você deverá ter acesso ao diretório do Github normalmente pelo VStudio. Porém isso não significa que as alterações serão sincronizadas em tempo real.</li>
</ul>
<pre>
      ,_     _,                    /\ ___ /\
      |\\___//|                   (  o   o  ) 
      |=6   6=|                    \  ><   /
      \=._Y_.=/                    /       \  
       )  `  (    ,               /         \        
      /       \  ((              |           |      
      |       |   ))             \           /     
     /| |   | |\_//               \         /    
     \| |._.| |/-`                 |       |    
      '"'   '"'                    ///  ///  
</pre>

<h2>Palavras Complicadas: Push, Commit, Branch...</h2>
<ul>
  <li>É arriscado demais fazer alterações diretamente no código principal, pois quando se trabalha com mais colaboradores o risco de surgir bugs é grande nas commitações</li>
  <li>Para isso, iremos criar um <code>branch // "galho" </code> para cada colaborador começando com você</li>
  <li>Clique no <code>main</code> localizado no canto esquerdo inferior </li>
  <li>Ou, aperte as teclas <code> Ctrl + Shift + P </code></li>
  <li>E em seguida, digite na barra do navegador:</li>
  <code> >branch </code>
  <li>A partir disso, ficará intuitivo o que deve ser feito: </li>

  <br> - Nomeie um novo galho com o nome do colaborador como, <code>Erica</code>
  <br> - Relacione ao código principal <code>main</code>
  <br> - Abra numa nova janela 

  <li>Agora você está livre para fazer o que quiser desde que tenha cuidado com as alterações onde não era para você estar codando. </li>
  <li>É recomendado como boas práticas sempre informar onde deseja fazer suas alterações e no que isso pode impactar</li>
  <li>Para salvar suas alterações ou melhor, commitar na branch do Github: </li>
  <li>Acesse a aba localizada na coluna da direita chamada <code>Controle do Código-Fonte</code> 
  <li>Ou, aperte as teclas <code> Ctrl + Shift + P </code></li>
  <li>E em seguida, digite na barra do navegador:</li>
  <code> >commit </code>
  <li>Ou, aperte as teclas <code> Ctrl + Shift + G </code></li>
  <li>A partir disso, ficará intuitivo o que deve ser feito: </li>
    <br> - (opcional) Escreva uma nota dizendo quais são suas últimas alterações, a data em que foi feito e no que pode impactar 
    <br> - Verifique que arquivos serão afetados e em seguida,
    <br> - <code>Commit and Push</code>
</ul>

  <h4>Tcharam! Suas alterações foram salvas, pode fechar o branch no VStudio com segurança</h4>

  <h2>No Github...</h2>
  <ul>
  <li>Acesse novamente o link do repositório e abra um chamado p aprovar as alterações feitas na branch</li>
  (https://github.com/zarquells/JavaScript-Started/assets/116844017/2fa52e55-4443-4410-ad2a-58ea16cbd806)
  <li>Sempre abra o chamado já que estas alterações só existem por enquanto, no branch</li>
  <li>Se ainda for modificar o seu código (e não for envolver outros colaboradores), **não abra o chamado ainda!**</li>
  <li>Somente com o seu código prestes a nascer, que você solicita ao administrador que ele commite a branch dentro do código principal</li>
  <li>Agora você pode excluir com confiança a branch criada!</li>
  </ul>

  <h2>Adendos...</h2>
  <ul>
  <li>Tome cuidado com os tipos de acesso que concede aos colaboradores, jamais os permita deletar o repositório ou até mesmo excluir algum arquivo principal</li>
  <li>Ao commitar uma branch em específico, preste atenção nas etapas e evite que antecipadamente a commite no código principal</li>
  <li>Para acessar novamente algum branch existente, siga as mesmas etapas porém, pesquise o nome da branch quando acessar o repositório:</li>
    <br> - Pesquise por <code> >Branch </code> e ache a opção escrita <code> Switch Branch </code>
  <br>
(as branchs são feitas para serem temporárias, e funcionam quase como um respawn garantindo a segurança do código)
(deixe aberto sempre a página referente ao repositorio no GitHub, faça isso sempre que for codar)
(quando o assunto é segurança, sempre peque pelo excesso ::))
</ul>
