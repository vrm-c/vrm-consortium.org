(function(){'use strict';var p;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function u(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&b!=null&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
u("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",e=0;return b});
u("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];typeof d==="function"&&typeof d.prototype[a]!="function"&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ha(a){return ia(a,a)}
function ia(a,b){a.raw=b;Object.freeze&&(Object.freeze(a),Object.freeze(b));return a}
function v(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ja(a){if(!(a instanceof Array)){a=v(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la=typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
u("Object.assign",function(a){return a||la});
var ma=typeof Object.create=="function"?Object.create:function(a){function b(){}
b.prototype=a;return new b},na=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if(typeof Reflect!="undefined"&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){e===void 0&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),oa;
if(typeof Object.setPrototypeOf=="function")oa=Object.setPrototypeOf;else{var pa;a:{var qa={a:!0},ra={};try{ra.__proto__=qa;pa=ra.a;break a}catch(a){}pa=!1}oa=pa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var sa=oa;
function x(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(sa)sa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Ca=b.prototype}
function va(){this.A=!1;this.u=null;this.i=void 0;this.h=1;this.D=this.o=0;this.I=this.j=null}
function wa(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
va.prototype.H=function(a){this.i=a};
function xa(a,b){a.j={exception:b,gd:!0};a.h=a.o||a.D}
va.prototype.return=function(a){this.j={return:a};this.h=this.D};
va.prototype.yield=function(a,b){this.h=b;return{value:a}};
va.prototype.F=function(a){this.h=a};
function ya(a,b,c){a.o=b;c!=void 0&&(a.D=c)}
function za(a){a.o=0;var b=a.j.exception;a.j=null;return b}
function Aa(a){var b=a.I.splice(0)[0];(b=a.j=a.j||b)?b.gd?a.h=a.o||a.D:b.F!=void 0&&a.D<b.F?(a.h=b.F,a.j=null):a.h=a.D:a.h=0}
function Ba(a){this.h=new va;this.i=a}
function Ca(a,b){wa(a.h);var c=a.h.u;if(c)return Da(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ea(a)}
function Da(a,b,c,d){try{var e=b.call(a.h.u,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.A=!1,e;var f=e.value}catch(g){return a.h.u=null,xa(a.h,g),Ea(a)}a.h.u=null;d.call(a.h,f);return Ea(a)}
function Ea(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.A=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.A=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.gd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Fa(a){this.next=function(b){wa(a.h);a.h.u?b=Da(a,a.h.u.next,b,a.h.H):(a.h.H(b),b=Ea(a));return b};
this.throw=function(b){wa(a.h);a.h.u?b=Da(a,a.h.u["throw"],b,a.h.H):(xa(a.h,b),b=Ea(a));return b};
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
u("Reflect.setPrototypeOf",function(a){return a?a:sa?function(b,c){try{return sa(b,c),!0}catch(d){return!1}}:null});
u("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.A=!1;var h=this.o();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(this.h==null){this.h=[];var h=this;this.j(function(){h.D()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.D=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.o(l)}}}this.h=null};
c.prototype.o=function(g){this.j(function(){throw g;})};
b.prototype.o=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.X),reject:g(this.D)}};
b.prototype.X=function(g){if(g===this)this.D(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ia(g);else{a:switch(typeof g){case "object":var h=g!=null;break a;case "function":h=!0;break a;default:h=!1}h?this.W(g):this.u(g)}};
b.prototype.W=function(g){var h=void 0;try{h=g.then}catch(k){this.D(k);return}typeof h=="function"?this.pa(h,g):this.u(g)};
b.prototype.D=function(g){this.H(2,g)};
b.prototype.u=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(this.h!=0)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;this.h===2&&this.ga();this.I()};
b.prototype.ga=function(){var g=this;e(function(){if(g.T()){var h=da.console;typeof h!=="undefined"&&h.error(g.j)}},1)};
b.prototype.T=function(){if(this.A)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if(typeof k==="undefined")return!0;typeof g==="function"?g=new g("unhandledrejection",{cancelable:!0}):typeof h==="function"?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.I=function(){if(this.i!=null){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ia=function(g){var h=this.o();g.Xb(h.resolve,h.reject)};
b.prototype.pa=function(g,h){var k=this.o();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,t){return typeof r=="function"?function(w){try{l(r(w))}catch(y){m(y)}}:t}
var l,m,n=new b(function(r,t){l=r;m=t});
this.Xb(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Xb=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;this.i==null?f.i(k):this.i.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=v(g),m=l.next();!m.done;m=l.next())d(m.value).Xb(h,k)})};
b.all=function(g){var h=v(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(w){return function(y){r[w]=y;t--;t==0&&l(r)}}
var r=[],t=0;do r.push(void 0),t++,d(k.value).Xb(n(r.length-1),m),k=h.next();while(!k.done)})};
return b});
u("Object.setPrototypeOf",function(a){return a||sa});
u("Symbol.dispose",function(a){return a?a:Symbol("Symbol.dispose")});
u("globalThis",function(a){return a||da});
u("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=v(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return l==="object"&&k!==null||l==="function"}
function e(k){if(!ka(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(m.get(k)!=2||m.get(l)!=3)return!1;m.delete(k);m.set(l,4);return!m.has(k)&&m.get(l)==4}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ka(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&ka(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)?delete k[g][this.h]:!1};
return b});
u("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h[1];return ea(function(){if(l){for(;l.head!=h[1];)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;l=="object"||l=="function"?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h[0][l];if(m&&ka(h[0],l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,entry:n}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this[0]={};this[1]=b();this.size=0;if(h){h=v(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var h=Object.seal({x:4}),k=new a(v([[h,"s"]]));if(k.get(h)!="s"||k.size!=1||k.get({x:4})||k.set({x:4},"t")!=k||k.size!=2)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||m.value[1]!="s")return!1;m=l.next();return m.done||m.value[0].x!=4||m.value[1]!="t"||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=h===0?0:h;var l=d(this,h);l.list||(l.list=this[0][l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this[1],previous:this[1].previous,head:this[1],key:h,value:k},l.list.push(l.entry),this[1].previous.next=l.entry,this[1].previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this[0][h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this[0]={};this[1]=this[1].previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
u("Set",function(a){function b(c){this.h=new Map;if(c){c=v(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||typeof a!="function"||!a.prototype.entries||typeof Object.seal!="function")return!1;try{var c=Object.seal({x:4}),d=new a(v([c]));if(!d.has(c)||d.size!=1||d.add(c)!=d||d.size!=1||d.add({x:4})!=d||d.size!=2)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||f.value[0].x!=4||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=c===0?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
function Ha(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
u("Array.prototype.entries",function(a){return a?a:function(){return Ha(this,function(b,c){return[b,c]})}});
u("Array.prototype.keys",function(a){return a?a:function(){return Ha(this,function(b){return b})}});
function Ia(a,b,c){if(a==null)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
u("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
u("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ia(this,b,"endsWith");b+="";c===void 0&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;e>0&&c>0;)if(d[--c]!=b[--e])return!1;return e<=0}});
u("Number.isFinite",function(a){return a?a:function(b){return typeof b!=="number"?!1:!isNaN(b)&&b!==Infinity&&b!==-Infinity}});
u("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
u("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
u("Object.is",function(a){return a?a:function(b,c){return b===c?b!==0||1/b===1/c:b!==b&&c!==c}});
u("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(c<0&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
u("String.prototype.includes",function(a){return a?a:function(b,c){return Ia(this,b,"includes").indexOf(b,c||0)!==-1}});
u("Array.from",function(a){return a?a:function(b,c,d){c=c!=null?c:function(h){return h};
var e=[],f=typeof Symbol!="undefined"&&Symbol.iterator&&b[Symbol.iterator];if(typeof f=="function"){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
u("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
u("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
u("Number.MIN_SAFE_INTEGER",function(){return-9007199254740991});
u("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
u("Number.isSafeInteger",function(a){return a?a:function(b){return Number.isInteger(b)&&Math.abs(b)<=Number.MAX_SAFE_INTEGER}});
u("Math.trunc",function(a){return a?a:function(b){b=Number(b);if(isNaN(b)||b===Infinity||b===-Infinity||b===0)return b;var c=Math.floor(Math.abs(b));return b<0?-c:c}});
u("Number.isNaN",function(a){return a?a:function(b){return typeof b==="number"&&isNaN(b)}});
u("Array.prototype.values",function(a){return a?a:function(){return Ha(this,function(b,c){return c})}});
u("Math.clz32",function(a){return a?a:function(b){b=Number(b)>>>0;if(b===0)return 32;var c=0;(b&4294901760)===0&&(b<<=16,c+=16);(b&4278190080)===0&&(b<<=8,c+=8);(b&4026531840)===0&&(b<<=4,c+=4);(b&3221225472)===0&&(b<<=2,c+=2);(b&2147483648)===0&&c++;return c}});
u("Math.log10",function(a){return a?a:function(b){return Math.log(b)/Math.LN10}});
u("Promise.prototype.finally",function(a){return a?a:function(b){return this.then(function(c){return Promise.resolve(b()).then(function(){return c})},function(c){return Promise.resolve(b()).then(function(){throw c;
})})}});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Ja=Ja||{},C=this||self;function D(a,b,c){a=a.split(".");c=c||C;a[0]in c||typeof c.execScript=="undefined"||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||b===void 0?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Na(a,b){var c=E("CLOSURE_FLAGS");a=c&&c[a];return a!=null?a:b}
function E(a,b){a=a.split(".");b=b||C;for(var c=0;c<a.length;c++)if(b=b[a[c]],b==null)return null;return b}
function Oa(a){var b=typeof a;return b!="object"?b:a?Array.isArray(a)?"array":b:"null"}
function Pa(a){var b=Oa(a);return b=="array"||b=="object"&&typeof a.length=="number"}
function Qa(a){var b=typeof a;return b=="object"&&a!=null||b=="function"}
function Ra(a){return Object.prototype.hasOwnProperty.call(a,Sa)&&a[Sa]||(a[Sa]=++Ta)}
var Sa="closure_uid_"+(Math.random()*1E9>>>0),Ta=0;function Ua(a,b,c){return a.call.apply(a.bind,arguments)}
function Va(a,b,c){if(!a)throw Error();if(arguments.length>2){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Wa(a,b,c){Wa=Function.prototype.bind&&Function.prototype.bind.toString().indexOf("native code")!=-1?Ua:Va;return Wa.apply(null,arguments)}
function Xa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Ya(){return Date.now()}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Ca=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
;function $a(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,$a);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));b!==void 0&&(this.cause=b)}
Za($a,Error);$a.prototype.name="CustomError";function ab(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.o=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;var bb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};/*

 Copyright Google LLC
 SPDX-License-Identifier: Apache-2.0
*/
var cb=globalThis.trustedTypes,db;function eb(){var a=null;if(!cb)return a;try{var b=function(c){return c};
a=cb.createPolicy("goog#html",{createHTML:b,createScript:b,createScriptURL:b})}catch(c){}return a}
function fb(){db===void 0&&(db=eb());return db}
;function gb(a){this.h=a}
gb.prototype.toString=function(){return this.h+""};
function hb(a){var b=fb();return new gb(b?b.createScriptURL(a):a)}
function ib(a){if(a instanceof gb)return a.h;throw Error("");}
;var jb=ha([""]),kb=ia(["\x00"],["\\0"]),mb=ia(["\n"],["\\n"]),nb=ia(["\x00"],["\\u0000"]);function ob(a){return a.toString().indexOf("`")===-1}
ob(function(a){return a(jb)})||ob(function(a){return a(kb)})||ob(function(a){return a(mb)})||ob(function(a){return a(nb)});function pb(a){this.h=a}
pb.prototype.toString=function(){return this.h};
var qb=new pb("about:invalid#zClosurez");function rb(a){this.ne=a}
function sb(a){return new rb(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var tb=[sb("data"),sb("http"),sb("https"),sb("mailto"),sb("ftp"),new rb(function(a){return/^[^:]*([/?#]|$)/.test(a)})],ub=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function vb(a){if(a instanceof pb)if(a instanceof pb)a=a.h;else throw Error("");else a=ub.test(a)?a:void 0;return a}
;function wb(a,b){b=vb(b);b!==void 0&&(a.href=b)}
;function xb(){this.h=yb[0].toLowerCase()}
xb.prototype.toString=function(){return this.h};function zb(a){this.h=a}
zb.prototype.toString=function(){return this.h+""};function Ab(a){var b="true".toString(),c=[new xb];if(c.length===0)throw Error("");if(c.map(function(d){if(d instanceof xb)d=d.h;else throw Error("");return d}).every(function(d){return"data-loaded".indexOf(d)!==0}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Bb(a,b){throw Error(b===void 0?"unexpected value "+a+"!":b);}
;var Cb="alternate author bookmark canonical cite help icon license modulepreload next prefetch dns-prefetch prerender preconnect preload prev search subresource".split(" ");function Db(a,b){if(b instanceof gb)a.href=ib(b).toString(),a.rel="stylesheet";else{if(Cb.indexOf("stylesheet")===-1)throw Error('TrustedResourceUrl href attribute required with rel="stylesheet"');b=vb(b);b!==void 0&&(a.href=b,a.rel="stylesheet")}}
;function Eb(a){var b,c;return(a=(c=(b=a.document).querySelector)==null?void 0:c.call(b,"script[nonce]"))?a.nonce||a.getAttribute("nonce")||"":""}
;function Fb(a){this.h=a}
Fb.prototype.toString=function(){return this.h+""};function Gb(a){var b=Eb(a.ownerDocument&&a.ownerDocument.defaultView||window);b&&a.setAttribute("nonce",b)}
function Hb(a,b){if(b instanceof Fb)b=b.h;else throw Error("");a.textContent=b;Gb(a)}
function Ib(a,b){a.src=ib(b);Gb(a)}
;var Jb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},Kb=Array.prototype.forEach?function(a,b){Array.prototype.forEach.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)e in d&&b.call(void 0,d[e],e,a)},Lb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f=typeof a==="string"?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},Mb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e=typeof a==="string"?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},Nb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
Kb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Ob(a,b){a:{for(var c=a.length,d=typeof a==="string"?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return b<0?null:typeof a==="string"?a.charAt(b):a[b]}
function Pb(a,b){b=Jb(a,b);var c;(c=b>=0)&&Array.prototype.splice.call(a,b,1);return c}
function Qb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Pa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Rb(a,b){a.__closure__error__context__984382||(a.__closure__error__context__984382={});a.__closure__error__context__984382.severity=b}
;function Sb(a){var b=E("window.location.href");a==null&&(a='Unknown Error of type "null/undefined"');if(typeof a==="string")return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||C.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Tb(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(c==
null){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Ub[c])c=Ub[c];else{c=String(c);if(!Ub[c]){var f=/function\s+([^\(]+)/m.exec(c);Ub[c]=f?f[1]:"[Anonymous]"}c=Ub[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";typeof a.toString==="function"&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}return{message:a.message,
name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:b}}
function Tb(a,b){b||(b={});b[Vb(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Vb(a)]&&(c+="\nCaused by: ",a.stack&&a.stack.indexOf(a.toString())==0||(c+=typeof a==="string"?a:a.message+"\n"),c+=Tb(a,b));return c}
function Vb(a){var b="";typeof a.toString==="function"&&(b=""+a);return b+a.stack}
var Ub={};function Wb(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Xb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Yb(a){return a?decodeURI(a):a}
function Zb(a,b){return b.match(Xb)[a]||null}
function $b(a){return Yb(Zb(3,a))}
function ac(a){var b=a.match(Xb);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function bc(a){var b=a.indexOf("#");return b<0?a:a.slice(0,b)}
function cc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)cc(a,String(b[d]),c);else b!=null&&c.push(a+(b===""?"":"="+encodeURIComponent(String(b))))}
function dc(a){var b=[],c;for(c in a)cc(c,a[c],b);return b.join("&")}
function ec(a,b){b=dc(b);if(b){var c=a.indexOf("#");c<0&&(c=a.length);var d=a.indexOf("?");if(d<0||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
function fc(a,b,c,d){for(var e=c.length;(b=a.indexOf(c,b))>=0&&b<d;){var f=a.charCodeAt(b-1);if(f==38||f==63)if(f=a.charCodeAt(b+e),!f||f==61||f==38||f==35)return b;b+=e+1}return-1}
var hc=/#|$/,ic=/[?&]($|#)/;function jc(a,b){for(var c=a.search(hc),d=0,e,f=[];(e=fc(a,d,b,c))>=0;)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(ic,"$1")}
;function kc(a){var b=b===void 0?Number("29"):b;for(var c=[],d=0;d<lc(a,mc,1).length;d++){var e=lc(a,mc,1)[d];nc(e,2)<=b&&c.push(Number(nc(e,1)))}return c}
function oc(a){var b=b===void 0?Number("29"):b;for(var c=[],d=0;d<lc(a,mc,1).length;d++){var e=lc(a,mc,1)[d];nc(e,2)>b&&c.push(Number(nc(e,1)))}return c}
;function pc(a){return{fieldType:2,fieldName:a}}
function F(a){return{fieldType:3,fieldName:a}}
;function qc(a){this.h=a;a.Ra("/client_streamz/bg/fic",F("ke"))}
function rc(a){this.h=a;a.Ra("/client_streamz/bg/fiec",F("rk"),F("ke"),pc("ec"))}
function sc(a){this.h=a;a.Cb("/client_streamz/bg/fil",F("rk"),F("ke"))}
sc.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fil",a,b,c)};
function tc(a){this.h=a;a.Ra("/client_streamz/bg/fcc",pc("ph"),F("ke"))}
function uc(a){this.h=a;a.Cb("/client_streamz/bg/fcd",pc("ph"),F("ke"))}
uc.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fcd",a,b,c)};
function vc(a){this.h=a;a.Ra("/client_streamz/bg/fsc",F("rk"),F("ke"))}
function wc(a){this.h=a;a.Cb("/client_streamz/bg/fsl",F("rk"),F("ke"))}
wc.prototype.record=function(a,b,c){this.h.record("/client_streamz/bg/fsl",a,b,c)};
function xc(a){this.h=a;a.Cb("/client_streamz/bg/wrl",F("mn"),pc("ac"),pc("sc"),F("rk"),F("mk"))}
xc.prototype.record=function(a,b,c,d,e,f){this.h.record("/client_streamz/bg/wrl",a,b,c,d,e,f)};
function yc(a){this.h=a;a.Cb("/client_streamz/bg/el",F("en"),F("bk"),F("rk"),F("mk"))}
yc.prototype.record=function(a,b,c,d,e){this.h.record("/client_streamz/bg/el",a,b,c,d,e)};
function zc(a){this.h=a;a.Ra("/client_streamz/bg/cec",pc("ec"),F("bk"),F("rk"),F("mk"))}
function Ac(a){a.Ra("/client_streamz/bg/po/csc",pc("cs"),F("rk"),F("mk"))}
function Bc(a){a.Ra("/client_streamz/bg/po/ctav",F("av"),F("rk"),F("mk"))}
function Cc(a){a.Ra("/client_streamz/bg/po/cwsc",F("su"),F("rk"),F("mk"))}
;function Dc(a){C.setTimeout(function(){throw a;},0)}
;var Ec=Na(610401301,!1),Fc=Na(645172343,!0),Gc=Na(653718497,Na(1,!0));function Hc(){var a=C.navigator;return a&&(a=a.userAgent)?a:""}
var Ic,Jc=C.navigator;Ic=Jc?Jc.userAgentData||null:null;function Kc(a){return Ec?Ic?Ic.brands.some(function(b){return(b=b.brand)&&b.indexOf(a)!=-1}):!1:!1}
function H(a){return Hc().indexOf(a)!=-1}
;function Lc(){return Ec?!!Ic&&Ic.brands.length>0:!1}
function Mc(){return Lc()?!1:H("Opera")}
function Nc(){return H("Firefox")||H("FxiOS")}
function Oc(){return Lc()?Kc("Chromium"):(H("Chrome")||H("CriOS"))&&!(Lc()?0:H("Edge"))||H("Silk")}
;function Pc(){return Ec?!!Ic&&!!Ic.platform:!1}
function Qc(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;var Rc=Mc(),Sc=Lc()?!1:H("Trident")||H("MSIE"),Tc=H("Edge"),Uc=H("Gecko")&&!(Hc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),Vc=Hc().toLowerCase().indexOf("webkit")!=-1&&!H("Edge");Vc&&H("Mobile");Pc()||H("Macintosh");Pc()||H("Windows");(Pc()?Ic.platform==="Linux":H("Linux"))||Pc()||H("CrOS");var Wc=Pc()?Ic.platform==="Android":H("Android");Qc();H("iPad");H("iPod");Qc()||H("iPad")||H("iPod");Hc().toLowerCase().indexOf("kaios");Nc();var Xc=Qc()||H("iPod"),Yc=H("iPad");!H("Android")||Oc()||Nc()||Mc()||H("Silk");Oc();var Zc=H("Safari")&&!(Oc()||(Lc()?0:H("Coast"))||Mc()||(Lc()?0:H("Edge"))||(Lc()?Kc("Microsoft Edge"):H("Edg/"))||(Lc()?Kc("Opera"):H("OPR"))||Nc()||H("Silk")||H("Android"))&&!(Qc()||H("iPad")||H("iPod"));var $c={},ad=null;function bd(a,b){Pa(a);b===void 0&&(b=0);cd();b=$c[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],l=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+l+g+h+k}l=0;k=d;switch(a.length-e){case 2:l=a[e+1],k=b[(l&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|l>>4]+k+d}return c.join("")}
function dd(a){var b=a.length,c=b*3/4;c%3?c=Math.floor(c):"=.".indexOf(a[b-1])!=-1&&(c="=.".indexOf(a[b-2])!=-1?c-2:c-1);var d=new Uint8Array(c),e=0;ed(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function ed(a,b){function c(k){for(;d<a.length;){var l=a.charAt(d++),m=ad[l];if(m!=null)return m;if(!/^[\s\xa0]*$/.test(l))throw Error("Unknown base64 encoding at char: "+l);}return k}
cd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(h===64&&e===-1)break;b(e<<2|f>>4);g!=64&&(b(f<<4&240|g>>2),h!=64&&b(g<<6&192|h))}}
function cd(){if(!ad){ad={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;c<5;c++){var d=a.concat(b[c].split(""));$c[c]=d;for(var e=0;e<d.length;e++){var f=d[e];ad[f]===void 0&&(ad[f]=e)}}}}
;var fd=typeof Uint8Array!=="undefined",gd=!Sc&&typeof btoa==="function";function hd(a){if(!gd)return bd(a);for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);return btoa(b)}
var id=/[-_.]/g,jd={"-":"+",_:"/",".":"="};function kd(a){return jd[a]||""}
function ld(a){return fd&&a!=null&&a instanceof Uint8Array}
var md={};var nd;function od(a){if(a!==md)throw Error("illegal external caller");}
function pd(a,b){od(b);this.h=a;if(a!=null&&a.length===0)throw Error("ByteString should be constructed with non-empty values");}
pd.prototype.sizeBytes=function(){od(md);var a=this.h;if(a!=null&&!ld(a))if(typeof a==="string")if(gd){id.test(a)&&(a=a.replace(id,kd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=dd(a);else Oa(a),a=null;return(a=a==null?a:this.h=a)?a.length:0};var qd;function rd(){var a=Error();Rb(a,"incident");Dc(a)}
function sd(a){a=Error(a);Rb(a,"warning");return a}
;function td(){return typeof BigInt==="function"}
;function ud(a){return Array.prototype.slice.call(a)}
;var vd=typeof Symbol==="function"&&typeof Symbol()==="symbol";function wd(a){return typeof Symbol==="function"&&typeof Symbol()==="symbol"?Symbol():a}
var xd=wd(),yd=wd("2ex"),zd=wd("1oa");Math.max.apply(Math,ja(Object.values({Gg:1,Eg:2,Dg:4,Jg:8,Ig:16,Hg:32,xf:64,Lg:128,Cg:256,Bg:512,Fg:1024,Df:2048,Kg:4096,Ef:8192,yf:16384})));var Ad=vd?function(a,b){a[xd]|=b}:function(a,b){a.h!==void 0?a.h|=b:Object.defineProperties(a,{h:{value:b,
configurable:!0,writable:!0,enumerable:!1}})},Bd=vd?function(a){return a[xd]|0}:function(a){return a.h|0},Cd=vd?function(a){return a[xd]}:function(a){return a.h},Dd=vd?function(a,b){a[xd]=b}:function(a,b){a.h!==void 0?a.h=b:Object.defineProperties(a,{h:{value:b,
configurable:!0,writable:!0,enumerable:!1}})};
function Ed(a,b){Dd(b,(a|0)&-14591)}
function Fd(a,b){Dd(b,(a|34)&-14557)}
;var Gd={},Hd={};function Id(a){return!(!a||typeof a!=="object"||a.h!==Hd)}
function Jd(a){return a!==null&&typeof a==="object"&&!Array.isArray(a)&&a.constructor===Object}
function Kd(a){return!Array.isArray(a)||a.length?!1:Bd(a)&1?!0:!1}
var Ld,Md=[];Dd(Md,55);Ld=Object.freeze(Md);function Nd(a){if(a&2)throw Error();}
var Od=Object.freeze({});Object.freeze({});var Pd=Object.freeze({});function Qd(a){a.Wg=!0;return a}
;var Rd=Qd(function(a){return typeof a==="number"}),Sd=Qd(function(a){return typeof a==="string"}),Td=Qd(function(a){return typeof a==="boolean"});
function Ud(){var a=Vd;return Qd(function(b){for(var c in a)if(b===a[c]&&!/^[0-9]+$/.test(c))return!0;return!1})}
;var Wd=typeof C.BigInt==="function"&&typeof C.BigInt(0)==="bigint";function Xd(a){var b=a;if(Sd(b)){if(!/^\s*(?:-?[1-9]\d*|0)?\s*$/.test(b))throw Error(String(b));}else if(Rd(b)&&!Number.isSafeInteger(b))throw Error(String(b));return Wd?BigInt(a):a=Td(a)?a?"1":"0":Sd(a)?a.trim()||"0":String(a)}
var ce=Qd(function(a){return Wd?a>=Yd&&a<=Zd:a[0]==="-"?$d(a,ae):$d(a,be)}),ae=Number.MIN_SAFE_INTEGER.toString(),Yd=Wd?BigInt(Number.MIN_SAFE_INTEGER):void 0,be=Number.MAX_SAFE_INTEGER.toString(),Zd=Wd?BigInt(Number.MAX_SAFE_INTEGER):void 0;
function $d(a,b){if(a.length>b.length)return!1;if(a.length<b.length||a===b)return!0;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(d>e)return!1;if(d<e)return!0}}
;var de=0,ee=0;function fe(a){var b=a>>>0;de=b;ee=(a-b)/4294967296>>>0}
function ge(a){if(a<0){fe(0-a);var b=v(he(de,ee));a=b.next().value;b=b.next().value;de=a>>>0;ee=b>>>0}else fe(a)}
function ie(a,b){b>>>=0;a>>>=0;if(b<=2097151)var c=""+(4294967296*b+a);else td()?c=""+(BigInt(b)<<BigInt(32)|BigInt(a)):(c=(a>>>24|b<<8)&16777215,b=b>>16&65535,a=(a&16777215)+c*6777216+b*6710656,c+=b*8147497,b*=2,a>=1E7&&(c+=a/1E7>>>0,a%=1E7),c>=1E7&&(b+=c/1E7>>>0,c%=1E7),c=b+je(c)+je(a));return c}
function je(a){a=String(a);return"0000000".slice(a.length)+a}
function ke(){var a=de,b=ee;b&2147483648?td()?a=""+(BigInt(b|0)<<BigInt(32)|BigInt(a>>>0)):(b=v(he(a,b)),a=b.next().value,b=b.next().value,a="-"+ie(a,b)):a=ie(a,b);return a}
function he(a,b){b=~b;a?a=~a+1:b+=1;return[a,b]}
;function le(a){return a.displayName||a.name||"unknown type name"}
function me(a){if(a!=null&&typeof a!=="boolean")throw Error("Expected boolean but got "+Oa(a)+": "+a);return a}
var ne=/^-?([1-9][0-9]*|0)(\.[0-9]+)?$/;function oe(a){var b=typeof a;switch(b){case "bigint":return!0;case "number":return Number.isFinite(a)}return b!=="string"?!1:ne.test(a)}
function pe(a){if(typeof a!=="number")throw sd("int32");if(!Number.isFinite(a))throw sd("int32");return a|0}
function qe(a){return a==null?a:pe(a)}
function re(a){if(a==null)return a;if(typeof a==="string"){if(!a)return;a=+a}if(typeof a==="number")return Number.isFinite(a)?a|0:void 0}
function se(a){var b=0;b=b===void 0?0:b;if(!oe(a))throw sd("int64");var c=typeof a;switch(b){case 4096:switch(c){case "string":return te(a);case "bigint":return String(BigInt.asIntN(64,a));default:return ue(a)}case 8192:switch(c){case "string":return b=Math.trunc(Number(a)),Number.isSafeInteger(b)?a=Xd(b):(b=a.indexOf("."),b!==-1&&(a=a.substring(0,b)),a=td()?Xd(BigInt.asIntN(64,BigInt(a))):Xd(ve(a))),a;case "bigint":return Xd(BigInt.asIntN(64,a));default:return Xd(we(a))}case 0:switch(c){case "string":return te(a);
case "bigint":return Xd(BigInt.asIntN(64,a));default:return we(a)}default:return Bb(b,"Unknown format requested type for int64")}}
function xe(a){return a==null?a:se(a)}
function ye(a){return a[0]==="-"?a.length<20?!0:a.length===20&&Number(a.substring(0,7))>-922337:a.length<19?!0:a.length===19&&Number(a.substring(0,6))<922337}
function ve(a){a.indexOf(".");if(ye(a))return a;if(a.length<16)ge(Number(a));else if(td())a=BigInt(a),de=Number(a&BigInt(4294967295))>>>0,ee=Number(a>>BigInt(32)&BigInt(4294967295));else{var b=+(a[0]==="-");ee=de=0;for(var c=a.length,d=0+b,e=(c-b)%6+b;e<=c;d=e,e+=6)d=Number(a.slice(d,e)),ee*=1E6,de=de*1E6+d,de>=4294967296&&(ee+=Math.trunc(de/4294967296),ee>>>=0,de>>>=0);b&&(b=v(he(de,ee)),a=b.next().value,b=b.next().value,de=a,ee=b)}return ke()}
function we(a){oe(a);a=Math.trunc(a);if(!Number.isSafeInteger(a)){ge(a);var b=de,c=ee;if(a=c&2147483648)b=~b+1>>>0,c=~c>>>0,b==0&&(c=c+1>>>0);b=c*4294967296+(b>>>0);a=a?-b:b}return a}
function ue(a){oe(a);a=Math.trunc(a);if(Number.isSafeInteger(a))a=String(a);else{var b=String(a);ye(b)?a=b:(ge(a),a=ke())}return a}
function te(a){oe(a);var b=Math.trunc(Number(a));if(Number.isSafeInteger(b))return String(b);b=a.indexOf(".");b!==-1&&(a=a.substring(0,b));return ve(a)}
function ze(a){if(a==null)return a;if(typeof a==="bigint")return ce(a)?a=Number(a):(a=BigInt.asIntN(64,a),a=ce(a)?Number(a):String(a)),a;if(oe(a))return typeof a==="number"?we(a):te(a)}
function Ae(a){if(typeof a!=="string")throw Error();return a}
function Be(a){if(a!=null&&typeof a!=="string")throw Error();return a}
function Ce(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+le(b)+" but got "+(a&&le(a.constructor)));}
function De(a,b,c){if(a!=null&&typeof a==="object"&&a.Dc===Gd)return a;if(Array.isArray(a)){var d=Bd(a),e=d;e===0&&(e|=c&32);e|=c&2;e!==d&&Dd(a,e);return new b(a)}}
;function Ee(a){Fe===void 0&&(Fe=typeof Proxy==="function"?Ge(Proxy):null);if(!Fe||!He())return a;var b=Ie(a);if(b)return b;if(Math.random()>.01)return a;typeof Symbol!=="undefined"&&Symbol.isConcatSpreadable&&(a[Symbol.isConcatSpreadable]=!0);b=new Fe(a,{set:function(c,d,e){Je();c[d]=e;return!0}});
Ke(a,b);return b}
function Je(){rd()}
var Le=void 0,Me=void 0;function Ie(a){var b;return(b=Le)==null?void 0:b.get(a)}
function Ne(a){var b;return((b=Me)==null?void 0:b.get(a))||a}
function Ke(a,b){(Le||(Le=new Oe)).set(a,b);(Me||(Me=new Oe)).set(b,a)}
var Fe=void 0,Oe=void 0;function He(){Oe===void 0&&(Oe=typeof WeakMap==="function"?Ge(WeakMap):null);return Oe}
function Ge(a){try{return a.toString().indexOf("[native code]")!==-1?a:null}catch(b){return null}}
function Pe(a,b,c){if(Gc&&He()){if(Qe(a,b)){if(c)return}else if(Math.random()>.01)return;if(a.length<=10)c=a.slice();else{c=Array(a.length);for(var d=0;d<10;d++){var e=Math.floor(Math.random()*a.length);c[e]=a[e]}}d=Re||(Re=new Oe);e=d.get(b);e||(e=new Oe,d.set(b,e));e.set(a,c)}}
function Se(a,b){var c=Qe(a,b);c&&(a.length!==c.length||c.some(function(d,e){e=a[e];return!(Number.isNaN(e)?Number.isNaN(d):e===d)}))&&(Te(),Ue(a,b))}
function Ve(a){if(a){var b=a.G;if(b)for(var c=0;c<b.length;c++){var d=b[c];if(c===b.length-1&&Jd(d))for(var e in d){var f=d[e];Array.isArray(f)&&Se(f,a)}else Array.isArray(d)&&Se(d,a)}}}
function Te(){rd()}
var Re=void 0;function Qe(a,b){var c,d;return(c=Re)==null?void 0:(d=c.get(b))==null?void 0:d.get(a)}
function Ue(a,b){var c,d;(c=Re)==null||(d=c.get(b))==null||d.delete(a)}
;var We;function Xe(a,b){Bd(b);We=b;a=new a(b);We=void 0;return a}
function J(a,b,c){a==null&&(a=We);We=void 0;if(a==null){var d=96;c?(a=[c],d|=512):a=[];b&&(d=d&-33521665|(b&1023)<<15)}else{if(!Array.isArray(a))throw Error("narr");d=Bd(a);if(d&2048)throw Error("farr");if(d&64)return a;d|=64;if(c&&(d|=512,c!==a[0]))throw Error("mid");a:{c=a;var e=c.length;if(e){var f=e-1;if(Jd(c[f])){d|=256;b=f-(+!!(d&512)-1);if(b>=1024)throw Error("pvtlmt");d=d&-33521665|(b&1023)<<15;break a}}if(b){b=Math.max(b,e-(+!!(d&512)-1));if(b>1024)throw Error("spvt");d=d&-33521665|(b&1023)<<
15}}}Dd(a,d);return a}
;function Ye(a,b){return Ze(b)}
function Ze(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "bigint":return ce(a)?Number(a):String(a);case "boolean":return a?1:0;case "object":if(a)if(Array.isArray(a)){if(Kd(a))return}else{if(ld(a))return hd(a);if(a instanceof pd){var b=a.h;return b==null?"":typeof b==="string"?b:a.h=hd(b)}}}return a}
;function $e(a,b,c){a=ud(a);var d=a.length,e=b&256?a[d-1]:void 0;d+=e?-1:0;for(b=b&512?1:0;b<d;b++)a[b]=c(a[b]);if(e){b=a[b]={};for(var f in e)b[f]=c(e[f])}return a}
function af(a,b,c,d,e){if(a!=null){if(Array.isArray(a))a=Kd(a)?void 0:e&&Bd(a)&2?a:bf(a,b,c,d!==void 0,e);else if(Jd(a)){var f={},g;for(g in a)f[g]=af(a[g],b,c,d,e);a=f}else a=b(a,d);return a}}
function bf(a,b,c,d,e){var f=d||c?Bd(a):0;d=d?!!(f&32):void 0;a=ud(a);for(var g=0;g<a.length;g++)a[g]=af(a[g],b,c,d,e);c&&c(f,a);return a}
function cf(a){return a.Dc===Gd?a.toJSON():Ze(a)}
;function df(a,b,c){c=c===void 0?Fd:c;if(a!=null){if(fd&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=Bd(a);if(d&2)return a;b&&(b=d===0||!!(d&32)&&!(d&64||!(d&16)));return b?(Dd(a,(d|34)&-12293),a):bf(a,df,d&4?Fd:c,!0,!0)}a.Dc===Gd&&(c=a.G,d=Cd(c),a=d&2?a:ef(a,c,d,!0));return a}}
function ef(a,b,c,d){Ve(a);return Xe(a.constructor,ff(b,c,d))}
function ff(a,b,c){var d=c||b&2?Fd:Ed,e=!!(b&32);a=$e(a,b,function(f){return df(f,e,d)});
Ad(a,32|(c?2:0));return a}
function gf(a){var b=a.G,c=Cd(b);return c&2?ef(a,b,c,!1):a}
;function hf(a,b){a=a.G;return jf(a,Cd(a),b)}
function kf(a,b,c,d){b=d+(+!!(b&512)-1);if(!(b<0||b>=a.length||b>=c))return a[b]}
function jf(a,b,c,d){if(c===-1)return null;var e=b>>15&1023||536870912;if(c>=e){if(b&256)return a[a.length-1][c]}else{var f=a.length;if(d&&b&256&&(d=a[f-1][c],d!=null)){if(kf(a,b,e,c)&&yd!=null){var g;a=(g=qd)!=null?g:qd={};g=a[yd]||0;g>=4||(a[yd]=g+1,rd())}return d}return kf(a,b,e,c)}}
function lf(a,b,c){var d=a.G,e=Cd(d);Nd(e);mf(d,e,b,c);return a}
function mf(a,b,c,d,e){Jd(d);var f=b>>15&1023||536870912;if(c>=f||e&&!Fc){var g=b;if(b&256)e=a[a.length-1];else{if(d==null)return g;e=a[f+(+!!(b&512)-1)]={};g|=256}e[c]=d;c<f&&(a[c+(+!!(b&512)-1)]=void 0);g!==b&&Dd(a,g);return g}a[c+(+!!(b&512)-1)]=d;b&256&&(a=a[a.length-1],c in a&&delete a[c]);return b}
function nf(a){return of(a,pf,11,!1)!==void 0}
function qf(a){return!!(2&a)&&!!(4&a)||!!(2048&a)}
function rf(a,b,c){var d=a.G,e=Cd(d);Nd(e);if(b==null)return mf(d,e,3),a;b=Ne(b);if(!Array.isArray(b))throw sd();var f=Bd(b),g=f,h=!!(2&f)||Object.isFrozen(b),k=!h&&(void 0===Pd||!1);if(!(4&f)){f=21;h&&(b=ud(b),g=0,f=sf(f,e),f=tf(f,e,!0));for(var l=0;l<b.length;l++)b[l]=c(b[l])}k?(b=ud(b),g=0,f=sf(f,e),f=tf(f,e,!0)):h||Pe(b,a);f!==g&&Dd(b,f);mf(d,e,3,b);return a}
function uf(a,b,c,d){a=a.G;var e=Cd(a);Nd(e);if(d==null){var f=vf(a);if(wf(f,a,e,c)===b)f.set(c,0);else return}else{c.includes(b);f=vf(a);var g=wf(f,a,e,c);g!==b&&(g&&(e=mf(a,e,g)),f.set(c,b))}mf(a,e,b,d)}
function vf(a){if(vd){var b;return(b=a[zd])!=null?b:a[zd]=new Map}if(zd in a)return a[zd];b=new Map;Object.defineProperty(a,zd,{value:b});return b}
function wf(a,b,c,d){var e=a.get(d);if(e!=null)return e;for(var f=e=0;f<d.length;f++){var g=d[f];jf(b,c,g)!=null&&(e!==0&&(c=mf(b,c,e)),e=g)}a.set(d,e);return e}
function of(a,b,c,d){a=a.G;var e=Cd(a),f=jf(a,e,c,d);b=De(f,b,e);b!==f&&b!=null&&mf(a,e,c,b,d);return b}
function xf(a,b,c,d){d=d===void 0?!1:d;b=of(a,b,c,d);if(b==null)return b;a=a.G;var e=Cd(a);if(!(e&2)){var f=gf(b);f!==b&&(b=f,mf(a,e,c,b,d))}return b}
function lc(a,b,c){var d=void 0===Od?2:5;var e=Cd(a.G),f=e,g=!(2&e);e=a.G;var h=!!(2&f);d=h?1:d;g&&(g=!h);h=jf(e,f,c);h=Array.isArray(h)?h:Ld;var k=Bd(h),l=h;Se(l,a);d!==2&&d!==1||Ue(l,a);l=!!(4&k);if(!l){var m=k;m===0&&(m=sf(m,f));k=h;m|=1;var n=f,r=!!(2&m);r&&(n|=2);for(var t=!r,w=!0,y=0,z=0;y<k.length;y++){var G=De(k[y],b,n);if(G instanceof b){if(!r){var I=!!(Bd(G.G)&2);t&&(t=!I);w&&(w=I)}k[z++]=G}}z<y&&(k.length=z);m|=4;m=w?m|16:m&-17;m=t?m|8:m&-9;Dd(k,m);r&&Object.freeze(k);k=m}if(g&&!(8&k||
!h.length&&(d===1||d===4&&32&k))){qf(k)?(h=ud(h),k=sf(k,f),f=mf(e,f,c,h)):Ue(h,a);b=h;g=k;for(k=0;k<b.length;k++)m=b[k],n=gf(m),m!==n&&(b[k]=n);g|=8;g=b.length?g&-17:g|16;Dd(b,g);k=g}if(d===1||d===4&&32&k)qf(k)||(a=k,f=!!(32&k),k|=!h.length||16&k&&(!l||f)?2:2048,k!==a&&Dd(h,k),Object.freeze(h));else if(l=d!==5?!1:!!(32&k)||qf(k)||!!Ie(h),(d===2||l)&&qf(k)&&(h=ud(h),k=sf(k,f),k=tf(k,f,!1),Dd(h,k),f=mf(e,f,c,h)),qf(k)||(c=k,k=tf(k,f,!1),k!==c&&Dd(h,k)),l){var M=Ee(h);Pe(h,a,!0)}else if(d===2){var O;
(O=Le)==null||O.delete(h)}return M||h}
function yf(a,b,c,d){d!=null?Ce(d,b):d=void 0;return lf(a,c,d)}
function zf(a,b,c,d){var e=a.G,f=Cd(e);Nd(f);if(d==null)return mf(e,f,c),a;d=Ne(d);if(!Array.isArray(d))throw sd();for(var g=Bd(d),h=g,k=!!(2&g)||!!(2048&g),l=k||Object.isFrozen(d),m=!l&&(void 0===Pd||!1),n=!0,r=!0,t=0;t<d.length;t++){var w=d[t];Ce(w,b);k||(w=!!(Bd(w.G)&2),n&&(n=!w),r&&(r=w))}k||(g|=5,g=n?g|8:g&-9,g=r?g|16:g&-17);m||l&&g!==h?(d=ud(d),h=0,g=sf(g,f),g=tf(g,f,!0)):l||Pe(d,a);g!==h&&Dd(d,g);mf(e,f,c,d);return a}
function sf(a,b){a=(2&b?a|2:a&-3)|32;return a&=-2049}
function tf(a,b,c){32&b&&c||(a&=-33);return a}
function Af(a){a=hf(a,1);var b=b===void 0?!1:b;var c=typeof a;b=a==null?a:c==="bigint"?String(BigInt.asIntN(64,a)):oe(a)?c==="string"?te(a):b?ue(a):we(a):void 0;return b}
function Bf(a,b){return a!=null?a:b}
function Cf(a){var b=b===void 0?!1:b;a=hf(a,4);return Bf(a==null||typeof a==="boolean"?a:typeof a==="number"?!!a:void 0,b)}
function nc(a,b,c){c=c===void 0?0:c;return Bf(re(hf(a,b)),c)}
function Df(a,b){var c=c===void 0?"":c;a=hf(a,b);return Bf(a==null||typeof a==="string"?a:void 0,c)}
function Ef(a){var b=0;b=b===void 0?0:b;a=hf(a,1);a=a==null?a:Number.isFinite(a)?a|0:void 0;return Bf(a,b)}
function Ff(a,b,c){return lf(a,b,Be(c))}
function Gf(a,b,c){if(c!=null){if(!Number.isFinite(c))throw sd("enum");c|=0}return lf(a,b,c)}
;function Hf(a){return a}
function If(a){return a}
function Jf(a,b,c,d){return Kf(a,b,c,d,Lf,Mf)}
function Nf(a,b,c,d){return Kf(a,b,c,d,Of,Pf)}
function Kf(a,b,c,d,e,f){if(!c.length&&!d)return 0;for(var g=0,h=0,k=0,l=0,m=0,n=c.length-1;n>=0;n--){var r=c[n];d&&n===c.length-1&&r===d||(l++,r!=null&&k++)}if(d)for(var t in d)n=+t,isNaN(n)||(m+=Qf(n),h++,n>g&&(g=n));l=e(l,k)+f(h,g,m);t=k;n=h;r=g;for(var w=m,y=c.length-1;y>=0;y--){var z=c[y];if(!(z==null||d&&y===c.length-1&&z===d)){z=y-b;var G=e(z,t)+f(n,r,w);G<l&&(a=1+z,l=G);n++;t--;w+=Qf(z);r=Math.max(r,z)}}b=e(0,0)+f(n,r,w);b<l&&(a=0,l=b);if(d){n=h;r=g;w=m;t=k;for(var I in d)d=+I,isNaN(d)||d>=
1024||(n--,t++,w-=I.length,g=e(d,t)+f(n,r,w),g<l&&(a=1+d,l=g))}return a}
function Pf(a,b,c){return c+a*3+(a>1?a-1:0)}
function Of(a,b){return(a>1?a-1:0)+(a-b)*4}
function Mf(a,b){return a==0?0:9*Math.max(1<<32-Math.clz32(a+a/2-1),4)<=b?a==0?0:a<4?100+(a-1)*16:a<6?148+(a-4)*16:a<12?244+(a-6)*16:a<22?436+(a-12)*19:a<44?820+(a-22)*17:52+32*a:40+4*b}
function Lf(a){return 40+4*a}
function Qf(a){return a>=100?a>=1E4?Math.ceil(Math.log10(1+a)):a<1E3?3:4:a<10?1:2}
;var Rf,Sf;function K(a,b,c){this.G=J(a,b,c)}
p=K.prototype;p.toJSON=function(){return Tf(this)};
p.serialize=function(a){try{return Sf=!0,a&&(Rf=a===If||a!==Hf&&a!==Jf&&a!==Nf?If:a),JSON.stringify(Tf(this),Ye)}finally{a&&(Rf=void 0),Sf=!1}};
function Uf(a,b){if(b==null||b=="")return new a;b=JSON.parse(b);if(!Array.isArray(b))throw Error("dnarr");Ad(b,32);return Xe(a,b)}
p.clone=function(){var a=this.G;return ef(this,a,Cd(a),!1)};
p.Dc=Gd;p.toString=function(){try{return Sf=!0,Tf(this).toString()}finally{Sf=!1}};
function Tf(a){Ve(a);var b;Sf?b=a.G:b=bf(a.G,cf,void 0,void 0,!1);var c=!Sf,d=Cd(c?a.G:b);if(a=b.length){var e=b[a-1],f=Jd(e);f?a--:e=void 0;var g=+!!(d&512)-1,h=a-g;d=!!Rf&&Fc&&!(d&512);var k,l=(k=Rf)!=null?k:If;k=d?l(h,g,b,e):h;d=(h=d&&h!==k)?Array.prototype.slice.call(b,0,a):b;if(f||h){b:{var m=d;var n=e;f={};l=!1;if(h)for(var r=Math.max(0,k+g);r<m.length;r++){var t=m[r],w=r-g;t==null||Kd(t)||Id(t)&&t.size===0||(m[r]=void 0,f[w]=t,l=!0)}if(n)for(var y in n)if(r=+y,isNaN(r))f[y]=n[y];else if(t=
n[y],Array.isArray(t)&&(Kd(t)||Id(t)&&t.size===0)&&(t=null),t==null&&(l=!0),h&&r<k){l=!0;t=r+g;for(w=m.length;w<=t;w++)m.push(void 0);m[t]=n[r]}else t!=null&&(f[y]=t);if(l){for(var z in f){n=f;break b}n=null}}m=n==null?e!=null:n!==e}h&&(a=d.length);for(;a>0;a--){y=d[a-1];if(!(y==null||Kd(y)||Id(y)&&y.size===0))break;var G=!0}if(d!==b||m||G){if(!h&&!c)d=Array.prototype.slice.call(d,0,a);else if(G||m||n)d.length=a;n&&d.push(n)}G=d}else G=b;return G}
;function Vf(a){return function(b){return Uf(a,b)}}
;function Wf(a){this.G=J(a)}
x(Wf,K);function Xf(a,b){return rf(a,b,pe)}
;function Yf(a){this.G=J(a)}
x(Yf,K);var Zf=[1,2,3];function $f(a){this.G=J(a)}
x($f,K);var ag=[1,2,3];function bg(a){this.G=J(a)}
x(bg,K);function cg(a){this.G=J(a)}
x(cg,K);function dg(a){this.G=J(a)}
x(dg,K);function eg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.indexOf("blob:")===0&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();a.indexOf("//")==0&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");c!=-1&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if(c!=="http"&&c!=="https"&&c!=="chrome-extension"&&
c!=="moz-extension"&&c!=="file"&&c!=="android-app"&&c!=="chrome-search"&&c!=="chrome-untrusted"&&c!=="chrome"&&c!=="app"&&c!=="devtools")throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(d!=-1){var e=b.substring(d+1);b=b.substring(0,d);if(c==="http"&&e!=="80"||c==="https"&&e!=="443")a=":"+e}return c+"://"+b+a}
;function fg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var r=g,t=0;t<64;t+=4)r[t/4]=n[t]<<24|n[t+1]<<16|n[t+2]<<8|n[t+3];for(t=16;t<80;t++)n=r[t-3]^r[t-8]^r[t-14]^r[t-16],r[t]=(n<<1|n>>>31)&4294967295;n=e[0];var w=e[1],y=e[2],z=e[3],G=e[4];for(t=0;t<80;t++){if(t<40)if(t<20){var I=z^w&(y^z);var M=1518500249}else I=w^y^z,M=1859775393;else t<60?(I=w&y|z&(w|y),M=2400959708):(I=w^y^z,M=3395469782);I=((n<<5|n>>>27)&4294967295)+I+G+M+r[t]&4294967295;G=z;z=y;y=(w<<30|w>>>2)&4294967295;w=n;n=I}e[0]=e[0]+n&4294967295;e[1]=e[1]+w&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+z&4294967295;e[4]=e[4]+G&4294967295}
function c(n,r){if(typeof n==="string"){n=unescape(encodeURIComponent(n));for(var t=[],w=0,y=n.length;w<y;++w)t.push(n.charCodeAt(w));n=t}r||(r=n.length);t=0;if(l==0)for(;t+64<r;)b(n.slice(t,t+64)),t+=64,m+=64;for(;t<r;)if(f[l++]=n[t++],m++,l==64)for(l=0,b(f);t+64<r;)b(n.slice(t,t+64)),t+=64,m+=64}
function d(){var n=[],r=m*8;l<56?c(h,56-l):c(h,64-(l-56));for(var t=63;t>=56;t--)f[t]=r&255,r>>>=8;b(f);for(t=r=0;t<5;t++)for(var w=24;w>=0;w-=8)n[r++]=e[t]>>w&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;k<64;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Qd:function(){for(var n=d(),r="",t=0;t<n.length;t++)r+="0123456789ABCDEF".charAt(Math.floor(n[t]/16))+"0123456789ABCDEF".charAt(n[t]%16);return r}}}
;function gg(a,b,c){var d=String(C.location.href);return d&&a&&b?[b,hg(eg(d),a,c||null)].join(" "):null}
function hg(a,b,c){var d=[],e=[];if((Array.isArray(c)?2:1)==1)return e=[b,a],Kb(d,function(h){e.push(h)}),ig(e.join(" "));
var f=[],g=[];Kb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=f.length==0?[c,b,a]:[f.join(":"),c,b,a];Kb(d,function(h){e.push(h)});
a=ig(e.join(" "));a=[c,a];g.length==0||a.push(g.join(""));return a.join("_")}
function ig(a){var b=fg();b.update(a);return b.Qd().toLowerCase()}
;var jg={};function kg(a){this.h=a||{cookie:""}}
p=kg.prototype;p.isEnabled=function(){if(!C.navigator.cookieEnabled)return!1;if(this.h.cookie)return!0;this.set("TESTCOOKIESENABLED","1",{Lb:60});if(this.get("TESTCOOKIESENABLED")!=="1")return!1;this.remove("TESTCOOKIESENABLED");return!0};
p.set=function(a,b,c){var d=!1;if(typeof c==="object"){var e=c.Je;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Lb}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');h===void 0&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=h<0?"":h==0?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+h*1E3)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(e!=null?";samesite="+
e:"")};
p.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=bb(d[e]);if(f.lastIndexOf(c,0)==0)return f.slice(c.length);if(f==a)return""}return b};
p.remove=function(a,b,c){var d=this.get(a)!==void 0;this.set(a,"",{Lb:0,path:b,domain:c});return d};
p.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=bb(a[f]),d=e.indexOf("="),d==-1?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;a>=0;a--)this.remove(b[a])};
var lg=new kg(typeof document=="undefined"?null:document);function mg(a){return!!jg.FPA_SAMESITE_PHASE2_MOD||!(a===void 0||!a)}
function ng(a){a=a===void 0?!1:a;var b=C.__SAPISID||C.__APISID||C.__3PSAPISID||C.__OVERRIDE_SID;mg(a)&&(b=b||C.__1PSAPISID);if(b)return!0;if(typeof document!=="undefined"){var c=new kg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID");mg(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function og(a,b,c,d){(a=C[a])||typeof document==="undefined"||(a=(new kg(document)).get(b));return a?gg(a,c,d):null}
function pg(a,b){b=b===void 0?!1:b;var c=eg(String(C.location.href)),d=[];if(ng(b)){c=c.indexOf("https:")==0||c.indexOf("chrome-extension:")==0||c.indexOf("chrome-untrusted://new-tab-page")==0||c.indexOf("moz-extension:")==0;var e=c?C.__SAPISID:C.__APISID;e||typeof document==="undefined"||(e=new kg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?gg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&mg(b)&&((b=og("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),
(a=og("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return d.length==0?null:d.join(" ")}
;function qg(a){a&&typeof a.dispose=="function"&&a.dispose()}
;function rg(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Pa(d)?rg.apply(null,d):qg(d)}}
;function L(){this.ea=this.ea;this.D=this.D}
L.prototype.ea=!1;L.prototype.dispose=function(){this.ea||(this.ea=!0,this.ba())};
L.prototype[Symbol.dispose]=function(){this.dispose()};
function sg(a,b){a.addOnDisposeCallback(Xa(qg,b))}
L.prototype.addOnDisposeCallback=function(a,b){this.ea?b!==void 0?a.call(b):a():(this.D||(this.D=[]),b&&(a=a.bind(b)),this.D.push(a))};
L.prototype.ba=function(){if(this.D)for(;this.D.length;)this.D.shift()()};function tg(a){this.G=J(a)}
x(tg,K);function ug(a,b){this.intervalMs=a;this.callback=b;this.enabled=!1;this.h=function(){return Ya()};
this.i=this.h()}
ug.prototype.setInterval=function(a){this.intervalMs=a;this.timer&&this.enabled?(this.stop(),this.start()):this.timer&&this.stop()};
ug.prototype.start=function(){var a=this;this.enabled=!0;this.timer||(this.timer=setTimeout(function(){a.tick()},this.intervalMs),this.i=this.h())};
ug.prototype.stop=function(){this.enabled=!1;this.timer&&(clearTimeout(this.timer),this.timer=void 0)};
ug.prototype.tick=function(){var a=this;if(this.enabled){var b=Math.max(this.h()-this.i,0);b<this.intervalMs*.8?this.timer=setTimeout(function(){a.tick()},this.intervalMs-b):(this.timer&&(clearTimeout(this.timer),this.timer=void 0),this.callback(),this.enabled&&(this.stop(),this.start()))}else this.timer=void 0};function vg(a){this.G=J(a)}
x(vg,K);function wg(a){this.G=J(a)}
x(wg,K);function xg(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function yg(a){var b=zg,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function Ag(a){for(var b in a)return!1;return!0}
function Bg(a,b){if(a!==null&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function Cg(a){return a!==null&&"privembed"in a?a.privembed:!1}
function Dg(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Eg(a){var b={},c;for(c in a)b[c]=a[c];return b}
function Fg(a){if(!a||typeof a!=="object")return a;if(typeof a.clone==="function")return a.clone();if(typeof Map!=="undefined"&&a instanceof Map)return new Map(a);if(typeof Set!=="undefined"&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:typeof ArrayBuffer!=="function"||typeof ArrayBuffer.isView!=="function"||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Fg(a[c]);return b}
var Gg="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Hg(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Gg.length;f++)c=Gg[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;function Ig(a,b){this.h=a===Jg&&b||""}
Ig.prototype.toString=function(){return this.h};
var Jg={};new Ig(Jg,"");"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Kg(a,b){this.x=a!==void 0?a:0;this.y=b!==void 0?b:0}
p=Kg.prototype;p.clone=function(){return new Kg(this.x,this.y)};
p.equals=function(a){return a instanceof Kg&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
p.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
p.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
p.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
p.scale=function(a,b){this.x*=a;this.y*=typeof b==="number"?b:a;return this};function Lg(a,b){this.width=a;this.height=b}
p=Lg.prototype;p.clone=function(){return new Lg(this.width,this.height)};
p.aspectRatio=function(){return this.width/this.height};
p.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
p.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
p.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
p.scale=function(a,b){this.width*=a;this.height*=typeof b==="number"?b:a;return this};function Mg(a){var b=document;return typeof a==="string"?b.getElementById(a):a}
function Ng(a){var b=document;a=String(a);b.contentType==="application/xhtml+xml"&&(a=a.toLowerCase());return b.createElement(a)}
function Og(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var Pg=function(){if(!C.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
C.addEventListener("test",c,b);C.removeEventListener("test",c,b)}catch(d){}return a}();function Qg(a){this.h=this.i=this.j=a}
Qg.prototype.reset=function(){this.h=this.i=this.j};
Qg.prototype.getValue=function(){return this.i};function Rg(a){this.G=J(a)}
x(Rg,K);Rg.prototype.cc=function(){return Ef(this)};function Sg(a){this.G=J(a)}
x(Sg,K);function Tg(a){this.G=J(a)}
x(Tg,K);function Ug(a,b){zf(a,Sg,1,b)}
;function pf(a){this.G=J(a)}
x(pf,K);var Vg=["platform","platformVersion","architecture","model","uaFullVersion"],Wg=new Tg,Xg=null;function Yg(a,b){b=b===void 0?Vg:b;if(!Xg){var c;a=(c=a.navigator)==null?void 0:c.userAgentData;if(!a||typeof a.getHighEntropyValues!=="function"||a.brands&&typeof a.brands.map!=="function")return Promise.reject(Error("UACH unavailable"));c=(a.brands||[]).map(function(e){var f=new Sg;f=Ff(f,1,e.brand);return Ff(f,2,e.version)});
Ug(lf(Wg,2,me(a.mobile)),c);Xg=a.getHighEntropyValues(b)}var d=new Set(b);return Xg.then(function(e){var f=Wg.clone();d.has("platform")&&Ff(f,3,e.platform);d.has("platformVersion")&&Ff(f,4,e.platformVersion);d.has("architecture")&&Ff(f,5,e.architecture);d.has("model")&&Ff(f,6,e.model);d.has("uaFullVersion")&&Ff(f,7,e.uaFullVersion);return f}).catch(function(){return Wg.clone()})}
;function Zg(a){this.G=J(a)}
x(Zg,K);function $g(a){this.G=J(a,4)}
x($g,K);function ch(a){this.G=J(a,35)}
x(ch,K);function dh(a){this.G=J(a,19)}
x(dh,K);dh.prototype.Ob=function(a){return Gf(this,2,a)};function eh(a){this.G=J(a,8)}
x(eh,K);var fh=Vf(eh);function gh(a){this.G=J(a)}
x(gh,K);var hh=new function(){this.ctor=gh;this.isRepeated=0;this.h=xf;this.defaultValue=void 0};function ih(a){L.call(this);var b=this;this.componentId="";this.j=[];this.X="";this.pageId=null;this.ga=this.T=-1;this.experimentIds=null;this.I=this.u=0;this.ia=1;this.timeoutMillis=0;this.logSource=a.logSource;this.Hb=a.Hb||function(){};
this.i=new jh(a.logSource,a.cb);this.network=a.network;this.xb=a.xb||null;this.bufferSize=1E3;this.A=a.hf||null;this.sessionIndex=a.sessionIndex||null;this.Fb=a.Fb||!1;this.logger=null;this.withCredentials=!a.Wc;this.cb=a.cb||!1;this.H=typeof URLSearchParams!=="undefined"&&!!(new URL(kh())).searchParams&&!!(new URL(kh())).searchParams.set;var c=Gf(new Zg,1,1);lh(this.i,c);this.o=new Qg(1E4);a=mh(this,a.Qc);this.h=new ug(this.o.getValue(),a);this.W=new ug(6E5,a);this.Fb||this.W.start();this.cb||(document.addEventListener("visibilitychange",
function(){document.visibilityState==="hidden"&&b.vc()}),document.addEventListener("pagehide",this.vc.bind(this)))}
x(ih,L);function mh(a,b){return a.H?b?function(){b().then(function(){a.flush()})}:function(){a.flush()}:function(){}}
p=ih.prototype;p.ba=function(){this.vc();this.h.stop();this.W.stop();L.prototype.ba.call(this)};
p.log=function(a){if(this.H){a=a.clone();var b=this.ia++;a=lf(a,21,xe(b));this.componentId&&Ff(a,26,this.componentId);if(Af(a)==null){var c=Date.now();b=a;c=Number.isFinite(c)?c.toString():"0";lf(b,1,xe(c))}ze(hf(a,15))==null&&lf(a,15,xe((new Date).getTimezoneOffset()*60));this.experimentIds&&(b=a,c=this.experimentIds.clone(),yf(b,tg,16,c));b=this.j.length-this.bufferSize+1;b>0&&(this.j.splice(0,b),this.u+=b);this.j.push(a);this.Fb||this.h.enabled||this.h.start()}};
p.flush=function(a,b){var c=this;if(this.j.length===0)a&&a();else{var d=Date.now();if(this.ga>d&&this.T<d)b&&b("throttled");else{this.network&&(typeof this.network.cc==="function"?nh(this.i,this.network.cc()):nh(this.i,0));var e=oh(this.i,this.j,this.u,this.I,this.xb);d={};var f=this.Hb();f&&(d.Authorization=f);this.A||(this.A=kh());try{var g=(new URL(this.A)).toString()}catch(k){g=(new URL(this.A,window.location.origin)).toString()}g=new URL(g);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,
g.searchParams.set("authuser",this.sessionIndex));this.pageId&&(Object.defineProperty(d,"X-Goog-PageId",{value:this.pageId}),g.searchParams.set("pageId",this.pageId));if(f&&this.X===f)b&&b("stale-auth-token");else{this.j=[];this.h.enabled&&this.h.stop();this.u=0;var h=e.serialize();d={url:g.toString(),body:h,Og:1,qd:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis};g=function(k){c.o.reset();c.h.setInterval(c.o.getValue());if(k){var l=null;try{var m=JSON.stringify(JSON.parse(k.replace(")]}'\n",
"")));l=fh(m)}catch(n){}l&&(k=Number,m="-1",m=m===void 0?"0":m,m=Bf(Af(l),m),k=k(m),k>0&&(c.T=Date.now(),c.ga=c.T+k),l=hh.ctor?hh.h(l,hh.ctor,175237375,!0):hh.h(l,175237375,null,!0),l=l===null?void 0:l)&&(l=nc(l,1,-1),l!==-1&&(c.o=new Qg(l<1?1:l),c.h.setInterval(c.o.getValue())))}a&&a();c.I=0};
h=function(k,l){var m=lc(e,ch,3);var n=ze(hf(e,14)),r=c.o;r.h=Math.min(3E5,r.h*2);r.i=Math.min(3E5,r.h+Math.round((Math.random()-.5)*.2*r.h));c.h.setInterval(c.o.getValue());k===401&&f&&(c.X=f);n&&(c.u+=n);l===void 0&&(l=c.isRetryable(k));l&&(c.j=m.concat(c.j),c.Fb||c.h.enabled||c.h.start());b&&b("net-send-failed",k);++c.I};
c.network&&c.network.send(d,g,h)}}}};
p.vc=function(){ph(this.i,!0);this.flush();ph(this.i,!1)};
p.isRetryable=function(a){return 500<=a&&a<600||a===401||a===0};
function kh(){return"https://play.google.com/log?format=json&hasfast=true"}
function jh(a,b){this.cb=b=b===void 0?!1:b;this.i=this.locale=null;this.h=new dh;Number.isInteger(a)&&this.h.Ob(a);b||(this.locale=document.documentElement.getAttribute("lang"));lh(this,new Zg)}
jh.prototype.Ob=function(a){this.h.Ob(a);return this};
function lh(a,b){yf(a.h,Zg,1,b);Ef(b)||Gf(b,1,1);a.cb||(b=qh(a),Df(b,5)||Ff(b,5,a.locale));a.i&&(b=qh(a),xf(b,Tg,9)||yf(b,Tg,9,a.i))}
function nh(a,b){nf(rh(a))&&(a=sh(a),Gf(a,1,b))}
function ph(a,b){nf(rh(a))&&(a=sh(a),lf(a,2,me(b)))}
function rh(a){return xf(a.h,Zg,1)}
function th(a){var b=b===void 0?Vg:b;var c=a.cb?void 0:window;c?Yg(c,b).then(function(d){a.i=d;d=qh(a);yf(d,Tg,9,a.i);return!0}).catch(function(){return!1}):Promise.resolve(!1)}
function qh(a){a=rh(a);var b=xf(a,pf,11);b||(b=new pf,yf(a,pf,11,b));return b}
function sh(a){a=qh(a);var b=xf(a,Rg,10);b||(b=new Rg,lf(b,2,me(!1)),yf(a,Rg,10,b));return b}
function oh(a,b,c,d,e){var f=0,g=0;c=c===void 0?0:c;f=f===void 0?0:f;g=g===void 0?0:g;d=d===void 0?0:d;if(nf(rh(a))){var h=sh(a);lf(h,3,qe(d))}nf(rh(a))&&(d=sh(a),lf(d,4,qe(f)));nf(rh(a))&&(f=sh(a),lf(f,5,qe(g)));a=a.h.clone();g=Date.now().toString();a=lf(a,4,xe(g));b=b.slice();b=zf(a,ch,3,b);e&&(a=new vg,e=lf(a,13,qe(e)),a=new wg,e=yf(a,vg,2,e),a=new $g,e=yf(a,wg,1,e),e=Gf(e,2,9),yf(b,$g,18,e));c&&lf(b,14,xe(c));return b}
;function uh(){this.Hd=typeof AbortController!=="undefined"}
uh.prototype.send=function(a,b,c){var d=this,e,f,g,h,k,l,m,n,r,t;return A(function(w){switch(w.h){case 1:return f=(e=d.Hd?new AbortController:void 0)?setTimeout(function(){e.abort()},a.timeoutMillis):void 0,ya(w,2,3),g=Object.assign({},{method:a.requestType,
headers:Object.assign({},a.qd)},a.body&&{body:a.body},a.withCredentials&&{credentials:"include"},{signal:a.timeoutMillis&&e?e.signal:null}),w.yield(fetch(a.url,g),5);case 5:h=w.i;if(h.status!==200){(k=c)==null||k(h.status);w.F(3);break}if((l=b)==null){w.F(7);break}return w.yield(h.text(),8);case 8:l(w.i);case 7:case 3:w.I=[w.j];w.o=0;w.D=0;clearTimeout(f);Aa(w);break;case 2:m=za(w);switch((n=m)==null?void 0:n.name){case "AbortError":(r=c)==null||r(408);break;default:(t=c)==null||t(400)}w.F(3)}})};
uh.prototype.cc=function(){return 4};function vh(a,b){L.call(this);this.logSource=a;this.sessionIndex=b;this.j="https://play.google.com/log?format=json&hasfast=true";this.h=null;this.o=!1;this.network=null;this.componentId="";this.pageId=this.i=this.xb=null}
x(vh,L);vh.prototype.Wc=function(){this.u=!0;return this};
function wh(a){a.network||(a.network=new uh);var b=new ih({logSource:a.logSource,Hb:a.Hb?a.Hb:pg,sessionIndex:a.sessionIndex,hf:a.j,cb:a.o,Fb:!1,Wc:a.u,Qc:a.Qc,network:a.network});sg(a,b);if(a.h){var c=a.h,d=qh(b.i);Ff(d,7,c)}a.componentId&&(b.componentId=a.componentId);a.xb&&(b.xb=a.xb);a.pageId&&(b.pageId=a.pageId);a.i&&((d=a.i)?(b.experimentIds||(b.experimentIds=new tg),c=b.experimentIds,d=d.serialize(),Ff(c,4,d)):b.experimentIds&&lf(b.experimentIds,4));th(b.i);a.network.Ob&&a.network.Ob(a.logSource);
a.network.Ue&&a.network.Ue(b);return b}
;function xh(a,b,c,d,e,f,g){a=a===void 0?-1:a;b=b===void 0?"":b;c=c===void 0?"":c;d=d===void 0?!1:d;e=e===void 0?"":e;L.call(this);this.logSource=a;this.componentId=b;f?b=f:(a=new vh(a,"0"),a.componentId=b,sg(this,a),c!==""&&(a.j=c),d&&(a.o=!0),e&&(a.h=e),g&&(a.network=g),b=wh(a));this.h=b}
x(xh,L);
xh.prototype.flush=function(a){var b=a||[];if(b.length){a=new dg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=new cg;f=Ff(f,1,e.i);var g=yh(e);f=rf(f,g,Ae);g=[];var h=[];for(var k=v(e.h.keys()),l=k.next();!l.done;l=k.next())h.push(l.value.split(","));for(k=0;k<h.length;k++){l=h[k];var m=e.o;for(var n=e.wc(l)||[],r=[],t=0;t<n.length;t++){var w=n[t],y=w&&w.h;w=new $f;switch(m){case 3:y=Number(y);Number.isFinite(y)&&uf(w,1,ag,xe(y));break;case 2:y=Number(y);if(y!=null&&typeof y!=="number")throw Error("Value of float/double field must be a number, found "+typeof y+
": "+y);uf(w,2,ag,y)}r.push(w)}m=r;for(n=0;n<m.length;n++){r=m[n];t=new bg;r=yf(t,$f,2,r);t=l;w=[];y=zh(e);for(var z=0;z<y.length;z++){var G=y[z],I=t[z],M=new Yf;switch(G){case 3:uf(M,1,Zf,Be(String(I)));break;case 2:G=Number(I);Number.isFinite(G)&&uf(M,2,Zf,qe(G));break;case 1:uf(M,3,Zf,me(I==="true"))}w.push(M)}zf(r,Yf,1,w);g.push(r)}}zf(f,bg,4,g);c.push(f);e.clear()}zf(a,cg,1,c);b=this.h;b.H&&(a instanceof ch?b.log(a):(c=new ch,a=a.serialize(),a=Ff(c,8,a),b.log(a)));this.h.flush()}};function Ah(a){this.h=a}
;function Bh(a,b,c){this.i=a;this.o=b;this.fields=c||[];this.h=new Map}
function zh(a){return a.fields.map(function(b){return b.fieldType})}
function yh(a){return a.fields.map(function(b){return b.fieldName})}
p=Bh.prototype;p.Id=function(a){var b=B.apply(1,arguments),c=this.wc(b);c?c.push(new Ah(a)):this.td(a,b)};
p.td=function(a){var b=this.Pc(B.apply(1,arguments));this.h.set(b,[new Ah(a)])};
p.wc=function(){var a=this.Pc(B.apply(0,arguments));return this.h.has(a)?this.h.get(a):void 0};
p.Zd=function(){var a=this.wc(B.apply(0,arguments));return a&&a.length?a[0]:void 0};
p.clear=function(){this.h.clear()};
p.Pc=function(){var a=B.apply(0,arguments);return a?a.join(","):"key"};function Ch(a,b){Bh.call(this,a,3,b)}
x(Ch,Bh);Ch.prototype.j=function(a){var b=B.apply(1,arguments),c=0,d=this.Zd(b);d&&(c=d.h);this.td(c+a,b)};function Dh(a,b){Bh.call(this,a,2,b)}
x(Dh,Bh);Dh.prototype.record=function(a){this.Id(a,B.apply(1,arguments))};function Eh(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Eh.prototype.stopPropagation=function(){this.j=!0};
Eh.prototype.preventDefault=function(){this.defaultPrevented=!0};function Fh(a,b){Eh.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
Za(Fh,Eh);
Fh.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;b=a.relatedTarget;b||(c=="mouseover"?b=a.fromElement:c=="mouseout"&&(b=a.toElement));this.relatedTarget=b;d?(this.clientX=d.clientX!==void 0?d.clientX:d.pageX,this.clientY=d.clientY!==void 0?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.clientX=a.clientX!==void 0?a.clientX:a.pageX,this.clientY=a.clientY!==
void 0?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||(c=="keypress"?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType=a.pointerType;this.state=a.state;this.i=a;a.defaultPrevented&&Fh.Ca.preventDefault.call(this)};
Fh.prototype.stopPropagation=function(){Fh.Ca.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Fh.prototype.preventDefault=function(){Fh.Ca.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Gh="closure_listenable_"+(Math.random()*1E6|0);var Hh=0;function Ih(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.dc=e;this.key=++Hh;this.Nb=this.Wb=!1}
function Jh(a){a.Nb=!0;a.listener=null;a.proxy=null;a.src=null;a.dc=null}
;function Kh(a){this.src=a;this.listeners={};this.h=0}
Kh.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Lh(a,b,d,e);g>-1?(b=a[g],c||(b.Wb=!1)):(b=new Ih(b,this.src,f,!!d,e),b.Wb=c,a.push(b));return b};
Kh.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Lh(e,b,c,d);return b>-1?(Jh(e[b]),Array.prototype.splice.call(e,b,1),e.length==0&&(delete this.listeners[a],this.h--),!0):!1};
function Mh(a,b){var c=b.type;c in a.listeners&&Pb(a.listeners[c],b)&&(Jh(b),a.listeners[c].length==0&&(delete a.listeners[c],a.h--))}
function Lh(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Nb&&f.listener==b&&f.capture==!!c&&f.dc==d)return e}return-1}
;var Nh="closure_lm_"+(Math.random()*1E6|0),Oh={},Ph=0;function Qh(a,b,c,d,e){if(d&&d.once)Rh(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Qh(a,b[f],c,d,e);else c=Sh(c),a&&a[Gh]?a.listen(b,c,Qa(d)?!!d.capture:!!d,e):Th(a,b,c,!1,d,e)}
function Th(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Qa(e)?!!e.capture:!!e,h=Uh(a);h||(a[Nh]=h=new Kh(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Vh();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Pg||(e=g),e===void 0&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Wh(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Ph++}}
function Vh(){function a(c){return b.call(a.src,a.listener,c)}
var b=Xh;return a}
function Rh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Rh(a,b[f],c,d,e);else c=Sh(c),a&&a[Gh]?a.h.add(String(b),c,!0,Qa(d)?!!d.capture:!!d,e):Th(a,b,c,!0,d,e)}
function Yh(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Yh(a,b[f],c,d,e);else(d=Qa(d)?!!d.capture:!!d,c=Sh(c),a&&a[Gh])?a.h.remove(String(b),c,d,e):a&&(a=Uh(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Lh(b,c,d,e)),(c=a>-1?b[a]:null)&&Zh(c))}
function Zh(a){if(typeof a!=="number"&&a&&!a.Nb){var b=a.src;if(b&&b[Gh])Mh(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Wh(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Ph--;(c=Uh(b))?(Mh(c,a),c.h==0&&(c.src=null,b[Nh]=null)):Jh(a)}}}
function Wh(a){return a in Oh?Oh[a]:Oh[a]="on"+a}
function Xh(a,b){if(a.Nb)a=!0;else{b=new Fh(b,this);var c=a.listener,d=a.dc||a.src;a.Wb&&Zh(a);a=c.call(d,b)}return a}
function Uh(a){a=a[Nh];return a instanceof Kh?a:null}
var $h="__closure_events_fn_"+(Math.random()*1E9>>>0);function Sh(a){if(typeof a==="function")return a;a[$h]||(a[$h]=function(b){return a.handleEvent(b)});
return a[$h]}
;function ai(){L.call(this);this.h=new Kh(this);this.Ka=this;this.ga=null}
Za(ai,L);ai.prototype[Gh]=!0;p=ai.prototype;p.addEventListener=function(a,b,c,d){Qh(this,a,b,c,d)};
p.removeEventListener=function(a,b,c,d){Yh(this,a,b,c,d)};
function bi(a,b){var c=a.ga;if(c){var d=[];for(var e=1;c;c=c.ga)d.push(c),++e}a=a.Ka;c=b.type||b;typeof b==="string"?b=new Eh(b,a):b instanceof Eh?b.target=b.target||a:(e=b,b=new Eh(c,a),Hg(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&f>=0;f--){var g=b.h=d[f];e=ci(g,c,!0,b)&&e}b.j||(g=b.h=a,e=ci(g,c,!0,b)&&e,b.j||(e=ci(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=ci(g,c,!1,b)&&e}
p.ba=function(){ai.Ca.ba.call(this);this.removeAllListeners();this.ga=null};
p.listen=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
p.removeAllListeners=function(a){if(this.h){var b=this.h;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,Jh(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function ci(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Nb&&g.capture==c){var h=g.listener,k=g.dc||g.src;g.Wb&&Mh(a.h,g);e=h.call(k,d)!==!1&&e}}return e&&!d.defaultPrevented}
;function di(a,b){this.j=a;this.o=b;this.i=0;this.h=null}
di.prototype.get=function(){if(this.i>0){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function ei(a,b){a.o(b);a.i<100&&(a.i++,b.next=a.h,a.h=b)}
;function fi(){}
function gi(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var hi;function ii(){var a=C.MessageChannel;typeof a==="undefined"&&typeof window!=="undefined"&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=Ng("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h=f.location.protocol=="file:"?"*":f.location.protocol+"//"+f.location.host;e=Wa(function(k){if((h=="*"||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if(typeof a!=="undefined"){var b=new a,c={},d=c;b.port1.onmessage=function(){if(c.next!==void 0){c=c.next;var e=c.Tc;c.Tc=null;e()}};
return function(e){d.next={Tc:e};d=d.next;b.port2.postMessage(0)}}return function(e){C.setTimeout(e,0)}}
;function ji(){this.i=this.h=null}
ji.prototype.add=function(a,b){var c=ki.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
ji.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var ki=new di(function(){return new li},function(a){return a.reset()});
function li(){this.next=this.scope=this.h=null}
li.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
li.prototype.reset=function(){this.next=this.scope=this.h=null};var mi,ni=!1,oi=new ji;function pi(a,b){mi||qi();ni||(mi(),ni=!0);oi.add(a,b)}
function qi(){if(C.Promise&&C.Promise.resolve){var a=C.Promise.resolve(void 0);mi=function(){a.then(ri)}}else mi=function(){var b=ri;
typeof C.setImmediate!=="function"||C.Window&&C.Window.prototype&&C.Window.prototype.setImmediate==C.setImmediate?(hi||(hi=ii()),hi(b)):C.setImmediate(b)}}
function ri(){for(var a;a=oi.remove();){try{a.h.call(a.scope)}catch(b){Dc(b)}ei(ki,a)}ni=!1}
;function si(a){this.h=0;this.A=void 0;this.o=this.i=this.j=null;this.D=this.u=!1;if(a!=fi)try{var b=this;a.call(void 0,function(c){ti(b,2,c)},function(c){ti(b,3,c)})}catch(c){ti(this,3,c)}}
function ui(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
ui.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var vi=new di(function(){return new ui},function(a){a.reset()});
function wi(a,b,c){var d=vi.get();d.i=a;d.h=b;d.context=c;return d}
function xi(a){return new si(function(b,c){c(a)})}
si.prototype.then=function(a,b,c){return yi(this,typeof a==="function"?a:null,typeof b==="function"?b:null,c)};
si.prototype.$goog_Thenable=!0;p=si.prototype;p.oc=function(a,b){return yi(this,null,a,b)};
p.catch=si.prototype.oc;p.cancel=function(a){if(this.h==0){var b=new zi(a);pi(function(){Ai(this,b)},this)}};
function Ai(a,b){if(a.h==0)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&d>1)));g=g.next)e||(f=g);e&&(c.h==0&&d==1?Ai(c,b):(f?(d=f,d.next==c.o&&(c.o=d),d.next=d.next.next):Bi(c),Ci(c,e,3,b)))}a.j=null}else ti(a,3,b)}
function Di(a,b){a.i||a.h!=2&&a.h!=3||Ei(a);a.o?a.o.next=b:a.i=b;a.o=b}
function yi(a,b,c,d){var e=wi(null,null,null);e.child=new si(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.h=c?function(h){try{var k=c.call(d,h);k===void 0&&h instanceof zi?g(h):f(k)}catch(l){g(l)}}:g});
e.child.j=a;Di(a,e);return e.child}
p.ff=function(a){this.h=0;ti(this,2,a)};
p.gf=function(a){this.h=0;ti(this,3,a)};
function ti(a,b,c){if(a.h==0){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.ff,f=a.gf;if(d instanceof si){Di(d,wi(e||fi,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Qa(d))try{var k=d.then;if(typeof k==="function"){Fi(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.A=c,a.h=b,a.j=null,Ei(a),b!=3||c instanceof zi||Gi(a,c))}}
function Fi(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Ei(a){a.u||(a.u=!0,pi(a.Ud,a))}
function Bi(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.o=null);return b}
p.Ud=function(){for(var a;a=Bi(this);)Ci(this,a,this.h,this.A);this.u=!1};
function Ci(a,b,c,d){if(c==3&&b.h&&!b.j)for(;a&&a.D;a=a.j)a.D=!1;if(b.child)b.child.j=null,Hi(b,c,d);else try{b.j?b.i.call(b.context):Hi(b,c,d)}catch(e){Ii.call(null,e)}ei(vi,b)}
function Hi(a,b,c){b==2?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function Gi(a,b){a.D=!0;pi(function(){a.D&&Ii.call(null,b)})}
var Ii=Dc;function zi(a){$a.call(this,a)}
Za(zi,$a);zi.prototype.name="cancel";function Ji(a,b){ai.call(this);this.j=a||1;this.i=b||C;this.o=Wa(this.cf,this);this.u=Ya()}
Za(Ji,ai);p=Ji.prototype;p.enabled=!1;p.Fa=null;p.setInterval=function(a){this.j=a;this.Fa&&this.enabled?(this.stop(),this.start()):this.Fa&&this.stop()};
p.cf=function(){if(this.enabled){var a=Ya()-this.u;a>0&&a<this.j*.8?this.Fa=this.i.setTimeout(this.o,this.j-a):(this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null),bi(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
p.start=function(){this.enabled=!0;this.Fa||(this.Fa=this.i.setTimeout(this.o,this.j),this.u=Ya())};
p.stop=function(){this.enabled=!1;this.Fa&&(this.i.clearTimeout(this.Fa),this.Fa=null)};
p.ba=function(){Ji.Ca.ba.call(this);this.stop();delete this.i};
function Ki(a,b,c){if(typeof a==="function")c&&(a=Wa(a,c));else if(a&&typeof a.handleEvent=="function")a=Wa(a.handleEvent,a);else throw Error("Invalid listener argument");return Number(b)>2147483647?-1:C.setTimeout(a,b||0)}
;function Li(a){L.call(this);this.H=a;this.j=0;this.o=100;this.u=!1;this.i=new Map;this.A=new Set;this.flushInterval=3E4;this.h=new Ji(this.flushInterval);this.h.listen("tick",this.Ab,!1,this);sg(this,this.h)}
x(Li,L);p=Li.prototype;p.sendIsolatedPayload=function(a){this.u=a;this.o=1};
function Mi(a){a.h.enabled||a.h.start();a.j++;a.j>=a.o&&a.Ab()}
p.Ab=function(){var a=this.i.values();a=[].concat(ja(a)).filter(function(b){return b.h.size});
a.length&&this.H.flush(a,this.u);Ni(a);this.j=0;this.h.enabled&&this.h.stop()};
p.Ra=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Ch(a,b))};
p.Cb=function(a){var b=B.apply(1,arguments);this.i.has(a)||this.i.set(a,new Dh(a,b))};
function Oi(a,b){return a.A.has(b)?void 0:a.i.get(b)}
p.zb=function(a){this.Gd(a,1,B.apply(1,arguments))};
p.Gd=function(a,b){var c=B.apply(2,arguments),d=Oi(this,a);d&&d instanceof Ch&&(d.j(b,c),Mi(this))};
p.record=function(a,b){var c=B.apply(2,arguments),d=Oi(this,a);d&&d instanceof Dh&&(d.record(b,c),Mi(this))};
function Ni(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Pi(){}
Pi.prototype.serialize=function(a){var b=[];Qi(this,a,b);return b.join("")};
function Qi(a,b,c){if(b==null)c.push("null");else{if(typeof b=="object"){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Qi(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],typeof f!="function"&&(c.push(e),Ri(d,c),c.push(":"),Qi(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ri(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Si={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Ti=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ri(a,b){b.push('"',a.replace(Ti,function(c){var d=Si[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Si[c]=d);return d}),'"')}
;function Ui(){}
Ui.prototype.h=null;Ui.prototype.getOptions=function(){var a;(a=this.h)||(a=this.h={});return a};var Vi;function Wi(){}
Za(Wi,Ui);Vi=new Wi;function Xi(a){ai.call(this);this.headers=new Map;this.ya=a||null;this.i=!1;this.I=this.U=null;this.o=this.X="";this.j=this.W=this.u=this.T=!1;this.H=0;this.A=null;this.pa="";this.ia=!1}
Za(Xi,ai);var Yi=/^https?$/i,Zi=["POST","PUT"],$i=[];function aj(a,b,c,d,e,f,g){var h=new Xi;$i.push(h);b&&h.listen("complete",b);h.h.add("ready",h.Nd,!0,void 0,void 0);f&&(h.H=Math.max(0,f));g&&(h.ia=g);h.send(a,c,d,e)}
p=Xi.prototype;p.Nd=function(){this.dispose();Pb($i,this)};
p.send=function(a,b,c,d){if(this.U)throw Error("[goog.net.XhrIo] Object is active with another request="+this.X+"; newUri="+a);b=b?b.toUpperCase():"GET";this.X=a;this.o="";this.T=!1;this.i=!0;this.U=new XMLHttpRequest;this.I=this.ya?this.ya.getOptions():Vi.getOptions();this.U.onreadystatechange=Wa(this.ld,this);try{this.getStatus(),this.W=!0,this.U.open(b,String(a),!0),this.W=!1}catch(g){this.getStatus();bj(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if(typeof d.keys==="function"&&typeof d.get==="function"){e=v(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=C.FormData&&a instanceof C.FormData;!(Jb(Zi,b)>=0)||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=v(c);for(d=b.next();!d.done;d=b.next())c=v(d.value),d=c.next().value,c=c.next().value,this.U.setRequestHeader(d,c);this.pa&&(this.U.responseType=this.pa);"withCredentials"in this.U&&this.U.withCredentials!==this.ia&&(this.U.withCredentials=this.ia);try{cj(this),this.H>0&&(this.getStatus(),this.A=Ki(this.ef,this.H,this)),this.getStatus(),this.u=!0,this.U.send(a),this.u=
!1}catch(g){this.getStatus(),bj(this,g)}};
p.ef=function(){typeof Ja!="undefined"&&this.U&&(this.o="Timed out after "+this.H+"ms, aborting",this.getStatus(),bi(this,"timeout"),this.abort(8))};
function bj(a,b){a.i=!1;a.U&&(a.j=!0,a.U.abort(),a.j=!1);a.o=b;dj(a);ej(a)}
function dj(a){a.T||(a.T=!0,bi(a,"complete"),bi(a,"error"))}
p.abort=function(){this.U&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.U.abort(),this.j=!1,bi(this,"complete"),bi(this,"abort"),ej(this))};
p.ba=function(){this.U&&(this.i&&(this.i=!1,this.j=!0,this.U.abort(),this.j=!1),ej(this,!0));Xi.Ca.ba.call(this)};
p.ld=function(){this.ea||(this.W||this.u||this.j?fj(this):this.xe())};
p.xe=function(){fj(this)};
function fj(a){if(a.i&&typeof Ja!="undefined")if(a.I[1]&&gj(a)==4&&a.getStatus()==2)a.getStatus();else if(a.u&&gj(a)==4)Ki(a.ld,0,a);else if(bi(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(hj(a))bi(a,"complete"),bi(a,"success");else{try{var b=gj(a)>2?a.U.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";dj(a)}}finally{ej(a)}}}
function ej(a,b){if(a.U){cj(a);var c=a.U,d=a.I[0]?function(){}:null;
a.U=null;a.I=null;b||bi(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function cj(a){a.A&&(C.clearTimeout(a.A),a.A=null)}
p.isActive=function(){return!!this.U};
p.isComplete=function(){return gj(this)==4};
function hj(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=b===0)a=Zb(1,String(a.X)),!a&&C.self&&C.self.location&&(a=C.self.location.protocol.slice(0,-1)),b=!Yi.test(a?a.toLowerCase():"");c=b}return c}
function gj(a){return a.U?a.U.readyState:0}
p.getStatus=function(){try{return gj(this)>2?this.U.status:-1}catch(a){return-1}};
p.getLastError=function(){return typeof this.o==="string"?this.o:String(this.o)};function ij(){}
ij.prototype.send=function(a,b,c){b=b===void 0?function(){}:b;
c=c===void 0?function(){}:c;
aj(a.url,function(d){d=d.target;if(hj(d)){try{var e=d.U?d.U.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.qd,a.timeoutMillis,a.withCredentials)};
ij.prototype.cc=function(){return 1};var jj={Aa:"_",pc:"",Ta:[],pe:0};function kj(a,b,c){this.logger=a;this.event=b;if(c===void 0||c)this.h=lj()}
kj.prototype.start=function(){this.h=lj()};
kj.prototype.done=function(){this.h!=null&&this.logger.Kb(this.event,lj()-this.h)};
function mj(){L.apply(this,arguments)}
x(mj,L);function nj(a,b){var c=lj();b=b();a.Kb("n",lj()-c);return b}
function oj(){mj.apply(this,arguments)}
x(oj,mj);p=oj.prototype;p.hd=function(){};
p.Ac=function(){};
p.Kb=function(){};
p.Ha=function(){};
p.Ga=function(){};
p.yd=function(){};
function pj(a,b,c){c=c===void 0?[]:c;mj.call(this);this.T=b;this.i=c;this.u=new Map;this.j=new Map;this.Ta=[];this.A=void 0;this.I=!1;b=Object.assign({},jj,a);this.Aa=b.Aa;this.pc=b.pc;this.H=b.pe;this.Ta=b.Ta;var d=new Wf,e;if((e=this.T)==null?0:Cf(e)){var f;this.Ta=(f=b.Ta)==null?void 0:f.sort(function(g,h){return g-h});
this.i=c.sort(function(g,h){return g-h});
Xf(d,this.Ta.concat(this.i))}else Xf(d,a.Ta);qj(this,d);this.u.set("h",1);this.u.set("u",2);this.u.set("k",3);this.j.set(25,1);this.j.set(26,2);this.j.set(27,3);this.j.set(28,4)}
x(pj,mj);p=pj.prototype;p.yd=function(a){var b;(b=this.T)!=null&&Cf(b)&&(a=a.sort(function(c,d){return c-d}),this.i!==a&&(this.i=a,a=Xf(new Wf,this.Ta.concat(this.i)),qj(this,a)))};
function qj(a,b){var c=new vh(1828,"0");c.h="29";c.network=new ij;c.i=b;a.h&&(a.Ga(),a.h.dispose());a.o&&a.o.dispose();a.o=new xh(1828,"","",!1,"",wh(c));a.h=new Li(a.o);a.h.o=1E5;b=a.h;b.flushInterval=3E4;b.h.setInterval(3E4);a.ya=new sc(a.h);a.Ka=new vc(a.h);a.Ya=new wc(a.h);a.pa=new rc(a.h);a.W=new tc(a.h);a.X=new uc(a.h);a.errorCount=new zc(a.h);a.ga=new yc(a.h);new xc(a.h);new Ac(a.h);new Bc(a.h);new Cc(a.h);a.ia=new qc(a.h);sg(a,a.o);sg(a,a.h)}
p.hd=function(){var a;(a=this.ia)!=null&&a.h.zb("/client_streamz/bg/fic",this.Aa)};
p.Ac=function(){var a;(a=this.Ka)!=null&&a.h.zb("/client_streamz/bg/fsc","",this.Aa)};
p.Kb=function(a,b){if(a==="t"){var c;(c=this.ya)==null||c.record(b,"",this.Aa)}else if(a==="n"){var d;(d=this.Ya)==null||d.record(b,"",this.Aa)}else if(a==="h"||a==="u"||a==="k"){if(a=this.u.get(a)){var e;(e=this.W)!=null&&e.h.zb("/client_streamz/bg/fcc",a,this.Aa);var f;(f=this.X)==null||f.record(b,a,this.Aa)}}else{var g;(g=this.ga)==null||g.record(b,a,"",this.pc,this.Aa)}};
p.Ha=function(a){var b=this.j.get(a);if(b){var c;(c=this.pa)!=null&&c.h.zb("/client_streamz/bg/fiec","",this.Aa,b)}else{var d;(d=this.errorCount)!=null&&d.h.zb("/client_streamz/bg/cec",a,"",this.pc,this.Aa)}};
p.Ga=function(){var a=this;if(!this.H){var b;(b=this.h)==null||b.Ab()}else if(!this.I)if(b=lj(),this.A===void 0){this.A=b;var c;(c=this.h)==null||c.Ab()}else if(c=b-this.A,c>=this.H){this.A=b;var d;(d=this.h)==null||d.Ab()}else this.I=!0,setTimeout(function(){a.ea||(a.I=!1,a.Ga())},this.H-c)};
function lj(){var a,b,c;return(c=(a=globalThis.performance)==null?void 0:(b=a.now)==null?void 0:b.call(a))!=null?c:Date.now()}
;function mc(a){this.G=J(a)}
x(mc,K);function rj(a){this.G=J(a)}
x(rj,K);var sj=Vf(rj);function tj(a){this.G=J(a,0,"bfkj")}
x(tj,K);var uj=function(a){return Qd(function(b){return b instanceof a&&!(Bd(b.G)&2)})}(tj);function vj(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function wj(a){function b(z,G,I,M){Promise.resolve().then(function(){n.done();d.V.Ga();m.resolve({Kd:z,Xe:G,eh:I,Rg:M})})}
function c(z,G,I,M){if(!d.V.ea){var O="k";G?O="h":I&&(O="u");O!=="k"?M!==0&&d.V.Kb(O,z):d.j<=0?(d.V.Kb(O,z),d.j=Math.floor(Math.random()*200)):d.j--}}
L.call(this);var d=this;this.j=Math.floor(Math.random()*200);this.i=[];if("challenge"in a&&uj(a.challenge)){var e=Df(a.challenge,4);var f=Df(a.challenge,5);Df(a.challenge,7).length?this.h=sj(Df(a.challenge,7)):this.h=xf(a.challenge,rj,6)}else e=a.program,f=a.be;var g=new L;this.addOnDisposeCallback(function(){var z,G,I;return A(function(M){if(M.h==1)return M.yield(d.o,2);if(M.h!=3)return z=M.i,G=z.Xe,M.yield(Promise.all(d.i),3);d.i=[];d.V.Ga();(I=G)==null||I();g.dispose();M.h=0})});
if(a.De!==!1)if(a.V){this.V=a.V;var h;((h=this.h)==null?0:Cf(h))&&this.V.yd(kc(this.h))}else{h=[];var k;if((k=this.h)==null?0:Cf(k))h=kc(this.h);var l;sg(g,this.V=new pj((l=a.ue)!=null?l:jj,this.h,h))}else sg(g,this.V=new oj);var m=new vj;this.o=m.promise;var n=new kj(this.V,"t",!0);this.V.hd();if(!C[f])throw this.V.Ha(25),this.V.Ga(),Error("EGOU");if(!C[f].a)throw this.V.Ha(26),this.V.Ga(),Error("ELIU");try{var r=C[f].a;f=[[],[]];var t;if((t=this.h)==null?0:Cf(t)){var w=kc(this.h);for(t=0;t<w.length;t++)f[0].push(w[t]),
f[1].push(1);var y=oc(this.h);for(w=0;w<y.length;w++)f[0].push(y[w]),f[1].push(0)}this.u=v(r(e,b,!0,a.oh,c,f)).next().value;this.We=m.promise.then(function(){})}catch(z){throw this.V.Ha(28),this.V.Ga(),z;
}}
x(wj,L);wj.prototype.snapshot=function(a){var b=this;if(this.ea)throw Error("Already disposed");var c=new vj;this.i.push(c.promise);this.V.Ac();return this.o.then(function(d){var e=d.Kd;return new Promise(function(f){var g=new kj(b.V,"n");e(function(h){g.done();b.V.Ga();f(h)},[a.Vc,
a.Ye,a.kf,a.Ze])})}).finally(function(){return void c.resolve()})};
wj.prototype.vd=function(a){var b=this;if(this.ea)throw Error("Already disposed");this.V.Ac();var c=nj(this.V,function(){return b.u([a.Vc,a.Ye,a.kf,a.Ze])});
this.V.Ga();return c};
wj.prototype.getLogger=function(){return this.V};var xj=window;function yj(a){var b=zj;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Aj(){var a=[];yj(function(b){a.push(b)});
return a}
var zj={lf:"allow-forms",mf:"allow-modals",nf:"allow-orientation-lock",pf:"allow-pointer-lock",qf:"allow-popups",rf:"allow-popups-to-escape-sandbox",sf:"allow-presentation",tf:"allow-same-origin",uf:"allow-scripts",vf:"allow-top-navigation",wf:"allow-top-navigation-by-user-activation"},Bj=gi(function(){return Aj()});
function Cj(){var a=Dj(),b={};Kb(Bj(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Dj(){var a=a===void 0?document:a;return a.createElement("iframe")}
;function Ej(a){typeof a=="number"&&(a=Math.round(a)+"px");return a}
;var Fj=(new Date).getTime();function Gj(a){ai.call(this);var b=this;this.A=this.j=0;this.Ea=a!=null?a:{qa:function(e,f){return setTimeout(e,f)},
ra:function(e){clearTimeout(e)}};
var c,d;this.i=(d=(c=window.navigator)==null?void 0:c.onLine)!=null?d:!0;this.o=function(){return A(function(e){return e.yield(Hj(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.A||Ij(this)}
x(Gj,ai);function Jj(){var a=Kj;Gj.h||(Gj.h=new Gj(a));return Gj.h}
Gj.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Ea.ra(this.A);delete Gj.h};
Gj.prototype.wa=function(){return this.i};
function Ij(a){a.A=a.Ea.qa(function(){var b;return A(function(c){if(c.h==1)return a.i?((b=window.navigator)==null?0:b.onLine)?c.F(3):c.yield(Hj(a),3):c.yield(Hj(a),3);Ij(a);c.h=0})},3E4)}
function Hj(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f,g;return A(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=(e=d)==null?void 0:e.signal,g=!1,ya(h,2,3),d&&(a.j=a.Ea.qa(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:h.I=[h.j];h.o=0;h.D=0;a.u=void 0;a.j&&(a.Ea.ra(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?bi(a,"networkstatus-online"):bi(a,"networkstatus-offline"));c(g);Aa(h);break;case 2:za(h),g=!1,h.F(3)}})})}
;function Lj(){this.data=[];this.h=-1}
Lj.prototype.set=function(a,b){b=b===void 0?!0:b;0<=a&&a<52&&Number.isInteger(a)&&this.data[a]!==b&&(this.data[a]=b,this.h=-1)};
Lj.prototype.get=function(a){return!!this.data[a]};
function Mj(a){a.h===-1&&(a.h=a.data.reduce(function(b,c,d){return b+(c?Math.pow(2,d):0)},0));
return a.h}
;function Nj(){this.blockSize=-1}
;function Oj(){this.blockSize=-1;this.blockSize=64;this.h=[];this.D=[];this.u=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.o=this.i=0;this.reset()}
Za(Oj,Nj);Oj.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.o=this.i=0};
function Pj(a,b,c){c||(c=0);var d=a.u;if(typeof b==="string")for(var e=0;e<16;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;e<16;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;e<80;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;e<80;e++){if(e<40)if(e<20){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else e<60?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
Oj.prototype.update=function(a,b){if(a!=null){b===void 0&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.D,f=this.i;d<b;){if(f==0)for(;d<=c;)Pj(this,a,d),d+=this.blockSize;if(typeof a==="string")for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Pj(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Pj(this,e);f=0;break}}this.i=f;this.o+=b}};
Oj.prototype.digest=function(){var a=[],b=this.o*8;this.i<56?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;c>=56;c--)this.D[c]=b&255,b/=256;Pj(this,this.D);for(c=b=0;c<5;c++)for(var d=24;d>=0;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Qj(a){return typeof a.className=="string"?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Rj(a,b){typeof a.className=="string"?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Sj(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Qj(a).match(/\S+/g)||[],b=Jb(a,b)>=0);return b}
function Tj(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Sj(a,"inverted-hdpi")&&Rj(a,Array.prototype.filter.call(a.classList?a.classList:Qj(a).match(/\S+/g)||[],function(b){return b!="inverted-hdpi"}).join(" "))}
;function Uj(){}
Uj.prototype.next=function(){return Vj};
var Vj={done:!0,value:void 0};Uj.prototype.lb=function(){return this};function Wj(a){if(a instanceof Xj||a instanceof Yj||a instanceof Zj)return a;if(typeof a.next=="function")return new Xj(function(){return a});
if(typeof a[Symbol.iterator]=="function")return new Xj(function(){return a[Symbol.iterator]()});
if(typeof a.lb=="function")return new Xj(function(){return a.lb()});
throw Error("Not an iterator or iterable.");}
function Xj(a){this.h=a}
Xj.prototype.lb=function(){return new Yj(this.h())};
Xj.prototype[Symbol.iterator]=function(){return new Zj(this.h())};
Xj.prototype.i=function(){return new Zj(this.h())};
function Yj(a){this.h=a}
x(Yj,Uj);Yj.prototype.next=function(){return this.h.next()};
Yj.prototype[Symbol.iterator]=function(){return new Zj(this.h)};
Yj.prototype.i=function(){return new Zj(this.h)};
function Zj(a){Xj.call(this,function(){return a});
this.j=a}
x(Zj,Xj);Zj.prototype.next=function(){return this.j.next()};function N(a){L.call(this);this.u=1;this.j=[];this.o=0;this.h=[];this.i={};this.A=!!a}
Za(N,L);p=N.prototype;p.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
p.unsubscribe=function(a,b,c){if(a=this.i[a]){var d=this.h;if(a=a.find(function(e){return d[e+1]==b&&d[e+2]==c}))return this.Rb(a)}return!1};
p.Rb=function(a){var b=this.h[a];if(b){var c=this.i[b];this.o!=0?(this.j.push(a),this.h[a+1]=function(){}):(c&&Pb(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
p.kb=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];ak(this.h[g+1],this.h[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.ea;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.o--,this.j.length>0&&this.o==0)for(;c=this.j.pop();)this.Rb(c)}}return e!=0}return!1};
function ak(a,b,c){pi(function(){a.apply(b,c)})}
p.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.Rb,this),delete this.i[a])}else this.h.length=0,this.i={}};
p.ba=function(){N.Ca.ba.call(this);this.clear();this.j.length=0};function bk(a){this.h=a}
bk.prototype.set=function(a,b){b===void 0?this.h.remove(a):this.h.set(a,(new Pi).serialize(b))};
bk.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(b!==null)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
bk.prototype.remove=function(a){this.h.remove(a)};function ck(a){this.h=a}
Za(ck,bk);function dk(a){this.data=a}
function ek(a){return a===void 0||a instanceof dk?a:new dk(a)}
ck.prototype.set=function(a,b){ck.Ca.set.call(this,a,ek(b))};
ck.prototype.i=function(a){a=ck.Ca.get.call(this,a);if(a===void 0||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
ck.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,a===void 0)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function fk(a){this.h=a}
Za(fk,ck);fk.prototype.set=function(a,b,c){if(b=ek(b)){if(c){if(c<Ya()){fk.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Ya()}fk.Ca.set.call(this,a,b)};
fk.prototype.i=function(a){var b=fk.Ca.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Ya()||c&&c>Ya())fk.prototype.remove.call(this,a);else return b}};function gk(){}
;function hk(){}
Za(hk,gk);hk.prototype[Symbol.iterator]=function(){return Wj(this.lb(!0)).i()};
hk.prototype.clear=function(){var a=Array.from(this);a=v(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ik(a){this.h=a;this.i=null}
Za(ik,hk);p=ik.prototype;p.isAvailable=function(){var a=this.h;if(a)try{a.setItem("__sak","1");a.removeItem("__sak");var b=!0}catch(c){b=c instanceof DOMException&&(c.name==="QuotaExceededError"||c.code===22||c.code===1014||c.name==="NS_ERROR_DOM_QUOTA_REACHED")&&a&&a.length!==0}else b=!1;return this.i=b};
p.set=function(a,b){jk(this);try{this.h.setItem(a,b)}catch(c){if(this.h.length==0)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
p.get=function(a){jk(this);a=this.h.getItem(a);if(typeof a!=="string"&&a!==null)throw"Storage mechanism: Invalid value was encountered";return a};
p.remove=function(a){jk(this);this.h.removeItem(a)};
p.lb=function(a){jk(this);var b=0,c=this.h,d=new Uj;d.next=function(){if(b>=c.length)return Vj;var e=c.key(b++);if(a)return{value:e,done:!1};e=c.getItem(e);if(typeof e!=="string")throw"Storage mechanism: Invalid value was encountered";return{value:e,done:!1}};
return d};
p.clear=function(){jk(this);this.h.clear()};
p.key=function(a){jk(this);return this.h.key(a)};
function jk(a){if(a.h==null)throw Error("Storage mechanism: Storage unavailable");var b;((b=a.i)!=null?b:a.isAvailable())||Dc(Error("Storage mechanism: Storage unavailable"))}
;function kk(){var a=null;try{a=C.localStorage||null}catch(b){}ik.call(this,a)}
Za(kk,ik);function lk(a,b){this.i=a;this.h=b+"::"}
Za(lk,hk);lk.prototype.set=function(a,b){this.i.set(this.h+a,b)};
lk.prototype.get=function(a){return this.i.get(this.h+a)};
lk.prototype.remove=function(a){this.i.remove(this.h+a)};
lk.prototype.lb=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Uj;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return{value:a?e.slice(c.h.length):c.i.get(e),done:!1}};
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
var P={},mk=typeof Uint8Array!=="undefined"&&typeof Uint16Array!=="undefined"&&typeof Int32Array!=="undefined";P.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if(typeof c!=="object")throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
P.Lc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var nk={mb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
Yc:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},ok={mb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
Yc:function(a){return[].concat.apply([],a)}};
P.Ve=function(){mk?(P.jb=Uint8Array,P.Ja=Uint16Array,P.Fd=Int32Array,P.assign(P,nk)):(P.jb=Array,P.Ja=Array,P.Fd=Array,P.assign(P,ok))};
P.Ve();var pk=!0;try{new Uint8Array(1)}catch(a){pk=!1}
function qk(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if((f&64512)===55296&&b+1<d){var g=a.charCodeAt(b+1);(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=f<128?1:f<2048?2:f<65536?3:4}var h=new P.jb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),(f&64512)===55296&&b+1<d&&(g=a.charCodeAt(b+1),(g&64512)===56320&&(f=65536+(f-55296<<10)+(g-56320),b++)),f<128?h[c++]=f:(f<2048?h[c++]=192|f>>>6:(f<65536?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var rk={};rk=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;c!==0;){f=c>2E3?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var sk={},tk,uk=[],vk=0;vk<256;vk++){tk=vk;for(var wk=0;wk<8;wk++)tk=tk&1?3988292384^tk>>>1:tk>>>1;uk[vk]=tk}sk=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^uk[(a^b[d])&255];return a^-1};var xk={};xk={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function yk(a){for(var b=a.length;--b>=0;)a[b]=0}
var zk=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],Ak=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],Bk=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],Ck=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],Dk=Array(576);yk(Dk);var Ek=Array(60);yk(Ek);var Fk=Array(512);yk(Fk);var Gk=Array(256);yk(Gk);var Hk=Array(29);yk(Hk);var Ik=Array(30);yk(Ik);function Jk(a,b,c,d,e){this.wd=a;this.Xd=b;this.Wd=c;this.Rd=d;this.te=e;this.cd=a&&a.length}
var Kk,Lk,Mk;function Nk(a,b){this.Xc=a;this.ub=0;this.Wa=b}
function Ok(a,b){a.aa[a.pending++]=b&255;a.aa[a.pending++]=b>>>8&255}
function Pk(a,b,c){a.ja>16-c?(a.oa|=b<<a.ja&65535,Ok(a,a.oa),a.oa=b>>16-a.ja,a.ja+=c-16):(a.oa|=b<<a.ja&65535,a.ja+=c)}
function Qk(a,b,c){Pk(a,c[b*2],c[b*2+1])}
function Rk(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(--b>0);return c>>>1}
function Sk(a,b,c){var d=Array(16),e=0,f;for(f=1;f<=15;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[c*2+1],e!==0&&(a[c*2]=Rk(d[e]++,e))}
function Tk(a){var b;for(b=0;b<286;b++)a.sa[b*2]=0;for(b=0;b<30;b++)a.ab[b*2]=0;for(b=0;b<19;b++)a.ka[b*2]=0;a.sa[512]=1;a.Qa=a.yb=0;a.za=a.matches=0}
function Uk(a){a.ja>8?Ok(a,a.oa):a.ja>0&&(a.aa[a.pending++]=a.oa);a.oa=0;a.ja=0}
function Vk(a,b,c){Uk(a);Ok(a,c);Ok(a,~c);P.mb(a.aa,a.window,b,c,a.pending);a.pending+=c}
function Wk(a,b,c,d){var e=b*2,f=c*2;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Xk(a,b,c){for(var d=a.da[c],e=c<<1;e<=a.Oa;){e<a.Oa&&Wk(b,a.da[e+1],a.da[e],a.depth)&&e++;if(Wk(b,d,a.da[e],a.depth))break;a.da[c]=a.da[e];c=e;e<<=1}a.da[c]=d}
function Yk(a,b,c){var d=0;if(a.za!==0){do{var e=a.aa[a.Eb+d*2]<<8|a.aa[a.Eb+d*2+1];var f=a.aa[a.zc+d];d++;if(e===0)Qk(a,f,b);else{var g=Gk[f];Qk(a,g+256+1,b);var h=zk[g];h!==0&&(f-=Hk[g],Pk(a,f,h));e--;g=e<256?Fk[e]:Fk[256+(e>>>7)];Qk(a,g,c);h=Ak[g];h!==0&&(e-=Ik[g],Pk(a,e,h))}}while(d<a.za)}Qk(a,256,b)}
function Zk(a,b){var c=b.Xc,d=b.Wa.wd,e=b.Wa.cd,f=b.Wa.Rd,g,h=-1;a.Oa=0;a.pb=573;for(g=0;g<f;g++)c[g*2]!==0?(a.da[++a.Oa]=h=g,a.depth[g]=0):c[g*2+1]=0;for(;a.Oa<2;){var k=a.da[++a.Oa]=h<2?++h:0;c[k*2]=1;a.depth[k]=0;a.Qa--;e&&(a.yb-=d[k*2+1])}b.ub=h;for(g=a.Oa>>1;g>=1;g--)Xk(a,c,g);k=f;do g=a.da[1],a.da[1]=a.da[a.Oa--],Xk(a,c,1),d=a.da[1],a.da[--a.pb]=g,a.da[--a.pb]=d,c[k*2]=c[g*2]+c[d*2],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[g*2+1]=c[d*2+1]=k,a.da[1]=k++,Xk(a,c,1);while(a.Oa>=
2);a.da[--a.pb]=a.da[1];g=b.Xc;k=b.ub;d=b.Wa.wd;e=b.Wa.cd;f=b.Wa.Xd;var l=b.Wa.Wd,m=b.Wa.te,n,r=0;for(n=0;n<=15;n++)a.La[n]=0;g[a.da[a.pb]*2+1]=0;for(b=a.pb+1;b<573;b++){var t=a.da[b];n=g[g[t*2+1]*2+1]+1;n>m&&(n=m,r++);g[t*2+1]=n;if(!(t>k)){a.La[n]++;var w=0;t>=l&&(w=f[t-l]);var y=g[t*2];a.Qa+=y*(n+w);e&&(a.yb+=y*(d[t*2+1]+w))}}if(r!==0){do{for(n=m-1;a.La[n]===0;)n--;a.La[n]--;a.La[n+1]+=2;a.La[m]--;r-=2}while(r>0);for(n=m;n!==0;n--)for(t=a.La[n];t!==0;)d=a.da[--b],d>k||(g[d*2+1]!==n&&(a.Qa+=(n-g[d*
2+1])*g[d*2],g[d*2+1]=n),t--)}Sk(c,h,a.La)}
function $k(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);b[(c+1)*2+1]=65535;for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];++g<h&&l===f||(g<k?a.ka[l*2]+=g:l!==0?(l!==e&&a.ka[l*2]++,a.ka[32]++):g<=10?a.ka[34]++:a.ka[36]++,g=0,e=l,f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4))}}
function al(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;f===0&&(h=138,k=3);for(d=0;d<=c;d++){var l=f;f=b[(d+1)*2+1];if(!(++g<h&&l===f)){if(g<k){do Qk(a,l,a.ka);while(--g!==0)}else l!==0?(l!==e&&(Qk(a,l,a.ka),g--),Qk(a,16,a.ka),Pk(a,g-3,2)):g<=10?(Qk(a,17,a.ka),Pk(a,g-3,3)):(Qk(a,18,a.ka),Pk(a,g-11,7));g=0;e=l;f===0?(h=138,k=3):l===f?(h=6,k=3):(h=7,k=4)}}}
function bl(a){var b=4093624447,c;for(c=0;c<=31;c++,b>>>=1)if(b&1&&a.sa[c*2]!==0)return 0;if(a.sa[18]!==0||a.sa[20]!==0||a.sa[26]!==0)return 1;for(c=32;c<256;c++)if(a.sa[c*2]!==0)return 1;return 0}
var cl=!1;function dl(a,b,c){a.aa[a.Eb+a.za*2]=b>>>8&255;a.aa[a.Eb+a.za*2+1]=b&255;a.aa[a.zc+a.za]=c&255;a.za++;b===0?a.sa[c*2]++:(a.matches++,b--,a.sa[(Gk[c]+256+1)*2]++,a.ab[(b<256?Fk[b]:Fk[256+(b>>>7)])*2]++);return a.za===a.Jb-1}
;function el(a,b){a.msg=xk[b];return b}
function fl(a){for(var b=a.length;--b>=0;)a[b]=0}
function gl(a){var b=a.state,c=b.pending;c>a.R&&(c=a.R);c!==0&&(P.mb(a.output,b.aa,b.Mb,c,a.vb),a.vb+=c,b.Mb+=c,a.Mc+=c,a.R-=c,b.pending-=c,b.pending===0&&(b.Mb=0))}
function hl(a,b){var c=a.va>=0?a.va:-1,d=a.v-a.va,e=0;if(a.level>0){a.M.uc===2&&(a.M.uc=bl(a));Zk(a,a.fc);Zk(a,a.Zb);$k(a,a.sa,a.fc.ub);$k(a,a.ab,a.Zb.ub);Zk(a,a.Rc);for(e=18;e>=3&&a.ka[Ck[e]*2+1]===0;e--);a.Qa+=3*(e+1)+14;var f=a.Qa+3+7>>>3;var g=a.yb+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&c!==-1)Pk(a,b?1:0,3),Vk(a,c,d);else if(a.strategy===4||g===f)Pk(a,2+(b?1:0),3),Yk(a,Dk,Ek);else{Pk(a,4+(b?1:0),3);c=a.fc.ub+1;d=a.Zb.ub+1;e+=1;Pk(a,c-257,5);Pk(a,d-1,5);Pk(a,e-4,4);for(f=0;f<e;f++)Pk(a,a.ka[Ck[f]*
2+1],3);al(a,a.sa,c-1);al(a,a.ab,d-1);Yk(a,a.sa,a.ab)}Tk(a);b&&Uk(a);a.va=a.v;gl(a.M)}
function R(a,b){a.aa[a.pending++]=b}
function il(a,b){a.aa[a.pending++]=b>>>8&255;a.aa[a.pending++]=b&255}
function jl(a,b){var c=a.jd,d=a.v,e=a.xa,f=a.kd,g=a.v>a.ma-262?a.v-(a.ma-262):0,h=a.window,k=a.Xa,l=a.Ia,m=a.v+258,n=h[d+e-1],r=h[d+e];a.xa>=a.bd&&(c>>=2);f>a.B&&(f=a.B);do{var t=b;if(h[t+e]===r&&h[t+e-1]===n&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<m;);t=258-(m-d);d=m-258;if(t>e){a.tb=b;e=t;if(t>=f)break;n=h[d+e-1];r=h[d+e]}}}while((b=l[b&k])>g&&--c!==0);return e<=
a.B?e:a.B}
function kl(a){var b=a.ma,c;do{var d=a.Dd-a.B-a.v;if(a.v>=b+(b-262)){P.mb(a.window,a.window,b,b,0);a.tb-=b;a.v-=b;a.va-=b;var e=c=a.ec;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ia[--e],a.Ia[e]=f>=b?f-b:0;while(--c);d+=b}if(a.M.na===0)break;e=a.M;c=a.window;f=a.v+a.B;var g=e.na;g>d&&(g=d);g===0?c=0:(e.na-=g,P.mb(c,e.input,e.gb,g,f),e.state.wrap===1?e.K=rk(e.K,c,g,f):e.state.wrap===2&&(e.K=sk(e.K,c,g,f)),e.gb+=g,e.ib+=g,c=g);a.B+=c;if(a.B+a.ta>=3)for(d=a.v-a.ta,a.P=a.window[d],
a.P=(a.P<<a.Na^a.window[d+1])&a.Ma;a.ta&&!(a.P=(a.P<<a.Na^a.window[d+3-1])&a.Ma,a.Ia[d&a.Xa]=a.head[a.P],a.head[a.P]=d,d++,a.ta--,a.B+a.ta<3););}while(a.B<262&&a.M.na!==0)}
function ll(a,b){for(var c;;){if(a.B<262){kl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.P=(a.P<<a.Na^a.window[a.v+3-1])&a.Ma,c=a.Ia[a.v&a.Xa]=a.head[a.P],a.head[a.P]=a.v);c!==0&&a.v-c<=a.ma-262&&(a.S=jl(a,c));if(a.S>=3)if(c=dl(a,a.v-a.tb,a.S-3),a.B-=a.S,a.S<=a.Bc&&a.B>=3){a.S--;do a.v++,a.P=(a.P<<a.Na^a.window[a.v+3-1])&a.Ma,a.Ia[a.v&a.Xa]=a.head[a.P],a.head[a.P]=a.v;while(--a.S!==0);a.v++}else a.v+=a.S,a.S=0,a.P=a.window[a.v],a.P=(a.P<<a.Na^a.window[a.v+1])&a.Ma;else c=dl(a,0,
a.window[a.v]),a.B--,a.v++;if(c&&(hl(a,!1),a.M.R===0))return 1}a.ta=a.v<2?a.v:2;return b===4?(hl(a,!0),a.M.R===0?3:4):a.za&&(hl(a,!1),a.M.R===0)?1:2}
function ml(a,b){for(var c,d;;){if(a.B<262){kl(a);if(a.B<262&&b===0)return 1;if(a.B===0)break}c=0;a.B>=3&&(a.P=(a.P<<a.Na^a.window[a.v+3-1])&a.Ma,c=a.Ia[a.v&a.Xa]=a.head[a.P],a.head[a.P]=a.v);a.xa=a.S;a.nd=a.tb;a.S=2;c!==0&&a.xa<a.Bc&&a.v-c<=a.ma-262&&(a.S=jl(a,c),a.S<=5&&(a.strategy===1||a.S===3&&a.v-a.tb>4096)&&(a.S=2));if(a.xa>=3&&a.S<=a.xa){d=a.v+a.B-3;c=dl(a,a.v-1-a.nd,a.xa-3);a.B-=a.xa-1;a.xa-=2;do++a.v<=d&&(a.P=(a.P<<a.Na^a.window[a.v+3-1])&a.Ma,a.Ia[a.v&a.Xa]=a.head[a.P],a.head[a.P]=a.v);
while(--a.xa!==0);a.eb=0;a.S=2;a.v++;if(c&&(hl(a,!1),a.M.R===0))return 1}else if(a.eb){if((c=dl(a,0,a.window[a.v-1]))&&hl(a,!1),a.v++,a.B--,a.M.R===0)return 1}else a.eb=1,a.v++,a.B--}a.eb&&(dl(a,0,a.window[a.v-1]),a.eb=0);a.ta=a.v<2?a.v:2;return b===4?(hl(a,!0),a.M.R===0?3:4):a.za&&(hl(a,!1),a.M.R===0)?1:2}
function nl(a,b){for(var c,d,e,f=a.window;;){if(a.B<=258){kl(a);if(a.B<=258&&b===0)return 1;if(a.B===0)break}a.S=0;if(a.B>=3&&a.v>0&&(d=a.v-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.v+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.S=258-(e-d);a.S>a.B&&(a.S=a.B)}a.S>=3?(c=dl(a,1,a.S-3),a.B-=a.S,a.v+=a.S,a.S=0):(c=dl(a,0,a.window[a.v]),a.B--,a.v++);if(c&&(hl(a,!1),a.M.R===0))return 1}a.ta=0;return b===4?(hl(a,!0),a.M.R===0?3:4):
a.za&&(hl(a,!1),a.M.R===0)?1:2}
function ol(a,b){for(var c;;){if(a.B===0&&(kl(a),a.B===0)){if(b===0)return 1;break}a.S=0;c=dl(a,0,a.window[a.v]);a.B--;a.v++;if(c&&(hl(a,!1),a.M.R===0))return 1}a.ta=0;return b===4?(hl(a,!0),a.M.R===0?3:4):a.za&&(hl(a,!1),a.M.R===0)?1:2}
function pl(a,b,c,d,e){this.ce=a;this.se=b;this.we=c;this.re=d;this.Yd=e}
var ql;ql=[new pl(0,0,0,0,function(a,b){var c=65535;for(c>a.Ba-5&&(c=a.Ba-5);;){if(a.B<=1){kl(a);if(a.B===0&&b===0)return 1;if(a.B===0)break}a.v+=a.B;a.B=0;var d=a.va+c;if(a.v===0||a.v>=d)if(a.B=a.v-d,a.v=d,hl(a,!1),a.M.R===0)return 1;if(a.v-a.va>=a.ma-262&&(hl(a,!1),a.M.R===0))return 1}a.ta=0;if(b===4)return hl(a,!0),a.M.R===0?3:4;a.v>a.va&&hl(a,!1);return 1}),
new pl(4,4,8,4,ll),new pl(4,5,16,8,ll),new pl(4,6,32,32,ll),new pl(4,4,16,16,ml),new pl(8,16,32,32,ml),new pl(8,16,128,128,ml),new pl(8,32,128,256,ml),new pl(32,128,258,1024,ml),new pl(32,258,258,4096,ml)];
function rl(){this.M=null;this.status=0;this.aa=null;this.wrap=this.pending=this.Mb=this.Ba=0;this.J=null;this.Da=0;this.method=8;this.rb=-1;this.Xa=this.Oc=this.ma=0;this.window=null;this.Dd=0;this.head=this.Ia=null;this.kd=this.bd=this.strategy=this.level=this.Bc=this.jd=this.xa=this.B=this.tb=this.v=this.eb=this.nd=this.S=this.va=this.Na=this.Ma=this.xc=this.ec=this.P=0;this.sa=new P.Ja(1146);this.ab=new P.Ja(122);this.ka=new P.Ja(78);fl(this.sa);fl(this.ab);fl(this.ka);this.Rc=this.Zb=this.fc=
null;this.La=new P.Ja(16);this.da=new P.Ja(573);fl(this.da);this.pb=this.Oa=0;this.depth=new P.Ja(573);fl(this.depth);this.ja=this.oa=this.ta=this.matches=this.yb=this.Qa=this.Eb=this.za=this.Jb=this.zc=0}
function sl(a,b){if(!a||!a.state||b>5||b<0)return a?el(a,-2):-2;var c=a.state;if(!a.output||!a.input&&a.na!==0||c.status===666&&b!==4)return el(a,a.R===0?-5:-2);c.M=a;var d=c.rb;c.rb=b;if(c.status===42)if(c.wrap===2)a.K=0,R(c,31),R(c,139),R(c,8),c.J?(R(c,(c.J.text?1:0)+(c.J.Ua?2:0)+(c.J.extra?4:0)+(c.J.name?8:0)+(c.J.comment?16:0)),R(c,c.J.time&255),R(c,c.J.time>>8&255),R(c,c.J.time>>16&255),R(c,c.J.time>>24&255),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,c.J.os&255),c.J.extra&&c.J.extra.length&&
(R(c,c.J.extra.length&255),R(c,c.J.extra.length>>8&255)),c.J.Ua&&(a.K=sk(a.K,c.aa,c.pending,0)),c.Da=0,c.status=69):(R(c,0),R(c,0),R(c,0),R(c,0),R(c,0),R(c,c.level===9?2:c.strategy>=2||c.level<2?4:0),R(c,3),c.status=113);else{var e=8+(c.Oc-8<<4)<<8;e|=(c.strategy>=2||c.level<2?0:c.level<6?1:c.level===6?2:3)<<6;c.v!==0&&(e|=32);c.status=113;il(c,e+(31-e%31));c.v!==0&&(il(c,a.K>>>16),il(c,a.K&65535));a.K=1}if(c.status===69)if(c.J.extra){for(e=c.pending;c.Da<(c.J.extra.length&65535)&&(c.pending!==c.Ba||
(c.J.Ua&&c.pending>e&&(a.K=sk(a.K,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending!==c.Ba));)R(c,c.J.extra[c.Da]&255),c.Da++;c.J.Ua&&c.pending>e&&(a.K=sk(a.K,c.aa,c.pending-e,e));c.Da===c.J.extra.length&&(c.Da=0,c.status=73)}else c.status=73;if(c.status===73)if(c.J.name){e=c.pending;do{if(c.pending===c.Ba&&(c.J.Ua&&c.pending>e&&(a.K=sk(a.K,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending===c.Ba)){var f=1;break}f=c.Da<c.J.name.length?c.J.name.charCodeAt(c.Da++)&255:0;R(c,f)}while(f!==0);c.J.Ua&&c.pending>
e&&(a.K=sk(a.K,c.aa,c.pending-e,e));f===0&&(c.Da=0,c.status=91)}else c.status=91;if(c.status===91)if(c.J.comment){e=c.pending;do{if(c.pending===c.Ba&&(c.J.Ua&&c.pending>e&&(a.K=sk(a.K,c.aa,c.pending-e,e)),gl(a),e=c.pending,c.pending===c.Ba)){f=1;break}f=c.Da<c.J.comment.length?c.J.comment.charCodeAt(c.Da++)&255:0;R(c,f)}while(f!==0);c.J.Ua&&c.pending>e&&(a.K=sk(a.K,c.aa,c.pending-e,e));f===0&&(c.status=103)}else c.status=103;c.status===103&&(c.J.Ua?(c.pending+2>c.Ba&&gl(a),c.pending+2<=c.Ba&&(R(c,
a.K&255),R(c,a.K>>8&255),a.K=0,c.status=113)):c.status=113);if(c.pending!==0){if(gl(a),a.R===0)return c.rb=-1,0}else if(a.na===0&&(b<<1)-(b>4?9:0)<=(d<<1)-(d>4?9:0)&&b!==4)return el(a,-5);if(c.status===666&&a.na!==0)return el(a,-5);if(a.na!==0||c.B!==0||b!==0&&c.status!==666){d=c.strategy===2?ol(c,b):c.strategy===3?nl(c,b):ql[c.level].Yd(c,b);if(d===3||d===4)c.status=666;if(d===1||d===3)return a.R===0&&(c.rb=-1),0;if(d===2&&(b===1?(Pk(c,2,3),Qk(c,256,Dk),c.ja===16?(Ok(c,c.oa),c.oa=0,c.ja=0):c.ja>=
8&&(c.aa[c.pending++]=c.oa&255,c.oa>>=8,c.ja-=8)):b!==5&&(Pk(c,0,3),Vk(c,0,0),b===3&&(fl(c.head),c.B===0&&(c.v=0,c.va=0,c.ta=0))),gl(a),a.R===0))return c.rb=-1,0}if(b!==4)return 0;if(c.wrap<=0)return 1;c.wrap===2?(R(c,a.K&255),R(c,a.K>>8&255),R(c,a.K>>16&255),R(c,a.K>>24&255),R(c,a.ib&255),R(c,a.ib>>8&255),R(c,a.ib>>16&255),R(c,a.ib>>24&255)):(il(c,a.K>>>16),il(c,a.K&65535));gl(a);c.wrap>0&&(c.wrap=-c.wrap);return c.pending!==0?0:1}
;var tl={};tl=function(){this.input=null;this.ib=this.na=this.gb=0;this.output=null;this.Mc=this.R=this.vb=0;this.msg="";this.state=null;this.uc=2;this.K=0};var ul=Object.prototype.toString;
function vl(a){if(!(this instanceof vl))return new vl(a);a=this.options=P.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&a.windowBits>0?a.windowBits=-a.windowBits:a.gzip&&a.windowBits>0&&a.windowBits<16&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.M=new tl;this.M.R=0;var b=this.M;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;c===-1&&(c=6);e<0?(h=0,e=-e):e>15&&(h=2,e-=16);if(f<1||f>
9||d!==8||e<8||e>15||c<0||c>9||g<0||g>4)b=el(b,-2);else{e===8&&(e=9);var k=new rl;b.state=k;k.M=b;k.wrap=h;k.J=null;k.Oc=e;k.ma=1<<k.Oc;k.Xa=k.ma-1;k.xc=f+7;k.ec=1<<k.xc;k.Ma=k.ec-1;k.Na=~~((k.xc+3-1)/3);k.window=new P.jb(k.ma*2);k.head=new P.Ja(k.ec);k.Ia=new P.Ja(k.ma);k.Jb=1<<f+6;k.Ba=k.Jb*4;k.aa=new P.jb(k.Ba);k.Eb=1*k.Jb;k.zc=3*k.Jb;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.ib=b.Mc=0;b.uc=2;c=b.state;c.pending=0;c.Mb=0;c.wrap<0&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.K=c.wrap===2?
0:1;c.rb=0;if(!cl){d=Array(16);for(f=g=0;f<28;f++)for(Hk[f]=g,e=0;e<1<<zk[f];e++)Gk[g++]=f;Gk[g-1]=f;for(f=g=0;f<16;f++)for(Ik[f]=g,e=0;e<1<<Ak[f];e++)Fk[g++]=f;for(g>>=7;f<30;f++)for(Ik[f]=g<<7,e=0;e<1<<Ak[f]-7;e++)Fk[256+g++]=f;for(e=0;e<=15;e++)d[e]=0;for(e=0;e<=143;)Dk[e*2+1]=8,e++,d[8]++;for(;e<=255;)Dk[e*2+1]=9,e++,d[9]++;for(;e<=279;)Dk[e*2+1]=7,e++,d[7]++;for(;e<=287;)Dk[e*2+1]=8,e++,d[8]++;Sk(Dk,287,d);for(e=0;e<30;e++)Ek[e*2+1]=5,Ek[e*2]=Rk(e,5);Kk=new Jk(Dk,zk,257,286,15);Lk=new Jk(Ek,
Ak,0,30,15);Mk=new Jk([],Bk,0,19,7);cl=!0}c.fc=new Nk(c.sa,Kk);c.Zb=new Nk(c.ab,Lk);c.Rc=new Nk(c.ka,Mk);c.oa=0;c.ja=0;Tk(c);c=0}else c=el(b,-2);c===0&&(b=b.state,b.Dd=2*b.ma,fl(b.head),b.Bc=ql[b.level].se,b.bd=ql[b.level].ce,b.kd=ql[b.level].we,b.jd=ql[b.level].re,b.v=0,b.va=0,b.B=0,b.ta=0,b.S=b.xa=2,b.eb=0,b.P=0);b=c}}else b=-2;if(b!==0)throw Error(xk[b]);a.header&&(b=this.M)&&b.state&&b.state.wrap===2&&(b.state.J=a.header);if(a.dictionary){var l;typeof a.dictionary==="string"?l=qk(a.dictionary):
ul.call(a.dictionary)==="[object ArrayBuffer]"?l=new Uint8Array(a.dictionary):l=a.dictionary;a=this.M;f=l;g=f.length;if(a&&a.state)if(l=a.state,b=l.wrap,b===2||b===1&&l.status!==42||l.B)b=-2;else{b===1&&(a.K=rk(a.K,f,g,0));l.wrap=0;g>=l.ma&&(b===0&&(fl(l.head),l.v=0,l.va=0,l.ta=0),c=new P.jb(l.ma),P.mb(c,f,g-l.ma,l.ma,0),f=c,g=l.ma);c=a.na;d=a.gb;e=a.input;a.na=g;a.gb=0;a.input=f;for(kl(l);l.B>=3;){f=l.v;g=l.B-2;do l.P=(l.P<<l.Na^l.window[f+3-1])&l.Ma,l.Ia[f&l.Xa]=l.head[l.P],l.head[l.P]=f,f++;while(--g);
l.v=f;l.B=2;kl(l)}l.v+=l.B;l.va=l.v;l.ta=l.B;l.B=0;l.S=l.xa=2;l.eb=0;a.gb=d;a.input=e;a.na=c;l.wrap=b;b=0}else b=-2;if(b!==0)throw Error(xk[b]);this.Mg=!0}}
vl.prototype.push=function(a,b){var c=this.M,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:b===!0?4:0;typeof a==="string"?c.input=qk(a):ul.call(a)==="[object ArrayBuffer]"?c.input=new Uint8Array(a):c.input=a;c.gb=0;c.na=c.input.length;do{c.R===0&&(c.output=new P.jb(d),c.vb=0,c.R=d);a=sl(c,e);if(a!==1&&a!==0)return wl(this,a),this.ended=!0,!1;if(c.R===0||c.na===0&&(e===4||e===2))if(this.options.to==="string"){var f=P.Lc(c.output,c.vb);b=f;f=f.length;if(f<65537&&(b.subarray&&pk||!b.subarray))b=
String.fromCharCode.apply(null,P.Lc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=P.Lc(c.output,c.vb),this.chunks.push(b)}while((c.na>0||c.R===0)&&a!==1);if(e===4)return(c=this.M)&&c.state?(d=c.state.status,d!==42&&d!==69&&d!==73&&d!==91&&d!==103&&d!==113&&d!==666?a=el(c,-2):(c.state=null,a=d===113?el(c,-3):0)):a=-2,wl(this,a),this.ended=!0,a===0;e===2&&(wl(this,0),c.R=0);return!0};
function wl(a,b){b===0&&(a.result=a.options.to==="string"?a.chunks.join(""):P.Yc(a.chunks));a.chunks=[];a.err=b;a.msg=a.M.msg}
function xl(a,b){b=b||{};b.gzip=!0;b=new vl(b);b.push(a,!0);if(b.err)throw b.msg||xk[b.err];return b.result}
;function yl(a){if(!a)return null;a=a.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue;var b;a?b=hb(a):b=null;return b}
;function zl(a){return hb(a===null?"null":a===void 0?"undefined":a)}
;function Al(a){this.name=a}
;var Bl=new Al("rawColdConfigGroup");var Cl=new Al("rawHotConfigGroup");function Dl(a){this.G=J(a)}
x(Dl,K);function El(a){this.G=J(a)}
x(El,K);El.prototype.setTrackingParams=function(a){if(a!=null)if(typeof a==="string")a=a?new pd(a,md):nd||(nd=new pd(null,md));else if(a.constructor!==pd)if(ld(a))a=a.length?new pd(new Uint8Array(a),md):nd||(nd=new pd(null,md));else throw Error();return lf(this,1,a)};var Fl=new Al("continuationCommand");var Gl=new Al("webCommandMetadata");var Hl=new Al("signalServiceEndpoint");var Il={Cf:"EMBEDDED_PLAYER_MODE_UNKNOWN",zf:"EMBEDDED_PLAYER_MODE_DEFAULT",Bf:"EMBEDDED_PLAYER_MODE_PFP",Af:"EMBEDDED_PLAYER_MODE_PFL"};var Jl=new Al("feedbackEndpoint");var Vd={rg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNKNOWN",Qf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_FOR_TESTING",gg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_RESUME_TO_HOME_TTL",kg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_START_TO_SHORTS_ANALYSIS_SLICE",Nf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_DEVICE_LAYER_SLICE",qg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_UNIFIED_LAYER_SLICE",sg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_VISITOR_LAYER_SLICE",jg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SHOW_SHEET_COMMAND_HANDLER_BLOCK",
ug:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_MIGRATED_COMPONENT",tg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WIZ_NEXT_CHANNEL_NAME_TOOLTIP",hg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ROTATION_LOCK_SUPPORTED",mg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_THEATER_MODE_ENABLED",yg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_PIN_SUGGESTION",xg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_LONG_PRESS_EDU_TOAST",wg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_AMBIENT",ng:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TIME_WATCHED_PANEL",
ig:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SEARCH_FROM_SEARCH_BAR_OVERLAY",zg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_SHOW_VOICE_SEARCH_EDU_TOAST",lg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_SUGGESTED_LANGUAGE_SELECTED",Ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_TRIGGER_SHORTS_PIP",Vf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IN_ZP_VOICE_CRASHY_SET",cg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_SUPPRESSED",ag:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_FAST_SWIPE_ALLOWED",eg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_PULL_TO_REFRESH_ATTEMPT",
vg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_WOULD_BLOCK_KABUKI",fg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_TALL_SCREEN",dg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_REEL_NORMAL_SCREEN",Gf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_ENABLED",Ff:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ACCESSIBILITY_MODE_DISABLED",Hf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_AUTOPLAY_ENABLED",If:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_CAST_MATCH_OCCURRED",Of:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_EMC3DS_ELIGIBLE",Pf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ENDSCREEN_TRIGGERED",
Zf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_TRIGGERED",Yf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_POSTPLAY_LACT_THRESHOLD_EXCEEDED",Rf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MATCHED_ON_REMOTE_CONNECTION",Tf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_SWITCHABLE_ON_REMOTE_CONNECTION",Sf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_STATE_MISATTRIBUTED_ON_REMOTE_CONNECTION",Uf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_IDENTITIES_TV_IS_SIGNED_IN_ON_REMOTE_CONNECTION",og:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_COLD_ON_REMOTE_CONNECTION",
pg:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_TV_START_TYPE_NON_COLD_ON_REMOTE_CONNECTION",Xf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_ON_REMOTE_CONNECTION",Mf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_VALID",Kf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_INVALID",Lf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_UNDEFINED",Jf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_COBALT_PERSISTENT_SETTINGS_TEST_DEFINED",Wf:"GENERIC_CLIENT_EXPERIMENT_EVENT_TYPE_LACT_THRESHOLD_EXCEEDED"};var Kl=new Al("shareEndpoint"),Ll=new Al("shareEntityEndpoint"),Ml=new Al("shareEntityServiceEndpoint"),Nl=new Al("webPlayerShareEntityServiceEndpoint");var Ol=new Al("playlistEditEndpoint");var Pl=new Al("modifyChannelNotificationPreferenceEndpoint");var Ql=new Al("unsubscribeEndpoint");var Rl=new Al("subscribeEndpoint");function Sl(){var a=Tl;E("yt.ads.biscotti.getId_")||D("yt.ads.biscotti.getId_",a)}
function Ul(a){D("yt.ads.biscotti.lastId_",a)}
;function Vl(a,b){b.length>1?a[b[0]]=b[1]:b.length===1&&Object.assign(a,b[0])}
;var Wl=C.window,Xl,Yl,Zl=(Wl==null?void 0:(Xl=Wl.yt)==null?void 0:Xl.config_)||(Wl==null?void 0:(Yl=Wl.ytcfg)==null?void 0:Yl.data_)||{};D("yt.config_",Zl);function $l(){Vl(Zl,arguments)}
function S(a,b){return a in Zl?Zl[a]:b}
function am(a){var b=Zl.EXPERIMENT_FLAGS;return b?b[a]:void 0}
;var bm=[];function cm(a){bm.forEach(function(b){return b(a)})}
function dm(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){em(b)}}:a}
function em(a){var b=E("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=S("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),$l("ERRORS",b));cm(a)}
function fm(a,b,c,d,e){var f=E("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=S("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),$l("ERRORS",f))}
;var gm=/^[\w.]*$/,hm={q:!0,search_query:!0};function im(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(f.length===1&&f[0]||f.length===2)try{var g=jm(f[0]||""),h=jm(f[1]||"");if(g in c){var k=c[g];Array.isArray(k)?Qb(k,h):c[g]=[k,h]}else c[g]=h}catch(r){var l=r,m=f[0],n=String(im);l.args=[{key:m,value:f[1],query:a,method:km===n?"unchanged":n}];hm.hasOwnProperty(m)||fm(l)}}return c}
var km=String(im);function lm(a){var b=[];xg(a,function(c,d){var e=encodeURIComponent(String(d));c=Array.isArray(c)?c:[c];Kb(c,function(f){f==""?b.push(e):b.push(e+"="+encodeURIComponent(String(f)))})});
return b.join("&")}
function mm(a){a.charAt(0)==="?"&&(a=a.substring(1));return im(a,"&")}
function nm(a){return a.indexOf("?")!==-1?(a=(a||"").split("#")[0],a=a.split("?",2),mm(a.length>1?a[1]:a[0])):{}}
function om(a,b,c){var d=a.split("#",2);a=d[0];d=d.length>1?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=mm(e[1]||"");for(var f in b)!c&&e!==null&&f in e||(e[f]=b[f]);return ec(a,e)+d}
function pm(a){if(!b)var b=window.location.href;var c=Zb(1,a),d=$b(a);c&&d?(a=a.match(Xb),b=b.match(Xb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?$b(b)===d&&(Number(Zb(4,b))||null)===(Number(Zb(4,a))||null):!0;return a}
function jm(a){return a&&a.match(gm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function qm(a){var b=rm;a=a===void 0?E("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Fj;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ka){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=g===void 0?xj:g;try{var h=g.history.length}catch(Ka){h=0}e.u_his=h;var k;e.u_h=(k=xj.screen)==null?void 0:k.height;var l;e.u_w=(l=xj.screen)==null?void 0:l.width;var m;e.u_ah=(m=xj.screen)==null?void 0:m.availHeight;var n;e.u_aw=
(n=xj.screen)==null?void 0:n.availWidth;var r;e.u_cd=(r=xj.screen)==null?void 0:r.colorDepth}catch(Ka){}h=b.h;try{var t=h.screenX;var w=h.screenY}catch(Ka){}try{var y=h.outerWidth;var z=h.outerHeight}catch(Ka){}try{var G=h.innerWidth;var I=h.innerHeight}catch(Ka){}try{var M=h.screenLeft;var O=h.screenTop}catch(Ka){}try{G=h.innerWidth,I=h.innerHeight}catch(Ka){}try{var ta=h.screen.availWidth;var lb=h.screen.availTop}catch(Ka){}t=[M,O,t,w,ta,lb,y,z,G,I];try{var T=(b.h.top||window).document,ua=T.compatMode==
"CSS1Compat"?T.documentElement:T.body;var La=(new Lg(ua.clientWidth,ua.clientHeight)).round()}catch(Ka){La=new Lg(-12245933,-12245933)}T=La;La={};var Ma=Ma===void 0?C:Ma;ua=new Lj;"SVGElement"in Ma&&"createElementNS"in Ma.document&&ua.set(0);w=Cj();w["allow-top-navigation-by-user-activation"]&&ua.set(1);w["allow-popups-to-escape-sandbox"]&&ua.set(2);Ma.crypto&&Ma.crypto.subtle&&ua.set(3);"TextDecoder"in Ma&&"TextEncoder"in Ma&&ua.set(4);Ma=Mj(ua);La.bc=Ma;La.bih=T.height;La.biw=T.width;La.brdim=t.join();
b=b.i;b=(La.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,La.wgl=!!xj.WebGLRenderingContext,La);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var rm=new function(){var a=window.document;this.h=window;this.i=a};
D("yt.ads_.signals_.getAdSignalsString",function(a){return lm(qm(a))});Ya();navigator.userAgent.indexOf(" (CrKey ");var sm="XMLHttpRequest"in C?function(){return new XMLHttpRequest}:null;
function tm(){if(!sm)return null;var a=sm();return"open"in a?a:null}
function um(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function wm(a,b){typeof a==="function"&&(a=dm(a));return window.setTimeout(a,b)}
;var xm="client_dev_domain client_dev_expflag client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ja(xm),["client_dev_set_cookie"]);function U(a){a=ym(a);return typeof a==="string"&&a==="false"?!1:!!a}
function zm(a,b){a=ym(a);return a===void 0&&b!==void 0?b:Number(a||0)}
function ym(a){return S("EXPERIMENT_FLAGS",{})[a]}
function Am(){for(var a=[],b=S("EXPERIMENTS_FORCED_FLAGS",{}),c=v(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=S("EXPERIMENT_FLAGS",{});d=v(Object.keys(c));for(var e=d.next();!e.done;e=d.next())e=e.value,e.startsWith("force_")&&b[e]===void 0&&a.push({key:e,value:String(c[e])});return a}
;var Bm={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Cm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ja(xm)),Dm=!1;
function Em(a,b,c,d,e,f,g,h){function k(){(l&&"readyState"in l?l.readyState:0)===4&&b&&dm(b)(l)}
c=c===void 0?"GET":c;d=d===void 0?"":d;h=h===void 0?!1:h;var l=tm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",k,!1):l.onreadystatechange=k;U("debug_forward_web_query_parameters")&&(a=Fm(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c=c==="POST"&&(window.FormData===void 0||!(d instanceof FormData));if(e=Gm(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"===m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");
if(h&&"setAttributionReporting"in XMLHttpRequest.prototype){a={eventSourceEligible:!0,triggerEligible:!1};try{l.setAttributionReporting(a)}catch(n){fm(n)}}l.send(d);return l}
function Gm(a,b){b=b===void 0?{}:b;var c=pm(a),d=S("INNERTUBE_CLIENT_NAME"),e=U("web_ajax_ignore_global_headers_if_set"),f;for(f in Bm){var g=S(Bm[f]),h=f==="X-Goog-AuthUser"||f==="X-Goog-PageId";f!=="X-Goog-Visitor-Id"||g||(g=S("VISITOR_DATA"));var k;if(!(k=!g)){if(!(k=c||($b(a)?!1:!0))){k=a;var l;if(l=U("add_auth_headers_to_remarketing_google_dot_com_ping")&&f==="Authorization"&&(d==="TVHTML5"||d==="TVHTML5_UNPLUGGED"||d==="TVHTML5_SIMPLY"))l=$b(k),l=l!==null?l.split(".").reverse():null,l=l===null?
!1:l[1]==="google"?!0:l[2]==="google"?l[0]==="au"&&l[1]==="com"?!0:l[0]==="uk"&&l[1]==="co"?!0:!1:!1;l&&(k=Yb(Zb(5,k))||"",k=k.split("/"),k="/"+(k.length>1?k[1]:""),l=k==="/pagead");k=l?!0:!1}k=!k}k||e&&b[f]!==void 0||d==="TVHTML5_UNPLUGGED"&&h||(b[f]=g)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!$b(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!$b(a)){try{var m=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(n){}m&&
(b["X-YouTube-Time-Zone"]=m)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&$b(a)||(b["X-YouTube-Ad-Signals"]=lm(qm()));return b}
function Hm(a,b){b.method="POST";b.postParams||(b.postParams={});return Im(a,b)}
function Im(a,b){var c=b.format||"JSON";a=Jm(a,b);var d=Km(a,b),e=!1,f=Lm(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var l=um(k),m=null,n=400<=k.status&&k.status<500,r=500<=k.status&&k.status<600;if(l||n||r)m=Mm(a,c,k,b.convertToSafeHtml);l&&(l=Nm(c,k,m));m=m||{};n=b.context||C;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&d>0){var g=b.onTimeout;var h=wm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||C,f))},d)}return f}
function Jm(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=S("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=om(a,b||{},!0);return a}
function Km(a,b){var c=S("XSRF_FIELD_NAME"),d=S("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=S("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||$b(a)&&!b.withCredentials&&$b(a)!==document.location.hostname||b.method!=="POST"||h&&h!=="application/x-www-form-urlencoded"||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(U("ajax_parse_query_data_only_when_filled")&&f&&Object.keys(f).length>0||f)&&typeof e==="string"&&(e=mm(e),Hg(e,f),e=b.postBodyFormat&&b.postBodyFormat===
"JSON"?JSON.stringify(e):dc(e));f=e||f&&!Ag(f);!Dm&&f&&b.method!=="POST"&&(Dm=!0,em(Error("AJAX request with postData should use POST")));return e}
function Mm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,fm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&a.indexOf("json")>=0&&(f.substring(0,5)===")]}'\n"&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Om(a):null)e={},Kb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Pm(g)})}d&&Qm(e);
return e}
function Qm(a){if(Qa(a))for(var b in a){var c;(c=b==="html_content")||(c=b.length-5,c=c>=0&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];var e=fb();d=new zb(e?e.createHTML(d):d);a[c]=d}else Qm(a[b])}}
function Nm(a,b,c){if(b&&b.status===204)return!0;switch(a){case "JSON":return!!c;case "XML":return Number(c&&c.return_code)===0;case "RAW":return!0;default:return!!c}}
function Om(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&a.length>0?a[0]:null:null}
function Pm(a){var b="";Kb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Fm(a){var b=window.location.search,c=$b(a);U("debug_handle_relative_url_for_query_forward_killswitch")||!c&&pm(a)&&(c=document.location.hostname);var d=Yb(Zb(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=mm(b),f={};Kb(Cm,function(g){e[g]&&(f[g]=e[g])});
return om(a,f||{},!1)}
var Lm=Em;var Rm=[{Cc:function(a){return"Cannot read property '"+a.key+"'"},
hc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Cc:function(a){return"Cannot call '"+a.key+"'"},
hc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Cc:function(a){return a.key+" is not defined"},
hc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Tm={Va:[],Sa:[{callback:Sm,weight:500}]};function Sm(a){if(a.name==="JavaException")return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Um(){this.Sa=[];this.Va=[]}
var Vm;function Wm(){if(!Vm){var a=Vm=new Um;a.Va.length=0;a.Sa.length=0;Tm.Va&&a.Va.push.apply(a.Va,Tm.Va);Tm.Sa&&a.Sa.push.apply(a.Sa,Tm.Sa)}return Vm}
;var Xm=new N;function Ym(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Zm(b);if(e===Infinity)break;var f=e>>3;switch(e&7){case 0:e=Zm(b);if(f===2)return e;break;case 1:if(f===2)return;d+=8;break;case 2:e=Zm(b);if(f===2)return a.substr(d,e);d+=e;break;case 5:if(f===2)return;d+=4;break;default:return}}while(d<c)}
function Zm(a){var b=a(),c=b&127;if(b<128)return c;b=a();c|=(b&127)<<7;if(b<128)return c;b=a();c|=(b&127)<<14;if(b<128)return c;b=a();return b<128?c|(b&127)<<21:Infinity}
;function $m(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=an(d,a[d],b,c),e>500));d++);d=e}else if(typeof a==="object")for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f=typeof g!=="string"||f!=="clickTrackingParams"&&f!=="trackingParams"?0:(g=Ym(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?an(f+".ve",g,h,k):0;d+=f;d+=an(e,a[e],b,c);if(d>500)break}}else c[b]=bn(a),d+=c[b].length;else c[b]=bn(a),d+=c[b].length;return d}
function an(a,b,c,d){c+="."+a;a=bn(b);d[c]=a;return c.length+a.length}
function bn(a){try{return(typeof a==="string"?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function cn(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function dn(){if(!C.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return C.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":C.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":C.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":C.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function en(){this.af=!0}
function fn(){en.h||(en.h=new en);return en.h}
function gn(a,b){a={};var c=[],d=U("enable_first_party_auth_v2")||(b==null?void 0:b.dd)&&U("enable_first_party_auth_v2_on_get_account_menu");"USER_SESSION_ID"in Zl&&d&&c.push({key:"u",value:S("USER_SESSION_ID")});if(c=pg(c))a.Authorization=c,c=b=b==null?void 0:b.sessionIndex,c===void 0&&(c=Number(S("SESSION_INDEX",0)),c=isNaN(c)?0:c),U("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Zl||(a["X-Origin"]=window.location.origin),b===void 0&&"DELEGATED_SESSION_ID"in
Zl&&(a["X-Goog-PageId"]=S("DELEGATED_SESSION_ID"));return a}
;var hn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function jn(a,b,c,d,e){lg.set(""+a,b,{Lb:c,path:"/",domain:d===void 0?"youtube.com":d,secure:e===void 0?!1:e})}
function kn(a){return lg.get(""+a,void 0)}
function ln(a,b,c){lg.remove(""+a,b===void 0?"/":b,c===void 0?"youtube.com":c)}
function mn(){if(U("embeds_web_enable_cookie_detection_fix")){if(!C.navigator.cookieEnabled)return!1}else if(!lg.isEnabled())return!1;if(lg.h.cookie)return!0;U("embeds_web_enable_cookie_detection_fix")?lg.set("TESTCOOKIESENABLED","1",{Lb:60,Je:"none",secure:!0}):lg.set("TESTCOOKIESENABLED","1",{Lb:60});if(lg.get("TESTCOOKIESENABLED")!=="1")return!1;lg.remove("TESTCOOKIESENABLED");return!0}
;var nn=E("ytglobal.prefsUserPrefsPrefs_")||{};D("ytglobal.prefsUserPrefsPrefs_",nn);function on(){this.h=S("ALT_PREF_COOKIE_NAME","PREF");this.i=S("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=kn(this.h);a&&this.parse(a)}
var pn;function qn(){pn||(pn=new on);return pn}
p=on.prototype;p.get=function(a,b){rn(a);sn(a);a=nn[a]!==void 0?nn[a].toString():null;return a!=null?a:b?b:""};
p.set=function(a,b){rn(a);sn(a);if(b==null)throw Error("ExpectedNotNull");nn[a]=b.toString()};
function tn(a){return!!((un("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
p.remove=function(a){rn(a);sn(a);delete nn[a]};
p.clear=function(){for(var a in nn)delete nn[a]};
function sn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function rn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function un(a){a=nn[a]!==void 0?nn[a].toString():null;return a!=null&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
p.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(nn[d]=c.toString())}};var vn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},wn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function xn(){var a=C.navigator;return a?a.connection:void 0}
function yn(){var a=xn();if(a){var b=vn[a.type||"unknown"]||"CONN_UNKNOWN";a=vn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";b==="CONN_CELLULAR_UNKNOWN"&&a!=="CONN_UNKNOWN"&&(b=a);if(b!=="CONN_UNKNOWN")return b;if(a!=="CONN_UNKNOWN")return a}}
function zn(){var a=xn();if(a!=null&&a.effectiveType)return wn.hasOwnProperty(a.effectiveType)?wn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function V(a){var b=B.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ja(b))}
x(V,Error);function An(){try{return Bn(),!0}catch(a){return!1}}
function Bn(a){if(S("DATASYNC_ID")!==void 0)return S("DATASYNC_ID");throw new V("Datasync ID not set",a===void 0?"unknown":a);}
;function Cn(){}
function Dn(a,b){return Kj.Za(a,0,b)}
Cn.prototype.qa=function(a,b){return this.Za(a,1,b)};
Cn.prototype.Bb=function(a){var b=E("yt.scheduler.instance.addImmediateJob");b?b(a):a()};var En=zm("web_emulated_idle_callback_delay",300),Fn=1E3/60-3,Gn=[8,5,4,3,2,1,0];
function Hn(a){a=a===void 0?{}:a;L.call(this);this.i=[];this.j={};this.X=this.h=0;this.W=this.u=!1;this.I=[];this.T=this.ga=!1;for(var b=v(Gn),c=b.next();!c.done;c=b.next())this.i[c.value]=[];this.o=0;this.sc=a.timeout||1;this.H=Fn;this.A=0;this.pa=this.ye.bind(this);this.qc=this.df.bind(this);this.Ka=this.Jd.bind(this);this.Ya=this.de.bind(this);this.Sb=this.Ce.bind(this);this.ya=!!window.requestIdleCallback&&!!window.cancelIdleCallback&&!U("disable_scheduler_requestIdleCallback");(this.ia=a.useRaf!==
!1&&!!window.requestAnimationFrame)&&document.addEventListener("visibilitychange",this.pa)}
x(Hn,L);p=Hn.prototype;p.Bb=function(a){var b=Ya();In(this,a);a=Ya()-b;this.u||(this.H-=a)};
p.Za=function(a,b,c){++this.X;if(b===10)return this.Bb(a),this.X;var d=this.X;this.j[d]=a;this.u&&!c?this.I.push({id:d,priority:b}):(this.i[b].push(d),this.W||this.u||(this.h!==0&&Jn(this)!==this.A&&this.stop(),this.start()));return d};
p.ra=function(a){delete this.j[a]};
function Kn(a){a.I.length=0;for(var b=5;b>=0;b--)a.i[b].length=0;a.i[8].length=0;a.j={};a.stop()}
p.isHidden=function(){return!!document.hidden||!1};
function Ln(a){return!a.isHidden()&&a.ia}
function Jn(a){if(a.i[8].length){if(a.T)return 4;if(Ln(a))return 3}for(var b=5;b>=a.o;b--)if(a.i[b].length>0)return b>0?Ln(a)?3:2:1;return 0}
p.Ha=function(a){var b=E("yt.logging.errors.log");b&&b(a)};
function In(a,b){try{b()}catch(c){a.Ha(c)}}
function Mn(a){for(var b=v(Gn),c=b.next();!c.done;c=b.next())if(a.i[c.value].length)return!0;return!1}
p.de=function(a){var b=void 0;a&&(b=a.timeRemaining());this.ga=!0;Nn(this,b);this.ga=!1};
p.df=function(){Nn(this)};
p.Jd=function(){On(this)};
p.Ce=function(a){this.T=!0;var b=Jn(this);b===4&&b!==this.A&&(this.stop(),this.start());Nn(this,void 0,a);this.T=!1};
p.ye=function(){this.isHidden()||On(this);this.h&&(this.stop(),this.start())};
function On(a){a.stop();a.u=!0;for(var b=Ya(),c=a.i[8];c.length;){var d=c.shift(),e=a.j[d];delete a.j[d];e&&In(a,e)}Pn(a);a.u=!1;Mn(a)&&a.start();b=Ya()-b;a.H-=b}
function Pn(a){for(var b=0,c=a.I.length;b<c;b++){var d=a.I[b];a.i[d.priority].push(d.id)}a.I.length=0}
function Nn(a,b,c){a.T&&a.A===4&&a.h||a.stop();a.u=!0;b=Ya()+(b||a.H);for(var d=a.i[5];d.length;){var e=d.shift(),f=a.j[e];delete a.j[e];if(f){e=a;try{f(c)}catch(l){e.Ha(l)}}}for(d=a.i[4];d.length;)c=d.shift(),f=a.j[c],delete a.j[c],f&&In(a,f);d=a.ga?0:1;d=a.o>d?a.o:d;if(!(Ya()>=b)){do{a:{c=a;f=d;for(e=3;e>=f;e--)for(var g=c.i[e];g.length;){var h=g.shift(),k=c.j[h];delete c.j[h];if(k){c=k;break a}}c=null}c&&In(a,c)}while(c&&Ya()<b)}a.u=!1;Pn(a);a.H=Fn;Mn(a)&&a.start()}
p.start=function(){this.W=!1;if(this.h===0)switch(this.A=Jn(this),this.A){case 1:var a=this.Ya;this.h=this.ya?window.requestIdleCallback(a,{timeout:3E3}):window.setTimeout(a,En);break;case 2:this.h=window.setTimeout(this.qc,this.sc);break;case 3:this.h=window.requestAnimationFrame(this.Sb);break;case 4:this.h=window.setTimeout(this.Ka,0)}};
p.pause=function(){this.stop();this.W=!0};
p.stop=function(){if(this.h){switch(this.A){case 1:var a=this.h;this.ya?window.cancelIdleCallback(a):window.clearTimeout(a);break;case 2:case 4:window.clearTimeout(this.h);break;case 3:window.cancelAnimationFrame(this.h)}this.h=0}};
p.ba=function(){Kn(this);this.stop();this.ia&&document.removeEventListener("visibilitychange",this.pa);L.prototype.ba.call(this)};var Qn=E("yt.scheduler.instance.timerIdMap_")||{},Rn=zm("kevlar_tuner_scheduler_soft_state_timer_ms",800),Sn=0,Tn=0;function Un(){var a=E("ytglobal.schedulerInstanceInstance_");if(!a||a.ea)a=new Hn(S("scheduler")||{}),D("ytglobal.schedulerInstanceInstance_",a);return a}
function Vn(){Wn();var a=E("ytglobal.schedulerInstanceInstance_");a&&(qg(a),D("ytglobal.schedulerInstanceInstance_",null))}
function Wn(){Kn(Un());for(var a in Qn)Qn.hasOwnProperty(a)&&delete Qn[Number(a)]}
function Xn(a,b,c){if(!c)return c=c===void 0,-Un().Za(a,b,c);var d=window.setTimeout(function(){var e=Un().Za(a,b);Qn[d]=e},c);
return d}
function Yn(a){Un().Bb(a)}
function Zn(a){var b=Un();if(a<0)b.ra(-a);else{var c=Qn[a];c?(b.ra(c),delete Qn[a]):window.clearTimeout(a)}}
function $n(){ao()}
function ao(){window.clearTimeout(Sn);Un().start()}
function bo(){Un().pause();window.clearTimeout(Sn);Sn=window.setTimeout($n,Rn)}
function co(){window.clearTimeout(Tn);Tn=window.setTimeout(function(){eo(0)},Rn)}
function eo(a){co();var b=Un();b.o=a;b.start()}
function fo(a){co();var b=Un();b.o>a&&(b.o=a,b.start())}
function go(){window.clearTimeout(Tn);var a=Un();a.o=0;a.start()}
;function ho(){Cn.apply(this,arguments)}
x(ho,Cn);function io(){ho.h||(ho.h=new ho);return ho.h}
ho.prototype.Za=function(a,b,c){c!==void 0&&Number.isNaN(Number(c))&&(c=void 0);var d=E("yt.scheduler.instance.addJob");return d?d(a,b,c):c===void 0?(a(),NaN):wm(a,c||0)};
ho.prototype.ra=function(a){if(a===void 0||!Number.isNaN(Number(a))){var b=E("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
ho.prototype.start=function(){var a=E("yt.scheduler.instance.start");a&&a()};
ho.prototype.pause=function(){var a=E("yt.scheduler.instance.pause");a&&a()};
var Kj=io();
U("web_scheduler_auto_init")&&!E("yt.scheduler.initialized")&&(D("yt.scheduler.instance.dispose",Vn),D("yt.scheduler.instance.addJob",Xn),D("yt.scheduler.instance.addImmediateJob",Yn),D("yt.scheduler.instance.cancelJob",Zn),D("yt.scheduler.instance.cancelAllJobs",Wn),D("yt.scheduler.instance.start",ao),D("yt.scheduler.instance.pause",bo),D("yt.scheduler.instance.setPriorityThreshold",eo),D("yt.scheduler.instance.enablePriorityThreshold",fo),D("yt.scheduler.instance.clearPriorityThreshold",go),D("yt.scheduler.initialized",
!0));function jo(a){var b=new kk;this.h=(a=b.isAvailable()?a?new lk(b,a):b:null)?new fk(a):null;this.i=document.domain||window.location.hostname}
jo.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+c*1E3);return}catch(f){}var e="";if(d)try{e=escape((new Pi).serialize(b))}catch(f){return}else e=escape(b);jn(a,e,c,this.i)};
jo.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=kn(a))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
jo.prototype.remove=function(a){this.h&&this.h.remove(a);ln(a,"/",this.i)};var ko=function(){var a;return function(){a||(a=new jo("ytidb"));return a}}();
function lo(){var a;return(a=ko())==null?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var mo=[],no,oo=!1;function po(){var a={};for(no=new qo(a.handleError===void 0?ro:a.handleError,a.logEvent===void 0?so:a.logEvent);mo.length>0;)switch(a=mo.shift(),a.type){case "ERROR":no.Ha(a.payload);break;case "EVENT":no.logEvent(a.eventType,a.payload)}}
function to(a){oo||(no?no.Ha(a):(mo.push({type:"ERROR",payload:a}),mo.length>10&&mo.shift()))}
function uo(a,b){oo||(no?no.logEvent(a,b):(mo.push({type:"EVENT",eventType:a,payload:b}),mo.length>10&&mo.shift()))}
;function vo(a){if(a.indexOf(":")>=0)throw Error("Database name cannot contain ':'");}
function wo(a){return a.substr(0,a.indexOf(":"))||a}
;var xo=Xc||Yc;function yo(a){var b=Hc();return b?b.toLowerCase().indexOf(a)>=0:!1}
;var zo={},Ao=(zo.AUTH_INVALID="No user identifier specified.",zo.EXPLICIT_ABORT="Transaction was explicitly aborted.",zo.IDB_NOT_SUPPORTED="IndexedDB is not supported.",zo.MISSING_INDEX="Index not created.",zo.MISSING_OBJECT_STORES="Object stores not created.",zo.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",zo.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",zo.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
zo.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",zo.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",zo.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",zo.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",zo),Bo={},Co=(Bo.AUTH_INVALID="ERROR",Bo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Bo.EXPLICIT_ABORT="IGNORED",Bo.IDB_NOT_SUPPORTED="ERROR",Bo.MISSING_INDEX=
"WARNING",Bo.MISSING_OBJECT_STORES="ERROR",Bo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Bo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Bo.QUOTA_EXCEEDED="WARNING",Bo.QUOTA_MAYBE_EXCEEDED="WARNING",Bo.UNKNOWN_ABORT="WARNING",Bo.INCOMPATIBLE_DB_VERSION="WARNING",Bo),Do={},Eo=(Do.AUTH_INVALID=!1,Do.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Do.EXPLICIT_ABORT=!1,Do.IDB_NOT_SUPPORTED=!1,Do.MISSING_INDEX=!1,Do.MISSING_OBJECT_STORES=!1,Do.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Do.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Do.QUOTA_EXCEEDED=!1,Do.QUOTA_MAYBE_EXCEEDED=!0,Do.UNKNOWN_ABORT=!0,Do.INCOMPATIBLE_DB_VERSION=!1,Do);function Fo(a,b,c,d,e){b=b===void 0?{}:b;c=c===void 0?Ao[a]:c;d=d===void 0?Co[a]:d;e=e===void 0?Eo[a]:e;V.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:self.document===void 0,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Fo.prototype)}
x(Fo,V);function Go(a,b){Fo.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Ao.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Go.prototype)}
x(Go,Fo);function Ho(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Ho.prototype)}
x(Ho,Error);var Io=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Jo(a,b,c,d){b=wo(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Fo)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if(e.name==="QuotaExceededError")return new Fo("QUOTA_EXCEEDED",a);if(Zc&&e.name==="UnknownError")return new Fo("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Ho)return new Fo("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if(e.name==="InvalidStateError"&&Io.some(function(f){return e.message.includes(f)}))return new Fo("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if(e.name==="AbortError")return new Fo("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",md:e.name})];e.level="WARNING";return e}
function Ko(a,b,c){var d=lo();return new Fo("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:d==null?void 0:d.hasSucceededOnce}})}
;function Lo(a){if(!a)throw Error();throw a;}
function Mo(a){return a}
function No(a){this.h=a}
function Oo(a){function b(e){if(d.state.status==="PENDING"){d.state={status:"REJECTED",reason:e};e=v(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if(d.state.status==="PENDING"){d.state={status:"FULFILLED",value:e};e=v(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Oo.all=function(a){return new Oo(new No(function(b,c){var d=[],e=a.length;e===0&&b(d);for(var f={qb:0};f.qb<a.length;f={qb:f.qb},++f.qb)Oo.resolve(a[f.qb]).then(function(g){return function(h){d[g.qb]=h;e--;e===0&&b(d)}}(f)).catch(function(g){c(g)})}))};
Oo.resolve=function(a){return new Oo(new No(function(b,c){a instanceof Oo?a.then(b,c):b(a)}))};
Oo.reject=function(a){return new Oo(new No(function(b,c){c(a)}))};
Oo.prototype.then=function(a,b){var c=this,d=a!=null?a:Mo,e=b!=null?b:Lo;return new Oo(new No(function(f,g){c.state.status==="PENDING"?(c.h.push(function(){Po(c,c,d,f,g)}),c.i.push(function(){Qo(c,c,e,f,g)})):c.state.status==="FULFILLED"?Po(c,c,d,f,g):c.state.status==="REJECTED"&&Qo(c,c,e,f,g)}))};
Oo.prototype.catch=function(a){return this.then(void 0,a)};
function Po(a,b,c,d,e){try{if(a.state.status!=="FULFILLED")throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Oo?Ro(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Qo(a,b,c,d,e){try{if(a.state.status!=="REJECTED")throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Oo?Ro(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ro(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Oo?Ro(a,b,f,d,e):d(f)},function(f){e(f)})}
;function So(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function To(a){return new Promise(function(b,c){So(a,b,c)})}
function Uo(a){return new Oo(new No(function(b,c){So(a,b,c)}))}
;function Vo(a,b){return new Oo(new No(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Wo=window,W=Wo.ytcsi&&Wo.ytcsi.now?Wo.ytcsi.now:Wo.performance&&Wo.performance.timing&&Wo.performance.now&&Wo.performance.timing.navigationStart?function(){return Wo.performance.timing.navigationStart+Wo.performance.now()}:function(){return(new Date).getTime()};function Xo(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(W());this.i=!1}
p=Xo.prototype;p.add=function(a,b,c){return Yo(this,[a],{mode:"readwrite",la:!0},function(d){return d.objectStore(a).add(b,c)})};
p.clear=function(a){return Yo(this,[a],{mode:"readwrite",la:!0},function(b){return b.objectStore(a).clear()})};
p.close=function(){this.h.close();var a;((a=this.options)==null?0:a.closed)&&this.options.closed()};
p.count=function(a,b){return Yo(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).count(b)})};
function Zo(a,b,c){a=a.h.createObjectStore(b,c);return new $o(a)}
p.delete=function(a,b){return Yo(this,[a],{mode:"readwrite",la:!0},function(c){return c.objectStore(a).delete(b)})};
p.get=function(a,b){return Yo(this,[a],{mode:"readonly",la:!0},function(c){return c.objectStore(a).get(b)})};
function ap(a,b,c){return Yo(a,[b],{mode:"readwrite",la:!0},function(d){d=d.objectStore(b);return Uo(d.h.put(c,void 0))})}
p.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function Yo(a,b,c,d){var e,f,g,h,k,l,m,n,r,t,w,y;return A(function(z){switch(z.h){case 1:var G={mode:"readonly",la:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};typeof c==="string"?G.mode=c:Object.assign(G,c);e=G;a.transactionCount++;f=e.la?3:1;g=0;case 2:if(h){z.F(4);break}g++;k=Math.round(W());ya(z,5);l=a.h.transaction(b,e.mode);G=z.yield;var I=new bp(l);I=cp(I,d);return G.call(z,I,7);case 7:return m=z.i,n=Math.round(W()),dp(a,k,n,g,void 0,b.join(),e),z.return(m);case 5:r=za(z);t=Math.round(W());w=Jo(r,
a.h.name,b.join(),a.h.version);if((y=w instanceof Fo&&!w.h)||g>=f)dp(a,k,t,g,w,b.join(),e),h=w;z.F(2);break;case 4:return z.return(Promise.reject(h))}})}
function dp(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Fo&&(e.type==="QUOTA_EXCEEDED"||e.type==="QUOTA_MAYBE_EXCEEDED")&&uo("QUOTA_EXCEEDED",{dbName:wo(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Fo&&e.type==="UNKNOWN_ABORT"&&(c-=a.j,c<0&&c>=2147483648&&(c=0),uo("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),ep(a,!1,d,f,b,g.tag),to(e)):ep(a,!0,d,f,b,g.tag)}
function ep(a,b,c,d,e,f){uo("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:f===void 0?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
p.getName=function(){return this.h.name};
function $o(a){this.h=a}
p=$o.prototype;p.add=function(a,b){return Uo(this.h.add(a,b))};
p.autoIncrement=function(){return this.h.autoIncrement};
p.clear=function(){return Uo(this.h.clear()).then(function(){})};
function fp(a,b,c){a.h.createIndex(b,c,{unique:!1})}
p.count=function(a){return Uo(this.h.count(a))};
function gp(a,b){return hp(a,{query:b},function(c){return c.delete().then(function(){return ip(c)})}).then(function(){})}
p.delete=function(a){return a instanceof IDBKeyRange?gp(this,a):Uo(this.h.delete(a))};
p.get=function(a){return Uo(this.h.get(a))};
p.index=function(a){try{return new jp(this.h.index(a))}catch(b){if(b instanceof Error&&b.name==="NotFoundError")throw new Ho(a,this.h.name);throw b;}};
p.getName=function(){return this.h.name};
p.keyPath=function(){return this.h.keyPath};
function hp(a,b,c){a=a.h.openCursor(b.query,b.direction);return kp(a).then(function(d){return Vo(d,c)})}
function bp(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Fo;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(k===null)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function cp(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return v(d).next().value})}
bp.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Fo("EXPLICIT_ABORT");};
bp.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new $o(a),this.i.set(a,b));return b};
function jp(a){this.h=a}
p=jp.prototype;p.count=function(a){return Uo(this.h.count(a))};
p.delete=function(a){return lp(this,{query:a},function(b){return b.delete().then(function(){return ip(b)})})};
p.get=function(a){return Uo(this.h.get(a))};
p.keyPath=function(){return this.h.keyPath};
p.unique=function(){return this.h.unique};
function lp(a,b,c){a=a.h.openCursor(b.query===void 0?null:b.query,b.direction===void 0?"next":b.direction);return kp(a).then(function(d){return Vo(d,c)})}
function mp(a,b){this.request=a;this.cursor=b}
function kp(a){return Uo(a).then(function(b){return b?new mp(a,b):null})}
function ip(a){a.cursor.continue(void 0);return kp(a.request)}
mp.prototype.delete=function(){return Uo(this.cursor.delete()).then(function(){})};
mp.prototype.getValue=function(){return this.cursor.value};
mp.prototype.update=function(a){return Uo(this.cursor.update(a))};function np(a,b,c){return new Promise(function(d,e){function f(){r||(r=new Xo(g.result,{closed:n}));return r}
var g=b!==void 0?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Ld,k=c.blocking,l=c.bf,m=c.upgrade,n=c.closed,r;g.addEventListener("upgradeneeded",function(t){try{if(t.newVersion===null)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(g.transaction===null)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&t.dataLoss!=="none"&&uo("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:wo(a)});var w=f(),y=new bp(g.transaction);
m&&m(w,function(z){return t.oldVersion<z&&t.newVersion>=z},y);
y.done.catch(function(z){e(z)})}catch(z){e(z)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){uo("IDB_UNEXPECTEDLY_CLOSED",{dbName:wo(a),dbVersion:t.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function op(a,b,c){c=c===void 0?{}:c;return np(a,b,c)}
function pp(a,b){b=b===void 0?{}:b;var c,d,e,f;return A(function(g){if(g.h==1)return ya(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Ld)&&c.addEventListener("blocked",function(){e()}),g.yield(To(c),4);
if(g.h!=2)g.h=0,g.o=0;else throw f=za(g),Jo(f,a,"",-1);})}
;function qp(a,b){this.name=a;this.options=b;this.j=!0;this.D=this.o=0}
qp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return op(a,b,c)};
qp.prototype.delete=function(a){a=a===void 0?{}:a;return pp(this.name,a)};
function rp(a,b){return new Fo("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function sp(a,b){if(!b)throw Ko("openWithToken",wo(a.name));return a.open()}
qp.prototype.open=function(){function a(){var f,g,h,k,l,m,n,r,t,w;return A(function(y){switch(y.h){case 1:return g=(f=Error().stack)!=null?f:"",ya(y,2),y.yield(c.i(c.name,c.options.version,e),4);case 4:for(var z=h=y.i,G=c.options,I=[],M=v(Object.keys(G.wb)),O=M.next();!O.done;O=M.next()){O=O.value;var ta=G.wb[O],lb=ta.Ee===void 0?Number.MAX_VALUE:ta.Ee;!(z.h.version>=ta.Db)||z.h.version>=lb||z.h.objectStoreNames.contains(O)||I.push(O)}k=I;if(k.length===0){y.F(5);break}l=Object.keys(c.options.wb);
m=h.objectStoreNames();if(c.D<zm("ytidb_reopen_db_retries",0))return c.D++,h.close(),to(new Fo("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),y.return(a());if(!(c.o<zm("ytidb_remake_db_retries",1))){y.F(6);break}c.o++;return y.yield(c.delete(),7);case 7:return to(new Fo("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:l,foundObjectStores:m})),y.return(a());case 6:throw new Go(m,l);case 5:return y.return(h);case 2:n=za(y);
if(n instanceof DOMException?n.name!=="VersionError":"DOMError"in self&&n instanceof DOMError?n.name!=="VersionError":!(n instanceof Object&&"message"in n)||n.message!=="An attempt was made to open a database using a lower version than the existing version."){y.F(8);break}return y.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:r=y.i;t=r.h.version;if(c.options.version!==void 0&&t>c.options.version+1)throw r.close(),c.j=!1,rp(c,t);return y.return(r);case 8:throw b(),n instanceof
Error&&!U("ytidb_async_stack_killswitch")&&(n.stack=n.stack+"\n"+g.substring(g.indexOf("\n")+1)),Jo(n,c.name,"",(w=c.options.version)!=null?w:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw rp(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,bf:b,upgrade:this.options.upgrade};return this.h=d=a()};var tp=new qp("YtIdbMeta",{wb:{databases:{Db:1}},upgrade:function(a,b){b(1)&&Zo(a,"databases",{keyPath:"actualName"})}});
function up(a,b){var c;return A(function(d){if(d.h==1)return d.yield(sp(tp,b),2);c=d.i;return d.return(Yo(c,["databases"],{la:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Uo(f.h.put(a,void 0)).then(function(){})})}))})}
function vp(a,b){var c;return A(function(d){if(d.h==1)return a?d.yield(sp(tp,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function wp(a,b){var c,d;return A(function(e){return e.h==1?(c=[],e.yield(sp(tp,b),2)):e.h!=3?(d=e.i,e.yield(Yo(d,["databases"],{la:!0,mode:"readonly"},function(f){c.length=0;return hp(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return ip(g)})}),3)):e.return(c)})}
function xp(a){return wp(function(b){return b.publicName==="LogsDatabaseV2"&&b.userIdentifier!==void 0},a)}
function yp(a,b,c){return wp(function(d){return c?d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):d.userIdentifier!==void 0&&!a.includes(d.userIdentifier)},b)}
function zp(a){var b,c;return A(function(d){if(d.h==1)return b=Bn("YtIdbMeta hasAnyMeta other"),d.yield(wp(function(e){return e.userIdentifier!==void 0&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(c.length>0)})}
;var Ap,Bp=new function(){}(new function(){});
function Cp(){var a,b,c,d;return A(function(e){switch(e.h){case 1:a=lo();if((b=a)==null?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=xo)f=/WebKit\/([0-9]+)/.exec(Hc()),f=!!(f&&parseInt(f[1],10)>=600);f&&(f=/WebKit\/([0-9]+)/.exec(Hc()),f=!(f&&parseInt(f[1],10)>=602));if(f||Tc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
ya(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(up(d,Bp),4);case 4:return e.yield(vp("yt-idb-test-do-not-use",Bp),5);case 5:return e.return(!0);case 2:return za(e),e.return(!1)}})}
function Dp(){if(Ap!==void 0)return Ap;oo=!0;return Ap=Cp().then(function(a){oo=!1;var b;if((b=ko())!=null&&b.h){var c;b={hasSucceededOnce:((c=lo())==null?void 0:c.hasSucceededOnce)||a};var d;(d=ko())==null||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Ep(){return E("ytglobal.idbToken_")||void 0}
function Fp(){var a=Ep();return a?Promise.resolve(a):Dp().then(function(b){(b=b?Bp:void 0)&&D("ytglobal.idbToken_",b);return b})}
;var Gp=0;function Hp(a,b){Gp||(Gp=Kj.qa(function(){var c,d,e,f,g;return A(function(h){switch(h.h){case 1:return h.yield(Fp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;ya(h,3);return h.yield(yp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.F(6);break}f=e[0];return h.yield(pp(f.actualName),7);case 7:return h.yield(vp(f.actualName,c),6);case 6:h.h=4;h.o=0;break;case 3:g=za(h),to(g),d=!1;case 4:Kj.ra(Gp),Gp=0,d&&Hp(a,b),h.h=0}})}))}
function Ip(){var a;return A(function(b){return b.h==1?b.yield(Fp(),2):(a=b.i)?b.return(zp(a)):b.return(!1)})}
new vj;function Jp(a){if(!An())throw a=new Fo("AUTH_INVALID",{dbName:a}),to(a),a;var b=Bn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Kp(a,b,c,d){var e,f,g,h,k,l;return A(function(m){switch(m.h){case 1:return f=(e=Error().stack)!=null?e:"",m.yield(Fp(),2);case 2:g=m.i;if(!g)throw h=Ko("openDbImpl",a,b),U("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),to(h),h;vo(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Jp(a);ya(m,3);return m.yield(up(k,g),5);case 5:return m.yield(op(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=za(m),ya(m,7),m.yield(vp(k.actualName,
g),9);case 9:m.h=8;m.o=0;break;case 7:za(m);case 8:throw l;}})}
function Lp(a,b,c){c=c===void 0?{}:c;return Kp(a,b,!1,c)}
function Mp(a,b,c){c=c===void 0?{}:c;return Kp(a,b,!0,c)}
function Np(a,b){b=b===void 0?{}:b;var c,d;return A(function(e){if(e.h==1)return e.yield(Fp(),2);if(e.h!=3){c=e.i;if(!c)return e.return();vo(a);d=Jp(a);return e.yield(pp(d.actualName,b),3)}return e.yield(vp(d.actualName,c),0)})}
function Op(a,b,c){a=a.map(function(d){return A(function(e){return e.h==1?e.yield(pp(d.actualName,b),2):e.yield(vp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Pp(){var a=a===void 0?{}:a;var b,c;return A(function(d){if(d.h==1)return d.yield(Fp(),2);if(d.h!=3){b=d.i;if(!b)return d.return();vo("LogsDatabaseV2");return d.yield(xp(b),3)}c=d.i;return d.yield(Op(c,a,b),0)})}
function Qp(a,b){b=b===void 0?{}:b;var c;return A(function(d){if(d.h==1)return d.yield(Fp(),2);if(d.h!=3){c=d.i;if(!c)return d.return();vo(a);return d.yield(pp(a,b),3)}return d.yield(vp(a,c),0)})}
;function Rp(a,b){qp.call(this,a,b);this.options=b;vo(a)}
x(Rp,qp);function Sp(a,b){var c;return function(){c||(c=new Rp(a,b));return c}}
Rp.prototype.i=function(a,b,c){c=c===void 0?{}:c;return(this.options.shared?Mp:Lp)(a,b,Object.assign({},c))};
Rp.prototype.delete=function(a){a=a===void 0?{}:a;return(this.options.shared?Qp:Np)(this.name,a)};
function Tp(a,b){return Sp(a,b)}
;var Up={},Vp=Tp("ytGcfConfig",{wb:(Up.coldConfigStore={Db:1},Up.hotConfigStore={Db:1},Up),shared:!1,upgrade:function(a,b){b(1)&&(fp(Zo(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),fp(Zo(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Wp(a){return sp(Vp(),a)}
function Xp(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:W()},g.yield(Wp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(ap(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Yp(a,b,c,d){var e,f,g;return A(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:W()},h.yield(Wp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(ap(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Zp(a){var b,c;return A(function(d){return d.h==1?d.yield(Wp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Yo(b,["coldConfigStore"],{mode:"readwrite",la:!0},function(e){return lp(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function $p(a){var b,c;return A(function(d){return d.h==1?d.yield(Wp(a),2):d.h!=3?(b=d.i,c=void 0,d.yield(Yo(b,["hotConfigStore"],{mode:"readwrite",la:!0},function(e){return lp(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function aq(){L.call(this);this.i=[];this.h=[];var a=E("yt.gcf.config.hotUpdateCallbacks");a?(this.i=[].concat(ja(a)),this.h=a):(this.h=[],D("yt.gcf.config.hotUpdateCallbacks",this.h))}
x(aq,L);aq.prototype.ba=function(){for(var a=v(this.i),b=a.next();!b.done;b=a.next()){var c=this.h;b=c.indexOf(b.value);b>=0&&c.splice(b,1)}this.i.length=0;L.prototype.ba.call(this)};function bq(){this.h=0;this.i=new aq}
function cq(){var a;return(a=E("yt.gcf.config.hotConfigGroup"))!=null?a:S("RAW_HOT_CONFIG_GROUP")}
function dq(a,b,c){var d,e,f;return A(function(g){switch(g.h){case 1:if(!U("start_client_gcf")){g.F(0);break}c&&(a.j=c,D("yt.gcf.config.hotConfigGroup",a.j||null));a.o(b);d=Ep();if(!d){g.F(3);break}if(c){g.F(4);break}return g.yield($p(d),5);case 5:e=g.i,c=(f=e)==null?void 0:f.config;case 4:return g.yield(Xp(c,b,d),3);case 3:if(c)for(var h=c,k=v(a.i.h),l=k.next();!l.done;l=k.next())l=l.value,l(h);g.h=0}})}
function eq(a,b,c){var d,e,f,g;return A(function(h){if(h.h==1){if(!U("start_client_gcf"))return h.F(0);a.coldHashData=b;D("yt.gcf.config.coldHashData",a.coldHashData||null);return(d=Ep())?c?h.F(4):h.yield(Zp(d),5):h.F(0)}h.h!=4&&(e=h.i,c=(f=e)==null?void 0:f.config);if(!c)return h.F(0);g=c.configData;return h.yield(Yp(c,b,g,d),0)})}
function fq(){if(!bq.h){var a=new bq;bq.h=a}a=bq.h;var b=W()-a.h;if(!(a.h!==0&&b<zm("send_config_hash_timer"))){b=E("yt.gcf.config.coldConfigData");var c=E("yt.gcf.config.hotHashData"),d=E("yt.gcf.config.coldHashData");b&&c&&d&&(a.h=W());return{coldConfigData:b,hotHashData:c,coldHashData:d}}}
bq.prototype.o=function(a){this.hotHashData=a;D("yt.gcf.config.hotHashData",this.hotHashData||null)};function gq(){return"INNERTUBE_API_KEY"in Zl&&"INNERTUBE_API_VERSION"in Zl}
function hq(){return{innertubeApiKey:S("INNERTUBE_API_KEY"),innertubeApiVersion:S("INNERTUBE_API_VERSION"),ee:S("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),ed:S("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Vg:S("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:S("INNERTUBE_CONTEXT_CLIENT_VERSION"),he:S("INNERTUBE_CONTEXT_HL"),ge:S("INNERTUBE_CONTEXT_GL"),je:S("INNERTUBE_HOST_OVERRIDE")||"",le:!!S("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),ke:!!S("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:S("SERIALIZED_CLIENT_CONFIG_DATA")}}
function iq(a){var b={client:{hl:a.he,gl:a.ge,clientName:a.ed,clientVersion:a.innertubeContextClientVersion,configInfo:a.ee}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=C.devicePixelRatio;c&&c!=1&&(b.client.screenDensityFloat=String(c));c=S("EXPERIMENTS_TOKEN","");c!==""&&(b.client.experimentsToken=c);c=Am();c.length>0&&(b.request={internalExperimentFlags:c});c=a.ed;if((c==="WEB"||c==="MWEB"||c===1||c===2)&&b){var d;b.client.mainAppWebInfo=(d=b.client.mainAppWebInfo)!=
null?d:{};b.client.mainAppWebInfo.webDisplayMode=dn()}(d=E("yt.embedded_player.embed_url"))&&b&&(b.thirdParty={embedUrl:d});var e;if(U("web_log_memory_total_kbytes")&&((e=C.navigator)==null?0:e.deviceMemory)){var f;e=(f=C.navigator)==null?void 0:f.deviceMemory;b&&(b.client.memoryTotalKbytes=""+e*1E6)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);(a=yn())&&b&&(b.client.connectionType=a);U("web_log_effective_connection_type")&&
(a=zn())&&b&&(b.client.effectiveConnectionType=a);U("start_client_gcf")&&(e=fq())&&(a=e.coldConfigData,f=e.coldHashData,e=e.hotHashData,b&&(b.client.configInfo=b.client.configInfo||{},a&&(b.client.configInfo.coldConfigData=a),f&&(b.client.configInfo.coldHashData=f),e&&(b.client.configInfo.hotHashData=e)));S("DELEGATED_SESSION_ID")&&!U("pageid_as_header_web")&&(b.user={onBehalfOfUser:S("DELEGATED_SESSION_ID")});!U("fill_delegate_context_in_gel_killswitch")&&(a=S("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&
(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;f=a.assign;e=b.client;d={};c=v(Object.entries(mm(S("DEVICE",""))));for(var g=c.next();!g.done;g=c.next()){var h=v(g.value);g=h.next().value;h=h.next().value;g==="cbrand"?d.deviceMake=h:g==="cmodel"?d.deviceModel=h:g==="cbr"?d.browserName=h:g==="cbrver"?d.browserVersion=h:g==="cos"?d.osName=h:g==="cosver"?d.osVersion=h:g==="cplatform"&&(d.platform=h)}b.client=f.call(a,e,d);return b}
function jq(a,b,c){c=c===void 0?{}:c;var d={};S("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":S("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||S("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||S("AUTHORIZATION");b||(a?b="Bearer "+E("gapi.auth.getToken")().Ng:(a=gn(fn()),U("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
;var kq=typeof TextEncoder!=="undefined"?new TextEncoder:null,lq=kq?function(a){return kq.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function mq(a,b){this.version=a;this.args=b}
mq.prototype.serialize=function(){return{version:this.version,args:this.args}};function nq(a,b){this.topic=a;this.h=b}
nq.prototype.toString=function(){return this.topic};var oq=E("ytPubsub2Pubsub2Instance")||new N;N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.Rb;N.prototype.publish=N.prototype.kb;N.prototype.clear=N.prototype.clear;D("ytPubsub2Pubsub2Instance",oq);var pq=E("ytPubsub2Pubsub2SubscribedKeys")||{};D("ytPubsub2Pubsub2SubscribedKeys",pq);var qq=E("ytPubsub2Pubsub2TopicToKeys")||{};D("ytPubsub2Pubsub2TopicToKeys",qq);var rq=E("ytPubsub2Pubsub2IsAsync")||{};D("ytPubsub2Pubsub2IsAsync",rq);
D("ytPubsub2Pubsub2SkipSubKey",null);function sq(a,b){var c=tq();c&&c.publish.call(c,a.toString(),a,b)}
function uq(a){var b=vq,c=tq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=E("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(pq[d])try{if(f&&b instanceof nq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Bd){var l=new h;h.Bd=l.version}var m=h.Bd}catch(z){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{m=Reflect;var n=m.construct;
var r=k.args,t=r.length;if(t>0){var w=Array(t);for(k=0;k<t;k++)w[k]=r[k];var y=w}else y=[];f=n.call(m,h,y)}catch(z){throw z.message="yt.pubsub2.Data.deserialize(): "+z.message,z;}}catch(z){throw z.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+z.message,z;}a.call(window,f)}catch(z){em(z)}},rq[b.toString()]?E("yt.scheduler.instance")?Kj.qa(g):wm(g,0):g())});
pq[d]=!0;qq[b.toString()]||(qq[b.toString()]=[]);qq[b.toString()].push(d);return d}
function wq(){var a=xq,b=uq(function(c){a.apply(void 0,arguments);yq(b)});
return b}
function yq(a){var b=tq();b&&(typeof a==="number"&&(a=[a]),Kb(a,function(c){b.unsubscribeByKey(c);delete pq[c]}))}
function tq(){return E("ytPubsub2Pubsub2Instance")}
;function zq(a,b,c){c=c===void 0?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&sq("meta_logging_csi_event",{timerName:a,nh:b})}
;var Aq=void 0,Bq=void 0;function Cq(){Bq||(Bq=yl(S("WORKER_SERIALIZATION_URL")));return Bq||void 0}
function Dq(){var a=Cq();Aq||a===void 0||(Aq=new Worker(ib(a),void 0));return Aq}
;var Eq=zm("max_body_size_to_compress",5E5),Fq=zm("min_body_size_to_compress",500),Gq=!0,Hq=0,Iq=0,Jq=zm("compression_performance_threshold_lr",250),Kq=zm("slow_compressions_before_abandon_count",4),Lq=!1,Mq=new Map,Nq=1,Oq=!0;function Pq(){if(typeof Worker==="function"&&Cq()&&!Lq){var a=function(c){c=c.data;if(c.op==="gzippedGelBatch"){var d=Mq.get(c.key);d&&(Qq(c.gzippedBatch,d.latencyPayload,d.url,d.options,d.sendFn),Mq.delete(c.key))}},b=Dq();
b&&(b.addEventListener("message",a),b.onerror=function(){Mq.clear()},Lq=!0)}}
function Rq(a,b,c,d,e){e=e===void 0?!1:e;var f={startTime:W(),ticks:{},infos:{}};if(Gq)try{var g=Sq(b);if(g!=null&&(g>Eq||g<Fq))d(a,c);else{if(U("gzip_gel_with_worker")&&(U("initial_gzip_use_main_thread")&&!Oq||!U("initial_gzip_use_main_thread"))){Lq||Pq();var h=Dq();if(h&&!e){Mq.set(Nq,{latencyPayload:f,url:a,options:c,sendFn:d});h.postMessage({op:"gelBatchToGzip",serializedBatch:b,key:Nq});Nq++;return}}var k=xl(lq(b));Qq(k,f,a,c,d)}}catch(l){fm(l),d(a,c)}else d(a,c)}
function Qq(a,b,c,d,e){Oq=!1;var f=W();b.ticks.gelc=f;Iq++;U("disable_compression_due_to_performance_degredation")&&f-b.startTime>=Jq&&(Hq++,U("abandon_compression_after_N_slow_zips")?Iq===zm("compression_disable_point")&&Hq>Kq&&(Gq=!1):Gq=!1);Tq(b);d.headers||(d.headers={});d.headers["Content-Encoding"]="gzip";d.postBody=a;d.postParams=void 0;e(c,d)}
function Uq(a){var b=b===void 0?!1:b;var c=c===void 0?!1:c;var d=W(),e={startTime:d,ticks:{},infos:{}},f=b?E("yt.logging.gzipForFetch",!1):!0;if(Gq&&f){if(!a.body)return a;try{var g=c?a.body:typeof a.body==="string"?a.body:JSON.stringify(a.body);f=g;if(!c&&typeof g==="string"){var h=Sq(g);if(h!=null&&(h>Eq||h<Fq))return a;c=b?{level:1}:void 0;f=xl(lq(g),c);var k=W();e.ticks.gelc=k;if(b){Iq++;if((U("disable_compression_due_to_performance_degredation")||U("disable_compression_due_to_performance_degradation_lr"))&&
k-d>=Jq)if(Hq++,U("abandon_compression_after_N_slow_zips")||U("abandon_compression_after_N_slow_zips_lr")){b=Hq/Iq;var l=Kq/zm("compression_disable_point");Iq>0&&Iq%zm("compression_disable_point")===0&&b>=l&&(Gq=!1)}else Gq=!1;Tq(e)}}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=f;return a}catch(m){return fm(m),a}}else return a}
function Sq(a){try{return(new Blob(a.split(""))).size}catch(b){return fm(b),null}}
function Tq(a){U("gel_compression_csi_killswitch")||!U("log_gel_compression_latency")&&!U("log_gel_compression_latency_lr")||zq("gel_compression",a,{sampleRate:.1})}
;function Vq(a){a=Object.assign({},a);delete a.Authorization;var b=pg();if(b){var c=new Oj;c.update(S("INNERTUBE_API_KEY"));c.update(b);a.hash=bd(c.digest(),3)}return a}
;var Wq;function Xq(){Wq||(Wq=new jo("yt.innertube"));return Wq}
function Yq(a,b,c,d){if(d)return null;d=Xq().get("nextId",!0)||1;var e=Xq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Vq(c),requestTime:Math.round(W())};Xq().set("nextId",d+1,86400,!0);Xq().set("requests",e,86400,!0);return d}
function Zq(a){var b=Xq().get("requests",!0)||{};delete b[a];Xq().set("requests",b,86400,!0)}
function $q(a){var b=Xq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(Math.round(W())-d.requestTime<6E4)){var e=d.authState,f=Vq(jq(!1));Dg(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(W())),ar(a,d.method,e,{}));delete b[c]}}Xq().set("requests",b,86400,!0)}}
;function br(a){this.Vb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ob=function(){};
this.now=Date.now;this.Gb=!1;var b;this.xd=(b=a.xd)!=null?b:100;var c;this.sd=(c=a.sd)!=null?c:1;var d;this.pd=(d=a.pd)!=null?d:2592E6;var e;this.od=(e=a.od)!=null?e:12E4;var f;this.rd=(f=a.rd)!=null?f:5E3;var g;this.Y=(g=a.Y)!=null?g:void 0;this.ac=!!a.ac;var h;this.Yb=(h=a.Yb)!=null?h:.1;var k;this.jc=(k=a.jc)!=null?k:10;a.handleError&&(this.handleError=a.handleError);a.ob&&(this.ob=a.ob);a.Gb&&(this.Gb=a.Gb);a.Vb&&(this.Vb=a.Vb);this.Z=a.Z;this.Ea=a.Ea;this.ha=a.ha;this.fa=a.fa;this.sendFn=a.sendFn;
this.Ic=a.Ic;this.Fc=a.Fc;cr(this)&&(!this.Z||this.Z("networkless_logging"))&&dr(this)}
function dr(a){cr(a)&&!a.Gb&&(a.h=!0,a.ac&&Math.random()<=a.Yb&&a.ha.Md(a.Y),er(a),a.fa.wa()&&a.Qb(),a.fa.listen(a.Ic,a.Qb.bind(a)),a.fa.listen(a.Fc,a.Sc.bind(a)))}
p=br.prototype;p.writeThenSend=function(a,b){var c=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.ha.set(d,this.Y).then(function(e){d.id=e;c.fa.wa()&&fr(c,d)}).catch(function(e){fr(c,d);
gr(c,e)})}else this.sendFn(a,b)};
p.sendThenWrite=function(a,b,c){var d=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Z&&this.Z("nwl_skip_retry")&&(e.skipRetry=c);if(this.fa.wa()||this.Z&&this.Z("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return A(function(k){if(k.h==1)return k.yield(d.ha.set(e,d.Y).catch(function(l){gr(d,l)}),2);
f(g,h);k.h=0})}}this.sendFn(a,b,e.skipRetry)}else this.ha.set(e,this.Y).catch(function(g){d.sendFn(a,b,e.skipRetry);
gr(d,g)})}else this.sendFn(a,b,this.Z&&this.Z("nwl_skip_retry")&&c)};
p.sendAndWrite=function(a,b){var c=this;b=b===void 0?{}:b;if(cr(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){d.id!==void 0?c.ha.nb(d.id,c.Y):e=!0;c.fa.fb&&c.Z&&c.Z("vss_network_hint")&&c.fa.fb(!0);f(g,h)};
this.sendFn(d.url,d.options,void 0,!0);this.ha.set(d,this.Y).then(function(g){d.id=g;e&&c.ha.nb(d.id,c.Y)}).catch(function(g){gr(c,g)})}else this.sendFn(a,b,void 0,!0)};
p.Qb=function(){var a=this;if(!cr(this))throw Error("IndexedDB is not supported: throttleSend");this.i||(this.i=this.Ea.qa(function(){var b;return A(function(c){if(c.h==1)return c.yield(a.ha.Zc("NEW",a.Y),2);if(c.h!=3)return b=c.i,b?c.yield(fr(a,b),3):(a.Sc(),c.return());a.i&&(a.i=0,a.Qb());c.h=0})},this.xd))};
p.Sc=function(){this.Ea.ra(this.i);this.i=0};
function fr(a,b){var c;return A(function(d){switch(d.h){case 1:if(!cr(a))throw Error("IndexedDB is not supported: immediateSend");if(b.id===void 0){d.F(2);break}return d.yield(a.ha.qe(b.id,a.Y),3);case 3:(c=d.i)||a.ob(Error("The request cannot be found in the database."));case 2:if(hr(a,b,a.pd)){d.F(4);break}a.ob(Error("Networkless Logging: Stored logs request expired age limit"));if(b.id===void 0){d.F(5);break}return d.yield(a.ha.nb(b.id,a.Y),5);case 5:return d.return();case 4:b.skipRetry||(b=ir(a,
b));if(!b){d.F(0);break}if(!b.skipRetry||b.id===void 0){d.F(8);break}return d.yield(a.ha.nb(b.id,a.Y),8);case 8:a.sendFn(b.url,b.options,!!b.skipRetry),d.h=0}})}
function ir(a,b){if(!cr(a))throw Error("IndexedDB is not supported: updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,l;return A(function(m){switch(m.h){case 1:g=jr(f);(h=kr(f))&&a.Z&&a.Z("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.Z&&a.Z("nwl_consider_error_code")&&g||a.Z&&!a.Z("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.jc)){m.F(2);break}if(!a.fa.nc){m.F(3);break}return m.yield(a.fa.nc(),3);case 3:if(a.fa.wa()){m.F(2);break}c(e,f);if(!a.Z||!a.Z("nwl_consider_error_code")||((k=b)==null?void 0:k.id)===void 0){m.F(6);
break}return m.yield(a.ha.Jc(b.id,a.Y,!1),6);case 6:return m.return();case 2:if(a.Z&&a.Z("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.jc)return m.return();a.potentialEsfErrorCounter++;if(((l=b)==null?void 0:l.id)===void 0){m.F(8);break}return b.sendCount<a.sd?m.yield(a.ha.Jc(b.id,a.Y,!0,h?!1:void 0),12):m.yield(a.ha.nb(b.id,a.Y),8);case 12:a.Ea.qa(function(){a.fa.wa()&&a.Qb()},a.rd);
case 8:c(e,f),m.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return A(function(h){if(h.h==1)return((g=b)==null?void 0:g.id)===void 0?h.F(2):h.yield(a.ha.nb(b.id,a.Y),2);a.fa.fb&&a.Z&&a.Z("vss_network_hint")&&a.fa.fb(!0);d(e,f);h.h=0})};
return b}
function hr(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function er(a){if(!cr(a))throw Error("IndexedDB is not supported: retryQueuedRequests");a.ha.Zc("QUEUED",a.Y).then(function(b){b&&!hr(a,b,a.od)?a.Ea.qa(function(){return A(function(c){if(c.h==1)return b.id===void 0?c.F(2):c.yield(a.ha.Jc(b.id,a.Y),2);er(a);c.h=0})}):a.fa.wa()&&a.Qb()})}
function gr(a,b){a.Ed&&!a.fa.wa()?a.Ed(b):a.handleError(b)}
function cr(a){return!!a.Y||a.Vb}
function jr(a){var b;return(a=a==null?void 0:(b=a.error)==null?void 0:b.code)&&a>=400&&a<=599?!1:!0}
function kr(a){var b;a=a==null?void 0:(b=a.error)==null?void 0:b.code;return!(a!==400&&a!==415)}
;var lr;
function mr(){if(lr)return lr();var a={};lr=Tp("LogsDatabaseV2",{wb:(a.LogsRequestsStore={Db:2},a),shared:!1,upgrade:function(b,c,d){c(2)&&Zo(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),fp(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return lr()}
;function nr(a){return sp(mr(),a)}
function or(a,b){var c,d,e,f;return A(function(g){if(g.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(nr(b),2);if(g.h!=3)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:S("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(ap(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=W();pr(c);return g.return(f)})}
function qr(a,b){var c,d,e,f,g,h,k,l;return A(function(m){if(m.h==1)return c={startTime:W(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(nr(b),2);if(m.h!=3)return d=m.i,e=S("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,W()],h=IDBKeyRange.bound(f,g),k="prev",U("use_fifo_for_networkless")&&(k="next"),l=void 0,m.yield(Yo(d,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(n){return lp(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:k},
function(r){r.getValue()&&(l=r.getValue(),a==="NEW"&&(l.status="QUEUED",r.update(l)))})}),3);
c.ticks.tc=W();pr(c);return m.return(l)})}
function rr(a,b){var c;return A(function(d){if(d.h==1)return d.yield(nr(b),2);c=d.i;return d.return(Yo(c,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Uo(f.h.put(g,void 0)).then(function(){return g})})}))})}
function sr(a,b,c,d){c=c===void 0?!0:c;var e;return A(function(f){if(f.h==1)return f.yield(nr(b),2);e=f.i;return f.return(Yo(e,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),d!==void 0&&(k.options.compress=d),Uo(h.h.put(k,void 0)).then(function(){return k})):Oo.resolve(void 0)})}))})}
function tr(a,b){var c;return A(function(d){if(d.h==1)return d.yield(nr(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function ur(a){var b,c;return A(function(d){if(d.h==1)return d.yield(nr(a),2);b=d.i;c=W()-2592E6;return d.yield(Yo(b,["LogsRequestsStore"],{mode:"readwrite",la:!0},function(e){return hp(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return ip(f)})})}),0)})}
function vr(){A(function(a){return a.yield(Pp(),0)})}
function pr(a){U("nwl_csi_killswitch")||zq("networkless_performance",a,{sampleRate:1})}
;var wr={accountStateChangeSignedIn:23,accountStateChangeSignedOut:24,delayedEventMetricCaptured:11,latencyActionBaselined:6,latencyActionInfo:7,latencyActionTicked:5,offlineTransferStatusChanged:2,offlineImageDownload:335,playbackStartStateChanged:9,systemHealthCaptured:3,mangoOnboardingCompleted:10,mangoPushNotificationReceived:230,mangoUnforkDbMigrationError:121,mangoUnforkDbMigrationSummary:122,mangoUnforkDbMigrationPreunforkDbVersionNumber:133,mangoUnforkDbMigrationPhoneMetadata:134,mangoUnforkDbMigrationPhoneStorage:135,
mangoUnforkDbMigrationStep:142,mangoAsyncApiMigrationEvent:223,mangoDownloadVideoResult:224,mangoHomepageVideoCount:279,mangoHomeV3State:295,mangoImageClientCacheHitEvent:273,sdCardStatusChanged:98,framesDropped:12,thumbnailHovered:13,deviceRetentionInfoCaptured:14,thumbnailLoaded:15,backToAppEvent:318,streamingStatsCaptured:17,offlineVideoShared:19,appCrashed:20,youThere:21,offlineStateSnapshot:22,mdxSessionStarted:25,mdxSessionConnected:26,mdxSessionDisconnected:27,bedrockResourceConsumptionSnapshot:28,
nextGenWatchWatchSwiped:29,kidsAccountsSnapshot:30,zeroStepChannelCreated:31,tvhtml5SearchCompleted:32,offlineSharePairing:34,offlineShareUnlock:35,mdxRouteDistributionSnapshot:36,bedrockRepetitiveActionTimed:37,unpluggedDegradationInfo:229,uploadMp4HeaderMoved:38,uploadVideoTranscoded:39,uploadProcessorStarted:46,uploadProcessorEnded:47,uploadProcessorReady:94,uploadProcessorRequirementPending:95,uploadProcessorInterrupted:96,uploadFrontendEvent:241,assetPackDownloadStarted:41,assetPackDownloaded:42,
assetPackApplied:43,assetPackDeleted:44,appInstallAttributionEvent:459,playbackSessionStopped:45,adBlockerMessagingShown:48,distributionChannelCaptured:49,dataPlanCpidRequested:51,detailedNetworkTypeCaptured:52,sendStateUpdated:53,receiveStateUpdated:54,sendDebugStateUpdated:55,receiveDebugStateUpdated:56,kidsErrored:57,mdxMsnSessionStatsFinished:58,appSettingsCaptured:59,mdxWebSocketServerHttpError:60,mdxWebSocketServer:61,startupCrashesDetected:62,coldStartInfo:435,offlinePlaybackStarted:63,liveChatMessageSent:225,
liveChatUserPresent:434,liveChatBeingModerated:457,liveCreationCameraUpdated:64,liveCreationEncodingCaptured:65,liveCreationError:66,liveCreationHealthUpdated:67,liveCreationVideoEffectsCaptured:68,liveCreationStageOccured:75,liveCreationBroadcastScheduled:123,liveCreationArchiveReplacement:149,liveCreationCostreamingConnection:421,liveCreationStreamWebrtcStats:288,mdxSessionRecoveryStarted:69,mdxSessionRecoveryCompleted:70,mdxSessionRecoveryStopped:71,visualElementShown:72,visualElementHidden:73,
visualElementGestured:78,visualElementStateChanged:208,screenCreated:156,playbackAssociated:202,visualElementAttached:215,playbackContextEvent:214,cloudCastingPlaybackStarted:74,webPlayerApiCalled:76,tvhtml5AccountDialogOpened:79,foregroundHeartbeat:80,foregroundHeartbeatScreenAssociated:111,kidsOfflineSnapshot:81,mdxEncryptionSessionStatsFinished:82,playerRequestCompleted:83,liteSchedulerStatistics:84,mdxSignIn:85,spacecastMetadataLookupRequested:86,spacecastBatchLookupRequested:87,spacecastSummaryRequested:88,
spacecastPlayback:89,spacecastDiscovery:90,tvhtml5LaunchUrlComponentChanged:91,mdxBackgroundPlaybackRequestCompleted:92,mdxBrokenAdditionalDataDeviceDetected:93,tvhtml5LocalStorage:97,tvhtml5DeviceStorageStatus:147,autoCaptionsAvailable:99,playbackScrubbingEvent:339,flexyState:100,interfaceOrientationCaptured:101,mainAppBrowseFragmentCache:102,offlineCacheVerificationFailure:103,offlinePlaybackExceptionDigest:217,vrCopresenceStats:104,vrCopresenceSyncStats:130,vrCopresenceCommsStats:137,vrCopresencePartyStats:153,
vrCopresenceEmojiStats:213,vrCopresenceEvent:141,vrCopresenceFlowTransitEvent:160,vrCowatchPartyEvent:492,vrCowatchUserStartOrJoinEvent:504,vrPlaybackEvent:345,kidsAgeGateTracking:105,offlineDelayAllowedTracking:106,mainAppAutoOfflineState:107,videoAsThumbnailDownload:108,videoAsThumbnailPlayback:109,liteShowMore:110,renderingError:118,kidsProfilePinGateTracking:119,abrTrajectory:124,scrollEvent:125,streamzIncremented:126,kidsProfileSwitcherTracking:127,kidsProfileCreationTracking:129,buyFlowStarted:136,
mbsConnectionInitiated:138,mbsPlaybackInitiated:139,mbsLoadChildren:140,liteProfileFetcher:144,mdxRemoteTransaction:146,reelPlaybackError:148,reachabilityDetectionEvent:150,mobilePlaybackEvent:151,courtsidePlayerStateChanged:152,musicPersistentCacheChecked:154,musicPersistentCacheCleared:155,playbackInterrupted:157,playbackInterruptionResolved:158,fixFopFlow:159,anrDetection:161,backstagePostCreationFlowEnded:162,clientError:163,gamingAccountLinkStatusChanged:164,liteHousewarming:165,buyFlowEvent:167,
kidsParentalGateTracking:168,kidsSignedOutSettingsStatus:437,kidsSignedOutPauseHistoryFixStatus:438,tvhtml5WatchdogViolation:444,ypcUpgradeFlow:169,yongleStudy:170,ypcUpdateFlowStarted:171,ypcUpdateFlowCancelled:172,ypcUpdateFlowSucceeded:173,ypcUpdateFlowFailed:174,liteGrowthkitPromo:175,paymentFlowStarted:341,transactionFlowShowPaymentDialog:405,transactionFlowStarted:176,transactionFlowSecondaryDeviceStarted:222,transactionFlowSecondaryDeviceSignedOutStarted:383,transactionFlowCancelled:177,transactionFlowPaymentCallBackReceived:387,
transactionFlowPaymentSubmitted:460,transactionFlowPaymentSucceeded:329,transactionFlowSucceeded:178,transactionFlowFailed:179,transactionFlowPlayBillingConnectionStartEvent:428,transactionFlowSecondaryDeviceSuccess:458,transactionFlowErrorEvent:411,liteVideoQualityChanged:180,watchBreakEnablementSettingEvent:181,watchBreakFrequencySettingEvent:182,videoEffectsCameraPerformanceMetrics:183,adNotify:184,startupTelemetry:185,playbackOfflineFallbackUsed:186,outOfMemory:187,ypcPauseFlowStarted:188,ypcPauseFlowCancelled:189,
ypcPauseFlowSucceeded:190,ypcPauseFlowFailed:191,uploadFileSelected:192,ypcResumeFlowStarted:193,ypcResumeFlowCancelled:194,ypcResumeFlowSucceeded:195,ypcResumeFlowFailed:196,adsClientStateChange:197,ypcCancelFlowStarted:198,ypcCancelFlowCancelled:199,ypcCancelFlowSucceeded:200,ypcCancelFlowFailed:201,ypcCancelFlowGoToPaymentProcessor:402,ypcDeactivateFlowStarted:320,ypcRedeemFlowStarted:203,ypcRedeemFlowCancelled:204,ypcRedeemFlowSucceeded:205,ypcRedeemFlowFailed:206,ypcFamilyCreateFlowStarted:258,
ypcFamilyCreateFlowCancelled:259,ypcFamilyCreateFlowSucceeded:260,ypcFamilyCreateFlowFailed:261,ypcFamilyManageFlowStarted:262,ypcFamilyManageFlowCancelled:263,ypcFamilyManageFlowSucceeded:264,ypcFamilyManageFlowFailed:265,restoreContextEvent:207,embedsAdEvent:327,autoplayTriggered:209,clientDataErrorEvent:210,experimentalVssValidation:211,tvhtml5TriggeredEvent:212,tvhtml5FrameworksFieldTrialResult:216,tvhtml5FrameworksFieldTrialStart:220,musicOfflinePreferences:218,watchTimeSegment:219,appWidthLayoutError:221,
accountRegistryChange:226,userMentionAutoCompleteBoxEvent:227,downloadRecommendationEnablementSettingEvent:228,musicPlaybackContentModeChangeEvent:231,offlineDbOpenCompleted:232,kidsFlowEvent:233,kidsFlowCorpusSelectedEvent:234,videoEffectsEvent:235,unpluggedOpsEogAnalyticsEvent:236,playbackAudioRouteEvent:237,interactionLoggingDebugModeError:238,offlineYtbRefreshed:239,kidsFlowError:240,musicAutoplayOnLaunchAttempted:242,deviceContextActivityEvent:243,deviceContextEvent:244,templateResolutionException:245,
musicSideloadedPlaylistServiceCalled:246,embedsStorageAccessNotChecked:247,embedsHasStorageAccessResult:248,embedsItpPlayedOnReload:249,embedsRequestStorageAccessResult:250,embedsShouldRequestStorageAccessResult:251,embedsRequestStorageAccessState:256,embedsRequestStorageAccessFailedState:257,embedsItpWatchLaterResult:266,searchSuggestDecodingPayloadFailure:252,siriShortcutActivated:253,tvhtml5KeyboardPerformance:254,latencyActionSpan:255,elementsLog:267,ytbFileOpened:268,tfliteModelError:269,apiTest:270,
yongleUsbSetup:271,touStrikeInterstitialEvent:272,liteStreamToSave:274,appBundleClientEvent:275,ytbFileCreationFailed:276,adNotifyFailure:278,ytbTransferFailed:280,blockingRequestFailed:281,liteAccountSelector:282,liteAccountUiCallbacks:283,dummyPayload:284,browseResponseValidationEvent:285,entitiesError:286,musicIosBackgroundFetch:287,mdxNotificationEvent:289,layersValidationError:290,musicPwaInstalled:291,liteAccountCleanup:292,html5PlayerHealthEvent:293,watchRestoreAttempt:294,liteAccountSignIn:296,
notaireEvent:298,kidsVoiceSearchEvent:299,adNotifyFilled:300,delayedEventDropped:301,analyticsSearchEvent:302,systemDarkThemeOptOutEvent:303,flowEvent:304,networkConnectivityBaselineEvent:305,ytbFileImported:306,downloadStreamUrlExpired:307,directSignInEvent:308,lyricImpressionEvent:309,accessibilityStateEvent:310,tokenRefreshEvent:311,genericAttestationExecution:312,tvhtml5VideoSeek:313,unpluggedAutoPause:314,scrubbingEvent:315,bedtimeReminderEvent:317,tvhtml5UnexpectedRestart:319,tvhtml5StabilityTraceEvent:478,
tvhtml5OperationHealth:467,tvhtml5WatchKeyEvent:321,voiceLanguageChanged:322,tvhtml5LiveChatStatus:323,parentToolsCorpusSelectedEvent:324,offerAdsEnrollmentInitiated:325,networkQualityIntervalEvent:326,deviceStartupMetrics:328,heartbeatActionPlayerTransitioned:330,tvhtml5Lifecycle:331,heartbeatActionPlayerHalted:332,adaptiveInlineMutedSettingEvent:333,mainAppLibraryLoadingState:334,thirdPartyLogMonitoringEvent:336,appShellAssetLoadReport:337,tvhtml5AndroidAttestation:338,tvhtml5StartupSoundEvent:340,
iosBackgroundRefreshTask:342,iosBackgroundProcessingTask:343,sliEventBatch:344,postImpressionEvent:346,musicSideloadedPlaylistExport:347,idbUnexpectedlyClosed:348,voiceSearchEvent:349,mdxSessionCastEvent:350,idbQuotaExceeded:351,idbTransactionEnded:352,idbTransactionAborted:353,tvhtml5KeyboardLogging:354,idbIsSupportedCompleted:355,creatorStudioMobileEvent:356,idbDataCorrupted:357,parentToolsAppChosenEvent:358,webViewBottomSheetResized:359,activeStateControllerScrollPerformanceSummary:360,navigatorValidation:361,
mdxSessionHeartbeat:362,clientHintsPolyfillDiagnostics:363,clientHintsPolyfillEvent:364,proofOfOriginTokenError:365,kidsAddedAccountSummary:366,musicWearableDevice:367,ypcRefundFlowEvent:368,tvhtml5PlaybackMeasurementEvent:369,tvhtml5WatermarkMeasurementEvent:370,clientExpGcfPropagationEvent:371,mainAppReferrerIntent:372,leaderLockEnded:373,leaderLockAcquired:374,googleHatsEvent:375,persistentLensLaunchEvent:376,parentToolsChildWelcomeChosenEvent:378,browseThumbnailPreloadEvent:379,finalPayload:380,
mdxDialAdditionalDataUpdateEvent:381,webOrchestrationTaskLifecycleRecord:382,startupSignalEvent:384,accountError:385,gmsDeviceCheckEvent:386,accountSelectorEvent:388,accountUiCallbacks:389,mdxDialAdditionalDataProbeEvent:390,downloadsSearchIcingApiStats:391,downloadsSearchIndexUpdatedEvent:397,downloadsSearchIndexSnapshot:398,dataPushClientEvent:392,kidsCategorySelectedEvent:393,mdxDeviceManagementSnapshotEvent:394,prefetchRequested:395,prefetchableCommandExecuted:396,gelDebuggingEvent:399,webLinkTtsPlayEnd:400,
clipViewInvalid:401,persistentStorageStateChecked:403,cacheWipeoutEvent:404,playerEvent:410,sfvEffectPipelineStartedEvent:412,sfvEffectPipelinePausedEvent:429,sfvEffectPipelineEndedEvent:413,sfvEffectChosenEvent:414,sfvEffectLoadedEvent:415,sfvEffectUserInteractionEvent:465,sfvEffectFirstFrameProcessedLatencyEvent:416,sfvEffectAggregatedFramesProcessedLatencyEvent:417,sfvEffectAggregatedFramesDroppedEvent:418,sfvEffectPipelineErrorEvent:430,sfvEffectGraphFrozenEvent:419,sfvEffectGlThreadBlockedEvent:420,
mdeVideoChangedEvent:442,mdePlayerPerformanceMetrics:472,mdeExporterEvent:497,genericClientExperimentEvent:423,homePreloadTaskScheduled:424,homePreloadTaskExecuted:425,homePreloadCacheHit:426,polymerPropertyChangedInObserver:427,applicationStarted:431,networkCronetRttBatch:432,networkCronetRttSummary:433,repeatChapterLoopEvent:436,seekCancellationEvent:462,lockModeTimeoutEvent:483,externalVideoShareToYoutubeAttempt:501,parentCodeEvent:502,offlineTransferStarted:4,musicOfflineMixtapePreferencesChanged:16,
mangoDailyNewVideosNotificationAttempt:40,mangoDailyNewVideosNotificationError:77,dtwsPlaybackStarted:112,dtwsTileFetchStarted:113,dtwsTileFetchCompleted:114,dtwsTileFetchStatusChanged:145,dtwsKeyframeDecoderBufferSent:115,dtwsTileUnderflowedOnNonkeyframe:116,dtwsBackfillFetchStatusChanged:143,dtwsBackfillUnderflowed:117,dtwsAdaptiveLevelChanged:128,blockingVisitorIdTimeout:277,liteSocial:18,mobileJsInvocation:297,biscottiBasedDetection:439,coWatchStateChange:440,embedsVideoDataDidChange:441,shortsFirst:443,
cruiseControlEvent:445,qoeClientLoggingContext:446,atvRecommendationJobExecuted:447,tvhtml5UserFeedback:448,producerProjectCreated:449,producerProjectOpened:450,producerProjectDeleted:451,producerProjectElementAdded:453,producerProjectElementRemoved:454,tvhtml5ShowClockEvent:455,deviceCapabilityCheckMetrics:456,youtubeClearcutEvent:461,offlineBrowseFallbackEvent:463,getCtvTokenEvent:464,startupDroppedFramesSummary:466,screenshotEvent:468,miniAppPlayEvent:469,elementsDebugCounters:470,fontLoadEvent:471,
webKillswitchReceived:473,webKillswitchExecuted:474,cameraOpenEvent:475,manualSmoothnessMeasurement:476,tvhtml5AppQualityEvent:477,polymerPropertyAccessEvent:479,miniAppSdkUsage:480,cobaltTelemetryEvent:481,crossDevicePlayback:482,channelCreatedWithObakeImage:484,channelEditedWithObakeImage:485,offlineDeleteEvent:486,crossDeviceNotificationTransfer:487,androidIntentEvent:488,unpluggedAmbientInterludesCounterfactualEvent:489,keyPlaysPlayback:490,shortsCreationFallbackEvent:493,vssData:491,castMatch:494,
miniAppPerformanceMetrics:495,userFeedbackEvent:496,kidsGuestSessionMismatch:498,musicSideloadedPlaylistMigrationEvent:499,sleepTimerSessionFinishEvent:500,watchEpPromoConflict:503};var xr={},yr=Tp("ServiceWorkerLogsDatabase",{wb:(xr.SWHealthLog={Db:1},xr),shared:!0,upgrade:function(a,b){b(1)&&fp(Zo(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function zr(a){return sp(yr(),a)}
function Ar(a){var b,c;A(function(d){if(d.h==1)return d.yield(zr(a),2);b=d.i;c=W()-2592E6;return d.yield(Yo(b,["SWHealthLog"],{mode:"readwrite",la:!0},function(e){return hp(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return ip(f)})})}),0)})}
function Br(a){var b;return A(function(c){if(c.h==1)return c.yield(zr(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Cr={},Dr=0;function Er(a){var b=new Image,c=""+Dr++;Cr[c]=b;b.onload=b.onerror=function(){delete Cr[c]};
b.src=a}
;var Fr;function Gr(){Fr||(Fr=new jo("yt.offline"));return Fr}
function Hr(a){if(U("offline_error_handling")){var b=Gr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Gr().set("errors",b,2592E3,!0)}}
;function Ir(){this.h=new Map;this.i=!1}
function Jr(){if(!Ir.h){var a=E("yt.networkRequestMonitor.instance")||new Ir;D("yt.networkRequestMonitor.instance",a);Ir.h=a}return Ir.h}
Ir.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Ir.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:a===!1&&this.i?!0:null};
Ir.prototype.removeParams=function(a){return a.split("?")[0]};
Ir.prototype.removeParams=Ir.prototype.removeParams;Ir.prototype.isEndpointCFR=Ir.prototype.isEndpointCFR;Ir.prototype.requestComplete=Ir.prototype.requestComplete;Ir.getInstance=Jr;function Kr(){ai.call(this);var a=this;this.j=!1;this.i=Jj();this.i.listen("networkstatus-online",function(){if(a.j&&U("offline_error_handling")){var b=Gr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new V(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;em(d)}Gr().set("errors",{},2592E3,!0)}}})}
x(Kr,ai);function Lr(){if(!Kr.h){var a=E("yt.networkStatusManager.instance")||new Kr;D("yt.networkStatusManager.instance",a);Kr.h=a}return Kr.h}
p=Kr.prototype;p.wa=function(){return this.i.wa()};
p.fb=function(a){this.i.i=a};
p.ae=function(){var a=window.navigator.onLine;return a===void 0?!0:a};
p.Sd=function(){this.j=!0};
p.listen=function(a,b){return this.i.listen(a,b)};
p.nc=function(a){a=Hj(this.i,a);a.then(function(b){U("use_cfr_monitor")&&Jr().requestComplete("generate_204",b)});
return a};
Kr.prototype.sendNetworkCheckRequest=Kr.prototype.nc;Kr.prototype.listen=Kr.prototype.listen;Kr.prototype.enableErrorFlushing=Kr.prototype.Sd;Kr.prototype.getWindowStatus=Kr.prototype.ae;Kr.prototype.networkStatusHint=Kr.prototype.fb;Kr.prototype.isNetworkAvailable=Kr.prototype.wa;Kr.getInstance=Lr;function Mr(a){a=a===void 0?{}:a;ai.call(this);var b=this;this.i=this.u=0;this.j=Lr();var c=E("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.rateLimit?(this.rateLimit=a.rateLimit,c("networkstatus-online",function(){Nr(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Nr(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){bi(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){bi(b,"publicytnetworkstatus-offline")})))}
x(Mr,ai);Mr.prototype.wa=function(){var a=E("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Mr.prototype.fb=function(a){var b=E("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Mr.prototype.nc=function(a){var b=this,c;return A(function(d){c=E("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return U("skip_network_check_if_cfr")&&Jr().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.fb(((f=window.navigator)==null?void 0:f.onLine)||!0);e(b.wa())})):c?d.return(c(a)):d.return(!0)})};
function Nr(a,b){a.rateLimit?a.i?(Kj.ra(a.u),a.u=Kj.qa(function(){a.o!==b&&(bi(a,b),a.o=b,a.i=W())},a.rateLimit-(W()-a.i))):(bi(a,b),a.o=b,a.i=W()):bi(a,b)}
;var Or;function Pr(){var a=br.call;Or||(Or=new Mr({ah:!0,Tg:!0}));a.call(br,this,{ha:{Md:ur,nb:tr,Zc:qr,qe:rr,Jc:sr,set:or},fa:Or,handleError:function(b,c,d){var e,f=d==null?void 0:(e=d.error)==null?void 0:e.code;if(f===400||f===415){var g;fm(new V(b.message,c,d==null?void 0:(g=d.error)==null?void 0:g.code),void 0,void 0,void 0,!0)}else em(b)},
ob:fm,sendFn:Ur,now:W,Ed:Hr,Ea:io(),Ic:"publicytnetworkstatus-online",Fc:"publicytnetworkstatus-offline",ac:!0,Yb:.1,jc:zm("potential_esf_error_limit",10),Z:U,Gb:!(An()&&Vr())});this.j=new vj;U("networkless_immediately_drop_all_requests")&&vr();Qp("LogsDatabaseV2")}
x(Pr,br);function Wr(){var a=E("yt.networklessRequestController.instance");a||(a=new Pr,D("yt.networklessRequestController.instance",a),U("networkless_logging")&&Fp().then(function(b){a.Y=b;dr(a);a.j.resolve();a.ac&&Math.random()<=a.Yb&&a.Y&&Ar(a.Y);U("networkless_immediately_drop_sw_health_store")&&Xr(a)}));
return a}
Pr.prototype.writeThenSend=function(a,b){b||(b={});b=Yr(a,b);An()||(this.h=!1);br.prototype.writeThenSend.call(this,a,b)};
Pr.prototype.sendThenWrite=function(a,b,c){b||(b={});b=Yr(a,b);An()||(this.h=!1);br.prototype.sendThenWrite.call(this,a,b,c)};
Pr.prototype.sendAndWrite=function(a,b){b||(b={});b=Yr(a,b);An()||(this.h=!1);br.prototype.sendAndWrite.call(this,a,b)};
Pr.prototype.awaitInitialization=function(){return this.j.promise};
function Xr(a){var b;A(function(c){if(!a.Y)throw b=Ko("clearSWHealthLogsDb"),b;return c.return(Br(a.Y).catch(function(d){a.handleError(d)}))})}
function Ur(a,b,c,d){d=d===void 0?!1:d;b=U("web_fp_via_jspb")?Object.assign({},b):b;U("use_cfr_monitor")&&Zr(a,b);if(U("use_request_time_ms_header"))b.headers&&pm(a)&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));else{var e;if((e=b.postParams)==null?0:e.requestTimeMs)b.postParams.requestTimeMs=Math.round(W())}if(c&&Object.keys(b).length===0){var f=f===void 0?"":f;var g=g===void 0?!1:g;var h=h===void 0?!1:h;if(a)if(f)Em(a,void 0,"POST",f,void 0);else if(S("USE_NET_AJAX_FOR_PING_TRANSPORT",
!1)||h)Em(a,void 0,"GET","",void 0,void 0,g,h);else{b:{try{var k=new ab({url:a});if(k.j&&k.i||k.o){var l=Yb(Zb(5,a)),m;if(!(m=!l||!l.endsWith("/aclk"))){var n=a.search(hc),r=fc(a,0,"ri",n);if(r<0)var t=null;else{var w=a.indexOf("&",r);if(w<0||w>n)w=n;t=decodeURIComponent(a.slice(r+3,w!==-1?w:0).replace(/\+/g," "))}m=t!=="1"}var y=!m;break b}}catch(G){}y=!1}if(y){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(G){}z=!1}c=z?!0:!1}else c=
!1;c||Er(a)}}else b.compress?b.postBody?(typeof b.postBody!=="string"&&(b.postBody=JSON.stringify(b.postBody)),Rq(a,b.postBody,b,Im,d)):Rq(a,JSON.stringify(b.postParams),b,Hm,d):Im(a,b)}
function Yr(a,b){U("use_event_time_ms_header")&&pm(a)&&(b.headers||(b.headers={}),b.headers["X-Goog-Event-Time"]=JSON.stringify(Math.round(W())));return b}
function Zr(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Jr().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Jr().requestComplete(a,!0);d(e,f)}}
function Vr(){return $b(document.location.toString())!=="www.youtube-nocookie.com"}
;var $r=!1,as=C.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:$r};D("ytNetworklessLoggingInitializationOptions",as);function bs(){var a;A(function(b){if(b.h==1)return b.yield(Fp(),2);a=b.i;if(!a||!An()&&!U("nwl_init_require_datasync_id_killswitch")||!Vr())return b.F(0);$r=!0;as.isNwlInitialized=$r;return b.yield(Wr().awaitInitialization(),0)})}
;function cs(a){var b=this;this.config_=null;a?this.config_=a:gq()&&(this.config_=hq());Dn(function(){$q(b)},5E3)}
cs.prototype.isReady=function(){!this.config_&&gq()&&(this.config_=hq());return!!this.config_};
function ar(a,b,c,d){function e(w){w=w===void 0?!1:w;var y;if(d.retry&&h!="www.youtube-nocookie.com"&&(w||U("skip_ls_gel_retry")||g.headers["Content-Type"]!=="application/json"||(y=Yq(b,c,l,k)),y)){var z=g.onSuccess,G=g.onFetchSuccess;g.onSuccess=function(O,ta){Zq(y);z(O,ta)};
c.onFetchSuccess=function(O,ta){Zq(y);G(O,ta)}}try{if(w&&d.retry&&!d.networklessOptions.bypassNetworkless)g.method="POST",d.networklessOptions.writeThenSend?Wr().writeThenSend(t,g):Wr().sendAndWrite(t,g);
else if(d.compress){var I=!d.networklessOptions.writeThenSend;if(g.postBody){var M=g.postBody;typeof M!=="string"&&(M=JSON.stringify(g.postBody));Rq(t,M,g,Im,I)}else Rq(t,JSON.stringify(g.postParams),g,Hm,I)}else U("web_all_payloads_via_jspb")?Im(t,g):Hm(t,g)}catch(O){if(O.name==="InvalidAccessError")y&&(Zq(y),y=0),fm(Error("An extension is blocking network request."));else throw O;}y&&Dn(function(){$q(a)},5E3)}
!S("VISITOR_DATA")&&b!=="visitor_id"&&Math.random()<.01&&fm(new V("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new V("innertube xhrclient not ready",b,c,d);em(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(w,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(w){if(d.onSuccess)d.onSuccess(w)},
onError:function(w,y){if(d.onError)d.onError(y)},
onFetchError:function(w){if(d.onError)d.onError(w)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.je)&&(h=f);var k=a.config_.le||!1,l=jq(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var m="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,n={alt:"json"},r=a.config_.ke&&f;r=r&&f.startsWith("Bearer");r||(n.key=a.config_.innertubeApiKey);var t=om(""+h+m,n||{},!0);(E("ytNetworklessLoggingInitializationOptions")?
as.isNwlInitialized:$r)?Dp().then(function(w){e(w)}):e(!1)}
;var ds=0,es=Vc?"webkit":Uc?"moz":Sc?"ms":Rc?"o":"";D("ytDomDomGetNextId",E("ytDomDomGetNextId")||function(){return++ds});var gs={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function hs(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in gs||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&c.nodeType==3&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else this.type=="mouseover"?d=a.fromElement:this.type=="mouseout"&&(d=a.toElement);this.relatedTarget=d;this.clientX=a.clientX!=void 0?a.clientX:a.pageX;this.clientY=a.clientY!=void 0?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||(this.type=="keypress"?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function is(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
hs.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
hs.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
hs.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var zg=C.ytEventsEventsListeners||{};D("ytEventsEventsListeners",zg);var js=C.ytEventsEventsCounter||{count:0};D("ytEventsEventsCounter",js);
function ks(a,b,c,d){d=d===void 0?{}:d;a.addEventListener&&(b!="mouseenter"||"onmouseenter"in document?b!="mouseleave"||"onmouseenter"in document?b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return yg(function(e){var f=typeof e[4]==="boolean"&&e[4]==!!d,g=Qa(e[4])&&Qa(d)&&Dg(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function ls(a,b,c,d){d=d===void 0?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=ks(a,b,c,d);if(e)return e;e=++js.count+"";var f=!(b!="mouseenter"&&b!="mouseleave"||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new hs(h);if(!Og(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new hs(h);
h.currentTarget=a;return c.call(a,h)};
g=dm(g);a.addEventListener?(b=="mouseenter"&&f?b="mouseover":b=="mouseleave"&&f?b="mouseout":b=="mousewheel"&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),ms()||typeof d==="boolean"?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);zg[e]=[a,b,c,g,d];return e}
function ns(a){a&&(typeof a=="string"&&(a=[a]),Kb(a,function(b){if(b in zg){var c=zg[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?ms()||typeof c==="boolean"?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete zg[b]}}))}
var ms=gi(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});function ps(a){this.H=a;this.h=null;this.o=0;this.A=null;this.u=0;this.i=[];for(a=0;a<4;a++)this.i.push(0);this.j=0;this.T=ls(window,"mousemove",Wa(this.W,this));a=Wa(this.I,this);typeof a==="function"&&(a=dm(a));this.X=window.setInterval(a,25)}
Za(ps,L);ps.prototype.W=function(a){a.h===void 0&&is(a);var b=a.h;a.i===void 0&&is(a);this.h=new Kg(b,a.i)};
ps.prototype.I=function(){if(this.h){var a=W();if(this.o!=0){var b=this.A,c=this.h,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.i[this.j]=Math.abs((d-this.u)/this.u)>.5?1:0;for(c=b=0;c<4;c++)b+=this.i[c]||0;b>=3&&this.H();this.u=d}this.o=a;this.A=this.h;this.j=(this.j+1)%4}};
ps.prototype.ba=function(){window.clearInterval(this.X);ns(this.T)};var qs={};
function rs(a){var b=a===void 0?{}:a;a=b.Ae===void 0?!1:b.Ae;b=b.Td===void 0?!0:b.Td;if(E("_lact",window)==null){var c=parseInt(S("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;D("_lact",c,window);D("_fact",c,window);c==-1&&ss();ls(document,"keydown",ss);ls(document,"keyup",ss);ls(document,"mousedown",ss);ls(document,"mouseup",ss);a?ls(window,"touchmove",function(){ts("touchmove",200)},{passive:!0}):(ls(window,"resize",function(){ts("resize",200)}),b&&ls(window,"scroll",function(){ts("scroll",200)}));
new ps(function(){ts("mouse",100)});
ls(document,"touchstart",ss,{passive:!0});ls(document,"touchend",ss,{passive:!0})}}
function ts(a,b){qs[a]||(qs[a]=!0,Kj.qa(function(){ss();qs[a]=!1},b))}
function ss(){E("_lact",window)==null&&rs();var a=Date.now();D("_lact",a,window);E("_fact",window)==-1&&D("_fact",a,window);(a=E("ytglobal.ytUtilActivityCallback_"))&&a()}
function us(){var a=E("_lact",window);return a==null?-1:Math.max(Date.now()-a,0)}
;var vs=C.ytPubsubPubsubInstance||new N,ws=C.ytPubsubPubsubSubscribedKeys||{},xs=C.ytPubsubPubsubTopicToKeys||{},ys=C.ytPubsubPubsubIsSynchronous||{};function zs(a,b){var c=As();if(c&&b){var d=c.subscribe(a,function(){function e(){ws[d]&&b.apply&&typeof b.apply=="function"&&b.apply(window,f)}
var f=arguments;try{ys[a]?e():wm(e,0)}catch(g){em(g)}},void 0);
ws[d]=!0;xs[a]||(xs[a]=[]);xs[a].push(d);return d}return 0}
function Bs(a){var b=As();b&&(typeof a==="number"?a=[a]:typeof a==="string"&&(a=[parseInt(a,10)]),Kb(a,function(c){b.unsubscribeByKey(c);delete ws[c]}))}
function Cs(a,b){var c=As();c&&c.publish.apply(c,arguments)}
function Ds(a){var b=As();if(b)if(b.clear(a),a)Es(a);else for(var c in xs)Es(c)}
function As(){return C.ytPubsubPubsubInstance}
function Es(a){xs[a]&&(a=xs[a],Kb(a,function(b){ws[b]&&delete ws[b]}),a.length=0)}
N.prototype.subscribe=N.prototype.subscribe;N.prototype.unsubscribeByKey=N.prototype.Rb;N.prototype.publish=N.prototype.kb;N.prototype.clear=N.prototype.clear;D("ytPubsubPubsubInstance",vs);D("ytPubsubPubsubTopicToKeys",xs);D("ytPubsubPubsubIsSynchronous",ys);D("ytPubsubPubsubSubscribedKeys",ws);var Fs=Symbol("injectionDeps");function Gs(a){this.name=a}
Gs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Hs(a){this.key=a}
function Is(){this.i=new Map;this.j=new Map;this.h=new Map}
function Js(a,b){a.i.set(b.lc,b);var c=a.j.get(b.lc);if(c)try{c.jh(a.resolve(b.lc))}catch(d){c.hh(d)}}
Is.prototype.resolve=function(a){return a instanceof Hs?Ks(this,a.key,[],!0):Ks(this,a,[])};
function Ks(a,b,c,d){d=d===void 0?!1:d;if(c.indexOf(b)>-1)throw Error("Deps cycle for: "+b);if(a.h.has(b))return a.h.get(b);if(!a.i.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.i.get(b);c.push(b);if(d.Ad!==void 0)var e=d.Ad;else if(d.jf)e=d[Fs]?Ls(a,d[Fs],c):[],e=d.jf.apply(d,ja(e));else if(d.zd){e=d.zd;var f=e[Fs]?Ls(a,e[Fs],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ja(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.mh||a.h.set(b,e);return e}
function Ls(a,b,c){return b?b.map(function(d){return d instanceof Hs?Ks(a,d.key,c,!0):Ks(a,d,c)}):[]}
;var Ms;function Ns(){Ms||(Ms=new Is);return Ms}
;var Os=window;function Ps(){var a,b;return"h5vcc"in Os&&((a=Os.h5vcc.traceEvent)==null?0:a.traceBegin)&&((b=Os.h5vcc.traceEvent)==null?0:b.traceEnd)?1:"performance"in Os&&Os.performance.mark&&Os.performance.measure?2:0}
function Qs(a){var b=Ps();switch(b){case 1:Os.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:Os.performance.mark(a+"-start");break;case 0:break;default:Bb(b,"unknown trace type")}}
function Rs(a){var b=Ps();switch(b){case 1:Os.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:b=a+"-start";var c=a+"-end";Os.performance.mark(c);Os.performance.measure(a,b,c);break;case 0:break;default:Bb(b,"unknown trace type")}}
;var Ss=U("web_enable_lifecycle_monitoring")&&Ps()!==0,Ts=U("web_enable_lifecycle_monitoring");function Us(a){var b=this;var c=c===void 0?0:c;var d=d===void 0?io():d;this.j=c;this.scheduler=d;this.i=new vj;this.h=a;for(a={bb:0};a.bb<this.h.length;a={ic:void 0,bb:a.bb},a.bb++)a.ic=this.h[a.bb],c=function(e){return function(){e.ic.yc();b.h[e.bb].kc=!0;b.h.every(function(f){return f.kc===!0})&&b.i.resolve()}}(a),d=this.getPriority(a.ic),d=this.scheduler.Za(c,d),this.h[a.bb]=Object.assign({},a.ic,{yc:c,
jobId:d})}
function Vs(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=v(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],c.jobId===void 0||c.kc||(a.scheduler.ra(c.jobId),a.scheduler.Za(c.yc,10))}
Us.prototype.cancel=function(){for(var a=v(this.h),b=a.next();!b.done;b=a.next())b=b.value,b.jobId===void 0||b.kc||this.scheduler.ra(b.jobId),b.kc=!0;this.i.resolve()};
Us.prototype.getPriority=function(a){var b;return(b=a.priority)!=null?b:this.j};function Ws(a){this.state=a;this.plugins=[];this.o=void 0;this.A={};Ss&&Qs(this.state)}
p=Ws.prototype;p.install=function(a){this.plugins.push(a);return this};
p.uninstall=function(){var a=this;B.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);b>-1&&a.plugins.splice(b,1)})};
p.transition=function(a,b){var c=this;Ss&&Rs(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(Vs(this.j),this.j=void 0);Xs(this,a,b);this.state=a;Ss&&Qs(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Ys(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Ys(a,b){var c=b.filter(function(e){return Zs(a,e)===10}),d=b.filter(function(e){return Zs(a,e)!==10});
return a.A.lh?function(){var e=B.apply(0,arguments);return A(function(f){if(f.h==1)return f.yield(a.He.apply(a,[c].concat(ja(e))),2);a.ud.apply(a,[d].concat(ja(e)));f.h=0})}:function(){var e=B.apply(0,arguments);
a.Ie.apply(a,[c].concat(ja(e)));a.ud.apply(a,[d].concat(ja(e)))}}
p.Ie=function(a){for(var b=B.apply(1,arguments),c=io(),d=v(a),e=d.next(),f={};!e.done;f={Ib:void 0},e=d.next())f.Ib=e.value,c.Bb(function(g){return function(){$s(g.Ib.name);g.Ib.callback.apply(g.Ib,ja(b));at(g.Ib.name)}}(f))};
p.He=function(a){var b=B.apply(1,arguments),c,d,e,f,g;return A(function(h){h.h==1&&(c=io(),d=v(a),e=d.next(),f={});if(h.h!=3){if(e.done)return h.F(0);f.sb=e.value;f.Tb=void 0;g=function(k){return function(){$s(k.sb.name);var l=k.sb.callback.apply(k.sb,ja(b));typeof(l==null?void 0:l.then)==="function"?k.Tb=l.then(function(){at(k.sb.name)}):at(k.sb.name)}}(f);
c.Bb(g);return f.Tb?h.yield(f.Tb,3):h.F(3)}f={sb:void 0,Tb:void 0};e=d.next();return h.F(2)})};
p.ud=function(a){var b=B.apply(1,arguments),c=this,d=a.map(function(e){return{yc:function(){$s(e.name);e.callback.apply(e,ja(b));at(e.name)},
priority:Zs(c,e)}});
d.length&&(this.j=new Us(d))};
function Zs(a,b){var c,d;return(d=(c=a.o)!=null?c:b.priority)!=null?d:0}
function $s(a){Ss&&a&&Qs(a)}
function at(a){Ss&&a&&Rs(a)}
function Xs(a,b,c){Ts&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
da.Object.defineProperties(Ws.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function bt(a){Ws.call(this,a===void 0?"none":a);this.h=null;this.o=10;this.transitions=[{from:"none",to:"application_navigating",action:this.i},{from:"application_navigating",to:"none",action:this.D},{from:"application_navigating",to:"application_navigating",action:function(){}},
{from:"none",to:"none",action:function(){}}]}
var ct;x(bt,Ws);bt.prototype.i=function(a,b){var c=this;this.h=Dn(function(){c.currentState==="application_navigating"&&c.transition("none")},5E3);
a(b==null?void 0:b.event)};
bt.prototype.D=function(a,b){this.h&&(Kj.ra(this.h),this.h=null);a(b==null?void 0:b.event)};
function dt(){ct||(ct=new bt);return ct}
;var et=[];D("yt.logging.transport.getScrapedGelPayloads",function(){return et});function ft(){this.store={};this.h={}}
ft.prototype.storePayload=function(a,b){a=gt(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
ft.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=ht(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ja(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ja(this.store[b[d]].splice(0,a.sizeLimit))));(a==null?0:a.sizeLimit)&&c.length<(a==null?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ja(this.smartExtractMatchingEntries(a))));return c};
ft.prototype.extractMatchingEntries=function(a){a=ht(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ja(this.store[a[c]])),delete this.store[a[c]]);return b};
ft.prototype.getSequenceCount=function(a){a=ht(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=((d=this.store[a[c]])==null?void 0:d.length)||0}return b};
function ht(a,b){var c=gt(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(d.length<=1&&gt(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(jt(b.auth,g[0])){var h=b.isJspb;jt(h===void 0?"undefined":h?"true":"false",g[1])&&jt(b.cttAuthInfo,g[2])&&(h=b.tier,h=h===void 0?"undefined":JSON.stringify(h),jt(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function jt(a,b){return a===void 0||a==="undefined"?!0:a===b}
ft.prototype.getSequenceCount=ft.prototype.getSequenceCount;ft.prototype.extractMatchingEntries=ft.prototype.extractMatchingEntries;ft.prototype.smartExtractMatchingEntries=ft.prototype.smartExtractMatchingEntries;ft.prototype.storePayload=ft.prototype.storePayload;function gt(a){return[a.auth===void 0?"undefined":a.auth,a.isJspb===void 0?"undefined":a.isJspb,a.cttAuthInfo===void 0?"undefined":a.cttAuthInfo,a.tier===void 0?"undefined":a.tier].join("/")}
;function kt(a,b){if(a)return a[b.name]}
;var lt=zm("initial_gel_batch_timeout",2E3),mt=zm("gel_queue_timeout_max_ms",6E4),nt=zm("gel_min_batch_size",5),ot=void 0;function pt(){this.o=this.h=this.i=0;this.j=!1}
var qt=new pt,rt=new pt,st=new pt,tt=new pt,ut,vt=!0,wt=C.ytLoggingTransportTokensToCttTargetIds_||{};D("ytLoggingTransportTokensToCttTargetIds_",wt);var xt={};function zt(){var a=E("yt.logging.ims");a||(a=new ft,D("yt.logging.ims",a));return a}
function At(a,b){if(a.endpoint==="log_event"){Bt();var c=Ct(a),d=Dt(a.payload)||"";a:{if(U("enable_web_tiered_gel")){var e=wr[d||""];var f,g,h,k=Ns().resolve(new Hs(bq))==null?void 0:(f=cq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.eventLoggingConfig)==null?void 0:h.payloadPolicies;if(k)for(f=0;f<k.length;f++)if(k[f].payloadNumber===e){e=k[f];break a}}e=void 0}k=200;if(e){if(e.enabled===!1&&!U("web_payload_policy_disabled_killswitch"))return;k=Et(e.tier);if(k===400){Ft(a,b);return}}xt[c]=
!0;e={cttAuthInfo:c,isJspb:!1,tier:k};zt().storePayload(e,a.payload);Gt(b,c,e,d==="gelDebuggingEvent")}}
function Gt(a,b,c,d){function e(){Ht({writeThenSend:!0},U("flush_only_full_queue")?b:void 0,f,c.tier)}
var f=!1;f=f===void 0?!1:f;d=d===void 0?!1:d;a&&(ot=new a);a=zm("tvhtml5_logging_max_batch_ads_fork")||zm("tvhtml5_logging_max_batch")||zm("web_logging_max_batch")||100;var g=W(),h=It(f,c.tier),k=h.o;d&&(h.j=!0);d=0;c&&(d=zt().getSequenceCount(c));d>=1E3?e():d>=a?ut||(ut=Jt(function(){e();ut=void 0},0)):g-k>=10&&(Kt(f,c.tier),h.o=g)}
function Ft(a,b){if(a.endpoint==="log_event"){Bt();var c=Ct(a),d=new Map;d.set(c,[a.payload]);var e=Dt(a.payload)||"";b&&(ot=new b);return new si(function(f,g){ot&&ot.isReady()?Lt(d,ot,f,g,{bypassNetworkless:!0},!0,e==="gelDebuggingEvent"):f()})}}
function Ct(a){var b="";if(a.dangerousLogToVisitorSession)b="visitorOnlyApprovedKey";else if(a.cttAuthInfo){b=a.cttAuthInfo;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);wt[a.cttAuthInfo.token]=c;b=a.cttAuthInfo.token}return b}
function Ht(a,b,c,d){a=a===void 0?{}:a;c=c===void 0?!1:c;new si(function(e,f){var g=It(c,d),h=g.j;g.j=!1;Mt(g.i);Mt(g.h);g.h=0;ot&&ot.isReady()?d===void 0&&U("enable_web_tiered_gel")?Nt(e,f,a,b,c,300,h):Nt(e,f,a,b,c,d,h):(Kt(c,d),e())})}
function Nt(a,b,c,d,e,f,g){var h=ot;c=c===void 0?{}:c;e=e===void 0?!1:e;f=f===void 0?200:f;g=g===void 0?!1:g;var k=new Map,l={isJspb:e,cttAuthInfo:d,tier:f};e={isJspb:e,cttAuthInfo:d};if(d!==void 0)f=U("enable_web_tiered_gel")?zt().smartExtractMatchingEntries({keys:[l,e],sizeLimit:1E3}):zt().extractMatchingEntries(e),k.set(d,f);else for(d=v(Object.keys(xt)),l=d.next();!l.done;l=d.next())l=l.value,e=U("enable_web_tiered_gel")?zt().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:l,tier:f},
{isJspb:!1,cttAuthInfo:l}],sizeLimit:1E3}):zt().extractMatchingEntries({isJspb:!1,cttAuthInfo:l}),e.length>0&&k.set(l,e),(U("web_fp_via_jspb_and_json")&&c.writeThenSend||!U("web_fp_via_jspb_and_json"))&&delete xt[l];Lt(k,h,a,b,c,!1,g)}
function Kt(a,b){function c(){Ht({writeThenSend:!0},void 0,a,b)}
a=a===void 0?!1:a;b=b===void 0?200:b;var d=It(a,b),e=d===tt||d===st?5E3:mt;U("web_gel_timeout_cap")&&!d.h&&(e=Jt(function(){c()},e),d.h=e);
Mt(d.i);e=S("LOGGING_BATCH_TIMEOUT",zm("web_gel_debounce_ms",1E4));U("shorten_initial_gel_batch_timeout")&&vt&&(e=lt);e=Jt(function(){zm("gel_min_batch_size")>0?zt().getSequenceCount({cttAuthInfo:void 0,isJspb:a,tier:b})>=nt&&c():c()},e);
d.i=e}
function Lt(a,b,c,d,e,f,g){e=e===void 0?{}:e;var h=Math.round(W()),k=a.size,l=(g===void 0?0:g)&&U("vss_through_gel_video_stats")?"video_stats":"log_event";a=v(a);var m=a.next();for(g={};!m.done;g={Ec:void 0,batchRequest:void 0,dangerousLogToVisitorSession:void 0,Hc:void 0,Gc:void 0},m=a.next()){var n=v(m.value);m=n.next().value;n=n.next().value;g.batchRequest=Fg({context:iq(b.config_||hq())});if(!Pa(n)&&!U("throw_err_when_logevent_malformed_killswitch")){d();break}g.batchRequest.events=n;(n=wt[m])&&
Ot(g.batchRequest,m,n);delete wt[m];g.dangerousLogToVisitorSession=m==="visitorOnlyApprovedKey";Pt(g.batchRequest,h,g.dangerousLogToVisitorSession);U("always_send_and_write")&&(e.writeThenSend=!1);g.Hc=function(r){U("start_client_gcf")&&Kj.qa(function(){return A(function(t){return t.yield(Qt(r),0)})});
k--;k||c()};
g.Ec=0;g.Gc=function(r){return function(){r.Ec++;if(e.bypassNetworkless&&r.Ec===1)try{ar(b,l,r.batchRequest,Rt({writeThenSend:!0},r.dangerousLogToVisitorSession,r.Hc,r.Gc,f)),vt=!1}catch(t){em(t),d()}k--;k||c()}}(g);
try{ar(b,l,g.batchRequest,Rt(e,g.dangerousLogToVisitorSession,g.Hc,g.Gc,f)),vt=!1}catch(r){em(r),d()}}}
function Rt(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,networklessOptions:a,dangerousLogToVisitorSession:b,Pg:!!e,headers:{},postBodyFormat:"",postBody:"",compress:U("compress_gel")||U("compress_gel_lr")};St()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(W())));return a}
function Pt(a,b,c){St()||(a.requestTimeMs=String(b));U("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=S("EVENT_ID"))&&((c=S("BATCH_CLIENT_COUNTER")||0)||(c=Math.floor(Math.random()*65535/2)),c++,c>65535&&(c=1),$l("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Ot(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Bt(){var a;(a=E("yt.logging.transport.enableScrapingForTest"))||(a=ym("il_payload_scraping"),a=(a!==void 0?String(a):"")!=="enable_il_payload_scraping");a||(et=[],D("yt.logging.transport.enableScrapingForTest",!0),D("yt.logging.transport.scrapedPayloadsForTesting",et),D("yt.logging.transport.payloadToScrape","visualElementShown visualElementHidden visualElementAttached screenCreated visualElementGestured visualElementStateChanged".split(" ")),D("yt.logging.transport.getScrapedPayloadFromClientEventsFunction"),
D("yt.logging.transport.scrapeClientEvent",!0))}
function St(){return U("use_request_time_ms_header")||U("lr_use_request_time_ms_header")}
function Jt(a,b){return U("transport_use_scheduler")===!1?wm(a,b):U("logging_avoid_blocking_during_navigation")||U("lr_logging_avoid_blocking_during_navigation")?Dn(function(){if(dt().currentState==="none")a();else{var c={};dt().install((c.none={callback:a},c))}},b):Dn(a,b)}
function Mt(a){U("transport_use_scheduler")?Kj.ra(a):window.clearTimeout(a)}
function Qt(a){var b,c,d,e,f,g,h,k,l,m;return A(function(n){return n.h==1?(d=(b=a)==null?void 0:(c=b.responseContext)==null?void 0:c.globalConfigGroup,e=kt(d,Cl),g=(f=d)==null?void 0:f.hotHashData,h=kt(d,Bl),l=(k=d)==null?void 0:k.coldHashData,(m=Ns().resolve(new Hs(bq)))?g?e?n.yield(dq(m,g,e),2):n.yield(dq(m,g),2):n.F(2):n.return()):l?h?n.yield(eq(m,l,h),0):n.yield(eq(m,l),0):n.F(0)})}
function It(a,b){b=b===void 0?200:b;return a?b===300?tt:rt:b===300?st:qt}
function Dt(a){a=Object.keys(a);a=v(a);for(var b=a.next();!b.done;b=a.next())if(b=b.value,wr[b])return b}
function Et(a){switch(a){case "DELAYED_EVENT_TIER_UNSPECIFIED":return 0;case "DELAYED_EVENT_TIER_DEFAULT":return 100;case "DELAYED_EVENT_TIER_DISPATCH_TO_EMPTY":return 200;case "DELAYED_EVENT_TIER_FAST":return 300;case "DELAYED_EVENT_TIER_IMMEDIATE":return 400;default:return 200}}
;var Tt=C.ytLoggingGelSequenceIdObj_||{};D("ytLoggingGelSequenceIdObj_",Tt);
function Ut(a,b,c,d){d=d===void 0?{}:d;var e={},f=Math.round(d.timestamp||W());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=us();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};d.sequenceGroup&&!U("web_gel_sequence_info_killswitch")&&(a=e.context,b=d.sequenceGroup,Tt[b]=b in Tt?Tt[b]+1:0,a.sequence={index:Tt[b],groupKey:b},d.endOfSequence&&delete Tt[d.sequenceGroup]);(d.sendIsolatedPayload?Ft:At)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},
c)}
;function so(a,b,c){c=c===void 0?{}:c;var d=cs;S("ytLoggingEventsDefaultDisabled",!1)&&cs===cs&&(d=null);Ut(a,b,d,c)}
;function Vt(a){return a.slice(0,void 0).map(function(b){return b.name}).join(" > ")}
;var Wt=new Set,Xt=0,Yt=0,Zt=0,$t=[],au=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function ro(a){bu(a)}
function cu(a){bu(a,"WARNING")}
function du(a){a instanceof Error?bu(a):(a=Qa(a)?JSON.stringify(a):String(a),a=new V(a),a.name="RejectedPromiseError",cu(a))}
function bu(a,b,c,d,e,f,g,h){f=f===void 0?{}:f;f.name=c||S("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||S("INNERTUBE_CONTEXT_CLIENT_VERSION");c=f;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;b=b===void 0?"ERROR":b;g=g===void 0?!1:g;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),U("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+
JSON.stringify(a.args)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),d=d.join("\n"),window.console.log(d,a)),!(Xt>=5))){d=$t;var k=Sb(a);e=k.message||"Unknown Error";f=k.name||"UnknownError";var l=k.stack||a.i||"Not available";if(l.startsWith(f+": "+e)){var m=l.split("\n");m.shift();l=m.join("\n")}m=k.lineNumber||"Not available";k=k.fileName||"Not available";var n=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var r=0;r<a.args.length&&!(n=$m(a.args[r],"params."+r,c,n),
n>=500);r++);else if(a.hasOwnProperty("params")&&a.params){var t=a.params;if(typeof a.params==="object")for(r in t){if(t[r]){var w="params."+r,y=bn(t[r]);c[w]=y;n+=w.length+y.length;if(n>500)break}}else c.params=bn(t)}if(d.length)for(r=0;r<d.length&&!(n=$m(d[r],"params.context."+r,c,n),n>=500);r++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);r={message:e,name:f,lineNumber:m,fileName:k,stack:l,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(r.lineNumber=
r.lineNumber+":"+c);if(a.level==="IGNORED")a=0;else a:{a=Wm();c=v(a.Va);for(d=c.next();!d.done;d=c.next())if(d=d.value,r.message&&r.message.match(d.bh)){a=d.weight;break a}a=v(a.Sa);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.callback(r)){a=c.weight;break a}a=1}r.sampleWeight=a;a=v(Rm);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.hc[r.name])for(e=v(c.hc[r.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=r.message.match(f.regexp)){r.params["params.error.original"]=d[0];e=f.groups;f={};
for(m=0;m<e.length;m++)f[e[m]]=d[m+1],r.params["params.error."+e[m]]=d[m+1];r.message=c.Cc(f);break}r.params||(r.params={});a=Wm();r.params["params.errorServiceSignature"]="msg="+a.Va.length+"&cb="+a.Sa.length;r.params["params.serviceWorker"]="false";C.document&&C.document.querySelectorAll&&(r.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));(new Ig(Jg,"sample")).constructor!==Ig&&(r.params["params.fconst"]="true");window.yterr&&typeof window.yterr==="function"&&
window.yterr(r);if(r.sampleWeight!==0&&!Wt.has(r.message)){if(g&&U("web_enable_error_204"))eu(b===void 0?"ERROR":b,r);else{b=b===void 0?"ERROR":b;b==="ERROR"?(Xm.kb("handleError",r),U("record_app_crashed_web")&&Zt===0&&r.sampleWeight===1&&(Zt++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},U("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:r.message}}}}),so("appCrashed",g)),Yt++):b==="WARNING"&&Xm.kb("handleWarning",r);if(U("kevlar_gel_error_routing")){g=
b;h=h===void 0?{}:h;b:{a=v(au);for(c=a.next();!c.done;c=a.next())if(yo(c.value.toLowerCase())){a=!0;break b}a=!1}if(a)h=void 0;else{c={stackTrace:r.stack};r.fileName&&(c.filename=r.fileName);a=r.lineNumber&&r.lineNumber.split?r.lineNumber.split(":"):[];a.length!==0&&(a.length!==1||isNaN(Number(a[0]))?a.length!==2||isNaN(Number(a[0]))||isNaN(Number(a[1]))||(c.lineNumber=Number(a[0]),c.columnNumber=Number(a[1])):c.lineNumber=Number(a[0]));a={level:"ERROR_LEVEL_UNKNOWN",message:r.message,errorClassName:r.name,
sampleWeight:r.sampleWeight};g==="ERROR"?a.level="ERROR_LEVEL_ERROR":g==="WARNING"&&(a.level="ERROR_LEVEL_WARNNING");c={isObfuscated:!0,browserStackInfo:c};h.pageUrl=window.location.href;h.kvPairs=[];S("FEXP_EXPERIMENTS")&&(h.experimentIds=S("FEXP_EXPERIMENTS"));d=S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!am("web_disable_gel_stp_ecatcher_killswitch")&&d)for(e=v(Object.keys(d)),f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:f,value:String(d[f])});if(d=r.params)for(e=v(Object.keys(d)),
f=e.next();!f.done;f=e.next())f=f.value,h.kvPairs.push({key:"client."+f,value:String(d[f])});d=S("SERVER_NAME");e=S("SERVER_VERSION");d&&e&&(h.kvPairs.push({key:"server.name",value:d}),h.kvPairs.push({key:"server.version",value:e}));h={errorMetadata:h,stackTrace:c,logMessage:a}}h&&(so("clientError",h),(g==="ERROR"||U("errors_flush_gel_always_killswitch"))&&Ht(void 0,void 0,!1))}U("suppress_error_204_logging")||eu(b,r)}try{Wt.add(r.message)}catch(z){}Xt++}}}
function eu(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:S("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=v(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=S("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=v(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=S("SERVER_NAME");b=S("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Im(S("ECATCHER_REPORT_HOST","")+"/error_204",a)}
function fu(a){var b=B.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ja(b))}
;function gu(){this.register=new Map}
function hu(a){a=v(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.gh("ABORTED")}
gu.prototype.clear=function(){hu(this);this.register.clear()};
var iu=new gu;var ju=Date.now().toString();
function ku(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;a<16;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(Math.random()*256)}if(ju)for(a=1,b=0;b<ju.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^ju.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var lu,mu=C.ytLoggingDocDocumentNonce_;mu||(mu=ku(),D("ytLoggingDocDocumentNonce_",mu));lu=mu;function nu(a){this.h=a}
p=nu.prototype;p.getAsJson=function(){var a={};this.h.trackingParams!==void 0?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,this.h.veCounter!==void 0&&(a.veCounter=this.h.veCounter),this.h.elementIndex!==void 0&&(a.elementIndex=this.h.elementIndex));this.h.dataElement!==void 0&&(a.dataElement=this.h.dataElement.getAsJson());this.h.youtubeData!==void 0&&(a.youtubeData=this.h.youtubeData);this.h.isCounterfactual&&(a.isCounterfactual=!0);return a};
p.getAsJspb=function(){var a=new El;this.h.trackingParams!==void 0?a.setTrackingParams(this.h.trackingParams):(this.h.veType!==void 0&&lf(a,2,qe(this.h.veType)),this.h.veCounter!==void 0&&lf(a,6,qe(this.h.veCounter)),this.h.elementIndex!==void 0&&lf(a,3,qe(this.h.elementIndex)),this.h.isCounterfactual&&lf(a,5,me(!0)));if(this.h.dataElement!==void 0){var b=this.h.dataElement.getAsJspb();yf(a,El,7,b)}this.h.youtubeData!==void 0&&yf(a,Dl,8,this.h.jspbYoutubeData);return a};
p.toString=function(){return JSON.stringify(this.getAsJson())};
p.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};
p.getLoggingDirectives=function(){return this.h.loggingDirectives};function ou(a){return S("client-screen-nonce-store",{})[a===void 0?0:a]}
function pu(a,b){b=b===void 0?0:b;var c=S("client-screen-nonce-store");c||(c={},$l("client-screen-nonce-store",c));c[b]=a}
function qu(a){a=a===void 0?0:a;return a===0?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function ru(a){return S(qu(a===void 0?0:a))}
D("yt_logging_screen.getRootVeType",ru);function su(){var a=S("csn-to-ctt-auth-info");a||(a={},$l("csn-to-ctt-auth-info",a));return a}
function tu(){return Object.values(S("client-screen-nonce-store",{})).filter(function(a){return a!==void 0})}
function uu(a){a=ou(a===void 0?0:a);if(!a&&!S("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
D("yt_logging_screen.getCurrentCsn",uu);function vu(a,b,c){var d=su();(c=uu(c))&&delete d[c];b&&(d[a]=b)}
function wu(a){return su()[a]}
D("yt_logging_screen.getCttAuthInfo",wu);D("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=c===void 0?0:c;if(a!==ou(c)||b!==S(qu(c)))if(vu(a,d,c),pu(a,c),$l(qu(c),b),b=function(){setTimeout(function(){a&&so("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:lu,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});function xu(){var a=Eg(yu),b;return(new si(function(c,d){a.onSuccess=function(e){um(e)?c(new zu(e)):d(new Au("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Au("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Au("Request timed out","net.timeout",e))};
b=Im("//googleads.g.doubleclick.net/pagead/id",a)})).oc(function(c){if(c instanceof zi){var d;
(d=b)==null||d.abort()}return xi(c)})}
function Au(a,b,c){$a.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
x(Au,$a);function zu(a){this.xhr=a}
;function Bu(){this.h=0;this.i=null}
Bu.prototype.then=function(a,b,c){return this.h===1&&a?(a=a.call(c,this.i))&&typeof a.then==="function"?a:Cu(a):this.h===2&&b?(a=b.call(c,this.i))&&typeof a.then==="function"?a:Du(a):this};
Bu.prototype.getValue=function(){return this.i};
Bu.prototype.isRejected=function(){return this.h==2};
Bu.prototype.$goog_Thenable=!0;function Du(a){var b=new Bu;a=a===void 0?null:a;b.h=2;b.i=a===void 0?null:a;return b}
function Cu(a){var b=new Bu;a=a===void 0?null:a;b.h=1;b.i=a===void 0?null:a;return b}
;function Eu(a,b){var c=c===void 0?{}:c;a={method:b===void 0?"POST":b,mode:pm(a)?"same-origin":"cors",credentials:pm(a)?"same-origin":"include"};b={};for(var d=v(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);Object.keys(b).length>0&&(a.headers=b);return a}
;function Fu(){return ng()||(Xc||Yc)&&yo("applewebkit")&&!yo("version")&&(!yo("safari")||yo("gsa/"))||Wc&&yo("version/")?!0:S("EOM_VISITOR_DATA")?!1:!0}
;function Gu(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Il)if(Il[d]==c.embeddedPlayerMode){b=Il[d];break b}}return b==="EMBEDDED_PLAYER_MODE_PFL"}
;function Hu(a){$a.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Iu;this.isTimeout=a instanceof Au&&a.errorCode=="net.timeout";this.isCanceled=a instanceof zi}
x(Hu,$a);Hu.prototype.name="BiscottiError";function Iu(){$a.call(this,"Biscotti ID is missing from server")}
x(Iu,$a);Iu.prototype.name="BiscottiMissingError";var yu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Ju=null;function Ku(){if(U("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Fu())return Error("User has not consented - not fetching biscotti id.");var a=S("PLAYER_VARS",{});if(Cg(a)=="1")return Error("Biscotti ID is not available in private embed mode");if(Gu(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Tl(){var a=Ku();if(a!==void 0)return xi(a);Ju||(Ju=xu().then(Lu).oc(function(b){return Mu(2,b)}));
return Ju}
function Lu(a){a=a.xhr.responseText;if(a.lastIndexOf(")]}'",0)!=0)throw new Iu;a=JSON.parse(a.substr(4));if((a.type||1)>1)throw new Iu;a=a.id;Ul(a);Ju=Cu(a);Nu(18E5,2);return a}
function Mu(a,b){b=new Hu(b);Ul("");Ju=Du(b);a>0&&Nu(12E4,a-1);throw b;}
function Nu(a,b){wm(function(){xu().then(Lu,function(c){return Mu(b,c)}).oc(fi)},a)}
function Ou(){try{var a=E("yt.ads.biscotti.getId_");return a?a():Tl()}catch(b){return xi(b)}}
;var yb=ha(["data-"]);function Pu(a){a&&(a.dataset?a.dataset[Qu()]="true":Ab(a))}
function Ru(a){return a?a.dataset?a.dataset[Qu()]:a.getAttribute("data-loaded"):null}
var Su={};function Qu(){return Su.loaded||(Su.loaded="loaded".replace(/\-([a-z])/g,function(a,b){return b.toUpperCase()}))}
;function Tu(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||Eg(b);this.assets=a.assets||{};this.attrs=a.attrs||Eg(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Tu.prototype.clone=function(){var a=new Tu,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];Oa(c)=="object"?a[b]=Eg(c):a[b]=c}return a};var Uu=["share/get_share_panel"],Vu=["share/get_web_player_share_panel"],Wu=["feedback"],Xu=["notification/modify_channel_preference"],Yu=["browse/edit_playlist"],Zu=["subscription/subscribe"],$u=["subscription/unsubscribe"];var av=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};D("yt.msgs_",av);function bv(a){Vl(av,arguments)}
;function cv(a,b,c){dv(a,b,c===void 0?null:c)}
function ev(a){a=fv(a);var b=document.getElementById(a);b&&(Ds(a),b.parentNode.removeChild(b))}
function gv(a,b){a&&b&&(a=""+Ra(b),(a=hv[a])&&Bs(a))}
function dv(a,b,c){c=c===void 0?null:c;var d=fv(a),e=document.getElementById(d),f=e&&Ru(e),g=e&&!f;f?b&&b():(b&&(f=zs(d,b),b=""+Ra(b),hv[b]=f),g||(e=iv(a,d,function(){Ru(e)||(Pu(e),Cs(d),wm(function(){Ds(d)},0))},c)))}
function iv(a,b,c,d){d=d===void 0?null:d;var e=Ng("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Ib(e,zl(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function fv(a){var b=document.createElement("a");wb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Wb(a)}
var hv={};function jv(a){var b=kv(a),c=document.getElementById(b),d=c&&Ru(c);d||c&&!d||(c=lv(a,b,function(){if(!Ru(c)){Pu(c);Cs(b);var e=Xa(Ds,b);wm(e,0)}}))}
function lv(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=zl(a);Db(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function kv(a){var b=Ng("A");wb(b,new pb(a));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Wb(a)}
;function mv(a){var b=B.apply(1,arguments);if(!nv(a)||b.some(function(d){return!nv(d)}))throw Error("Only objects may be merged.");
b=v(b);for(var c=b.next();!c.done;c=b.next())ov(a,c.value)}
function ov(a,b){for(var c in b)if(nv(b[c])){if(c in a&&!nv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});ov(a[c],b[c])}else if(pv(b[c])){if(c in a&&!pv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);qv(a[c],b[c])}else a[c]=b[c];return a}
function qv(a,b){b=v(b);for(var c=b.next();!c.done;c=b.next())c=c.value,nv(c)?a.push(ov({},c)):pv(c)?a.push(qv([],c)):a.push(c);return a}
function nv(a){return typeof a==="object"&&!Array.isArray(a)}
function pv(a){return typeof a==="object"&&Array.isArray(a)}
;var rv="absolute_experiments app conditional_experiments debugcss debugjs expflag forced_experiments pbj pbjreload sbb spf spfreload sr_bns_address sttick".split(" ");
function sv(a,b){var c=c===void 0?!0:c;var d=S("VALID_SESSION_TEMPDATA_DOMAINS",[]),e=$b(window.location.href);e&&d.push(e);e=$b(a);if(Jb(d,e)>=0||!e&&a.lastIndexOf("/",0)==0)if(d=document.createElement("a"),wb(d,a),a=d.href)if(a=ac(a),a=bc(a))if(c&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:uu()},b)),f){var f=parseInt(f,10);isFinite(f)&&f>0&&tv(a,b,f)}else tv(a,b)}
function tv(a,b,c){a=uv(a);b=b?dc(b):"";c=c||5;Fu()&&jn(a,b,c)}
function uv(a){for(var b=v(rv),c=b.next();!c.done;c=b.next())a=jc(a,c.value);return"ST-"+Wb(a).toString(36)}
;function vv(a){mq.call(this,1,arguments);this.csn=a}
x(vv,mq);var vq=new nq("screen-created",vv),wv=[],xv=0,yv=new Map,zv=new Map,Av=new Map;
function Bv(a,b,c,d,e){e=e===void 0?!1:e;for(var f=Cv({cttAuthInfo:wu(b)||void 0},b),g=v(d),h=g.next();!h.done;h=g.next()){h=h.value;var k=h.getAsJson();(Ag(k)||!k.trackingParams&&!k.veType)&&cu(Error("Child VE logged with no data"));if(U("no_client_ve_attach_unless_shown")){var l=Dv(h,b);if(k.veType&&!zv.has(l)&&!Av.has(l)&&!e){if(!U("il_attach_cache_limit")||yv.size<1E3){yv.set(l,[a,b,c,h]);return}U("il_attach_cache_limit")&&yv.size>1E3&&cu(new V("IL Attach cache exceeded limit"))}h=Dv(c,b);yv.has(h)?
Ev(c,b):Av.set(h,!0)}}d=d.filter(function(m){m.csn!==b?(m.csn=b,m=!0):m=!1;return m});
c={csn:b,parentVe:c.getAsJson(),childVes:Mb(d,function(m){return m.getAsJson()})};
b==="UNDEFINED_CSN"?Fv("visualElementAttached",f,c):a?Ut("visualElementAttached",c,a,f):so("visualElementAttached",c,f)}
function Fv(a,b,c){wv.push({ze:a,payload:c,Xg:void 0,options:b});xv||(xv=wq())}
function xq(a){if(wv){for(var b=v(wv),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,so(c.ze,c.payload,c.options));wv.length=0}xv=0}
function Dv(a,b){return""+a.getAsJson().veType+a.getAsJson().veCounter+b}
function Ev(a,b){a=Dv(a,b);yv.has(a)&&(b=yv.get(a)||[],Bv(b[0],b[1],b[2],[b[3]],!0),yv.delete(a))}
function Cv(a,b){U("log_sequence_info_on_gel_web")&&(a.sequenceGroup=b);return a}
;function Gv(){try{return!!self.localStorage}catch(a){return!1}}
;function Hv(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Iv(a){if(Gv()){var b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Hv(c);d===void 0||a.includes(d)||self.localStorage.removeItem(c)}}}
function Jv(){if(!Gv())return!1;var a=Bn(),b=Object.keys(window.localStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Hv(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Kv(){var a=!1;try{a=!!window.sessionStorage.getItem("session_logininfo")}catch(b){a=!0}return(S("INNERTUBE_CLIENT_NAME")==="WEB"||S("INNERTUBE_CLIENT_NAME")==="WEB_CREATOR")&&a}
function Lv(a){if(S("LOGGED_IN",!0)&&Kv()){var b=S("VALID_SESSION_TEMPDATA_DOMAINS",[]);var c=$b(window.location.href);c&&b.push(c);c=$b(a);Jb(b,c)>=0||!c&&a.lastIndexOf("/",0)==0?(b=ac(a),(b=bc(b))?(b=uv(b),b=(b=kn(b)||null)?mm(b):{}):b=null):b=null;b==null&&(b={});c=b;var d=void 0;Kv()?(d||(d=S("LOGIN_INFO")),d?(c.session_logininfo=d,c=!0):c=!1):c=!1;c&&sv(a,b)}}
;function Mv(a,b,c){b=b===void 0?{}:b;c=c===void 0?!1:c;var d=S("EVENT_ID");d&&(b.ei||(b.ei=d));b&&sv(a,b);if(c)return!1;Lv(a);var e=e===void 0?{}:e;var f=f===void 0?"":f;var g=g===void 0?window:g;a=ec(a,e);Lv(a);f=a+f;var h=h===void 0?tb:h;a:if(h=h===void 0?tb:h,f instanceof pb)h=f;else{for(a=0;a<h.length;++a)if(b=h[a],b instanceof rb&&b.ne(f)){h=new pb(f);break a}h=void 0}g=g.location;h=vb(h||qb);h!==void 0&&(g.href=h);return!0}
;function Nv(a){if(Cg(S("PLAYER_VARS",{}))!="1"){a&&Sl();try{Ou().then(function(){},function(){}),wm(Nv,18E5)}catch(b){em(b)}}}
;var Ov=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Pv(){var a=a===void 0?window.location.href:a;if(U("kevlar_disable_theme_param"))return null;Yb(Zb(5,a));try{var b=nm(a).theme;return Ov.get(b)||null}catch(c){}return null}
;function Qv(){this.h={};if(this.i=mn()){var a=kn("CONSISTENCY");a&&Rv(this,{encryptedTokenJarContents:a})}}
Qv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=((c=b.Pa.context)==null?void 0:(d=c.request)==null?void 0:d.consistencyTokenJars)||[];var e;if(a=(e=a.responseContext)==null?void 0:e.consistencyTokenJar){e=v(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];Rv(this,a)}};
function Rv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,typeof b.expirationSeconds==="string")){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},c*1E3);
a.i&&jn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Sv=window.location.hostname.split(".").slice(-2).join(".");function Tv(){this.j=-1;var a=S("LOCATION_PLAYABILITY_TOKEN");S("INNERTUBE_CLIENT_NAME")==="TVHTML5"&&(this.h=Uv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var Vv;function Wv(){Vv=E("yt.clientLocationService.instance");Vv||(Vv=new Tv,D("yt.clientLocationService.instance",Vv));return Vv}
p=Tv.prototype;
p.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});if(this.i)a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(this.i.coords.latitude*1E7),a.client.locationInfo.longitudeE7=Math.floor(this.i.coords.longitude*1E7),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0;else if(this.o||this.locationPlayabilityToken)a.client.locationPlayabilityToken=this.o||
this.locationPlayabilityToken};
p.handleResponse=function(a){var b;a=(b=a.responseContext)==null?void 0:b.locationPlayabilityToken;a!==void 0&&(this.locationPlayabilityToken=a,this.i=void 0,S("INNERTUBE_CLIENT_NAME")==="TVHTML5"?(this.h=Uv(this))&&this.h.set("yt-location-playability-token",a,15552E3):jn("YT_CL",JSON.stringify({loctok:a}),15552E3,Sv,!0))};
function Uv(a){return a.h===void 0?new jo("yt-client-location"):a.h}
p.clearLocationPlayabilityToken=function(a){a==="TVHTML5"?(this.h=Uv(this))&&this.h.remove("yt-location-playability-token"):ln("YT_CL");this.o=void 0;this.j!==-1&&(clearTimeout(this.j),this.j=-1)};
p.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;S("INNERTUBE_CLIENT_NAME")==="MWEB"&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
p.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);if(a==null?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};
p.createLocationInfo=function(a){var b={};a=a.coords;if(a==null?0:a.latitude)b.latitudeE7=Math.floor(a.latitude*1E7);if(a==null?0:a.longitude)b.longitudeE7=Math.floor(a.longitude*1E7);return b};function Xv(a){var b={"Content-Type":"application/json"};S("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=S("EOM_VISITOR_DATA"):S("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=S("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=S("LOGGED_IN",!1);S("DEBUG_SETTINGS_METADATA")&&(b["X-Debug-Settings-Metadata"]=S("DEBUG_SETTINGS_METADATA"));a!=="cors"&&((a=S("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=S("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=S("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=S("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;function Yv(){this.h={}}
Yv.prototype.contains=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)};
Yv.prototype.get=function(a){if(this.contains(a))return this.h[a]};
Yv.prototype.set=function(a,b){this.h[a]=b};
Yv.prototype.remove=function(a){delete this.h[a]};function Zv(){this.mappings=new Yv}
Zv.prototype.getModuleId=function(a){return a.serviceId.getModuleId()};
Zv.prototype.get=function(a){a:{var b=this.mappings.get(a.toString());switch(b.type){case "mapping":a=b.value;break a;case "factory":b=b.value();this.mappings.set(a.toString(),{type:"mapping",value:b});a=b;break a;default:a=Bb(b)}}return a};
new Zv;function $v(a){return function(){return new a}}
;var aw={},bw=(aw.WEB_UNPLUGGED="^unplugged/",aw.WEB_UNPLUGGED_ONBOARDING="^unplugged/",aw.WEB_UNPLUGGED_OPS="^unplugged/",aw.WEB_UNPLUGGED_PUBLIC="^unplugged/",aw.WEB_CREATOR="^creator/",aw.WEB_KIDS="^kids/",aw.WEB_EXPERIMENTS="^experiments/",aw.WEB_MUSIC="^music/",aw.WEB_REMIX="^music/",aw.WEB_MUSIC_EMBEDDED_PLAYER="^music/",aw.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",aw);
function cw(a){var b=b===void 0?"UNKNOWN_INTERFACE":b;if(a.length===1)return a[0];var c=bw[b];if(c){c=new RegExp(c);for(var d=v(a),e=d.next();!e.done;e=d.next())if(e=e.value,c.exec(e))return e}var f=[];Object.entries(bw).forEach(function(g){var h=v(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
c=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
d=v(a);for(e=d.next();!e.done;e=d.next())if(e=e.value,!c.exec(e))return e;return a[0]}
;function dw(){}
dw.prototype.D=function(a,b,c){b=b===void 0?{}:b;c=c===void 0?hn:c;var d=a.clickTrackingParams,e=this.o,f=!1;f=f===void 0?!1:f;e=e===void 0?!1:e;var g=S("INNERTUBE_CONTEXT");if(g){g=Fg(g);U("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;h.clientName==="MWEB"&&h.clientFormFactor!=="AUTOMOTIVE_FORM_FACTOR"&&(h.clientFormFactor=S("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=
window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=k===void 0?!1:k;qn();var l="USER_INTERFACE_THEME_LIGHT";tn(165)?l="USER_INTERFACE_THEME_DARK":tn(174)?l="USER_INTERFACE_THEME_LIGHT":!U("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(l="USER_INTERFACE_THEME_DARK");
k=k?l:Pv()||l;h.userInterfaceTheme=k;if(!f){if(k=yn())h.connectionType=k;U("web_log_effective_connection_type")&&(k=zn())&&(g.client.effectiveConnectionType=k)}var m;if(U("web_log_memory_total_kbytes")&&((m=C.navigator)==null?0:m.deviceMemory)){var n;m=(n=C.navigator)==null?void 0:n.deviceMemory;g.client.memoryTotalKbytes=""+m*1E6}U("web_gcf_hashes_innertube")&&(k=fq())&&(n=k.coldConfigData,m=k.coldHashData,k=k.hotHashData,g.client.configInfo=g.client.configInfo||{},n&&(g.client.configInfo.coldConfigData=
n),m&&(g.client.configInfo.coldHashData=m),k&&(g.client.configInfo.hotHashData=k));n=nm(C.location.href);!U("web_populate_internal_geo_killswitch")&&n.internalcountrycode&&(h.internalGeo=n.internalcountrycode);h.clientName==="MWEB"||h.clientName==="WEB"?(h.mainAppWebInfo={graftUrl:C.location.href},U("kevlar_woffle")&&cn.h&&(n=cn.h,h.mainAppWebInfo.pwaInstallabilityStatus=!n.h&&n.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=dn(),
h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&navigator.share!==void 0):h.clientName==="TVHTML5"&&(!U("web_lr_app_quality_killswitch")&&(n=S("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:n})),n=S("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:n}));if(!U("web_populate_time_zone_itc_killswitch")){b:{if(typeof Intl!=="undefined")try{var r=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(ua){}r=
void 0}r&&(h.timeZone=r)}(r=S("EXPERIMENTS_TOKEN",""))?h.experimentsToken=r:delete h.experimentsToken;r=Am();Qv.h||(Qv.h=new Qv);h=Qv.h.h;n=[];m=0;for(var t in h)n[m++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:r,consistencyTokenJars:n});!U("web_prequest_context_killswitch")&&(t=S("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=t);r=qn();t=tn(58);r=r.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);r&&(g.user.lockedSafetyMode=
!0);U("warm_op_csn_cleanup")?e&&(f=uu())&&(g.clientScreenNonce=f):!f&&(f=uu())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=E("yt.mdx.remote.remoteClient_"))g.remoteClient=d;Wv().setLocationOnInnerTubeContext(g);try{var w=qm(),y=w.bid;delete w.bid;g.adSignalsInfo={params:[],bid:y};var z=v(Object.entries(w));for(var G=z.next();!G.done;G=z.next()){var I=v(G.value),M=I.next().value,O=I.next().value;w=M;y=O;d=void 0;(d=g.adSignalsInfo.params)==null||d.push({key:w,value:""+
y})}var ta;if(((ta=g.client)==null?void 0:ta.clientName)==="TVHTML5"){var lb=S("INNERTUBE_CONTEXT");lb.adSignalsInfo&&(g.adSignalsInfo.advertisingId=lb.adSignalsInfo.advertisingId,g.adSignalsInfo.advertisingIdSignalType="DEVICE_ID_TYPE_CONNECTED_TV_IFA",g.adSignalsInfo.limitAdTracking=lb.adSignalsInfo.limitAdTracking)}}catch(ua){bu(ua)}z=g}else bu(Error("Error: No InnerTubeContext shell provided in ytconfig.")),z={};z={context:z};if(G=this.i(a)){this.h(z,G,b);var T;b="/youtubei/v1/"+cw(this.j());
(G=(T=kt(a.commandMetadata,Gl))==null?void 0:T.apiUrl)&&(b=G);T=b;(b=S("INNERTUBE_HOST_OVERRIDE"))&&(T=String(b)+String(ac(T)));b={};U("web_api_key_killswitch")&&(b.key=S("INNERTUBE_API_KEY"));U("json_condensed_response")&&(b.prettyPrint="false");T=om(T,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:T,hb:Eu(T),Pa:z,config:a};a.config.Ub?a.config.Ub.identity=c:a.config.Ub={identity:c};return a}bu(new V("Error: Failed to create Request from Command.",a))};
da.Object.defineProperties(dw.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!1}}});
function ew(){}
x(ew,dw);function fw(){}
x(fw,ew);fw.prototype.D=function(){return{input:"/getDatasyncIdsEndpoint",hb:Eu("/getDatasyncIdsEndpoint","GET"),Pa:{}}};
fw.prototype.j=function(){return[]};
fw.prototype.i=function(){};
fw.prototype.h=function(){};var gw={},hw=(gw.GET_DATASYNC_IDS=$v(fw),gw);function iw(a){var b;(b=E("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},D("ytcsi."+(a||"")+"data_",b));return b}
function jw(){var a=iw();a.info||(a.info={});return a.info}
function kw(a){a=iw(a);a.metadata||(a.metadata={});return a.metadata}
function lw(a){a=iw(a);a.tick||(a.tick={});return a.tick}
function mw(a){a=iw(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function nw(a){a=mw(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function ow(a){var b=iw(a).nonce;b||(b=ku(),iw(a).nonce=b);return b}
;function pw(){var a=E("ytcsi.debug");a||(a=[],D("ytcsi.debug",a),D("ytcsi.reference",{}));return a}
function qw(a){a=a||"";var b=E("ytcsi.reference");b||(pw(),b=E("ytcsi.reference"));if(b[a])return b[a];var c=pw(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var X={},rw=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
X["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",X["asset.composition_ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_OWNERSHIP",X["asset.composition_policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION_POLICY",X["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",X["asset.history"]="LATENCY_ACTION_CREATOR_CMS_ASSET_HISTORY",X["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",X["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",X["asset.metadata"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",X["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",X["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",X["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",X["asset.shares"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SHARES",X["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",X["asset_group.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_ASSETS",X["asset_group.campaigns"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CAMPAIGNS",
X["asset_group.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_CLAIMED_VIDEOS",X["asset_group.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUP_METADATA",X["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",X.browse="LATENCY_ACTION_BROWSE",X.cast_splash="LATENCY_ACTION_CAST_SPLASH",X.channel_activity="LATENCY_ACTION_KIDS_CHANNEL_ACTIVITY",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",
X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",
X["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X.commerce_transaction="LATENCY_ACTION_COMMERCE_TRANSACTION",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",
X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.favorites="LATENCY_ACTION_FAVORITES",X.home="LATENCY_ACTION_HOME",X.inboarding="LATENCY_ACTION_INBOARDING",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",
X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.mini_app="LATENCY_ACTION_MINI_APP_PLAY",X.notification_settings="LATENCY_ACTION_KIDS_NOTIFICATION_SETTINGS",X.onboarding="LATENCY_ACTION_ONBOARDING",X.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",X["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",X["owner.analytics"]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS",X["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",X["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",X["owner.asset_groups"]=
"LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",X["owner.bulk"]="LATENCY_ACTION_CREATOR_CMS_BULK_HISTORY",X["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",X["owner.channel_invites"]="LATENCY_ACTION_CREATOR_CMS_CHANNEL_INVITES",X["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",X["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",X["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",X["owner.delivery"]=
"LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",X["owner.delivery_templates"]="LATENCY_ACTION_CREATOR_CMS_DELIVERY_TEMPLATES",X["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",X["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",X["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",X["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",X["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",X["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",X["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",
X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["playlist.videos"]="LATENCY_ACTION_CREATOR_PLAYLIST_VIDEO_LIST",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",
X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",X.red="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.premium="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE",X.privacy_policy="LATENCY_ACTION_KIDS_PRIVACY_POLICY",X.search_overview_answer="LATENCY_ACTION_SEARCH_OVERVIEW_ANSWER",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.store="LATENCY_ACTION_STORE",X.supervision_dashboard="LATENCY_ACTION_KIDS_SUPERVISION_DASHBOARD",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]=
"LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.copyright"]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]=
"LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",X["video.rights_management"]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",
X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",X.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",X);function sw(a,b){mq.call(this,1,arguments);this.timer=b}
x(sw,mq);var tw=new nq("aft-recorded",sw);D("ytLoggingGelSequenceIdObj_",C.ytLoggingGelSequenceIdObj_||{});var uw=C.ytLoggingLatencyUsageStats_||{};D("ytLoggingLatencyUsageStats_",uw);function vw(){this.h=0}
function ww(){vw.h||(vw.h=new vw);return vw.h}
vw.prototype.tick=function(a,b,c,d){xw(this,"tick_"+a+"_"+b)||so("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
vw.prototype.info=function(a,b,c){var d=Object.keys(a).join("");xw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,so("latencyActionInfo",a,{cttAuthInfo:c}))};
vw.prototype.jspbInfo=function(){};
vw.prototype.span=function(a,b,c){var d=Object.keys(a).join("");xw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,so("latencyActionSpan",a,{cttAuthInfo:c}))};
function xw(a,b){uw[b]=uw[b]||{count:0};var c=uw[b];c.count++;c.time=W();a.h||(a.h=Dn(function(){var d=W(),e;for(e in uw)uw[e]&&d-uw[e].time>6E4&&delete uw[e];a&&(a.h=0)},5E3));
return c.count>5?(c.count===6&&Math.random()*1E5<1&&(c=new V("CSI data exceeded logging limit with key",b.split("_")),b.indexOf("plev")>=0||cu(c)),!0):!1}
;var yw=window;function zw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function Aw(){var a;if(U("csi_use_performance_navigation_timing")||U("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=Y==null?void 0:(a=Y.getEntriesByType)==null?void 0:(b=a.call(Y,"navigation"))==null?void 0:(c=b[0])==null?void 0:(d=c.toJSON)==null?void 0:d.call(c);e?(e.requestStart=Bw(e.requestStart),e.responseEnd=Bw(e.responseEnd),e.redirectStart=Bw(e.redirectStart),e.redirectEnd=Bw(e.redirectEnd),e.domainLookupEnd=Bw(e.domainLookupEnd),e.connectStart=Bw(e.connectStart),e.connectEnd=
Bw(e.connectEnd),e.responseStart=Bw(e.responseStart),e.secureConnectionStart=Bw(e.secureConnectionStart),e.domainLookupStart=Bw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=Y.timing}else a=U("csi_performance_timing_to_object")?JSON.parse(JSON.stringify(Y.timing)):Y.timing;return a}
function Bw(a){return Math.round(Cw()+a)}
function Cw(){return(U("csi_use_time_origin")||U("csi_use_time_origin_tvhtml5"))&&Y.timeOrigin?Math.floor(Y.timeOrigin):Y.timing.navigationStart}
var Y=yw.performance||yw.mozPerformance||yw.msPerformance||yw.webkitPerformance||new zw;var Dw=!1,Ew=!1,Fw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="preload"][name="player/embed"]':"pej",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",
'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",
'script[name="mobile_blazer_watch_mod"]':"mbwj"};Wa(Y.clearResourceTimings||Y.webkitClearResourceTimings||Y.mozClearResourceTimings||Y.msClearResourceTimings||Y.oClearResourceTimings||fi,Y);function Gw(a,b){if(!U("web_csi_action_sampling_enabled")||!iw(b).actionDisabled){var c=qw(b||"");mv(c.info,a);a.loadType&&(c=a.loadType,kw(b).loadType=c);mv(nw(b),a);c=ow(b);b=iw(b).cttAuthInfo;ww().info(a,c,b)}}
function Hw(){var a,b,c,d;return((d=Ns().resolve(new Hs(bq))==null?void 0:(a=cq())==null?void 0:(b=a.loggingHotConfig)==null?void 0:(c=b.csiConfig)==null?void 0:c.debugTicks)!=null?d:[]).map(function(e){return Object.values(e)[0]})}
function Z(a,b,c){if(!U("web_csi_action_sampling_enabled")||!iw(c).actionDisabled){var d=ow(c),e;if(e=U("web_csi_debug_sample_enabled")&&d){(Ns().resolve(new Hs(bq))==null?0:cq())&&!Ew&&(Ew=!0,Z("gcfl",W(),c));var f,g,h;e=(Ns().resolve(new Hs(bq))==null?void 0:(f=cq())==null?void 0:(g=f.loggingHotConfig)==null?void 0:(h=g.csiConfig)==null?void 0:h.debugSampleWeight)||0;if(f=e!==0)b:{f=Hw();if(f.length>0)for(g=0;g<f.length;g++)if(a===f[g]){f=!0;break b}f=!1}if(f){for(g=f=0;g<d.length;g++)f=f*31+d.charCodeAt(g),
g<d.length-1&&(f%=0x800000000000);e=f%1E5%e!==0;iw(c).debugTicksExcludedLogged||(f={},f.debugTicksExcluded=e,Gw(f,c));iw(c).debugTicksExcludedLogged=!0}else e=!1}if(!e){if(a[0]!=="_"&&(e=a,f=b,Y.mark))if(e.startsWith("mark_")||(e="mark_"+e),c&&(e+=" ("+c+")"),f===void 0||U("web_csi_disable_alt_time_performance_mark"))Y.mark(e);else{f=U("csi_use_performance_navigation_timing")||U("csi_use_performance_navigation_timing_tvhtml5")?f-Y.timeOrigin:f-(Y.timeOrigin||Y.timing.navigationStart);try{Y.mark(e,
{startTime:f})}catch(k){}}e=qw(c||"");e.tick[a]=b||W();if(e.callback&&e.callback[a])for(e=v(e.callback[a]),f=e.next();!f.done;f=e.next())f=f.value,f();e=mw(c);e.gelTicks&&(e.gelTicks[a]=!0);f=lw(c);e=b||W();U("log_repeated_ytcsi_ticks")?a in f||(f[a]=e):f[a]=e;f=iw(c).cttAuthInfo;a==="_start"?(a=ww(),xw(a,"baseline_"+d)||so("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:f})):ww().tick(a,d,b,f);Iw(c);return e}}}
function Jw(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=es+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Kw(){function a(f,g,h){g=g.match("_rid")?g.split("_rid")[0]:g;typeof h==="number"&&(h=JSON.stringify(h));f.requestIds?f.requestIds.push({endpoint:g,id:h}):f.requestIds=[{endpoint:g,id:h}]}
for(var b={},c=v(Object.entries(S("TIMING_INFO",{}))),d=c.next();!d.done;d=c.next()){var e=v(d.value);d=e.next().value;e=e.next().value;switch(d){case "GetBrowse_rid":a(b,d,e);break;case "GetGuide_rid":a(b,d,e);break;case "GetHome_rid":a(b,d,e);break;case "GetPlayer_rid":a(b,d,e);break;case "GetSearch_rid":a(b,d,e);break;case "GetSettings_rid":a(b,d,e);break;case "GetTrending_rid":a(b,d,e);break;case "GetWatchNext_rid":a(b,d,e);break;case "yt_red":b.isRedSubscriber=!!e;break;case "yt_ad":b.isMonetized=
!!e}}return b}
function Lw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;d==="SCRIPT"?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):d==="LINK"&&(c=a.href);Eb(window)&&a.setAttribute("nonce",Eb(window));return c?(a=Y.getEntriesByName(c))&&a[0]&&(a=a[0],c=Cw(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),a.transferSize!==void 0&&a.transferSize===0)?!0:!1:!1}
function Mw(){var a=window.location.protocol,b=Y.getEntriesByType("resource");b=Lb(b,function(c){return c.name.indexOf(a+"//fonts.gstatic.com/s/")===0});
(b=Nb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&b.startTime>0&&b.responseEnd>0&&(Z("wffs",Bw(b.startTime)),Z("wffe",Bw(b.responseEnd)))}
function Nw(a){var b=Ow("aft",a);if(b)return b;b=S((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Ow(b[d],a);if(e)return e}return NaN}
function Ow(a,b){if(a=lw(b)[a])return typeof a==="number"?a:a[a.length-1]}
function Iw(a){var b=Ow("_start",a),c=Nw(a),d=U("enable_cow_info_csi")||!Dw;b&&c&&d&&(sq(tw,new sw(Math.round(c-b),a)),Dw=!0)}
function Pw(){if(Y.getEntriesByType){var a=Y.getEntriesByType("paint");if(a=Ob(a,function(c){return c.name==="first-paint"}))return Bw(a.startTime)}var b;
U("csi_use_performance_navigation_timing")||U("csi_use_performance_navigation_timing_tvhtml5")?b=Y.getEntriesByType("first-paint")[0].startTime:b=Y.timing.dh;return b?Math.max(0,b):0}
;function Qw(a,b){dm(function(){qw("").info.actionType=a;b&&$l("TIMING_AFT_KEYS",b);$l("TIMING_ACTION",a);var c=Kw();Object.keys(c).length>0&&Gw(c);c={isNavigation:!0,actionType:rw[S("TIMING_ACTION")]||"LATENCY_ACTION_UNKNOWN"};var d=S("PREVIOUS_ACTION");d&&(c.previousAction=rw[d]||"LATENCY_ACTION_UNKNOWN");if(d=S("CLIENT_PROTOCOL"))c.httpProtocol=d;if(d=S("CLIENT_TRANSPORT"))c.transportProtocol=d;(d=uu())&&d!=="UNDEFINED_CSN"&&(c.clientScreenNonce=d);d=Jw();if(d===1||d===-1)c.isVisible=!0;kw();jw();
c.loadType="cold";d=jw();var e=Aw(),f=Cw(),g=S("CSI_START_TIMESTAMP_MILLIS",0);g>0&&!U("embeds_web_enable_csi_start_override_killswitch")&&(f=g);f&&(Z("srt",e.responseStart),d.prerender!==1&&Z("_start",f,void 0));d=Pw();d>0&&Z("fpt",d);d=Aw();d.isPerformanceNavigationTiming&&Gw({performanceNavigationTiming:!0},void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);d.redirectEnd-d.redirectStart>0&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,
void 0));d.domainLookupEnd-d.domainLookupStart>0&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));d.connectEnd-d.connectStart>0&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=Cw()&&d.connectEnd-d.secureConnectionStart>0&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));Y&&"getEntriesByType"in Y&&Mw();d=[];if(document.querySelector&&Y&&Y.getEntriesByName)for(var h in Fw)Fw.hasOwnProperty(h)&&(e=Fw[h],
Lw(h,e)&&d.push(e));if(d.length>0)for(c.resourceInfo=[],h=v(d),d=h.next();!d.done;d=h.next())c.resourceInfo.push({resourceCache:d.value});Gw(c);c=mw();c.preLoggedGelInfos||(c.preLoggedGelInfos=[]);h=c.preLoggedGelInfos;c=nw();d=void 0;for(e=0;e<h.length;e++)if(f=h[e],f.loadType){d=f.loadType;break}if(kw().loadType==="cold"&&(c.loadType==="cold"||d==="cold")){d=lw();e=mw();e=e.gelTicks?e.gelTicks:e.gelTicks={};for(var k in d)if(!(k in e))if(typeof d[k]==="number")Z(k,Ow(k));else if(U("log_repeated_ytcsi_ticks"))for(f=
v(d[k]),g=f.next();!g.done;g=f.next())g=g.value,Z(k.slice(1),g);k={};d=!1;h=v(h);for(e=h.next();!e.done;e=h.next())d=e.value,mv(c,d),mv(k,d),d=!0;d&&Gw(k)}D("ytglobal.timingready_",!0);k=S("TIMING_ACTION");E("ytglobal.timingready_")&&k&&Rw()&&Nw()&&Iw()})()}
function Rw(){return dm(function(){return Sw()})()}
function Tw(a,b,c){dm(Gw)(a,b,c===void 0?!1:c)}
function Uw(a,b,c){return dm(Z)(a,b,c)}
function Sw(){return dm(function(){return"_start"in lw()})()}
function Vw(){dm(function(){var a=ow();requestAnimationFrame(function(){setTimeout(function(){a===ow()&&Uw("ol",void 0,void 0)},0)})})()}
var Ww=window;Ww.ytcsi&&(Ww.ytcsi.infoGel=Tw,Ww.ytcsi.tick=Uw);var Xw="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD shorts_prefetch".split(" "),Yw=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse","type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.PlayerResponse"];function Zw(a,b,c,d){this.D=a;this.fa=b;this.o=c;this.j=d;this.i=void 0;this.h=new Map;a.Pb||(a.Pb={});a.Pb=Object.assign({},hw,a.Pb)}
function $w(a,b,c,d){if(Zw.h!==void 0){if(d=Zw.h,a=[a!==d.D,b!==d.fa,c!==d.o,!1,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new V("InnerTubeTransportService is already initialized",a);
}else Zw.h=new Zw(a,b,c,d)}
function ax(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=c===void 0?hn:c;var d=bx(a,b);return d?new si(function(e,f){var g,h,k,l,m;return A(function(n){switch(n.h){case 1:return n.yield(d,2);case 2:g=n.i;h=g.D(b,void 0,c);if(!h){f(new V("Error: Failed to build request for command.",b));n.F(0);break}Lv(h.input);l=((k=h.hb)==null?void 0:k.mode)==="cors"?"cors":void 0;if(a.o.af){var r=h.config,t,w=r==null?void 0:(t=r.Ub)==null?void 0:t.sessionIndex,y;r=((y=kt(r==null?void 0:r.command,
Hl))==null?void 0:y.signal)==="GET_ACCOUNT_MENU"?!0:!1;w=gn(0,{sessionIndex:w,dd:r});m=Object.assign({},Xv(l),w);n.F(4);break}return n.yield(cx(h.config,l),5);case 5:m=n.i;case 4:e(dx(a,h,m)),n.h=0}})}):xi(new V("Error: No request builder found for command.",b))}
function ex(a,b,c){var d;if(b&&!(b==null?0:(d=b.sequenceMetaData)==null?0:d.skipProcessing)&&a.j){d=v(Xw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function dx(a,b,c){var d=d===void 0?function(){}:d;
var e,f,g,h,k,l,m,n,r,t,w,y,z,G,I,M,O,ta,lb,T,ua,La,Ma,Ka,ah,bh,Qr,Rr,Sr,Tr;return A(function(fa){switch(fa.h){case 1:fa.F(2);break;case 3:if((e=fa.i)&&!e.isExpired())return fa.return(Promise.resolve(e.h()));case 2:if(!((f=b)==null?0:(g=f.Pa)==null?0:g.context)){fa.F(4);break}h=b.Pa.context;fa.F(5);break;case 5:k=v([]),l=k.next();case 8:if(l.done){fa.F(4);break}m=l.value;return fa.yield(m.fh(h),9);case 9:l=k.next();fa.F(8);break;case 4:if((n=a.i)==null||!n.kh(b.input,b.Pa)){fa.F(12);break}return fa.yield(a.i.Zg(b.input,
b.Pa),13);case 13:return r=fa.i,U("kevlar_process_local_innertube_responses_killswitch")||ex(a,r,b),fa.return(r);case 12:return(y=(w=b.config)==null?void 0:w.ih)&&a.h.has(y)?t=a.h.get(y):(z=JSON.stringify(b.Pa),M=(I=(G=b.hb)==null?void 0:G.headers)!=null?I:{},b.hb=Object.assign({},b.hb,{headers:Object.assign({},M,c)}),O=Object.assign({},b.hb),b.hb.method==="POST"&&(O=Object.assign({},O,{body:z})),((ta=b.config)==null?0:ta.Fe)&&Uw(b.config.Fe),lb=function(){return a.fa.fetch(b.input,O,b.config)},t=
lb(),y&&a.h.set(y,t)),fa.yield(t,14);
case 14:if((T=fa.i)&&"error"in T&&((ua=T)==null?0:(La=ua.error)==null?0:La.details))for(Ma=T.error.details,Ka=v(Ma),ah=Ka.next();!ah.done;ah=Ka.next())bh=ah.value,(Qr=bh["@type"])&&Yw.indexOf(Qr)>-1&&(delete bh["@type"],T=bh);y&&a.h.has(y)&&a.h.delete(y);((Rr=b.config)==null?0:Rr.Ge)&&Uw(b.config.Ge);if(T||(Sr=a.i)==null||!Sr.Qg(b.input,b.Pa)){fa.F(15);break}return fa.yield(a.i.Yg(b.input,b.Pa),16);case 16:T=fa.i;case 15:return ex(a,T,b),((Tr=b.config)==null?0:Tr.Be)&&Uw(b.config.Be),d(),fa.return(T||
void 0)}})}
function bx(a,b){a:{a=a.D;var c,d=(c=kt(b,Hl))==null?void 0:c.signal;if(d&&a.Pb&&(c=a.Pb[d])){var e=c();break a}var f;if((c=(f=kt(b,Fl))==null?void 0:f.request)&&a.Pd&&(f=a.Pd[c])){e=f();break a}for(e in b)if(a.Uc[e]&&(b=a.Uc[e])){e=b();break a}e=void 0}if(e!==void 0)return Promise.resolve(e)}
function cx(a,b){var c,d,e,f,g,h,k;return A(function(l){if(l.h==1){e=(c=a)==null?void 0:(d=c.Ub)==null?void 0:d.sessionIndex;h=((g=kt((f=a)==null?void 0:f.command,Hl))==null?void 0:g.signal)==="GET_ACCOUNT_MENU"?!0:!1;var m=l.yield;var n=gn(0,{sessionIndex:e,dd:h});if(!(n instanceof si)){var r=new si(fi);ti(r,2,n);n=r}return m.call(l,n,2)}k=l.i;return l.return(Promise.resolve(Object.assign({},Xv(b),k)))})}
;var fx=new Gs("INNERTUBE_TRANSPORT_TOKEN");function gx(){}
x(gx,ew);gx.prototype.j=function(){return Zu};
gx.prototype.i=function(a){return kt(a,Rl)||void 0};
gx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
da.Object.defineProperties(gx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function hx(){}
x(hx,ew);hx.prototype.j=function(){return $u};
hx.prototype.i=function(a){return kt(a,Ql)||void 0};
hx.prototype.h=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
da.Object.defineProperties(hx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});var ix=new Gs("SHARE_CLIENT_PARAMS_PROVIDER_TOKEN");function jx(a){this.u=a}
x(jx,ew);jx.prototype.j=function(){return Uu};
jx.prototype.i=function(a){return kt(a,Ll)||kt(a,Ml)||kt(a,Kl)};
jx.prototype.h=function(a,b){b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);if(b.clientParamIdentifier){var c;if((c=this.u)==null?0:c.h(b.clientParamIdentifier))a.clientParams=this.u.i(b.clientParamIdentifier)}};
jx[Fs]=[ix];function kx(){}
x(kx,ew);kx.prototype.j=function(){return Wu};
kx.prototype.i=function(a){return kt(a,Jl)||void 0};
kx.prototype.h=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
da.Object.defineProperties(kx.prototype,{o:{configurable:!0,enumerable:!0,get:function(){return!0}}});function lx(){}
x(lx,ew);lx.prototype.j=function(){return Xu};
lx.prototype.i=function(a){return kt(a,Pl)||void 0};
lx.prototype.h=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function mx(){}
x(mx,ew);mx.prototype.j=function(){return Yu};
mx.prototype.i=function(a){return kt(a,Ol)||void 0};
mx.prototype.h=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function nx(){}
x(nx,ew);nx.prototype.j=function(){return Vu};
nx.prototype.i=function(a){return kt(a,Nl)};
nx.prototype.h=function(a,b,c){c=c===void 0?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};function ox(a,b){var c=B.apply(2,arguments);a=a===void 0?0:a;V.call(this,b,c);this.errorType=a;Object.setPrototypeOf(this,this.constructor.prototype)}
x(ox,V);var px=new Gs("NETWORK_SLI_TOKEN");function qx(a){this.h=a}
qx.prototype.fetch=function(a,b,c){var d=this,e;return A(function(f){e=rx(d,a,b);return f.return(fetch(e).then(function(g){return d.handleResponse(g,c)}).catch(function(g){cu(g);
if((c==null?0:c.Vd)&&g instanceof ox&&g.errorType===1)return Promise.reject(g)}))})};
function rx(a,b,c){if(a.h){var d=Yb(Zb(5,jc(b,"key")))||"/UNKNOWN_PATH";a.h.start(d)}a=c;U("wug_networking_gzip_request")&&(a=Uq(c));return new window.Request(b,a)}
qx.prototype.handleResponse=function(a,b){var c=a.text().then(function(d){if((b==null?0:b.oe)&&a.ok)return Uf(b.oe,d);d=d.replace(")]}'","");if((b==null?0:b.Vd)&&d)try{var e=JSON.parse(d)}catch(g){throw new ox(1,"JSON parsing failed after fetch");}var f;return(f=e)!=null?f:JSON.parse(d)});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Ug(),c=c.then(function(d){cu(new V("Error: API fetch failed",a.status,a.url,d));return Object.assign({},d,{errorMetadata:{status:a.status}})}));
return c};
qx[Fs]=[new Hs(px)];var sx=new Gs("NETWORK_MANAGER_TOKEN");var tx;function ux(){var a,b,c;return A(function(d){if(d.h==1)return a=Ns().resolve(fx),a?d.yield(ax(a),2):(cu(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return cu(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Sg;return d.return(c)}cu(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;function vx(){var a;return(a=S("WEB_PLAYER_CONTEXT_CONFIGS"))==null?void 0:a.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER}
;var wx=C.caches,xx;function yx(a){var b=a.indexOf(":");return b===-1?{md:a}:{md:a.substring(0,b),datasyncId:a.substring(b+1)}}
function zx(){return A(function(a){if(xx!==void 0)return a.return(xx);xx=new Promise(function(b){var c;return A(function(d){switch(d.h){case 1:return ya(d,2),d.yield(wx.open("test-only"),4);case 4:return d.yield(wx.delete("test-only"),5);case 5:d.h=3;d.o=0;break;case 2:if(c=za(d),c instanceof Error&&c.name==="SecurityError")return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(xx)})}
function Ax(a){var b,c,d,e,f,g,h;A(function(k){if(k.h==1)return k.yield(zx(),2);if(k.h!=3){if(!k.i)return k.return(!1);b=[];return k.yield(wx.keys(),3)}c=k.i;d=v(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=yx(f),h=g.datasyncId,!h||a.includes(h)||b.push(wx.delete(f));return k.return(Promise.all(b).then(function(l){return l.some(function(m){return m})}))})}
function Bx(){var a,b,c,d,e,f,g;return A(function(h){if(h.h==1)return h.yield(zx(),2);if(h.h!=3){if(!h.i)return h.return(!1);a=Bn("cache contains other");return h.yield(wx.keys(),3)}b=h.i;c=v(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=yx(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Cx(){try{return!!self.sessionStorage}catch(a){return!1}}
;function Dx(a){a=a.match(/(.*)::.*::.*/);if(a!==null)return a[1]}
function Ex(a){if(Cx()){var b=Object.keys(window.sessionStorage);b=v(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Dx(c);d===void 0||a.includes(d)||self.sessionStorage.removeItem(c)}}}
function Fx(){if(!Cx())return!1;var a=Bn(),b=Object.keys(window.sessionStorage);b=v(b);for(var c=b.next();!c.done;c=b.next())if(c=Dx(c.value),c!==void 0&&c!==a)return!0;return!1}
;function Gx(){ux().then(function(a){a&&(Hp(a),Ax(a),Iv(a),Ex(a))})}
function Hx(){var a=new Mr;Kj.qa(function(){var b,c,d,e,f;return A(function(g){switch(g.h){case 1:if(U("ytidb_clear_optimizations_killswitch")){g.F(2);break}b=Bn("clear");if(b.startsWith("V")&&b.endsWith("||")){var h=[b];Hp(h);Ax(h);Iv(h);Ex(h);return g.return()}c=Jv();d=Fx();return g.yield(Bx(),3);case 3:return e=g.i,g.yield(Ip(),4);case 4:if(f=g.i,!(c||d||e||f))return g.return();case 2:a.wa()?Gx():a.h.add("publicytnetworkstatus-online",Gx,!0,void 0,void 0),g.h=0}})})}
;function Ix(){this.state=1;this.h=null}
p=Ix.prototype;p.initialize=function(a,b,c){if(a.program){var d,e=(d=a.interpreterUrl)!=null?d:null;if(a.interpreterSafeScript){var f=a.interpreterSafeScript;f?((f=f.privateDoNotAccessOrElseSafeScriptWrappedValue)?(d=fb(),f=new Fb(d?d.createScript(f):f)):f=null,d=f):d=null}else d=(f=a.interpreterScript)!=null?f:null;a.interpreterSafeUrl&&(e=yl(a.interpreterSafeUrl).toString());Jx(this,d,e,a.program,b,c)}else cu(Error("Cannot initialize botguard without program"))};
function Jx(a,b,c,d,e,f){var g=g===void 0?"trayride":g;c?(a.state=2,cv(c,function(){window[g]?Kx(a,d,g,e):(a.state=3,ev(c),cu(new V("Unable to load Botguard","from "+c)))},f)):b?(f=Ng("SCRIPT"),b instanceof Fb?Hb(f,b):f.textContent=b,f.nonce=Eb(window),document.head.appendChild(f),document.head.removeChild(f),window[g]?Kx(a,d,g,e):(a.state=4,cu(new V("Unable to load Botguard from JS")))):cu(new V("Unable to load VM; no url or JS provided"))}
p.isLoading=function(){return this.state===2};
function Kx(a,b,c,d){a.state=5;try{var e=new wj({program:b,be:c,De:U("att_web_record_metrics"),ue:{Aa:"aGIf"}});e.We.then(function(){a.state=6;d&&d(b)});
a.Kc(e)}catch(f){a.state=7,f instanceof Error&&cu(f)}}
p.invoke=function(a){a=a===void 0?{}:a;return this.Nc()?this.Cd({Vc:a}):null};
p.dispose=function(){this.Kc(null);this.state=8};
p.Nc=function(){return!!this.h};
p.Cd=function(a){return this.h.vd(a)};
p.Kc=function(a){qg(this.h);this.h=a};var Lx=[],Mx=!1;function Nx(){if(!U("disable_biscotti_fetch_for_ad_blocker_detection")&&!U("disable_biscotti_fetch_entirely_for_all_web_clients")&&Fu()){var a=S("PLAYER_VARS",{});if(Cg(a)!="1"&&!Gu(a)){var b=function(){Mx=!0;"google_ad_status"in window?$l("DCLKSTAT",1):$l("DCLKSTAT",2)};
try{cv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Lx.push(Kj.qa(function(){if(!(Mx||"google_ad_status"in window)){try{gv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Mx=!0;$l("DCLKSTAT",3)}},5E3))}}}
function Ox(){var a=Number(S("DCLKSTAT",0));return isNaN(a)?0:a}
;function Px(){var a=E("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Qx(){Ix.apply(this,arguments)}
x(Qx,Ix);Qx.prototype.Kc=function(a){var b;(b=Px())==null||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.vd.bind(a)},D("yt.abuse.playerAttLoader",b),D("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(D("yt.abuse.playerAttLoader",null),D("yt.abuse.playerAttLoaderRun",null))};
Qx.prototype.Nc=function(){return!!Px()};
Qx.prototype.Cd=function(a){return Px().bgvmc(a)};function Rx(a){Ws.call(this,a===void 0?"document_active":a);var b=this;this.o=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.H},{from:"document_active",to:"document_disposed",action:this.D},{from:"document_disposed_preventable",to:"document_disposed",action:this.D},{from:"document_disposed_preventable",to:"flush_logs",action:this.u},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.u},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
x(Rx,Ws);Rx.prototype.H=function(a,b){if(!this.h.get("document_disposed_preventable")){a(b==null?void 0:b.event);var c,d;if((b==null?0:(c=b.event)==null?0:c.defaultPrevented)||(b==null?0:(d=b.event)==null?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Rx.prototype.D=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(b==null?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
Rx.prototype.u=function(a,b){a(b==null?void 0:b.event);this.transition("document_active")};
Rx.prototype.i=function(){this.h=new Map};function Sx(a){Ws.call(this,a===void 0?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.u},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.D},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.u},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.u},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.D},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.D},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){document.visibilityState==="visible"?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
U("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
x(Sx,Ws);Sx.prototype.i=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Sx.prototype.h=function(a,b){a(b==null?void 0:b.event);U("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Sx.prototype.D=function(a,b){a(b==null?void 0:b.event)};
Sx.prototype.u=function(a,b){a(b==null?void 0:b.event)};function Tx(){this.o=new Rx;this.D=new Sx}
Tx.prototype.install=function(){var a=B.apply(0,arguments),b=this;a.forEach(function(c){b.o.install(c)});
a.forEach(function(c){b.D.install(c)})};function Ux(){this.o=[];this.i=new Map;this.h=new Map;this.j=new Set}
Ux.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=c===void 0?0:c;if(d)if(c=uu(c===void 0?0:c)){a=this.client;d=new nu({trackingParams:d});var e=void 0;if(U("no_client_ve_attach_unless_shown")){var f=Dv(d,c);zv.set(f,!0);Ev(d,c)}e=e||"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";f=Cv({cttAuthInfo:wu(c)||void 0},c);d={csn:c,ve:d.getAsJson(),gestureType:e};b&&(d.clientData=b);c==="UNDEFINED_CSN"?Fv("visualElementGestured",f,d):a?Ut("visualElementGestured",d,a,f):so("visualElementGestured",
d,f);b=!0}else b=!1;else b=!1;return b};
Ux.prototype.stateChanged=function(a,b,c){this.visualElementStateChanged(new nu({trackingParams:a}),b,c===void 0?0:c)};
Ux.prototype.visualElementStateChanged=function(a,b,c){c=c===void 0?0:c;if(c===0&&this.j.has(c))this.o.push([a,b]);else{var d=c;d=d===void 0?0:d;c=uu(d);a||(a=(a=ru(d===void 0?0:d))?new nu({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null);var e=a;c&&e&&(a=this.client,d=Cv({cttAuthInfo:wu(c)||void 0},c),b={csn:c,ve:e.getAsJson(),clientData:b},c==="UNDEFINED_CSN"?Fv("visualElementStateChanged",d,b):a?Ut("visualElementStateChanged",b,a,d):so("visualElementStateChanged",b,d))}};
function Vx(a,b){if(b===void 0)for(var c=tu(),d=0;d<c.length;d++)c[d]!==void 0&&Vx(a,c[d]);else a.i.forEach(function(e,f){(f=a.h.get(f))&&Bv(a.client,b,f,e)}),a.i.clear(),a.h.clear()}
;function Wx(){Tx.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));U("combine_ve_grafts")&&(a={},this.install((a.document_disposed={callback:this.i},a)));a={};this.install((a.flush_logs={callback:this.j},a));U("web_log_cfg_cee_ks")||Dn(Xx)}
x(Wx,Tx);Wx.prototype.j=function(){so("finalPayload",{csn:uu()})};
Wx.prototype.h=function(){hu(iu)};
Wx.prototype.i=function(){var a=Vx;Ux.h||(Ux.h=new Ux);a(Ux.h)};
function Xx(){var a=S("CLIENT_EXPERIMENT_EVENTS");if(a){var b=Ud();a=v(a);for(var c=a.next();!c.done;c=a.next())c=c.value,b(c)&&so("genericClientExperimentEvent",{eventType:c});delete Zl.CLIENT_EXPERIMENT_EVENTS}}
;function Yx(){}
function Zx(){var a=E("ytglobal.storage_");a||(a=new Yx,D("ytglobal.storage_",a));return a}
Yx.prototype.estimate=function(){var a,b,c;return A(function(d){a=navigator;return((b=a.storage)==null?0:b.estimate)?d.return(a.storage.estimate()):((c=a.webkitTemporaryStorage)==null?0:c.queryUsageAndQuota)?d.return($x()):d.return()})};
function $x(){var a=navigator;return new Promise(function(b,c){var d;(d=a.webkitTemporaryStorage)!=null&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
D("ytglobal.storageClass_",Yx);function qo(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;self.document===void 0||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=.2}
qo.prototype.Ha=function(a){this.handleError(a)};
qo.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":U("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":U("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":ay(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=.1&&this.h("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=
Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function ay(a,b){Zx().estimate().then(function(c){c=Object.assign({},b,{isSw:self.document===void 0,isIframe:self!==self.top,deviceStorageUsageMbytes:by(c==null?void 0:c.usage),deviceStorageQuotaMbytes:by(c==null?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function by(a){return typeof a==="undefined"?"-1":String(Math.ceil(a/1048576))}
;var cy={},dy=(cy["api.invalidparam"]=2,cy.auth=150,cy["drm.auth"]=150,cy["heartbeat.net"]=150,cy["heartbeat.servererror"]=150,cy["heartbeat.stop"]=150,cy["html5.unsupportedads"]=5,cy["fmt.noneavailable"]=5,cy["fmt.decode"]=5,cy["fmt.unplayable"]=5,cy["html5.missingapi"]=5,cy["html5.unsupportedlive"]=5,cy["drm.unavailable"]=5,cy["mrm.blocked"]=151,cy["embedder.identity.denied"]=152,cy);var ey=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function fy(a){return(a.search("cue")===0||a.search("load")===0)&&a!=="loadModule"}
function gy(a,b,c){if(typeof a==="string")return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=v(ey);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function hy(a,b,c,d){if(Qa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};typeof a==="string"&&a.length===16?b.list="PL"+a:b.playlist=a;return b}
;function iy(a){L.call(this);var b=this;this.api=a;this.W=this.u=!1;this.A=[];this.I={};this.j=[];this.i=[];this.X=!1;this.sessionId=this.h=null;this.targetOrigin="*";this.T=U("web_player_split_event_bus_iframe");this.o=S("POST_MESSAGE_ORIGIN")||document.location.protocol+"//"+document.location.hostname;this.H=function(c){a:if(!(b.o!=="*"&&c.origin!==b.o||b.h&&c.source!==b.h||typeof c.data!=="string")){try{var d=JSON.parse(c.data)}catch(h){break a}if(d)switch(d.event){case "listening":var e=c.source;
c=c.origin;d=d.id;c!=="null"&&(b.o=b.targetOrigin=c);b.h=e;b.sessionId=d;if(b.u){b.W=!0;b.u=!1;b.sendMessage("initialDelivery",jy(b));b.sendMessage("onReady");e=v(b.A);for(d=e.next();!d.done;d=e.next())ky(b,d.value);b.A=[]}break;case "command":if(e=d.func,d=d.args,e==="addEventListener"&&d)e=d[0],d=c.origin,e==="onReady"?b.api.logApiCall(e+" invocation",d):e==="onError"&&b.X&&(b.api.logApiCall(e+" invocation",d,b.errorCode),b.errorCode=void 0),b.api.logApiCall(e+" registration",d),b.I[e]||e==="onReady"||
(c=ly(b,e,d),b.i.push({eventType:e,listener:c,origin:d}),b.T?b.api.handleExternalCall("addEventListener",[e,c],d):b.api.addEventListener(e,c),b.I[e]=!0);else if(c=c.origin,b.api.isExternalMethodAvailable(e,c)){d=d||[];if(d.length>0&&fy(e)){var f=d;if(Qa(f[0])&&!Array.isArray(f[0]))var g=f[0];else switch(g={},e){case "loadVideoById":case "cueVideoById":g=gy(f[0],f[1]!==void 0?Number(f[1]):void 0,f[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":g=f[0];typeof g==="string"&&(g={mediaContentUrl:g,
startSeconds:f[1]!==void 0?Number(f[1]):void 0,suggestedQuality:f[2]});c:{if((f=g.mediaContentUrl)&&(f=/\/([ve]|embed)\/([^#?]+)/.exec(f))&&f[2]){f=f[2];break c}f=null}g.videoId=f;g=gy(g);break;case "loadPlaylist":case "cuePlaylist":g=hy(f[0],f[1],f[2],f[3])}d.length=1;d[0]=g}b.api.handleExternalCall(e,d,c);fy(e)&&my(b,jy(b))}}}};
ny.addEventListener("message",this.H);if(a=S("WIDGET_ID"))this.sessionId=a;oy(this,"onReady",function(){b.u=!0;var c=b.api.getVideoData();if(!c.isPlayable){b.X=!0;c=c.errorCode;var d=d===void 0?5:d;b.errorCode=c?dy[c]||d:d;b.sendMessage("onError",Number(b.errorCode))}});
oy(this,"onVideoProgress",this.Re.bind(this));oy(this,"onVolumeChange",this.Se.bind(this));oy(this,"onApiChange",this.Ke.bind(this));oy(this,"onPlaybackQualityChange",this.Oe.bind(this));oy(this,"onPlaybackRateChange",this.Pe.bind(this));oy(this,"onStateChange",this.Qe.bind(this));oy(this,"onWebglSettingsChanged",this.Te.bind(this));oy(this,"onCaptionsTrackListChanged",this.Le.bind(this));oy(this,"captionssettingschanged",this.Me.bind(this))}
x(iy,L);function my(a,b){a.sendMessage("infoDelivery",b)}
p=iy.prototype;p.sendMessage=function(a,b){a={event:a,info:b===void 0?null:b};this.W?ky(this,a):this.A.push(a)};
function ly(a,b,c){return function(d){b==="onError"?a.api.logApiCall(b+" invocation",c,d):a.api.logApiCall(b+" invocation",c);a.sendMessage(b,d)}}
function oy(a,b,c){a.j.push({eventType:b,listener:c});a.api.addEventListener(b,c)}
function jy(a){if(!a.api)return null;var b=a.api.getApiInterface();Pb(b,"getVideoData");for(var c={apiInterface:b},d=0,e=b.length;d<e;d++){var f=b[d];if(f.search("get")===0||f.search("is")===0){var g=0;f.search("get")===0?g=3:f.search("is")===0&&(g=2);g=f.charAt(g).toLowerCase()+f.substr(g+1);try{var h=a.api[f]();c[g]=h}catch(k){}}}c.videoData=a.api.getVideoData();c.currentTimeLastUpdated_=Date.now()/1E3;return c}
p.Qe=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());my(this,a)};
p.Oe=function(a){a={playbackQuality:a};this.api.getAvailableQualityLevels&&(a.availableQualityLevels=this.api.getAvailableQualityLevels());this.api.getPreferredQuality&&(a.preferredQuality=this.api.getPreferredQuality());my(this,a)};
p.Pe=function(a){my(this,{playbackRate:a})};
p.Ke=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
p.Se=function(){my(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
p.Re=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());my(this,a)};
p.Te=function(){my(this,{sphericalProperties:this.api.getSphericalProperties()})};
p.Le=function(){if(this.api.getCaptionTracks){var a={captionTracks:this.api.getCaptionTracks()};my(this,a)}};
p.Me=function(){if(this.api.getSubtitlesUserSettings){var a={subtitlesUserSettings:this.api.getSubtitlesUserSettings()};my(this,a)}};
function ky(a,b){if(a.h){b.channel="widget";a.sessionId&&(b.id=a.sessionId);try{var c=JSON.stringify(b);a.h.postMessage(c,a.targetOrigin)}catch(d){cu(d)}}}
p.ba=function(){L.prototype.ba.call(this);ny.removeEventListener("message",this.H);for(var a=0;a<this.j.length;a++){var b=this.j[a];this.api.removeEventListener(b.eventType,b.listener)}this.j=[];for(a=0;a<this.i.length;a++)b=this.i[a],this.T?this.api.handleExternalCall("removeEventListener",[b.eventType,b.listener],b.origin):this.api.removeEventListener(b.eventType,b.listener);this.i=[]};
var ny=window;function py(a,b,c){L.call(this);var d=this;this.api=a;this.id=b;this.origin=c;this.h={};this.j=U("web_player_split_event_bus_iframe");this.i=function(e){a:if(e.origin===d.origin){var f=e.data;if(typeof f==="string"){try{f=JSON.parse(f)}catch(k){break a}if(f.command){var g=f.command;f=f.data;e=e.origin;if(!d.ea){var h=f||{};switch(g){case "addEventListener":typeof h.event==="string"&&d.addListener(h.event,e);break;case "removeEventListener":typeof h.event==="string"&&d.removeListener(h.event,e);break;
default:d.api.isReady()&&d.api.isExternalMethodAvailable(g,e||null)&&(f=qy(g,f||{}),f=d.api.handleExternalCall(g,f,e||null),(f=ry(g,f))&&sy(d,g,f))}}}}}};
ty.addEventListener("message",this.i);sy(this,"RECEIVING")}
x(py,L);p=py.prototype;p.addListener=function(a,b){if(!(a in this.h)){var c=this.Ne.bind(this,a);this.h[a]=c;this.addEventListener(a,c,b)}};
p.Ne=function(a,b){this.ea||sy(this,a,uy(a,b))};
p.removeListener=function(a,b){a in this.h&&(this.removeEventListener(a,this.h[a],b),delete this.h[a])};
p.addEventListener=function(a,b,c){this.j?a==="onReady"?this.api.addEventListener(a,b):this.api.handleExternalCall("addEventListener",[a,b],c||null):this.api.addEventListener(a,b)};
p.removeEventListener=function(a,b,c){this.j?a==="onReady"?this.api.removeEventListener(a,b):this.api.handleExternalCall("removeEventListener",[a,b],c||null):this.api.removeEventListener(a,b)};
function qy(a,b){switch(a){case "loadVideoById":return[gy(b)];case "cueVideoById":return[gy(b)];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return[hy(b)];case "cuePlaylist":return[hy(b)];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];case "setShuffle":return[b.shufflePlaylist];
case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function ry(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
function uy(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}if(b!=null)return{value:b}}
function sy(a,b,c){a.ea||(b={id:a.id,command:b},c&&(b.data=c),vy.postMessage(JSON.stringify(b),a.origin))}
p.ba=function(){ty.removeEventListener("message",this.i);for(var a in this.h)this.h.hasOwnProperty(a)&&this.removeListener(a);L.prototype.ba.call(this)};
var ty=window,vy=window.parent;var wy=new Qx;function xy(){return wy.Nc()}
function yy(a){a=a===void 0?{}:a;return wy.invoke(a)}
;function zy(a,b,c,d,e){L.call(this);var f=this;this.A=b;this.webPlayerContextConfig=d;this.qc=e;this.Ka=!1;this.api={};this.ia=this.u=null;this.T=new N;this.h={};this.X=this.pa=this.elementId=this.Ya=this.config=null;this.W=!1;this.j=this.H=null;this.ya={};this.sc=["onReady"];this.lastError=null;this.Sb=NaN;this.I={};this.ga=0;this.i=this.o=a;sg(this,this.T);Ay(this);c?this.ga=setTimeout(function(){f.loadNewVideoConfig(c)},0):d&&(By(this),Cy(this))}
x(zy,L);p=zy.prototype;p.getId=function(){return this.A};
p.loadNewVideoConfig=function(a){if(!this.ea){this.ga&&(clearTimeout(this.ga),this.ga=0);var b=a||{};b instanceof Tu||(b=new Tu(b));this.config=b;this.setConfig(a);Cy(this);this.isReady()&&Dy(this)}};
function By(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;a.elementId==="video-player"&&(a.elementId=a.A,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.A:a.config.attrs.id=a.A);var c;((c=a.i)==null?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
p.setConfig=function(a){this.Ya=a;this.config=Ey(a);By(this);if(!this.pa){var b;this.pa=Fy(this,((b=this.config.args)==null?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if((c=this.config)==null?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.i&&(this.i.style.width=Ej(Number(b)||b)),(a=a.height)&&this.i&&(this.i.style.height=Ej(Number(a)||a))};
function Dy(a){if(a.config&&a.config.loaded!==!0)if(a.config.loaded=!0,!a.config.args||a.config.args.autoplay!=="0"&&a.config.args.autoplay!==0&&a.config.args.autoplay!==!1){var b;a.api.loadVideoByPlayerVars((b=a.config.args)!=null?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Gy(a){var b=!0,c=Hy(a);c&&a.config&&(b=c.dataset.version===Iy(a));return b&&!!E("yt.player.Application.create")}
function Cy(a){if(!a.ea&&!a.W){var b=Gy(a);if(b&&(Hy(a)?"html5":null)==="html5")a.X="html5",a.isReady()||Jy(a);else if(Ky(a),a.X="html5",b&&a.j&&a.o)a.o.appendChild(a.j),Jy(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.H=function(){c=!0;var d=Ly(a,"player_bootstrap_method")?E("yt.player.Application.createAlternate")||E("yt.player.Application.create"):E("yt.player.Application.create");var e=a.config?Ey(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig,a.qc);Jy(a)};
a.W=!0;b?a.H():(cv(Iy(a),a.H),(b=My(a))&&jv(b||""),Ny(a)&&!c&&D("yt.player.Application.create",null))}}}
function Hy(a){var b=Mg(a.elementId);!b&&a.i&&a.i.querySelector&&(b=a.i.querySelector("#"+a.elementId));return b}
function Jy(a){if(!a.ea){var b=Hy(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.W=!1;if(!Ly(a,"html5_remove_not_servable_check_killswitch")){var d;if((b==null?0:b.isNotServable)&&a.config&&(b==null?0:b.isNotServable((d=a.config.args)==null?void 0:d.video_id)))return}Oy(a)}else a.Sb=setTimeout(function(){Jy(a)},50)}}
function Oy(a){Ay(a);a.Ka=!0;var b=Hy(a);if(b){a.u=Py(a,b,"addEventListener");a.ia=Py(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Py(a,b,f))}}for(var g in a.h)a.h.hasOwnProperty(g)&&a.u&&a.u(g,a.h[g]);Dy(a);a.pa&&a.pa(a.api);a.T.kb("onReady",a.api)}
function Py(a,b,c){var d=b[c];return function(){var e=B.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){if(c!=="sendAbandonmentPing")throw f.params=c,a.lastError=f,e=new V("PlayerProxy error in method call",{error:f,method:c,playerId:a.A}),e.level="WARNING",e;}}}
function Ay(a){a.Ka=!1;if(a.ia)for(var b in a.h)a.h.hasOwnProperty(b)&&a.ia(b,a.h[b]);for(var c in a.I)a.I.hasOwnProperty(c)&&clearTimeout(Number(c));a.I={};a.u=null;a.ia=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ya};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
p.isReady=function(){return this.Ka};
p.addEventListener=function(a,b){var c=this,d=Fy(this,b);d&&(Jb(this.sc,a)>=0||this.h[a]||(b=Qy(this,a),this.u&&this.u(a,b)),this.T.subscribe(a,d),a==="onReady"&&this.isReady()&&setTimeout(function(){d(c.api)},0))};
p.removeEventListener=function(a,b){this.ea||(b=Fy(this,b))&&this.T.unsubscribe(a,b)};
function Fy(a,b){var c=b;if(typeof b==="string"){if(a.ya[b])return a.ya[b];c=function(){var d=B.apply(0,arguments),e=E(b);if(e)try{e.apply(C,d)}catch(f){throw d=new V("PlayerProxy error when executing callback",{error:f}),d.level="ERROR",d;}};
a.ya[b]=c}return c?c:null}
function Qy(a,b){function c(d){var e=setTimeout(function(){if(!a.ea){try{a.T.kb(b,d!=null?d:void 0)}catch(h){var f=new V("PlayerProxy error when creating global callback",{error:h.message,event:b,playerId:a.A,data:d,originalStack:h.stack,componentStack:h.Od});f.level="WARNING";throw f;}f=a.I;var g=String(e);g in f&&delete f[g]}},0);
Bg(a.I,String(e))}
return a.h[b]=c}
p.getPlayerType=function(){return this.X||(Hy(this)?"html5":null)};
p.getLastError=function(){return this.lastError};
function Ky(a){a.cancel();Ay(a);a.X=null;a.config&&(a.config.loaded=!1);var b=Hy(a);b&&(Gy(a)||!Ny(a)?a.j=b:(b&&b.destroy&&b.destroy(),a.j=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
p.cancel=function(){this.H&&gv(Iy(this),this.H);clearTimeout(this.Sb);this.W=!1};
p.ba=function(){Ky(this);if(this.j&&this.config&&this.j.destroy)try{this.j.destroy()}catch(b){var a=new V("PlayerProxy error during disposal",{error:b});a.level="ERROR";throw a;}this.ya=null;for(a in this.h)this.h.hasOwnProperty(a)&&delete this.h[a];this.Ya=this.config=this.api=null;delete this.o;delete this.i;L.prototype.ba.call(this)};
function Ny(a){var b,c;a=(b=a.config)==null?void 0:(c=b.args)==null?void 0:c.fflags;return!!a&&a.indexOf("player_destroy_old_version=true")!==-1}
function Iy(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function My(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Ly(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if((d=a.config)==null?0:d.args)c=a.config.args.fflags}return(c||"").split("&").includes(b+"=true")}
function Ey(a){for(var b={},c=v(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]=typeof e==="object"?Eg(e):e}return b}
;var Ry={},Sy="player_uid_"+(Math.random()*1E9>>>0);function Ty(a,b){var c="player",d=!1;d=d===void 0?!0:d;c=typeof c==="string"?Mg(c):c;var e=Sy+"_"+Ra(c),f=Ry[e];if(f&&d)return Uy(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new zy(c,e,a,b,void 0);Ry[e]=f;f.addOnDisposeCallback(function(){delete Ry[f.getId()]});
return f.api}
function Uy(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Vy=null,Wy=null;
function Xy(){Vw();var a=qn(),b=tn(119),c=window.devicePixelRatio>1;if(document.body&&Sj(document.body,"exp-invert-logo"))if(c&&!Sj(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Sj(d,"inverted-hdpi")){var e=Qj(d);Rj(d,e+(e.length>0?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Sj(document.body,"inverted-hdpi")&&Tj();if(b!=c){b="f"+(Math.floor(119/31)+1);d=un(b)||0;d=c?d|67108864:d&-67108865;d===0?delete nn[b]:(c=d.toString(16),nn[b]=c.toString());
c=!0;U("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in nn)nn.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(nn[f])));var f=d.join("&");jn(b,f,63072E3,a.i,c)}}
function Yy(){Zy()}
function $y(){Uw("ep_init_pr");Zy()}
function Zy(){var a=Vy.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function az(){Vy&&Vy.sendAbandonmentPing&&Vy.sendAbandonmentPing();S("PL_ATT")&&wy.dispose();for(var a=Kj,b=0,c=Lx.length;b<c;b++)a.ra(Lx[b]);Lx.length=0;ev("//static.doubleclick.net/instream/ad_status.js");Mx=!1;$l("DCLKSTAT",0);rg(Wy);Vy&&(Vy.removeEventListener("onVideoDataChange",Yy),Vy.destroy())}
;D("yt.setConfig",$l);D("yt.config.set",$l);D("yt.setMsg",bv);D("yt.msgs.set",bv);D("yt.logging.errors.log",bu);
D("writeEmbed",function(){var a=S("PLAYER_CONFIG");if(!a){var b=S("PLAYER_VARS");b&&(a={args:b})}Nv(!0);a.args.ps==="gvn"&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=S("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Qw("embed",["ol"]);c=vx();if(!c.serializedForcedExperimentIds){var d=nm(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=
d.forced_experiments)}var e;((e=a.args)==null?0:e.autoplay)&&Qw("watch",["pbs","pbu","pbp"]);Vy=Ty(a,c);Vy.addEventListener("onVideoDataChange",Yy);Vy.addEventListener("onReady",$y);a=S("POST_MESSAGE_ID","player");S("ENABLE_JS_API")?Wy=new iy(Vy):S("ENABLE_POST_API")&&typeof a==="string"&&typeof b==="string"&&(Wy=new py(Vy,a,b));Nx();U("ytidb_create_logger_embed_killswitch")||po();a={};Wx.h||(Wx.h=new Wx);Wx.h.install((a.flush_logs={callback:function(){Ht()}},a));
bs();U("ytidb_clear_embedded_player")&&Kj.qa(function(){var f,g;if(!tx){var h=Ns();Js(h,{lc:sx,zd:qx});var k={Uc:{feedbackEndpoint:$v(kx),modifyChannelNotificationPreferenceEndpoint:$v(lx),playlistEditEndpoint:$v(mx),shareEntityEndpoint:$v(jx),subscribeEndpoint:$v(gx),unsubscribeEndpoint:$v(hx),webPlayerShareEntityServiceEndpoint:$v(nx)}},l=Wv(),m={};l&&(m.client_location=l);f===void 0&&(f=fn());g===void 0&&(g=h.resolve(sx));$w(k,g,f,m);Js(h,{lc:fx,Ad:Zw.h});tx=h.resolve(fx)}Hx()})});
D("yt.abuse.player.botguardInitialized",E("yt.abuse.player.botguardInitialized")||xy);D("yt.abuse.player.invokeBotguard",E("yt.abuse.player.invokeBotguard")||yy);D("yt.abuse.dclkstatus.checkDclkStatus",E("yt.abuse.dclkstatus.checkDclkStatus")||Ox);D("yt.player.exports.navigate",E("yt.player.exports.navigate")||Mv);D("yt.util.activity.init",E("yt.util.activity.init")||rs);D("yt.util.activity.getTimeSinceActive",E("yt.util.activity.getTimeSinceActive")||us);
D("yt.util.activity.setTimestamp",E("yt.util.activity.setTimestamp")||ss);window.addEventListener("load",dm(function(){Xy()}));
window.addEventListener("pageshow",dm(function(a){a.persisted||Xy()}));
window.addEventListener("pagehide",dm(function(a){U("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?az():a.persisted||az()}));
window.onerror=function(a,b,c,d,e){var f;b=b===void 0?"Unknown file":b;c=c===void 0?0:c;var g=!1,h=am("log_window_onerror_fraction");if(h&&Math.random()<h)g=!0;else{h=document.getElementsByTagName("script");for(var k=0,l=h.length;k<l;k++)if(h[k].src.indexOf("/debug-")>0){g=!0;break}}if(g){g=!1;e?g=!0:(typeof a==="string"?h=a:ErrorEvent&&a instanceof ErrorEvent?(g=!0,h=a.message,b=a.filename,c=a.lineno,d=a.colno):(h="Unknown error",b="Unknown file",c=0),e=new V(h),e.name="UnhandledWindowError",e.message=
h,e.fileName=b,e.lineNumber=c,isNaN(d)?delete e.columnNumber:e.columnNumber=d);if(!U("wiz_enable_component_stack_propagation_killswitch")){a=e;var m;if((m=f)==null||!m.componentStack)if(m=a.Od)f||(f={}),f.componentStack=Vt(m)}f&&fu(e,f);g?bu(e):cu(e)}};
Ii=du;window.addEventListener("unhandledrejection",function(a){du(a.reason)});
Kb(S("ERRORS")||[],function(a){bu.apply(null,a)});
$l("ERRORS",[]);}).call(this);
