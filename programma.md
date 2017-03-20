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
    - ng-if
    - ng-switch (https://codepen.io/_vik/pen/jBWEGq)
    - ng-required (https://codepen.io/_vik/pen/MpeZEW)
    - ng-disabled (https://codepen.io/_vik/pen/LWZMvO)
    - ng-submit (https://codepen.io/_vik/pen/mWEaZz)
    - ng-options (https://codepen.io/_vik/pen/MpeLbJ)
    - ng-change
    - ng-class (https://codepen.io/_vik/pen/GWmYzy)
    - ng-style (https://codepen.io/_vik/pen/jBmQbo)
* La struttura di un'applicazione AngularJs
    - module
    - controller
    - config
    - service e factory
    - directive
    - constant
* $inject
* $scope e $watch
* eventi ($emit, $broadcast, $on)
* Perché **non** usare lo $scope (https://codepen.io/_vik/pen/NpgeKK)
* $element (https://codepen.io/_vik/pen/wJeRgv)
* $apply LO GUARDEREI DOPO
* $filter (https://codepen.io/_vik/pen/YZQdJb)
* Chiamate AJAX, $http e *promise*

## L'universo delle Web application

* Less e Sass
* Git
* Package e gestione dei pacchetti tramite npm
    - gestione versione node/npm con nvm
* Bower e gestione componenti frontend
* Le componenti bower indispensabili:
    - lodash
    - moment.js
    - angular-sanitize, angular-animate e angular-touch
    - angular-translate LO INTRODURREI PIÙ AVANTI
    - *accenno a* bootstrap e angular-bootstrap   

## UI Router

Lo sviluppo secondo il paradigma di *routing*.

UI-Router:
* stati
* views
* resolve

[Applicazione di esempio](https://github.com/vincenzomilone/corso-angular-01)

## Struttura dei sorgenti

Come *mettere insieme* tutti i pezzi tenendo in ordine il codice.

Integrazione del framework Bootstrap nel frontend.

## Applicazioni di esempio

|Applicazione|Scopo|Link|
|------------|-----|----|
|I applicazione|Mostrare l'uso di UI-Router <small>(già vista in precedenza)</small>|[Link](https://github.com/vincenzomilone/corso-angular-01)
|II applicazione|Applicazione che recupera una lista di utenti dal server e la mostra|[Link](https://github.com/vincenzomilone/corso-angular-02)
|III applicazione|Modifica di un utente. Validare una form.|[Link](https://github.com/vincenzomilone/corso-angular-03)
|IV applicazione|Internalizzazione dell'app|[Link](https://github.com/vincenzomilone/corso-angular-04)

## A fine corso...

* html5mode
* problemi SEO per applicazioni pubbliche                  
* $scope.$apply()
* prepararsi ad Angular 2 con le componenti Angular
* material design

Vincenzo Milone
