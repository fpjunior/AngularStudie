# Primeiros passos com Angular e Bootstrap
 
 ## Criando um projeto Angular
  ` ng new angular-bootstrap-example `
 
 ## Instalando o bootstrap
 `npm install bootstrap` (instalando na ultima versão)

 - Configurando o  angular.json para responder com o bootstrap
"styles": [
  "node_modules/bootstrap/dist/css/bootstrap.min.css",
  "styles.scss"
]

 - @import '~bootstrap/dist/css/bootstrap.min.css'; (realizar a importação no styles.css)

 `npm install ngx-bootstrap --save `(substituindo o Jquery)
 `npm install bootstrap ngx-bootstrap` --save

 - configurando o app.module.ts

import { BsDropdownModule } from 'ngx-bootstrap/dropdown';
import { TooltipModule } from 'ngx-bootstrap/tooltip';
import { ModalModule } from 'ngx-bootstrap/modal';

@NgModule({
  imports: [
    BrowserModule,
    BsDropdownModule.forRoot(),
    TooltipModule.forRoot(),
    ModalModule.forRoot()
  ],
  // ...
})
export class AppBootstrapModule {}

 - npm install -g json-server (instalando o json server)

 - - -REFERÊNCIAS - - -
    Angular CLI
    Bootstrap 4
    ngx-bootstrap
    ng-bootstrap
    
    ## Links Uteis
    <a href="https://www.npmjs.com/package/json-server">Json Server </a><br>
     <a href="https://getbootstrap.com/">BootStrap </a><br>
      <a href="https://loiane.com//">Loiane </a><br>
     
     ## Useful links
    <a href="https://www.npmjs.com/package/json-server">Json Server </a><br>
     <a href="https://getbootstrap.com/">BootStrap </a><br>
      <a href="https://loiane.com//">Loiane </a><br>
      a href=" https://material.io/develop/web/docs/getting-started/">Loiane </a><br>
    
    

