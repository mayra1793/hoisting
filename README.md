# hoisting
Código entregado 

var feature = "closures";
(function () {
if ( typeof feature === "undefined"){         
var feature = "callbacks";         
    console.log("JS coders love its " + feature );     
    } else {       
    console.log("JS developers love its " + feature );     
    }
 })();
 
Código modificado

(function () {
var feature = "closures";
if ( typeof feature === "undefined"){         
    var feature = "callbacks";         
        console.log("JS coders love its " + feature );     
    } else {       
    console.log("JS developers love its " + feature );     
    }
 })();