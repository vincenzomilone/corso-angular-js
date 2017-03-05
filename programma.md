# Lo sviluppo di applicaizoni web client: AngularJs

## Perché Angular

Breve introduzione allo sviluppo di applicativi web e i vantaggi dell'uso di AngularJs.

Note:
* perché client-side?
* perché AngularJs e non jQuery?

## AngularJs

Inclusi esempi d'uso di base dei vari punti.

* Le direttive fondamentali
    - ng-app
    - ng-controller (https://codepen.io/_vik/pen/OpMLqx)
    - ng-bind
    - ng-model (https://codepen.io/_vik/pen/dvGyGO)
    - ng-click (https://codepen.io/_vik/pen/Vpewjp)
    - ng-repeat (https://codepen.io/_vik/pen/YZwzYr)
    - ng-change ???
    - ng-show e ng-hide (https://codepen.io/_vik/pen/zZrYmK)
    - ng-if NO ESEMPIO
    - ng-switch (https://codepen.io/_vik/pen/jBWEGq)
    - ng-required (https://codepen.io/_vik/pen/MpeZEW)
    - ng-disabled (https://codepen.io/_vik/pen/LWZMvO)
    - ng-submit (https://codepen.io/_vik/pen/mWEaZz)
    - ng-options (https://codepen.io/_vik/pen/MpeLbJ)
    - ng-change 
    - ng-class
    - ng-style    
* La struttura di un'applicazione AngularJs
    - module
    - controller
    - service e factory
    - directive
    - constant
    - value
* $scope e $inject
* $watch
* eventi ($emit, $broadcast, $on)
* $apply
* Perché **non** usare lo $scope
* $scope, $element, e la (terribile e potentissima) combinazione AngularJs/jQuery
* $filter
* Chiamate AJAX, $http e *promise*
* Http Interceptor

## L'universo delle Web application

* Less e Sass
* Git
* Package e gestione dei pacchetti tramite npm
    - gestione versione node/npm con nvm
* Bower e gestione componenti frontend
* Le componenti bower indispensabili:
    - lodash
    - moment.js
    - angular-sanitize, angular-touch e angular-cookies
    - angular-translate
    - *accenno a* bootstrap e angular-bootstrap   

## UI Router

* stati
* views
* resolve

## Struttura dei sorgenti

Come *mettere insieme* tutti i pezzi tenendo in ordine il codice.

Integrazione del framework Bootstrap nel frontend.

## Prima applicazione

Un'esempio di applicazione che mostra un elenco di dati ricevuti dal server.

## Seconda applicazione

Vista "modifica dati" e gestione del routing con ui-router (stati, sotto-stati e resolve)

## Terza applicazione

Uso di filtri, form di ricerca e modali. Sincronizzazione con il server.

## Quarta applicazione

Gestione internalizzazione (angular-translate e moment.js).

## Argomenti avanzati

* prepararsi ad Angular 2 con le componenti Angular 1.5
* material design
* sicurezza e cookie
* problemi SEO per applicazioni pubbliche

Vincenzo Milone
