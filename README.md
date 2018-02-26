# Web-Science

Resumo:
    
    Faz a raspagem de algumas informações referente ao tema de busca do site e em seguida analisa esses dados.

----

O programa está dividido em três etapas:
<ul>
  <li> Obter os links de todos os artigos referente ao tema de busca </li>
  <li> Percorrer por todos os links e raspar algumas informações em cada link </li>
  <li> Fazer uma analise com os dados e obter algumas informações </li>
</ul>

----

## Raspando os links:

O programa ***get_links*** acessa o site e insere o termo de busca (váriavel busc). Em seguida obtém todas as url's dos artigos  referente ao termo de busca e salva em um arquivo com nome *link.csv*.

----

## Raspando algumas informações

O programa ***get_information*** vai percorrer todos os link's salvo do arquivo *link.csv* e raspas as seguintes informações:

<ul>
    <li>Titulo</li>
    <li>Autores</li>
    <li>Nome da revista</li>
    <li>Ano da publicação</li>
    <li>Número de referências</li>
    <li>Número de citações</li>
    <li>Resumo</li>
</ul>

Em seguida vai salvar os dados no arquivo *information.csv*

----

## Analisando os dados coletados

O programa ***data_analysis*** vai ler o arquivo *information.csv* e obter algumas informações referente ao tema do busca, como:
<ul>
    <li> O número de publicações ao ano </li>
    <li> O número total de autores que já publicaram sobre o tema pesquisado </li>
    <li> O número total revistas e/ou conferências que já publicaram sobre o tema pesquisado </li>
    <li> Os 10 autores que mais publicaram sobre o tema pesquisado </li>
    <li> As 10 mais revistas que publicaram o tema pesquisado </li>
    <li> Os artigos mais citados </li>
</ul>

----

## Bibliotecas utilizadas
<ul>
    <li> Selenium </li>
    <li> Requests </li>
    <li> BeatifulSoup </li>
    <li> Pandas </li>
    <li> Matplotlib </li>
    <li> Seaborn </li>
</ul>

---
