(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function u(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ha(a){return a.raw=a}
function v(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ia(a){if(!(a instanceof Array)){a=v(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ja(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ja(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||la});
var ma="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},na=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),pa;
if("function"==typeof Object.setPrototypeOf)pa=Object.setPrototypeOf;else{var qa;a:{var sa={a:!0},ta={};try{ta.__proto__=sa;qa=ta.a;break a}catch(a){}qa=!1}pa=qa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ua=pa;
function w(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(ua)ua(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.va=b.prototype}
function va(){this.v=!1;this.m=null;this.i=void 0;this.h=1;this.s=this.l=0;this.Da=this.j=null}
function wa(a){if(a.v)throw new TypeError("Generator is already running");a.v=!0}
va.prototype.fa=function(a){this.i=a};
function xa(a,b){a.j={exception:b,rd:!0};a.h=a.l||a.s}
va.prototype.return=function(a){this.j={return:a};this.h=this.s};
va.prototype.yield=function(a,b){this.h=b;return{value:a}};
va.prototype.A=function(a){this.h=a};
function ya(a,b,c){a.l=b;void 0!=c&&(a.s=c)}
function za(a){a.l=0;var b=a.j.exception;a.j=null;return b}
function Aa(a){var b=a.Da.splice(0)[0];(b=a.j=a.j||b)?b.rd?a.h=a.l||a.s:void 0!=b.A&&a.s<b.A?(a.h=b.A,a.j=null):a.h=a.s:a.h=0}
function Ba(a){this.h=new va;this.i=a}
function Ca(a,b){wa(a.h);var c=a.h.m;if(c)return Da(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ea(a)}
function Da(a,b,c,d){try{var e=b.call(a.h.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.v=!1,e;var f=e.value}catch(g){return a.h.m=null,xa(a.h,g),Ea(a)}a.h.m=null;d.call(a.h,f);return Ea(a)}
function Ea(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.v=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.v=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.rd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Fa(a){this.next=function(b){wa(a.h);a.h.m?b=Da(a,a.h.m.next,b,a.h.fa):(a.h.fa(b),b=Ea(a));return b};
this.throw=function(b){wa(a.h);a.h.m?b=Da(a,a.h.m["throw"],b,a.h.fa):(xa(a.h,b),b=Ea(a));return b};
this.return=function(b){return Ca(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ga(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function A(a){return Ga(new Fa(new Ba(a)))}
function B(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
u("Reflect",function(a){return a?a:{}});
u("Reflect.construct",function(){return na});
u("Reflect.setPrototypeOf",function(a){return a?a:ua?function(b,c){try{return ua(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.v=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.W),reject:g(this.m)}};
b.prototype.W=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ba(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.V(g):this.s(g)}};
b.prototype.V=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ja(h,g):this.s(g)};
b.prototype.m=function(g){this.fa(2,g)};
b.prototype.s=function(g){this.fa(1,g)};
b.prototype.fa=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Z();this.Da()};
b.prototype.Z=function(){var g=this;e(function(){if(g.P()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.P=function(){if(this.v)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.Da=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ba=function(g){var h=this.l();g.cc(h.resolve,h.reject)};
b.prototype.ja=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,r){return"function"==typeof t?function(x){try{l(t(x))}catch(y){n(y)}}:r}
var l,n,p=new b(function(t,r){l=t;n=r});
this.cc(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.cc=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.v=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=v(g),n=l.next();!n.done;n=l.next())d(n.value).cc(h,k)})};
b.all=function(g){var h=v(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(x){return function(y){t[x]=y;r--;0==r&&l(t)}}
var t=[],r=0;do t.push(void 0),r++,d(k.value).cc(p(t.length-1),n),k=h.next();while(!k.done)})};
return b});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=v(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!ja(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ja(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ja(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return fa(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h[0][l];if(n&&ja(h[0],l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=v(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(v([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ia(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
u("Object.setPrototypeOf",function(a){return a||ua});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
function Ja(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.keys",function(a){return a?a:function(){return Ja(this,function(b){return b})}});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=v(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(v([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
u("Array.prototype.values",function(a){return a?a:function(){return Ja(this,function(b,c){return c})}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ia(this,b,"includes").indexOf(b,c||0)}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Array.prototype.entries",function(a){return a?a:function(){return Ja(this,function(b,c){return[b,c]})}});
u("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push([d,b[d]]);return c}});
u("globalThis",function(a){return a||da});
var Ka=Ka||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function La(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Na(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Oa(a){return Object.prototype.hasOwnProperty.call(a,Pa)&&a[Pa]||(a[Pa]=++Qa)}
var Pa="closure_uid_"+(1E9*Math.random()>>>0),Qa=0;function Ra(a,b,c){return a.call.apply(a.bind,arguments)}
function Sa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ta(a,b,c){Ta=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ra:Sa;return Ta.apply(null,arguments)}
function Ua(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Va(a,b){function c(){}
c.prototype=b.prototype;a.va=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Wa(a){return a}
;function Xa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Xa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Va(Xa,Error);Xa.prototype.name="CustomError";function Ya(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Za(){}
function $a(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var ab=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},bb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},cb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},db=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},eb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
bb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function fb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function gb(a,b){b=ab(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function hb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function ib(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function jb(a){var b=kb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function lb(a){for(var b in a)return!1;return!0}
function mb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function nb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function ob(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function pb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function qb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=qb(a[c]);return b}
var rb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function sb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<rb.length;f++)c=rb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var tb;function ub(){if(void 0===tb){var a=null,b=C.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Wa,createScript:Wa,createScriptURL:Wa})}catch(c){C.console&&C.console.error(c.message)}tb=a}else tb=a}return tb}
;function vb(a,b){this.j=a===wb&&b||""}
vb.prototype.i=!0;vb.prototype.h=function(){return this.j};
function xb(a){return new vb(wb,a)}
var wb={};xb("");var yb={};function zb(a){this.j=a;this.i=!0}
zb.prototype.toString=function(){return this.j.toString()};
zb.prototype.h=function(){return this.j.toString()};function Ab(a){this.j=a}
Ab.prototype.toString=function(){return this.j+""};
Ab.prototype.i=!0;Ab.prototype.h=function(){return this.j.toString()};
function Bb(a){if(a instanceof Ab&&a.constructor===Ab)return a.j;La(a);return"type_error:TrustedResourceUrl"}
var Cb={};function Db(a){var b=ub();a=b?b.createScriptURL(a):a;return new Ab(a,Cb)}
;var Eb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};function Fb(a){this.j=a}
Fb.prototype.toString=function(){return this.j.toString()};
Fb.prototype.i=!0;Fb.prototype.h=function(){return this.j.toString()};
function Gb(a){if(a instanceof Fb&&a.constructor===Fb)return a.j;La(a);return"type_error:SafeUrl"}
var Hb;try{new URL("s://g"),Hb=!0}catch(a){Hb=!1}var Ib=Hb,Jb={},Kb=new Fb("about:invalid#zClosurez",Jb);var Lb,Mb=E("CLOSURE_FLAGS"),Nb=Mb&&Mb[610401301];Lb=null!=Nb?Nb:!1;function Ob(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Pb,Qb=C.navigator;Pb=Qb?Qb.userAgentData||null:null;function Rb(a){return Lb?Pb?Pb.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function F(a){return-1!=Ob().indexOf(a)}
;function Sb(){return Lb?!!Pb&&0<Pb.brands.length:!1}
function Tb(){return Sb()?!1:F("Opera")}
function Ub(){return Sb()?!1:F("Trident")||F("MSIE")}
function Vb(){return F("Firefox")||F("FxiOS")}
function Wb(){return Sb()?Rb("Chromium"):(F("Chrome")||F("CriOS"))&&!(Sb()?0:F("Edge"))||F("Silk")}
;function Xb(a){this.j=a;this.i=!0}
Xb.prototype.h=function(){return this.j.toString()};
Xb.prototype.toString=function(){return this.j.toString()};function Yb(a,b){if(!(b instanceof Fb||b instanceof Fb)){b="object"==typeof b&&b.i?b.h():String(b);b:{var c=b;if(Ib){try{var d=new URL(c)}catch(e){c="https:";break b}c=d.protocol}else c:{d=document.createElement("a");try{d.href=c}catch(e){c=void 0;break c}c=d.protocol;c=":"===c||""===c?"https:":c}}"javascript:"!==c||(b="about:invalid#zClosurez");b=new Fb(b,Jb)}a.href=Gb(b)}
function Zb(a,b){a.rel="stylesheet";a.href=Bb(b).toString();(b=$b('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function ac(){return $b("script[nonce]")}
var bc=/^[\w+/_-]+[=]{0,2}$/;function $b(a,b){b=(b||C).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&bc.test(a)?a:"":""}
;function cc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var dc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function ec(a){return a?decodeURI(a):a}
function fc(a,b){return b.match(dc)[a]||null}
function hc(a){return ec(fc(3,a))}
function ic(a){var b=a.match(dc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function jc(a){var b=a.indexOf("#");return 0>b?a:a.slice(0,b)}
function kc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function lc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)lc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function mc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)lc(a[b],a[b+1],c);return c.join("&")}
function nc(a){var b=[],c;for(c in a)lc(c,a[c],b);return b.join("&")}
function oc(a,b){var c=2==arguments.length?mc(arguments[1],0):mc(arguments,1);return kc(a,c)}
function pc(a,b){b=nc(b);return kc(a,b)}
function qc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return kc(a,b+c)}
function rc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var sc=/#|$/,tc=/[?&]($|#)/;function uc(a,b){for(var c=a.search(sc),d=0,e,f=[];0<=(e=rc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(tc,"$1")}
;function vc(a){this.gd=a}
;function wc(a,b,c){this.i=a;this.l=b;this.h=c||[];this.rb=new Map}
m=wc.prototype;m.Td=function(a){var b=B.apply(1,arguments),c=this.Cc(b);c?c.push(new vc(a)):this.Ed(a,b)};
m.Ed=function(a){var b=this.md(B.apply(1,arguments));this.rb.set(b,[new vc(a)])};
m.Cc=function(){var a=this.md(B.apply(0,arguments));return this.rb.has(a)?this.rb.get(a):void 0};
m.le=function(){var a=this.Cc(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
m.clear=function(){this.rb.clear()};
m.md=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function xc(a,b){wc.call(this,a,3,b)}
w(xc,wc);xc.prototype.j=function(a){var b=B.apply(1,arguments),c=0,d=this.le(b);d&&(c=d.gd);this.Ed(c+a,b)};function yc(a,b){wc.call(this,a,2,b)}
w(yc,wc);yc.prototype.record=function(a){this.Td(a,B.apply(1,arguments))};function zc(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function Ac(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ma(d)?Ac.apply(null,d):zc(d)}}
;function G(){this.Da=this.Da;this.fa=this.fa}
G.prototype.Da=!1;G.prototype.h=function(){return this.Da};
G.prototype.dispose=function(){this.Da||(this.Da=!0,this.M())};
function Bc(a,b){Cc(a,Ua(zc,b))}
function Cc(a,b){a.Da?b():(a.fa||(a.fa=[]),a.fa.push(b))}
G.prototype.M=function(){if(this.fa)for(;this.fa.length;)this.fa.shift()()};function Dc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Dc.prototype.stopPropagation=function(){this.j=!0};
Dc.prototype.preventDefault=function(){this.defaultPrevented=!0};function Ec(a){var b=E("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Fc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Gc[c])c=Gc[c];else{c=String(c);if(!Gc[c]){var f=/function\s+([^\(]+)/m.exec(c);Gc[c]=f?f[1]:"[Anonymous]"}c=Gc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Fc(a,b){b||(b={});b[Hc(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Hc(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Fc(a,b));return c}
function Hc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Gc={};var Ic=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();function Jc(){return Lb?!!Pb&&!!Pb.platform:!1}
function Kc(){return F("iPhone")&&!F("iPod")&&!F("iPad")}
;function Lc(a){Lc[" "](a);return a}
Lc[" "]=function(){};var Mc=Tb(),Nc=Ub(),Oc=F("Edge"),Pc=F("Gecko")&&!(-1!=Ob().toLowerCase().indexOf("webkit")&&!F("Edge"))&&!(F("Trident")||F("MSIE"))&&!F("Edge"),Qc=-1!=Ob().toLowerCase().indexOf("webkit")&&!F("Edge");Qc&&F("Mobile");Jc()||F("Macintosh");Jc()||F("Windows");(Jc()?"Linux"===Pb.platform:F("Linux"))||Jc()||F("CrOS");var Rc=C.navigator||null;Rc&&(Rc.appVersion||"").indexOf("X11");var Sc=Jc()?"Android"===Pb.platform:F("Android");Kc();F("iPad");F("iPod");Kc()||F("iPad")||F("iPod");Ob().toLowerCase().indexOf("kaios");
function Tc(){var a=C.document;return a?a.documentMode:void 0}
var Uc;a:{var Vc="",Wc=function(){var a=Ob();if(Pc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Oc)return/Edge\/([\d\.]+)/.exec(a);if(Nc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Qc)return/WebKit\/(\S+)/.exec(a);if(Mc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Wc&&(Vc=Wc?Wc[1]:"");if(Nc){var Xc=Tc();if(null!=Xc&&Xc>parseFloat(Vc)){Uc=String(Xc);break a}}Uc=Vc}var Yc=Uc,Zc;if(C.document&&Nc){var $c=Tc();Zc=$c?$c:parseInt(Yc,10)||void 0}else Zc=void 0;var ad=Zc;function bd(a,b){Dc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Va(bd,Dc);var cd={2:"touch",3:"pen",4:"mouse"};
bd.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Pc){a:{try{Lc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:cd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&bd.va.preventDefault.call(this)};
bd.prototype.stopPropagation=function(){bd.va.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
bd.prototype.preventDefault=function(){bd.va.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var dd="closure_listenable_"+(1E6*Math.random()|0);var ed=0;function fd(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.hc=e;this.key=++ed;this.Sb=this.ac=!1}
function gd(a){a.Sb=!0;a.listener=null;a.proxy=null;a.src=null;a.hc=null}
;function hd(a){this.src=a;this.listeners={};this.h=0}
hd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=id(a,b,d,e);-1<g?(b=a[g],c||(b.ac=!1)):(b=new fd(b,this.src,f,!!d,e),b.ac=c,a.push(b));return b};
hd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=id(e,b,c,d);return-1<b?(gd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function jd(a,b){var c=b.type;c in a.listeners&&gb(a.listeners[c],b)&&(gd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function id(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Sb&&f.listener==b&&f.capture==!!c&&f.hc==d)return e}return-1}
;var kd="closure_lm_"+(1E6*Math.random()|0),ld={},md=0;function nd(a,b,c,d,e){if(d&&d.once)od(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)nd(a,b[f],c,d,e);else c=pd(c),a&&a[dd]?a.listen(b,c,Na(d)?!!d.capture:!!d,e):qd(a,b,c,!1,d,e)}
function qd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Na(e)?!!e.capture:!!e,h=rd(a);h||(a[kd]=h=new hd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=sd();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ic||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(td(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");md++}}
function sd(){function a(c){return b.call(a.src,a.listener,c)}
var b=ud;return a}
function od(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)od(a,b[f],c,d,e);else c=pd(c),a&&a[dd]?a.l.add(String(b),c,!0,Na(d)?!!d.capture:!!d,e):qd(a,b,c,!0,d,e)}
function vd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)vd(a,b[f],c,d,e);else(d=Na(d)?!!d.capture:!!d,c=pd(c),a&&a[dd])?a.l.remove(String(b),c,d,e):a&&(a=rd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=id(b,c,d,e)),(c=-1<a?b[a]:null)&&wd(c))}
function wd(a){if("number"!==typeof a&&a&&!a.Sb){var b=a.src;if(b&&b[dd])jd(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(td(c),d):b.addListener&&b.removeListener&&b.removeListener(d);md--;(c=rd(b))?(jd(c,a),0==c.h&&(c.src=null,b[kd]=null)):gd(a)}}}
function td(a){return a in ld?ld[a]:ld[a]="on"+a}
function ud(a,b){if(a.Sb)a=!0;else{b=new bd(b,this);var c=a.listener,d=a.hc||a.src;a.ac&&wd(a);a=c.call(d,b)}return a}
function rd(a){a=a[kd];return a instanceof hd?a:null}
var xd="__closure_events_fn_"+(1E9*Math.random()>>>0);function pd(a){if("function"===typeof a)return a;a[xd]||(a[xd]=function(b){return a.handleEvent(b)});
return a[xd]}
;function yd(){G.call(this);this.l=new hd(this);this.Lb=this;this.Qa=null}
Va(yd,G);yd.prototype[dd]=!0;m=yd.prototype;m.addEventListener=function(a,b,c,d){nd(this,a,b,c,d)};
m.removeEventListener=function(a,b,c,d){vd(this,a,b,c,d)};
function zd(a,b){var c=a.Qa;if(c){var d=[];for(var e=1;c;c=c.Qa)d.push(c),++e}a=a.Lb;c=b.type||b;"string"===typeof b?b=new Dc(b,a):b instanceof Dc?b.target=b.target||a:(e=b,b=new Dc(c,a),sb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Ad(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Ad(g,c,!0,b)&&e,b.j||(e=Ad(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Ad(g,c,!1,b)&&e}
m.M=function(){yd.va.M.call(this);this.removeAllListeners();this.Qa=null};
m.listen=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
m.removeAllListeners=function(a){if(this.l){var b=this.l;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,gd(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function Ad(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Sb&&g.capture==c){var h=g.listener,k=g.hc||g.src;g.ac&&jd(a.l,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Bd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Bd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Cd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function Dd(a,b){return a+Math.random()*(b-a)}
;function Ed(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=Ed.prototype;m.clone=function(){return new Ed(this.x,this.y)};
m.equals=function(a){return a instanceof Ed&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function Fd(a,b){this.width=a;this.height=b}
m=Fd.prototype;m.clone=function(){return new Fd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Gd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Hd(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function Id(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Jd;function Kd(){var a=C.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!F("Presto")&&(a=function(){var e=Hd("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ta(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Ub()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.ed;c.ed=null;e()}};
return function(e){d.next={ed:e};d=d.next;b.port2.postMessage(0)}}return function(e){C.setTimeout(e,0)}}
;function Ld(a){C.setTimeout(function(){throw a;},0)}
;function Md(){this.i=this.h=null}
Md.prototype.add=function(a,b){var c=Nd.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Md.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Nd=new Bd(function(){return new Od},function(a){return a.reset()});
function Od(){this.next=this.scope=this.fn=null}
Od.prototype.set=function(a,b){this.fn=a;this.scope=b;this.next=null};
Od.prototype.reset=function(){this.next=this.scope=this.fn=null};var Pd,Qd=!1,Rd=new Md;function Sd(a,b){Pd||Td();Qd||(Pd(),Qd=!0);Rd.add(a,b)}
function Td(){if(C.Promise&&C.Promise.resolve){var a=C.Promise.resolve(void 0);Pd=function(){a.then(Ud)}}else Pd=function(){var b=Ud;
"function"!==typeof C.setImmediate||C.Window&&C.Window.prototype&&(Sb()||!F("Edge"))&&C.Window.prototype.setImmediate==C.setImmediate?(Jd||(Jd=Kd()),Jd(b)):C.setImmediate(b)}}
function Ud(){for(var a;a=Rd.remove();){try{a.fn.call(a.scope)}catch(b){Ld(b)}Cd(Nd,a)}Qd=!1}
;function Vd(a){this.h=0;this.v=void 0;this.l=this.i=this.j=null;this.m=this.s=!1;if(a!=Za)try{var b=this;a.call(void 0,function(c){Wd(b,2,c)},function(c){Wd(b,3,c)})}catch(c){Wd(this,3,c)}}
function Xd(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
Xd.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Yd=new Bd(function(){return new Xd},function(a){a.reset()});
function Zd(a,b,c){var d=Yd.get();d.i=a;d.h=b;d.context=c;return d}
function $d(a){if(a instanceof Vd)return a;var b=new Vd(Za);Wd(b,2,a);return b}
function ae(a){return new Vd(function(b,c){c(a)})}
function be(a,b,c){ce(a,b,c,null)||Sd(Ua(b,a))}
function de(a){return new Vd(function(b){var c=a.length,d=[];if(c)for(var e=function(h,k,l){c--;d[h]=k?{fulfilled:!0,value:l}:{fulfilled:!1,reason:l};0==c&&b(d)},f=0,g;f<a.length;f++)g=a[f],be(g,Ua(e,f,!0),Ua(e,f,!1));
else b(d)})}
Vd.prototype.then=function(a,b,c){return ee(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Vd.prototype.$goog_Thenable=!0;m=Vd.prototype;m.sc=function(a,b){return ee(this,null,a,b)};
m.catch=Vd.prototype.sc;m.cancel=function(a){if(0==this.h){var b=new fe(a);Sd(function(){ge(this,b)},this)}};
function ge(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?ge(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):he(c),ie(c,e,3,b)))}a.j=null}else Wd(a,3,b)}
function je(a,b){a.i||2!=a.h&&3!=a.h||ke(a);a.l?a.l.next=b:a.i=b;a.l=b}
function ee(a,b,c,d){var e=Zd(null,null,null);e.child=new Vd(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof fe?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;je(a,e);return e.child}
m.bf=function(a){this.h=0;Wd(this,2,a)};
m.cf=function(a){this.h=0;Wd(this,3,a)};
function Wd(a,b,c){0==a.h&&(a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself")),a.h=1,ce(c,a.bf,a.cf,a)||(a.v=c,a.h=b,a.j=null,ke(a),3!=b||c instanceof fe||le(a,c)))}
function ce(a,b,c,d){if(a instanceof Vd)return je(a,Zd(b||Za,c||null,d)),!0;if(a)try{var e=!!a.$goog_Thenable}catch(g){e=!1}else e=!1;if(e)return a.then(b,c,d),!0;if(Na(a))try{var f=a.then;if("function"===typeof f)return me(a,f,b,c,d),!0}catch(g){return c.call(d,g),!0}return!1}
function me(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function ke(a){a.s||(a.s=!0,Sd(a.ee,a))}
function he(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
m.ee=function(){for(var a;a=he(this);)ie(this,a,this.h,this.v);this.s=!1};
function ie(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.child)b.child.j=null,ne(b,c,d);else try{b.j?b.i.call(b.context):ne(b,c,d)}catch(e){oe.call(null,e)}Cd(Yd,b)}
function ne(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function le(a,b){a.m=!0;Sd(function(){a.m&&oe.call(null,b)})}
var oe=Ld;function fe(a){Xa.call(this,a)}
Va(fe,Xa);fe.prototype.name="cancel";function pe(a,b){yd.call(this);this.j=a||1;this.i=b||C;this.m=Ta(this.af,this);this.s=Date.now()}
Va(pe,yd);m=pe.prototype;m.enabled=!1;m.Ca=null;m.setInterval=function(a){this.j=a;this.Ca&&this.enabled?(this.stop(),this.start()):this.Ca&&this.stop()};
m.af=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.j?this.Ca=this.i.setTimeout(this.m,this.j-a):(this.Ca&&(this.i.clearTimeout(this.Ca),this.Ca=null),zd(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
m.start=function(){this.enabled=!0;this.Ca||(this.Ca=this.i.setTimeout(this.m,this.j),this.s=Date.now())};
m.stop=function(){this.enabled=!1;this.Ca&&(this.i.clearTimeout(this.Ca),this.Ca=null)};
m.M=function(){pe.va.M.call(this);this.stop();delete this.i};
function qe(a,b,c){if("function"===typeof a)c&&(a=Ta(a,c));else if(a&&"function"==typeof a.handleEvent)a=Ta(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:C.setTimeout(a,b||0)}
;function re(a){G.call(this);this.P=a;this.j=new Map;this.v=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.i=new pe(this.flushInterval);this.i.listen("tick",this.pb,!1,this);Bc(this,this.i);this.s=!1}
w(re,G);m=re.prototype;m.sendIsolatedPayload=function(a){this.s=a;this.m=1};
function se(a){a.i.enabled||a.i.start();a.l++;a.l>=a.m&&a.pb()}
m.pb=function(){var a=this.j.values();a=[].concat(ia(a)).filter(function(b){return b.rb.size});
a.length&&this.P.flush(a,this.s);te(a);this.l=0;this.i.enabled&&this.i.stop()};
m.Zc=function(a){var b=B.apply(1,arguments);this.j.has(a)||this.j.set(a,new xc(a,b))};
m.bd=function(a){var b=B.apply(1,arguments);this.j.has(a)||this.j.set(a,new yc(a,b))};
function ue(a,b){return a.v.has(b)?void 0:a.j.get(b)}
m.uc=function(a){this.Qd.apply(this,[a,1].concat(ia(B.apply(1,arguments))))};
m.Qd=function(a,b){var c=B.apply(2,arguments),d=ue(this,a);d&&d instanceof xc&&(d.j(b,c),se(this))};
m.record=function(a,b){var c=B.apply(2,arguments),d=ue(this,a);d&&d instanceof yc&&(d.record(b,c),se(this))};
function te(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function ve(a){this.h=a;this.h.Zc("/client_streamz/bg/fiec",{ub:3,tb:"rk"},{ub:2,tb:"ec"},{ub:3,tb:"em"})}
function we(a,b,c,d){a.h.uc("/client_streamz/bg/fiec",b,c,d)}
function xe(a){this.h=a;this.h.bd("/client_streamz/bg/fil",{ub:3,tb:"rk"})}
xe.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fil",a,b)};
function ye(a){this.h=a;this.h.Zc("/client_streamz/bg/fsc",{ub:3,tb:"rk"})}
function ze(a){this.h=a;this.h.bd("/client_streamz/bg/fsl",{ub:3,tb:"rk"})}
ze.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fsl",a,b)};var Ae={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function Be(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=Ce(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=De(a,h),d+=De(a,h+4),e+=De(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return Ae.toString(e)}
function Ce(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function De(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;Vb();var Ee=Kc()||F("iPod"),Fe=F("iPad");!F("Android")||Wb()||Vb()||Tb()||F("Silk");Wb();var Ge=F("Safari")&&!(Wb()||(Sb()?0:F("Coast"))||Tb()||(Sb()?0:F("Edge"))||(Sb()?Rb("Microsoft Edge"):F("Edg/"))||(Sb()?Rb("Opera"):F("OPR"))||Vb()||F("Silk")||F("Android"))&&!(Kc()||F("iPad")||F("iPod"));var He={},Ie=null;function Je(a,b){Ma(a);void 0===b&&(b=0);Ke();b=He[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function Le(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;Me(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function Me(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),n=Ie[l];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
Ke();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function Ke(){if(!Ie){Ie={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));He[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===Ie[f]&&(Ie[f]=e)}}}}
;var Ne="undefined"!==typeof Uint8Array,Oe=!Nc&&"function"===typeof btoa;function Pe(a){if(!Oe)return Je(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var Qe=/[-_.]/g,Re={"-":"+",_:"/",".":"="};function Se(a){return Re[a]||""}
function Te(a){return Ne&&null!=a&&a instanceof Uint8Array}
var Ue={};var Ve;function We(a){if(a!==Ue)throw Error("illegal external caller");}
function Xe(a,b){We(b);this.value_=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Xe.prototype.isEmpty=function(){return null==this.value_};
Xe.prototype.sizeBytes=function(){We(Ue);var a=this.value_;if(null!=a&&!Te(a))if("string"===typeof a)if(Oe){Qe.test(a)&&(a=a.replace(Qe,Se));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=Le(a);else La(a),a=null;return(a=null==a?a:this.value_=a)?a.length:0};function Ye(a){return Array.prototype.slice.call(a)}
;var Ze="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;Math.max.apply(Math,ia(Object.values({Df:1,Cf:2,Bf:4,Gf:8,Ff:16,Ef:32,tf:64,Hf:128,zf:256,yf:512,Af:1024})));var $e=Ze?function(a,b){a[Ze]|=b}:function(a,b){void 0!==a.Aa?a.Aa|=b:Object.defineProperties(a,{Aa:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function af(a){var b=bf(a);1!==(b&1)&&(Object.isFrozen(a)&&(a=Ye(a)),cf(a,b|1));return a}
var df=Ze?function(a,b){a[Ze]&=~b}:function(a,b){void 0!==a.Aa&&(a.Aa&=~b)},bf=Ze?function(a){return a[Ze]|0}:function(a){return a.Aa|0},ef=Ze?function(a){return a[Ze]}:function(a){return a.Aa},cf=Ze?function(a,b){a[Ze]=b}:function(a,b){void 0!==a.Aa?a.Aa=b:Object.defineProperties(a,{Aa:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function ff(a,b){Object.isFrozen(a)&&(a=Ye(a));cf(a,b);return a}
function gf(a){$e(a,1);return a}
function hf(a,b){cf(b,(a|0)&-99)}
function jf(a,b){cf(b,(a|34)&-73)}
function kf(a){a=a>>11&1023;return 0===a?536870912:a}
;var lf={};function mf(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var nf,of,pf=[];cf(pf,39);of=Object.freeze(pf);function qf(a){if(a&2)throw Error();}
;function rf(a){return a.displayName||a.name||"unknown type name"}
function sf(a){if(null!=a){if("boolean"!==typeof a)throw Error("Expected boolean but got "+La(a)+": "+a);a=!!a}return a}
function tf(a){if(null!=a&&"number"!==typeof a)throw Error();return a}
function uf(a){if(null==a)return a;if("string"===typeof a){if(!a)return;a=+a}return"number"===typeof a?a:void 0}
function vf(a){if(null!=a&&"string"!==typeof a)throw Error();return a}
function wf(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+rf(b)+" but got "+(a&&rf(a.constructor)));}
function xf(a,b,c){var d=!1;if(null!=a&&"object"===typeof a&&!(d=Array.isArray(a))&&a.Mc===lf)return a;if(d){var e=d=bf(a);0===e&&(e|=c&32);e|=c&2;e!==d&&cf(a,e);return new b(a)}}
;var yf;function zf(a,b){bf(b);yf=b;a=new a(b);yf=void 0;return a}
function Af(a,b,c){null==a&&(a=yf);yf=void 0;if(null==a){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-2095105|(b&1023)<<11)}else{if(!Array.isArray(a))throw Error();d=bf(a);if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error();a:{c=a;var e=c.length;if(e){var f=e-1,g=c[f];if(mf(g)){d|=256;b=(d>>9&1)-1;e=f-b;1024<=e&&(Bf(c,b,g),e=1023);d=d&-2095105|(e&1023)<<11;break a}}b&&(g=(d>>9&1)-1,b=Math.max(b,e-g),1024<b&&(Bf(c,g,{}),d|=256,b=1023),d=d&-2095105|(b&1023)<<11)}}cf(a,d);return a}
function Bf(a,b,c){for(var d=1023+b,e=a.length,f=d;f<e;f++){var g=a[f];null!=g&&g!==c&&(c[f-b]=g)}a.length=d+1;a[d]=c}
;function Cf(a,b){return Df(b)}
function Df(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a&&!Array.isArray(a)){if(Te(a))return Pe(a);if(a instanceof Xe){var b=a.value_;return null==b?"":"string"===typeof b?b:a.value_=Pe(b)}}}return a}
;function Ef(a,b,c){a=Ye(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function Ff(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&bf(a)&1?void 0:f&&bf(a)&2?a:Gf(a,b,c,void 0!==d,e,f);else if(mf(a)){var g={},h;for(h in a)g[h]=Ff(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function Gf(a,b,c,d,e,f){var g=d||c?bf(a):0;d=d?!!(g&32):void 0;a=Ye(a);for(var h=0;h<a.length;h++)a[h]=Ff(a[h],b,c,d,e,f);c&&c(g,a);return a}
function Hf(a){return a.Mc===lf?a.toJSON():Df(a)}
;function If(a,b,c){c=void 0===c?jf:c;if(null!=a){if(Ne&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=bf(a);if(d&2)return a;if(b&&!(d&64)&&(d&32||0===d))return cf(a,d|34),a;a=Gf(a,If,d&4?jf:c,!0,!1,!0);b=bf(a);b&4&&b&2&&Object.freeze(a);return a}a.Mc===lf&&(b=a.B,c=ef(b),a=c&2?a:zf(a.constructor,Jf(b,c,!0)));return a}}
function Jf(a,b,c){var d=c||b&2?jf:hf,e=!!(b&32);a=Ef(a,b,function(f){return If(f,e,d)});
$e(a,32|(c?2:0));return a}
function Kf(a){var b=a.B,c=ef(b);return c&2?zf(a.constructor,Jf(b,c,!1)):a}
;function Lf(a,b){a=a.B;return Mf(a,ef(a),b)}
function Mf(a,b,c,d){if(-1===c)return null;if(c>=kf(b)){if(b&256)return a[a.length-1][c]}else{var e=a.length;if(d&&b&256&&(d=a[e-1][c],null!=d))return d;b=c+((b>>9&1)-1);if(b<e)return a[b]}}
function J(a,b,c,d){var e=a.B,f=ef(e);qf(f);Nf(e,f,b,c,d);return a}
function Nf(a,b,c,d,e){mf(d);var f=kf(b);if(c>=f||e){e=b;if(b&256)f=a[a.length-1];else{if(null==d)return;f=a[f+((b>>9&1)-1)]={};e|=256}f[c]=d;e&=-1025;e!==b&&cf(a,e)}else a[c+((b>>9&1)-1)]=d,b&256&&(d=a[a.length-1],c in d&&delete d[c]),b&1024&&cf(a,b&-1025)}
function Of(a){return void 0!==Pf(a,Qf,11,!1)}
function Rf(a,b,c,d){a=a.B;var e=ef(a);qf(e);for(var f=0,g=0;g<c.length;g++){var h=c[g];null!=Mf(a,e,h)&&(0!==f&&Nf(a,e,f),f=h)}(c=f)&&c!==b&&null!=d&&Nf(a,e,c);Nf(a,e,b,d)}
function Pf(a,b,c,d){a=a.B;var e=ef(a),f=Mf(a,e,c,d);b=xf(f,b,e);b!==f&&null!=b&&Nf(a,e,c,b,d);return b}
function Sf(a,b,c,d){d=void 0===d?!1:d;b=Pf(a,b,c,d);if(null==b)return b;a=a.B;var e=ef(a);if(!(e&2)){var f=Kf(b);f!==b&&(b=f,Nf(a,e,c,b,d))}return b}
function Tf(a,b,c,d){null!=d?wf(d,b):d=void 0;return J(a,c,d)}
function Uf(a,b,c,d){var e=a.B,f=ef(e);qf(f);if(null!=d){for(var g=!!d.length,h=0;h<d.length;h++){var k=d[h];wf(k,b);g=g&&!(bf(k.B)&2)}b=bf(d);h=b|1;h=(g?h|8:h&-9)|4;h!=b&&(d=ff(d,h))}null==d&&(d=void 0);Nf(e,f,c,d);return a}
function Vf(){var a=new Wf;return J(a,1,1)}
;function Xf(a,b,c){this.B=Af(a,b,c)}
m=Xf.prototype;m.toJSON=function(){if(nf)var a=Yf(this,this.B,!1);else a=Gf(this.B,Hf,void 0,void 0,!1,!1),a=Yf(this,a,!0);return a};
m.serialize=function(){nf=!0;try{return JSON.stringify(this.toJSON(),Cf)}finally{nf=!1}};
m.clone=function(){var a=this.B,b=ef(a);return zf(this.constructor,Jf(a,b,!1))};
m.Mc=lf;m.toString=function(){return Yf(this,this.B,!1).toString()};
function Yf(a,b,c){var d=a.constructor.Va,e=ef(c?a.B:b),f=kf(e);e=!1;if(d){if(!c){b=Ye(b);var g;if(b.length&&mf(g=b[b.length-1]))for(e=0;e<d.length;e++)if(d[e]>=f){Object.assign(b[b.length-1]={},g);break}e=!0}g=b;c=!c;f=ef(a.B);a=kf(f);f=(f>>9&1)-1;for(var h,k,l=0;l<d.length;l++)if(k=d[l],k<a){k+=f;var n=g[k];null==n?g[k]=c?of:gf([]):c&&n!==of&&af(n)}else h||(n=void 0,g.length&&mf(n=g[g.length-1])?h=n:g.push(h={})),n=h[k],null==h[k]?h[k]=c?of:gf([]):c&&n!==of&&af(n)}d=b.length;if(!d)return b;var p;
if(mf(h=b[d-1])){a:{var t=h;g={};c=!1;for(var r in t)a=t[r],Array.isArray(a)&&a!=a&&(c=!0),null!=a?g[r]=a:c=!0;if(c){for(var x in g){t=g;break a}t=null}}t!=h&&(p=!0);d--}for(;0<d;d--){h=b[d-1];if(null!=h)break;var y=!0}if(!p&&!y)return b;var z;e?z=b:z=Array.prototype.slice.call(b,0,d);b=z;e&&(b.length=d);t&&b.push(t);return b}
;function Zf(a){this.B=Af(a)}
w(Zf,Xf);var $f=[1,2,3];function ag(a){this.B=Af(a)}
w(ag,Xf);var bg=[1,2,3];function cg(a){this.B=Af(a)}
w(cg,Xf);cg.Va=[1];function dg(a){this.B=Af(a)}
w(dg,Xf);dg.Va=[3,6,4];function eg(a){this.B=Af(a)}
w(eg,Xf);eg.Va=[1];function fg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function gg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var t=g,r=0;64>r;r+=4)t[r/4]=p[r]<<24|p[r+1]<<16|p[r+2]<<8|p[r+3];for(r=16;80>r;r++)p=t[r-3]^t[r-8]^t[r-14]^t[r-16],t[r]=(p<<1|p>>>31)&4294967295;p=e[0];var x=e[1],y=e[2],z=e[3],H=e[4];for(r=0;80>r;r++){if(40>r)if(20>r){var I=z^x&(y^z);var M=1518500249}else I=x^y^z,M=1859775393;else 60>r?(I=x&y|z&(x|y),M=2400959708):(I=x^y^z,M=3395469782);I=((p<<5|p>>>27)&4294967295)+I+H+M+t[r]&4294967295;H=z;z=y;y=(x<<30|x>>>2)&4294967295;x=p;p=I}e[0]=e[0]+p&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+H&4294967295}
function c(p,t){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var r=[],x=0,y=p.length;x<y;++x)r.push(p.charCodeAt(x));p=r}t||(t=p.length);r=0;if(0==l)for(;r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64;for(;r<t;)if(f[l++]=p[r++],n++,64==l)for(l=0,b(f);r+64<t;)b(p.slice(r,r+64)),r+=64,n+=64}
function d(){var p=[],t=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var r=63;56<=r;r--)f[r]=t&255,t>>>=8;b(f);for(r=t=0;5>r;r++)for(var x=24;0<=x;x-=8)p[t++]=e[r]>>x&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,ae:function(){for(var p=d(),t="",r=0;r<p.length;r++)t+="0123456789ABCDEF".charAt(Math.floor(p[r]/16))+"0123456789ABCDEF".charAt(p[r]%16);return t}}}
;function hg(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,ig(fg(d),a,c||null)].join(" "):null}
function ig(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],bb(d,function(h){e.push(h)}),jg(e.join(" "));
var f=[],g=[];bb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];bb(d,function(h){e.push(h)});
a=jg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function jg(a){var b=gg();b.update(a);return b.ae().toLowerCase()}
;var kg={};function lg(a){this.h=a||{cookie:""}}
m=lg.prototype;m.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{kc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Yf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.kc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Eb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{kc:0,path:b,domain:c});return d};
m.Fc=function(){return mg(this).keys};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=mg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function mg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Eb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var ng=new lg("undefined"==typeof document?null:document);function og(a){return!!kg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function pg(a){a=void 0===a?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;og(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if("undefined"!==typeof document){var c=new lg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");og(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function qg(a,b,c,d){(a=C[a])||"undefined"===typeof document||(a=(new lg(document)).get(b));return a?hg(a,c,d):null}
function rg(a,b){b=void 0===b?!1:b;var c=fg(String(C.location.href)),d=[];if(pg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?C.__SAPISID:C.__APISID;e||"undefined"===typeof document||(e=new lg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?hg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&og(b)&&((b=qg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=qg("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return 0==d.length?null:d.join(" ")}
;function sg(a){this.B=Af(a)}
w(sg,Xf);sg.Va=[2];function tg(a){this.B=Af(a)}
w(tg,Xf);function ug(a){this.B=Af(a)}
w(ug,Xf);function vg(a){this.h=this.i=this.j=a}
vg.prototype.reset=function(){this.h=this.i=this.j};
vg.prototype.getValue=function(){return this.i};function wg(){}
wg.prototype.serialize=function(a){var b=[];xg(this,a,b);return b.join("")};
function xg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),xg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),yg(d,c),c.push(":"),xg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":yg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Ag={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Bg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function yg(a,b){b.push('"',a.replace(Bg,function(c){var d=Ag[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Ag[c]=d);return d}),'"')}
;function Cg(){}
Cg.prototype.h=null;Cg.prototype.getOptions=function(){var a;(a=this.h)||(a={},Dg(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Eg;function Fg(){}
Va(Fg,Cg);function Gg(a){return(a=Dg(a))?new ActiveXObject(a):new XMLHttpRequest}
function Dg(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Eg=new Fg;function Hg(a){yd.call(this);this.headers=new Map;this.W=a||null;this.i=!1;this.V=this.H=null;this.m=this.ja="";this.j=this.ba=this.v=this.Z=!1;this.s=0;this.P=null;this.Ha="";this.wa=this.xa=!1}
Va(Hg,yd);var Ig=/^https?$/i,Jg=["POST","PUT"],Kg=[];function Lg(a,b,c,d,e,f,g){var h=new Hg;Kg.push(h);b&&h.listen("complete",b);h.l.add("ready",h.Zd,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.xa=g);h.send(a,c,d,e)}
m=Hg.prototype;m.Zd=function(){this.dispose();gb(Kg,this)};
m.send=function(a,b,c,d){if(this.H)throw Error("[goog.net.XhrIo] Object is active with another request="+this.ja+"; newUri="+a);b=b?b.toUpperCase():"GET";this.ja=a;this.m="";this.Z=!1;this.i=!0;this.H=this.W?Gg(this.W):Gg(Eg);this.V=this.W?this.W.getOptions():Eg.getOptions();this.H.onreadystatechange=Ta(this.vd,this);try{this.getStatus(),this.ba=!0,this.H.open(b,String(a),!0),this.ba=!1}catch(g){this.getStatus();Mg(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===
Object.prototype)for(var e in d)c.set(e,d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=v(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(0<=ab(Jg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=v(c);for(d=b.next();!d.done;d=b.next())c=v(d.value),d=c.next().value,c=c.next().value,this.H.setRequestHeader(d,c);this.Ha&&(this.H.responseType=this.Ha);"withCredentials"in this.H&&this.H.withCredentials!==this.xa&&(this.H.withCredentials=this.xa);try{Ng(this),0<this.s&&(this.wa=Og(this.H),this.getStatus(),this.wa?(this.H.timeout=this.s,this.H.ontimeout=Ta(this.Jd,
this)):this.P=qe(this.Jd,this.s,this)),this.getStatus(),this.v=!0,this.H.send(a),this.v=!1}catch(g){this.getStatus(),Mg(this,g)}};
function Og(a){return Nc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
m.Jd=function(){"undefined"!=typeof Ka&&this.H&&(this.m="Timed out after "+this.s+"ms, aborting",this.getStatus(),zd(this,"timeout"),this.abort(8))};
function Mg(a,b){a.i=!1;a.H&&(a.j=!0,a.H.abort(),a.j=!1);a.m=b;Pg(a);Qg(a)}
function Pg(a){a.Z||(a.Z=!0,zd(a,"complete"),zd(a,"error"))}
m.abort=function(){this.H&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.H.abort(),this.j=!1,zd(this,"complete"),zd(this,"abort"),Qg(this))};
m.M=function(){this.H&&(this.i&&(this.i=!1,this.j=!0,this.H.abort(),this.j=!1),Qg(this,!0));Hg.va.M.call(this)};
m.vd=function(){this.h()||(this.ba||this.v||this.j?Rg(this):this.De())};
m.De=function(){Rg(this)};
function Rg(a){if(a.i&&"undefined"!=typeof Ka)if(a.V[1]&&4==Sg(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==Sg(a))qe(a.vd,0,a);else if(zd(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(Tg(a))zd(a,"complete"),zd(a,"success");else{try{var b=2<Sg(a)?a.H.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";Pg(a)}}finally{Qg(a)}}}
function Qg(a,b){if(a.H){Ng(a);var c=a.H,d=a.V[0]?function(){}:null;
a.H=null;a.V=null;b||zd(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Ng(a){a.H&&a.wa&&(a.H.ontimeout=null);a.P&&(C.clearTimeout(a.P),a.P=null)}
m.isActive=function(){return!!this.H};
m.isComplete=function(){return 4==Sg(this)};
function Tg(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=fc(1,String(a.ja)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!Ig.test(a?a.toLowerCase():"");c=b}return c}
function Sg(a){return a.H?a.H.readyState:0}
m.getStatus=function(){try{return 2<Sg(this)?this.H.status:-1}catch(a){return-1}};
m.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function Ug(a){this.B=Af(a)}
w(Ug,Xf);function Vg(a){this.B=Af(a)}
w(Vg,Xf);Vg.Va=[1];function Qf(a){this.B=Af(a)}
w(Qf,Xf);var Wg=["platform","platformVersion","architecture","model","uaFullVersion"];new Vg;function Wf(a){this.B=Af(a)}
w(Wf,Xf);function Xg(a){this.B=Af(a)}
w(Xg,Xf);function Yg(a){this.B=Af(a,34)}
w(Yg,Xf);Yg.Va=[3,20,27];function Zg(a){this.B=Af(a,19)}
w(Zg,Xf);Zg.Va=[3,5];function $g(a){this.B=Af(a,6)}
w($g,Xf);var ah=function(a){return function(b){if(null==b||""==b)b=new a;else{b=JSON.parse(b);if(!Array.isArray(b))throw Error(void 0);$e(b,32);b=zf(a,b)}return b}}($g);
$g.Va=[5];function bh(a){this.B=Af(a)}
w(bh,Xf);var ch;ch=new function(a,b,c){this.h=a;this.fieldName=b;this.ctor=c;this.isRepeated=0;this.i=Sf;this.defaultValue=void 0}(175237375,{Qf:0},bh);function dh(a){yd.call(this);var b=this;this.componentId="";this.j=[];this.xa="";this.Ha=this.ja=-1;this.wa=!1;this.V=this.experimentIds=null;this.P=this.s=0;this.Xb=1;this.timeoutMillis=0;this.W=!1;yd.call(this);this.logSource=a.logSource;this.vb=a.vb||function(){};
this.m=new eh(a.logSource,a.yb);this.Cb=a.Cb;this.network=a.network;this.Fb=a.Fb||null;this.bufferSize=1E3;this.vc=Ua(Dd,0,1);this.ba=a.df||null;this.sessionIndex=a.sessionIndex||null;this.Ob=a.Ob||!1;this.pageId=a.pageId||null;this.logger=null;this.withCredentials=!a.jd;this.yb=a.yb||!1;var c=Vf();fh(this.m,c);this.v=new vg(1E4);this.i=new pe(this.v.getValue());Bc(this,this.i);a=gh(this,a.Vd);nd(this.i,"tick",a,!1,this);this.Z=new pe(6E5);Bc(this,this.Z);nd(this.Z,"tick",a,!1,this);this.Ob||this.Z.start();
this.yb||(nd(document,"visibilitychange",function(){"hidden"===document.visibilityState&&b.Ac()}),nd(document,"pagehide",this.Ac,!1,this))}
w(dh,yd);function gh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
m=dh.prototype;m.M=function(){this.Ac();yd.prototype.M.call(this)};
function hh(a){a.ba||(a.ba=.01>a.vc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.ba}
function ih(a,b){a.v=new vg(1>b?1:b);a.i.setInterval(a.v.getValue())}
m.log=function(a){a=a.clone();var b=this.Xb++;a=J(a,21,b);this.componentId&&J(a,26,vf(this.componentId));if(!Lf(a,1)){b=a;var c=Date.now().toString();J(b,1,c)}null==Lf(a,15)&&J(a,15,60*(new Date).getTimezoneOffset());this.experimentIds&&(b=this.experimentIds.clone(),Tf(a,sg,16,b));b=this.j.length-this.bufferSize+1;0<b&&(this.j.splice(0,b),this.s+=b);this.j.push(a);zd(this,new jh(a));this.Ob||this.i.enabled||this.i.start()};
m.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.W)kh(this.m,3),lh(this);else{var d=Date.now();if(this.Ha>d&&this.ja<d)b&&b("throttled");else{kh(this.m,1);var e=mh(this.m,this.j,this.s,this.P,this.Fb);d={};var f=this.vb();f&&(d.Authorization=f);var g=hh(this);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,g=qc(g,"authuser",this.sessionIndex));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=qc(g,"pageId",this.pageId));if(f&&this.xa===f)b&&b("stale-auth-token");else{this.j=
[];this.i.enabled&&this.i.stop();this.s=0;var h=e.serialize(),k;this.V&&this.V.isSupported(h.length)&&(k=this.V.compress(h));var l={url:g,body:h,Xd:1,Qc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(r){c.v.reset();c.i.setInterval(c.v.getValue());if(r){var x=null;try{var y=JSON.stringify(JSON.parse(r.replace(")]}'\n","")));x=ah(y)}catch(H){}if(x){r=Number;y="-1";y=void 0===y?"0":y;var z=Lf(x,1);r=r(null!=z?z:y);0<r&&(c.ja=Date.now(),c.Ha=c.ja+
r);x=ch.ctor?ch.i(x,ch.ctor,ch.h,!0):ch.i(x,ch.h,null,!0);if(r=null===x?void 0:x)x=-1,x=void 0===x?0:x,r=uf(Lf(r,1)),x=null!=r?r:x,-1!==x&&(c.wa||ih(c,x))}}a&&a();c.P=0},p=function(r,x){var y=e.B,z=ef(y),H=!!(z&2);
var I=H?1:2,M=!!(z&2);var L=z&2;var K=Mf(y,z,3);Array.isArray(K)||(K=of);var V=bf(K);V&1||gf(K);L?V&2||$e(K,34):V&32&&!(V&2)&&df(K,32);L=K;if(L!==of&&bf(L)&4)3!==I&&(M?2===I&&(I=bf(L),L=Ye(L),cf(L,I),Nf(y,z,3,L)):(M=Object.isFrozen(L),1===I?M||Object.freeze(L):(I=bf(L),K=I&-35,M&&(L=Ye(L),I=0,Nf(y,z,3,L)),I!==K&&cf(L,K)))),y=L;else{K=L;L=!!(z&2);var Z=!!(bf(K)&2);M=K;!L&&Z&&(K=Ye(K));V=z|(Z?2:0);Z=Z||void 0;for(var ea=0,ra=0;ea<K.length;ea++){var oa=xf(K[ea],Yg,V);void 0!==oa&&(Z=Z||ef(oa.B)&2,K[ra++]=
oa)}ra<ea&&(K.length=ra);Z=!Z;V=bf(K);ea=V|5;Z=Z?ea|8:ea&-9;V!=Z&&(K=ff(K,Z));M!==K&&Nf(y,z,3,K);(L&&2!==I||1===I)&&Object.freeze(K);y=K}if(!(H||bf(y)&8)){for(H=0;H<y.length;H++)z=y[H],I=Kf(z),z!==I&&(y[H]=I);$e(y,8)}H=Lf(e,14);z=c.v;z.h=Math.min(3E5,2*z.h);z.i=Math.min(3E5,z.h+Math.round(.2*(Math.random()-.5)*z.h));c.i.setInterval(c.v.getValue());401===r&&f&&(c.xa=f);H&&(c.s+=H);void 0===x&&(x=c.isRetryable(r));x&&(c.j=y.concat(c.j),c.Ob||c.i.enabled||c.i.start());b&&b("net-send-failed",r);++c.P},
t=function(){c.network?c.network.send(l,n,p):c.Cb&&c.Cb(l,n,p)};
k?k.then(function(r){l.Qc["Content-Encoding"]="gzip";l.Qc["Content-Type"]="application/binary";l.body=r;l.Xd=2;t()},function(){t()}):t()}}}};
m.Ac=function(){nh(this.m,!0);this.flush();nh(this.m,!1)};
function lh(a){oh(a,function(b,c){b=qc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,c.serialize())}catch(e){}a.W&&!d&&(a.W=!1);return d})}
function oh(a,b){if(0!==a.j.length){var c=uc(hh(a),"format");c=oc(c,"auth",a.vb(),"authuser",a.sessionIndex||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=mh(a.m,e,a.s,a.P,a.Fb);if(!b(c,f)){++a.P;break}a.s=0;a.P=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
m.isRetryable=function(a){return 500<=a&&600>a||401===a||0===a};
function jh(){Dc.call(this,"event-logged",void 0)}
w(jh,Dc);function eh(a,b){this.yb=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new Zg;Number.isInteger(a)&&J(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));fh(this,new Wf)}
function fh(a,b){Tf(a.h,Wf,1,b);var c=Lf(b,1);(null==c?c:c)||J(b,1,1);a.yb||(b=ph(a),c=Lf(b,5),(null==c||"string"===typeof c)&&c||J(b,5,vf(a.locale)));a.uach&&(b=ph(a),Sf(b,Vg,9)||Tf(b,Vg,9,a.uach))}
function kh(a,b){Of(Sf(a.h,Wf,1))&&(a=qh(a),J(a,1,b))}
function nh(a,b){Of(Sf(a.h,Wf,1))&&(a=qh(a),J(a,2,sf(b)))}
function rh(a,b){var c=void 0===c?Wg:c;b(window,c).then(function(d){a.uach=d;d=ph(a);Tf(d,Vg,9,a.uach);return!0}).catch(function(){return!1})}
function ph(a){a=Sf(a.h,Wf,1);var b=Sf(a,Qf,11);b||(b=new Qf,Tf(a,Qf,11,b));return b}
function qh(a){a=ph(a);var b=Sf(a,Ug,10);b||(b=new Ug,J(b,2,sf(!1)),Tf(a,Ug,10,b));return b}
function mh(a,b,c,d,e){c=void 0===c?0:c;d=void 0===d?0:d;if(Of(Sf(a.h,Wf,1))){var f=qh(a);J(f,3,tf(d))}a=a.h.clone();d=Date.now().toString();a=J(a,4,d);b=Uf(a,Yg,3,b);e&&(a=new tg,e=J(a,13,tf(e)),a=new ug,e=Tf(a,tg,2,e),a=new Xg,e=Tf(a,ug,1,e),Tf(b,Xg,18,e));c&&J(b,14,c);return b}
;function sh(a,b,c){Lg(a.url,function(d){d=d.target;if(Tg(d)){try{var e=d.H?d.H.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Qc,a.timeoutMillis,a.withCredentials)}
;function th(a,b){G.call(this);this.logSource=a;this.sessionIndex=b;this.j="https://play.google.com/log?format=json&hasfast=true";this.l=!1;this.componentId="";this.Cb=sh}
w(th,G);th.prototype.jd=function(){this.Z=!0;return this};function uh(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;G.call(this);f?a=f:(a=new th(a,"0"),a.componentId=b,Bc(this,a),""!=c&&(a.j=c),d&&(a.l=!0),e&&(a.i=e),b=new dh({logSource:a.logSource,vb:a.vb?a.vb:rg,sessionIndex:a.sessionIndex,Cb:a.Cb,df:a.j,yb:a.l,Ob:!1,jd:a.Z,pageId:void 0,Vd:void 0,network:a.network?a.network:void 0}),Bc(a,b),a.v&&fh(b.m,a.v),a.i&&(c=a.i,d=ph(b.m),J(d,7,vf(c))),a.s&&(b.V=a.s),a.componentId&&(b.componentId=a.componentId),
a.Fb&&(b.Fb=a.Fb),a.m&&((c=a.m)?(b.experimentIds||(b.experimentIds=new sg),c=c.serialize(),J(b.experimentIds,4,vf(c))):b.experimentIds&&J(b.experimentIds,4,void 0,!1)),a.V&&(e=a.V,b.experimentIds||(b.experimentIds=new sg),c=b.experimentIds.B,d=ef(c),qf(d),e=null==e?of:af(e),Nf(c,d,2,e)),a.P&&(c=a.P,b.wa=!0,ih(b,c)),a.W&&rh(b.m,a.W),a=b);this.i=a}
w(uh,G);
uh.prototype.flush=function(a){var b=a||[];if(b.length){a=new eg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new dg;g=J(g,1,vf(f.i));for(var h=f,k=[],l=0;l<h.h.length;l++)k.push(h.h[l].tb);h=g.B;l=ef(h);qf(l);if(null==k)Nf(h,l,3);else{var n=bf(k);if(!(n&4)){if(n&2||Object.isFrozen(k))k=Ye(k);for(var p=0;p<k.length;p++){var t=k,r=p,x=k[p];if("string"!==typeof x)throw Error();t[r]=x}cf(k,n|5)}Nf(h,l,3,k)}k=[];h=[];l=v(f.rb.keys());for(n=l.next();!n.done;n=l.next())h.push(n.value.split(","));for(l=
0;l<h.length;l++){n=h[l];p=f.l;t=f.Cc(n)||[];r=[];for(x=0;x<t.length;x++){var y=t[x],z=y&&y.gd;y=new ag;switch(p){case 3:Rf(y,1,bg,Number(z));break;case 2:var H=y;z=Number(z);if(null!=z&&"number"!==typeof z)throw Error("Value of float/double field must be a number|null|undefined, found "+typeof z+": "+z);Rf(H,2,bg,z)}r.push(y)}p=r;for(t=0;t<p.length;t++){r=p[t];x=new cg;r=Tf(x,ag,2,r);x=n;y=[];H=f;z=[];for(var I=0;I<H.h.length;I++)z.push(H.h[I].ub);H=z;for(z=0;z<H.length;z++){I=H[z];var M=x[z],L=
new Zf;switch(I){case 3:Rf(L,1,$f,vf(String(M)));break;case 2:Rf(L,2,$f,tf(Number(M)));break;case 1:Rf(L,3,$f,sf("true"==M))}y.push(L)}Uf(r,Zf,1,y);k.push(r)}}Uf(g,cg,4,k);c.push(g);e.clear()}Uf(a,dg,1,c);b=this.i;a instanceof Yg?b.log(a):(c=new Yg,a=a.serialize(),a=J(c,8,vf(a)),b.log(a));this.i.flush()}};function vh(a){this.v=wh();this.m=new uh(1828);this.h=new re(this.m);this.s=new xe(this.h);this.j=new ye(this.h);this.l=new ze(this.h);this.i=new ve(this.h);this.Oa=Be(a)}
function wh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function xh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function yh(a){function b(r,x){Promise.resolve().then(function(){var y;null!=(y=c.oa)&&y.s.record(wh()-y.v,y.Oa);g.resolve({Ud:r,We:x})})}
var c=this;this.i=!1;var d=a.program;var e=a.ne;if(a.Ge){var f;this.oa=null!=(f=a.oa)?f:new vh(e)}var g=new xh;this.j=g.promise;if(!C[e]){var h;null!=(h=this.oa)&&we(h.i,h.Oa,1,"");var k;null!=(k=this.oa)&&k.h.pb()}else if(!C[e].a){var l;null!=(l=this.oa)&&we(l.i,l.Oa,2,"");var n;null!=(n=this.oa)&&n.h.pb()}try{this.l=v((0,C[e].a)(d,b,!0,a.gg)).next().value,this.Ve=g.promise.then(function(){})}catch(r){var p;
null!=(p=this.oa)&&we(p.i,p.Oa,4,r.message);var t;null!=(t=this.oa)&&t.h.pb();throw r;}}
yh.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=wh(),d;null!=(d=this.oa)&&d.j.h.uc("/client_streamz/bg/fsc",d.Oa);return this.j.then(function(e){var f=e.Ud;return new Promise(function(g){f(function(h){var k;null!=(k=b.oa)&&k.l.record(wh()-c,k.Oa);g(h)},[a.hd,
a.Xe,a.ff])})})};
yh.prototype.Gd=function(a){if(this.i)throw Error("Already disposed");var b=wh(),c;null!=(c=this.oa)&&c.j.h.uc("/client_streamz/bg/fsc",c.Oa);a=this.l([a.hd,a.Xe,a.ff]);var d;null!=(d=this.oa)&&d.l.record(wh()-b,d.Oa);return a};
yh.prototype.dispose=function(){var a;null!=(a=this.oa)&&a.h.pb();this.i=!0;this.j.then(function(b){(b=b.We)&&b()})};
yh.prototype.h=function(){return this.i};var zh=window;xb("csi.gstatic.com");xb("googleads.g.doubleclick.net");xb("partner.googleadservices.com");xb("pubads.g.doubleclick.net");xb("securepubads.g.doubleclick.net");xb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Ah;try{new URL("s://g"),Ah=!0}catch(a){Ah=!1}var Bh=Ah;function Ch(a){if(a instanceof Fb)a=Gb(a);else{b:if(Bh){try{var b=new URL(a)}catch(c){b="https:";break b}b=b.protocol}else c:{b=document.createElement("a");try{b.href=a}catch(c){b=void 0;break c}b=b.protocol;b=":"===b||""===b?"https:":b}a="javascript:"!==b?a:void 0}return a}
;var Dh={};function Eh(){}
function Fh(a){this.h=a}
w(Fh,Eh);Fh.prototype.toString=function(){return this.h};function Gh(a){var b="true".toString(),c=[new Fh(Hh[0].toLowerCase(),Dh)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof Fh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Ih(){throw Error("unknown trace type");}
;function Jh(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function Kh(a,b){a.src=Bb(b);Jh(a)}
;(function(){return""}).toString().indexOf("`");function Lh(a){this.we=a}
function Mh(a){return new Lh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Nh=[Mh("data"),Mh("http"),Mh("https"),Mh("mailto"),Mh("ftp"),new Lh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Oh(a){var b=Ph;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Qh(){var a=[];Oh(function(b){a.push(b)});
return a}
var Ph={gf:"allow-forms",hf:"allow-modals",jf:"allow-orientation-lock",kf:"allow-pointer-lock",lf:"allow-popups",mf:"allow-popups-to-escape-sandbox",nf:"allow-presentation",pf:"allow-same-origin",qf:"allow-scripts",rf:"allow-top-navigation",sf:"allow-top-navigation-by-user-activation"},Rh=$a(function(){return Qh()});
function Sh(){var a=Th(),b={};bb(Rh(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Th(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Uh(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Vh=(new Date).getTime();"undefined"!==typeof TextDecoder&&new TextDecoder;var Wh="undefined"!==typeof TextEncoder?new TextEncoder:null,Xh=Wh?function(a){return Wh.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function Yh(a){yd.call(this);var b=this;this.v=this.j=0;this.Ba=null!=a?a:{ka:function(e,f){return setTimeout(e,f)},
ya:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return A(function(e){return e.yield(Zh(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.v||$h(this)}
w(Yh,yd);function ai(){var a=bi;Yh.h||(Yh.h=new Yh(a));return Yh.h}
Yh.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.Ba.ya(this.v);delete Yh.h};
Yh.prototype.qa=function(){return this.i};
function $h(a){a.v=a.Ba.ka(function(){var b;return A(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):c.yield(Zh(a),3):c.yield(Zh(a),3);$h(a);c.h=0})},3E4)}
function Zh(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Ba.ka(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.Da=[h.j];h.l=0;h.s=0;a.s=void 0;a.j&&(a.Ba.ya(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?zd(a,"networkstatus-online"):zd(a,"networkstatus-offline"));c(g);Aa(h);break;case 2:za(h),g=!1,h.A(3)}})})}
;function ci(){this.data=[];this.h=-1}
ci.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
ci.prototype.get=function(a){return!!this.data[a]};
function di(a){-1===a.h&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function ei(a,b){this.h=a[C.Symbol.iterator]();this.i=b}
ei.prototype[Symbol.iterator]=function(){return this};
ei.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function fi(a,b){return new ei(a,b)}
;function gi(){this.blockSize=-1}
;function hi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.s=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
Va(hi,gi);hi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function ii(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
hi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)ii(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){ii(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){ii(this,e);f=0;break}}this.i=f;this.l+=b}};
hi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;ii(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function ji(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function ki(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function li(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:ji(a).match(/\S+/g)||[],b=0<=ab(a,b));return b}
function mi(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):li(a,"inverted-hdpi")&&ki(a,Array.prototype.filter.call(a.classList?a.classList:ji(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function ni(){}
ni.prototype.next=function(){return oi};
var oi={done:!0,value:void 0};function pi(a){return{value:a,done:!1}}
ni.prototype.Ea=function(){return this};function qi(a){if(a instanceof ri||a instanceof si||a instanceof ti)return a;if("function"==typeof a.next)return new ri(function(){return a});
if("function"==typeof a[Symbol.iterator])return new ri(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ea)return new ri(function(){return a.Ea()});
throw Error("Not an iterator or iterable.");}
function ri(a){this.i=a}
ri.prototype.Ea=function(){return new si(this.i())};
ri.prototype[Symbol.iterator]=function(){return new ti(this.i())};
ri.prototype.h=function(){return new ti(this.i())};
function si(a){this.i=a}
w(si,ni);si.prototype.next=function(){return this.i.next()};
si.prototype[Symbol.iterator]=function(){return new ti(this.i)};
si.prototype.h=function(){return new ti(this.i)};
function ti(a){ri.call(this,function(){return a});
this.j=a}
w(ti,ri);ti.prototype.next=function(){return this.j.next()};function ui(a,b){this.i={};this.h=[];this.Xa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof ui)for(c=a.Fc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
m=ui.prototype;m.Fc=function(){vi(this);return this.h.concat()};
m.has=function(a){return wi(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||xi;vi(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function xi(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.Xa=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return wi(this.i,a)?(delete this.i[a],--this.size,this.Xa++,this.h.length>2*this.size&&vi(this),!0):!1};
function vi(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];wi(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],wi(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return wi(this.i,a)?this.i[a]:b};
m.set=function(a,b){wi(this.i,a)||(this.size+=1,this.h.push(a),this.Xa++);this.i[a]=b};
m.forEach=function(a,b){for(var c=this.Fc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new ui(this)};
m.keys=function(){return qi(this.Ea(!0)).h()};
m.values=function(){return qi(this.Ea(!1)).h()};
m.entries=function(){var a=this;return fi(this.keys(),function(b){return[b,a.get(b)]})};
m.Ea=function(a){vi(this);var b=0,c=this.Xa,d=this,e=new ni;e.next=function(){if(c!=d.Xa)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return oi;var f=d.h[b++];return pi(a?f:d.i[f])};
return e};
function wi(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function N(a){G.call(this);this.s=1;this.l=[];this.m=0;this.i=[];this.j={};this.v=!!a}
Va(N,G);m=N.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.s;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.s=e+3;d.push(e);return e};
function yi(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Kb(b)}}
m.Kb=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&gb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.cb=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];zi(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Kb(c)}}return 0!=e}return!1};
function zi(a,b,c){Sd(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Kb,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.M=function(){N.va.M.call(this);this.clear();this.l.length=0};function Ai(a){this.h=a}
Ai.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,(new wg).serialize(b))};
Ai.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Ai.prototype.remove=function(a){this.h.remove(a)};function Bi(a){this.h=a}
Va(Bi,Ai);function Ci(a){this.data=a}
function Di(a){return void 0===a||a instanceof Ci?a:new Ci(a)}
Bi.prototype.set=function(a,b){Bi.va.set.call(this,a,Di(b))};
Bi.prototype.i=function(a){a=Bi.va.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Bi.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Ei(a){this.h=a}
Va(Ei,Bi);Ei.prototype.set=function(a,b,c){if(b=Di(b)){if(c){if(c<Date.now()){Ei.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Ei.va.set.call(this,a,b)};
Ei.prototype.i=function(a){var b=Ei.va.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Ei.prototype.remove.call(this,a);else return b}};function Fi(){}
;function Gi(){}
Va(Gi,Fi);Gi.prototype[Symbol.iterator]=function(){return qi(this.Ea(!0)).h()};
Gi.prototype.clear=function(){var a=Array.from(this);a=v(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Hi(a){this.h=a}
Va(Hi,Gi);m=Hi.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.Ea=function(a){var b=0,c=this.h,d=new ni;d.next=function(){if(b>=c.length)return oi;var e=c.key(b++);if(a)return pi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return pi(e)};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function Ii(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
Va(Ii,Hi);function Ji(a,b){this.i=a;this.h=null;var c;if(c=Nc)c=!(9<=Number(ad));if(c){Ki||(Ki=new ui);this.h=Ki.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Ki.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
Va(Ji,Gi);var Li={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Ki=null;function Mi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Li[b]})}
m=Ji.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(Mi(a),b);Ni(this)};
m.get=function(a){a=this.h.getAttribute(Mi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(Mi(a));Ni(this)};
m.Ea=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new ni;d.next=function(){if(b>=c.length)return oi;var e=c[b++];if(a)return pi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return pi(e)};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Ni(this)};
function Ni(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Oi(a,b){this.i=a;this.h=b+"::"}
Va(Oi,Gi);Oi.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Oi.prototype.get=function(a){return this.i.get(this.h+a)};
Oi.prototype.remove=function(a){this.i.remove(this.h+a)};
Oi.prototype.Ea=function(a){var b=this.i[Symbol.iterator](),c=this,d=new ni;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return pi(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var O={},Pi="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;O.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
O.Tc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var Qi={qb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ld:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},Ri={qb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ld:function(a){return[].concat.apply([],a)}};
O.Ue=function(){Pi?(O.ob=Uint8Array,O.Ga=Uint16Array,O.Pd=Int32Array,O.assign(O,Qi)):(O.ob=Array,O.Ga=Array,O.Pd=Array,O.assign(O,Ri))};
O.Ue();var Si=!0;try{new Uint8Array(1)}catch(a){Si=!1}
function Ti(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new O.ob(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var Ui={};Ui=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var Vi={},Wi,Xi=[],Yi=0;256>Yi;Yi++){Wi=Yi;for(var Zi=0;8>Zi;Zi++)Wi=Wi&1?3988292384^Wi>>>1:Wi>>>1;Xi[Yi]=Wi}Vi=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^Xi[(a^b[d])&255];return a^-1};var $i={};$i={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function aj(a){for(var b=a.length;0<=--b;)a[b]=0}
var bj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],cj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],dj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],ej=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],fj=Array(576);aj(fj);var gj=Array(60);aj(gj);var hj=Array(512);aj(hj);var ij=Array(256);aj(ij);var jj=Array(29);aj(jj);var kj=Array(30);aj(kj);function lj(a,b,c,d,e){this.Hd=a;this.he=b;this.ge=c;this.be=d;this.Ae=e;this.pd=a&&a.length}
var mj,nj,oj;function pj(a,b){this.kd=a;this.Bb=0;this.Wa=b}
function qj(a,b){a.T[a.pending++]=b&255;a.T[a.pending++]=b>>>8&255}
function rj(a,b,c){a.aa>16-c?(a.ia|=b<<a.aa&65535,qj(a,a.ia),a.ia=b>>16-a.aa,a.aa+=c-16):(a.ia|=b<<a.aa&65535,a.aa+=c)}
function sj(a,b,c){rj(a,c[2*b],c[2*b+1])}
function tj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function uj(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=tj(d[e]++,e))}
function vj(a){var b;for(b=0;286>b;b++)a.la[2*b]=0;for(b=0;30>b;b++)a.eb[2*b]=0;for(b=0;19>b;b++)a.da[2*b]=0;a.la[512]=1;a.Na=a.Gb=0;a.sa=a.matches=0}
function wj(a){8<a.aa?qj(a,a.ia):0<a.aa&&(a.T[a.pending++]=a.ia);a.ia=0;a.aa=0}
function xj(a,b,c){wj(a);qj(a,c);qj(a,~c);O.qb(a.T,a.window,b,c,a.pending);a.pending+=c}
function yj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function zj(a,b,c){for(var d=a.U[c],e=c<<1;e<=a.La;){e<a.La&&yj(b,a.U[e+1],a.U[e],a.depth)&&e++;if(yj(b,d,a.U[e],a.depth))break;a.U[c]=a.U[e];c=e;e<<=1}a.U[c]=d}
function Aj(a,b,c){var d=0;if(0!==a.sa){do{var e=a.T[a.Nb+2*d]<<8|a.T[a.Nb+2*d+1];var f=a.T[a.Jc+d];d++;if(0===e)sj(a,f,b);else{var g=ij[f];sj(a,g+256+1,b);var h=bj[g];0!==h&&(f-=jj[g],rj(a,f,h));e--;g=256>e?hj[e]:hj[256+(e>>>7)];sj(a,g,c);h=cj[g];0!==h&&(e-=kj[g],rj(a,e,h))}}while(d<a.sa)}sj(a,256,b)}
function Bj(a,b){var c=b.kd,d=b.Wa.Hd,e=b.Wa.pd,f=b.Wa.be,g,h=-1;a.La=0;a.xb=573;for(g=0;g<f;g++)0!==c[2*g]?(a.U[++a.La]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.La;){var k=a.U[++a.La]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Na--;e&&(a.Gb-=d[2*k+1])}b.Bb=h;for(g=a.La>>1;1<=g;g--)zj(a,c,g);k=f;do g=a.U[1],a.U[1]=a.U[a.La--],zj(a,c,1),d=a.U[1],a.U[--a.xb]=g,a.U[--a.xb]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.U[1]=k++,zj(a,c,1);while(2<=a.La);a.U[--a.xb]=
a.U[1];g=b.kd;k=b.Bb;d=b.Wa.Hd;e=b.Wa.pd;f=b.Wa.he;var l=b.Wa.ge,n=b.Wa.Ae,p,t=0;for(p=0;15>=p;p++)a.Ia[p]=0;g[2*a.U[a.xb]+1]=0;for(b=a.xb+1;573>b;b++){var r=a.U[b];p=g[2*g[2*r+1]+1]+1;p>n&&(p=n,t++);g[2*r+1]=p;if(!(r>k)){a.Ia[p]++;var x=0;r>=l&&(x=f[r-l]);var y=g[2*r];a.Na+=y*(p+x);e&&(a.Gb+=y*(d[2*r+1]+x))}}if(0!==t){do{for(p=n-1;0===a.Ia[p];)p--;a.Ia[p]--;a.Ia[p+1]+=2;a.Ia[n]--;t-=2}while(0<t);for(p=n;0!==p;p--)for(r=a.Ia[p];0!==r;)d=a.U[--b],d>k||(g[2*d+1]!==p&&(a.Na+=(p-g[2*d+1])*g[2*d],g[2*
d+1]=p),r--)}uj(c,h,a.Ia)}
function Cj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];++g<h&&l===f||(g<k?a.da[2*l]+=g:0!==l?(l!==e&&a.da[2*l]++,a.da[32]++):10>=g?a.da[34]++:a.da[36]++,g=0,e=l,0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function Dj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[2*(d+1)+1];if(!(++g<h&&l===f)){if(g<k){do sj(a,l,a.da);while(0!==--g)}else 0!==l?(l!==e&&(sj(a,l,a.da),g--),sj(a,16,a.da),rj(a,g-3,2)):10>=g?(sj(a,17,a.da),rj(a,g-3,3)):(sj(a,18,a.da),rj(a,g-11,7));g=0;e=l;0===f?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function Ej(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.la[2*c])return 0;if(0!==a.la[18]||0!==a.la[20]||0!==a.la[26])return 1;for(c=32;256>c;c++)if(0!==a.la[2*c])return 1;return 0}
var Fj=!1;function Gj(a,b,c){a.T[a.Nb+2*a.sa]=b>>>8&255;a.T[a.Nb+2*a.sa+1]=b&255;a.T[a.Jc+a.sa]=c&255;a.sa++;0===b?a.la[2*c]++:(a.matches++,b--,a.la[2*(ij[c]+256+1)]++,a.eb[2*(256>b?hj[b]:hj[256+(b>>>7)])]++);return a.sa===a.Qb-1}
;function Hj(a,b){a.msg=$i[b];return b}
function Ij(a){for(var b=a.length;0<=--b;)a[b]=0}
function Jj(a){var b=a.state,c=b.pending;c>a.J&&(c=a.J);0!==c&&(O.qb(a.output,b.T,b.Rb,c,a.Db),a.Db+=c,b.Rb+=c,a.Uc+=c,a.J-=c,b.pending-=c,0===b.pending&&(b.Rb=0))}
function Kj(a,b){var c=0<=a.na?a.na:-1,d=a.o-a.na,e=0;if(0<a.level){2===a.G.zc&&(a.G.zc=Ej(a));Bj(a,a.jc);Bj(a,a.ec);Cj(a,a.la,a.jc.Bb);Cj(a,a.eb,a.ec.Bb);Bj(a,a.cd);for(e=18;3<=e&&0===a.da[2*ej[e]+1];e--);a.Na+=3*(e+1)+14;var f=a.Na+3+7>>>3;var g=a.Gb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)rj(a,b?1:0,3),xj(a,c,d);else if(4===a.strategy||g===f)rj(a,2+(b?1:0),3),Aj(a,fj,gj);else{rj(a,4+(b?1:0),3);c=a.jc.Bb+1;d=a.ec.Bb+1;e+=1;rj(a,c-257,5);rj(a,d-1,5);rj(a,e-4,4);for(f=0;f<e;f++)rj(a,a.da[2*
ej[f]+1],3);Dj(a,a.la,c-1);Dj(a,a.eb,d-1);Aj(a,a.la,a.eb)}vj(a);b&&wj(a);a.na=a.o;Jj(a.G)}
function P(a,b){a.T[a.pending++]=b}
function Lj(a,b){a.T[a.pending++]=b>>>8&255;a.T[a.pending++]=b&255}
function Mj(a,b){var c=a.sd,d=a.o,e=a.ra,f=a.ud,g=a.o>a.ga-262?a.o-(a.ga-262):0,h=a.window,k=a.Ya,l=a.Fa,n=a.o+258,p=h[d+e-1],t=h[d+e];a.ra>=a.od&&(c>>=2);f>a.u&&(f=a.u);do{var r=b;if(h[r+e]===t&&h[r+e-1]===p&&h[r]===h[d]&&h[++r]===h[d+1]){d+=2;for(r++;h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&h[++d]===h[++r]&&d<n;);r=258-(n-d);d=n-258;if(r>e){a.Ab=b;e=r;if(r>=f)break;p=h[d+e-1];t=h[d+e]}}}while((b=l[b&k])>g&&0!==--c);return e<=
a.u?e:a.u}
function Nj(a){var b=a.ga,c;do{var d=a.Nd-a.u-a.o;if(a.o>=b+(b-262)){O.qb(a.window,a.window,b,b,0);a.Ab-=b;a.o-=b;a.na-=b;var e=c=a.ic;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Fa[--e],a.Fa[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.G.ha)break;e=a.G;c=a.window;f=a.o+a.u;var g=e.ha;g>d&&(g=d);0===g?c=0:(e.ha-=g,O.qb(c,e.input,e.hb,g,f),1===e.state.wrap?e.F=Ui(e.F,c,g,f):2===e.state.wrap&&(e.F=Vi(e.F,c,g,f)),e.hb+=g,e.lb+=g,c=g);a.u+=c;if(3<=a.u+a.ma)for(d=a.o-a.ma,a.I=a.window[d],
a.I=(a.I<<a.Ka^a.window[d+1])&a.Ja;a.ma&&!(a.I=(a.I<<a.Ka^a.window[d+3-1])&a.Ja,a.Fa[d&a.Ya]=a.head[a.I],a.head[a.I]=d,d++,a.ma--,3>a.u+a.ma););}while(262>a.u&&0!==a.G.ha)}
function Oj(a,b){for(var c;;){if(262>a.u){Nj(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.I=(a.I<<a.Ka^a.window[a.o+3-1])&a.Ja,c=a.Fa[a.o&a.Ya]=a.head[a.I],a.head[a.I]=a.o);0!==c&&a.o-c<=a.ga-262&&(a.K=Mj(a,c));if(3<=a.K)if(c=Gj(a,a.o-a.Ab,a.K-3),a.u-=a.K,a.K<=a.Kc&&3<=a.u){a.K--;do a.o++,a.I=(a.I<<a.Ka^a.window[a.o+3-1])&a.Ja,a.Fa[a.o&a.Ya]=a.head[a.I],a.head[a.I]=a.o;while(0!==--a.K);a.o++}else a.o+=a.K,a.K=0,a.I=a.window[a.o],a.I=(a.I<<a.Ka^a.window[a.o+1])&a.Ja;else c=Gj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(Kj(a,!1),0===a.G.J))return 1}a.ma=2>a.o?a.o:2;return 4===b?(Kj(a,!0),0===a.G.J?3:4):a.sa&&(Kj(a,!1),0===a.G.J)?1:2}
function Pj(a,b){for(var c,d;;){if(262>a.u){Nj(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.I=(a.I<<a.Ka^a.window[a.o+3-1])&a.Ja,c=a.Fa[a.o&a.Ya]=a.head[a.I],a.head[a.I]=a.o);a.ra=a.K;a.xd=a.Ab;a.K=2;0!==c&&a.ra<a.Kc&&a.o-c<=a.ga-262&&(a.K=Mj(a,c),5>=a.K&&(1===a.strategy||3===a.K&&4096<a.o-a.Ab)&&(a.K=2));if(3<=a.ra&&a.K<=a.ra){d=a.o+a.u-3;c=Gj(a,a.o-1-a.xd,a.ra-3);a.u-=a.ra-1;a.ra-=2;do++a.o<=d&&(a.I=(a.I<<a.Ka^a.window[a.o+3-1])&a.Ja,a.Fa[a.o&a.Ya]=a.head[a.I],a.head[a.I]=a.o);
while(0!==--a.ra);a.fb=0;a.K=2;a.o++;if(c&&(Kj(a,!1),0===a.G.J))return 1}else if(a.fb){if((c=Gj(a,0,a.window[a.o-1]))&&Kj(a,!1),a.o++,a.u--,0===a.G.J)return 1}else a.fb=1,a.o++,a.u--}a.fb&&(Gj(a,0,a.window[a.o-1]),a.fb=0);a.ma=2>a.o?a.o:2;return 4===b?(Kj(a,!0),0===a.G.J?3:4):a.sa&&(Kj(a,!1),0===a.G.J)?1:2}
function Qj(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){Nj(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.K=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.K=258-(e-d);a.K>a.u&&(a.K=a.u)}3<=a.K?(c=Gj(a,1,a.K-3),a.u-=a.K,a.o+=a.K,a.K=0):(c=Gj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(Kj(a,!1),0===a.G.J))return 1}a.ma=0;return 4===b?(Kj(a,!0),0===a.G.J?3:4):
a.sa&&(Kj(a,!1),0===a.G.J)?1:2}
function Rj(a,b){for(var c;;){if(0===a.u&&(Nj(a),0===a.u)){if(0===b)return 1;break}a.K=0;c=Gj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(Kj(a,!1),0===a.G.J))return 1}a.ma=0;return 4===b?(Kj(a,!0),0===a.G.J?3:4):a.sa&&(Kj(a,!1),0===a.G.J)?1:2}
function Sj(a,b,c,d,e){this.oe=a;this.ze=b;this.Ce=c;this.ye=d;this.ke=e}
var Tj;Tj=[new Sj(0,0,0,0,function(a,b){var c=65535;for(c>a.ta-5&&(c=a.ta-5);;){if(1>=a.u){Nj(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.na+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,Kj(a,!1),0===a.G.J)return 1;if(a.o-a.na>=a.ga-262&&(Kj(a,!1),0===a.G.J))return 1}a.ma=0;if(4===b)return Kj(a,!0),0===a.G.J?3:4;a.o>a.na&&Kj(a,!1);return 1}),
new Sj(4,4,8,4,Oj),new Sj(4,5,16,8,Oj),new Sj(4,6,32,32,Oj),new Sj(4,4,16,16,Pj),new Sj(8,16,32,32,Pj),new Sj(8,16,128,128,Pj),new Sj(8,32,128,256,Pj),new Sj(32,128,258,1024,Pj),new Sj(32,258,258,4096,Pj)];
function Uj(){this.G=null;this.status=0;this.T=null;this.wrap=this.pending=this.Rb=this.ta=0;this.D=null;this.za=0;this.method=8;this.zb=-1;this.Ya=this.Wc=this.ga=0;this.window=null;this.Nd=0;this.head=this.Fa=null;this.ud=this.od=this.strategy=this.level=this.Kc=this.sd=this.ra=this.u=this.Ab=this.o=this.fb=this.xd=this.K=this.na=this.Ka=this.Ja=this.Gc=this.ic=this.I=0;this.la=new O.Ga(1146);this.eb=new O.Ga(122);this.da=new O.Ga(78);Ij(this.la);Ij(this.eb);Ij(this.da);this.cd=this.ec=this.jc=
null;this.Ia=new O.Ga(16);this.U=new O.Ga(573);Ij(this.U);this.xb=this.La=0;this.depth=new O.Ga(573);Ij(this.depth);this.aa=this.ia=this.ma=this.matches=this.Gb=this.Na=this.Nb=this.sa=this.Qb=this.Jc=0}
function Vj(a,b){if(!a||!a.state||5<b||0>b)return a?Hj(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.ha||666===c.status&&4!==b)return Hj(a,0===a.J?-5:-2);c.G=a;var d=c.zb;c.zb=b;if(42===c.status)if(2===c.wrap)a.F=0,P(c,31),P(c,139),P(c,8),c.D?(P(c,(c.D.text?1:0)+(c.D.Ta?2:0)+(c.D.Sa?4:0)+(c.D.name?8:0)+(c.D.comment?16:0)),P(c,c.D.time&255),P(c,c.D.time>>8&255),P(c,c.D.time>>16&255),P(c,c.D.time>>24&255),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,c.D.os&255),c.D.Sa&&c.D.Sa.length&&
(P(c,c.D.Sa.length&255),P(c,c.D.Sa.length>>8&255)),c.D.Ta&&(a.F=Vi(a.F,c.T,c.pending,0)),c.za=0,c.status=69):(P(c,0),P(c,0),P(c,0),P(c,0),P(c,0),P(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),P(c,3),c.status=113);else{var e=8+(c.Wc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;Lj(c,e+(31-e%31));0!==c.o&&(Lj(c,a.F>>>16),Lj(c,a.F&65535));a.F=1}if(69===c.status)if(c.D.Sa){for(e=c.pending;c.za<(c.D.Sa.length&65535)&&(c.pending!==c.ta||(c.D.Ta&&
c.pending>e&&(a.F=Vi(a.F,c.T,c.pending-e,e)),Jj(a),e=c.pending,c.pending!==c.ta));)P(c,c.D.Sa[c.za]&255),c.za++;c.D.Ta&&c.pending>e&&(a.F=Vi(a.F,c.T,c.pending-e,e));c.za===c.D.Sa.length&&(c.za=0,c.status=73)}else c.status=73;if(73===c.status)if(c.D.name){e=c.pending;do{if(c.pending===c.ta&&(c.D.Ta&&c.pending>e&&(a.F=Vi(a.F,c.T,c.pending-e,e)),Jj(a),e=c.pending,c.pending===c.ta)){var f=1;break}f=c.za<c.D.name.length?c.D.name.charCodeAt(c.za++)&255:0;P(c,f)}while(0!==f);c.D.Ta&&c.pending>e&&(a.F=Vi(a.F,
c.T,c.pending-e,e));0===f&&(c.za=0,c.status=91)}else c.status=91;if(91===c.status)if(c.D.comment){e=c.pending;do{if(c.pending===c.ta&&(c.D.Ta&&c.pending>e&&(a.F=Vi(a.F,c.T,c.pending-e,e)),Jj(a),e=c.pending,c.pending===c.ta)){f=1;break}f=c.za<c.D.comment.length?c.D.comment.charCodeAt(c.za++)&255:0;P(c,f)}while(0!==f);c.D.Ta&&c.pending>e&&(a.F=Vi(a.F,c.T,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.D.Ta?(c.pending+2>c.ta&&Jj(a),c.pending+2<=c.ta&&(P(c,a.F&255),P(c,a.F>>
8&255),a.F=0,c.status=113)):c.status=113);if(0!==c.pending){if(Jj(a),0===a.J)return c.zb=-1,0}else if(0===a.ha&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Hj(a,-5);if(666===c.status&&0!==a.ha)return Hj(a,-5);if(0!==a.ha||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?Rj(c,b):3===c.strategy?Qj(c,b):Tj[c.level].ke(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.J&&(c.zb=-1),0;if(2===d&&(1===b?(rj(c,2,3),sj(c,256,fj),16===c.aa?(qj(c,c.ia),c.ia=0,c.aa=0):8<=c.aa&&(c.T[c.pending++]=
c.ia&255,c.ia>>=8,c.aa-=8)):5!==b&&(rj(c,0,3),xj(c,0,0),3===b&&(Ij(c.head),0===c.u&&(c.o=0,c.na=0,c.ma=0))),Jj(a),0===a.J))return c.zb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(P(c,a.F&255),P(c,a.F>>8&255),P(c,a.F>>16&255),P(c,a.F>>24&255),P(c,a.lb&255),P(c,a.lb>>8&255),P(c,a.lb>>16&255),P(c,a.lb>>24&255)):(Lj(c,a.F>>>16),Lj(c,a.F&65535));Jj(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var Wj={};Wj=function(){this.input=null;this.lb=this.ha=this.hb=0;this.output=null;this.Uc=this.J=this.Db=0;this.msg="";this.state=null;this.zc=2;this.F=0};var Xj=Object.prototype.toString;
function Yj(a){if(!(this instanceof Yj))return new Yj(a);a=this.options=O.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&0<a.windowBits?a.windowBits=-a.windowBits:a.gzip&&0<a.windowBits&&16>a.windowBits&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.G=new Wj;this.G.J=0;var b=this.G;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<
f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Hj(b,-2);else{8===e&&(e=9);var k=new Uj;b.state=k;k.G=b;k.wrap=h;k.D=null;k.Wc=e;k.ga=1<<k.Wc;k.Ya=k.ga-1;k.Gc=f+7;k.ic=1<<k.Gc;k.Ja=k.ic-1;k.Ka=~~((k.Gc+3-1)/3);k.window=new O.ob(2*k.ga);k.head=new O.Ga(k.ic);k.Fa=new O.Ga(k.ga);k.Qb=1<<f+6;k.ta=4*k.Qb;k.T=new O.ob(k.ta);k.Nb=1*k.Qb;k.Jc=3*k.Qb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.lb=b.Uc=0;b.zc=2;c=b.state;c.pending=0;c.Rb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.F=2===c.wrap?
0:1;c.zb=0;if(!Fj){d=Array(16);for(f=g=0;28>f;f++)for(jj[f]=g,e=0;e<1<<bj[f];e++)ij[g++]=f;ij[g-1]=f;for(f=g=0;16>f;f++)for(kj[f]=g,e=0;e<1<<cj[f];e++)hj[g++]=f;for(g>>=7;30>f;f++)for(kj[f]=g<<7,e=0;e<1<<cj[f]-7;e++)hj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)fj[2*e+1]=8,e++,d[8]++;for(;255>=e;)fj[2*e+1]=9,e++,d[9]++;for(;279>=e;)fj[2*e+1]=7,e++,d[7]++;for(;287>=e;)fj[2*e+1]=8,e++,d[8]++;uj(fj,287,d);for(e=0;30>e;e++)gj[2*e+1]=5,gj[2*e]=tj(e,5);mj=new lj(fj,bj,257,286,15);nj=new lj(gj,
cj,0,30,15);oj=new lj([],dj,0,19,7);Fj=!0}c.jc=new pj(c.la,mj);c.ec=new pj(c.eb,nj);c.cd=new pj(c.da,oj);c.ia=0;c.aa=0;vj(c);c=0}else c=Hj(b,-2);0===c&&(b=b.state,b.Nd=2*b.ga,Ij(b.head),b.Kc=Tj[b.level].ze,b.od=Tj[b.level].oe,b.ud=Tj[b.level].Ce,b.sd=Tj[b.level].ye,b.o=0,b.na=0,b.u=0,b.ma=0,b.K=b.ra=2,b.fb=0,b.I=0);b=c}}else b=-2;if(0!==b)throw Error($i[b]);a.header&&(b=this.G)&&b.state&&2===b.state.wrap&&(b.state.D=a.header);if(a.dictionary){var l;"string"===typeof a.dictionary?l=Ti(a.dictionary):
"[object ArrayBuffer]"===Xj.call(a.dictionary)?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.G;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,2===b||1===b&&42!==l.status||l.u)b=-2;else{1===b&&(a.F=Ui(a.F,f,g,0));l.wrap=0;g>=l.ga&&(0===b&&(Ij(l.head),l.o=0,l.na=0,l.ma=0),c=new O.ob(l.ga),O.qb(c,f,g-l.ga,l.ga,0),f=c,g=l.ga);c=a.ha;d=a.hb;e=a.input;a.ha=g;a.hb=0;a.input=f;for(Nj(l);3<=l.u;){f=l.o;g=l.u-2;do l.I=(l.I<<l.Ka^l.window[f+3-1])&l.Ja,l.Fa[f&l.Ya]=l.head[l.I],l.head[l.I]=f,f++;while(--g);
l.o=f;l.u=2;Nj(l)}l.o+=l.u;l.na=l.o;l.ma=l.u;l.u=0;l.K=l.ra=2;l.fb=0;a.hb=d;a.input=e;a.ha=c;l.wrap=b;b=0}else b=-2;if(0!==b)throw Error($i[b]);this.If=!0}}
Yj.prototype.push=function(a,b){var c=this.G,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=Ti(a):"[object ArrayBuffer]"===Xj.call(a)?c.input=new Uint8Array(a):c.input=a;c.hb=0;c.ha=c.input.length;do{0===c.J&&(c.output=new O.ob(d),c.Db=0,c.J=d);a=Vj(c,e);if(1!==a&&0!==a)return Zj(this,a),this.ended=!0,!1;if(0===c.J||0===c.ha&&(4===e||2===e))if("string"===this.options.to){var f=O.Tc(c.output,c.Db);b=f;f=f.length;if(65537>f&&(b.subarray&&Si||!b.subarray))b=
String.fromCharCode.apply(null,O.Tc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=O.Tc(c.output,c.Db),this.chunks.push(b)}while((0<c.ha||0===c.J)&&1!==a);if(4===e)return(c=this.G)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Hj(c,-2):(c.state=null,a=113===d?Hj(c,-3):0)):a=-2,Zj(this,a),this.ended=!0,0===a;2===e&&(Zj(this,0),c.J=0);return!0};
function Zj(a,b){0===b&&(a.result="string"===a.options.to?a.chunks.join(""):O.ld(a.chunks));a.chunks=[];a.err=b;a.msg=a.G.msg}
function ak(a,b){b=b||{};b.gzip=!0;b=new Yj(b);b.push(a,!0);if(b.err)throw b.msg||$i[b.err];return b.result}
;function bk(a){return Db(null===a?"null":void 0===a?"undefined":a)}
;function ck(a){this.name=a}
;var dk=new ck("rawColdConfigGroup");var ek=new ck("rawHotConfigGroup");var fk=new ck("commandExecutorCommand");function gk(a){this.B=Af(a)}
w(gk,Xf);var hk=new ck("continuationCommand");var ik=new ck("signalAction");var jk=new ck("webCommandMetadata");var kk=new ck("signalServiceEndpoint");var lk={xf:"EMBEDDED_PLAYER_MODE_UNKNOWN",uf:"EMBEDDED_PLAYER_MODE_DEFAULT",wf:"EMBEDDED_PLAYER_MODE_PFP",vf:"EMBEDDED_PLAYER_MODE_PFL"};var mk=new ck("feedbackEndpoint");function nk(a){this.B=Af(a)}
w(nk,Xf);var ok=new ck("webPlayerShareEntityServiceEndpoint");var pk=new ck("playlistEditEndpoint");var qk=new ck("modifyChannelNotificationPreferenceEndpoint");var rk=new ck("unsubscribeEndpoint");var sk=new ck("subscribeEndpoint");function tk(){var a=uk;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function vk(a){D("yt.ads.biscotti.lastId_",a)}
;function wk(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var xk=C.window,yk,zk,Ak=(null==xk?void 0:null==(yk=xk.yt)?void 0:yk.config_)||(null==xk?void 0:null==(zk=xk.ytcfg)?void 0:zk.data_)||{};D("yt.config_",Ak);function Bk(){wk(Ak,arguments)}
function R(a,b){return a in Ak?Ak[a]:b}
function Ck(a){var b=Ak.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var Dk=[];function Ek(a){Dk.forEach(function(b){return b(a)})}
function Fk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Gk(b)}}:a}
function Gk(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Bk("ERRORS",b));Ek(a)}
function Hk(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=R("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Bk("ERRORS",f))}
;var Ik=/^[\w.]*$/,Jk={q:!0,search_query:!0};function Kk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Lk(f[0]||""),h=Lk(f[1]||"");g in c?Array.isArray(c[g])?hb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(Kk);k.args=[{key:l,value:f[1],query:a,method:Mk==n?"unchanged":n}];Jk.hasOwnProperty(l)||Hk(k)}}return c}
var Mk=String(Kk);function Nk(a){var b=[];ib(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];bb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Ok(a){"?"==a.charAt(0)&&(a=a.substr(1));return Kk(a,"&")}
function Pk(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Ok(1<a.length?a[1]:a[0])):{}}
function Qk(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Ok(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return pc(a,e)+d}
function Rk(a){if(!b)var b=window.location.href;var c=fc(1,a),d=hc(a);c&&d?(a=a.match(dc),b=b.match(dc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?hc(b)==d&&(Number(fc(4,b))||null)==(Number(fc(4,a))||null):!0;return a}
function Lk(a){return a&&a.match(Ik)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Sk(a){var b=Tk;a=void 0===a?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Vh;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ha){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?zh:g;try{var h=g.history.length}catch(Ha){h=0}e.u_his=h;var k;e.u_h=null==(k=zh.screen)?void 0:k.height;var l;e.u_w=null==(l=zh.screen)?void 0:l.width;var n;e.u_ah=null==(n=zh.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=zh.screen)?void 0:p.availWidth;var t;e.u_cd=null==(t=zh.screen)?void 0:t.colorDepth}catch(Ha){}h=b.h;try{var r=h.screenX;var x=h.screenY}catch(Ha){}try{var y=h.outerWidth;var z=h.outerHeight}catch(Ha){}try{var H=h.innerWidth;var I=h.innerHeight}catch(Ha){}try{var M=h.screenLeft;var L=h.screenTop}catch(Ha){}try{H=h.innerWidth,I=h.innerHeight}catch(Ha){}try{var K=h.screen.availWidth;var V=h.screen.availTop}catch(Ha){}r=[M,L,r,x,K,V,y,z,H,I];try{var Z=(b.h.top||window).document,ea="CSS1Compat"==
Z.compatMode?Z.documentElement:Z.body;var ra=(new Fd(ea.clientWidth,ea.clientHeight)).round()}catch(Ha){ra=new Fd(-12245933,-12245933)}Z=ra;ra={};var oa=void 0===oa?C:oa;ea=new ci;"SVGElement"in oa&&"createElementNS"in oa.document&&ea.set(0);x=Sh();x["allow-top-navigation-by-user-activation"]&&ea.set(1);x["allow-popups-to-escape-sandbox"]&&ea.set(2);oa.crypto&&oa.crypto.subtle&&ea.set(3);"TextDecoder"in oa&&"TextEncoder"in oa&&ea.set(4);oa=di(ea);ra.bc=oa;ra.bih=Z.height;ra.biw=Z.width;ra.brdim=r.join();
b=b.i;b=(ra.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,ra.wgl=!!zh.WebGLRenderingContext,ra);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Tk=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return Nk(Sk(a))});Date.now();navigator.userAgent.indexOf(" (CrKey ");function S(a){a=Uk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Vk(a,b){a=Uk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Uk(a){var b=R("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:R("EXPERIMENT_FLAGS",{})[a]}
function Wk(){for(var a=[],b=R("EXPERIMENTS_FORCED_FLAGS",{}),c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=R("EXPERIMENT_FLAGS",{});var e=v(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Xk="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function Yk(){if(!Xk)return null;var a=Xk();return"open"in a?a:null}
function Zk(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function $k(a,b){"function"===typeof a&&(a=Fk(a));return window.setTimeout(a,b)}
;var al="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ia(al),["client_dev_set_cookie"]);var bl={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},cl="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(al)),dl=!1;
function el(a,b){b=void 0===b?{}:b;var c=Rk(a),d=S("web_ajax_ignore_global_headers_if_set"),e;for(e in bl){var f=R(bl[e]),g="X-Goog-AuthUser"===e||"X-Goog-PageId"===e;"X-Goog-Visitor-Id"!==e||f||(f=R("VISITOR_DATA"));!f||!c&&hc(a)||d&&void 0!==b[e]||(!S("move_vss_away_from_login_info_cookie")||"TVHTML5_UNPLUGGED"===R("INNERTUBE_CLIENT_NAME"))&&g||(b[e]=f)}S("move_vss_away_from_login_info_cookie")&&c&&R("SESSION_INDEX")&&"TVHTML5_UNPLUGGED"!==R("INNERTUBE_CLIENT_NAME")&&(b["X-Yt-Auth-Test"]="test");
"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!hc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!hc(a)){try{var h=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(k){}h&&(b["X-YouTube-Time-Zone"]=h)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&hc(a)||(b["X-YouTube-Ad-Signals"]=Nk(Sk()));return b}
function fl(a){var b=window.location.search,c=hc(a);S("debug_handle_relative_url_for_query_forward_killswitch")||!c&&Rk(a)&&(c=document.location.hostname);var d=ec(fc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Ok(b),f={};bb(cl,function(g){e[g]&&(f[g]=e[g])});
return Qk(a,f||{},!1)}
function gl(a,b){var c=b.format||"JSON";a=hl(a,b);var d=il(a,b),e=!1,f=jl(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=Zk(k),n=null,p=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||p||t)n=kl(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||C;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=$k(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function hl(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Qk(a,b||{},!0);return a}
function il(a,b){var c=R("XSRF_FIELD_NAME"),d=R("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||hc(a)&&!b.withCredentials&&hc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(S("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Ok(e),sb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):nc(e));f=e||f&&!lb(f);!dl&&f&&"POST"!=b.method&&(dl=!0,Gk(Error("AJAX request with postData should use POST")));return e}
function kl(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Hk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?ll(a):null)e={},bb(a.getElementsByTagName("*"),function(g){e[g.tagName]=ml(g)})}d&&nl(e);
return e}
function nl(a){if(Na(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=ub();d=e?e.createHTML(d):d;a[c]=new Xb(d)}else nl(a[b])}}
function ll(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function ml(a){var b="";bb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function ol(a,b){b.method="POST";b.postParams||(b.postParams={});return gl(a,b)}
function jl(a,b,c,d,e,f,g,h){function k(){4==(l&&"readyState"in l?l.readyState:0)&&b&&Fk(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;h=void 0===h?!1:h;var l=Yk();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;S("debug_forward_web_query_parameters")&&(a=fl(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=el(a,e))for(var n in e)l.setRequestHeader(n,e[n]),"content-type"==n.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
h&&"setAttributionReporting"in XMLHttpRequest.prototype&&l.setAttributionReporting({eventSourceEligible:!0,triggerEligible:!1});l.send(d);return l}
;var pl=[{Lc:function(a){return"Cannot read property '"+a.key+"'"},
lc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Lc:function(a){return"Cannot call '"+a.key+"'"},
lc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Lc:function(a){return a.key+" is not defined"},
lc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var rl={Ua:[],Ra:[{callback:ql,weight:500}]};function ql(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function sl(){this.Ra=[];this.Ua=[]}
var tl;function ul(){if(!tl){var a=tl=new sl;a.Ua.length=0;a.Ra.length=0;rl.Ua&&a.Ua.push.apply(a.Ua,rl.Ua);rl.Ra&&a.Ra.push.apply(a.Ra,rl.Ra)}return tl}
;var vl=new N;function wl(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=xl(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=xl(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=xl(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function xl(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function yl(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=zl(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=wl(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?zl(e+".ve",f,g,h):0;d+=g;d+=zl(e,a[e],b,c);if(500<d)break}}else c[b]=Al(a),d+=c[b].length;else c[b]=Al(a),d+=c[b].length;return d}
function zl(a,b,c,d){c+="."+a;a=Al(b);d[c]=a;return c.length+a.length}
function Al(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function Bl(){this.Ye=!0}
function Cl(){Bl.h||(Bl.h=new Bl);return Bl.h}
function Dl(a,b){a={};var c=rg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(R("SESSION_INDEX",0)),c=isNaN(c)?0:c),S("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Ak||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in Ak&&(a["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));return a}
;var El={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Fl(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function Gl(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Hl(a,b,c,d,e){ng.set(""+a,b,{kc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Il(a){return ng.get(""+a,void 0)}
function Jl(a,b,c){ng.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function Kl(){if(!ng.isEnabled())return!1;if(!ng.isEmpty())return!0;ng.set("TESTCOOKIESENABLED","1",{kc:60});if("1"!==ng.get("TESTCOOKIESENABLED"))return!1;ng.remove("TESTCOOKIESENABLED");return!0}
;var Ll=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",Ll);function Ml(){this.h=R("ALT_PREF_COOKIE_NAME","PREF");this.i=R("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Il(this.h);a&&this.parse(a)}
var Nl;function Ol(){Nl||(Nl=new Ml);return Nl}
m=Ml.prototype;m.get=function(a,b){Pl(a);Ql(a);a=void 0!==Ll[a]?Ll[a].toString():null;return null!=a?a:b?b:""};
m.set=function(a,b){Pl(a);Ql(a);if(null==b)throw Error("ExpectedNotNull");Ll[a]=b.toString()};
function Rl(a){return!!((Sl("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
m.remove=function(a){Pl(a);Ql(a);delete Ll[a]};
m.clear=function(){for(var a in Ll)delete Ll[a]};
function Ql(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Pl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Sl(a){a=void 0!==Ll[a]?Ll[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
m.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Ll[d]=c.toString())}};var Tl={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Ul={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Vl(){var a=C.navigator;return a?a.connection:void 0}
function Wl(){var a=Vl();if(a){var b=Tl[a.type||"unknown"]||"CONN_UNKNOWN";a=Tl[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Xl(){var a=Vl();if(null!=a&&a.effectiveType)return Ul.hasOwnProperty(a.effectiveType)?Ul[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function Yl(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
w(Yl,Error);function Zl(){try{return $l(),!0}catch(a){return!1}}
function $l(a){if(void 0!==R("DATASYNC_ID"))return R("DATASYNC_ID");throw new Yl("Datasync ID not set",void 0===a?"unknown":a);}
;function am(){}
function bm(a,b){return cm(a,0,b)}
am.prototype.ka=function(a,b){return cm(a,1,b)};
function dm(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function em(){am.apply(this,arguments)}
w(em,am);function fm(){em.h||(em.h=new em);return em.h}
function cm(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):$k(a,c||0)}
em.prototype.ya=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
em.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
em.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var bi=fm();function gm(a){var b=new Ii;(b=b.isAvailable()?a?new Oi(b,a):b:null)||(a=new Ji(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Ei(a):null;this.i=document.domain||window.location.hostname}
gm.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape((new wg).serialize(b))}catch(f){return}else e=escape(b);Hl(a,e,c,this.i)};
gm.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Il(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
gm.prototype.remove=function(a){this.h&&this.h.remove(a);Jl(a,"/",this.i)};var hm=function(){var a;return function(){a||(a=new gm("ytidb"));return a}}();
function im(){var a;return null==(a=hm())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var jm=[],km,lm=!1;function mm(){var a={};for(km=new nm(void 0===a.handleError?om:a.handleError,void 0===a.logEvent?pm:a.logEvent);0<jm.length;)switch(a=jm.shift(),a.type){case "ERROR":km.handleError(a.payload);break;case "EVENT":km.logEvent(a.eventType,a.payload)}}
function qm(a){lm||(km?km.handleError(a):(jm.push({type:"ERROR",payload:a}),10<jm.length&&jm.shift()))}
function rm(a,b){lm||(km?km.logEvent(a,b):(jm.push({type:"EVENT",eventType:a,payload:b}),10<jm.length&&jm.shift()))}
;function sm(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function tm(a){return a.substr(0,a.indexOf(":"))||a}
;var um=Ee||Fe;function wm(a){var b=Ob();return b?0<=b.toLowerCase().indexOf(a):!1}
;var xm={},ym=(xm.AUTH_INVALID="No user identifier specified.",xm.EXPLICIT_ABORT="Transaction was explicitly aborted.",xm.IDB_NOT_SUPPORTED="IndexedDB is not supported.",xm.MISSING_INDEX="Index not created.",xm.MISSING_OBJECT_STORES="Object stores not created.",xm.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",xm.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",xm.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
xm.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",xm.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",xm.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",xm.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",xm),zm={},Am=(zm.AUTH_INVALID="ERROR",zm.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",zm.EXPLICIT_ABORT="IGNORED",zm.IDB_NOT_SUPPORTED="ERROR",zm.MISSING_INDEX=
"WARNING",zm.MISSING_OBJECT_STORES="ERROR",zm.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",zm.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",zm.QUOTA_EXCEEDED="WARNING",zm.QUOTA_MAYBE_EXCEEDED="WARNING",zm.UNKNOWN_ABORT="WARNING",zm.INCOMPATIBLE_DB_VERSION="WARNING",zm),Bm={},Cm=(Bm.AUTH_INVALID=!1,Bm.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Bm.EXPLICIT_ABORT=!1,Bm.IDB_NOT_SUPPORTED=!1,Bm.MISSING_INDEX=!1,Bm.MISSING_OBJECT_STORES=!1,Bm.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Bm.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Bm.QUOTA_EXCEEDED=!1,Bm.QUOTA_MAYBE_EXCEEDED=!0,Bm.UNKNOWN_ABORT=!0,Bm.INCOMPATIBLE_DB_VERSION=!1,Bm);function Dm(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?ym[a]:c;d=void 0===d?Am[a]:d;e=void 0===e?Cm[a]:e;Yl.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Dm.prototype)}
w(Dm,Yl);function Em(a,b){Dm.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},ym.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Em.prototype)}
w(Em,Dm);function Fm(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Fm.prototype)}
w(Fm,Error);var Gm=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Hm(a,b,c,d){b=tm(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Dm)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Dm("QUOTA_EXCEEDED",a);if(Ge&&"UnknownError"===e.name)return new Dm("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Fm)return new Dm("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Gm.some(function(f){return e.message.includes(f)}))return new Dm("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Dm("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",wd:e.name})];e.level="WARNING";return e}
function Im(a,b,c){var d=im();return new Dm("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Jm(a){if(!a)throw Error();throw a;}
function Km(a){return a}
function Lm(a){this.h=a}
function Mm(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=v(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=v(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Mm.all=function(a){return new Mm(new Lm(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={mb:0};f.mb<a.length;f={mb:f.mb},++f.mb)Mm.resolve(a[f.mb]).then(function(g){return function(h){d[g.mb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Mm.resolve=function(a){return new Mm(new Lm(function(b,c){a instanceof Mm?a.then(b,c):b(a)}))};
Mm.reject=function(a){return new Mm(new Lm(function(b,c){c(a)}))};
Mm.prototype.then=function(a,b){var c=this,d=null!=a?a:Km,e=null!=b?b:Jm;return new Mm(new Lm(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Nm(c,c,d,f,g)}),c.i.push(function(){Om(c,c,e,f,g)})):"FULFILLED"===c.state.status?Nm(c,c,d,f,g):"REJECTED"===c.state.status&&Om(c,c,e,f,g)}))};
Mm.prototype.catch=function(a){return this.then(void 0,a)};
function Nm(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Mm?Pm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Om(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Mm?Pm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Pm(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Mm?Pm(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Qm(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Rm(a){return new Promise(function(b,c){Qm(a,b,c)})}
function Sm(a){return new Mm(new Lm(function(b,c){Qm(a,b,c)}))}
;function Tm(a,b){return new Mm(new Lm(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Um=window,T=Um.ytcsi&&Um.ytcsi.now?Um.ytcsi.now:Um.performance&&Um.performance.timing&&Um.performance.now&&Um.performance.timing.navigationStart?function(){return Um.performance.timing.navigationStart+Um.performance.now()}:function(){return(new Date).getTime()};function Vm(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(T());this.i=!1}
m=Vm.prototype;m.add=function(a,b,c){return Wm(this,[a],{mode:"readwrite",ea:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return Wm(this,[a],{mode:"readwrite",ea:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return Wm(this,[a],{mode:"readonly",ea:!0},function(c){return c.objectStore(a).count(b)})};
function Xm(a,b,c){a=a.h.createObjectStore(b,c);return new Ym(a)}
m.delete=function(a,b){return Wm(this,[a],{mode:"readwrite",ea:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return Wm(this,[a],{mode:"readonly",ea:!0},function(c){return c.objectStore(a).get(b)})};
function Zm(a,b,c){return Wm(a,[b],{mode:"readwrite",ea:!0},function(d){d=d.objectStore(b);return Sm(d.h.put(c,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Wm(a,b,c,d){var e,f,g,h,k,l,n,p,t,r,x,y;return A(function(z){switch(z.h){case 1:var H={mode:"readonly",ea:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?H.mode=c:Object.assign(H,c);e=H;a.transactionCount++;f=e.ea?3:1;g=0;case 2:if(h){z.A(4);break}g++;k=Math.round(T());ya(z,5);l=a.h.transaction(b,e.mode);H=z.yield;var I=new $m(l);I=an(I,d);return H.call(z,I,7);case 7:return n=z.i,p=Math.round(T()),bn(a,k,p,g,void 0,b.join(),e),z.return(n);case 5:t=za(z);r=Math.round(T());x=Hm(t,
a.h.name,b.join(),a.h.version);if((y=x instanceof Dm&&!x.h)||g>=f)bn(a,k,r,g,x,b.join(),e),h=x;z.A(2);break;case 4:return z.return(Promise.reject(h))}})}
function bn(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Dm&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&rm("QUOTA_EXCEEDED",{dbName:tm(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Dm&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),rm("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),cn(a,!1,d,f,b,g.tag),qm(e)):cn(a,!0,d,f,b,g.tag)}
function cn(a,b,c,d,e,f){rm("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function Ym(a){this.h=a}
m=Ym.prototype;m.add=function(a,b){return Sm(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return Sm(this.h.clear()).then(function(){})};
function dn(a,b,c){a.h.createIndex(b,c,{unique:!1})}
m.count=function(a){return Sm(this.h.count(a))};
function en(a,b){return fn(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?en(this,a):Sm(this.h.delete(a))};
m.get=function(a){return Sm(this.h.get(a))};
m.index=function(a){try{return new gn(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Fm(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function fn(a,b,c){a=a.h.openCursor(b.query,b.direction);return hn(a).then(function(d){return Tm(d,c)})}
function $m(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Dm;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function an(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return v(d).next().value})}
$m.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Dm("EXPLICIT_ABORT");};
$m.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new Ym(a),this.i.set(a,b));return b};
function gn(a){this.h=a}
m=gn.prototype;m.count=function(a){return Sm(this.h.count(a))};
m.delete=function(a){return jn(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return Sm(this.h.get(a))};
m.getKey=function(a){return Sm(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function jn(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return hn(a).then(function(d){return Tm(d,c)})}
function kn(a,b){this.request=a;this.cursor=b}
function hn(a){return Sm(a).then(function(b){return b?new kn(a,b):null})}
m=kn.prototype;m.advance=function(a){this.cursor.advance(a);return hn(this.request)};
m.continue=function(a){this.cursor.continue(a);return hn(this.request)};
m.delete=function(){return Sm(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return Sm(this.cursor.update(a))};function ln(a,b,c){return new Promise(function(d,e){function f(){t||(t=new Vm(g.result,{closed:p}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Wd,k=c.blocking,l=c.Ze,n=c.upgrade,p=c.closed,t;g.addEventListener("upgradeneeded",function(r){try{if(null===r.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");r.dataLoss&&"none"!==r.dataLoss&&rm("IDB_DATA_CORRUPTED",{reason:r.dataLossMessage||"unknown reason",dbName:tm(a)});var x=f(),y=new $m(g.transaction);
n&&n(x,function(z){return r.oldVersion<z&&r.newVersion>=z},y);
y.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var r=g.result;k&&r.addEventListener("versionchange",function(){k(f())});
r.addEventListener("close",function(){rm("IDB_UNEXPECTEDLY_CLOSED",{dbName:tm(a),dbVersion:r.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function mn(a,b,c){c=void 0===c?{}:c;return ln(a,b,c)}
function nn(a,b){b=void 0===b?{}:b;var c,d,e,f;return A(function(g){if(1==g.h)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Wd)&&c.addEventListener("blocked",function(){e()}),g.yield(Rm(c),4);
if(2!=g.h)g.h=0,g.l=0;else throw f=za(g),Hm(f,a,"",-1);})}
;function on(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
on.prototype.i=function(a,b,c){c=void 0===c?{}:c;return mn(a,b,c)};
on.prototype.delete=function(a){a=void 0===a?{}:a;return nn(this.name,a)};
function pn(a,b){return new Dm("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function qn(a,b){if(!b)throw Im("openWithToken",tm(a.name));return a.open()}
on.prototype.open=function(){function a(){var f,g,h,k,l,n,p,t,r,x;return A(function(y){switch(y.h){case 1:return g=null!=(f=Error().stack)?f:"",ya(y,2),y.yield(c.i(c.name,c.options.version,e),4);case 4:h=y.i;for(var z=c.options,H=[],I=v(Object.keys(z.Eb)),M=I.next();!M.done;M=I.next()){M=M.value;var L=z.Eb[M],K=void 0===L.He?Number.MAX_VALUE:L.He;!(h.h.version>=L.Mb)||h.h.version>=K||h.h.objectStoreNames.contains(M)||H.push(M)}k=H;if(0===k.length){y.A(5);break}l=Object.keys(c.options.Eb);n=h.objectStoreNames();
if(c.m<Vk("ytidb_reopen_db_retries",0))return c.m++,h.close(),qm(new Dm("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());if(!(c.l<Vk("ytidb_remake_db_retries",1))){y.A(6);break}c.l++;return y.yield(c.delete(),7);case 7:return qm(new Dm("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:n})),y.return(a());case 6:throw new Em(n,l);case 5:return y.return(h);case 2:p=za(y);if(p instanceof DOMException?
"VersionError"!==p.name:"DOMError"in self&&p instanceof DOMError?"VersionError"!==p.name:!(p instanceof Object&&"message"in p)||"An attempt was made to open a database using a lower version than the existing version."!==p.message){y.A(8);break}return y.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:t=y.i;r=t.h.version;if(void 0!==c.options.version&&r>c.options.version+1)throw t.close(),c.j=!1,pn(c,r);return y.return(t);case 8:throw b(),p instanceof Error&&!S("ytidb_async_stack_killswitch")&&
(p.stack=p.stack+"\n"+g.substring(g.indexOf("\n")+1)),Hm(p,c.name,"",null!=(x=c.options.version)?x:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw pn(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Ze:b,upgrade:this.options.upgrade};return this.h=d=a()};var rn=new on("YtIdbMeta",{Eb:{databases:{Mb:1}},upgrade:function(a,b){b(1)&&Xm(a,"databases",{keyPath:"actualName"})}});
function sn(a,b){var c;return A(function(d){if(1==d.h)return d.yield(qn(rn,b),2);c=d.i;return d.return(Wm(c,["databases"],{ea:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Sm(f.h.put(a,void 0)).then(function(){})})}))})}
function tn(a,b){var c;return A(function(d){if(1==d.h)return a?d.yield(qn(rn,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function un(a,b){var c,d;return A(function(e){return 1==e.h?(c=[],e.yield(qn(rn,b),2)):3!=e.h?(d=e.i,e.yield(Wm(d,["databases"],{ea:!0,mode:"readonly"},function(f){c.length=0;return fn(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function vn(a){return un(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function wn(a,b,c){return un(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function xn(a){var b,c;return A(function(d){if(1==d.h)return b=$l("YtIdbMeta hasAnyMeta other"),d.yield(un(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var yn,zn=new function(){}(new function(){});
function An(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=im();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=um)f=/WebKit\/([0-9]+)/.exec(Ob()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Ob()),f=!(f&&602<=parseInt(f[1],10)));if(f||Oc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(sn(d,zn),4);case 4:return e.yield(tn("yt-idb-test-do-not-use",zn),5);case 5:return e.return(!0);case 2:return za(e),e.return(!1)}})}
function Bn(){if(void 0!==yn)return yn;lm=!0;return yn=An().then(function(a){lm=!1;var b;if(null!=(b=hm())&&b.h){var c;b={hasSucceededOnce:(null==(c=im())?void 0:c.hasSucceededOnce)||a};var d;null==(d=hm())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Cn(){return E("ytglobal.idbToken_")||void 0}
function Dn(){var a=Cn();return a?Promise.resolve(a):Bn().then(function(b){(b=b?zn:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var En=0;function Fn(a,b){En||(En=bi.ka(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(Dn(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return h.yield(wn(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(nn(f.actualName),7);case 7:return h.yield(tn(f.actualName,c),6);case 6:h.h=4;h.l=0;break;case 3:g=za(h),qm(g),d=!1;case 4:bi.ya(En),En=0,d&&Fn(a,b),h.h=0}})}))}
function Gn(){var a;return A(function(b){return 1==b.h?b.yield(Dn(),2):(a=b.i)?b.return(xn(a)):b.return(!1)})}
new xh;function Hn(a){if(!Zl())throw a=new Dm("AUTH_INVALID",{dbName:a}),qm(a),a;var b=$l();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function In(a,b,c,d){var e,f,g,h,k,l;return A(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",n.yield(Dn(),2);case 2:g=n.i;if(!g)throw h=Im("openDbImpl",a,b),S("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),qm(h),h;sm(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Hn(a);ya(n,3);return n.yield(sn(k,g),5);case 5:return n.yield(mn(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=za(n),ya(n,7),n.yield(tn(k.actualName,
g),9);case 9:n.h=8;n.l=0;break;case 7:za(n);case 8:throw l;}})}
function Jn(a,b,c){c=void 0===c?{}:c;return In(a,b,!1,c)}
function Kn(a,b,c){c=void 0===c?{}:c;return In(a,b,!0,c)}
function Ln(a,b){b=void 0===b?{}:b;var c,d;return A(function(e){if(1==e.h)return e.yield(Dn(),2);if(3!=e.h){c=e.i;if(!c)return e.return();sm(a);d=Hn(a);return e.yield(nn(d.actualName,b),3)}return e.yield(tn(d.actualName,c),0)})}
function Mn(a,b,c){a=a.map(function(d){return A(function(e){return 1==e.h?e.yield(nn(d.actualName,b),2):e.yield(tn(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Nn(){var a=void 0===a?{}:a;var b,c;return A(function(d){if(1==d.h)return d.yield(Dn(),2);if(3!=d.h){b=d.i;if(!b)return d.return();sm("LogsDatabaseV2");return d.yield(vn(b),3)}c=d.i;return d.yield(Mn(c,a,b),0)})}
function On(a,b){b=void 0===b?{}:b;var c;return A(function(d){if(1==d.h)return d.yield(Dn(),2);if(3!=d.h){c=d.i;if(!c)return d.return();sm(a);return d.yield(nn(a,b),3)}return d.yield(tn(a,c),0)})}
;function Pn(a,b){on.call(this,a,b);this.options=b;sm(a)}
w(Pn,on);function Qn(a,b){var c;return function(){c||(c=new Pn(a,b));return c}}
Pn.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.qc?Kn:Jn)(a,b,Object.assign({},c))};
Pn.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.qc?On:Ln)(this.name,a)};
function Rn(a,b){return Qn(a,b)}
;var Sn={},Tn=Rn("ytGcfConfig",{Eb:(Sn.coldConfigStore={Mb:1},Sn.hotConfigStore={Mb:1},Sn),qc:!1,upgrade:function(a,b){b(1)&&(dn(Xm(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),dn(Xm(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Un(a){return qn(Tn(),a)}
function Vn(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:T()},g.yield(Un(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(Zm(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Wn(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:T()},h.yield(Un(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(Zm(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Xn(a){var b,c;return A(function(d){return 1==d.h?d.yield(Un(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Wm(b,["coldConfigStore"],{mode:"readwrite",ea:!0},function(e){return jn(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Yn(a){var b,c;return A(function(d){return 1==d.h?d.yield(Un(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(Wm(b,["hotConfigStore"],{mode:"readwrite",ea:!0},function(e){return jn(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Zn(){G.apply(this,arguments);this.i=[]}
w(Zn,G);Zn.prototype.M=function(){this.i.length=0;G.prototype.M.call(this)};function $n(){this.h=0;this.i=new Zn}
function ao(){var a;return null!=(a=E("yt.gcf.config.hotConfigGroup"))?a:null}
function bo(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!S("start_client_gcf")){g.A(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.hotHashData=b;D("yt.gcf.config.hotHashData",a.hotHashData||null);d=Cn();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(Yn(d),5);case 5:e=g.i,c=null==(f=e)?void 0:f.config;case 4:return g.yield(Vn(c,b,d),3);case 3:if(c)for(var h=c,k=v(a.i.i),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function co(a,b,c){var d,e,f,g;return A(function(h){if(1==h.h){if(!S("start_client_gcf"))return h.A(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Cn())?c?h.A(4):h.yield(Xn(d),5):h.A(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(Wn(c,b,g,d),0)})}
function eo(){if(!$n.h){var a=new $n;$n.h=a}a=$n.h;var b=T()-a.h;if(!(0!==a.h&&b<Vk("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=T());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
;function fo(){return"INNERTUBE_API_KEY"in Ak&&"INNERTUBE_API_VERSION"in Ak}
function go(){return{innertubeApiKey:R("INNERTUBE_API_KEY"),innertubeApiVersion:R("INNERTUBE_API_VERSION"),pe:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),qd:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Pf:R("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION"),re:R("INNERTUBE_CONTEXT_HL"),qe:R("INNERTUBE_CONTEXT_GL"),se:R("INNERTUBE_HOST_OVERRIDE")||"",ue:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),te:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA")}}
function ho(a){var b={client:{hl:a.re,gl:a.qe,clientName:a.qd,clientVersion:a.innertubeContextClientVersion,configInfo:a.pe}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=Wk();0<c.length&&(b.request={internalExperimentFlags:c});c=a.qd;if(("WEB"===c||"MWEB"===c||1===c||2===c)&&b){var d;b.client.mainAppWebInfo=null!=(d=b.client.mainAppWebInfo)?
d:{};b.client.mainAppWebInfo.webDisplayMode=Gl()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(S("web_log_memory_total_kbytes")&&(null==(e=C.navigator)?0:e.deviceMemory)){var f;e=null==(f=C.navigator)?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+1E6*e)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=Wl())&&b&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&(a=Xl())&&
b&&(b.client.effectiveConnectionType=a);S("start_client_gcf")&&(e=eo())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,a&&f&&e&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.coldConfigData=a,b.client.configInfo.coldHashData=f,b.client.configInfo.hotHashData=e));R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});!S("fill_delegate_context_in_gel_killswitch")&&(a=R("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=v(Object.entries(Ok(R("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=v(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?d.deviceMake=h:"cmodel"===g?d.deviceModel=h:"cbr"===g?d.browserName=h:"cbrver"===g?d.browserVersion=h:"cos"===g?d.osName=h:"cosver"===g?d.osVersion=h:"cplatform"===g&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function io(a,b,c){c=void 0===c?{}:c;var d={};R("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":R("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||R("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().Jf:(a=Dl(Cl()),S("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;function jo(a,b){this.version=a;this.args=b}
jo.prototype.serialize=function(){return{version:this.version,args:this.args}};function ko(a,b){this.topic=a;this.h=b}
ko.prototype.toString=function(){return this.topic};var lo=E("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.Kb;N.prototype.publish=N.prototype.cb;N.prototype.clear=N.prototype.clear;D("ytPubsub2Pubsub2Instance",lo);var mo=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",mo);var no=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",no);var oo=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",oo);
D("ytPubsub2Pubsub2SkipSubKey",null);function po(a,b){var c=qo();c&&c.publish.call(c,a.toString(),a,b)}
function ro(a){var b=so,c=qo();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(mo[d])try{if(f&&b instanceof ko&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Xa){var l=new h;h.Xa=l.version}var n=h.Xa}catch(z){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var p=n.construct;
var t=k.args,r=t.length;if(0<r){var x=Array(r);for(k=0;k<r;k++)x[k]=t[k];var y=x}else y=[];f=p.call(n,h,y)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){Gk(z)}},oo[b.toString()]?E("yt.scheduler.instance")?bi.ka(g):$k(g,0):g())});
mo[d]=!0;no[b.toString()]||(no[b.toString()]=[]);no[b.toString()].push(d);return d}
function to(){var a=uo,b=ro(function(c){a.apply(void 0,arguments);vo(b)});
return b}
function vo(a){var b=qo();b&&("number"===typeof a&&(a=[a]),bb(a,function(c){b.unsubscribeByKey(c);delete mo[c]}))}
function qo(){return E("ytPubsub2Pubsub2Instance")}
;function wo(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&po("meta_logging_csi_event",{timerName:a,fg:b})}
;var xo=Vk("max_body_size_to_compress",5E5),yo=Vk("min_body_size_to_compress",500),zo=!0,Ao=0,Bo=0,Co=Vk("compression_performance_threshold_lr",250),Do=Vk("slow_compressions_before_abandon_count",4);
function Eo(a,b,c,d){var e=T(),f={startTime:e,ticks:{},infos:{}};if(zo)try{var g=Fo(b);if(null==g||!(g>xo||g<yo)){var h=ak(Xh(b)),k=T();f.ticks.gelc=k;Bo++;S("disable_compression_due_to_performance_degredation")&&k-e>=Co&&(Ao++,S("abandon_compression_after_N_slow_zips")?Bo===Vk("compression_disable_point")&&Ao>Do&&(zo=!1):zo=!1);Go(f);c.headers||(c.headers={});c.headers["Content-Encoding"]="gzip";c.postBody=h;c.postParams=void 0}d(a,c)}catch(l){Hk(l),d(a,c)}else d(a,c)}
function Ho(a){var b=void 0===b?!1:b;var c=void 0===c?!1:c;var d=T(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(zo&&f){if(!a.body)return a;try{var g=c?a.body:"string"===typeof a.body?a.body:JSON.stringify(a.body);f=g;if(!c&&"string"===typeof g){var h=Fo(g);if(null!=h&&(h>xo||h<yo))return a;f=ak(Xh(g),b?{level:1}:void 0);var k=T();e.ticks.gelc=k;if(b){Bo++;if((S("disable_compression_due_to_performance_degredation")||S("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Co)if(Ao++,S("abandon_compression_after_N_slow_zips")||S("abandon_compression_after_N_slow_zips_lr")){b=Ao/Bo;var l=Do/Vk("compression_disable_point");0<Bo&&0===Bo%Vk("compression_disable_point")&&b>=l&&(zo=!1)}else zo=!1;Go(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(n){return Hk(n),a}}else return a}
function Fo(a){try{return(new Blob(a.split(""))).size}catch(b){return Hk(b),null}}
function Go(a){S("gel_compression_csi_killswitch")||!S("log_gel_compression_latency")&&!S("log_gel_compression_latency_lr")||wo("gel_compression",a,{sampleRate:.1})}
;function Io(a){a=Object.assign({},a);delete a.Authorization;var b=rg();if(b){var c=new hi;c.update(R("INNERTUBE_API_KEY"));c.update(b);a.hash=Je(c.digest(),3)}return a}
;var Jo;function Ko(){Jo||(Jo=new gm("yt.innertube"));return Jo}
function Lo(a,b,c,d){if(d)return null;d=Ko().get("nextId",!0)||1;var e=Ko().get("requests",!0)||{};e[d]={method:a,request:b,authState:Io(c),requestTime:Math.round(T())};Ko().set("nextId",d+1,86400,!0);Ko().set("requests",e,86400,!0);return d}
function Mo(a){var b=Ko().get("requests",!0)||{};delete b[a];Ko().set("requests",b,86400,!0)}
function No(a){var b=Ko().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=Io(io(!1));ob(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),Oo(a,d.method,e,{}));delete b[c]}}Ko().set("requests",b,86400,!0)}}
;function Po(a){this.Zb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.wb=function(){};
this.now=Date.now;this.Pb=!1;var b;this.Id=null!=(b=a.Id)?b:100;var c;this.Cd=null!=(c=a.Cd)?c:1;var d;this.Ad=null!=(d=a.Ad)?d:2592E6;var e;this.yd=null!=(e=a.yd)?e:12E4;var f;this.Bd=null!=(f=a.Bd)?f:5E3;var g;this.R=null!=(g=a.R)?g:void 0;this.fc=!!a.fc;var h;this.dc=null!=(h=a.dc)?h:.1;var k;this.mc=null!=(k=a.mc)?k:10;a.handleError&&(this.handleError=a.handleError);a.wb&&(this.wb=a.wb);a.Pb&&(this.Pb=a.Pb);a.Zb&&(this.Zb=a.Zb);this.S=a.S;this.Ba=a.Ba;this.Y=a.Y;this.X=a.X;this.Pa=a.Pa;this.Oc=
a.Oc;this.Nc=a.Nc;Qo(this)&&(!this.S||this.S("networkless_logging"))&&Ro(this)}
function Ro(a){Qo(a)&&!a.Pb&&(a.h=!0,a.fc&&Math.random()<=a.dc&&a.Y.Yd(a.R),So(a),a.X.qa()&&a.Tb(),a.X.listen(a.Oc,a.Tb.bind(a)),a.X.listen(a.Nc,a.dd.bind(a)))}
m=Po.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Qo(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y.set(d,this.R).then(function(e){d.id=e;c.X.qa()&&To(c,d)}).catch(function(e){To(c,d);
Uo(c,e)})}else this.Pa(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Qo(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.S&&this.S("nwl_skip_retry")&&(e.skipRetry=c);if(this.X.qa()||this.S&&this.S("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(1==k.h)return k.yield(d.Y.set(e,d.R).catch(function(l){Uo(d,l)}),2);
f(g,h);k.h=0})}}this.Pa(a,b,e.skipRetry)}else this.Y.set(e,this.R).catch(function(g){d.Pa(a,b,e.skipRetry);
Uo(d,g)})}else this.Pa(a,b,this.S&&this.S("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Qo(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.Y.sb(d.id,c.R):e=!0;c.X.gb&&c.S&&c.S("vss_network_hint")&&c.X.gb(!0);f(g,h)};
this.Pa(d.url,d.options);this.Y.set(d,this.R).then(function(g){d.id=g;e&&c.Y.sb(d.id,c.R)}).catch(function(g){Uo(c,g)})}else this.Pa(a,b)};
m.Tb=function(){var a=this;if(!Qo(this))throw Im("throttleSend");this.i||(this.i=this.Ba.ka(function(){var b;return A(function(c){if(1==c.h)return c.yield(a.Y.nd("NEW",a.R),2);if(3!=c.h)return b=c.i,b?c.yield(To(a,b),3):(a.dd(),c.return());a.i&&(a.i=0,a.Tb());c.h=0})},this.Id))};
m.dd=function(){this.Ba.ya(this.i);this.i=0};
function To(a,b){var c,d;return A(function(e){switch(e.h){case 1:if(!Qo(a))throw c=Im("immediateSend"),c;if(void 0===b.id){e.A(2);break}return e.yield(a.Y.xe(b.id,a.R),3);case 3:(d=e.i)||a.wb(Error("The request cannot be found in the database."));case 2:if(Vo(a,b,a.Ad)){e.A(4);break}a.wb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return e.yield(a.Y.sb(b.id,a.R),5);case 5:return e.return();case 4:b.skipRetry||(b=Wo(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return e.yield(a.Y.sb(b.id,a.R),8);case 8:a.Pa(b.url,b.options,!!b.skipRetry),e.h=0}})}
function Wo(a,b){if(!Qo(a))throw Im("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(n){switch(n.h){case 1:g=Xo(f);(h=Yo(f))&&a.S&&a.S("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.S&&a.S("nwl_consider_error_code")&&g||a.S&&!a.S("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.mc)){n.A(2);break}if(!a.X.pc){n.A(3);break}return n.yield(a.X.pc(),3);case 3:if(a.X.qa()){n.A(2);break}c(e,f);if(!a.S||!a.S("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.A(6);
break}return n.yield(a.Y.Rc(b.id,a.R,!1),6);case 6:return n.return();case 2:if(a.S&&a.S("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.mc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(l=b)?void 0:l.id)){n.A(8);break}return b.sendCount<a.Cd?n.yield(a.Y.Rc(b.id,a.R,!0,h?!1:void 0),12):n.yield(a.Y.sb(b.id,a.R),8);case 12:a.Ba.ka(function(){a.X.qa()&&a.Tb()},a.Bd);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):h.yield(a.Y.sb(b.id,a.R),2);a.X.gb&&a.S&&a.S("vss_network_hint")&&a.X.gb(!0);d(e,f);h.h=0})};
return b}
function Vo(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function So(a){if(!Qo(a))throw Im("retryQueuedRequests");a.Y.nd("QUEUED",a.R).then(function(b){b&&!Vo(a,b,a.yd)?a.Ba.ka(function(){return A(function(c){if(1==c.h)return void 0===b.id?c.A(2):c.yield(a.Y.Rc(b.id,a.R),2);So(a);c.h=0})}):a.X.qa()&&a.Tb()})}
function Uo(a,b){a.Od&&!a.X.qa()?a.Od(b):a.handleError(b)}
function Qo(a){return!!a.R||a.Zb}
function Xo(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function Yo(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var Zo;
function $o(){if(Zo)return Zo();var a={};Zo=Rn("LogsDatabaseV2",{Eb:(a.LogsRequestsStore={Mb:2},a),qc:!1,upgrade:function(b,c,d){c(2)&&Xm(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),dn(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Zo()}
;function ap(a){return qn($o(),a)}
function bp(a,b){var c,d,e,f;return A(function(g){if(1==g.h)return c={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(ap(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:R("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(Zm(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=T();cp(c);return g.return(f)})}
function dp(a,b){var c,d,e,f,g,h,k;return A(function(l){if(1==l.h)return c={startTime:T(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},l.yield(ap(b),2);if(3!=l.h)return d=l.i,e=R("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,T()],h=IDBKeyRange.bound(f,g),k=void 0,l.yield(Wm(d,["LogsRequestsStore"],{mode:"readwrite",ea:!0},function(n){return jn(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===
a&&(k.status="QUEUED",p.update(k)))})}),3);
c.ticks.tc=T();cp(c);return l.return(k)})}
function ep(a,b){var c;return A(function(d){if(1==d.h)return d.yield(ap(b),2);c=d.i;return d.return(Wm(c,["LogsRequestsStore"],{mode:"readwrite",ea:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Sm(f.h.put(g,void 0)).then(function(){return g})})}))})}
function fp(a,b,c,d){c=void 0===c?!0:c;var e;return A(function(f){if(1==f.h)return f.yield(ap(b),2);e=f.i;return f.return(Wm(e,["LogsRequestsStore"],{mode:"readwrite",ea:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),Sm(h.h.put(k,void 0)).then(function(){return k})):Mm.resolve(void 0)})}))})}
function gp(a,b){var c;return A(function(d){if(1==d.h)return d.yield(ap(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function hp(a){var b,c;return A(function(d){if(1==d.h)return d.yield(ap(a),2);b=d.i;c=T()-2592E6;return d.yield(Wm(b,["LogsRequestsStore"],{mode:"readwrite",ea:!0},function(e){return fn(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function ip(){A(function(a){return a.yield(Nn(),0)})}
function cp(a){S("nwl_csi_killswitch")||wo("networkless_performance",a,{sampleRate:1})}
;var jp={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,mbsConnectionInitiated:138,mbsPlaybackInitiated:139,
mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,
kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,transactionFlowPaymentSubmitted:460,
transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,ypcPauseFlowSucceeded:190,
ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,ypcFamilyCreateFlowCancelled:259,
ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,accountRegistryChange:226,
userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,musicSideloadedPlaylistServiceCalled:246,
embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,tvhtml5ApiTest:270,yongleUsbSetup:271,touStrikeInterstitialEvent:272,
liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,
delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,
voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,
sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,
clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,
startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,
playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,genericClientExperimentEvent:423,
homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,
dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,
producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,
cobaltTelemetryEvent:481};var kp={},lp=Rn("ServiceWorkerLogsDatabase",{Eb:(kp.SWHealthLog={Mb:1},kp),qc:!0,upgrade:function(a,b){b(1)&&dn(Xm(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function mp(a){return qn(lp(),a)}
function np(a){var b,c;A(function(d){if(1==d.h)return d.yield(mp(a),2);b=d.i;c=T()-2592E6;return d.yield(Wm(b,["SWHealthLog"],{mode:"readwrite",ea:!0},function(e){return fn(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function op(a){var b;return A(function(c){if(1==c.h)return c.yield(mp(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var pp={},qp=0;function rp(a){var b=new Image,c=""+qp++;pp[c]=b;b.onload=b.onerror=function(){delete pp[c]};
b.src=a}
;function sp(){this.h=new Map;this.i=!1}
function tp(){if(!sp.h){var a=E("yt.networkRequestMonitor.instance")||new sp;D("yt.networkRequestMonitor.instance",a);sp.h=a}return sp.h}
sp.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
sp.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
sp.prototype.removeParams=function(a){return a.split("?")[0]};
sp.prototype.removeParams=sp.prototype.removeParams;sp.prototype.isEndpointCFR=sp.prototype.isEndpointCFR;sp.prototype.requestComplete=sp.prototype.requestComplete;sp.getInstance=tp;var up;function vp(){up||(up=new gm("yt.offline"));return up}
function wp(a){if(S("offline_error_handling")){var b=vp().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);vp().set("errors",b,2592E3,!0)}}
;function xp(){yd.call(this);var a=this;this.j=!1;this.i=ai();this.i.listen("networkstatus-online",function(){if(a.j&&S("offline_error_handling")){var b=vp().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new Yl(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Gk(d)}vp().set("errors",{},2592E3,!0)}}})}
w(xp,yd);function yp(){if(!xp.h){var a=E("yt.networkStatusManager.instance")||new xp;D("yt.networkStatusManager.instance",a);xp.h=a}return xp.h}
m=xp.prototype;m.qa=function(){return this.i.qa()};
m.gb=function(a){this.i.i=a};
m.me=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.ce=function(){this.j=!0};
m.listen=function(a,b){return this.i.listen(a,b)};
m.pc=function(a){a=Zh(this.i,a);a.then(function(b){S("use_cfr_monitor")&&tp().requestComplete("generate_204",b)});
return a};
xp.prototype.sendNetworkCheckRequest=xp.prototype.pc;xp.prototype.listen=xp.prototype.listen;xp.prototype.enableErrorFlushing=xp.prototype.ce;xp.prototype.getWindowStatus=xp.prototype.me;xp.prototype.networkStatusHint=xp.prototype.gb;xp.prototype.isNetworkAvailable=xp.prototype.qa;xp.getInstance=yp;function zp(a){a=void 0===a?{}:a;yd.call(this);var b=this;this.i=this.s=0;this.j=yp();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.oc?(this.oc=a.oc,c("networkstatus-online",function(){Ap(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Ap(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){zd(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){zd(b,"publicytnetworkstatus-offline")})))}
w(zp,yd);zp.prototype.qa=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
zp.prototype.gb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
zp.prototype.pc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return S("skip_network_check_if_cfr")&&tp().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.gb((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.qa())})):c?d.return(c(a)):d.return(!0)})};
function Ap(a,b){a.oc?a.i?(bi.ya(a.s),a.s=bi.ka(function(){a.m!==b&&(zd(a,b),a.m=b,a.i=T())},a.oc-(T()-a.i))):(zd(a,b),a.m=b,a.i=T()):zd(a,b)}
;var Bp;function Cp(){var a=Po.call;Bp||(Bp=new zp({Uf:!0,Nf:!0}));a.call(Po,this,{Y:{Yd:hp,sb:gp,nd:dp,xe:ep,Rc:fp,set:bp},X:Bp,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;Hk(new Yl(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else Gk(b)},
wb:Hk,Pa:Dp,now:T,Od:wp,Ba:fm(),Oc:"publicytnetworkstatus-online",Nc:"publicytnetworkstatus-offline",fc:!0,dc:.1,mc:Vk("potential_esf_error_limit",10),S:S,Pb:!(Zl()&&Ep())});this.j=new xh;S("networkless_immediately_drop_all_requests")&&ip();On("LogsDatabaseV2")}
w(Cp,Po);function Fp(){var a=E("yt.networklessRequestController.instance");a||(a=new Cp,D("yt.networklessRequestController.instance",a),S("networkless_logging")&&Dn().then(function(b){a.R=b;Ro(a);a.j.resolve();a.fc&&Math.random()<=a.dc&&a.R&&np(a.R);S("networkless_immediately_drop_sw_health_store")&&Gp(a)}));
return a}
Cp.prototype.writeThenSend=function(a,b){b||(b={});Zl()||(this.h=!1);Po.prototype.writeThenSend.call(this,a,b)};
Cp.prototype.sendThenWrite=function(a,b,c){b||(b={});Zl()||(this.h=!1);Po.prototype.sendThenWrite.call(this,a,b,c)};
Cp.prototype.sendAndWrite=function(a,b){b||(b={});Zl()||(this.h=!1);Po.prototype.sendAndWrite.call(this,a,b)};
Cp.prototype.awaitInitialization=function(){return this.j.promise};
function Gp(a){var b;A(function(c){if(!a.R)throw b=Im("clearSWHealthLogsDb"),b;return c.return(op(a.R).catch(function(d){a.handleError(d)}))})}
function Dp(a,b,c){b=S("web_fp_via_jspb")?Object.assign({},b):b;S("use_cfr_monitor")&&Hp(a,b);if(S("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(T())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;var g=void 0===g?!1:g;if(a)if(e)jl(a,void 0,"POST",e);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))jl(a,void 0,"GET",
"",void 0,void 0,f,g);else{b:{try{var h=new Ya({url:a});if(h.j&&h.i||h.l){var k=ec(fc(5,a)),l;if(!(l=!k||!k.endsWith("/aclk"))){var n=a.search(sc),p=rc(a,0,"ri",n);if(0>p)var t=null;else{var r=a.indexOf("&",p);if(0>r||r>n)r=n;t=decodeURIComponent(a.slice(p+3,-1!==r?r:0).replace(/\+/g," "))}l="1"!==t}var x=!l;break b}}catch(z){}x=!1}if(x){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var y=!0;break b}}catch(z){}y=!1}c=y?!0:!1}else c=!1;c||rp(a)}}else b.compress?
b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),Eo(a,b.postBody,b,gl)):Eo(a,JSON.stringify(b.postParams),b,ol):gl(a,b)}
function Hp(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){tp().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){tp().requestComplete(a,!0);d(e,f)}}
function Ep(){return"www.youtube-nocookie.com"!==hc(document.location.toString())}
;var Ip=!1,Jp=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Ip};D("ytNetworklessLoggingInitializationOptions",Jp);function Kp(){var a;A(function(b){if(1==b.h)return b.yield(Dn(),2);a=b.i;if(!a||!Zl()&&!S("nwl_init_require_datasync_id_killswitch")||!Ep())return b.A(0);Ip=!0;Jp.isNwlInitialized=Ip;return b.yield(Fp().awaitInitialization(),0)})}
;function Lp(a){var b=this;this.config_=null;a?this.config_=a:fo()&&(this.config_=go());bm(function(){No(b)},5E3)}
Lp.prototype.isReady=function(){!this.config_&&fo()&&(this.config_=go());return!!this.config_};
function Oo(a,b,c,d){function e(x){x=void 0===x?!1:x;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(x||S("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=Lo(b,c,l,k)),y)){var z=g.onSuccess,H=g.onFetchSuccess;g.onSuccess=function(M,L){Mo(y);z(M,L)};
c.onFetchSuccess=function(M,L){Mo(y);H(M,L)}}try{if(x&&d.retry&&!d.td.bypassNetworkless)g.method="POST",d.td.writeThenSend?Fp().writeThenSend(r,g):Fp().sendAndWrite(r,g);
else if(d.compress)if(g.postBody){var I=g.postBody;"string"!==typeof I&&(I=JSON.stringify(g.postBody));Eo(r,I,g,gl)}else Eo(r,JSON.stringify(g.postParams),g,ol);else S("web_all_payloads_via_jspb")?gl(r,g):ol(r,g)}catch(M){if("InvalidAccessError"==M.name)y&&(Mo(y),y=0),Hk(Error("An extension is blocking network request."));else throw M;}y&&bm(function(){No(a)},5E3)}
!R("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Hk(new Yl("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Yl("innertube xhrclient not ready",b,c,d);Gk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(x,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,y){if(d.onError)d.onError(y)},
onFetchError:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.se)&&(h=f);var k=a.config_.ue||!1,l=io(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},t=a.config_.te&&f;t=t&&f.startsWith("Bearer");t||(p.key=a.config_.innertubeApiKey);var r=Qk(""+h+n,p||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
Jp.isNwlInitialized:Ip)?Bn().then(function(x){e(x)}):e(!1)}
;var Mp=0,Np=Qc?"webkit":Pc?"moz":Nc?"ms":Mc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++Mp});var Op={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Pp(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Op||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Qp(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Pp.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Pp.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Pp.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var kb=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",kb);var Rp=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",Rp);
function Sp(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return jb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Na(e[4])&&Na(d)&&ob(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Tp=$a(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Up(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Sp(a,b,c,d);if(e)return e;e=++Rp.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Pp(h);if(!Id(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Pp(h);
h.currentTarget=a;return c.call(a,h)};
g=Fk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Tp()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);kb[e]=[a,b,c,g,d];return e}
function Vp(a){a&&("string"==typeof a&&(a=[a]),bb(a,function(b){if(b in kb){var c=kb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Tp()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete kb[b]}}))}
;function Wp(a){this.P=a;this.i=null;this.m=0;this.v=null;this.s=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.W=Up(window,"mousemove",Ta(this.Z,this));a=Ta(this.V,this);"function"===typeof a&&(a=Fk(a));this.ba=window.setInterval(a,25)}
Va(Wp,G);Wp.prototype.Z=function(a){void 0===a.h&&Qp(a);var b=a.h;void 0===a.i&&Qp(a);this.i=new Ed(b,a.i)};
Wp.prototype.V=function(){if(this.i){var a=T();if(0!=this.m){var b=this.v,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.P();this.s=d}this.m=a;this.v=this.i;this.l=(this.l+1)%4}};
Wp.prototype.M=function(){window.clearInterval(this.ba);Vp(this.W)};var Xp=new Set([174,173,175]),Yp={};
function Zp(a){var b=void 0===a?{}:a;a=void 0===b.Ee?!1:b.Ee;b=void 0===b.de?!0:b.de;if(null==E("_lact",window)){var c=parseInt(R("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);-1==c&&$p();Up(document,"keydown",$p);Up(document,"keyup",$p);Up(document,"mousedown",$p);Up(document,"mouseup",$p);a?Up(window,"touchmove",function(){aq("touchmove",200)},{passive:!0}):(Up(window,"resize",function(){aq("resize",200)}),b&&Up(window,"scroll",function(){aq("scroll",
200)}));
new Wp(function(){aq("mouse",100)});
Up(document,"touchstart",$p,{passive:!0});Up(document,"touchend",$p,{passive:!0})}}
function aq(a,b){Yp[a]||(Yp[a]=!0,bi.ka(function(){$p();Yp[a]=!1},b))}
function $p(a){var b;if(null!=(b=E("experiment.flags",window))&&b.enable_lact_reset_by_volume_buttons||!Xp.has(null==a?void 0:a.keyCode))null==E("_lact",window)&&Zp(),a=Date.now(),D("_lact",a,window),-1==E("_fact",window)&&D("_fact",a,window),(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function bq(){var a=E("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var cq=C.ytPubsubPubsubInstance||new N,dq=C.ytPubsubPubsubSubscribedKeys||{},eq=C.ytPubsubPubsubTopicToKeys||{},fq=C.ytPubsubPubsubIsSynchronous||{};function gq(a,b){var c=hq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){dq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{fq[a]?f():$k(f,0)}catch(g){Gk(g)}},void 0);
dq[d]=!0;eq[a]||(eq[a]=[]);eq[a].push(d);return d}return 0}
function iq(a){var b=hq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),bb(a,function(c){b.unsubscribeByKey(c);delete dq[c]}))}
function jq(a,b){var c=hq();c&&c.publish.apply(c,arguments)}
function kq(a){var b=hq();if(b)if(b.clear(a),a)oq(a);else for(var c in eq)oq(c)}
function hq(){return C.ytPubsubPubsubInstance}
function oq(a){eq[a]&&(a=eq[a],bb(a,function(b){dq[b]&&delete dq[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.Kb;N.prototype.publish=N.prototype.cb;N.prototype.clear=N.prototype.clear;D("ytPubsubPubsubInstance",cq);D("ytPubsubPubsubTopicToKeys",eq);D("ytPubsubPubsubIsSynchronous",fq);D("ytPubsubPubsubSubscribedKeys",dq);var pq=Symbol("injectionDeps");function qq(a){this.name=a}
qq.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function rq(a){this.key=a}
function sq(){this.h=new Map;this.i=new Map}
sq.prototype.resolve=function(a){return a instanceof rq?tq(this,a.key,[],!0):tq(this,a,[])};
function tq(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Ld)var e=d.Ld;else if(d.ef)e=d[pq]?uq(a,d[pq],c):[],e=d.ef.apply(d,ia(e));else if(d.Kd){e=d.Kd;var f=e[pq]?uq(a,e[pq],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.dg||a.i.set(b,e);return e}
function uq(a,b,c){return b?b.map(function(d){return d instanceof rq?tq(a,d.key,c,!0):tq(a,d,c)}):[]}
;var vq;function wq(){vq||(vq=new sq);return vq}
;var xq=window;function yq(){var a,b;return"h5vcc"in xq&&(null==(a=xq.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=xq.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in xq&&xq.performance.mark&&xq.performance.measure?2:0}
function zq(a){switch(yq()){case 1:xq.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:xq.performance.mark(a+"-start");break;case 0:break;default:Ih()}}
function Aq(a){switch(yq()){case 1:xq.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";xq.performance.mark(c);xq.performance.measure(a,b,c);break;case 0:break;default:Ih()}}
;var Bq=S("web_enable_lifecycle_monitoring")&&0!==yq();function Cq(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?fm():d;this.j=c;this.scheduler=d;this.i=new xh;this.h=a;for(a={ab:0};a.ab<this.h.length;a={Jb:a.Jb,ab:a.ab},a.ab++)a.Jb=this.h[a.ab],c=function(e){return function(){e.Jb.Ic();b.h[e.ab].nc=!0;b.h.every(function(f){return!0===f.nc})&&b.i.resolve()}}(a),d=this.getPriority(a.Jb),d=cm(c,d),this.h[a.ab]=Object.assign({},a.Jb,{Ic:c,
jobId:d})}
function Dq(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=v(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.nc||(a.scheduler.ya(c.jobId),cm(c.Ic,10))}
Cq.prototype.cancel=function(){for(var a=v(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.nc||this.scheduler.ya(b.jobId),b.nc=!0;this.i.resolve()};
Cq.prototype.getPriority=function(a){var b;return null!=(b=a.priority)?b:this.j};function Eq(a){this.state=a;this.plugins=[];this.l=void 0;this.v={};Bq&&zq(this.state)}
m=Eq.prototype;m.install=function(a){this.plugins.push(a);return this};
m.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
m.transition=function(a,b){var c=this;Bq&&Aq(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Dq(this.j),this.j=void 0);Fq(this,a,b);this.state=a;Bq&&zq(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Gq(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Gq(a,b){var c=b.filter(function(e){return 10===Hq(a,e)}),d=b.filter(function(e){return 10!==Hq(a,e)});
return a.v.cg?function(){var e=B.apply(0,arguments);return A(function(f){if(1==f.h)return f.yield(a.Ke.apply(a,[c].concat(ia(e))),2);a.Fd.apply(a,[d].concat(ia(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Le.apply(a,[c].concat(ia(e)));a.Fd.apply(a,[d].concat(ia(e)))}}
m.Le=function(a){var b=B.apply(1,arguments);fm();for(var c=v(a),d=c.next(),e={};!d.done;e={nb:e.nb},d=c.next())e.nb=d.value,dm(function(f){return function(){Iq(f.nb.name);f.nb.callback.apply(f.nb,ia(b));Jq(f.nb.name)}}(e))};
m.Ke=function(a){var b=B.apply(1,arguments),c,d,e,f;return A(function(g){1==g.h&&(fm(),c=v(a),d=c.next(),e={});if(3!=g.h){if(d.done)return g.A(0);e.bb=d.value;e.Hb=void 0;f=function(h){return function(){Iq(h.bb.name);var k=h.bb.callback.apply(h.bb,ia(b));"function"===typeof(null==k?void 0:k.then)?h.Hb=k.then(function(){Jq(h.bb.name)}):Jq(h.bb.name)}}(e);
dm(f);return e.Hb?g.yield(e.Hb,3):g.A(3)}e={bb:e.bb,Hb:e.Hb};d=c.next();return g.A(2)})};
m.Fd=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{Ic:function(){Iq(e.name);e.callback.apply(e,ia(b));Jq(e.name)},
priority:Hq(c,e)}});
d.length&&(this.j=new Cq(d))};
function Hq(a,b){var c,d;return null!=(d=null!=(c=a.l)?c:b.priority)?d:0}
function Iq(a){Bq&&a&&zq(a)}
function Jq(a){Bq&&a&&Aq(a)}
function Fq(a,b,c){Bq&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(Eq.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Kq(a){Eq.call(this,void 0===a?"none":a);this.h=null;this.l=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.m},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var Lq;w(Kq,Eq);Kq.prototype.i=function(a,b){var c=this;this.h=bm(function(){"application_navigating"===c.currentState&&c.transition("none")},5E3);
a(null==b?void 0:b.event)};
Kq.prototype.m=function(a,b){this.h&&(bi.ya(this.h),this.h=null);a(null==b?void 0:b.event)};
function Mq(){Lq||(Lq=new Kq);return Lq}
;function Nq(){this.store={};this.h={}}
Nq.prototype.storePayload=function(a,b){a=Oq(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
Nq.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=Pq(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ia(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ia(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ia(this.smartExtractMatchingEntries(a))));return c};
Nq.prototype.extractMatchingEntries=function(a){a=Pq(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ia(this.store[a[c]])),delete this.store[a[c]]);return b};
Nq.prototype.getSequenceCount=function(a){a=Pq(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function Pq(a,b){var c=Oq(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&Oq(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(Qq(b.auth,g[0])){var h=b.isJspb;Qq(void 0===h?"undefined":h?"true":"false",g[1])&&Qq(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),Qq(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function Qq(a,b){return void 0===a||"undefined"===a?!0:a===b}
Nq.prototype.getSequenceCount=Nq.prototype.getSequenceCount;Nq.prototype.extractMatchingEntries=Nq.prototype.extractMatchingEntries;Nq.prototype.smartExtractMatchingEntries=Nq.prototype.smartExtractMatchingEntries;Nq.prototype.storePayload=Nq.prototype.storePayload;function Oq(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;function U(a,b){if(a)return a[b.name]}
;var Rq=Vk("initial_gel_batch_timeout",2E3),Sq=Vk("gel_queue_timeout_max_ms",6E4),Tq=Math.pow(2,16)-1,Uq=void 0;function Vq(){this.j=this.h=this.i=0}
var Wq=new Vq,Xq=new Vq,Yq=new Vq,Zq=new Vq,$q,ar=!0,br=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",br);var cr={};function dr(){var a=E("yt.logging.ims");a||(a=new Nq,D("yt.logging.ims",a));return a}
function er(a,b){if("log_event"===a.endpoint){var c=fr(a);a:{var d=Object.keys(a.payload);d=v(d);for(var e=d.next();!e.done;e=d.next())if(e=e.value,jp[e]){d=e;break a}d=void 0}var f;a:if(S("enable_web_tiered_gel")){d=jp[d||""];var g,h;if(e=null==wq().resolve(new rq($n))?void 0:null==(f=ao())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.eventLoggingConfig)?void 0:h.payloadPolicies)for(f=0;f<e.length;f++)if(e[f].payloadNumber===d){f=gr(e[f].tier);break a}f=200}else f=void 0;400===f?hr(a,b):
(cr[c]=!0,f={cttAuthInfo:c,isJspb:!1,tier:f},dr().storePayload(f,a.payload),ir(b,c,f))}}
function ir(a,b,c){function d(){jr({writeThenSend:!0},S("flush_only_full_queue")?b:void 0,e,c.tier)}
var e=!1;e=void 0===e?!1:e;a&&(Uq=new a);a=Vk("tvhtml5_logging_max_batch_ads_fork")||Vk("web_logging_max_batch")||100;var f=T(),g=kr(e,c.tier),h=g.j,k=0;c&&(k=dr().getSequenceCount(c));1E3<=k?d():k>=a?$q||($q=lr(function(){d();$q=void 0},0)):10<=f-h&&(mr(e,c.tier),g.j=f)}
function hr(a,b){if("log_event"===a.endpoint){var c=fr(a),d=new Map;d.set(c,[a.payload]);b&&(Uq=new b);return new Vd(function(e,f){Uq&&Uq.isReady()?nr(d,Uq,e,f,{bypassNetworkless:!0},!0):e()})}}
function fr(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);br[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function jr(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new Vd(function(e,f){var g=kr(c,d);or(g.i);or(g.h);g.h=0;Uq&&Uq.isReady()?void 0===d&&S("enable_web_tiered_gel")?pr(e,f,a,b,c,300):pr(e,f,a,b,c,d):(mr(c,d),e())})}
function pr(a,b,c,d,e,f){var g=Uq;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;var h=new Map;var k={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(void 0!==d)f=S("enable_web_tiered_gel")?dr().smartExtractMatchingEntries({keys:[k,e],sizeLimit:1E3}):dr().extractMatchingEntries(e),h.set(d,f);else for(d=v(Object.keys(cr)),k=d.next();!k.done;k=d.next())k=k.value,e=S("enable_web_tiered_gel")?dr().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:k,tier:f},{isJspb:!1,cttAuthInfo:k}],
sizeLimit:1E3}):dr().extractMatchingEntries({isJspb:!1,cttAuthInfo:k}),0<e.length&&h.set(k,e),(S("web_fp_via_jspb_and_json")&&c.writeThenSend||!S("web_fp_via_jspb_and_json"))&&delete cr[k];nr(h,g,a,b,c)}
function mr(a,b){a=void 0===a?!1:a;b=void 0===b?200:b;var c=kr(a,b),d=c===Zq||c===Yq?5E3:Sq;S("web_gel_timeout_cap")&&!c.h&&(d=lr(function(){jr({writeThenSend:!0},void 0,a,b)},d),c.h=d);
or(c.i);d=R("LOGGING_BATCH_TIMEOUT",Vk("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&ar&&(d=Rq);d=lr(function(){jr({writeThenSend:!0},void 0,a,b)},d);
c.i=d}
function nr(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(T()),h=a.size;a=v(a);for(var k=a.next(),l={};!k.done;l={Ub:l.Ub,Za:l.Za,Ib:l.Ib,Wb:l.Wb,Vb:l.Vb},k=a.next()){var n=v(k.value);k=n.next().value;n=n.next().value;l.Za=qb({context:ho(b.config_||go())});if(!Ma(n)&&!S("throw_err_when_logevent_malformed_killswitch")){d();break}l.Za.events=n;(n=br[k])&&qr(l.Za,k,n);delete br[k];l.Ib="visitorOnlyApprovedKey"===k;rr(l.Za,g,l.Ib);S("always_send_and_write")&&(e.writeThenSend=!1);l.Wb=function(p){S("start_client_gcf")&&
bi.ka(function(){return A(function(t){return t.yield(sr(p),0)})});
h--;h||c()};
l.Ub=0;l.Vb=function(p){return function(){p.Ub++;if(e.bypassNetworkless&&1===p.Ub)try{Oo(b,"log_event",p.Za,tr({writeThenSend:!0},p.Ib,p.Wb,p.Vb,f)),ar=!1}catch(t){Gk(t),d()}h--;h||c()}}(l);
try{Oo(b,"log_event",l.Za,tr(e,l.Ib,l.Wb,l.Vb,f)),ar=!1}catch(p){Gk(p),d()}}}
function tr(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,td:a,dangerousLogToVisitorSession:b,Kf:!!e,headers:{},postBodyFormat:"",postBody:"",compress:S("compress_gel")||S("compress_gel_lr")};ur()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));return a}
function rr(a,b,c){ur()||(a.requestTimeMs=String(b));S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=R("EVENT_ID"))&&((c=R("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*Tq/2)),c++,c>Tq&&(c=1),Bk("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function qr(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function ur(){return S("use_request_time_ms_header")||S("lr_use_request_time_ms_header")}
function lr(a,b){return S("transport_use_scheduler")?S("logging_avoid_blocking_during_navigation")||S("lr_logging_avoid_blocking_during_navigation")?bm(function(){if("none"===Mq().currentState)a();else{var c={};Mq().install((c.none={callback:a},c))}},b):bm(a,b):$k(a,b)}
function or(a){S("transport_use_scheduler")?bi.ya(a):window.clearTimeout(a)}
function sr(a){var b,c,d,e,f,g,h,k,l,n;return A(function(p){return 1==p.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=U(d,ek),g=null==(f=d)?void 0:f.hotHashData,h=U(d,dk),l=null==(k=d)?void 0:k.coldHashData,(n=wq().resolve(new rq($n)))?g?e?p.yield(bo(n,g,e),2):p.yield(bo(n,g),2):p.A(2):p.return()):l?h?p.yield(co(n,l,h),0):p.yield(co(n,l),0):p.A(0)})}
function kr(a,b){b=void 0===b?200:b;return a?300===b?Zq:Xq:300===b?Yq:Wq}
function gr(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var vr=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",vr);
function wr(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||T());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=bq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!S("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,vr[b]=b in vr?vr[b]+1:0,a.sequence={index:vr[b],groupKey:b},d.endOfSequence&&delete vr[d.sequenceGroup]);(d.sendIsolatedPayload?hr:er)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function pm(a,b,c){c=void 0===c?{}:c;var d=Lp;R("ytLoggingEventsDefaultDisabled",!1)&&Lp===Lp&&(d=null);S("web_all_payloads_via_jspb")&&!c.timestamp&&(c.lact=bq(),c.timestamp=T());wr(a,b,d,c)}
;D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var xr=new Set,yr=0,zr=0,Ar=0,Br=[],Cr=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function om(a){Dr(a)}
function Er(a){Dr(a,"WARNING")}
function Fr(a){a instanceof Error?Dr(a):(a=Na(a)?JSON.stringify(a):String(a),a=new Yl(a),a.name="RejectedPromiseError",Er(a))}
function Dr(a,b,c,d,e,f,g,h){f=void 0===f?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;b=void 0===b?"ERROR":b;g=void 0===g?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),S("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(5<=yr))){d=Br;var k=Ec(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var n=l.split("\n");n.shift();l=n.join("\n")}n=k.lineNumber||"Not available";k=k.fileName||"Not available";var p=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var t=0;t<a.args.length&&!(p=yl(a.args[t],"params."+t,c,p),
500<=p);t++);else if(a.hasOwnProperty("params")&&a.params){var r=a.params;if("object"===typeof a.params)for(t in r){if(r[t]){var x="params."+t,y=Al(r[t]);c[x]=y;p+=x.length+y.length;if(500<p)break}}else c.params=Al(r)}if(d.length)for(t=0;t<d.length&&!(p=yl(d[t],"params.context."+t,c,p),500<=p);t++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);t={message:e,name:f,lineNumber:n,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(t.lineNumber=
t.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=ul();c=v(a.Ua);for(d=c.next();!d.done;d=c.next())if(d=d.value,t.message&&t.message.match(d.Vf)){a=d.weight;break a}a=v(a.Ra);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(t)){a=c.weight;break a}a=1}t.sampleWeight=a;a=v(pl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.lc[t.name])for(e=v(c.lc[t.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=t.message.match(f.regexp)){t.params["params.error.original"]=d[0];e=f.groups;f={};
for(n=0;n<e.length;n++)f[e[n]]=d[n+1],t.params["params.error."+e[n]]=d[n+1];t.message=c.Lc(f);break}t.params||(t.params={});a=ul();t.params["params.errorServiceSignature"]="msg="+a.Ua.length+"&cb="+a.Ra.length;t.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(t.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));xb("sample").constructor!==vb&&(t.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(t);
if(0!==t.sampleWeight&&!xr.has(t.message)){if(g&&S("web_enable_error_204"))Gr(void 0===b?"ERROR":b,t);else{b=void 0===b?"ERROR":b;"ERROR"===b?(vl.cb("handleError",t),S("record_app_crashed_web")&&0===Ar&&1===t.sampleWeight&&(Ar++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},S("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:t.message}}}}),pm("appCrashed",g)),zr++):"WARNING"===b&&vl.cb("handleWarning",t);if(S("kevlar_gel_error_routing")){g=b;h=void 0===
h?{}:h;b:{a=v(Cr);for(c=a.next();!c.done;c=a.next())if(wm(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:t.stack};t.fileName&&(c.filename=t.fileName);a=t.lineNumber&&t.lineNumber.split?t.lineNumber.split(":"):[];0!==a.length&&(1!==a.length||isNaN(Number(a[0]))?2!==a.length||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:t.message,errorClassName:t.name,sampleWeight:t.sampleWeight};
"ERROR"===g?a.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];R("FEXP_EXPERIMENTS")&&(h.experimentIds=R("FEXP_EXPERIMENTS"));e=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Ck("web_disable_gel_stp_ecatcher_killswitch")&&e)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=d.value,h.kvPairs.push({key:d,value:String(e[d])});if(e=t.params)for(f=v(Object.keys(e)),d=f.next();!d.done;d=f.next())d=
d.value,h.kvPairs.push({key:"client."+d,value:String(e[d])});d=R("SERVER_NAME");e=R("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(pm("clientError",h),("ERROR"===g||S("errors_flush_gel_always_killswitch"))&&jr(void 0,void 0,!1))}S("suppress_error_204_logging")||Gr(b,t)}try{xr.add(t.message)}catch(z){}yr++}}}
function Gr(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:R("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=v(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=v(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=R("SERVER_NAME");b=R("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}gl(R("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function Hr(){this.register=new Map}
function Ir(a){a=v(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Xf("ABORTED")}
Hr.prototype.clear=function(){Ir(this);this.register.clear()};
var Jr=new Hr;var Kr=Date.now().toString();
function Lr(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Kr)for(a=1,b=0;b<Kr.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Kr.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Mr,Nr=C.ytLoggingDocDocumentNonce_;Nr||(Nr=Lr(),D("ytLoggingDocDocumentNonce_",Nr));Mr=Nr;function Or(a){this.h=a}
m=Or.prototype;m.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
m.getAsJspb=function(){var a=new nk;if(void 0!==this.h.trackingParams){var b=this.h.trackingParams;if(null!=b)if("string"===typeof b)b=b?new Xe(b,Ue):Ve||(Ve=new Xe(null,Ue));else if(b.constructor!==Xe)if(Te(b))b instanceof Uint8Array||Array.isArray(b),b=b.length?new Xe(new Uint8Array(b),Ue):Ve||(Ve=new Xe(null,Ue));else throw Error();J(a,1,b)}else void 0!==this.h.veType&&J(a,2,tf(this.h.veType)),void 0!==this.h.veCounter&&J(a,6,tf(this.h.veCounter)),void 0!==this.h.elementIndex&&J(a,3,tf(this.h.elementIndex)),
this.h.isCounterfactual&&J(a,5,sf(!0));void 0!==this.h.dataElement&&(b=this.h.dataElement.getAsJspb(),Tf(a,nk,7,b));void 0!==this.h.youtubeData&&Tf(a,gk,8,this.h.jspbYoutubeData);return a};
m.toString=function(){return JSON.stringify(this.getAsJson())};
m.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
m.getLoggingDirectives=function(){return this.h.loggingDirectives};function Pr(a){return R("client-screen-nonce-store",{})[void 0===a?0:a]}
function Qr(a,b){b=void 0===b?0:b;var c=R("client-screen-nonce-store");c||(c={},Bk("client-screen-nonce-store",c));c[b]=a}
function Rr(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Sr(a){return R(Rr(void 0===a?0:a))}
D("yt_logging_screen.getRootVeType",Sr);function Tr(){var a=R("csn-to-ctt-auth-info");a||(a={},Bk("csn-to-ctt-auth-info",a));return a}
function Ur(){return Object.values(R("client-screen-nonce-store",{})).filter(function(a){return void 0!==a})}
function Vr(a){a=Pr(void 0===a?0:a);if(!a&&!R("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",Vr);function Wr(a,b,c){var d=Tr();(c=Vr(c))&&delete d[c];b&&(d[a]=b)}
function Xr(a){return Tr()[a]}
D("yt_logging_screen.getCttAuthInfo",Xr);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=void 0===c?0:c;if(a!==Pr(c)||b!==R(Rr(c)))if(Wr(a,d,c),Qr(a,c),Bk(Rr(c),b),b=function(){setTimeout(function(){a&&pm("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Mr,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});var Yr=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",Yr);function Zr(a){wk(Yr,arguments)}
;function $r(){var a=pb(as),b;return(new Vd(function(c,d){a.onSuccess=function(e){Zk(e)?c(new bs(e)):d(new cs("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new cs("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new cs("Request timed out","net.timeout",e))};
b=gl("//googleads.g.doubleclick.net/pagead/id",a)})).sc(function(c){c instanceof fe&&b.abort();
return ae(c)})}
function cs(a,b,c){Xa.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
w(cs,Xa);function bs(a){this.xhr=a}
;function ds(){this.h=0;this.value_=null}
ds.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.value_))&&"function"===typeof a.then?a:es(a):2===this.h&&b?(a=b.call(c,this.value_))&&"function"===typeof a.then?a:gs(a):this};
ds.prototype.getValue=function(){return this.value_};
ds.prototype.isRejected=function(){return 2==this.h};
ds.prototype.$goog_Thenable=!0;function gs(a){var b=new ds;a=void 0===a?null:a;b.h=2;b.value_=void 0===a?null:a;return b}
function es(a){var b=new ds;a=void 0===a?null:a;b.h=1;b.value_=void 0===a?null:a;return b}
;function hs(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:Rk(a)?"same-origin":"cors",credentials:Rk(a)?"same-origin":"include"};b={};for(var d=v(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function is(){return pg()||(Ee||Fe)&&wm("applewebkit")&&!wm("version")&&(!wm("safari")||wm("gsa/"))||Sc&&wm("version/")?!0:R("EOM_VISITOR_DATA")?!1:!0}
;function js(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in lk)if(lk[d]==c.embeddedPlayerMode){b=lk[d];break b}}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function ks(a){Xa.call(this,a.message||a.description||a.name);this.isMissing=a instanceof ls;this.isTimeout=a instanceof cs&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof fe}
w(ks,Xa);ks.prototype.name="BiscottiError";function ls(){Xa.call(this,"Biscotti ID is missing from server")}
w(ls,Xa);ls.prototype.name="BiscottiMissingError";var as={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},ms=null;function ns(){if(S("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!is())return Error("User has not consented - not fetching biscotti id.");var a=R("PLAYER_VARS",{});if("1"==nb(a))return Error("Biscotti ID is not available in private embed mode");if(js(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function uk(){var a=ns();if(void 0!==a)return ae(a);ms||(ms=$r().then(ps).sc(function(b){return qs(2,b)}));
return ms}
function ps(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new ls;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new ls;a=a.id;vk(a);ms=es(a);rs(18E5,2);return a}
function qs(a,b){b=new ks(b);vk("");ms=gs(b);0<a&&rs(12E4,a-1);throw b;}
function rs(a,b){$k(function(){$r().then(ps,function(c){return qs(b,c)}).sc(Za)},a)}
function ss(){try{var a=E("yt.ads.biscotti.getId_");return a?a():uk()}catch(b){return ae(b)}}
;function ts(a){if("1"!=nb(R("PLAYER_VARS",{}))){a&&tk();try{ss().then(function(){},function(){}),$k(ts,18E5)}catch(b){Gk(b)}}}
;function us(){var a=Ol(),b=Rl(119),c=1<window.devicePixelRatio;if(document.body&&li(document.body,"exp-invert-logo"))if(c&&!li(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!li(d,"inverted-hdpi")){var e=ji(d);ki(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&li(document.body,"inverted-hdpi")&&mi();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Sl(b)||0;d=c?d|67108864:d&-67108865;0===d?delete Ll[b]:(c=d.toString(16),Ll[b]=c.toString());
c=!0;S("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in Ll)Ll.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(Ll[f])));var f=d.join("&");Hl(b,f,63072E3,a.i,c)}}
;var vs=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function ws(){var a=void 0===a?window.location.href:a;if(S("kevlar_disable_theme_param"))return null;ec(fc(5,a));try{var b=Pk(a).theme;return vs.get(b)||null}catch(c){}return null}
;function xs(){this.h={};if(this.i=Kl()){var a=Il("CONSISTENCY");a&&ys(this,{encryptedTokenJarContents:a})}}
xs.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Ma.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=v(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];ys(this,a)}};
function ys(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Hl("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var zs=window.location.hostname.split(".").slice(-2).join(".");function As(){var a=R("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===R("INNERTUBE_CLIENT_NAME")&&(this.h=Bs(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Cs;function Ds(){Cs=E("yt.clientLocationService.instance");Cs||(Cs=new As,D("yt.clientLocationService.instance",Cs));return Cs}
m=As.prototype;m.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
m.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===R("INNERTUBE_CLIENT_NAME")?(this.h=Bs(this))&&this.h.set("yt-location-playability-token",a,15552E3):Hl("YT_CL",JSON.stringify({loctok:a}),15552E3,zs,!0))};
function Bs(a){return void 0===a.h?new gm("yt-client-location"):a.h}
m.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=Bs(this))&&this.h.remove("yt-location-playability-token"):Jl("YT_CL")};
m.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===R("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
m.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Es(a,b){if(!a)return!1;var c,d=null==(c=U(a,kk))?void 0:c.signal;if(d&&b.kb)return!!b.kb[d];var e;if((c=null==(e=U(a,hk))?void 0:e.request)&&b.yc)return!!b.yc[c];for(var f in a)if(b.xc[f])return!0;return!1}
function Fs(a,b){var c,d=null==(c=U(a,kk))?void 0:c.signal;if(d&&b.kb&&(c=b.kb[d]))return c();var e;if((c=null==(e=U(a,hk))?void 0:e.request)&&b.yc&&(e=b.yc[c]))return e();for(var f in a)if(b.xc[f]&&(a=b.xc[f]))return a()}
;function Gs(a){return function(){return new a}}
;var Hs={},Is=(Hs.WEB_UNPLUGGED="^unplugged/",Hs.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Hs.WEB_UNPLUGGED_OPS="^unplugged/",Hs.WEB_UNPLUGGED_PUBLIC="^unplugged/",Hs.WEB_CREATOR="^creator/",Hs.WEB_KIDS="^kids/",Hs.WEB_EXPERIMENTS="^experiments/",Hs.WEB_MUSIC="^music/",Hs.WEB_REMIX="^music/",Hs.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Hs.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Hs);
function Js(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Is[b];if(c){var d=new RegExp(c),e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Is).forEach(function(g){var h=v(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=v(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Ks(){}
Ks.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?El:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=R("INNERTUBE_CONTEXT");if(g){g=qb(g);S("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=R("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;Ol();var l="USER_INTERFACE_THEME_LIGHT";Rl(165)?l="USER_INTERFACE_THEME_DARK":Rl(174)?l="USER_INTERFACE_THEME_LIGHT":!S("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");k=k?l:ws()||l;h.userInterfaceTheme=k;if(!f){if(k=Wl())h.connectionType=
k;S("web_log_effective_connection_type")&&(k=Xl())&&(g.client.effectiveConnectionType=k)}var n;if(S("web_log_memory_total_kbytes")&&(null==(n=C.navigator)?0:n.deviceMemory)){var p;n=null==(p=C.navigator)?void 0:p.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}S("web_gcf_hashes_innertube")&&(k=eo())&&(p=k.coldConfigData,n=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},g.client.configInfo.coldConfigData=p,g.client.configInfo.coldHashData=n,g.client.configInfo.hotHashData=
k);p=Pk(C.location.href);!S("web_populate_internal_geo_killswitch")&&p.internalcountrycode&&(h.internalGeo=p.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:C.location.href},S("kevlar_woffle")&&Fl.h&&(p=Fl.h,h.mainAppWebInfo.pwaInstallabilityStatus=!p.h&&p.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=Gl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):
"TVHTML5"===h.clientName&&(!S("web_lr_app_quality_killswitch")&&(p=R("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:p})),p=R("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:p}));if(!S("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var t=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(V){}t=void 0}t&&(h.timeZone=t)}(t=R("EXPERIMENTS_TOKEN",""))?h.experimentsToken=
t:delete h.experimentsToken;t=Wk();xs.h||(xs.h=new xs);h=xs.h.h;p=[];n=0;for(var r in h)p[n++]=h[r];g.request=Object.assign({},g.request,{internalExperimentFlags:t,consistencyTokenJars:p});!S("web_prequest_context_killswitch")&&(r=R("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=r);t=Ol();r=Rl(58);t=t.get("gsml","");g.user=Object.assign({},g.user);r&&(g.user.enableSafetyMode=r);t&&(g.user.lockedSafetyMode=!0);S("warm_op_csn_cleanup")?e&&(f=Vr())&&(g.clientScreenNonce=f):
!f&&(f=Vr())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Ds().setLocationOnInnerTubeContext(g);try{var x=Sk(),y=x.bid;delete x.bid;g.adSignalsInfo={params:[],bid:y};var z=v(Object.entries(x));for(var H=z.next();!H.done;H=z.next()){var I=v(H.value),M=I.next().value,L=I.next().value;x=M;y=L;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:x,value:""+y})}}catch(V){Dr(V)}z=g}else Dr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),
z={};z={context:z};if(H=this.h(a)){this.i(z,H,b);var K;b="/youtubei/v1/"+Js(this.j());(H=null==(K=U(a.commandMetadata,jk))?void 0:K.apiUrl)&&(b=H);K=b;(b=R("INNERTUBE_HOST_OVERRIDE"))&&(K=String(b)+String(ic(K)));b={};b.key=R("INNERTUBE_API_KEY");S("json_condensed_response")&&(b.prettyPrint="false");K=Qk(K,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:K,ib:hs(K),Ma:z,config:a};a.config.Yb?a.config.Yb.identity=c:a.config.Yb={identity:c};return a}Dr(new Yl("Error: Failed to create Request from Command.",
a))};
da.Object.defineProperties(Ks.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Ls(){}
w(Ls,Ks);Ls.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",ib:hs("/getDatasyncIdsEndpoint","GET"),Ma:{}}};
Ls.prototype.j=function(){return[]};
Ls.prototype.h=function(){};
Ls.prototype.i=function(){};var Ms={},Ns=(Ms.GET_DATASYNC_IDS=Gs(Ls),Ms);function Os(a,b){var c=void 0===c?!0:c;var d=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=hc(window.location.href);e&&d.push(e);e=hc(a);if(0<=ab(d,e)||!e&&0==a.lastIndexOf("/",0))if(d=document.createElement("a"),Yb(d,a),a=d.href)if(a=ic(a),a=jc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Vr()},b)),f){var f=parseInt(f,10);isFinite(f)&&0<f&&Ps(a,b,f)}else Ps(a,b)}
function Ps(a,b,c){a="ST-"+cc(a).toString(36);b=b?nc(b):"";c=c||5;is()&&Hl(a,b,c)}
;function Qs(){try{return!!self.localStorage}catch(a){return!1}}
;function Rs(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Ss(a){if(Qs()){var b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Rs(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Ts(){if(!Qs())return!1;var a=$l(),b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Rs(c.value),void 0!==c&&c!==a)return!0;return!1}
;function Us(){return S("copy_login_info_to_st_cookie")&&("WEB"===R("INNERTUBE_CLIENT_NAME")||"WEB_CREATOR"===R("INNERTUBE_CLIENT_NAME"))}
function Vs(a){if(pg()&&Us()){var b=R("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=hc(window.location.href);c&&b.push(c);c=hc(a);0<=ab(b,c)||!c&&0==a.lastIndexOf("/",0)?(b=ic(a),(b=jc(b))?(b="ST-"+cc(b).toString(36),b=(b=Il(b)||null)?Ok(b):{}):b=null):b=null;null==b&&(b={});c=void 0;Us()&&(c||(c=R("LOGIN_INFO")),c&&(b.session_logininfo=c));Os(a,b)}}
;function Ws(a){var b=B.apply(1,arguments);if(!Xs(a)||b.some(function(d){return!Xs(d)}))throw Error("Only objects may be merged.");
b=v(b);for(var c=b.next();!c.done;c=b.next())Ys(a,c.value);return a}
function Ys(a,b){for(var c in b)if(Xs(b[c])){if(c in a&&!Xs(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Ys(a[c],b[c])}else if(Zs(b[c])){if(c in a&&!Zs(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);$s(a[c],b[c])}else a[c]=b[c];return a}
function $s(a,b){b=v(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Xs(c)?a.push(Ys({},c)):Zs(c)?a.push($s([],c)):a.push(c);return a}
function Xs(a){return"object"===typeof a&&!Array.isArray(a)}
function Zs(a){return"object"===typeof a&&Array.isArray(a)}
;function at(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function bt(){var a=at();a.info||(a.info={});return a.info}
function ct(a){a=at(a);a.metadata||(a.metadata={});return a.metadata}
function dt(a){a=at(a);a.tick||(a.tick={});return a.tick}
function et(a){a=at(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function ft(a){a=et(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function gt(a){var b=at(a).nonce;b||(b=Lr(),at(a).nonce=b);return b}
;function ht(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function jt(a){a=a||"";var b=E("ytcsi.reference");b||(ht(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=ht(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var W={},kt=(W.auto_search="LATENCY_ACTION_AUTO_SEARCH",W.ad_to_ad="LATENCY_ACTION_AD_TO_AD",W.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",W["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",W.app_startup="LATENCY_ACTION_APP_STARTUP",W["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",W["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",W["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",W["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
W["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",W["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",W["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",W["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",W["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",W["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",W["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",W["asset.ownership"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",W["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",W["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",W["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",W["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",W["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",W["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",W["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",
W["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",W["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",W.browse="LATENCY_ACTION_BROWSE",W.cast_splash="LATENCY_ACTION_CAST_SPLASH",W.channels="LATENCY_ACTION_CHANNELS",W.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",W["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",W["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",W["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
W["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",W["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",W["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",W["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",W["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",W["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",W["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",W["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",W["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",W["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",W.chips="LATENCY_ACTION_CHIPS",W["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",W["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",W["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",W.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",W.embed="LATENCY_ACTION_EMBED",
W.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",W.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",W.explore="LATENCY_ACTION_EXPLORE",W.home="LATENCY_ACTION_HOME",W.library="LATENCY_ACTION_LIBRARY",W.live="LATENCY_ACTION_LIVE",W.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",W.mini_app="LATENCY_ACTION_MINI_APP_PLAY",W.onboarding="LATENCY_ACTION_ONBOARDING",W.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",W["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",
W["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",W["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",W["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",W["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",W["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",W["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",W["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",W["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",W["owner.claimed_videos"]=
"LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",W["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",W["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",W["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",W["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",W["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",W["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",W["owner.policies"]=
"LATENCY_ACTION_CREATOR_CMS_POLICIES",W["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",W["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",W["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",W.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",W.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",W.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",W.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",W["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",
W["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",W["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",W.prebuffer="LATENCY_ACTION_PREBUFFER",W.prefetch="LATENCY_ACTION_PREFETCH",W.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",W.profile_switcher="LATENCY_ACTION_LOGIN",W.reel_watch="LATENCY_ACTION_REEL_WATCH",W.results="LATENCY_ACTION_RESULTS",W["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",W.search_ui="LATENCY_ACTION_SEARCH_UI",W.search_suggest="LATENCY_ACTION_SUGGEST",
W.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",W.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",W.seek="LATENCY_ACTION_PLAYER_SEEK",W.settings="LATENCY_ACTION_SETTINGS",W.store="LATENCY_ACTION_STORE",W.tenx="LATENCY_ACTION_TENX",W.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",W.watch="LATENCY_ACTION_WATCH",W.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",W["watch,watch7"]="LATENCY_ACTION_WATCH",W["watch,watch7_html5"]="LATENCY_ACTION_WATCH",W["watch,watch7ad"]="LATENCY_ACTION_WATCH",W["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",W.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",W.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",W["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",W["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",W["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",W["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",W["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",W["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",W["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",
W["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",W["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",W["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",W["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",W["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",W["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",W.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",W.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",
W.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",W.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",W.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",W),X={},lt=(X.ad_allowed="adTypesAllowed",X.yt_abt="adBreakType",X.ad_cpn="adClientPlaybackNonce",X.ad_docid="adVideoId",X.yt_ad_an="adNetworks",X.ad_at="adType",X.aida="appInstallDataAgeMs",X.browse_id="browseId",X.p="httpProtocol",X.t="transportProtocol",X.cpn="clientPlaybackNonce",X.ccs="creatorInfo.creatorCanaryState",X.ctop=
"creatorInfo.topEntityType",X.csn="clientScreenNonce",X.docid="videoId",X.GetHome_rid="requestIds",X.GetSearch_rid="requestIds",X.GetPlayer_rid="requestIds",X.GetWatchNext_rid="requestIds",X.GetBrowse_rid="requestIds",X.GetLibrary_rid="requestIds",X.is_continuation="isContinuation",X.is_nav="isNavigation",X.b_p="kabukiInfo.browseParams",X.is_prefetch="kabukiInfo.isPrefetch",X.is_secondary_nav="kabukiInfo.isSecondaryNav",X.nav_type="kabukiInfo.navigationType",X.prev_browse_id="kabukiInfo.prevBrowseId",
X.query_source="kabukiInfo.querySource",X.voz_type="kabukiInfo.vozType",X.yt_lt="loadType",X.mver="creatorInfo.measurementVersion",X.yt_ad="isMonetized",X.nr="webInfo.navigationReason",X.nrsu="navigationRequestedSameUrl",X.pnt="performanceNavigationTiming",X.prt="playbackRequiresTap",X.plt="playerInfo.playbackType",X.pis="playerInfo.playerInitializedState",X.paused="playerInfo.isPausedOnLoad",X.yt_pt="playerType",X.fmt="playerInfo.itag",X.yt_pl="watchInfo.isPlaylist",X.yt_pre="playerInfo.preloadType",
X.yt_ad_pr="prerollAllowed",X.pa="previousAction",X.yt_red="isRedSubscriber",X.rce="mwebInfo.responseContentEncoding",X.rc="resourceInfo.resourceCache",X.scrh="screenHeight",X.scrw="screenWidth",X.st="serverTimeMs",X.ssdm="shellStartupDurationMs",X.br_trs="tvInfo.bedrockTriggerState",X.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",X.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",X.label="tvInfo.label",X.is_mdx="tvInfo.isMdx",X.preloaded="tvInfo.isPreloaded",X.aac_type="tvInfo.authAccessCredentialType",
X.upg_player_vis="playerInfo.visibilityState",X.query="unpluggedInfo.query",X.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",X.yt_vst="videoStreamType",X.vph="viewportHeight",X.vpw="viewportWidth",X.yt_vis="isVisible",X.rcl="mwebInfo.responseContentLength",X.GetSettings_rid="requestIds",X.GetTrending_rid="requestIds",X.GetMusicSearchSuggestions_rid="requestIds",X.REQUEST_ID="requestIds",X),mt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
nt={},ot=(nt.ccs="CANARY_STATE_",nt.mver="MEASUREMENT_VERSION_",nt.pis="PLAYER_INITIALIZED_STATE_",nt.yt_pt="LATENCY_PLAYER_",nt.pa="LATENCY_ACTION_",nt.ctop="TOP_ENTITY_TYPE_",nt.yt_vst="VIDEO_STREAM_TYPE_",nt),pt="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function qt(a,b,c){c=et(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in lt){c=lt[a];0<=ab(mt,c)&&(b=!!b);a in ot&&"string"===typeof b&&(b=ot[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Ws({},d)}0<=ab(pt,a)||Er(new Yl("Unknown label logged with GEL CSI",a))}
;function rt(a,b){jo.call(this,1,arguments);this.timer=b}
w(rt,jo);var st=new ko("aft-recorded",rt);var tt=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",tt);function ut(){this.h=0}
function vt(){ut.h||(ut.h=new ut);return ut.h}
ut.prototype.tick=function(a,b,c,d){wt(this,"tick_"+a+"_"+b)||pm("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
ut.prototype.info=function(a,b,c){var d=Object.keys(a).join("");wt(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,pm("latencyActionInfo",a,{cttAuthInfo:c}))};
ut.prototype.jspbInfo=function(){};
ut.prototype.span=function(a,b,c){var d=Object.keys(a).join("");wt(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,pm("latencyActionSpan",a,{cttAuthInfo:c}))};
function wt(a,b){tt[b]=tt[b]||{count:0};var c=tt[b];c.count++;c.time=T();a.h||(a.h=bm(function(){var d=T(),e;for(e in tt)tt[e]&&6E4<d-tt[e].time&&delete tt[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Yl("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Er(c)),!0):!1}
;var xt=window;function zt(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function At(){var a;if(S("csi_use_performance_navigation_timing")||S("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==Y?void 0:null==(a=Y.getEntriesByType)?void 0:null==(b=a.call(Y,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=Bt(e.requestStart),e.responseEnd=Bt(e.responseEnd),e.redirectStart=Bt(e.redirectStart),e.redirectEnd=Bt(e.redirectEnd),e.domainLookupEnd=Bt(e.domainLookupEnd),e.connectStart=Bt(e.connectStart),e.connectEnd=
Bt(e.connectEnd),e.responseStart=Bt(e.responseStart),e.secureConnectionStart=Bt(e.secureConnectionStart),e.domainLookupStart=Bt(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=Y.timing;return a}
function Bt(a){return Math.round(Ct()+a)}
function Ct(){return(S("csi_use_time_origin")||S("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=xt.performance||xt.mozPerformance||xt.msPerformance||xt.webkitPerformance||new zt;var Dt=!1,Et={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Ta(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||Za,Y);function Ft(a,b,c){if(null!==b){if("yt_lt"===a){var d="string"===typeof b?b:""+b;ct(c).loadType=d}(a=qt(a,b,c))&&Gt(a,c)}}
function Gt(a,b){var c=jt(b||"");Ws(c.info,a);a.loadType&&(c=a.loadType,ct(b).loadType=c);Ws(ft(b),a);c=gt(b);b=at(b).cttAuthInfo;vt().info(a,c,b)}
function Ht(a){var b,c,d,e,f=(null!=(e=null==wq().resolve(new rq($n))?void 0:null==(b=ao())?void 0:null==(c=b.loggingHotConfig)?void 0:null==(d=c.csiConfig)?void 0:d.debugTicks)?e:[]).map(function(g){return Object.values(g)[0]});
if(0<f.length)for(b=0;b<f.length;b++)if(a===f[b])return!0;return!1}
function It(a,b,c){var d=gt(c),e;if(e=S("web_csi_debug_sample_enabled")&&d){var f,g,h;e=(null==wq().resolve(new rq($n))?void 0:null==(f=ao())?void 0:null==(g=f.loggingHotConfig)?void 0:null==(h=g.csiConfig)?void 0:h.debugSampleWeight)||0;if(0!==e&&Ht(a)){for(g=f=0;g<d.length;g++)f=(31*f+d.charCodeAt(g))%Number.MAX_SAFE_INTEGER;e=0!==f%1E5%e;at(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Gt(f,c));at(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){b||"_"===a[0]||(e=a,Y.mark&&(0==e.lastIndexOf("mark_",
0)||(e="mark_"+e),c&&(e+=" ("+c+")"),Y.mark(e)));e=jt(c||"");e.tick[a]=b||T();if(e.callback&&e.callback[a])for(e=v(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=et(c);e.gelTicks&&(e.gelTicks[a]=!0);f=dt(c);e=b||T();S("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=at(c).cttAuthInfo;"_start"===a?(a=vt(),wt(a,"baseline_"+d)||pm("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):vt().tick(a,d,b,f);Jt(c);return e}}
function Kt(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Np+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Lt(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);ac()&&a.setAttribute("nonce",ac());return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Ct(),It("rsf_"+b,c+Math.round(a.fetchStart)),It("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Mt(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=cb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=eb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(It("wffs",Bt(b.startTime)),It("wffe",Bt(b.responseEnd)))}
function Nt(a){var b=Ot("aft",a);if(b)return b;b=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Ot(b[d],a);if(e)return e}return NaN}
function Ot(a,b){if(a=dt(b)[a])return"number"===typeof a?a:a[a.length-1]}
function Jt(a){var b=Ot("_start",a),c=Nt(a);b&&c&&!Dt&&(po(st,new rt(Math.round(c-b),a)),Dt=!0)}
function Pt(a,b){for(var c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Pt(a[d],b[d]))return!1;return!0}
function Qt(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=fb(a,function(b){return"first-paint"===b.name}))return Bt(a.startTime)}a=Y.timing;
return a.Be?Math.max(0,a.Be):0}
;function Rt(a,b){Fk(function(){jt("").info.actionType=a;b&&Bk("TIMING_AFT_KEYS",b);Bk("TIMING_ACTION",a);var c=R("TIMING_INFO",{}),d;for(d in c)c.hasOwnProperty(d)&&Ft(d,c[d]);c={isNavigation:!0,actionType:kt[R("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};if(d=R("PREVIOUS_ACTION"))c.previousAction=kt[d]||"LATENCY_ACTION_UNKNOWN";if(d=R("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=R("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=Vr())&&"UNDEFINED_CSN"!==d&&(c.clientScreenNonce=d);d=Kt();if(1===d||-1===d)c.isVisible=
!0;ct();bt();c.loadType="cold";d=bt();var e=At(),f=Ct(),g=R("CSI_START_TIMESTAMP_MILLIS",0);0<g&&!S("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(It("srt",e.responseStart),1!==d.prerender&&It("_start",f,void 0));d=Qt();0<d&&It("fpt",d);d=At();d.isPerformanceNavigationTiming&&Gt({performanceNavigationTiming:!0});It("nreqs",d.requestStart,void 0);It("nress",d.responseStart,void 0);It("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(It("nrs",d.redirectStart,void 0),It("nre",
d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(It("ndnss",d.domainLookupStart,void 0),It("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(It("ntcps",d.connectStart,void 0),It("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Ct()&&0<d.connectEnd-d.secureConnectionStart&&(It("nstcps",d.secureConnectionStart,void 0),It("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Mt();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Et)Et.hasOwnProperty(h)&&
(e=Et[h],Lt(h,e)&&d.push(e));if(0<d.length)for(c.resourceInfo=[],h=v(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Gt(c);c=bt();h=ft();if("cold"===ct().loadType&&("cold"===c.yt_lt||"cold"===h.loadType)){d=dt();e=et();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if("number"===typeof d[k])It(k,Ot(k));else if(S("log_repeated_ytcsi_ticks"))for(f=v(d[k]),g=f.next();!g.done;g=f.next())g=g.value,It(k.slice(1),g);k={};d=!1;e=v(Object.keys(c));for(f=e.next();!f.done;f=
e.next())f=f.value,(f=qt(f,c[f]))&&!Pt(ft(),f)&&(Ws(h,f),Ws(k,f),d=!0);d&&Gt(k)}D("ytglobal.timingready_",!0);k=R("TIMING_ACTION");E("ytglobal.timingready_")&&k&&St()&&Nt()&&Jt()})()}
function Tt(a,b,c,d){Fk(Ft)(a,b,c,d)}
function Ut(a,b,c){return Fk(It)(a,b,c)}
function St(){return Fk(function(){return"_start"in dt()})()}
function Vt(){Fk(function(){var a=gt();requestAnimationFrame(function(){setTimeout(function(){a===gt()&&Ut("ol",void 0,void 0)},0)})})()}
var Wt=window;Wt.ytcsi&&(Wt.ytcsi.info=Tt,Wt.ytcsi.tick=Ut);var Xt="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),Yt=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Zt(a,b,c,d){this.j=a;this.X=b;this.m=c;this.l=d;this.i=void 0;this.h=new Map;a.kb||(a.kb={});a.kb=Object.assign({},Ns,a.kb)}
function $t(a,b,c,d){if(void 0!==Zt.h){if(d=Zt.h,a=[a!==d.j,b!==d.X,c!==d.m,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new Yl("InnerTubeTransportService is already initialized",a);
}else Zt.h=new Zt(a,b,c,d)}
function au(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?El:c;var d=Fs(b,a.j);if(!d)return ae(new Yl("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?(Vs(e.input),new Vd(function(f){var g,h,k;return A(function(l){if(1==l.h){h="cors"===(null==(g=e.ib)?void 0:g.mode)?"cors":void 0;if(a.m.Ye){var n=e.config,p;n=null==n?void 0:null==(p=n.Yb)?void 0:p.sessionIndex;p=Dl(0,{sessionIndex:n});k=Object.assign({},bu(h),p);return l.A(2)}return l.yield(cu(e.config,
h),3)}2!=l.h&&(k=l.i);f(du(a,e,k));l.h=0})})):ae(new Yl("Error: Failed to build request for command.",b))}
function eu(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Zf)?0:d.eg)&&a.l){d=v(Xt);for(var e=d.next();!e.done;e=d.next())e=e.value,a.l[e]&&a.l[e].handleResponse(b,c)}}
function du(a,b,c){var d,e,f,g,h,k,l,n,p,t,r,x,y,z,H,I,M,L,K,V,Z,ea,ra,oa,Ha,zg,lq,mq,nq;return A(function(ka){switch(ka.h){case 1:ka.A(2);break;case 3:if((d=ka.i)&&!d.isExpired())return ka.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Ma)?0:f.context)){ka.A(4);break}g=b.Ma.context;ka.A(5);break;case 5:h=v([]),k=h.next();case 7:if(k.done){ka.A(4);break}l=k.value;return ka.yield(l.Wf(g),8);case 8:k=h.next();ka.A(7);break;case 4:if(null==(n=a.i)||!n.ag(b.input,b.Ma)){ka.A(11);
break}return ka.yield(a.i.Tf(b.input,b.Ma),12);case 12:return p=ka.i,S("kevlar_process_local_innertube_responses_killswitch")||eu(a,p,b),ka.return(p);case 11:return(x=null==(r=b.config)?void 0:r.Oa)&&a.h.has(x)&&S("web_memoize_inflight_requests")?t=a.h.get(x):(y=JSON.stringify(b.Ma),I=null!=(H=null==(z=b.ib)?void 0:z.headers)?H:{},b.ib=Object.assign({},b.ib,{headers:Object.assign({},I,c)}),M=Object.assign({},b.ib),"POST"===b.ib.method&&(M=Object.assign({},M,{body:y})),(null==(L=b.config)?0:L.Ie)&&
Ut(b.config.Ie),K=function(){return a.X.fetch(b.input,M,b.config)},t=K(),x&&a.h.set(x,t)),ka.yield(t,13);
case 13:if((V=ka.i)&&"error"in V&&(null==(Z=V)?0:null==(ea=Z.error)?0:ea.details))for(ra=V.error.details,oa=v(ra),Ha=oa.next();!Ha.done;Ha=oa.next())zg=Ha.value,(lq=zg["@type"])&&-1<Yt.indexOf(lq)&&(delete zg["@type"],V=zg);x&&a.h.has(x)&&a.h.delete(x);(null==(mq=b.config)?0:mq.Je)&&Ut(b.config.Je);if(V||null==(nq=a.i)||!nq.Lf(b.input,b.Ma)){ka.A(14);break}return ka.yield(a.i.Sf(b.input,b.Ma),15);case 15:V=ka.i;case 14:return eu(a,V,b),ka.return(V||void 0)}})}
function cu(a,b){var c,d,e,f;return A(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Yb)?void 0:d.sessionIndex;var h=g.yield;var k=$d(Dl(0,{sessionIndex:e}));return h.call(g,k,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},bu(b),f)))})}
function bu(a){var b={"Content-Type":"application/json"};R("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=R("EOM_VISITOR_DATA"):R("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=R("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=R("LOGGED_IN",!1);"cors"!==a&&((a=R("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=R("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=R("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=R("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var fu=new qq("INNERTUBE_TRANSPORT_TOKEN");var gu=["share/get_web_player_share_panel"],hu=["feedback"],iu=["notification/modify_channel_preference"],ju=["browse/edit_playlist"],ku=["subscription/subscribe"],lu=["subscription/unsubscribe"];function mu(){}
w(mu,Ks);mu.prototype.j=function(){return ku};
mu.prototype.h=function(a){return U(a,sk)||void 0};
mu.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(mu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function nu(){}
w(nu,Ks);nu.prototype.j=function(){return lu};
nu.prototype.h=function(a){return U(a,rk)||void 0};
nu.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(nu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function ou(){}
w(ou,Ks);ou.prototype.j=function(){return hu};
ou.prototype.h=function(a){return U(a,mk)||void 0};
ou.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(ou.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function pu(){}
w(pu,Ks);pu.prototype.j=function(){return iu};
pu.prototype.h=function(a){return U(a,qk)||void 0};
pu.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function qu(){}
w(qu,Ks);qu.prototype.j=function(){return ju};
qu.prototype.h=function(a){return U(a,pk)||void 0};
qu.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function ru(){}
w(ru,Ks);ru.prototype.j=function(){return gu};
ru.prototype.h=function(a){return U(a,ok)};
ru.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var su=new qq("NETWORK_SLI_TOKEN");function tu(a){this.h=a}
tu.prototype.fetch=function(a,b){var c=this,d,e,f;return A(function(g){c.h&&(d=ec(fc(5,uc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;S("wug_networking_gzip_request")&&(e=Ho(b));f=new window.Request(a,e);return S("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){Er(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){Er(h)}))})};
tu.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Of(),b=b.then(function(c){Er(new Yl("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
tu[pq]=[new rq(su)];var uu=new qq("NETWORK_MANAGER_TOKEN");var vu;function wu(){var a=xu,b=yu,c=zu;this.l=Au;this.navigate=a;this.i=b;this.j=c;this.h=new Set}
function Bu(a,b,c){if(Cu(b))Du(a,b,c);else{var d=a.l(b,c);if(null==c?0:c.wc)d.wc=c.wc;0===d.type?a.navigate?Eu(d.command)?Fu(a,d.command)||(S("logging_avoid_blocking_during_navigation")&&Mq().transition("application_navigating"),b=a.navigate(d)||[],de(b).then(function(){a.h.delete(d.command)})):Dr(Error("Error: Command handler page requests need to specify a url.")):Dr(Error("Error: Command handler navigate function was called but not set.")):1===d.type?a.i?Fu(a,d.command)||(b=a.i(d),de(b).then(function(){a.h.delete(d.command)})):
Dr(Error("Error: Command handler handle service request function was called but not set.")):2===d.type&&(a.j?a.j(d):Dr(Error("Error: Command handler send action was called but not set.")))}}
function Fu(a,b){if(a.h.has(b))return!0;a.h.add(b);return!1}
function Cu(a){var b=!!U(a,fk),c;a="CLIENT_SIGNAL"===(null==(c=U(a,kk))?void 0:c.signal);return b||a}
function Du(a,b,c){var d=U(b,fk);if(d)var e=(null==d?void 0:d.commands)||[];else{var f;if("CLIENT_SIGNAL"===(null==(f=U(b,kk))?void 0:f.signal)){var g;e=(null==(g=U(b,kk))?void 0:g.actions)||[]}}if(e)for(b=v(e),e=b.next();!e.done;e=b.next()){e=e.value;try{Bu(a,e,c)}catch(h){h instanceof Error&&Dr(h)}}else Dr(Error("Could not handle the meta command."))}
function Eu(a){var b;return!(null==(b=U(null==a?void 0:a.commandMetadata,jk))||!b.url)}
;function Gu(){var a,b,c;return A(function(d){if(1==d.h)return a=wq().resolve(fu),a?d.yield(au(a),2):(Er(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return Er(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Mf;return d.return(c)}Er(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var Hu=C.caches,Iu;function Ju(a){var b=a.indexOf(":");return-1===b?{wd:a}:{wd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Ku(){return A(function(a){if(void 0!==Iu)return a.return(Iu);Iu=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return ya(d,2),d.yield(Hu.open("test-only"),4);case 4:return d.yield(Hu.delete("test-only"),5);case 5:d.h=3;d.l=0;break;case 2:if(c=za(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Iu)})}
function Lu(a){var b,c,d,e,f,g,h;A(function(k){if(1==k.h)return k.yield(Ku(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return k.yield(Hu.keys(),3)}c=k.i;d=v(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Ju(f),h=g.datasyncId,!h||a.includes(h)||b.push(Hu.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(n){return n})}))})}
function Mu(){var a,b,c,d,e,f,g;return A(function(h){if(1==h.h)return h.yield(Ku(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=$l("cache contains other");return h.yield(Hu.keys(),3)}b=h.i;c=v(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Ju(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Nu(){Gu().then(function(a){a&&(Fn(a),Lu(a),Ss(a))})}
function Ou(){var a=new zp;bi.ka(function(){var b,c,d,e;return A(function(f){switch(f.h){case 1:if(S("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=$l("clear");if(b.startsWith("V")&&b.endsWith("||")){var g=[b];Fn(g);Lu(g);Ss(g);return f.return()}c=Ts();return f.yield(Mu(),3);case 3:return d=f.i,f.yield(Gn(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.qa()?Nu():a.l.add("publicytnetworkstatus-online",Nu,!0,void 0,void 0),f.h=0}})})}
;var Hh=ha(["data-"]);function Pu(a){a&&(a.dataset?a.dataset[Qu("loaded")]="true":Gh(a))}
function Ru(a,b){return a?a.dataset?a.dataset[Qu(b)]:a.getAttribute("data-"+b):null}
var Su={};function Qu(a){return Su[a]||(Su[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Tu=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Uu=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Vu(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Tu,""),c=c.replace(Uu,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Wu(a,b,c)}
function Wu(a,b,c){c=void 0===c?null:c;var d=Xu(a),e=document.getElementById(d),f=e&&Ru(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=gq(d,b),b=""+Oa(b),Yu[b]=f),g||(e=Zu(a,d,function(){if(!Ru(e,"loaded")){Pu(e);jq(d);var h=Ua(kq,d);$k(h,0)}},c)))}
function Zu(a,b,c,d){d=void 0===d?null:d;var e=Hd("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Kh(e,bk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function $u(a){a=Xu(a);var b=document.getElementById(a);b&&(kq(a),b.parentNode.removeChild(b))}
function av(a,b){a&&b&&(a=""+Oa(b),(a=Yu[a])&&iq(a))}
function Xu(a){var b=document.createElement("a");Yb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+cc(a)}
var Yu={};var bv=[],cv=!1;function dv(){if(!S("disable_biscotti_fetch_for_ad_blocker_detection")&&!S("disable_biscotti_fetch_entirely_for_all_web_clients")&&is()){var a=R("PLAYER_VARS",{});if("1"!=nb(a)&&!js(a)){var b=function(){cv=!0;"google_ad_status"in window?Bk("DCLKSTAT",1):Bk("DCLKSTAT",2)};
try{Vu("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}bv.push(bi.ka(function(){if(!(cv||"google_ad_status"in window)){try{av("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}cv=!0;Bk("DCLKSTAT",3)}},5E3))}}}
function ev(){var a=Number(R("DCLKSTAT",0));return isNaN(a)?0:a}
;function fv(a){Eq.call(this,void 0===a?"document_active":a);var b=this;this.l=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.fa},{from:"document_active",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"document_disposed",action:this.m},{from:"document_disposed_preventable",to:"flush_logs",action:this.s},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.s},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
w(fv,Eq);fv.prototype.fa=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
fv.prototype.m=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
fv.prototype.s=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
fv.prototype.i=function(){this.h=new Map};function gv(a){Eq.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.s},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.m},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.s},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.s},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.m},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.m},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
S("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
w(gv,Eq);gv.prototype.i=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
gv.prototype.h=function(a,b){a(null==b?void 0:b.event);S("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
gv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
gv.prototype.s=function(a,b){a(null==b?void 0:b.event)};function hv(){this.l=new fv;this.m=new gv}
hv.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.l.install(c)});
a.forEach(function(c){b.m.install(c)})};function iv(a){jo.call(this,1,arguments);this.csn=a}
w(iv,jo);var so=new ko("screen-created",iv),jv=[],kv=0,lv=new Map,mv=new Map,nv=new Map;
function ov(a,b,c,d,e){e=void 0===e?!1:e;for(var f=pv({cttAuthInfo:Xr(b)||void 0},b),g=v(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(lb(k)||!k.trackingParams&&!k.veType)&&Er(Error("Child VE logged with no data"));if(S("no_client_ve_attach_unless_shown")){var l=qv(h,b);if(k.veType&&!mv.has(l)&&!nv.has(l)&&!e){lv.set(l,[a,b,c,h]);return}h=qv(c,b);lv.has(h)?rv(c,b):nv.set(h,!0)}}d=d.filter(function(n){n.csn!==b?(n.csn=b,n=!0):n=!1;return n});
c={csn:b,parentVe:c.getAsJson(),childVes:db(d,function(n){return n.getAsJson()})};
"UNDEFINED_CSN"===b?sv("visualElementAttached",f,c):a?wr("visualElementAttached",c,a,f):pm("visualElementAttached",c,f)}
function sv(a,b,c){jv.push({payloadName:a,payload:c,Rf:void 0,options:b});kv||(kv=to())}
function uo(a){if(jv){for(var b=v(jv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,pm(c.payloadName,c.payload,c.options));jv.length=0}kv=0}
function qv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function rv(a,b){a=qv(a,b);lv.has(a)&&(b=lv.get(a)||[],ov(b[0],b[1],b[2],[b[3]],!0),lv.delete(a))}
function pv(a,b){S("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function tv(){this.l=[];this.i=new Map;this.h=new Map;this.j=new Set}
tv.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Vr(void 0===c?0:c)){a=this.client;d=new Or({trackingParams:d});var e=void 0;if(S("no_client_ve_attach_unless_shown")){var f=qv(d,c);mv.set(f,!0);rv(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=pv({cttAuthInfo:Xr(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);"UNDEFINED_CSN"===c?sv("visualElementGestured",f,d):a?wr("visualElementGestured",d,a,f):pm("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
tv.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;if(0===c&&this.j.has(c))this.l.push([a,b]);else{var d=c;d=void 0===d?0:d;c=Vr(d);a||(a=(a=Sr(void 0===d?0:d))?new Or({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=pv({cttAuthInfo:Xr(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},"UNDEFINED_CSN"===c?sv("visualElementStateChanged",d,b):a?wr("visualElementStateChanged",b,a,d):pm("visualElementStateChanged",b,d))}};
function uv(a,b){if(void 0===b)for(var c=Ur(),d=0;d<c.length;d++)void 0!==c[d]&&uv(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&ov(a.client,b,f,e)}),a.i.clear(),a.h.clear(),a.m=void 0}
;function vv(){hv.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));S("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a))}
w(vv,hv);vv.prototype.j=function(){pm("finalPayload",{csn:Vr()})};
vv.prototype.h=function(){Ir(Jr)};
vv.prototype.i=function(){var a=uv;tv.h||(tv.h=new tv);a(tv.h)};function wv(){}
function xv(){var a=E("ytglobal.storage_");a||(a=new wv,D("ytglobal.storage_",a));return a}
wv.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(yv()):d.return()})};
function yv(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",wv);function nm(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=Vk("ytidb_transaction_ended_event_rate_limit_session",.2)}
nm.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":S("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":S("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":zv(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=Vk("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function zv(a,b){xv().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Av(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Av(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Av(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Bv(a){this.args=void 0===a?null:a;this.returnValue=[]}
;var Cv=new Map;function Dv(a,b){if(!a)return null;a=Object.keys(a);a=v(a);for(var c=a.next();!c.done;c=a.next()){c=c.value;var d=c.toLowerCase();if(-1<d.indexOf(b,d.length-b.length))return c}return null}
;function Ev(a,b,c){var d;d||(d={bubbles:!0,cancelable:!1,composed:!0});null!==c&&void 0!==c&&(d.detail=c);b=new CustomEvent(b,d);a.dispatchEvent(b)}
;function Fv(a,b){b=new Bv(b);Ev(a,"yt-action",b);return b.returnValue}
function Gv(a,b,c,d){b&&b.length&&b.forEach(function(e){var f=Dv(e,"action")||Dv(e,"command")||Dv(e,"endpoint");if(f){var g="yt"+f;var h=Cv.get(g);h?g=h:(f="yt-"+f.replace(/([A-Z])/g,"-$1").toLowerCase(),Cv.set(g,f),g=f);U(e,ik)&&(g+="-"+U(e,ik).signal.toLowerCase().replace(/_/g,"-"))}else g=null;g&&(S("handle_service_request_actions")&&e.commandMetadata&&e.commandMetadata.webCommandMetadata&&e.commandMetadata.webCommandMetadata.sendPost?Hv(c?c:a,[e]):Fv(a,[e,c,d]))})}
function Hv(a,b){var c=[a];b&&c.push.apply(c,b);b=Fv(a,c);return 0<b.length&&(b=b[0],Ev(a,"yt-service-request-sent",b),b&&b.ajaxPromise)?(b.ajaxPromise.then(function(d){Ev(a,"yt-service-request-completed",d)},function(d){Ev(a,"yt-service-request-error",{error:d,
params:c})},a),b.ajaxPromise):$d()}
;function Au(a,b,c){b=void 0===b?{}:b;var d,e=null==(d=U(a.commandMetadata,jk))?void 0:d.url;d=b.form||{};!c||d.element||d.skipDefaultElement||(b.form=b.form||{},b.form.element=c);if(e&&"/service_ajax"!==e)return{type:0,command:a,form:b.form};if(S("kevlar_service_command_check")){if(c=wq().resolve(fu),Es(a,c.j))return Object.assign({},{type:1,command:a},b)}else{var f;if(null==(f=U(a.commandMetadata,jk))?0:f.apiUrl)return Object.assign({},{type:1,command:a},b)}return{type:2,command:a,form:b.form}}
function yu(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);if(b)return[Hv(b,[a.command,c,a.wc])]}return[]}
function zu(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);b&&Gv(b,[a.command],b,c)}}
;function Iv(a,b,c){G.call(this);var d=this;c=c||R("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.targetOrigin="*";this.l=c;this.sessionId=null;this.channel="widget";this.P=!!a;this.v=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.P&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.targetOrigin=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.s||0<=ab(d.s,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.s=this.i=this.m=null;window.addEventListener("message",this.v)}
w(Iv,G);Iv.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Hk(d)}}};
Iv.prototype.M=function(){window.removeEventListener("message",this.v);G.prototype.M.call(this)};function Jv(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Iv(!!R("WIDGET_ID_ENFORCE")),b=this.Fe.bind(this);a.m=b;a.s=null;this.h.channel="widget";if(a=R("WIDGET_ID"))this.h.sessionId=a}
m=Jv.prototype;m.Fe=function(a,b,c){"addEventListener"===a&&b?this.Hc(b[0],c):this.Xc(a,b,c)};
m.Xc=function(){};
m.Bc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
m.Hc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.Bc(a,b)),this.j[a]=!0)};
m.addEventListener=function(){};
m.je=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Ec());this.sendMessage("onReady");bb(this.i,this.Dd,this);this.i=[]};
m.Ec=function(){return null};
function Kv(a,b){a.sendMessage("infoDelivery",b)}
m.Dd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.Dd({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};var Lv={},Mv=(Lv["api.invalidparam"]=2,Lv.auth=150,Lv["drm.auth"]=150,Lv["heartbeat.net"]=150,Lv["heartbeat.servererror"]=150,Lv["heartbeat.stop"]=150,Lv["html5.unsupportedads"]=5,Lv["fmt.noneavailable"]=5,Lv["fmt.decode"]=5,Lv["fmt.unplayable"]=5,Lv["html5.missingapi"]=5,Lv["html5.unsupportedlive"]=5,Lv["drm.unavailable"]=5,Lv["mrm.blocked"]=151,Lv);var Nv=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Ov(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Pv(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=v(Nv);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Qv(a,b,c,d){if(Na(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Rv(a){Jv.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Re.bind(this));this.addEventListener("onVolumeChange",this.Se.bind(this));this.addEventListener("onApiChange",this.Me.bind(this));this.addEventListener("onPlaybackQualityChange",this.Oe.bind(this));this.addEventListener("onPlaybackRateChange",this.Pe.bind(this));this.addEventListener("onStateChange",this.Qe.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Te.bind(this))}
w(Rv,Jv);m=Rv.prototype;
m.Xc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Ov(a)){var d=b;if(Na(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Pv(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Pv(e);break;case "loadPlaylist":case "cuePlaylist":e=Qv(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Ov(a)&&Kv(this,this.Ec())}};
m.Hc=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);Jv.prototype.Hc.call(this,a,b)};
m.Bc=function(a,b){var c=this,d=Jv.prototype.Bc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
m.onReady=function(){var a=this.je.bind(this);this.h.i=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?Mv[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Ec=function(){if(!this.api)return null;var a=this.api.getApiInterface();gb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Qe=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Kv(this,a)};
m.Oe=function(a){Kv(this,{playbackQuality:a})};
m.Pe=function(a){Kv(this,{playbackRate:a})};
m.Me=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Se=function(){Kv(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Re=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Kv(this,a)};
m.Te=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Kv(this,a)};
m.dispose=function(){Jv.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Sv(a){G.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.zd,this)}
w(Sv,G);m=Sv.prototype;m.start=function(){this.started||this.h()||(this.started=!0,this.connection.jb("RECEIVING"))};
m.jb=function(a,b){this.started&&!this.h()&&this.connection.jb(a,b)};
m.zd=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Tv(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Uv(a,c))&&this.jb(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Ne.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Ne=function(a,b){this.started&&!this.h()&&this.connection.jb(a,this.Dc(a,b))};
m.Dc=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.M=function(){var a=this.connection;a.h()||yi(a.i,"command",this.zd,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);G.prototype.M.call(this)};function Vv(a,b){Sv.call(this,b);this.api=a;this.start()}
w(Vv,Sv);Vv.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Vv.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Tv(a,b){switch(a){case "loadVideoById":return a=Pv(b),[a];case "cueVideoById":return a=Pv(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Qv(b),[a];case "cuePlaylist":return a=Qv(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Uv(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Vv.prototype.Dc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Sv.prototype.Dc.call(this,a,b)};
Vv.prototype.M=function(){Sv.prototype.M.call(this);delete this.api};function Wv(a){a=void 0===a?!1:a;G.call(this);this.i=new N(a);Bc(this,this.i)}
Va(Wv,G);Wv.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
Wv.prototype.m=function(a,b){this.h()||this.i.cb.apply(this.i,arguments)};function Xv(a,b,c){Wv.call(this);this.l=a;this.j=b;this.id=c}
w(Xv,Wv);Xv.prototype.jb=function(a,b){this.h()||this.l.jb(this.j,this.id,a,b)};
Xv.prototype.M=function(){this.j=this.l=null;Wv.prototype.M.call(this)};function Yv(a,b,c){G.call(this);this.i=a;this.origin=c;this.j=Up(window,"message",this.l.bind(this));this.connection=new Xv(this,a,b);Bc(this,this.connection)}
w(Yv,G);Yv.prototype.jb=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
Yv.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
Yv.prototype.M=function(){Vp(this.j);this.i=null;G.prototype.M.call(this)};function Zv(){this.state=1;this.h=null}
m=Zv.prototype;m.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=ub();d=f?f.createScript(d):d;d=new zb(d,yb)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,xb("From proto message. b/166824318"),e=Db(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());$v(this,d,e,a.program,b,c)}else Er(Error("Cannot initialize botguard without program"))};
function $v(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Vu(c,function(){window[g]?aw(a,d,g,e):(a.state=3,$u(c),Er(new Yl("Unable to load Botguard","from "+c)))},f)):b?(f=Hd("SCRIPT"),b instanceof zb?(b instanceof zb&&b.constructor===zb?b=b.j:(La(b),b="type_error:SafeScript"),f.textContent=b,Jh(f)):f.textContent=b,f.nonce=ac(),document.head.appendChild(f),document.head.removeChild(f),window[g]?aw(a,d,g,e):(a.state=4,Er(new Yl("Unable to load Botguard from JS")))):Er(new Yl("Unable to load VM; no url or JS provided"))}
function aw(a,b,c,d){a.state=5;try{var e=new yh({program:b,ne:c,Ge:S("att_web_record_metrics")});e.Ve.then(function(){a.state=6;d&&d(b)});
a.Sc(e)}catch(f){a.state=7,f instanceof Error&&Er(f)}}
m.invoke=function(a){a=void 0===a?{}:a;return this.Vc()?this.Md({hd:a}):null};
m.dispose=function(){this.Yc()};
m.Yc=function(){this.Sc(null);this.state=8};
m.Vc=function(){return!!this.h};
m.Md=function(a){return this.h.Gd(a)};
m.Sc=function(a){zc(this.h);this.h=a};function bw(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function cw(){Zv.apply(this,arguments)}
w(cw,Zv);cw.prototype.Yc=function(){this.state=8};
cw.prototype.Sc=function(a){var b;null==(b=bw())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Gd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
cw.prototype.Vc=function(){return!!bw()};
cw.prototype.Md=function(a){return bw().bgvmc(a)};var dw=new cw;function ew(){return dw.Vc()}
function fw(a){a=void 0===a?{}:a;return dw.invoke(a)}
;function gw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||pb(b);this.assets=a.assets||{};this.attrs=a.attrs||pb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
gw.prototype.clone=function(){var a=new gw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==La(c)?a[b]=pb(c):a[b]=c}return a};var hw=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function iw(a){a=a||"";if(window.spf){var b=a.match(hw);spf.style.load(a,b?b[1]:"",void 0)}else jw(a)}
function jw(a){var b=kw(a),c=document.getElementById(b),d=c&&Ru(c,"loaded");d||c&&!d||(c=lw(a,b,function(){if(!Ru(c,"loaded")){Pu(c);jq(b);var e=Ua(kq,b);$k(e,0)}}))}
function lw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=bk(a);Zb(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function kw(a){var b=Hd("A");Yb(b,new Fb(a,Jb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+cc(a)}
;function mw(){G.call(this);this.i=[]}
w(mw,G);mw.prototype.M=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}G.prototype.M.call(this)};function nw(){mw.apply(this,arguments)}
w(nw,mw);function ow(a,b,c,d,e){G.call(this);var f=this;this.v=b;this.webPlayerContextConfig=d;this.vc=e;this.Ha=!1;this.api={};this.Qa=this.s=null;this.W=new N;this.i={};this.ba=this.wa=this.elementId=this.Lb=this.config=null;this.Z=!1;this.l=this.P=null;this.xa={};this.Rd=["onReady"];this.lastError=null;this.Xb=NaN;this.V={};this.Sd=new nw(this);this.ja=0;this.j=this.m=a;Bc(this,this.W);pw(this);qw(this);Bc(this,this.Sd);c?this.ja=$k(function(){f.loadNewVideoConfig(c)},0):d&&(rw(this),sw(this))}
w(ow,G);m=ow.prototype;m.getId=function(){return this.v};
m.loadNewVideoConfig=function(a){if(!this.h()){this.ja&&(window.clearTimeout(this.ja),this.ja=0);var b=a||{};b instanceof gw||(b=new gw(b));this.config=b;this.setConfig(a);sw(this);this.isReady()&&tw(this)}};
function rw(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){this.Lb=a;this.config=uw(a);rw(this);if(!this.wa){var b;this.wa=vw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=Uh(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=Uh(Number(a)||a))};
function tw(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function ww(a){var b=!0,c=xw(a);c&&a.config&&(a=yw(a),b=Ru(c,"version")===a);return b&&!!E("yt.player.Application.create")}
function sw(a){if(!a.h()&&!a.Z){var b=ww(a);if(b&&"html5"===(xw(a)?"html5":null))a.ba="html5",a.isReady()||zw(a);else if(Aw(a),a.ba="html5",b&&a.l&&a.m)a.m.appendChild(a.l),zw(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.P=function(){c=!0;var d=Bw(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?uw(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.vc);zw(a)};
a.Z=!0;b?a.P():(Vu(yw(a),a.P),(b=Cw(a))&&iw(b),Dw(a)&&!c&&D("yt.player.Application.create",null))}}}
function xw(a){var b=Gd(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function zw(a){if(!a.h()){var b=xw(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Z=!1;if(!Bw(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Ew(a)}else a.Xb=$k(function(){zw(a)},50)}}
function Ew(a){pw(a);a.Ha=!0;var b=xw(a);if(b){a.s=Fw(a,b,"addEventListener");a.Qa=Fw(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Fw(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.s&&a.s(g,a.i[g]);tw(a);a.wa&&a.wa(a.api);a.W.cb("onReady",a.api)}
function Fw(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Er(f))}}}
function pw(a){a.Ha=!1;if(a.Qa)for(var b in a.i)a.i.hasOwnProperty(b)&&a.Qa(b,a.i[b]);for(var c in a.V)a.V.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.V={};a.s=null;a.Qa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Lb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ha};
function qw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){jq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){jq("WATCH_LATER_VIDEO_REMOVED",b)})}
m.addEventListener=function(a,b){var c=this,d=vw(this,b);d&&(0<=ab(this.Rd,a)||this.i[a]||(b=Gw(this,a),this.s&&this.s(a,b)),this.W.subscribe(a,d),"onReady"===a&&this.isReady()&&$k(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h()||(b=vw(this,b))&&yi(this.W,a,b)};
function vw(a,b){var c=b;if("string"===typeof b){if(a.xa[b])return a.xa[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){Dr(f)}};
a.xa[b]=c}return c?c:null}
function Gw(a,b){var c="ytPlayer"+b+a.v;a.i[b]=c;C[c]=function(d){var e=$k(function(){if(!a.h()){try{a.W.cb(b,null!=d?d:void 0)}catch(h){Er(new Yl("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.V,g=String(e);g in f&&delete f[g]}},0);
mb(a.V,String(e))};
return c}
m.getPlayerType=function(){return this.ba||(xw(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function Aw(a){a.cancel();pw(a);a.ba=null;a.config&&(a.config.loaded=!1);var b=xw(a);b&&(ww(a)||!Dw(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.P&&av(yw(this),this.P);window.clearTimeout(this.Xb);this.Z=!1};
m.M=function(){Aw(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Dr(b)}this.xa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(C[this.i[a]]=null);this.Lb=this.config=this.api=null;delete this.m;delete this.j;G.prototype.M.call(this)};
function Dw(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function yw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Cw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Bw(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Kk(c||"","&")[b]}
function uw(a){for(var b={},c=v(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?pb(e):e}return b}
;var Hw={},Iw="player_uid_"+(1E9*Math.random()>>>0);function Jw(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?Gd(c):c;var e=Iw+"_"+Oa(c),f=Hw[e];if(f&&d)return Kw(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new ow(c,e,a,b,void 0);Hw[e]=f;jq("player-added",f.api);Cc(f,function(){delete Hw[f.getId()]});
return f.api}
function Kw(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Lw=null,Mw=null,Nw=null;function Ow(){Pw()}
function Qw(){Pw()}
function Pw(){var a=Lw.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function xu(a){var b,c;if(a=null==(b=a.command)?void 0:null==(c=b.urlEndpoint)?void 0:c.url)b=window,c=Ch(a),void 0!==c&&b.open(c,void 0,void 0);return[]}
function Rw(){Lw&&Lw.sendAbandonmentPing&&Lw.sendAbandonmentPing();R("PL_ATT")&&dw.dispose();for(var a=bi,b=0,c=bv.length;b<c;b++)a.ya(bv[b]);bv.length=0;$u("//static.doubleclick.net/instream/ad_status.js");cv=!1;Bk("DCLKSTAT",0);Ac(Nw,Mw);Lw&&(Lw.removeEventListener("onVideoDataChange",Ow),Lw.destroy())}
;function Sw(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));b&&Os(a,b);if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var e=void 0===e?{}:e;var f=void 0===f?"":f;var g=void 0===g?window:g;b=g.location;a=pc(a,e)+f;var h=void 0===h?Nh:h;a:{h=void 0===h?Nh:h;for(e=0;e<h.length;++e)if(f=h[e],f instanceof Lh&&f.we(a)){h=new Fb(a,Jb);break a}h=void 0}h=Ch(h||Kb);void 0!==h&&(b.href=h)}return!0}
;D("yt.setConfig",Bk);D("yt.config.set",Bk);D("yt.setMsg",Zr);D("yt.msgs.set",Zr);D("yt.logging.errors.log",Dr);
D("writeEmbed",function(){var a=R("PLAYER_CONFIG");if(!a){var b=R("PLAYER_VARS");b&&(a={args:b})}ts(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Rt("embed",["ol"]);c=R("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Pk(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&Rt("watch",["pbs","pbu","pbp"]);Lw=Jw(a,c);S("embeds_enable_server_driven_watch_again_on_youtube")&&!wu.h&&(wu.h=new wu);Lw.addEventListener("onVideoDataChange",Ow);Lw.addEventListener("onReady",Qw);S("embeds_enable_server_driven_watch_again_on_youtube")&&Lw.addEventListener("innertubeCommand",function(f){Bu(wu.h,f)});
a=R("POST_MESSAGE_ID","player");R("ENABLE_JS_API")?Nw=new Rv(Lw):R("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Mw=new Yv(window.parent,a,b),Nw=new Vv(Lw,Mw.connection));dv();S("ytidb_create_logger_embed_killswitch")||mm();a={};vv.h||(vv.h=new vv);vv.h.install((a.flush_logs={callback:function(){jr()}},a));
Kp();S("ytidb_clear_embedded_player")&&bi.ka(function(){var f,g;if(!vu){var h=wq(),k={Pc:uu,Kd:tu};h.h.set(k.Pc,k);k={xc:{feedbackEndpoint:Gs(ou),modifyChannelNotificationPreferenceEndpoint:Gs(pu),playlistEditEndpoint:Gs(qu),subscribeEndpoint:Gs(mu),unsubscribeEndpoint:Gs(nu),webPlayerShareEntityServiceEndpoint:Gs(ru)}};var l=Ds(),n={};l&&(n.client_location=l);void 0===f&&(f=Cl());void 0===g&&(g=h.resolve(uu));$t(k,g,f,n);f={Pc:fu,Ld:Zt.h};h.h.set(f.Pc,f);vu=h.resolve(fu)}Ou()})});
var Tw=Fk(function(){Vt();us()}),Uw=Fk(function(a){a.persisted||(Vt(),us())}),Vw=Fk(function(a){S("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Rw():a.persisted||Rw()}),Ww=Fk(Rw);
window.addEventListener?(window.addEventListener("load",Tw),window.addEventListener("pageshow",Uw),window.addEventListener("pagehide",Vw)):window.attachEvent&&(window.attachEvent("onload",Tw),window.attachEvent("onunload",Ww));
window.onerror=function(a,b,c,d,e){b=void 0===b?"Unknown file":b;c=void 0===c?0:c;var f=!1,g=Ck("log_window_onerror_fraction");if(g&&Math.random()<g)f=!0;else{g=document.getElementsByTagName("script");for(var h=0,k=g.length;h<k;h++)if(0<g[h].src.indexOf("/debug-")){f=!0;break}}f&&(f=!1,e?f=!0:("string"===typeof a?g=a:ErrorEvent&&a instanceof ErrorEvent?(f=!0,g=a.message,b=a.filename,c=a.lineno,d=a.colno):(g="Unknown error",b="Unknown file",c=0),e=new Yl(g),e.name="UnhandledWindowError",e.message=
g,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d),f?Dr(e):Er(e))};
oe=Fr;window.addEventListener("unhandledrejection",function(a){Fr(a.reason)});
bb(R("ERRORS")||[],function(a){Dr.apply(null,a)});
Bk("ERRORS",[]);D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||ew);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||fw);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||ev);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Sw);D("yt.util.activity.init",E("yt.util.activity.init")||Zp);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||bq);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||$p);}).call(this);
