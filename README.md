# designkit-utilities
1.0.6

Sass module containing utility classes to help design apps.

## Install
```
npm i --save designkit-utilities
```

## CSS

```css
/*
//
// Designkit-Utilities
// --------------------------------------------------
*/
.flex {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.inline-flex {
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
}

.flex-none {
  -webkit-box-flex: 0;
      -ms-flex: none;
          flex: none;
}

.flex-column {
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
}

.flex-row {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
      -ms-flex-direction: row;
          flex-direction: row;
}

.flex-wrap {
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
}

.flex-nowrap {
  -ms-flex-wrap: nowrap;
      flex-wrap: nowrap;
}

.flex-wrap-reverse {
  -ms-flex-wrap: wrap-reverse;
      flex-wrap: wrap-reverse;
}

.flex-column-reverse {
  -webkit-box-orient: vertical;
  -webkit-box-direction: reverse;
      -ms-flex-direction: column-reverse;
          flex-direction: column-reverse;
}

.flex-row-reverse {
  -webkit-box-orient: horizontal;
  -webkit-box-direction: reverse;
      -ms-flex-direction: row-reverse;
          flex-direction: row-reverse;
}

.items-start {
  -webkit-box-align: start;
      -ms-flex-align: start;
          align-items: flex-start;
}

.items-end {
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
}

.items-center {
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.items-baseline {
  -webkit-box-align: baseline;
      -ms-flex-align: baseline;
          align-items: baseline;
}

.items-stretch {
  -webkit-box-align: stretch;
      -ms-flex-align: stretch;
          align-items: stretch;
}

.self-start {
  -ms-flex-item-align: start;
      align-self: flex-start;
}

.self-end {
  -ms-flex-item-align: end;
      align-self: flex-end;
}

.self-center {
  -ms-flex-item-align: center;
      -ms-grid-row-align: center;
      align-self: center;
}

.self-baseline {
  -ms-flex-item-align: baseline;
      align-self: baseline;
}

.self-stretch {
  -ms-flex-item-align: stretch;
      -ms-grid-row-align: stretch;
      align-self: stretch;
}

.justify-start {
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
}

.justify-end {
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
}

.justify-center {
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}

.justify-between {
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
}

.justify-around {
  -ms-flex-pack: distribute;
      justify-content: space-around;
}

.content-start {
  -ms-flex-line-pack: start;
      align-content: flex-start;
}

.content-end {
  -ms-flex-line-pack: end;
      align-content: flex-end;
}

.content-center {
  -ms-flex-line-pack: center;
      align-content: center;
}

.content-between {
  -ms-flex-line-pack: justify;
      align-content: space-between;
}

.content-around {
  -ms-flex-line-pack: distribute;
      align-content: space-around;
}

.content-stretch {
  -ms-flex-line-pack: stretch;
      align-content: stretch;
}

.dn {
  display: none;
}

.di {
  display: inline;
}

.db {
  display: block;
}

.dib {
  display: inline-block;
}

.dif {
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
}

.dig {
  display: -ms-inline-grid;
  display: inline-grid;
}

.dit {
  display: inline-table;
}

.dt {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.dtr {
  display: table-row;
}

.dtc {
  display: table-cell;
}

.dtcol {
  display: table-column;
}

.dtcolg {
  display: table-column-group;
}

.center {
  margin-right: auto;
  margin-left: auto;
}

.center-block {
  display: block;
  margin-right: auto;
  margin-left: auto;
}

.cf::after, .clearfix::after {
  clear: both;
  content: "";
  display: table;
}

.fl, .pull-left {
  float: left;
  display: inline;
}

.fr, .pull-right {
  float: right;
  display: inline;
}

.fn {
  float: none;
}

.pa0 {
  padding: 0;
}

.pa1 {
  padding: .25rem;
}

.pa2 {
  padding: .5rem;
}

.pa3 {
  padding: 1rem;
}

.pa4 {
  padding: 2rem;
}

.pa5 {
  padding: 4rem;
}

.pa6 {
  padding: 8rem;
}

.pa7 {
  padding: 16rem;
}

.pl0 {
  padding-left: 0;
}

.pl1 {
  padding-left: .25rem;
}

.pl2 {
  padding-left: .5rem;
}

.pl3 {
  padding-left: 1rem;
}

.pl4 {
  padding-left: 2rem;
}

.pl5 {
  padding-left: 4rem;
}

.pl6 {
  padding-left: 8rem;
}

.pl7 {
  padding-left: 16rem;
}

.pr0 {
  padding-right: 0;
}

.pr1 {
  padding-right: .25rem;
}

.pr2 {
  padding-right: .5rem;
}

.pr3 {
  padding-right: 1rem;
}

.pr4 {
  padding-right: 2rem;
}

.pr5 {
  padding-right: 4rem;
}

.pr6 {
  padding-right: 8rem;
}

.pr7 {
  padding-right: 16rem;
}

.pb0 {
  padding-bottom: 0;
}

.pb1 {
  padding-bottom: .25rem;
}

.pb2 {
  padding-bottom: .5rem;
}

.pb3 {
  padding-bottom: 1rem;
}

.pb4 {
  padding-bottom: 2rem;
}

.pb5 {
  padding-bottom: 4rem;
}

.pb6 {
  padding-bottom: 8rem;
}

.pb7 {
  padding-bottom: 16rem;
}

.pt0 {
  padding-top: 0;
}

.pt1 {
  padding-top: .25rem;
}

.pt2 {
  padding-top: .5rem;
}

.pt3 {
  padding-top: 1rem;
}

.pt4 {
  padding-top: 2rem;
}

.pt5 {
  padding-top: 4rem;
}

.pt6 {
  padding-top: 8rem;
}

.pt7 {
  padding-top: 16rem;
}

.pv0 {
  padding-top: 0;
  padding-bottom: 0;
}

.pv1 {
  padding-top: .25rem;
  padding-bottom: .25rem;
}

.pv2 {
  padding-top: .5rem;
  padding-bottom: .5rem;
}

.pv3 {
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.pv4 {
  padding-top: 2rem;
  padding-bottom: 2rem;
}

.pv5 {
  padding-top: 4rem;
  padding-bottom: 4rem;
}

.pv6 {
  padding-top: 8rem;
  padding-bottom: 8rem;
}

.pv7 {
  padding-top: 16rem;
  padding-bottom: 16rem;
}

.ph0 {
  padding-left: 0;
  padding-right: 0;
}

.ph1 {
  padding-left: .25rem;
  padding-right: .25rem;
}

.ph2 {
  padding-left: .5rem;
  padding-right: .5rem;
}

.ph3 {
  padding-left: 1rem;
  padding-right: 1rem;
}

.ph4 {
  padding-left: 2rem;
  padding-right: 2rem;
}

.ph5 {
  padding-left: 4rem;
  padding-right: 4rem;
}

.ph6 {
  padding-left: 8rem;
  padding-right: 8rem;
}

.ph7 {
  padding-left: 16rem;
  padding-right: 16rem;
}

.ma0 {
  margin: 0;
}

.ma1 {
  margin: .25rem;
}

.ma2 {
  margin: .5rem;
}

.ma3 {
  margin: 1rem;
}

.ma4 {
  margin: 2rem;
}

.ma5 {
  margin: 4rem;
}

.ma6 {
  margin: 8rem;
}

.ma7 {
  margin: 16rem;
}

.ml0 {
  margin-left: 0;
}

.ml1 {
  margin-left: .25rem;
}

.ml2 {
  margin-left: .5rem;
}

.ml3 {
  margin-left: 1rem;
}

.ml4 {
  margin-left: 2rem;
}

.ml5 {
  margin-left: 4rem;
}

.ml6 {
  margin-left: 8rem;
}

.ml7 {
  margin-left: 16rem;
}

.mr0 {
  margin-right: 0;
}

.mr1 {
  margin-right: .25rem;
}

.mr2 {
  margin-right: .5rem;
}

.mr3 {
  margin-right: 1rem;
}

.mr4 {
  margin-right: 2rem;
}

.mr5 {
  margin-right: 4rem;
}

.mr6 {
  margin-right: 8rem;
}

.mr7 {
  margin-right: 16rem;
}

.mb0 {
  margin-bottom: 0;
}

.mb1 {
  margin-bottom: .25rem;
}

.mb2 {
  margin-bottom: .5rem;
}

.mb3 {
  margin-bottom: 1rem;
}

.mb4 {
  margin-bottom: 2rem;
}

.mb5 {
  margin-bottom: 4rem;
}

.mb6 {
  margin-bottom: 8rem;
}

.mb7 {
  margin-bottom: 16rem;
}

.mt0 {
  margin-top: 0;
}

.mt1 {
  margin-top: .25rem;
}

.mt2 {
  margin-top: .5rem;
}

.mt3 {
  margin-top: 1rem;
}

.mt4 {
  margin-top: 2rem;
}

.mt5 {
  margin-top: 4rem;
}

.mt6 {
  margin-top: 8rem;
}

.mt7 {
  margin-top: 16rem;
}

.mv0 {
  margin-top: 0;
  margin-bottom: 0rem;
}

.mv1 {
  margin-top: .25rem;
  margin-bottom: .25rem;
}

.mv2 {
  margin-top: .5rem;
  margin-bottom: .5rem;
}

.mv3 {
  margin-top: 1rem;
  margin-bottom: 1rem;
}

.mv4 {
  margin-top: 2rem;
  margin-bottom: 2rem;
}

.mv5 {
  margin-top: 4rem;
  margin-bottom: 4rem;
}

.mv6 {
  margin-top: 8rem;
  margin-bottom: 8rem;
}

.mv7 {
  margin-top: 16rem;
  margin-bottom: 16rem;
}

.mv-auto {
  margin-left: auto;
  margin-right: auto;
}

.mh0 {
  margin-left: 0;
  margin-right: 0;
}

.mh1 {
  margin-left: .25rem;
  margin-right: .25rem;
}

.mh2 {
  margin-left: .5rem;
  margin-right: .5rem;
}

.mh3 {
  margin-left: 1rem;
  margin-right: 1rem;
}

.mh4 {
  margin-left: 2rem;
  margin-right: 2rem;
}

.mh5 {
  margin-left: 4rem;
  margin-right: 4rem;
}

.mh6 {
  margin-left: 8rem;
  margin-right: 8rem;
}

.mh7 {
  margin-left: 16rem;
  margin-right: 16rem;
}

@media screen and (min-width: 599px) {
  .pa0-ns {
    padding: 0;
  }
  .pa1-ns {
    padding: .25rem;
  }
  .pa2-ns {
    padding: .5rem;
  }
  .pa3-ns {
    padding: 1rem;
  }
  .pa4-ns {
    padding: 2rem;
  }
  .pa5-ns {
    padding: 4rem;
  }
  .pa6-ns {
    padding: 8rem;
  }
  .pa7-ns {
    padding: 16rem;
  }
  .pl0-ns {
    padding-left: 0;
  }
  .pl1-ns {
    padding-left: .25rem;
  }
  .pl2-ns {
    padding-left: .5rem;
  }
  .pl3-ns {
    padding-left: 1rem;
  }
  .pl4-ns {
    padding-left: 2rem;
  }
  .pl5-ns {
    padding-left: 4rem;
  }
  .pl6-ns {
    padding-left: 8rem;
  }
  .pl7-ns {
    padding-left: 16rem;
  }
  .pr0-ns {
    padding-right: 0;
  }
  .pr1-ns {
    padding-right: .25rem;
  }
  .pr2-ns {
    padding-right: .5rem;
  }
  .pr3-ns {
    padding-right: 1rem;
  }
  .pr4-ns {
    padding-right: 2rem;
  }
  .pr5-ns {
    padding-right: 4rem;
  }
  .pr6-ns {
    padding-right: 8rem;
  }
  .pr7-ns {
    padding-right: 16rem;
  }
  .pb0-ns {
    padding-bottom: 0;
  }
  .pb1-ns {
    padding-bottom: .25rem;
  }
  .pb2-ns {
    padding-bottom: .5rem;
  }
  .pb3-ns {
    padding-bottom: 1rem;
  }
  .pb4-ns {
    padding-bottom: 2rem;
  }
  .pb5-ns {
    padding-bottom: 4rem;
  }
  .pb6-ns {
    padding-bottom: 8rem;
  }
  .pb7-ns {
    padding-bottom: 16rem;
  }
  .pt0-ns {
    padding-top: 0;
  }
  .pt1-ns {
    padding-top: .25rem;
  }
  .pt2-ns {
    padding-top: .5rem;
  }
  .pt3-ns {
    padding-top: 1rem;
  }
  .pt4-ns {
    padding-top: 2rem;
  }
  .pt5-ns {
    padding-top: 4rem;
  }
  .pt6-ns {
    padding-top: 8rem;
  }
  .pt7-ns {
    padding-top: 16rem;
  }
  .pv0-ns {
    padding-top: 0;
    padding-bottom: 0;
  }
  .pv1-ns {
    padding-top: .25rem;
    padding-bottom: .25rem;
  }
  .pv2-ns {
    padding-top: .5rem;
    padding-bottom: .5rem;
  }
  .pv3-ns {
    padding-top: 1rem;
    padding-bottom: 1rem;
  }
  .pv4-ns {
    padding-top: 2rem;
    padding-bottom: 2rem;
  }
  .pv5-ns {
    padding-top: 4rem;
    padding-bottom: 4rem;
  }
  .pv6-ns {
    padding-top: 8rem;
    padding-bottom: 8rem;
  }
  .pv7-ns {
    padding-top: 16rem;
    padding-bottom: 16rem;
  }
  .ph0-ns {
    padding-left: 0;
    padding-right: 0;
  }
  .ph1-ns {
    padding-left: .25rem;
    padding-right: .25rem;
  }
  .ph2-ns {
    padding-left: .5rem;
    padding-right: .5rem;
  }
  .ph3-ns {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  .ph4-ns {
    padding-left: 2rem;
    padding-right: 2rem;
  }
  .ph5-ns {
    padding-left: 4rem;
    padding-right: 4rem;
  }
  .ph6-ns {
    padding-left: 8rem;
    padding-right: 8rem;
  }
  .ph7-ns {
    padding-left: 16rem;
    padding-right: 16rem;
  }
  .ma0-ns {
    margin: 0;
  }
  .ma1-ns {
    margin: .25rem;
  }
  .ma2-ns {
    margin: .5rem;
  }
  .ma3-ns {
    margin: 1rem;
  }
  .ma4-ns {
    margin: 2rem;
  }
  .ma5-ns {
    margin: 4rem;
  }
  .ma6-ns {
    margin: 8rem;
  }
  .ma7-ns {
    margin: 16rem;
  }
  .ml0-ns {
    margin-left: 0;
  }
  .ml1-ns {
    margin-left: .25rem;
  }
  .ml2-ns {
    margin-left: .5rem;
  }
  .ml3-ns {
    margin-left: 1rem;
  }
  .ml4-ns {
    margin-left: 2rem;
  }
  .ml5-ns {
    margin-left: 4rem;
  }
  .ml6-ns {
    margin-left: 8rem;
  }
  .ml7-ns {
    margin-left: 16rem;
  }
  .mr0-ns {
    margin-right: 0;
  }
  .mr1-ns {
    margin-right: .25rem;
  }
  .mr2-ns {
    margin-right: .5rem;
  }
  .mr3-ns {
    margin-right: 1rem;
  }
  .mr4-ns {
    margin-right: 2rem;
  }
  .mr5-ns {
    margin-right: 4rem;
  }
  .mr6-ns {
    margin-right: 8rem;
  }
  .mr7-ns {
    margin-right: 16rem;
  }
  .mb0-ns {
    margin-bottom: 0;
  }
  .mb1-ns {
    margin-bottom: .25rem;
  }
  .mb2-ns {
    margin-bottom: .5rem;
  }
  .mb3-ns {
    margin-bottom: 1rem;
  }
  .mb4-ns {
    margin-bottom: 2rem;
  }
  .mb5-ns {
    margin-bottom: 4rem;
  }
  .mb6-ns {
    margin-bottom: 8rem;
  }
  .mb7-ns {
    margin-bottom: 16rem;
  }
  .mt0-ns {
    margin-top: 0;
  }
  .mt1-ns {
    margin-top: .25rem;
  }
  .mt2-ns {
    margin-top: .5rem;
  }
  .mt3-ns {
    margin-top: 1rem;
  }
  .mt4-ns {
    margin-top: 2rem;
  }
  .mt5-ns {
    margin-top: 4rem;
  }
  .mt6-ns {
    margin-top: 8rem;
  }
  .mt7-ns {
    margin-top: 16rem;
  }
  .mv0-ns {
    margin-top: 0;
    margin-bottom: 0;
  }
  .mv1-ns {
    margin-top: .25rem;
    margin-bottom: .25rem;
  }
  .mv2-ns {
    margin-top: .5rem;
    margin-bottom: .5rem;
  }
  .mv3-ns {
    margin-top: 1rem;
    margin-bottom: 1rem;
  }
  .mv4-ns {
    margin-top: 2rem;
    margin-bottom: 2rem;
  }
  .mv5-ns {
    margin-top: 4rem;
    margin-bottom: 4rem;
  }
  .mv6-ns {
    margin-top: 8rem;
    margin-bottom: 8rem;
  }
  .mv7-ns {
    margin-top: 16rem;
    margin-bottom: 16rem;
  }
  .mh0-ns {
    margin-left: 0;
    margin-right: 0;
  }
  .mh1-ns {
    margin-left: .25rem;
    margin-right: .25rem;
  }
  .mh2-ns {
    margin-left: .5rem;
    margin-right: .5rem;
  }
  .mh3-ns {
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .mh4-ns {
    margin-left: 2rem;
    margin-right: 2rem;
  }
  .mh5-ns {
    margin-left: 4rem;
    margin-right: 4rem;
  }
  .mh6-ns {
    margin-left: 8rem;
    margin-right: 8rem;
  }
  .mh7-ns {
    margin-left: 16rem;
    margin-right: 16rem;
  }
}

@media screen and (min-width: 600px) and (max-width: 959px) {
  .pa0-m {
    padding: 0;
  }
  .pa1-m {
    padding: .25rem;
  }
  .pa2-m {
    padding: .5rem;
  }
  .pa3-m {
    padding: 1rem;
  }
  .pa4-m {
    padding: 2rem;
  }
  .pa5-m {
    padding: 4rem;
  }
  .pa6-m {
    padding: 8rem;
  }
  .pa7-m {
    padding: 16rem;
  }
  .pl0-m {
    padding-left: 0;
  }
  .pl1-m {
    padding-left: .25rem;
  }
  .pl2-m {
    padding-left: .5rem;
  }
  .pl3-m {
    padding-left: 1rem;
  }
  .pl4-m {
    padding-left: 2rem;
  }
  .pl5-m {
    padding-left: 4rem;
  }
  .pl6-m {
    padding-left: 8rem;
  }
  .pl7-m {
    padding-left: 16rem;
  }
  .pr0-m {
    padding-right: 0;
  }
  .pr1-m {
    padding-right: .25rem;
  }
  .pr2-m {
    padding-right: .5rem;
  }
  .pr3-m {
    padding-right: 1rem;
  }
  .pr4-m {
    padding-right: 2rem;
  }
  .pr5-m {
    padding-right: 4rem;
  }
  .pr6-m {
    padding-right: 8rem;
  }
  .pr7-m {
    padding-right: 16rem;
  }
  .pb0-m {
    padding-bottom: 0;
  }
  .pb1-m {
    padding-bottom: .25rem;
  }
  .pb2-m {
    padding-bottom: .5rem;
  }
  .pb3-m {
    padding-bottom: 1rem;
  }
  .pb4-m {
    padding-bottom: 2rem;
  }
  .pb5-m {
    padding-bottom: 4rem;
  }
  .pb6-m {
    padding-bottom: 8rem;
  }
  .pb7-m {
    padding-bottom: 16rem;
  }
  .pt0-m {
    padding-top: 0;
  }
  .pt1-m {
    padding-top: .25rem;
  }
  .pt2-m {
    padding-top: .5rem;
  }
  .pt3-m {
    padding-top: 1rem;
  }
  .pt4-m {
    padding-top: 2rem;
  }
  .pt5-m {
    padding-top: 4rem;
  }
  .pt6-m {
    padding-top: 8rem;
  }
  .pt7-m {
    padding-top: 16rem;
  }
  .pv0-m {
    padding-top: 0;
    padding-bottom: 0;
  }
  .pv1-m {
    padding-top: .25rem;
    padding-bottom: .25rem;
  }
  .pv2-m {
    padding-top: .5rem;
    padding-bottom: .5rem;
  }
  .pv3-m {
    padding-top: 1rem;
    padding-bottom: 1rem;
  }
  .pv4-m {
    padding-top: 2rem;
    padding-bottom: 2rem;
  }
  .pv5-m {
    padding-top: 4rem;
    padding-bottom: 4rem;
  }
  .pv6-m {
    padding-top: 8rem;
    padding-bottom: 8rem;
  }
  .pv7-m {
    padding-top: 16rem;
    padding-bottom: 16rem;
  }
  .ph0-m {
    padding-left: 0;
    padding-right: 0;
  }
  .ph1-m {
    padding-left: .25rem;
    padding-right: .25rem;
  }
  .ph2-m {
    padding-left: .5rem;
    padding-right: .5rem;
  }
  .ph3-m {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  .ph4-m {
    padding-left: 2rem;
    padding-right: 2rem;
  }
  .ph5-m {
    padding-left: 4rem;
    padding-right: 4rem;
  }
  .ph6-m {
    padding-left: 8rem;
    padding-right: 8rem;
  }
  .ph7-m {
    padding-left: 16rem;
    padding-right: 16rem;
  }
  .ma0-m {
    margin: 0;
  }
  .ma1-m {
    margin: .25rem;
  }
  .ma2-m {
    margin: .5rem;
  }
  .ma3-m {
    margin: 1rem;
  }
  .ma4-m {
    margin: 2rem;
  }
  .ma5-m {
    margin: 4rem;
  }
  .ma6-m {
    margin: 8rem;
  }
  .ma7-m {
    margin: 16rem;
  }
  .ml0-m {
    margin-left: 0;
  }
  .ml1-m {
    margin-left: .25rem;
  }
  .ml2-m {
    margin-left: .5rem;
  }
  .ml3-m {
    margin-left: 1rem;
  }
  .ml4-m {
    margin-left: 2rem;
  }
  .ml5-m {
    margin-left: 4rem;
  }
  .ml6-m {
    margin-left: 8rem;
  }
  .ml7-m {
    margin-left: 16rem;
  }
  .mr0-m {
    margin-right: 0;
  }
  .mr1-m {
    margin-right: .25rem;
  }
  .mr2-m {
    margin-right: .5rem;
  }
  .mr3-m {
    margin-right: 1rem;
  }
  .mr4-m {
    margin-right: 2rem;
  }
  .mr5-m {
    margin-right: 4rem;
  }
  .mr6-m {
    margin-right: 8rem;
  }
  .mr7-m {
    margin-right: 16rem;
  }
  .mb0-m {
    margin-bottom: 0;
  }
  .mb1-m {
    margin-bottom: .25rem;
  }
  .mb2-m {
    margin-bottom: .5rem;
  }
  .mb3-m {
    margin-bottom: 1rem;
  }
  .mb4-m {
    margin-bottom: 2rem;
  }
  .mb5-m {
    margin-bottom: 4rem;
  }
  .mb6-m {
    margin-bottom: 8rem;
  }
  .mb7-m {
    margin-bottom: 16rem;
  }
  .mt0-m {
    margin-top: 0;
  }
  .mt1-m {
    margin-top: .25rem;
  }
  .mt2-m {
    margin-top: .5rem;
  }
  .mt3-m {
    margin-top: 1rem;
  }
  .mt4-m {
    margin-top: 2rem;
  }
  .mt5-m {
    margin-top: 4rem;
  }
  .mt6-m {
    margin-top: 8rem;
  }
  .mt7-m {
    margin-top: 16rem;
  }
  .mv0-m {
    margin-top: 0;
    margin-bottom: 0;
  }
  .mv1-m {
    margin-top: .25rem;
    margin-bottom: .25rem;
  }
  .mv2-m {
    margin-top: .5rem;
    margin-bottom: .5rem;
  }
  .mv3-m {
    margin-top: 1rem;
    margin-bottom: 1rem;
  }
  .mv4-m {
    margin-top: 2rem;
    margin-bottom: 2rem;
  }
  .mv5-m {
    margin-top: 4rem;
    margin-bottom: 4rem;
  }
  .mv6-m {
    margin-top: 8rem;
    margin-bottom: 8rem;
  }
  .mv7-m {
    margin-top: 16rem;
    margin-bottom: 16rem;
  }
  .mh0-m {
    margin-left: 0;
    margin-right: 0;
  }
  .mh1-m {
    margin-left: .25rem;
    margin-right: .25rem;
  }
  .mh2-m {
    margin-left: .5rem;
    margin-right: .5rem;
  }
  .mh3-m {
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .mh4-m {
    margin-left: 2rem;
    margin-right: 2rem;
  }
  .mh5-m {
    margin-left: 4rem;
    margin-right: 4rem;
  }
  .mh6-m {
    margin-left: 8rem;
    margin-right: 8rem;
  }
  .mh7-m {
    margin-left: 16rem;
    margin-right: 16rem;
  }
}

@media screen and (min-width: 1200px) {
  .pa0-l {
    padding: 0;
  }
  .pa1-l {
    padding: .25rem;
  }
  .pa2-l {
    padding: .5rem;
  }
  .pa3-l {
    padding: 1rem;
  }
  .pa4-l {
    padding: 2rem;
  }
  .pa5-l {
    padding: 4rem;
  }
  .pa6-l {
    padding: 8rem;
  }
  .pa7-l {
    padding: 16rem;
  }
  .pl0-l {
    padding-left: 0;
  }
  .pl1-l {
    padding-left: .25rem;
  }
  .pl2-l {
    padding-left: .5rem;
  }
  .pl3-l {
    padding-left: 1rem;
  }
  .pl4-l {
    padding-left: 2rem;
  }
  .pl5-l {
    padding-left: 4rem;
  }
  .pl6-l {
    padding-left: 8rem;
  }
  .pl7-l {
    padding-left: 16rem;
  }
  .pr0-l {
    padding-right: 0;
  }
  .pr1-l {
    padding-right: .25rem;
  }
  .pr2-l {
    padding-right: .5rem;
  }
  .pr3-l {
    padding-right: 1rem;
  }
  .pr4-l {
    padding-right: 2rem;
  }
  .pr5-l {
    padding-right: 4rem;
  }
  .pr6-l {
    padding-right: 8rem;
  }
  .pr7-l {
    padding-right: 16rem;
  }
  .pb0-l {
    padding-bottom: 0;
  }
  .pb1-l {
    padding-bottom: .25rem;
  }
  .pb2-l {
    padding-bottom: .5rem;
  }
  .pb3-l {
    padding-bottom: 1rem;
  }
  .pb4-l {
    padding-bottom: 2rem;
  }
  .pb5-l {
    padding-bottom: 4rem;
  }
  .pb6-l {
    padding-bottom: 8rem;
  }
  .pb7-l {
    padding-bottom: 16rem;
  }
  .pt0-l {
    padding-top: 0;
  }
  .pt1-l {
    padding-top: .25rem;
  }
  .pt2-l {
    padding-top: .5rem;
  }
  .pt3-l {
    padding-top: 1rem;
  }
  .pt4-l {
    padding-top: 2rem;
  }
  .pt5-l {
    padding-top: 4rem;
  }
  .pt6-l {
    padding-top: 8rem;
  }
  .pt7-l {
    padding-top: 16rem;
  }
  .pv0-l {
    padding-top: 0;
    padding-bottom: 0;
  }
  .pv1-l {
    padding-top: .25rem;
    padding-bottom: .25rem;
  }
  .pv2-l {
    padding-top: .5rem;
    padding-bottom: .5rem;
  }
  .pv3-l {
    padding-top: 1rem;
    padding-bottom: 1rem;
  }
  .pv4-l {
    padding-top: 2rem;
    padding-bottom: 2rem;
  }
  .pv5-l {
    padding-top: 4rem;
    padding-bottom: 4rem;
  }
  .pv6-l {
    padding-top: 8rem;
    padding-bottom: 8rem;
  }
  .pv7-l {
    padding-top: 16rem;
    padding-bottom: 16rem;
  }
  .ph0-l {
    padding-left: 0;
    padding-right: 0;
  }
  .ph1-l {
    padding-left: .25rem;
    padding-right: .25rem;
  }
  .ph2-l {
    padding-left: .5rem;
    padding-right: .5rem;
  }
  .ph3-l {
    padding-left: 1rem;
    padding-right: 1rem;
  }
  .ph4-l {
    padding-left: 2rem;
    padding-right: 2rem;
  }
  .ph5-l {
    padding-left: 4rem;
    padding-right: 4rem;
  }
  .ph6-l {
    padding-left: 8rem;
    padding-right: 8rem;
  }
  .ph7-l {
    padding-left: 16rem;
    padding-right: 16rem;
  }
  .ma0-l {
    margin: 0;
  }
  .ma1-l {
    margin: .25rem;
  }
  .ma2-l {
    margin: .5rem;
  }
  .ma3-l {
    margin: 1rem;
  }
  .ma4-l {
    margin: 2rem;
  }
  .ma5-l {
    margin: 4rem;
  }
  .ma6-l {
    margin: 8rem;
  }
  .ma7-l {
    margin: 16rem;
  }
  .ml0-l {
    margin-left: 0;
  }
  .ml1-l {
    margin-left: .25rem;
  }
  .ml2-l {
    margin-left: .5rem;
  }
  .ml3-l {
    margin-left: 1rem;
  }
  .ml4-l {
    margin-left: 2rem;
  }
  .ml5-l {
    margin-left: 4rem;
  }
  .ml6-l {
    margin-left: 8rem;
  }
  .ml7-l {
    margin-left: 16rem;
  }
  .mr0-l {
    margin-right: 0;
  }
  .mr1-l {
    margin-right: .25rem;
  }
  .mr2-l {
    margin-right: .5rem;
  }
  .mr3-l {
    margin-right: 1rem;
  }
  .mr4-l {
    margin-right: 2rem;
  }
  .mr5-l {
    margin-right: 4rem;
  }
  .mr6-l {
    margin-right: 8rem;
  }
  .mr7-l {
    margin-right: 16rem;
  }
  .mb0-l {
    margin-bottom: 0;
  }
  .mb1-l {
    margin-bottom: .25rem;
  }
  .mb2-l {
    margin-bottom: .5rem;
  }
  .mb3-l {
    margin-bottom: 1rem;
  }
  .mb4-l {
    margin-bottom: 2rem;
  }
  .mb5-l {
    margin-bottom: 4rem;
  }
  .mb6-l {
    margin-bottom: 8rem;
  }
  .mb7-l {
    margin-bottom: 16rem;
  }
  .mt0-l {
    margin-top: 0;
  }
  .mt1-l {
    margin-top: .25rem;
  }
  .mt2-l {
    margin-top: .5rem;
  }
  .mt3-l {
    margin-top: 1rem;
  }
  .mt4-l {
    margin-top: 2rem;
  }
  .mt5-l {
    margin-top: 4rem;
  }
  .mt6-l {
    margin-top: 8rem;
  }
  .mt7-l {
    margin-top: 16rem;
  }
  .mv0-l {
    margin-top: 0;
    margin-bottom: 0;
  }
  .mv1-l {
    margin-top: .25rem;
    margin-bottom: .25rem;
  }
  .mv2-l {
    margin-top: .5rem;
    margin-bottom: .5rem;
  }
  .mv3-l {
    margin-top: 1rem;
    margin-bottom: 1rem;
  }
  .mv4-l {
    margin-top: 2rem;
    margin-bottom: 2rem;
  }
  .mv5-l {
    margin-top: 4rem;
    margin-bottom: 4rem;
  }
  .mv6-l {
    margin-top: 8rem;
    margin-bottom: 8rem;
  }
  .mv7-l {
    margin-top: 16rem;
    margin-bottom: 16rem;
  }
  .mh0-l {
    margin-left: 0;
    margin-right: 0;
  }
  .mh1-l {
    margin-left: .25rem;
    margin-right: .25rem;
  }
  .mh2-l {
    margin-left: .5rem;
    margin-right: .5rem;
  }
  .mh3-l {
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .mh4-l {
    margin-left: 2rem;
    margin-right: 2rem;
  }
  .mh5-l {
    margin-left: 4rem;
    margin-right: 4rem;
  }
  .mh6-l {
    margin-left: 8rem;
    margin-right: 8rem;
  }
  .mh7-l {
    margin-left: 16rem;
    margin-right: 16rem;
  }
}

.ba {
  border-style: solid;
  border-width: 1px;
}

.bt {
  border-top-style: solid;
  border-top-width: 1px;
}

.br {
  border-right-style: solid;
  border-right-width: 1px;
}

.bb {
  border-bottom-style: solid;
  border-bottom-width: 1px;
}

.bl {
  border-left-style: solid;
  border-left-width: 1px;
}

.bn {
  border-style: none;
  border-width: 0;
}

.bw0 {
  border-width: 0;
}

.bw1 {
  border-width: .125rem;
}

.bw2 {
  border-width: .25rem;
}

.bw3 {
  border-width: .5rem;
}

.bw4 {
  border-width: 1rem;
}

.bw5 {
  border-width: 2rem;
}

.b-grey {
  border-color: #D1D6DC;
}

.b-grey-light {
  border-color: #e2e5e9;
}

.b-blue {
  border-color: #0A83F6;
}

.b-green {
  border-color: #80C11A;
}

.b-red {
  border-color: #C32525;
}

.br0 {
  border-radius: 0;
}

.br1 {
  border-radius: .125rem;
}

.br2 {
  border-radius: .25rem;
}

.br3 {
  border-radius: .5rem;
}

.br4 {
  border-radius: 1rem;
}

.br-100 {
  border-radius: 100%;
}

.br--top {
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

.br--right {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}

.br--bottom {
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

.br--left {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}

.o-100 {
  opacity: 1;
}

.o-90 {
  opacity: .9;
}

.o-80 {
  opacity: .8;
}

.o-70 {
  opacity: .7;
}

.o-60 {
  opacity: .6;
}

.o-50 {
  opacity: .5;
}

.o-40 {
  opacity: .4;
}

.o-30 {
  opacity: .3;
}

.o-20 {
  opacity: .2;
}

.o-10 {
  opacity: .1;
}

.o-05 {
  opacity: .05;
}

.o-025 {
  opacity: .025;
}

.v-base {
  vertical-align: baseline;
}

.v-sub {
  vertical-align: sub;
}

.v-sup {
  vertical-align: super;
}

.v-txt-top {
  vertical-align: text-top;
}

.v-txt-btm {
  vertical-align: text-bottom;
}

.v-mid {
  vertical-align: middle;
}

.v-top {
  vertical-align: top;
}

.v-btm {
  vertical-align: bottom;
}

.static {
  position: static;
}

.relative {
  position: relative;
}

.absolute {
  position: absolute;
}

.fixed {
  position: fixed;
}

.top-0 {
  top: 0;
}

.right-0 {
  right: 0;
}

.bottom-0 {
  bottom: 0;
}

.left-0 {
  left: 0;
}

.top-1 {
  top: 1rem;
}

.right-1 {
  right: 1rem;
}

.bottom-1 {
  bottom: 1rem;
}

.left-1 {
  left: 1rem;
}

.top-2 {
  top: 2rem;
}

.right-2 {
  right: 2rem;
}

.bottom-2 {
  bottom: 2rem;
}

.left-2 {
  left: 2rem;
}

.top--1 {
  top: -1rem;
}

.right--1 {
  right: -1rem;
}

.bottom--1 {
  bottom: -1rem;
}

.left--1 {
  left: -1rem;
}

.top--2 {
  top: -2rem;
}

.right--2 {
  right: -2rem;
}

.bottom--2 {
  bottom: -2rem;
}

.left--2 {
  left: -2rem;
}

.absolute--fill {
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

.w1 {
  width: 1rem;
}

.w2 {
  width: 2rem;
}

.w3 {
  width: 4rem;
}

.w4 {
  width: 8rem;
}

.w5 {
  width: 16rem;
}

.w-10 {
  width: 10%;
}

.w-20 {
  width: 20%;
}

.w-25 {
  width: 25%;
}

.w-33 {
  width: 33%;
}

.w-34 {
  width: 34%;
}

.w-40 {
  width: 40%;
}

.w-50 {
  width: 50%;
}

.w-60 {
  width: 60%;
}

.w-75 {
  width: 75%;
}

.w-80 {
  width: 80%;
}

.w-100 {
  width: 100%;
}

.w-auto {
  width: auto;
}

.h1 {
  height: 1rem;
}

.h2 {
  height: 2rem;
}

.h3 {
  height: 4rem;
}

.h4 {
  height: 8rem;
}

.h5 {
  height: 16rem;
}

.h-25 {
  height: 25%;
}

.h-50 {
  height: 50%;
}

.h-75 {
  height: 75%;
}

.h-100 {
  height: 100%;
}

.h-auto {
  height: auto;
}

.h-inherit {
  height: inherit;
}

.overflow-visible {
  overflow: visible;
}

.overflow-hidden {
  overflow: hidden;
}

.overflow-scroll {
  overflow: scroll;
}

.overflow-auto {
  overflow: auto;
}

.overflow-x-visible {
  overflow-x: visible;
}

.overflow-x-hidden {
  overflow-x: hidden;
}

.overflow-x-scroll {
  overflow-x: scroll;
}

.overflow-x-auto {
  overflow-x: auto;
}

.overflow-y-visible {
  overflow-y: visible;
}

.overflow-y-hidden {
  overflow-y: hidden;
}

.overflow-y-scroll {
  overflow-y: scroll;
}

.overflow-y-auto {
  overflow-y: auto;
}

.color-link {
  color: #0A83F6;
}

.color-link-hover {
  color: #0769c6;
}

.color-text {
  color: #76899A;
}

.color-heading {
  color: #57626C;
}

.lh-solid {
  line-height: 1;
}

.lh-title {
  line-height: 1.3;
}

.lh-copy {
  line-height: 1.6;
}

.normal {
  font-weight: normal;
}

.b {
  font-weight: bold;
}

.fw1 {
  font-weight: 100;
}

.fw2 {
  font-weight: 200;
}

.fw3 {
  font-weight: 300;
}

.fw4 {
  font-weight: 400;
}

.fw5 {
  font-weight: 500;
}

.fw6 {
  font-weight: 600;
}

.fw7 {
  font-weight: 700;
}

.fw8 {
  font-weight: 800;
}

.fw9 {
  font-weight: 900;
}

.bg-highlight-hover {
  background-color: #FAFAFA;
}

.bg-highlight-select {
  background-color: #FAFAFA;
}

.bg-highlight-inline {
  background-color: #E2E5E9;
}

.bg-header {
  background-color: #f5f5f5;
}

.bg-white {
  background-color: #fff;
}

.vis-visible {
  visibility: visible;
}

.vis-hidden {
  visibility: hidden;
}

.vis-collapse {
  visibility: collapse;
}

.vis-inherit {
  visibility: inherit;
}

.vis-initial {
  visibility: initial;
}

.vis-unset {
  visibility: unset;
}

.hover-highlight {
  background-color: #fff;
  transition: background-color .500ms ease-in;
}

.hover-highlight:hover {
  background-color: #FAFAFA;
}

.cursor-auto {
  cursor: auto;
}

.cursor-default {
  cursor: default;
}

.cursor-none {
  cursor: none;
}

.cursor-help {
  cursor: help;
}

.cursor-pointer {
  cursor: pointer;
}

.cursor-text {
  cursor: text;
}

.cursor-vertical-text {
  cursor: vertical-text;
}

.cursor-move {
  cursor: move;
}

.cursor-not-allowed {
  cursor: not-allowed;
}

.shadow {
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
}

.tl {
  text-align: left;
}

.tr {
  text-align: right;
}

.tc {
  text-align: center;
}

.ttc {
  text-transform: capitalize;
}

.ttl {
  text-transform: lowercase;
}

.ttu {
  text-transform: uppercase;
}

.ttn {
  text-transform: none;
}

.hide {
  display: none !important;
}

.show {
  display: block !important;
}

.invisible {
  visibility: hidden;
}

.scroll {
  -webkit-overflow-scrolling: touch;
  overflow-y: scroll;
}

.user-select-none {
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
}

.user-select-all {
  -webkit-user-select: all;
     -moz-user-select: all;
      -ms-user-select: all;
          user-select: all;
}

.ws-normal {
  white-space: normal;
}

.nowrap {
  white-space: nowrap;
}

.pre {
  white-space: pre;
}

.z-0 {
  z-index: 0;
}

.z-1 {
  z-index: 1;
}

.z-2 {
  z-index: 2;
}

.z-3 {
  z-index: 3;
}

.strike {
  text-decoration: line-through;
}

.underline {
  text-decoration: underline;
}

.no-underline {
  text-decoration: none;
}

.aspect-ratio-16-9,
.aspect-ratio-60,
.aspect-ratio-75,
.aspect-ratio-100 {
  position: relative;
}

.aspect-ratio-16-9:before,
.aspect-ratio-60:before,
.aspect-ratio-75:before,
.aspect-ratio-100:before {
  display: block;
  content: "";
}

.aspect-ratio-16-9:before {
  padding-top: 56.25%;
}

.aspect-ratio-60:before {
  padding-top: 62.5%;
}

.aspect-ratio-75:before {
  padding-top: 75%;
}

.aspect-ratio-100:before {
  padding-top: 100%;
}

.list-style-disc {
  list-style-type: disc;
}

.list-style-circle {
  list-style-type: circle;
}

.list-style-square {
  list-style-type: square;
}

.list-style-decimal {
  list-style-type: decimal;
}

.list-style-none {
  list-style-type: none;
}

body.fullbleed {
  height: 100vh;
  padding: 0;
  margin: 0;
}

```

## Author

Jason Melgoza

## License

MIT