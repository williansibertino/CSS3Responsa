# CSS3Responsa framework

## **Framework básico de CSS3 grid layout responsivo.**
As classes de grid de colunas são iniciadas com o tipo específico da largura da resolução entre elas XL, SM, MD e LG.<br>
As classe de colunas vazias são iniciadas com o (off-) seguido da abreviatura do tamanho da resolução.<br>
<br>
## Classes Responsivas para device extra small
```
@media only screen and (max-width: 478px) {
    /* Device Extra Small */
    .xs--1{width:  8.33%;} 
    .xs--2{width: 16.66%;} 
    .xs--3{width: 25.00%;} 
    .xs--4{width: 33.33%;} 
    .xs--5{width: 41.66%;}
    .xs--6{width: 50.00%;}
    .xs--7{width: 58.33%;}
    .xs--8{width: 66.33%;}
    .xs--9{width: 75.00%;}
    .xs--10{width:83.33%;}
    .xs--11{width:91.66%;}
    .xs--12{width:100.0%;}
    /* colunas vazias Extra Small */
    .off-xs-1{margin-left:  8.33%;}
    .off-xs-2{margin-left: 16.66%;}
    .off-xs-3{margin-left: 25.00%;}
    .off-xs-4{margin-left: 33.33%;}
    .off-xs-5{margin-left: 41.66%;}
    .off-xs-6{margin-left: 50.00%;}
    .off-xs-7{margin-left: 58.33%;}
    .off-xs-8{margin-left: 66.66%;}
    .off-xs-9{margin-left: 75.00%;}
    .off-xs-10{margin-left:83.33%;}
    .off-xs-11{margin-left:91.66%;}
    .off-xs-12{margin-left:100.0%;}
}
```
<br>

## Classes Responsivas para devices small
```
@media only screen and (min-width: 480px) {
    /* Device Small */
    .sm--1{width:  8.33%;}
    .sm--2{width: 16.66%;}
    .sm--3{width: 25.00%;}
    .sm--4{width: 33.33%;}
    .sm--5{width: 41.66%;}
    .sm--6{width: 50.00%;}
    .sm--7{width: 58.33%;}    
    .sm--8{width: 66.66%;}
    .sm--9{width: 75.00%;}
    .sm--10{width:83.33%;}
    .sm--11{width:91.66%;}
    .sm--12{width:100.0%;}
    /* colunas vazias Small */
    .off-sm-1{margin-left:  8.33%;}
    .off-sm-2{margin-left: 16.66%;}
    .off-sm-3{margin-left: 25.00%;}
    .off-sm-4{margin-left: 33.33%;}
    .off-sm-5{margin-left: 41.66%;}
    .off-sm-6{margin-left: 50.00%;}
    .off-sm-7{margin-left: 58.33%;}
    .off-sm-8{margin-left: 66.66%;}
    .off-sm-9{margin-left: 75.00%;}
    .off-sm-10{margin-left:83.33%;}
    .off-sm-11{margin-left:91.66%;}
    .off-sm-12{margin-left:100.0%;}
}
```
<br>

## Classes Responsivas para devices medium
```
@media only screen and (min-width: 768px) {
    /* Device Medium */
    .md--1{width:  8.33%;}
    .md--2{width: 16.66%;}
    .md--3{width: 25.00%;}
    .md--4{width: 33.33%;}
    .md--5{width: 41.66%;}
    .md--6{width: 50.00%;}
    .md--7{width: 58.33%;}    
    .md--8{width: 66.66%;}
    .md--9{width: 75.00%;}
    .md--10{width:83.33%;}
    .md--11{width:91.66%;}
    .md--12{width:100.0%;}
    /* colunas vazias Medium */
    .off-md-1{margin-left:  8.33%;}
    .off-md-2{margin-left: 16.66%;}
    .off-md-3{margin-left: 25.00%;}
    .off-md-4{margin-left: 33.33%;}
    .off-md-5{margin-left: 41.66%;}
    .off-md-6{margin-left: 50.00%;}
    .off-md-7{margin-left: 58.33%;}
    .off-md-8{margin-left: 66.66%;}
    .off-md-9{margin-left: 75.00%;}
    .off-md-10{margin-left:83.33%;}
    .off-md-11{margin-left:91.66%;}
    .off-md-12{margin-left:100.0%;}
}
```
<br>

## Classes Responsivas para devices larges
```
@media only screen and (min-width: 1024px) {
    /* Device Large */
    .lg--1{width:  8.33%;}
    .lg--2{width: 16.66%;}
    .lg--3{width: 25.00%;}
    .lg--4{width: 33.33%;}
    .lg--5{width: 41.66%;}
    .lg--6{width: 50.00%;}
    .lg--7{width: 58.33%;}
    .lg--8{width: 66.66%;}
    .lg--9{width: 75.00%;}
    .lg--10{width:83.33%;}
    .lg--11{width:91.66%;}
    .lg--12{width:100.0%;}
    /* Colunas vazias Large */
    .off-lg-1{margin-left:  8.33%;}
    .off-lg-2{margin-left: 16.66%;}
    .off-lg-3{margin-left: 25.00%;}
    .off-lg-4{margin-left: 33.33%;}
    .off-lg-5{margin-left: 41.66%;}
    .off-lg-6{margin-left: 50.00%;}
    .off-lg-7{margin-left: 58.33%;}
    .off-lg-8{margin-left: 66.66%;}
    .off-lg-9{margin-left: 75.00%;}
    .off-lg-10{margin-left:83.33%;}
    .off-lg-11{margin-left:91.66%;}
    .off-lg-12{margin-left:100.0%;}
}
```
## Container Classes
`.container--small` container com 80% de largura da width da página e margin auto. <br>
`.container--medium` container com 90% de largura da width da página e margin auto. <br>
`.container--full` container com 100% da largura da width da página e margin auto.
## Hidden Classes
`.xs--hidden` esconder elementos abaixo de 480px <br>
`.sm--hidden` esconder elementos acima de 480px <br>
`.md--hidden` esconder elementos acima de 768px <br> 
`.lg--hidden` esconder elementos acima de 1024px