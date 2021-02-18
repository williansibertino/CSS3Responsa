# CSS3Responsa framework

## **Framework básico de CSS3 grid layout responsivo.**
---
### Classes Responsivas para dispositivos ABAIXO DE 479px
```
@media only screen and (max-width: 479px) {
    .res--1{width:  8.33%;}
    .res--2{width: 16.66%;}
    .res--3{width: 25.00%;}
    .res--4{width: 33.33%;}
    .res--5{width: 41.66%;}
    .res--6{width: 50.00%;}
    .res--7{width: 58.33%;}    
    .res--8{width: 66.66%;}
    .res--9{width: 75.00%;}
    .res--10{width:83.33%;}
    .res--11{width:91.66%;}
    .res--12{width:100.0%;}
}
```
---
### Classes Responsivas para dispositivos ACIMA DE 480px
```
@media only screen and (min-width: 480px) {
    /* For Smartphones */
    .res--s1{width:  8.33%;}
    .res--s2{width: 16.66%;}
    .res--s3{width: 25.00%;}
    .res--s4{width: 33.33%;}
    .res--s5{width: 41.66%;}
    .res--s6{width: 50.00%;}
    .res--s7{width: 58.33%;}    
    .res--s8{width: 66.66%;}
    .res--s9{width: 75.00%;}
    .res--s10{width:83.33%;}
    .res--s11{width:91.66%;}
    .res--s12{width:100.0%;}
}
```
---
### Classes Responsivas para dispositivos ACIMA DE 768px
```
@media only screen and (min-width: 768px) {
    /* For Tablets */
    .res--t1{width:  8.33%;}
    .res--t2{width: 16.66%;}
    .res--t3{width: 25.00%;}
    .res--t4{width: 33.33%;}
    .res--t5{width: 41.66%;}
    .res--t6{width: 50.00%;}
    .res--t7{width: 58.33%;}    
    .res--t8{width: 66.66%;}
    .res--t9{width: 75.00%;}
    .res--t10{width:83.33%;}
    .res--t11{width:91.66%;}
    .res--t12{width:100.0%;}
}
```
---
### Classes Responsivas para dispositivos ACIMA DE 1024px
```
@media only screen and (min-width: 1024px) {
    /* For Desktops */
    .res--d1{width:  8.33%;}
    .res--d2{width: 16.66%;}
    .res--d3{width: 25.00%;}
    .res--d4{width: 33.33%;}
    .res--d5{width: 41.66%;}
    .res--d6{width: 50.00%;}
    .res--d7{width: 58.33%;}
    .res--d8{width: 66.66%;}
    .res--d9{width: 75.00%;}
    .res--d10{width:83.33%;}
    .res--d11{width:91.66%;}
    .res--d12{width:100.0%;}
}
```
### Container Classes
`.container--p` container com 80% de largura da width da página e margin auto. <br>
`.container--m` container com 90% de largura da width da página e margin auto. <br>
`.container--full` container com 100% da largura da width da página e margin auto.
### Hidden Classes
`.hidden--p` esconder elementos abaixo de 480px <br>
`.hidden--m` esconder elementos acima de 768px <br> 
`.hidden--d` esconder elementos acima de 1024px