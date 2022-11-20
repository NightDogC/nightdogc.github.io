/*! For license information please see chunk.729.b9dddc9ef490a606a608.js.LICENSE.txt */

(self.webpackChunk_ember_auto_import_=self.webpackChunk_ember_auto_import_||[]).push([[729],{7001:(e,t,r)=>{var n
!function(i,o,s){if(i){for(var a,l={8:"backspace",9:"tab",13:"enter",16:"shift",17:"ctrl",18:"alt",20:"capslock",27:"esc",32:"space",33:"pageup",34:"pagedown",35:"end",36:"home",37:"left",38:"up",39:"right",40:"down",45:"ins",46:"del",91:"meta",93:"meta",224:"meta"},c={106:"*",107:"+",109:"-",110:".",111:"/",186:";",187:"=",188:",",189:"-",190:".",191:"/",192:"`",219:"[",220:"\\",221:"]",222:"'"},u={"~":"`","!":"1","@":"2","#":"3",$:"4","%":"5","^":"6","&":"7","*":"8","(":"9",")":"0",_:"-","+":"=",":":";",'"':"'","<":",",">":".","?":"/","|":"\\"},p={option:"alt",command:"meta",return:"enter",escape:"esc",plus:"+",mod:/Mac|iPod|iPhone|iPad/.test(navigator.platform)?"meta":"ctrl"},h={},d=1;d<20;++d)l[111+d]="f"+d
for(d=0;d<=9;++d)l[d+96]=d.toString()
k.prototype.bind=function(e,t,r){var n=this
return e=e instanceof Array?e:[e],n._bindMultiple.call(n,e,t,r),n},k.prototype.unbind=function(e,t){return this.bind.call(this,e,(function(){}),t)},k.prototype.trigger=function(e,t){var r=this
return r._directMap[e+":"+t]&&r._directMap[e+":"+t]({},e),r},k.prototype.reset=function(){var e=this
return e._callbacks={},e._directMap={},e},k.prototype.destroy=function(){var e=this
e.reset(),m(e.target,"keypress",e._handleKeyEvent),m(e.target,"keydown",e._handleKeyEvent),m(e.target,"keyup",e._handleKeyEvent),e.target=s,e._handleKeyEvent=s},k.prototype.stopCallback=function(e,t,r,n){if(this.paused)return!0
if(h[r]||h[n])return!1
if((" "+t.className+" ").indexOf(" itsatrap ")>-1)return!1
if(w(t,this.target))return!1
if("composedPath"in e&&"function"==typeof e.composedPath){var i=e.composedPath()[0]
i!==e.target&&(t=i)}return"INPUT"==t.tagName||"SELECT"==t.tagName||"TEXTAREA"==t.tagName||t.isContentEditable},k.prototype.handleKey=function(){var e=this
return e._handleKey.apply(e,arguments)},k.addKeycodes=function(e){for(var t in e)e.hasOwnProperty(t)&&(l[t]=e[t])
a=null},k.prototype.pause=function(){this.paused=!0},k.prototype.unpause=function(){this.paused=!1},k.prototype.bindGlobal=function(e,t,r){if(this.bind(e,t,r),e instanceof Array)for(var n=0;n<e.length;n++)h[e[n]]=!0
else h[e]=!0},i.ItsATrap=k,e.exports&&(e.exports=k),(n=function(){return k}.call(t,r,t,e))===s||(e.exports=n)}function f(e,t,r){e.addEventListener?e.addEventListener(t,r,!1):e.attachEvent("on"+t,r)}function m(e,t,r){e.removeEventListener?e.removeEventListener(t,r,!1):e.detachEvent("on"+t,r)}function g(e){if("keypress"==e.type){var t=String.fromCharCode(e.which)
return e.shiftKey||(t=t.toLowerCase()),t}return l[e.which]?l[e.which]:c[e.which]?c[e.which]:String.fromCharCode(e.which).toLowerCase()}function v(e){return"shift"==e||"ctrl"==e||"alt"==e||"meta"==e}function y(e,t,r){return r||(r=function(){if(!a)for(var e in a={},l)e>95&&e<112||l.hasOwnProperty(e)&&(a[l[e]]=e)
return a}()[e]?"keydown":"keypress"),"keypress"==r&&t.length&&(r="keydown"),r}function b(e,t){var r,n,i,o=[]
for(r=function(e){return"+"===e?["+"]:(e=e.replace(/\+{2}/g,"+plus")).split("+")}(e),i=0;i<r.length;++i)n=r[i],p[n]&&(n=p[n]),t&&"keypress"!=t&&u[n]&&(n=u[n],o.push("shift")),v(n)&&o.push(n)
return{key:n,modifiers:o,action:t=y(n,o,t)}}function w(e,t){return null!==e&&e!==o&&(e===t||w(e.parentNode,t))}function k(e){var t=this
if(e=e||o,!(t instanceof k))return new k(e)
t.target=e,t._callbacks={},t._directMap={}
var r,n={},i=!1,s=!1,a=!1
function l(e){e=e||{}
var t,r=!1
for(t in n)e[t]?r=!0:n[t]=0
r||(a=!1)}function c(e,r,i,o,s,a){var l,c,u,p,h=[],d=i.type
if(!t._callbacks[e])return[]
for("keyup"==d&&v(e)&&(r=[e]),l=0;l<t._callbacks[e].length;++l)if(c=t._callbacks[e][l],(o||!c.seq||n[c.seq]==c.level)&&d==c.action&&("keypress"==d&&!i.metaKey&&!i.ctrlKey||(u=r,p=c.modifiers,u.sort().join(",")===p.sort().join(",")))){var f=!o&&c.combo==s,m=o&&c.seq==o&&c.level==a;(f||m)&&t._callbacks[e].splice(l,1),h.push(c)}return h}function u(e,r,n,i){t.stopCallback(r,r.target||r.srcElement,n,i)||!1===e(r,n)&&(function(e){e.preventDefault?e.preventDefault():e.returnValue=!1}(r),function(e){e.stopPropagation?e.stopPropagation():e.cancelBubble=!0}(r))}function p(e,o,s,h,d){t._directMap[e+":"+s]=o
var f,m=(e=e.replace(/\s+/g," ")).split(" ")
m.length>1?function(e,t,o,s){function c(t){return function(){a=t,++n[e],clearTimeout(r),r=setTimeout(l,1e3)}}function h(t){u(o,t,e),"keyup"!==s&&(i=g(t)),setTimeout(l,10)}n[e]=0
for(var d=0;d<t.length;++d){var f=d+1===t.length?h:c(s||b(t[d+1]).action)
p(t[d],f,s,e,d)}}(e,m,o,s):(f=b(e,s),t._callbacks[f.key]=t._callbacks[f.key]||[],c(f.key,f.modifiers,{type:f.action},h,e,d),t._callbacks[f.key][h?"unshift":"push"]({callback:o,modifiers:f.modifiers,action:f.action,seq:h,level:d,combo:e}))}t._handleKey=function(e,t,r){var n,i=c(e,t,r),o={},p=0,h=!1
for(n=0;n<i.length;++n)i[n].seq&&(p=Math.max(p,i[n].level))
for(n=0;n<i.length;++n)if(i[n].seq){if(i[n].level!=p)continue
h=!0,o[i[n].seq]=1,u(i[n].callback,r,i[n].combo,i[n].seq)}else h||u(i[n].callback,r,i[n].combo)
var d="keypress"==r.type&&s
r.type!=a||v(e)||d||l(o),s=h&&"keydown"==r.type},t._handleKeyEvent=function(e){"number"!=typeof e.which&&(e.which=e.keyCode)
var r=g(e)
r&&("keyup"!=e.type||i!==r?t.handleKey(r,function(e){var t=[]
return e.shiftKey&&t.push("shift"),e.altKey&&t.push("alt"),e.ctrlKey&&t.push("ctrl"),e.metaKey&&t.push("meta"),t}(e),e):i=!1)},t._bindMultiple=function(e,t,r){for(var n=0;n<e.length;++n)p(e[n],t,r)},f(e,"keypress",t._handleKeyEvent),f(e,"keydown",t._handleKeyEvent),f(e,"keyup",t._handleKeyEvent)}}("undefined"!=typeof window?window:null,"undefined"!=typeof window?document:null)},1518:(e,t,r)=>{"use strict"
r.d(t,{fi:()=>k,kZ:()=>w})
var n=r(1863),i=r(6823),o=r(8012),s=r(7729),a=r(1671),l=r(5741),c=r(4094),u=r(4327),p=r(7529)
function h(e,t,r){void 0===r&&(r=!1)
var h,d,f=(0,s.Re)(t),m=(0,s.Re)(t)&&function(e){var t=e.getBoundingClientRect(),r=(0,p.NM)(t.width)/e.offsetWidth||1,n=(0,p.NM)(t.height)/e.offsetHeight||1
return 1!==r||1!==n}(t),g=(0,c.Z)(t),v=(0,n.Z)(e,m,r),y={scrollLeft:0,scrollTop:0},b={x:0,y:0}
return(f||!f&&!r)&&(("body"!==(0,a.Z)(t)||(0,u.Z)(g))&&(y=(h=t)!==(0,o.Z)(h)&&(0,s.Re)(h)?{scrollLeft:(d=h).scrollLeft,scrollTop:d.scrollTop}:(0,i.Z)(h)),(0,s.Re)(t)?((b=(0,n.Z)(t,!0)).x+=t.clientLeft,b.y+=t.clientTop):g&&(b.x=(0,l.Z)(g))),{x:v.left+y.scrollLeft-b.x,y:v.top+y.scrollTop-b.y,width:v.width,height:v.height}}var d=r(3864),f=r(5763),m=r(8217),g=r(8713)
function v(e){var t=new Map,r=new Set,n=[]
function i(e){r.add(e.name),[].concat(e.requires||[],e.requiresIfExists||[]).forEach((function(e){if(!r.has(e)){var n=t.get(e)
n&&i(n)}})),n.push(e)}return e.forEach((function(e){t.set(e.name,e)})),e.forEach((function(e){r.has(e.name)||i(e)})),n}var y={placement:"bottom",modifiers:[],strategy:"absolute"}
function b(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
return!t.some((function(e){return!(e&&"function"==typeof e.getBoundingClientRect)}))}function w(e){void 0===e&&(e={})
var t=e,r=t.defaultModifiers,n=void 0===r?[]:r,i=t.defaultOptions,o=void 0===i?y:i
return function(e,t,r){void 0===r&&(r=o)
var i,a,l={placement:"bottom",orderedModifiers:[],options:Object.assign({},y,o),modifiersData:{},elements:{reference:e,popper:t},attributes:{},styles:{}},c=[],u=!1,p={state:l,setOptions:function(r){var i="function"==typeof r?r(l.options):r
w(),l.options=Object.assign({},o,l.options,i),l.scrollParents={reference:(0,s.kK)(e)?(0,f.Z)(e):e.contextElement?(0,f.Z)(e.contextElement):[],popper:(0,f.Z)(t)}
var a,u,h=function(e){var t=v(e)
return g.xs.reduce((function(e,r){return e.concat(t.filter((function(e){return e.phase===r})))}),[])}((a=[].concat(n,l.options.modifiers),u=a.reduce((function(e,t){var r=e[t.name]
return e[t.name]=r?Object.assign({},r,t,{options:Object.assign({},r.options,t.options),data:Object.assign({},r.data,t.data)}):t,e}),{}),Object.keys(u).map((function(e){return u[e]}))))
return l.orderedModifiers=h.filter((function(e){return e.enabled})),l.orderedModifiers.forEach((function(e){var t=e.name,r=e.options,n=void 0===r?{}:r,i=e.effect
if("function"==typeof i){var o=i({state:l,name:t,instance:p,options:n})
c.push(o||function(){})}})),p.update()},forceUpdate:function(){if(!u){var e=l.elements,t=e.reference,r=e.popper
if(b(t,r)){l.rects={reference:h(t,(0,m.Z)(r),"fixed"===l.options.strategy),popper:(0,d.Z)(r)},l.reset=!1,l.placement=l.options.placement,l.orderedModifiers.forEach((function(e){return l.modifiersData[e.name]=Object.assign({},e.data)}))
for(var n=0;n<l.orderedModifiers.length;n++)if(!0!==l.reset){var i=l.orderedModifiers[n],o=i.fn,s=i.options,a=void 0===s?{}:s,c=i.name
"function"==typeof o&&(l=o({state:l,options:a,name:c,instance:p})||l)}else l.reset=!1,n=-1}}},update:(i=function(){return new Promise((function(e){p.forceUpdate(),e(l)}))},function(){return a||(a=new Promise((function(e){Promise.resolve().then((function(){a=void 0,e(i())}))}))),a}),destroy:function(){w(),u=!0}}
if(!b(e,t))return p
function w(){c.forEach((function(e){return e()})),c=[]}return p.setOptions(r).then((function(e){!u&&r.onFirstUpdate&&r.onFirstUpdate(e)})),p}}var k=w()},3268:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(7729)
function i(e,t){var r=t.getRootNode&&t.getRootNode()
if(e.contains(t))return!0
if(r&&(0,n.Zq)(r)){var i=t
do{if(i&&e.isSameNode(i))return!0
i=i.parentNode||i.host}while(i)}return!1}},1863:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>a})
var n=r(7729),i=r(7529),o=r(8012),s=r(3063)
function a(e,t,r){void 0===t&&(t=!1),void 0===r&&(r=!1)
var a=e.getBoundingClientRect(),l=1,c=1
t&&(0,n.Re)(e)&&(l=e.offsetWidth>0&&(0,i.NM)(a.width)/e.offsetWidth||1,c=e.offsetHeight>0&&(0,i.NM)(a.height)/e.offsetHeight||1)
var u=((0,n.kK)(e)?(0,o.Z)(e):window).visualViewport,p=!(0,s.Z)()&&r,h=(a.left+(p&&u?u.offsetLeft:0))/l,d=(a.top+(p&&u?u.offsetTop:0))/c,f=a.width/l,m=a.height/c
return{width:f,height:m,top:d,right:h+f,bottom:d+m,left:h,x:h,y:d}}},9987:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(8012)
function i(e){return(0,n.Z)(e).getComputedStyle(e)}},4094:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(7729)
function i(e){return(((0,n.kK)(e)?e.ownerDocument:e.document)||window.document).documentElement}},3864:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(1863)
function i(e){var t=(0,n.Z)(e),r=e.offsetWidth,i=e.offsetHeight
return Math.abs(t.width-r)<=1&&(r=t.width),Math.abs(t.height-i)<=1&&(i=t.height),{x:e.offsetLeft,y:e.offsetTop,width:r,height:i}}},1671:(e,t,r)=>{"use strict"
function n(e){return e?(e.nodeName||"").toLowerCase():null}r.d(t,{Z:()=>n})},8217:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>p})
var n=r(8012),i=r(1671),o=r(9987),s=r(7729)
function a(e){return["table","td","th"].indexOf((0,i.Z)(e))>=0}var l=r(4407),c=r(9422)
function u(e){return(0,s.Re)(e)&&"fixed"!==(0,o.Z)(e).position?e.offsetParent:null}function p(e){for(var t=(0,n.Z)(e),r=u(e);r&&a(r)&&"static"===(0,o.Z)(r).position;)r=u(r)
return r&&("html"===(0,i.Z)(r)||"body"===(0,i.Z)(r)&&"static"===(0,o.Z)(r).position)?t:r||function(e){var t=/firefox/i.test((0,c.Z)())
if(/Trident/i.test((0,c.Z)())&&(0,s.Re)(e)&&"fixed"===(0,o.Z)(e).position)return null
var r=(0,l.Z)(e)
for((0,s.Zq)(r)&&(r=r.host);(0,s.Re)(r)&&["html","body"].indexOf((0,i.Z)(r))<0;){var n=(0,o.Z)(r)
if("none"!==n.transform||"none"!==n.perspective||"paint"===n.contain||-1!==["transform","perspective"].indexOf(n.willChange)||t&&"filter"===n.willChange||t&&n.filter&&"none"!==n.filter)return r
r=r.parentNode}return null}(e)||t}},4407:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>s})
var n=r(1671),i=r(4094),o=r(7729)
function s(e){return"html"===(0,n.Z)(e)?e:e.assignedSlot||e.parentNode||((0,o.Zq)(e)?e.host:null)||(0,i.Z)(e)}},8012:(e,t,r)=>{"use strict"
function n(e){if(null==e)return window
if("[object Window]"!==e.toString()){var t=e.ownerDocument
return t&&t.defaultView||window}return e}r.d(t,{Z:()=>n})},6823:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(8012)
function i(e){var t=(0,n.Z)(e)
return{scrollLeft:t.pageXOffset,scrollTop:t.pageYOffset}}},5741:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>s})
var n=r(1863),i=r(4094),o=r(6823)
function s(e){return(0,n.Z)((0,i.Z)(e)).left+(0,o.Z)(e).scrollLeft}},7729:(e,t,r)=>{"use strict"
r.d(t,{Re:()=>o,Zq:()=>s,kK:()=>i})
var n=r(8012)
function i(e){return e instanceof(0,n.Z)(e).Element||e instanceof Element}function o(e){return e instanceof(0,n.Z)(e).HTMLElement||e instanceof HTMLElement}function s(e){return"undefined"!=typeof ShadowRoot&&(e instanceof(0,n.Z)(e).ShadowRoot||e instanceof ShadowRoot)}},3063:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(9422)
function i(){return!/^((?!chrome|android).)*safari/i.test((0,n.Z)())}},4327:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(9987)
function i(e){var t=(0,n.Z)(e),r=t.overflow,i=t.overflowX,o=t.overflowY
return/auto|scroll|overlay|hidden/.test(r+o+i)}},5763:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>c})
var n=r(4407),i=r(4327),o=r(1671),s=r(7729)
function a(e){return["html","body","#document"].indexOf((0,o.Z)(e))>=0?e.ownerDocument.body:(0,s.Re)(e)&&(0,i.Z)(e)?e:a((0,n.Z)(e))}var l=r(8012)
function c(e,t){var r
void 0===t&&(t=[])
var o=a(e),s=o===(null==(r=e.ownerDocument)?void 0:r.body),u=(0,l.Z)(o),p=s?[u].concat(u.visualViewport||[],(0,i.Z)(o)?o:[]):o,h=t.concat(p)
return s?h:h.concat(c((0,n.Z)(p)))}},8713:(e,t,r)=>{"use strict"
r.d(t,{BL:()=>c,Ct:()=>g,DH:()=>k,F2:()=>o,I:()=>i,MS:()=>S,N7:()=>v,Pj:()=>h,XM:()=>w,YP:()=>f,bw:()=>m,cW:()=>P,d7:()=>a,ij:()=>y,iv:()=>x,k5:()=>d,mv:()=>l,r5:()=>b,t$:()=>s,ut:()=>u,wX:()=>_,we:()=>n,xs:()=>E,zV:()=>p})
var n="top",i="bottom",o="right",s="left",a="auto",l=[n,i,o,s],c="start",u="end",p="clippingParents",h="viewport",d="popper",f="reference",m=l.reduce((function(e,t){return e.concat([t+"-"+c,t+"-"+u])}),[]),g=[].concat(l,[a]).reduce((function(e,t){return e.concat([t,t+"-"+c,t+"-"+u])}),[]),v="beforeRead",y="read",b="afterRead",w="beforeMain",k="main",_="afterMain",x="beforeWrite",P="write",S="afterWrite",E=[v,y,b,w,k,_,x,P,S]},1505:(e,t,r)=>{"use strict"
r.r(t),r.d(t,{afterMain:()=>n.wX,afterRead:()=>n.r5,afterWrite:()=>n.MS,applyStyles:()=>i.Z,arrow:()=>o.Z,auto:()=>n.d7,basePlacements:()=>n.mv,beforeMain:()=>n.XM,beforeRead:()=>n.N7,beforeWrite:()=>n.iv,bottom:()=>n.I,clippingParents:()=>n.zV,computeStyles:()=>s.Z,createPopper:()=>m.fi,createPopperBase:()=>d.fi,createPopperLite:()=>v,detectOverflow:()=>f.Z,end:()=>n.ut,eventListeners:()=>a.Z,flip:()=>l.Z,hide:()=>c.Z,left:()=>n.t$,main:()=>n.DH,modifierPhases:()=>n.xs,offset:()=>u.Z,placements:()=>n.Ct,popper:()=>n.k5,popperGenerator:()=>d.kZ,popperOffsets:()=>p.Z,preventOverflow:()=>h.Z,read:()=>n.ij,reference:()=>n.YP,right:()=>n.F2,start:()=>n.BL,top:()=>n.we,variationPlacements:()=>n.bw,viewport:()=>n.Pj,write:()=>n.cW})
var n=r(8713),i=r(175),o=r(642),s=r(353),a=r(5210),l=r(7730),c=r(3077),u=r(7347),p=r(502),h=r(1144),d=r(1518),f=r(8006),m=r(2152),g=[a.Z,p.Z,s.Z,i.Z],v=(0,d.kZ)({defaultModifiers:g})},175:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>o})
var n=r(1671),i=r(7729)
const o={name:"applyStyles",enabled:!0,phase:"write",fn:function(e){var t=e.state
Object.keys(t.elements).forEach((function(e){var r=t.styles[e]||{},o=t.attributes[e]||{},s=t.elements[e];(0,i.Re)(s)&&(0,n.Z)(s)&&(Object.assign(s.style,r),Object.keys(o).forEach((function(e){var t=o[e]
!1===t?s.removeAttribute(e):s.setAttribute(e,!0===t?"":t)})))}))},effect:function(e){var t=e.state,r={popper:{position:t.options.strategy,left:"0",top:"0",margin:"0"},arrow:{position:"absolute"},reference:{}}
return Object.assign(t.elements.popper.style,r.popper),t.styles=r,t.elements.arrow&&Object.assign(t.elements.arrow.style,r.arrow),function(){Object.keys(t.elements).forEach((function(e){var o=t.elements[e],s=t.attributes[e]||{},a=Object.keys(t.styles.hasOwnProperty(e)?t.styles[e]:r[e]).reduce((function(e,t){return e[t]="",e}),{});(0,i.Re)(o)&&(0,n.Z)(o)&&(Object.assign(o.style,a),Object.keys(s).forEach((function(e){o.removeAttribute(e)})))}))}},requires:["computeStyles"]}},642:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>h})
var n=r(8983),i=r(3864),o=r(3268),s=r(8217),a=r(9561),l=r(1188),c=r(5414),u=r(8484),p=r(8713)
const h={name:"arrow",enabled:!0,phase:"main",fn:function(e){var t,r=e.state,o=e.name,h=e.options,d=r.elements.arrow,f=r.modifiersData.popperOffsets,m=(0,n.Z)(r.placement),g=(0,a.Z)(m),v=[p.t$,p.F2].indexOf(m)>=0?"height":"width"
if(d&&f){var y=function(e,t){return e="function"==typeof e?e(Object.assign({},t.rects,{placement:t.placement})):e,(0,c.Z)("number"!=typeof e?e:(0,u.Z)(e,p.mv))}(h.padding,r),b=(0,i.Z)(d),w="y"===g?p.we:p.t$,k="y"===g?p.I:p.F2,_=r.rects.reference[v]+r.rects.reference[g]-f[g]-r.rects.popper[v],x=f[g]-r.rects.reference[g],P=(0,s.Z)(d),S=P?"y"===g?P.clientHeight||0:P.clientWidth||0:0,E=_/2-x/2,O=y[w],A=S-b[v]-y[k],C=S/2-b[v]/2+E,T=(0,l.u)(O,C,A),L=g
r.modifiersData[o]=((t={})[L]=T,t.centerOffset=T-C,t)}},effect:function(e){var t=e.state,r=e.options.element,n=void 0===r?"[data-popper-arrow]":r
null!=n&&("string"!=typeof n||(n=t.elements.popper.querySelector(n)))&&(0,o.Z)(t.elements.popper,n)&&(t.elements.arrow=n)},requires:["popperOffsets"],requiresIfExists:["preventOverflow"]}},353:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>d})
var n=r(8713),i=r(8217),o=r(8012),s=r(4094),a=r(9987),l=r(8983),c=r(6118),u=r(7529),p={top:"auto",right:"auto",bottom:"auto",left:"auto"}
function h(e){var t,r=e.popper,l=e.popperRect,c=e.placement,h=e.variation,d=e.offsets,f=e.position,m=e.gpuAcceleration,g=e.adaptive,v=e.roundOffsets,y=e.isFixed,b=d.x,w=void 0===b?0:b,k=d.y,_=void 0===k?0:k,x="function"==typeof v?v({x:w,y:_}):{x:w,y:_}
w=x.x,_=x.y
var P=d.hasOwnProperty("x"),S=d.hasOwnProperty("y"),E=n.t$,O=n.we,A=window
if(g){var C=(0,i.Z)(r),T="clientHeight",L="clientWidth"
C===(0,o.Z)(r)&&(C=(0,s.Z)(r),"static"!==(0,a.Z)(C).position&&"absolute"===f&&(T="scrollHeight",L="scrollWidth")),C=C,(c===n.we||(c===n.t$||c===n.F2)&&h===n.ut)&&(O=n.I,_-=(y&&C===A&&A.visualViewport?A.visualViewport.height:C[T])-l.height,_*=m?1:-1),c!==n.t$&&(c!==n.we&&c!==n.I||h!==n.ut)||(E=n.F2,w-=(y&&C===A&&A.visualViewport?A.visualViewport.width:C[L])-l.width,w*=m?1:-1)}var j,I=Object.assign({position:f},g&&p),R=!0===v?function(e){var t=e.x,r=e.y,n=window.devicePixelRatio||1
return{x:(0,u.NM)(t*n)/n||0,y:(0,u.NM)(r*n)/n||0}}({x:w,y:_}):{x:w,y:_}
return w=R.x,_=R.y,m?Object.assign({},I,((j={})[O]=S?"0":"",j[E]=P?"0":"",j.transform=(A.devicePixelRatio||1)<=1?"translate("+w+"px, "+_+"px)":"translate3d("+w+"px, "+_+"px, 0)",j)):Object.assign({},I,((t={})[O]=S?_+"px":"",t[E]=P?w+"px":"",t.transform="",t))}const d={name:"computeStyles",enabled:!0,phase:"beforeWrite",fn:function(e){var t=e.state,r=e.options,n=r.gpuAcceleration,i=void 0===n||n,o=r.adaptive,s=void 0===o||o,a=r.roundOffsets,u=void 0===a||a,p={placement:(0,l.Z)(t.placement),variation:(0,c.Z)(t.placement),popper:t.elements.popper,popperRect:t.rects.popper,gpuAcceleration:i,isFixed:"fixed"===t.options.strategy}
null!=t.modifiersData.popperOffsets&&(t.styles.popper=Object.assign({},t.styles.popper,h(Object.assign({},p,{offsets:t.modifiersData.popperOffsets,position:t.options.strategy,adaptive:s,roundOffsets:u})))),null!=t.modifiersData.arrow&&(t.styles.arrow=Object.assign({},t.styles.arrow,h(Object.assign({},p,{offsets:t.modifiersData.arrow,position:"absolute",adaptive:!1,roundOffsets:u})))),t.attributes.popper=Object.assign({},t.attributes.popper,{"data-popper-placement":t.placement})},data:{}}},5210:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>o})
var n=r(8012),i={passive:!0}
const o={name:"eventListeners",enabled:!0,phase:"write",fn:function(){},effect:function(e){var t=e.state,r=e.instance,o=e.options,s=o.scroll,a=void 0===s||s,l=o.resize,c=void 0===l||l,u=(0,n.Z)(t.elements.popper),p=[].concat(t.scrollParents.reference,t.scrollParents.popper)
return a&&p.forEach((function(e){e.addEventListener("scroll",r.update,i)})),c&&u.addEventListener("resize",r.update,i),function(){a&&p.forEach((function(e){e.removeEventListener("scroll",r.update,i)})),c&&u.removeEventListener("resize",r.update,i)}},data:{}}},7730:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>p})
var n={left:"right",right:"left",bottom:"top",top:"bottom"}
function i(e){return e.replace(/left|right|bottom|top/g,(function(e){return n[e]}))}var o=r(8983),s={start:"end",end:"start"}
function a(e){return e.replace(/start|end/g,(function(e){return s[e]}))}var l=r(8006),c=r(6118),u=r(8713)
const p={name:"flip",enabled:!0,phase:"main",fn:function(e){var t=e.state,r=e.options,n=e.name
if(!t.modifiersData[n]._skip){for(var s=r.mainAxis,p=void 0===s||s,h=r.altAxis,d=void 0===h||h,f=r.fallbackPlacements,m=r.padding,g=r.boundary,v=r.rootBoundary,y=r.altBoundary,b=r.flipVariations,w=void 0===b||b,k=r.allowedAutoPlacements,_=t.options.placement,x=(0,o.Z)(_),P=f||(x!==_&&w?function(e){if((0,o.Z)(e)===u.d7)return[]
var t=i(e)
return[a(e),t,a(t)]}(_):[i(_)]),S=[_].concat(P).reduce((function(e,r){return e.concat((0,o.Z)(r)===u.d7?function(e,t){void 0===t&&(t={})
var r=t,n=r.placement,i=r.boundary,s=r.rootBoundary,a=r.padding,p=r.flipVariations,h=r.allowedAutoPlacements,d=void 0===h?u.Ct:h,f=(0,c.Z)(n),m=f?p?u.bw:u.bw.filter((function(e){return(0,c.Z)(e)===f})):u.mv,g=m.filter((function(e){return d.indexOf(e)>=0}))
0===g.length&&(g=m)
var v=g.reduce((function(t,r){return t[r]=(0,l.Z)(e,{placement:r,boundary:i,rootBoundary:s,padding:a})[(0,o.Z)(r)],t}),{})
return Object.keys(v).sort((function(e,t){return v[e]-v[t]}))}(t,{placement:r,boundary:g,rootBoundary:v,padding:m,flipVariations:w,allowedAutoPlacements:k}):r)}),[]),E=t.rects.reference,O=t.rects.popper,A=new Map,C=!0,T=S[0],L=0;L<S.length;L++){var j=S[L],I=(0,o.Z)(j),R=(0,c.Z)(j)===u.BL,N=[u.we,u.I].indexOf(I)>=0,U=N?"width":"height",F=(0,l.Z)(t,{placement:j,boundary:g,rootBoundary:v,altBoundary:y,padding:m}),M=N?R?u.F2:u.t$:R?u.I:u.we
E[U]>O[U]&&(M=i(M))
var D=i(M),H=[]
if(p&&H.push(F[I]<=0),d&&H.push(F[M]<=0,F[D]<=0),H.every((function(e){return e}))){T=j,C=!1
break}A.set(j,H)}if(C)for(var B=function(e){var t=S.find((function(t){var r=A.get(t)
if(r)return r.slice(0,e).every((function(e){return e}))}))
if(t)return T=t,"break"},Z=w?3:1;Z>0&&"break"!==B(Z);Z--);t.placement!==T&&(t.modifiersData[n]._skip=!0,t.placement=T,t.reset=!0)}},requiresIfExists:["offset"],data:{_skip:!1}}},3077:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>a})
var n=r(8713),i=r(8006)
function o(e,t,r){return void 0===r&&(r={x:0,y:0}),{top:e.top-t.height-r.y,right:e.right-t.width+r.x,bottom:e.bottom-t.height+r.y,left:e.left-t.width-r.x}}function s(e){return[n.we,n.F2,n.I,n.t$].some((function(t){return e[t]>=0}))}const a={name:"hide",enabled:!0,phase:"main",requiresIfExists:["preventOverflow"],fn:function(e){var t=e.state,r=e.name,n=t.rects.reference,a=t.rects.popper,l=t.modifiersData.preventOverflow,c=(0,i.Z)(t,{elementContext:"reference"}),u=(0,i.Z)(t,{altBoundary:!0}),p=o(c,n),h=o(u,a,l),d=s(p),f=s(h)
t.modifiersData[r]={referenceClippingOffsets:p,popperEscapeOffsets:h,isReferenceHidden:d,hasPopperEscaped:f},t.attributes.popper=Object.assign({},t.attributes.popper,{"data-popper-reference-hidden":d,"data-popper-escaped":f})}}},7347:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>o})
var n=r(8983),i=r(8713)
const o={name:"offset",enabled:!0,phase:"main",requires:["popperOffsets"],fn:function(e){var t=e.state,r=e.options,o=e.name,s=r.offset,a=void 0===s?[0,0]:s,l=i.Ct.reduce((function(e,r){return e[r]=function(e,t,r){var o=(0,n.Z)(e),s=[i.t$,i.we].indexOf(o)>=0?-1:1,a="function"==typeof r?r(Object.assign({},t,{placement:e})):r,l=a[0],c=a[1]
return l=l||0,c=(c||0)*s,[i.t$,i.F2].indexOf(o)>=0?{x:c,y:l}:{x:l,y:c}}(r,t.rects,a),e}),{}),c=l[t.placement],u=c.x,p=c.y
null!=t.modifiersData.popperOffsets&&(t.modifiersData.popperOffsets.x+=u,t.modifiersData.popperOffsets.y+=p),t.modifiersData[o]=l}}},502:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(9594)
const i={name:"popperOffsets",enabled:!0,phase:"read",fn:function(e){var t=e.state,r=e.name
t.modifiersData[r]=(0,n.Z)({reference:t.rects.reference,element:t.rects.popper,strategy:"absolute",placement:t.placement})},data:{}}},1144:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>d})
var n=r(8713),i=r(8983),o=r(9561),s=r(1188),a=r(3864),l=r(8217),c=r(8006),u=r(6118),p=r(2868),h=r(7529)
const d={name:"preventOverflow",enabled:!0,phase:"main",fn:function(e){var t=e.state,r=e.options,d=e.name,f=r.mainAxis,m=void 0===f||f,g=r.altAxis,v=void 0!==g&&g,y=r.boundary,b=r.rootBoundary,w=r.altBoundary,k=r.padding,_=r.tether,x=void 0===_||_,P=r.tetherOffset,S=void 0===P?0:P,E=(0,c.Z)(t,{boundary:y,rootBoundary:b,padding:k,altBoundary:w}),O=(0,i.Z)(t.placement),A=(0,u.Z)(t.placement),C=!A,T=(0,o.Z)(O),L="x"===T?"y":"x",j=t.modifiersData.popperOffsets,I=t.rects.reference,R=t.rects.popper,N="function"==typeof S?S(Object.assign({},t.rects,{placement:t.placement})):S,U="number"==typeof N?{mainAxis:N,altAxis:N}:Object.assign({mainAxis:0,altAxis:0},N),F=t.modifiersData.offset?t.modifiersData.offset[t.placement]:null,M={x:0,y:0}
if(j){if(m){var D,H="y"===T?n.we:n.t$,B="y"===T?n.I:n.F2,Z="y"===T?"height":"width",V=j[T],q=V+E[H],$=V-E[B],z=x?-R[Z]/2:0,W=A===n.BL?I[Z]:R[Z],K=A===n.BL?-R[Z]:-I[Z],X=t.elements.arrow,G=x&&X?(0,a.Z)(X):{width:0,height:0},Y=t.modifiersData["arrow#persistent"]?t.modifiersData["arrow#persistent"].padding:(0,p.Z)(),J=Y[H],Q=Y[B],ee=(0,s.u)(0,I[Z],G[Z]),te=C?I[Z]/2-z-ee-J-U.mainAxis:W-ee-J-U.mainAxis,re=C?-I[Z]/2+z+ee+Q+U.mainAxis:K+ee+Q+U.mainAxis,ne=t.elements.arrow&&(0,l.Z)(t.elements.arrow),ie=ne?"y"===T?ne.clientTop||0:ne.clientLeft||0:0,oe=null!=(D=null==F?void 0:F[T])?D:0,se=V+te-oe-ie,ae=V+re-oe,le=(0,s.u)(x?(0,h.VV)(q,se):q,V,x?(0,h.Fp)($,ae):$)
j[T]=le,M[T]=le-V}if(v){var ce,ue="x"===T?n.we:n.t$,pe="x"===T?n.I:n.F2,he=j[L],de="y"===L?"height":"width",fe=he+E[ue],me=he-E[pe],ge=-1!==[n.we,n.t$].indexOf(O),ve=null!=(ce=null==F?void 0:F[L])?ce:0,ye=ge?fe:he-I[de]-R[de]-ve+U.altAxis,be=ge?he+I[de]+R[de]-ve-U.altAxis:me,we=x&&ge?(0,s.q)(ye,he,be):(0,s.u)(x?ye:fe,he,x?be:me)
j[L]=we,M[L]=we-he}t.modifiersData[d]=M}},requiresIfExists:["offset"]}},2152:(e,t,r)=>{"use strict"
r.d(t,{fi:()=>f})
var n=r(1518),i=r(5210),o=r(502),s=r(353),a=r(175),l=r(7347),c=r(7730),u=r(1144),p=r(642),h=r(3077),d=[i.Z,o.Z,s.Z,a.Z,l.Z,c.Z,u.Z,p.Z,h.Z],f=(0,n.kZ)({defaultModifiers:d})},9594:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>a})
var n=r(8983),i=r(6118),o=r(9561),s=r(8713)
function a(e){var t,r=e.reference,a=e.element,l=e.placement,c=l?(0,n.Z)(l):null,u=l?(0,i.Z)(l):null,p=r.x+r.width/2-a.width/2,h=r.y+r.height/2-a.height/2
switch(c){case s.we:t={x:p,y:r.y-a.height}
break
case s.I:t={x:p,y:r.y+r.height}
break
case s.F2:t={x:r.x+r.width,y:h}
break
case s.t$:t={x:r.x-a.width,y:h}
break
default:t={x:r.x,y:r.y}}var d=c?(0,o.Z)(c):null
if(null!=d){var f="y"===d?"height":"width"
switch(u){case s.BL:t[d]=t[d]-(r[f]/2-a[f]/2)
break
case s.ut:t[d]=t[d]+(r[f]/2-a[f]/2)}}return t}},8006:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>x})
var n=r(8713),i=r(8012),o=r(4094),s=r(5741),a=r(3063),l=r(9987),c=r(6823),u=r(7529),p=r(5763),h=r(8217),d=r(7729),f=r(1863),m=r(4407),g=r(3268),v=r(1671)
function y(e){return Object.assign({},e,{left:e.x,top:e.y,right:e.x+e.width,bottom:e.y+e.height})}function b(e,t,r){return t===n.Pj?y(function(e,t){var r=(0,i.Z)(e),n=(0,o.Z)(e),l=r.visualViewport,c=n.clientWidth,u=n.clientHeight,p=0,h=0
if(l){c=l.width,u=l.height
var d=(0,a.Z)();(d||!d&&"fixed"===t)&&(p=l.offsetLeft,h=l.offsetTop)}return{width:c,height:u,x:p+(0,s.Z)(e),y:h}}(e,r)):(0,d.kK)(t)?function(e,t){var r=(0,f.Z)(e,!1,"fixed"===t)
return r.top=r.top+e.clientTop,r.left=r.left+e.clientLeft,r.bottom=r.top+e.clientHeight,r.right=r.left+e.clientWidth,r.width=e.clientWidth,r.height=e.clientHeight,r.x=r.left,r.y=r.top,r}(t,r):y(function(e){var t,r=(0,o.Z)(e),n=(0,c.Z)(e),i=null==(t=e.ownerDocument)?void 0:t.body,a=(0,u.Fp)(r.scrollWidth,r.clientWidth,i?i.scrollWidth:0,i?i.clientWidth:0),p=(0,u.Fp)(r.scrollHeight,r.clientHeight,i?i.scrollHeight:0,i?i.clientHeight:0),h=-n.scrollLeft+(0,s.Z)(e),d=-n.scrollTop
return"rtl"===(0,l.Z)(i||r).direction&&(h+=(0,u.Fp)(r.clientWidth,i?i.clientWidth:0)-a),{width:a,height:p,x:h,y:d}}((0,o.Z)(e)))}var w=r(9594),k=r(5414),_=r(8484)
function x(e,t){void 0===t&&(t={})
var r=t,i=r.placement,s=void 0===i?e.placement:i,a=r.strategy,c=void 0===a?e.strategy:a,x=r.boundary,P=void 0===x?n.zV:x,S=r.rootBoundary,E=void 0===S?n.Pj:S,O=r.elementContext,A=void 0===O?n.k5:O,C=r.altBoundary,T=void 0!==C&&C,L=r.padding,j=void 0===L?0:L,I=(0,k.Z)("number"!=typeof j?j:(0,_.Z)(j,n.mv)),R=A===n.k5?n.YP:n.k5,N=e.rects.popper,U=e.elements[T?R:A],F=function(e,t,r,n){var i="clippingParents"===t?function(e){var t=(0,p.Z)((0,m.Z)(e)),r=["absolute","fixed"].indexOf((0,l.Z)(e).position)>=0&&(0,d.Re)(e)?(0,h.Z)(e):e
return(0,d.kK)(r)?t.filter((function(e){return(0,d.kK)(e)&&(0,g.Z)(e,r)&&"body"!==(0,v.Z)(e)})):[]}(e):[].concat(t),o=[].concat(i,[r]),s=o[0],a=o.reduce((function(t,r){var i=b(e,r,n)
return t.top=(0,u.Fp)(i.top,t.top),t.right=(0,u.VV)(i.right,t.right),t.bottom=(0,u.VV)(i.bottom,t.bottom),t.left=(0,u.Fp)(i.left,t.left),t}),b(e,s,n))
return a.width=a.right-a.left,a.height=a.bottom-a.top,a.x=a.left,a.y=a.top,a}((0,d.kK)(U)?U:U.contextElement||(0,o.Z)(e.elements.popper),P,E,c),M=(0,f.Z)(e.elements.reference),D=(0,w.Z)({reference:M,element:N,strategy:"absolute",placement:s}),H=y(Object.assign({},N,D)),B=A===n.k5?H:M,Z={top:F.top-B.top+I.top,bottom:B.bottom-F.bottom+I.bottom,left:F.left-B.left+I.left,right:B.right-F.right+I.right},V=e.modifiersData.offset
if(A===n.k5&&V){var q=V[s]
Object.keys(Z).forEach((function(e){var t=[n.F2,n.I].indexOf(e)>=0?1:-1,r=[n.we,n.I].indexOf(e)>=0?"y":"x"
Z[e]+=q[r]*t}))}return Z}},8484:(e,t,r)=>{"use strict"
function n(e,t){return t.reduce((function(t,r){return t[r]=e,t}),{})}r.d(t,{Z:()=>n})},8983:(e,t,r)=>{"use strict"
function n(e){return e.split("-")[0]}r.d(t,{Z:()=>n})},2868:(e,t,r)=>{"use strict"
function n(){return{top:0,right:0,bottom:0,left:0}}r.d(t,{Z:()=>n})},9561:(e,t,r)=>{"use strict"
function n(e){return["top","bottom"].indexOf(e)>=0?"x":"y"}r.d(t,{Z:()=>n})},6118:(e,t,r)=>{"use strict"
function n(e){return e.split("-")[1]}r.d(t,{Z:()=>n})},7529:(e,t,r)=>{"use strict"
r.d(t,{Fp:()=>n,NM:()=>o,VV:()=>i})
var n=Math.max,i=Math.min,o=Math.round},5414:(e,t,r)=>{"use strict"
r.d(t,{Z:()=>i})
var n=r(2868)
function i(e){return Object.assign({},(0,n.Z)(),e)}},9422:(e,t,r)=>{"use strict"
function n(){var e=navigator.userAgentData
return null!=e&&e.brands?e.brands.map((function(e){return e.brand+"/"+e.version})).join(" "):navigator.userAgent}r.d(t,{Z:()=>n})},1188:(e,t,r)=>{"use strict"
r.d(t,{q:()=>o,u:()=>i})
var n=r(7529)
function i(e,t,r){return(0,n.Fp)(e,(0,n.VV)(t,r))}function o(e,t,r){var n=i(e,t,r)
return n>r?r:n}},204:e=>{e.exports=function(e){if("number"!=typeof e||isNaN(e))throw new TypeError("Expected a number, got "+typeof e)
var t=e<0,r=["B","KB","MB","GB","TB","PB","EB","ZB","YB"]
if(t&&(e=-e),e<1)return(t?"-":"")+e+" B"
var n=Math.min(Math.floor(Math.log(e)/Math.log(1024)),r.length-1)
e=Number(e/Math.pow(1024,n))
var i=r[n]
return e>=10||e%1==0?(t?"-":"")+e.toFixed(0)+" "+i:(t?"-":"")+e.toFixed(1)+" "+i}},9419:(e,t,r)=>{"use strict"
r.r(t),r.d(t,{default:()=>i})
var n=['a[href]:not([tabindex^="-"])','area[href]:not([tabindex^="-"])','input:not([type="hidden"]):not([type="radio"]):not([disabled]):not([tabindex^="-"])','input[type="radio"]:not([disabled]):not([tabindex^="-"])','select:not([disabled]):not([tabindex^="-"])','textarea:not([disabled]):not([tabindex^="-"])','button:not([disabled]):not([tabindex^="-"])','iframe:not([tabindex^="-"])','audio[controls]:not([tabindex^="-"])','video[controls]:not([tabindex^="-"])','[contenteditable]:not([tabindex^="-"])','[tabindex]:not([tabindex^="-"])']
function i(e){this._show=this.show.bind(this),this._hide=this.hide.bind(this),this._maintainFocus=this._maintainFocus.bind(this),this._bindKeypress=this._bindKeypress.bind(this),this.$el=e,this.shown=!1,this._id=this.$el.getAttribute("data-a11y-dialog")||this.$el.id,this._previouslyFocused=null,this._listeners={},this.create()}function o(e,t){return r=(t||document).querySelectorAll(e),Array.prototype.slice.call(r)
var r}function s(e){(e.querySelector("[autofocus]")||e).focus()}function a(){o("[data-a11y-dialog]").forEach((function(e){new i(e)}))}i.prototype.create=function(){this.$el.setAttribute("aria-hidden",!0),this.$el.setAttribute("aria-modal",!0),this.$el.setAttribute("tabindex",-1),this.$el.hasAttribute("role")||this.$el.setAttribute("role","dialog"),this._openers=o('[data-a11y-dialog-show="'+this._id+'"]'),this._openers.forEach(function(e){e.addEventListener("click",this._show)}.bind(this))
const e=this.$el
return this._closers=o("[data-a11y-dialog-hide]",this.$el).filter((function(t){return t.closest('[aria-modal="true"], [data-a11y-dialog]')===e})).concat(o('[data-a11y-dialog-hide="'+this._id+'"]')),this._closers.forEach(function(e){e.addEventListener("click",this._hide)}.bind(this)),this._fire("create"),this},i.prototype.show=function(e){return this.shown||(this._previouslyFocused=document.activeElement,this.$el.removeAttribute("aria-hidden"),this.shown=!0,s(this.$el),document.body.addEventListener("focus",this._maintainFocus,!0),document.addEventListener("keydown",this._bindKeypress),this._fire("show",e)),this},i.prototype.hide=function(e){return this.shown?(this.shown=!1,this.$el.setAttribute("aria-hidden","true"),this._previouslyFocused&&this._previouslyFocused.focus&&this._previouslyFocused.focus(),document.body.removeEventListener("focus",this._maintainFocus,!0),document.removeEventListener("keydown",this._bindKeypress),this._fire("hide",e),this):this},i.prototype.destroy=function(){return this.hide(),this._openers.forEach(function(e){e.removeEventListener("click",this._show)}.bind(this)),this._closers.forEach(function(e){e.removeEventListener("click",this._hide)}.bind(this)),this._fire("destroy"),this._listeners={},this},i.prototype.on=function(e,t){return void 0===this._listeners[e]&&(this._listeners[e]=[]),this._listeners[e].push(t),this},i.prototype.off=function(e,t){var r=(this._listeners[e]||[]).indexOf(t)
return r>-1&&this._listeners[e].splice(r,1),this},i.prototype._fire=function(e,t){var r=this._listeners[e]||[],n=new CustomEvent(e,{detail:t})
this.$el.dispatchEvent(n),r.forEach(function(e){e(this.$el,t)}.bind(this))},i.prototype._bindKeypress=function(e){const t=document.activeElement
t&&t.closest('[aria-modal="true"]')!==this.$el||(this.shown&&"Escape"===e.key&&"alertdialog"!==this.$el.getAttribute("role")&&(e.preventDefault(),this.hide(e)),this.shown&&"Tab"===e.key&&function(e,t){var r=function(e){return o(n.join(","),e).filter((function(e){return!!(e.offsetWidth||e.offsetHeight||e.getClientRects().length)}))}(e),i=r.indexOf(document.activeElement)
t.shiftKey&&0===i?(r[r.length-1].focus(),t.preventDefault()):t.shiftKey||i!==r.length-1||(r[0].focus(),t.preventDefault())}(this.$el,e))},i.prototype._maintainFocus=function(e){!this.shown||e.target.closest('[aria-modal="true"]')||e.target.closest("[data-a11y-dialog-ignore-focus-trap]")||s(this.$el)},"undefined"!=typeof document&&("loading"===document.readyState?document.addEventListener("DOMContentLoaded",a):window.requestAnimationFrame?window.requestAnimationFrame(a):window.setTimeout(a,16))},2316:e=>{e.exports=function(e){var t,r=String.prototype.split,n=/()??/.exec("")[1]===e
return t=function(t,i,o){if("[object RegExp]"!==Object.prototype.toString.call(i))return r.call(t,i,o)
var s,a,l,c,u=[],p=(i.ignoreCase?"i":"")+(i.multiline?"m":"")+(i.extended?"x":"")+(i.sticky?"y":""),h=0
for(i=new RegExp(i.source,p+"g"),t+="",n||(s=new RegExp("^"+i.source+"$(?!\\s)",p)),o=o===e?-1>>>0:o>>>0;(a=i.exec(t))&&!((l=a.index+a[0].length)>h&&(u.push(t.slice(h,a.index)),!n&&a.length>1&&a[0].replace(s,(function(){for(var t=1;t<arguments.length-2;t++)arguments[t]===e&&(a[t]=e)})),a.length>1&&a.index<t.length&&Array.prototype.push.apply(u,a.slice(1)),c=a[0].length,h=l,u.length>=o));)i.lastIndex===a.index&&i.lastIndex++
return h===t.length?!c&&i.test("")||u.push(""):u.push(t.slice(h)),u.length>o?u.slice(0,o):u},t}()},181:(e,t,r)=>{var n=r(815),i=r(8998)
function o(e){return null==e}function s(e){(e=function(e){var t={}
for(var r in e)t[r]=e[r]
return t}(e||{})).whiteList=e.whiteList||n.whiteList,e.onAttr=e.onAttr||n.onAttr,e.onIgnoreAttr=e.onIgnoreAttr||n.onIgnoreAttr,e.safeAttrValue=e.safeAttrValue||n.safeAttrValue,this.options=e}r(2939),s.prototype.process=function(e){if(!(e=(e=e||"").toString()))return""
var t=this.options,r=t.whiteList,n=t.onAttr,s=t.onIgnoreAttr,a=t.safeAttrValue
return i(e,(function(e,t,i,l,c){var u=r[i],p=!1
if(!0===u?p=u:"function"==typeof u?p=u(l):u instanceof RegExp&&(p=u.test(l)),!0!==p&&(p=!1),l=a(i,l)){var h,d={position:t,sourcePosition:e,source:c,isWhite:p}
return p?o(h=n(i,l,d))?i+":"+l:h:o(h=s(i,l,d))?void 0:h}}))},e.exports=s},815:(e,t)=>{var r=/javascript\s*\:/gim
t.whiteList={"align-content":!1,"align-items":!1,"align-self":!1,"alignment-adjust":!1,"alignment-baseline":!1,all:!1,"anchor-point":!1,animation:!1,"animation-delay":!1,"animation-direction":!1,"animation-duration":!1,"animation-fill-mode":!1,"animation-iteration-count":!1,"animation-name":!1,"animation-play-state":!1,"animation-timing-function":!1,azimuth:!1,"backface-visibility":!1,background:!0,"background-attachment":!0,"background-clip":!0,"background-color":!0,"background-image":!0,"background-origin":!0,"background-position":!0,"background-repeat":!0,"background-size":!0,"baseline-shift":!1,binding:!1,bleed:!1,"bookmark-label":!1,"bookmark-level":!1,"bookmark-state":!1,border:!0,"border-bottom":!0,"border-bottom-color":!0,"border-bottom-left-radius":!0,"border-bottom-right-radius":!0,"border-bottom-style":!0,"border-bottom-width":!0,"border-collapse":!0,"border-color":!0,"border-image":!0,"border-image-outset":!0,"border-image-repeat":!0,"border-image-slice":!0,"border-image-source":!0,"border-image-width":!0,"border-left":!0,"border-left-color":!0,"border-left-style":!0,"border-left-width":!0,"border-radius":!0,"border-right":!0,"border-right-color":!0,"border-right-style":!0,"border-right-width":!0,"border-spacing":!0,"border-style":!0,"border-top":!0,"border-top-color":!0,"border-top-left-radius":!0,"border-top-right-radius":!0,"border-top-style":!0,"border-top-width":!0,"border-width":!0,bottom:!1,"box-decoration-break":!0,"box-shadow":!0,"box-sizing":!0,"box-snap":!0,"box-suppress":!0,"break-after":!0,"break-before":!0,"break-inside":!0,"caption-side":!1,chains:!1,clear:!0,clip:!1,"clip-path":!1,"clip-rule":!1,color:!0,"color-interpolation-filters":!0,"column-count":!1,"column-fill":!1,"column-gap":!1,"column-rule":!1,"column-rule-color":!1,"column-rule-style":!1,"column-rule-width":!1,"column-span":!1,"column-width":!1,columns:!1,contain:!1,content:!1,"counter-increment":!1,"counter-reset":!1,"counter-set":!1,crop:!1,cue:!1,"cue-after":!1,"cue-before":!1,cursor:!1,direction:!1,display:!0,"display-inside":!0,"display-list":!0,"display-outside":!0,"dominant-baseline":!1,elevation:!1,"empty-cells":!1,filter:!1,flex:!1,"flex-basis":!1,"flex-direction":!1,"flex-flow":!1,"flex-grow":!1,"flex-shrink":!1,"flex-wrap":!1,float:!1,"float-offset":!1,"flood-color":!1,"flood-opacity":!1,"flow-from":!1,"flow-into":!1,font:!0,"font-family":!0,"font-feature-settings":!0,"font-kerning":!0,"font-language-override":!0,"font-size":!0,"font-size-adjust":!0,"font-stretch":!0,"font-style":!0,"font-synthesis":!0,"font-variant":!0,"font-variant-alternates":!0,"font-variant-caps":!0,"font-variant-east-asian":!0,"font-variant-ligatures":!0,"font-variant-numeric":!0,"font-variant-position":!0,"font-weight":!0,grid:!1,"grid-area":!1,"grid-auto-columns":!1,"grid-auto-flow":!1,"grid-auto-rows":!1,"grid-column":!1,"grid-column-end":!1,"grid-column-start":!1,"grid-row":!1,"grid-row-end":!1,"grid-row-start":!1,"grid-template":!1,"grid-template-areas":!1,"grid-template-columns":!1,"grid-template-rows":!1,"hanging-punctuation":!1,height:!0,hyphens:!1,icon:!1,"image-orientation":!1,"image-resolution":!1,"ime-mode":!1,"initial-letters":!1,"inline-box-align":!1,"justify-content":!1,"justify-items":!1,"justify-self":!1,left:!1,"letter-spacing":!0,"lighting-color":!0,"line-box-contain":!1,"line-break":!1,"line-grid":!1,"line-height":!1,"line-snap":!1,"line-stacking":!1,"line-stacking-ruby":!1,"line-stacking-shift":!1,"line-stacking-strategy":!1,"list-style":!0,"list-style-image":!0,"list-style-position":!0,"list-style-type":!0,margin:!0,"margin-bottom":!0,"margin-left":!0,"margin-right":!0,"margin-top":!0,"marker-offset":!1,"marker-side":!1,marks:!1,mask:!1,"mask-box":!1,"mask-box-outset":!1,"mask-box-repeat":!1,"mask-box-slice":!1,"mask-box-source":!1,"mask-box-width":!1,"mask-clip":!1,"mask-image":!1,"mask-origin":!1,"mask-position":!1,"mask-repeat":!1,"mask-size":!1,"mask-source-type":!1,"mask-type":!1,"max-height":!0,"max-lines":!1,"max-width":!0,"min-height":!0,"min-width":!0,"move-to":!1,"nav-down":!1,"nav-index":!1,"nav-left":!1,"nav-right":!1,"nav-up":!1,"object-fit":!1,"object-position":!1,opacity:!1,order:!1,orphans:!1,outline:!1,"outline-color":!1,"outline-offset":!1,"outline-style":!1,"outline-width":!1,overflow:!1,"overflow-wrap":!1,"overflow-x":!1,"overflow-y":!1,padding:!0,"padding-bottom":!0,"padding-left":!0,"padding-right":!0,"padding-top":!0,page:!1,"page-break-after":!1,"page-break-before":!1,"page-break-inside":!1,"page-policy":!1,pause:!1,"pause-after":!1,"pause-before":!1,perspective:!1,"perspective-origin":!1,pitch:!1,"pitch-range":!1,"play-during":!1,position:!1,"presentation-level":!1,quotes:!1,"region-fragment":!1,resize:!1,rest:!1,"rest-after":!1,"rest-before":!1,richness:!1,right:!1,rotation:!1,"rotation-point":!1,"ruby-align":!1,"ruby-merge":!1,"ruby-position":!1,"shape-image-threshold":!1,"shape-outside":!1,"shape-margin":!1,size:!1,speak:!1,"speak-as":!1,"speak-header":!1,"speak-numeral":!1,"speak-punctuation":!1,"speech-rate":!1,stress:!1,"string-set":!1,"tab-size":!1,"table-layout":!1,"text-align":!0,"text-align-last":!0,"text-combine-upright":!0,"text-decoration":!0,"text-decoration-color":!0,"text-decoration-line":!0,"text-decoration-skip":!0,"text-decoration-style":!0,"text-emphasis":!0,"text-emphasis-color":!0,"text-emphasis-position":!0,"text-emphasis-style":!0,"text-height":!0,"text-indent":!0,"text-justify":!0,"text-orientation":!0,"text-overflow":!0,"text-shadow":!0,"text-space-collapse":!0,"text-transform":!0,"text-underline-position":!0,"text-wrap":!0,top:!1,transform:!1,"transform-origin":!1,"transform-style":!1,transition:!1,"transition-delay":!1,"transition-duration":!1,"transition-property":!1,"transition-timing-function":!1,"unicode-bidi":!1,"vertical-align":!1,visibility:!1,"voice-balance":!1,"voice-duration":!1,"voice-family":!1,"voice-pitch":!1,"voice-range":!1,"voice-rate":!1,"voice-stress":!1,"voice-volume":!1,volume:!1,"white-space":!1,widows:!1,width:!0,"will-change":!1,"word-break":!0,"word-spacing":!0,"word-wrap":!0,"wrap-flow":!1,"wrap-through":!1,"writing-mode":!1,"z-index":!1},t.getDefaultWhiteList=function(){return{"align-content":!1,"align-items":!1,"align-self":!1,"alignment-adjust":!1,"alignment-baseline":!1,all:!1,"anchor-point":!1,animation:!1,"animation-delay":!1,"animation-direction":!1,"animation-duration":!1,"animation-fill-mode":!1,"animation-iteration-count":!1,"animation-name":!1,"animation-play-state":!1,"animation-timing-function":!1,azimuth:!1,"backface-visibility":!1,background:!0,"background-attachment":!0,"background-clip":!0,"background-color":!0,"background-image":!0,"background-origin":!0,"background-position":!0,"background-repeat":!0,"background-size":!0,"baseline-shift":!1,binding:!1,bleed:!1,"bookmark-label":!1,"bookmark-level":!1,"bookmark-state":!1,border:!0,"border-bottom":!0,"border-bottom-color":!0,"border-bottom-left-radius":!0,"border-bottom-right-radius":!0,"border-bottom-style":!0,"border-bottom-width":!0,"border-collapse":!0,"border-color":!0,"border-image":!0,"border-image-outset":!0,"border-image-repeat":!0,"border-image-slice":!0,"border-image-source":!0,"border-image-width":!0,"border-left":!0,"border-left-color":!0,"border-left-style":!0,"border-left-width":!0,"border-radius":!0,"border-right":!0,"border-right-color":!0,"border-right-style":!0,"border-right-width":!0,"border-spacing":!0,"border-style":!0,"border-top":!0,"border-top-color":!0,"border-top-left-radius":!0,"border-top-right-radius":!0,"border-top-style":!0,"border-top-width":!0,"border-width":!0,bottom:!1,"box-decoration-break":!0,"box-shadow":!0,"box-sizing":!0,"box-snap":!0,"box-suppress":!0,"break-after":!0,"break-before":!0,"break-inside":!0,"caption-side":!1,chains:!1,clear:!0,clip:!1,"clip-path":!1,"clip-rule":!1,color:!0,"color-interpolation-filters":!0,"column-count":!1,"column-fill":!1,"column-gap":!1,"column-rule":!1,"column-rule-color":!1,"column-rule-style":!1,"column-rule-width":!1,"column-span":!1,"column-width":!1,columns:!1,contain:!1,content:!1,"counter-increment":!1,"counter-reset":!1,"counter-set":!1,crop:!1,cue:!1,"cue-after":!1,"cue-before":!1,cursor:!1,direction:!1,display:!0,"display-inside":!0,"display-list":!0,"display-outside":!0,"dominant-baseline":!1,elevation:!1,"empty-cells":!1,filter:!1,flex:!1,"flex-basis":!1,"flex-direction":!1,"flex-flow":!1,"flex-grow":!1,"flex-shrink":!1,"flex-wrap":!1,float:!1,"float-offset":!1,"flood-color":!1,"flood-opacity":!1,"flow-from":!1,"flow-into":!1,font:!0,"font-family":!0,"font-feature-settings":!0,"font-kerning":!0,"font-language-override":!0,"font-size":!0,"font-size-adjust":!0,"font-stretch":!0,"font-style":!0,"font-synthesis":!0,"font-variant":!0,"font-variant-alternates":!0,"font-variant-caps":!0,"font-variant-east-asian":!0,"font-variant-ligatures":!0,"font-variant-numeric":!0,"font-variant-position":!0,"font-weight":!0,grid:!1,"grid-area":!1,"grid-auto-columns":!1,"grid-auto-flow":!1,"grid-auto-rows":!1,"grid-column":!1,"grid-column-end":!1,"grid-column-start":!1,"grid-row":!1,"grid-row-end":!1,"grid-row-start":!1,"grid-template":!1,"grid-template-areas":!1,"grid-template-columns":!1,"grid-template-rows":!1,"hanging-punctuation":!1,height:!0,hyphens:!1,icon:!1,"image-orientation":!1,"image-resolution":!1,"ime-mode":!1,"initial-letters":!1,"inline-box-align":!1,"justify-content":!1,"justify-items":!1,"justify-self":!1,left:!1,"letter-spacing":!0,"lighting-color":!0,"line-box-contain":!1,"line-break":!1,"line-grid":!1,"line-height":!1,"line-snap":!1,"line-stacking":!1,"line-stacking-ruby":!1,"line-stacking-shift":!1,"line-stacking-strategy":!1,"list-style":!0,"list-style-image":!0,"list-style-position":!0,"list-style-type":!0,margin:!0,"margin-bottom":!0,"margin-left":!0,"margin-right":!0,"margin-top":!0,"marker-offset":!1,"marker-side":!1,marks:!1,mask:!1,"mask-box":!1,"mask-box-outset":!1,"mask-box-repeat":!1,"mask-box-slice":!1,"mask-box-source":!1,"mask-box-width":!1,"mask-clip":!1,"mask-image":!1,"mask-origin":!1,"mask-position":!1,"mask-repeat":!1,"mask-size":!1,"mask-source-type":!1,"mask-type":!1,"max-height":!0,"max-lines":!1,"max-width":!0,"min-height":!0,"min-width":!0,"move-to":!1,"nav-down":!1,"nav-index":!1,"nav-left":!1,"nav-right":!1,"nav-up":!1,"object-fit":!1,"object-position":!1,opacity:!1,order:!1,orphans:!1,outline:!1,"outline-color":!1,"outline-offset":!1,"outline-style":!1,"outline-width":!1,overflow:!1,"overflow-wrap":!1,"overflow-x":!1,"overflow-y":!1,padding:!0,"padding-bottom":!0,"padding-left":!0,"padding-right":!0,"padding-top":!0,page:!1,"page-break-after":!1,"page-break-before":!1,"page-break-inside":!1,"page-policy":!1,pause:!1,"pause-after":!1,"pause-before":!1,perspective:!1,"perspective-origin":!1,pitch:!1,"pitch-range":!1,"play-during":!1,position:!1,"presentation-level":!1,quotes:!1,"region-fragment":!1,resize:!1,rest:!1,"rest-after":!1,"rest-before":!1,richness:!1,right:!1,rotation:!1,"rotation-point":!1,"ruby-align":!1,"ruby-merge":!1,"ruby-position":!1,"shape-image-threshold":!1,"shape-outside":!1,"shape-margin":!1,size:!1,speak:!1,"speak-as":!1,"speak-header":!1,"speak-numeral":!1,"speak-punctuation":!1,"speech-rate":!1,stress:!1,"string-set":!1,"tab-size":!1,"table-layout":!1,"text-align":!0,"text-align-last":!0,"text-combine-upright":!0,"text-decoration":!0,"text-decoration-color":!0,"text-decoration-line":!0,"text-decoration-skip":!0,"text-decoration-style":!0,"text-emphasis":!0,"text-emphasis-color":!0,"text-emphasis-position":!0,"text-emphasis-style":!0,"text-height":!0,"text-indent":!0,"text-justify":!0,"text-orientation":!0,"text-overflow":!0,"text-shadow":!0,"text-space-collapse":!0,"text-transform":!0,"text-underline-position":!0,"text-wrap":!0,top:!1,transform:!1,"transform-origin":!1,"transform-style":!1,transition:!1,"transition-delay":!1,"transition-duration":!1,"transition-property":!1,"transition-timing-function":!1,"unicode-bidi":!1,"vertical-align":!1,visibility:!1,"voice-balance":!1,"voice-duration":!1,"voice-family":!1,"voice-pitch":!1,"voice-range":!1,"voice-rate":!1,"voice-stress":!1,"voice-volume":!1,volume:!1,"white-space":!1,widows:!1,width:!0,"will-change":!1,"word-break":!0,"word-spacing":!0,"word-wrap":!0,"wrap-flow":!1,"wrap-through":!1,"writing-mode":!1,"z-index":!1}},t.onAttr=function(e,t,r){},t.onIgnoreAttr=function(e,t,r){},t.safeAttrValue=function(e,t){return r.test(t)?"":t}},8223:(e,t,r)=>{var n=r(815),i=r(181)
for(var o in(t=e.exports=function(e,t){return new i(t).process(e)}).FilterCSS=i,n)t[o]=n[o]
"undefined"!=typeof window&&(window.filterCSS=e.exports)},8998:(e,t,r)=>{var n=r(2939)
e.exports=function(e,t){";"!==(e=n.trimRight(e))[e.length-1]&&(e+=";")
var r=e.length,i=!1,o=0,s=0,a=""
function l(){if(!i){var r=n.trim(e.slice(o,s)),l=r.indexOf(":")
if(-1!==l){var c=n.trim(r.slice(0,l)),u=n.trim(r.slice(l+1))
if(c){var p=t(o,a.length,c,u,r)
p&&(a+=p+"; ")}}}o=s+1}for(;s<r;s++){var c=e[s]
if("/"===c&&"*"===e[s+1]){var u=e.indexOf("*/",s+2)
if(-1===u)break
o=(s=u+1)+1,i=!1}else"("===c?i=!0:")"===c?i=!1:";"===c?i||l():"\n"===c&&l()}return n.trim(a)}},2939:e=>{e.exports={indexOf:function(e,t){var r,n
if(Array.prototype.indexOf)return e.indexOf(t)
for(r=0,n=e.length;r<n;r++)if(e[r]===t)return r
return-1},forEach:function(e,t,r){var n,i
if(Array.prototype.forEach)return e.forEach(t,r)
for(n=0,i=e.length;n<i;n++)t.call(r,e[n],n,e)},trim:function(e){return String.prototype.trim?e.trim():e.replace(/(^\s*)|(\s*$)/g,"")},trimRight:function(e){return String.prototype.trimRight?e.trimRight():e.replace(/(\s*$)/g,"")}}},2612:(e,t,r)=>{"use strict"
r(1678)("ev-store","7")
var n="__EV_STORE_KEY@7"
e.exports=function(e){var t=e[n]
return t||(t=e[n]={}),t}},2957:(e,t,r)=>{var n,i="undefined"!=typeof global?global:"undefined"!=typeof window?window:{},o=r(444)
"undefined"!=typeof document?n=document:(n=i["__GLOBAL_DOCUMENT_CACHE@4"])||(n=i["__GLOBAL_DOCUMENT_CACHE@4"]=o),e.exports=n},1977:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0
var i=n(r(2505)),o=n(r(9758)),s=r(8146),a=r(3204),l=n(r(7868)),c=n(r(5861)),u=n(r(8226)),p=i.default.create
function h(){var e=p()
return e.compile=function(t,r){return a.compile(t,r,e)},e.precompile=function(t,r){return a.precompile(t,r,e)},e.AST=o.default,e.Compiler=a.Compiler,e.JavaScriptCompiler=l.default,e.Parser=s.parser,e.parse=s.parse,e.parseWithoutProcessing=s.parseWithoutProcessing,e}var d=h()
d.create=h,u.default(d),d.Visitor=c.default,d.default=d,t.default=d,e.exports=t.default},2505:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}function i(e){if(e&&e.__esModule)return e
var t={}
if(null!=e)for(var r in e)Object.prototype.hasOwnProperty.call(e,r)&&(t[r]=e[r])
return t.default=e,t}t.__esModule=!0
var o=i(r(6713)),s=n(r(1373)),a=n(r(3800)),l=i(r(699)),c=i(r(9771)),u=n(r(8226))
function p(){var e=new o.HandlebarsEnvironment
return l.extend(e,o),e.SafeString=s.default,e.Exception=a.default,e.Utils=l,e.escapeExpression=l.escapeExpression,e.VM=c,e.template=function(t){return c.template(t,e)},e}var h=p()
h.create=p,u.default(h),h.default=h,t.default=h,e.exports=t.default},6713:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0,t.HandlebarsEnvironment=p
var i=r(699),o=n(r(3800)),s=r(8843),a=r(781),l=n(r(7266)),c=r(2038)
t.VERSION="4.7.7",t.COMPILER_REVISION=8,t.LAST_COMPATIBLE_COMPILER_REVISION=7,t.REVISION_CHANGES={1:"<= 1.0.rc.2",2:"== 1.0.0-rc.3",3:"== 1.0.0-rc.4",4:"== 1.x.x",5:"== 2.0.0-alpha.x",6:">= 2.0.0-beta.1",7:">= 4.0.0 <4.3.0",8:">= 4.3.0"}
var u="[object Object]"
function p(e,t,r){this.helpers=e||{},this.partials=t||{},this.decorators=r||{},s.registerDefaultHelpers(this),a.registerDefaultDecorators(this)}p.prototype={constructor:p,logger:l.default,log:l.default.log,registerHelper:function(e,t){if(i.toString.call(e)===u){if(t)throw new o.default("Arg not supported with multiple helpers")
i.extend(this.helpers,e)}else this.helpers[e]=t},unregisterHelper:function(e){delete this.helpers[e]},registerPartial:function(e,t){if(i.toString.call(e)===u)i.extend(this.partials,e)
else{if(void 0===t)throw new o.default('Attempting to register a partial called "'+e+'" as undefined')
this.partials[e]=t}},unregisterPartial:function(e){delete this.partials[e]},registerDecorator:function(e,t){if(i.toString.call(e)===u){if(t)throw new o.default("Arg not supported with multiple decorators")
i.extend(this.decorators,e)}else this.decorators[e]=t},unregisterDecorator:function(e){delete this.decorators[e]},resetLoggedPropertyAccesses:function(){c.resetLoggedProperties()}}
var h=l.default.log
t.log=h,t.createFrame=i.createFrame,t.logger=l.default},9758:(e,t)=>{"use strict"
t.__esModule=!0
var r={helpers:{helperExpression:function(e){return"SubExpression"===e.type||("MustacheStatement"===e.type||"BlockStatement"===e.type)&&!!(e.params&&e.params.length||e.hash)},scopedId:function(e){return/^\.|this\b/.test(e.original)},simpleId:function(e){return 1===e.parts.length&&!r.helpers.scopedId(e)&&!e.depth}}}
t.default=r,e.exports=t.default},8146:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0,t.parseWithoutProcessing=c,t.parse=function(e,t){var r=c(e,t)
return new o.default(t).accept(r)}
var i=n(r(6398)),o=n(r(6825)),s=function(e){if(e&&e.__esModule)return e
var t={}
if(null!=e)for(var r in e)Object.prototype.hasOwnProperty.call(e,r)&&(t[r]=e[r])
return t.default=e,t}(r(386)),a=r(699)
t.parser=i.default
var l={}
function c(e,t){return"Program"===e.type?e:(i.default.yy=l,l.locInfo=function(e){return new l.SourceLocation(t&&t.srcName,e)},i.default.parse(e))}a.extend(l,s)},5079:(e,t,r)=>{"use strict"
t.__esModule=!0
var n=r(699),i=void 0
function o(e,t,r){if(n.isArray(e)){for(var i=[],o=0,s=e.length;o<s;o++)i.push(t.wrap(e[o],r))
return i}return"boolean"==typeof e||"number"==typeof e?e+"":e}function s(e){this.srcFile=e,this.source=[]}i||((i=function(e,t,r,n){this.src="",n&&this.add(n)}).prototype={add:function(e){n.isArray(e)&&(e=e.join("")),this.src+=e},prepend:function(e){n.isArray(e)&&(e=e.join("")),this.src=e+this.src},toStringWithSourceMap:function(){return{code:this.toString()}},toString:function(){return this.src}}),s.prototype={isEmpty:function(){return!this.source.length},prepend:function(e,t){this.source.unshift(this.wrap(e,t))},push:function(e,t){this.source.push(this.wrap(e,t))},merge:function(){var e=this.empty()
return this.each((function(t){e.add(["  ",t,"\n"])})),e},each:function(e){for(var t=0,r=this.source.length;t<r;t++)e(this.source[t])},empty:function(){var e=this.currentLocation||{start:{}}
return new i(e.start.line,e.start.column,this.srcFile)},wrap:function(e){var t=arguments.length<=1||void 0===arguments[1]?this.currentLocation||{start:{}}:arguments[1]
return e instanceof i?e:(e=o(e,this,t),new i(t.start.line,t.start.column,this.srcFile,e))},functionCall:function(e,t,r){return r=this.generateList(r),this.wrap([e,t?"."+t+"(":"(",r,")"])},quotedString:function(e){return'"'+(e+"").replace(/\\/g,"\\\\").replace(/"/g,'\\"').replace(/\n/g,"\\n").replace(/\r/g,"\\r").replace(/\u2028/g,"\\u2028").replace(/\u2029/g,"\\u2029")+'"'},objectLiteral:function(e){var t=this,r=[]
Object.keys(e).forEach((function(n){var i=o(e[n],t)
"undefined"!==i&&r.push([t.quotedString(n),":",i])}))
var n=this.generateList(r)
return n.prepend("{"),n.add("}"),n},generateList:function(e){for(var t=this.empty(),r=0,n=e.length;r<n;r++)r&&t.add(","),t.add(o(e[r],this))
return t},generateArray:function(e){var t=this.generateList(e)
return t.prepend("["),t.add("]"),t}},t.default=s,e.exports=t.default},3204:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0,t.Compiler=l,t.precompile=function(e,t,r){if(null==e||"string"!=typeof e&&"Program"!==e.type)throw new i.default("You must pass a string or Handlebars AST to Handlebars.precompile. You passed "+e)
"data"in(t=t||{})||(t.data=!0),t.compat&&(t.useDepths=!0)
var n=r.parse(e,t),o=(new r.Compiler).compile(n,t)
return(new r.JavaScriptCompiler).compile(o,t)},t.compile=function(e,t,r){if(void 0===t&&(t={}),null==e||"string"!=typeof e&&"Program"!==e.type)throw new i.default("You must pass a string or Handlebars AST to Handlebars.compile. You passed "+e)
"data"in(t=o.extend({},t))||(t.data=!0),t.compat&&(t.useDepths=!0)
var n=void 0
function s(){var n=r.parse(e,t),i=(new r.Compiler).compile(n,t),o=(new r.JavaScriptCompiler).compile(i,t,void 0,!0)
return r.template(o)}function a(e,t){return n||(n=s()),n.call(this,e,t)}return a._setup=function(e){return n||(n=s()),n._setup(e)},a._child=function(e,t,r,i){return n||(n=s()),n._child(e,t,r,i)},a}
var i=n(r(3800)),o=r(699),s=n(r(9758)),a=[].slice
function l(){}function c(e,t){if(e===t)return!0
if(o.isArray(e)&&o.isArray(t)&&e.length===t.length){for(var r=0;r<e.length;r++)if(!c(e[r],t[r]))return!1
return!0}}function u(e){if(!e.path.parts){var t=e.path
e.path={type:"PathExpression",data:!1,depth:0,parts:[t.original+""],original:t.original+"",loc:t.loc}}}l.prototype={compiler:l,equals:function(e){var t=this.opcodes.length
if(e.opcodes.length!==t)return!1
for(var r=0;r<t;r++){var n=this.opcodes[r],i=e.opcodes[r]
if(n.opcode!==i.opcode||!c(n.args,i.args))return!1}for(t=this.children.length,r=0;r<t;r++)if(!this.children[r].equals(e.children[r]))return!1
return!0},guid:0,compile:function(e,t){return this.sourceNode=[],this.opcodes=[],this.children=[],this.options=t,this.stringParams=t.stringParams,this.trackIds=t.trackIds,t.blockParams=t.blockParams||[],t.knownHelpers=o.extend(Object.create(null),{helperMissing:!0,blockHelperMissing:!0,each:!0,if:!0,unless:!0,with:!0,log:!0,lookup:!0},t.knownHelpers),this.accept(e)},compileProgram:function(e){var t=(new this.compiler).compile(e,this.options),r=this.guid++
return this.usePartial=this.usePartial||t.usePartial,this.children[r]=t,this.useDepths=this.useDepths||t.useDepths,r},accept:function(e){if(!this[e.type])throw new i.default("Unknown type: "+e.type,e)
this.sourceNode.unshift(e)
var t=this[e.type](e)
return this.sourceNode.shift(),t},Program:function(e){this.options.blockParams.unshift(e.blockParams)
for(var t=e.body,r=t.length,n=0;n<r;n++)this.accept(t[n])
return this.options.blockParams.shift(),this.isSimple=1===r,this.blockParams=e.blockParams?e.blockParams.length:0,this},BlockStatement:function(e){u(e)
var t=e.program,r=e.inverse
t=t&&this.compileProgram(t),r=r&&this.compileProgram(r)
var n=this.classifySexpr(e)
"helper"===n?this.helperSexpr(e,t,r):"simple"===n?(this.simpleSexpr(e),this.opcode("pushProgram",t),this.opcode("pushProgram",r),this.opcode("emptyHash"),this.opcode("blockValue",e.path.original)):(this.ambiguousSexpr(e,t,r),this.opcode("pushProgram",t),this.opcode("pushProgram",r),this.opcode("emptyHash"),this.opcode("ambiguousBlockValue")),this.opcode("append")},DecoratorBlock:function(e){var t=e.program&&this.compileProgram(e.program),r=this.setupFullMustacheParams(e,t,void 0),n=e.path
this.useDecorators=!0,this.opcode("registerDecorator",r.length,n.original)},PartialStatement:function(e){this.usePartial=!0
var t=e.program
t&&(t=this.compileProgram(e.program))
var r=e.params
if(r.length>1)throw new i.default("Unsupported number of partial arguments: "+r.length,e)
r.length||(this.options.explicitPartialContext?this.opcode("pushLiteral","undefined"):r.push({type:"PathExpression",parts:[],depth:0}))
var n=e.name.original,o="SubExpression"===e.name.type
o&&this.accept(e.name),this.setupFullMustacheParams(e,t,void 0,!0)
var s=e.indent||""
this.options.preventIndent&&s&&(this.opcode("appendContent",s),s=""),this.opcode("invokePartial",o,n,s),this.opcode("append")},PartialBlockStatement:function(e){this.PartialStatement(e)},MustacheStatement:function(e){this.SubExpression(e),e.escaped&&!this.options.noEscape?this.opcode("appendEscaped"):this.opcode("append")},Decorator:function(e){this.DecoratorBlock(e)},ContentStatement:function(e){e.value&&this.opcode("appendContent",e.value)},CommentStatement:function(){},SubExpression:function(e){u(e)
var t=this.classifySexpr(e)
"simple"===t?this.simpleSexpr(e):"helper"===t?this.helperSexpr(e):this.ambiguousSexpr(e)},ambiguousSexpr:function(e,t,r){var n=e.path,i=n.parts[0],o=null!=t||null!=r
this.opcode("getContext",n.depth),this.opcode("pushProgram",t),this.opcode("pushProgram",r),n.strict=!0,this.accept(n),this.opcode("invokeAmbiguous",i,o)},simpleSexpr:function(e){var t=e.path
t.strict=!0,this.accept(t),this.opcode("resolvePossibleLambda")},helperSexpr:function(e,t,r){var n=this.setupFullMustacheParams(e,t,r),o=e.path,a=o.parts[0]
if(this.options.knownHelpers[a])this.opcode("invokeKnownHelper",n.length,a)
else{if(this.options.knownHelpersOnly)throw new i.default("You specified knownHelpersOnly, but used the unknown helper "+a,e)
o.strict=!0,o.falsy=!0,this.accept(o),this.opcode("invokeHelper",n.length,o.original,s.default.helpers.simpleId(o))}},PathExpression:function(e){this.addDepth(e.depth),this.opcode("getContext",e.depth)
var t=e.parts[0],r=s.default.helpers.scopedId(e),n=!e.depth&&!r&&this.blockParamIndex(t)
n?this.opcode("lookupBlockParam",n,e.parts):t?e.data?(this.options.data=!0,this.opcode("lookupData",e.depth,e.parts,e.strict)):this.opcode("lookupOnContext",e.parts,e.falsy,e.strict,r):this.opcode("pushContext")},StringLiteral:function(e){this.opcode("pushString",e.value)},NumberLiteral:function(e){this.opcode("pushLiteral",e.value)},BooleanLiteral:function(e){this.opcode("pushLiteral",e.value)},UndefinedLiteral:function(){this.opcode("pushLiteral","undefined")},NullLiteral:function(){this.opcode("pushLiteral","null")},Hash:function(e){var t=e.pairs,r=0,n=t.length
for(this.opcode("pushHash");r<n;r++)this.pushParam(t[r].value)
for(;r--;)this.opcode("assignToHash",t[r].key)
this.opcode("popHash")},opcode:function(e){this.opcodes.push({opcode:e,args:a.call(arguments,1),loc:this.sourceNode[0].loc})},addDepth:function(e){e&&(this.useDepths=!0)},classifySexpr:function(e){var t=s.default.helpers.simpleId(e.path),r=t&&!!this.blockParamIndex(e.path.parts[0]),n=!r&&s.default.helpers.helperExpression(e),i=!r&&(n||t)
if(i&&!n){var o=e.path.parts[0],a=this.options
a.knownHelpers[o]?n=!0:a.knownHelpersOnly&&(i=!1)}return n?"helper":i?"ambiguous":"simple"},pushParams:function(e){for(var t=0,r=e.length;t<r;t++)this.pushParam(e[t])},pushParam:function(e){var t=null!=e.value?e.value:e.original||""
if(this.stringParams)t.replace&&(t=t.replace(/^(\.?\.\/)*/g,"").replace(/\//g,".")),e.depth&&this.addDepth(e.depth),this.opcode("getContext",e.depth||0),this.opcode("pushStringParam",t,e.type),"SubExpression"===e.type&&this.accept(e)
else{if(this.trackIds){var r=void 0
if(!e.parts||s.default.helpers.scopedId(e)||e.depth||(r=this.blockParamIndex(e.parts[0])),r){var n=e.parts.slice(1).join(".")
this.opcode("pushId","BlockParam",r,n)}else(t=e.original||t).replace&&(t=t.replace(/^this(?:\.|$)/,"").replace(/^\.\//,"").replace(/^\.$/,"")),this.opcode("pushId",e.type,t)}this.accept(e)}},setupFullMustacheParams:function(e,t,r,n){var i=e.params
return this.pushParams(i),this.opcode("pushProgram",t),this.opcode("pushProgram",r),e.hash?this.accept(e.hash):this.opcode("emptyHash",n),i},blockParamIndex:function(e){for(var t=0,r=this.options.blockParams.length;t<r;t++){var n=this.options.blockParams[t],i=n&&o.indexOf(n,e)
if(n&&i>=0)return[t,i]}}}},386:(e,t,r)=>{"use strict"
t.__esModule=!0,t.SourceLocation=function(e,t){this.source=e,this.start={line:t.first_line,column:t.first_column},this.end={line:t.last_line,column:t.last_column}},t.id=function(e){return/^\[.*\]$/.test(e)?e.substring(1,e.length-1):e},t.stripFlags=function(e,t){return{open:"~"===e.charAt(2),close:"~"===t.charAt(t.length-3)}},t.stripComment=function(e){return e.replace(/^\{\{~?!-?-?/,"").replace(/-?-?~?\}\}$/,"")},t.preparePath=function(e,t,r){r=this.locInfo(r)
for(var n=e?"@":"",o=[],s=0,a=0,l=t.length;a<l;a++){var c=t[a].part,u=t[a].original!==c
if(n+=(t[a].separator||"")+c,u||".."!==c&&"."!==c&&"this"!==c)o.push(c)
else{if(o.length>0)throw new i.default("Invalid path: "+n,{loc:r})
".."===c&&s++}}return{type:"PathExpression",data:e,depth:s,parts:o,original:n,loc:r}},t.prepareMustache=function(e,t,r,n,i,o){var s=n.charAt(3)||n.charAt(2),a="{"!==s&&"&"!==s
return{type:/\*/.test(n)?"Decorator":"MustacheStatement",path:e,params:t,hash:r,escaped:a,strip:i,loc:this.locInfo(o)}},t.prepareRawBlock=function(e,t,r,n){o(e,r)
var i={type:"Program",body:t,strip:{},loc:n=this.locInfo(n)}
return{type:"BlockStatement",path:e.path,params:e.params,hash:e.hash,program:i,openStrip:{},inverseStrip:{},closeStrip:{},loc:n}},t.prepareBlock=function(e,t,r,n,s,a){n&&n.path&&o(e,n)
var l=/\*/.test(e.open)
t.blockParams=e.blockParams
var c=void 0,u=void 0
if(r){if(l)throw new i.default("Unexpected inverse block on decorator",r)
r.chain&&(r.program.body[0].closeStrip=n.strip),u=r.strip,c=r.program}return s&&(s=c,c=t,t=s),{type:l?"DecoratorBlock":"BlockStatement",path:e.path,params:e.params,hash:e.hash,program:t,inverse:c,openStrip:e.strip,inverseStrip:u,closeStrip:n&&n.strip,loc:this.locInfo(a)}},t.prepareProgram=function(e,t){if(!t&&e.length){var r=e[0].loc,n=e[e.length-1].loc
r&&n&&(t={source:r.source,start:{line:r.start.line,column:r.start.column},end:{line:n.end.line,column:n.end.column}})}return{type:"Program",body:e,strip:{},loc:t}},t.preparePartialBlock=function(e,t,r,n){return o(e,r),{type:"PartialBlockStatement",name:e.path,params:e.params,hash:e.hash,program:t,openStrip:e.strip,closeStrip:r&&r.strip,loc:this.locInfo(n)}}
var n,i=(n=r(3800))&&n.__esModule?n:{default:n}
function o(e,t){if(t=t.path?t.path.original:t,e.path.original!==t){var r={loc:e.path.loc}
throw new i.default(e.path.original+" doesn't match "+t,r)}}},7868:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0
var i=r(6713),o=n(r(3800)),s=r(699),a=n(r(5079))
function l(e){this.value=e}function c(){}c.prototype={nameLookup:function(e,t){return this.internalNameLookup(e,t)},depthedLookup:function(e){return[this.aliasable("container.lookup"),"(depths, ",JSON.stringify(e),")"]},compilerInfo:function(){var e=i.COMPILER_REVISION
return[e,i.REVISION_CHANGES[e]]},appendToBuffer:function(e,t,r){return s.isArray(e)||(e=[e]),e=this.source.wrap(e,t),this.environment.isSimple?["return ",e,";"]:r?["buffer += ",e,";"]:(e.appendToBuffer=!0,e)},initializeBuffer:function(){return this.quotedString("")},internalNameLookup:function(e,t){return this.lookupPropertyFunctionIsUsed=!0,["lookupProperty(",e,",",JSON.stringify(t),")"]},lookupPropertyFunctionIsUsed:!1,compile:function(e,t,r,n){this.environment=e,this.options=t,this.stringParams=this.options.stringParams,this.trackIds=this.options.trackIds,this.precompile=!n,this.name=this.environment.name,this.isChild=!!r,this.context=r||{decorators:[],programs:[],environments:[]},this.preamble(),this.stackSlot=0,this.stackVars=[],this.aliases={},this.registers={list:[]},this.hashes=[],this.compileStack=[],this.inlineStack=[],this.blockParams=[],this.compileChildren(e,t),this.useDepths=this.useDepths||e.useDepths||e.useDecorators||this.options.compat,this.useBlockParams=this.useBlockParams||e.useBlockParams
var i=e.opcodes,s=void 0,a=void 0,l=void 0,c=void 0
for(l=0,c=i.length;l<c;l++)s=i[l],this.source.currentLocation=s.loc,a=a||s.loc,this[s.opcode].apply(this,s.args)
if(this.source.currentLocation=a,this.pushSource(""),this.stackSlot||this.inlineStack.length||this.compileStack.length)throw new o.default("Compile completed with content left on stack")
this.decorators.isEmpty()?this.decorators=void 0:(this.useDecorators=!0,this.decorators.prepend(["var decorators = container.decorators, ",this.lookupPropertyFunctionVarDeclaration(),";\n"]),this.decorators.push("return fn;"),n?this.decorators=Function.apply(this,["fn","props","container","depth0","data","blockParams","depths",this.decorators.merge()]):(this.decorators.prepend("function(fn, props, container, depth0, data, blockParams, depths) {\n"),this.decorators.push("}\n"),this.decorators=this.decorators.merge()))
var u=this.createFunctionContext(n)
if(this.isChild)return u
var p={compiler:this.compilerInfo(),main:u}
this.decorators&&(p.main_d=this.decorators,p.useDecorators=!0)
var h=this.context,d=h.programs,f=h.decorators
for(l=0,c=d.length;l<c;l++)d[l]&&(p[l]=d[l],f[l]&&(p[l+"_d"]=f[l],p.useDecorators=!0))
return this.environment.usePartial&&(p.usePartial=!0),this.options.data&&(p.useData=!0),this.useDepths&&(p.useDepths=!0),this.useBlockParams&&(p.useBlockParams=!0),this.options.compat&&(p.compat=!0),n?p.compilerOptions=this.options:(p.compiler=JSON.stringify(p.compiler),this.source.currentLocation={start:{line:1,column:0}},p=this.objectLiteral(p),t.srcName?(p=p.toStringWithSourceMap({file:t.destName})).map=p.map&&p.map.toString():p=p.toString()),p},preamble:function(){this.lastContext=0,this.source=new a.default(this.options.srcName),this.decorators=new a.default(this.options.srcName)},createFunctionContext:function(e){var t=this,r="",n=this.stackVars.concat(this.registers.list)
n.length>0&&(r+=", "+n.join(", "))
var i=0
Object.keys(this.aliases).forEach((function(e){var n=t.aliases[e]
n.children&&n.referenceCount>1&&(r+=", alias"+ ++i+"="+e,n.children[0]="alias"+i)})),this.lookupPropertyFunctionIsUsed&&(r+=", "+this.lookupPropertyFunctionVarDeclaration())
var o=["container","depth0","helpers","partials","data"];(this.useBlockParams||this.useDepths)&&o.push("blockParams"),this.useDepths&&o.push("depths")
var s=this.mergeSource(r)
return e?(o.push(s),Function.apply(this,o)):this.source.wrap(["function(",o.join(","),") {\n  ",s,"}"])},mergeSource:function(e){var t=this.environment.isSimple,r=!this.forceBuffer,n=void 0,i=void 0,o=void 0,s=void 0
return this.source.each((function(e){e.appendToBuffer?(o?e.prepend("  + "):o=e,s=e):(o&&(i?o.prepend("buffer += "):n=!0,s.add(";"),o=s=void 0),i=!0,t||(r=!1))})),r?o?(o.prepend("return "),s.add(";")):i||this.source.push('return "";'):(e+=", buffer = "+(n?"":this.initializeBuffer()),o?(o.prepend("return buffer + "),s.add(";")):this.source.push("return buffer;")),e&&this.source.prepend("var "+e.substring(2)+(n?"":";\n")),this.source.merge()},lookupPropertyFunctionVarDeclaration:function(){return"\n      lookupProperty = container.lookupProperty || function(parent, propertyName) {\n        if (Object.prototype.hasOwnProperty.call(parent, propertyName)) {\n          return parent[propertyName];\n        }\n        return undefined\n    }\n    ".trim()},blockValue:function(e){var t=this.aliasable("container.hooks.blockHelperMissing"),r=[this.contextName(0)]
this.setupHelperArgs(e,0,r)
var n=this.popStack()
r.splice(1,0,n),this.push(this.source.functionCall(t,"call",r))},ambiguousBlockValue:function(){var e=this.aliasable("container.hooks.blockHelperMissing"),t=[this.contextName(0)]
this.setupHelperArgs("",0,t,!0),this.flushInline()
var r=this.topStack()
t.splice(1,0,r),this.pushSource(["if (!",this.lastHelper,") { ",r," = ",this.source.functionCall(e,"call",t),"}"])},appendContent:function(e){this.pendingContent?e=this.pendingContent+e:this.pendingLocation=this.source.currentLocation,this.pendingContent=e},append:function(){if(this.isInline())this.replaceStack((function(e){return[" != null ? ",e,' : ""']})),this.pushSource(this.appendToBuffer(this.popStack()))
else{var e=this.popStack()
this.pushSource(["if (",e," != null) { ",this.appendToBuffer(e,void 0,!0)," }"]),this.environment.isSimple&&this.pushSource(["else { ",this.appendToBuffer("''",void 0,!0)," }"])}},appendEscaped:function(){this.pushSource(this.appendToBuffer([this.aliasable("container.escapeExpression"),"(",this.popStack(),")"]))},getContext:function(e){this.lastContext=e},pushContext:function(){this.pushStackLiteral(this.contextName(this.lastContext))},lookupOnContext:function(e,t,r,n){var i=0
n||!this.options.compat||this.lastContext?this.pushContext():this.push(this.depthedLookup(e[i++])),this.resolvePath("context",e,i,t,r)},lookupBlockParam:function(e,t){this.useBlockParams=!0,this.push(["blockParams[",e[0],"][",e[1],"]"]),this.resolvePath("context",t,1)},lookupData:function(e,t,r){e?this.pushStackLiteral("container.data(data, "+e+")"):this.pushStackLiteral("data"),this.resolvePath("data",t,0,!0,r)},resolvePath:function(e,t,r,n,i){var o=this
if(this.options.strict||this.options.assumeObjects)this.push(function(e,t,r,n){var i=t.popStack(),o=0,s=r.length
for(e&&s--;o<s;o++)i=t.nameLookup(i,r[o],n)
return e?[t.aliasable("container.strict"),"(",i,", ",t.quotedString(r[o]),", ",JSON.stringify(t.source.currentLocation)," )"]:i}(this.options.strict&&i,this,t,e))
else for(var s=t.length;r<s;r++)this.replaceStack((function(i){var s=o.nameLookup(i,t[r],e)
return n?[" && ",s]:[" != null ? ",s," : ",i]}))},resolvePossibleLambda:function(){this.push([this.aliasable("container.lambda"),"(",this.popStack(),", ",this.contextName(0),")"])},pushStringParam:function(e,t){this.pushContext(),this.pushString(t),"SubExpression"!==t&&("string"==typeof e?this.pushString(e):this.pushStackLiteral(e))},emptyHash:function(e){this.trackIds&&this.push("{}"),this.stringParams&&(this.push("{}"),this.push("{}")),this.pushStackLiteral(e?"undefined":"{}")},pushHash:function(){this.hash&&this.hashes.push(this.hash),this.hash={values:{},types:[],contexts:[],ids:[]}},popHash:function(){var e=this.hash
this.hash=this.hashes.pop(),this.trackIds&&this.push(this.objectLiteral(e.ids)),this.stringParams&&(this.push(this.objectLiteral(e.contexts)),this.push(this.objectLiteral(e.types))),this.push(this.objectLiteral(e.values))},pushString:function(e){this.pushStackLiteral(this.quotedString(e))},pushLiteral:function(e){this.pushStackLiteral(e)},pushProgram:function(e){null!=e?this.pushStackLiteral(this.programExpression(e)):this.pushStackLiteral(null)},registerDecorator:function(e,t){var r=this.nameLookup("decorators",t,"decorator"),n=this.setupHelperArgs(t,e)
this.decorators.push(["fn = ",this.decorators.functionCall(r,"",["fn","props","container",n])," || fn;"])},invokeHelper:function(e,t,r){var n=this.popStack(),i=this.setupHelper(e,t),o=[]
r&&o.push(i.name),o.push(n),this.options.strict||o.push(this.aliasable("container.hooks.helperMissing"))
var s=["(",this.itemsSeparatedBy(o,"||"),")"],a=this.source.functionCall(s,"call",i.callParams)
this.push(a)},itemsSeparatedBy:function(e,t){var r=[]
r.push(e[0])
for(var n=1;n<e.length;n++)r.push(t,e[n])
return r},invokeKnownHelper:function(e,t){var r=this.setupHelper(e,t)
this.push(this.source.functionCall(r.name,"call",r.callParams))},invokeAmbiguous:function(e,t){this.useRegister("helper")
var r=this.popStack()
this.emptyHash()
var n=this.setupHelper(0,e,t),i=["(","(helper = ",this.lastHelper=this.nameLookup("helpers",e,"helper")," || ",r,")"]
this.options.strict||(i[0]="(helper = ",i.push(" != null ? helper : ",this.aliasable("container.hooks.helperMissing"))),this.push(["(",i,n.paramsInit?["),(",n.paramsInit]:[],"),","(typeof helper === ",this.aliasable('"function"')," ? ",this.source.functionCall("helper","call",n.callParams)," : helper))"])},invokePartial:function(e,t,r){var n=[],i=this.setupParams(t,1,n)
e&&(t=this.popStack(),delete i.name),r&&(i.indent=JSON.stringify(r)),i.helpers="helpers",i.partials="partials",i.decorators="container.decorators",e?n.unshift(t):n.unshift(this.nameLookup("partials",t,"partial")),this.options.compat&&(i.depths="depths"),i=this.objectLiteral(i),n.push(i),this.push(this.source.functionCall("container.invokePartial","",n))},assignToHash:function(e){var t=this.popStack(),r=void 0,n=void 0,i=void 0
this.trackIds&&(i=this.popStack()),this.stringParams&&(n=this.popStack(),r=this.popStack())
var o=this.hash
r&&(o.contexts[e]=r),n&&(o.types[e]=n),i&&(o.ids[e]=i),o.values[e]=t},pushId:function(e,t,r){"BlockParam"===e?this.pushStackLiteral("blockParams["+t[0]+"].path["+t[1]+"]"+(r?" + "+JSON.stringify("."+r):"")):"PathExpression"===e?this.pushString(t):"SubExpression"===e?this.pushStackLiteral("true"):this.pushStackLiteral("null")},compiler:c,compileChildren:function(e,t){for(var r=e.children,n=void 0,i=void 0,o=0,s=r.length;o<s;o++){n=r[o],i=new this.compiler
var a=this.matchExistingProgram(n)
if(null==a){this.context.programs.push("")
var l=this.context.programs.length
n.index=l,n.name="program"+l,this.context.programs[l]=i.compile(n,t,this.context,!this.precompile),this.context.decorators[l]=i.decorators,this.context.environments[l]=n,this.useDepths=this.useDepths||i.useDepths,this.useBlockParams=this.useBlockParams||i.useBlockParams,n.useDepths=this.useDepths,n.useBlockParams=this.useBlockParams}else n.index=a.index,n.name="program"+a.index,this.useDepths=this.useDepths||a.useDepths,this.useBlockParams=this.useBlockParams||a.useBlockParams}},matchExistingProgram:function(e){for(var t=0,r=this.context.environments.length;t<r;t++){var n=this.context.environments[t]
if(n&&n.equals(e))return n}},programExpression:function(e){var t=this.environment.children[e],r=[t.index,"data",t.blockParams]
return(this.useBlockParams||this.useDepths)&&r.push("blockParams"),this.useDepths&&r.push("depths"),"container.program("+r.join(", ")+")"},useRegister:function(e){this.registers[e]||(this.registers[e]=!0,this.registers.list.push(e))},push:function(e){return e instanceof l||(e=this.source.wrap(e)),this.inlineStack.push(e),e},pushStackLiteral:function(e){this.push(new l(e))},pushSource:function(e){this.pendingContent&&(this.source.push(this.appendToBuffer(this.source.quotedString(this.pendingContent),this.pendingLocation)),this.pendingContent=void 0),e&&this.source.push(e)},replaceStack:function(e){var t=["("],r=void 0,n=void 0,i=void 0
if(!this.isInline())throw new o.default("replaceStack on non-inline")
var s=this.popStack(!0)
if(s instanceof l)t=["(",r=[s.value]],i=!0
else{n=!0
var a=this.incrStack()
t=["((",this.push(a)," = ",s,")"],r=this.topStack()}var c=e.call(this,r)
i||this.popStack(),n&&this.stackSlot--,this.push(t.concat(c,")"))},incrStack:function(){return this.stackSlot++,this.stackSlot>this.stackVars.length&&this.stackVars.push("stack"+this.stackSlot),this.topStackName()},topStackName:function(){return"stack"+this.stackSlot},flushInline:function(){var e=this.inlineStack
this.inlineStack=[]
for(var t=0,r=e.length;t<r;t++){var n=e[t]
if(n instanceof l)this.compileStack.push(n)
else{var i=this.incrStack()
this.pushSource([i," = ",n,";"]),this.compileStack.push(i)}}},isInline:function(){return this.inlineStack.length},popStack:function(e){var t=this.isInline(),r=(t?this.inlineStack:this.compileStack).pop()
if(!e&&r instanceof l)return r.value
if(!t){if(!this.stackSlot)throw new o.default("Invalid stack pop")
this.stackSlot--}return r},topStack:function(){var e=this.isInline()?this.inlineStack:this.compileStack,t=e[e.length-1]
return t instanceof l?t.value:t},contextName:function(e){return this.useDepths&&e?"depths["+e+"]":"depth"+e},quotedString:function(e){return this.source.quotedString(e)},objectLiteral:function(e){return this.source.objectLiteral(e)},aliasable:function(e){var t=this.aliases[e]
return t?(t.referenceCount++,t):((t=this.aliases[e]=this.source.wrap(e)).aliasable=!0,t.referenceCount=1,t)},setupHelper:function(e,t,r){var n=[]
return{params:n,paramsInit:this.setupHelperArgs(t,e,n,r),name:this.nameLookup("helpers",t,"helper"),callParams:[this.aliasable(this.contextName(0)+" != null ? "+this.contextName(0)+" : (container.nullContext || {})")].concat(n)}},setupParams:function(e,t,r){var n={},i=[],o=[],s=[],a=!r,l=void 0
a&&(r=[]),n.name=this.quotedString(e),n.hash=this.popStack(),this.trackIds&&(n.hashIds=this.popStack()),this.stringParams&&(n.hashTypes=this.popStack(),n.hashContexts=this.popStack())
var c=this.popStack(),u=this.popStack();(u||c)&&(n.fn=u||"container.noop",n.inverse=c||"container.noop")
for(var p=t;p--;)l=this.popStack(),r[p]=l,this.trackIds&&(s[p]=this.popStack()),this.stringParams&&(o[p]=this.popStack(),i[p]=this.popStack())
return a&&(n.args=this.source.generateArray(r)),this.trackIds&&(n.ids=this.source.generateArray(s)),this.stringParams&&(n.types=this.source.generateArray(o),n.contexts=this.source.generateArray(i)),this.options.data&&(n.data="data"),this.useBlockParams&&(n.blockParams="blockParams"),n},setupHelperArgs:function(e,t,r,n){var i=this.setupParams(e,t,r)
return i.loc=JSON.stringify(this.source.currentLocation),i=this.objectLiteral(i),n?(this.useRegister("options"),r.push("options"),["options=",i]):r?(r.push(i),""):i}},function(){for(var e="break else new var case finally return void catch for switch while continue function this with default if throw delete in try do instanceof typeof abstract enum int short boolean export interface static byte extends long super char final native synchronized class float package throws const goto private transient debugger implements protected volatile double import public let yield await null true false".split(" "),t=c.RESERVED_WORDS={},r=0,n=e.length;r<n;r++)t[e[r]]=!0}(),c.isValidJavaScriptVariableName=function(e){return!c.RESERVED_WORDS[e]&&/^[a-zA-Z_$][0-9a-zA-Z_$]*$/.test(e)},t.default=c,e.exports=t.default},6398:(e,t)=>{"use strict"
t.__esModule=!0
var r=function(){var e={trace:function(){},yy:{},symbols_:{error:2,root:3,program:4,EOF:5,program_repetition0:6,statement:7,mustache:8,block:9,rawBlock:10,partial:11,partialBlock:12,content:13,COMMENT:14,CONTENT:15,openRawBlock:16,rawBlock_repetition0:17,END_RAW_BLOCK:18,OPEN_RAW_BLOCK:19,helperName:20,openRawBlock_repetition0:21,openRawBlock_option0:22,CLOSE_RAW_BLOCK:23,openBlock:24,block_option0:25,closeBlock:26,openInverse:27,block_option1:28,OPEN_BLOCK:29,openBlock_repetition0:30,openBlock_option0:31,openBlock_option1:32,CLOSE:33,OPEN_INVERSE:34,openInverse_repetition0:35,openInverse_option0:36,openInverse_option1:37,openInverseChain:38,OPEN_INVERSE_CHAIN:39,openInverseChain_repetition0:40,openInverseChain_option0:41,openInverseChain_option1:42,inverseAndProgram:43,INVERSE:44,inverseChain:45,inverseChain_option0:46,OPEN_ENDBLOCK:47,OPEN:48,mustache_repetition0:49,mustache_option0:50,OPEN_UNESCAPED:51,mustache_repetition1:52,mustache_option1:53,CLOSE_UNESCAPED:54,OPEN_PARTIAL:55,partialName:56,partial_repetition0:57,partial_option0:58,openPartialBlock:59,OPEN_PARTIAL_BLOCK:60,openPartialBlock_repetition0:61,openPartialBlock_option0:62,param:63,sexpr:64,OPEN_SEXPR:65,sexpr_repetition0:66,sexpr_option0:67,CLOSE_SEXPR:68,hash:69,hash_repetition_plus0:70,hashSegment:71,ID:72,EQUALS:73,blockParams:74,OPEN_BLOCK_PARAMS:75,blockParams_repetition_plus0:76,CLOSE_BLOCK_PARAMS:77,path:78,dataName:79,STRING:80,NUMBER:81,BOOLEAN:82,UNDEFINED:83,NULL:84,DATA:85,pathSegments:86,SEP:87,$accept:0,$end:1},terminals_:{2:"error",5:"EOF",14:"COMMENT",15:"CONTENT",18:"END_RAW_BLOCK",19:"OPEN_RAW_BLOCK",23:"CLOSE_RAW_BLOCK",29:"OPEN_BLOCK",33:"CLOSE",34:"OPEN_INVERSE",39:"OPEN_INVERSE_CHAIN",44:"INVERSE",47:"OPEN_ENDBLOCK",48:"OPEN",51:"OPEN_UNESCAPED",54:"CLOSE_UNESCAPED",55:"OPEN_PARTIAL",60:"OPEN_PARTIAL_BLOCK",65:"OPEN_SEXPR",68:"CLOSE_SEXPR",72:"ID",73:"EQUALS",75:"OPEN_BLOCK_PARAMS",77:"CLOSE_BLOCK_PARAMS",80:"STRING",81:"NUMBER",82:"BOOLEAN",83:"UNDEFINED",84:"NULL",85:"DATA",87:"SEP"},productions_:[0,[3,2],[4,1],[7,1],[7,1],[7,1],[7,1],[7,1],[7,1],[7,1],[13,1],[10,3],[16,5],[9,4],[9,4],[24,6],[27,6],[38,6],[43,2],[45,3],[45,1],[26,3],[8,5],[8,5],[11,5],[12,3],[59,5],[63,1],[63,1],[64,5],[69,1],[71,3],[74,3],[20,1],[20,1],[20,1],[20,1],[20,1],[20,1],[20,1],[56,1],[56,1],[79,2],[78,1],[86,3],[86,1],[6,0],[6,2],[17,0],[17,2],[21,0],[21,2],[22,0],[22,1],[25,0],[25,1],[28,0],[28,1],[30,0],[30,2],[31,0],[31,1],[32,0],[32,1],[35,0],[35,2],[36,0],[36,1],[37,0],[37,1],[40,0],[40,2],[41,0],[41,1],[42,0],[42,1],[46,0],[46,1],[49,0],[49,2],[50,0],[50,1],[52,0],[52,2],[53,0],[53,1],[57,0],[57,2],[58,0],[58,1],[61,0],[61,2],[62,0],[62,1],[66,0],[66,2],[67,0],[67,1],[70,1],[70,2],[76,1],[76,2]],performAction:function(e,t,r,n,i,o,s){var a=o.length-1
switch(i){case 1:return o[a-1]
case 2:this.$=n.prepareProgram(o[a])
break
case 3:case 4:case 5:case 6:case 7:case 8:case 20:case 27:case 28:case 33:case 34:case 40:case 41:this.$=o[a]
break
case 9:this.$={type:"CommentStatement",value:n.stripComment(o[a]),strip:n.stripFlags(o[a],o[a]),loc:n.locInfo(this._$)}
break
case 10:this.$={type:"ContentStatement",original:o[a],value:o[a],loc:n.locInfo(this._$)}
break
case 11:this.$=n.prepareRawBlock(o[a-2],o[a-1],o[a],this._$)
break
case 12:this.$={path:o[a-3],params:o[a-2],hash:o[a-1]}
break
case 13:this.$=n.prepareBlock(o[a-3],o[a-2],o[a-1],o[a],!1,this._$)
break
case 14:this.$=n.prepareBlock(o[a-3],o[a-2],o[a-1],o[a],!0,this._$)
break
case 15:this.$={open:o[a-5],path:o[a-4],params:o[a-3],hash:o[a-2],blockParams:o[a-1],strip:n.stripFlags(o[a-5],o[a])}
break
case 16:case 17:this.$={path:o[a-4],params:o[a-3],hash:o[a-2],blockParams:o[a-1],strip:n.stripFlags(o[a-5],o[a])}
break
case 18:this.$={strip:n.stripFlags(o[a-1],o[a-1]),program:o[a]}
break
case 19:var l=n.prepareBlock(o[a-2],o[a-1],o[a],o[a],!1,this._$),c=n.prepareProgram([l],o[a-1].loc)
c.chained=!0,this.$={strip:o[a-2].strip,program:c,chain:!0}
break
case 21:this.$={path:o[a-1],strip:n.stripFlags(o[a-2],o[a])}
break
case 22:case 23:this.$=n.prepareMustache(o[a-3],o[a-2],o[a-1],o[a-4],n.stripFlags(o[a-4],o[a]),this._$)
break
case 24:this.$={type:"PartialStatement",name:o[a-3],params:o[a-2],hash:o[a-1],indent:"",strip:n.stripFlags(o[a-4],o[a]),loc:n.locInfo(this._$)}
break
case 25:this.$=n.preparePartialBlock(o[a-2],o[a-1],o[a],this._$)
break
case 26:this.$={path:o[a-3],params:o[a-2],hash:o[a-1],strip:n.stripFlags(o[a-4],o[a])}
break
case 29:this.$={type:"SubExpression",path:o[a-3],params:o[a-2],hash:o[a-1],loc:n.locInfo(this._$)}
break
case 30:this.$={type:"Hash",pairs:o[a],loc:n.locInfo(this._$)}
break
case 31:this.$={type:"HashPair",key:n.id(o[a-2]),value:o[a],loc:n.locInfo(this._$)}
break
case 32:this.$=n.id(o[a-1])
break
case 35:this.$={type:"StringLiteral",value:o[a],original:o[a],loc:n.locInfo(this._$)}
break
case 36:this.$={type:"NumberLiteral",value:Number(o[a]),original:Number(o[a]),loc:n.locInfo(this._$)}
break
case 37:this.$={type:"BooleanLiteral",value:"true"===o[a],original:"true"===o[a],loc:n.locInfo(this._$)}
break
case 38:this.$={type:"UndefinedLiteral",original:void 0,value:void 0,loc:n.locInfo(this._$)}
break
case 39:this.$={type:"NullLiteral",original:null,value:null,loc:n.locInfo(this._$)}
break
case 42:this.$=n.preparePath(!0,o[a],this._$)
break
case 43:this.$=n.preparePath(!1,o[a],this._$)
break
case 44:o[a-2].push({part:n.id(o[a]),original:o[a],separator:o[a-1]}),this.$=o[a-2]
break
case 45:this.$=[{part:n.id(o[a]),original:o[a]}]
break
case 46:case 48:case 50:case 58:case 64:case 70:case 78:case 82:case 86:case 90:case 94:this.$=[]
break
case 47:case 49:case 51:case 59:case 65:case 71:case 79:case 83:case 87:case 91:case 95:case 99:case 101:o[a-1].push(o[a])
break
case 98:case 100:this.$=[o[a]]}},table:[{3:1,4:2,5:[2,46],6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{1:[3]},{5:[1,4]},{5:[2,2],7:5,8:6,9:7,10:8,11:9,12:10,13:11,14:[1,12],15:[1,20],16:17,19:[1,23],24:15,27:16,29:[1,21],34:[1,22],39:[2,2],44:[2,2],47:[2,2],48:[1,13],51:[1,14],55:[1,18],59:19,60:[1,24]},{1:[2,1]},{5:[2,47],14:[2,47],15:[2,47],19:[2,47],29:[2,47],34:[2,47],39:[2,47],44:[2,47],47:[2,47],48:[2,47],51:[2,47],55:[2,47],60:[2,47]},{5:[2,3],14:[2,3],15:[2,3],19:[2,3],29:[2,3],34:[2,3],39:[2,3],44:[2,3],47:[2,3],48:[2,3],51:[2,3],55:[2,3],60:[2,3]},{5:[2,4],14:[2,4],15:[2,4],19:[2,4],29:[2,4],34:[2,4],39:[2,4],44:[2,4],47:[2,4],48:[2,4],51:[2,4],55:[2,4],60:[2,4]},{5:[2,5],14:[2,5],15:[2,5],19:[2,5],29:[2,5],34:[2,5],39:[2,5],44:[2,5],47:[2,5],48:[2,5],51:[2,5],55:[2,5],60:[2,5]},{5:[2,6],14:[2,6],15:[2,6],19:[2,6],29:[2,6],34:[2,6],39:[2,6],44:[2,6],47:[2,6],48:[2,6],51:[2,6],55:[2,6],60:[2,6]},{5:[2,7],14:[2,7],15:[2,7],19:[2,7],29:[2,7],34:[2,7],39:[2,7],44:[2,7],47:[2,7],48:[2,7],51:[2,7],55:[2,7],60:[2,7]},{5:[2,8],14:[2,8],15:[2,8],19:[2,8],29:[2,8],34:[2,8],39:[2,8],44:[2,8],47:[2,8],48:[2,8],51:[2,8],55:[2,8],60:[2,8]},{5:[2,9],14:[2,9],15:[2,9],19:[2,9],29:[2,9],34:[2,9],39:[2,9],44:[2,9],47:[2,9],48:[2,9],51:[2,9],55:[2,9],60:[2,9]},{20:25,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:36,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{4:37,6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],39:[2,46],44:[2,46],47:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{4:38,6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],44:[2,46],47:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{15:[2,48],17:39,18:[2,48]},{20:41,56:40,64:42,65:[1,43],72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{4:44,6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],47:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{5:[2,10],14:[2,10],15:[2,10],18:[2,10],19:[2,10],29:[2,10],34:[2,10],39:[2,10],44:[2,10],47:[2,10],48:[2,10],51:[2,10],55:[2,10],60:[2,10]},{20:45,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:46,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:47,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:41,56:48,64:42,65:[1,43],72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{33:[2,78],49:49,65:[2,78],72:[2,78],80:[2,78],81:[2,78],82:[2,78],83:[2,78],84:[2,78],85:[2,78]},{23:[2,33],33:[2,33],54:[2,33],65:[2,33],68:[2,33],72:[2,33],75:[2,33],80:[2,33],81:[2,33],82:[2,33],83:[2,33],84:[2,33],85:[2,33]},{23:[2,34],33:[2,34],54:[2,34],65:[2,34],68:[2,34],72:[2,34],75:[2,34],80:[2,34],81:[2,34],82:[2,34],83:[2,34],84:[2,34],85:[2,34]},{23:[2,35],33:[2,35],54:[2,35],65:[2,35],68:[2,35],72:[2,35],75:[2,35],80:[2,35],81:[2,35],82:[2,35],83:[2,35],84:[2,35],85:[2,35]},{23:[2,36],33:[2,36],54:[2,36],65:[2,36],68:[2,36],72:[2,36],75:[2,36],80:[2,36],81:[2,36],82:[2,36],83:[2,36],84:[2,36],85:[2,36]},{23:[2,37],33:[2,37],54:[2,37],65:[2,37],68:[2,37],72:[2,37],75:[2,37],80:[2,37],81:[2,37],82:[2,37],83:[2,37],84:[2,37],85:[2,37]},{23:[2,38],33:[2,38],54:[2,38],65:[2,38],68:[2,38],72:[2,38],75:[2,38],80:[2,38],81:[2,38],82:[2,38],83:[2,38],84:[2,38],85:[2,38]},{23:[2,39],33:[2,39],54:[2,39],65:[2,39],68:[2,39],72:[2,39],75:[2,39],80:[2,39],81:[2,39],82:[2,39],83:[2,39],84:[2,39],85:[2,39]},{23:[2,43],33:[2,43],54:[2,43],65:[2,43],68:[2,43],72:[2,43],75:[2,43],80:[2,43],81:[2,43],82:[2,43],83:[2,43],84:[2,43],85:[2,43],87:[1,50]},{72:[1,35],86:51},{23:[2,45],33:[2,45],54:[2,45],65:[2,45],68:[2,45],72:[2,45],75:[2,45],80:[2,45],81:[2,45],82:[2,45],83:[2,45],84:[2,45],85:[2,45],87:[2,45]},{52:52,54:[2,82],65:[2,82],72:[2,82],80:[2,82],81:[2,82],82:[2,82],83:[2,82],84:[2,82],85:[2,82]},{25:53,38:55,39:[1,57],43:56,44:[1,58],45:54,47:[2,54]},{28:59,43:60,44:[1,58],47:[2,56]},{13:62,15:[1,20],18:[1,61]},{33:[2,86],57:63,65:[2,86],72:[2,86],80:[2,86],81:[2,86],82:[2,86],83:[2,86],84:[2,86],85:[2,86]},{33:[2,40],65:[2,40],72:[2,40],80:[2,40],81:[2,40],82:[2,40],83:[2,40],84:[2,40],85:[2,40]},{33:[2,41],65:[2,41],72:[2,41],80:[2,41],81:[2,41],82:[2,41],83:[2,41],84:[2,41],85:[2,41]},{20:64,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{26:65,47:[1,66]},{30:67,33:[2,58],65:[2,58],72:[2,58],75:[2,58],80:[2,58],81:[2,58],82:[2,58],83:[2,58],84:[2,58],85:[2,58]},{33:[2,64],35:68,65:[2,64],72:[2,64],75:[2,64],80:[2,64],81:[2,64],82:[2,64],83:[2,64],84:[2,64],85:[2,64]},{21:69,23:[2,50],65:[2,50],72:[2,50],80:[2,50],81:[2,50],82:[2,50],83:[2,50],84:[2,50],85:[2,50]},{33:[2,90],61:70,65:[2,90],72:[2,90],80:[2,90],81:[2,90],82:[2,90],83:[2,90],84:[2,90],85:[2,90]},{20:74,33:[2,80],50:71,63:72,64:75,65:[1,43],69:73,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{72:[1,79]},{23:[2,42],33:[2,42],54:[2,42],65:[2,42],68:[2,42],72:[2,42],75:[2,42],80:[2,42],81:[2,42],82:[2,42],83:[2,42],84:[2,42],85:[2,42],87:[1,50]},{20:74,53:80,54:[2,84],63:81,64:75,65:[1,43],69:82,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{26:83,47:[1,66]},{47:[2,55]},{4:84,6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],39:[2,46],44:[2,46],47:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{47:[2,20]},{20:85,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{4:86,6:3,14:[2,46],15:[2,46],19:[2,46],29:[2,46],34:[2,46],47:[2,46],48:[2,46],51:[2,46],55:[2,46],60:[2,46]},{26:87,47:[1,66]},{47:[2,57]},{5:[2,11],14:[2,11],15:[2,11],19:[2,11],29:[2,11],34:[2,11],39:[2,11],44:[2,11],47:[2,11],48:[2,11],51:[2,11],55:[2,11],60:[2,11]},{15:[2,49],18:[2,49]},{20:74,33:[2,88],58:88,63:89,64:75,65:[1,43],69:90,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{65:[2,94],66:91,68:[2,94],72:[2,94],80:[2,94],81:[2,94],82:[2,94],83:[2,94],84:[2,94],85:[2,94]},{5:[2,25],14:[2,25],15:[2,25],19:[2,25],29:[2,25],34:[2,25],39:[2,25],44:[2,25],47:[2,25],48:[2,25],51:[2,25],55:[2,25],60:[2,25]},{20:92,72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:74,31:93,33:[2,60],63:94,64:75,65:[1,43],69:95,70:76,71:77,72:[1,78],75:[2,60],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:74,33:[2,66],36:96,63:97,64:75,65:[1,43],69:98,70:76,71:77,72:[1,78],75:[2,66],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:74,22:99,23:[2,52],63:100,64:75,65:[1,43],69:101,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{20:74,33:[2,92],62:102,63:103,64:75,65:[1,43],69:104,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{33:[1,105]},{33:[2,79],65:[2,79],72:[2,79],80:[2,79],81:[2,79],82:[2,79],83:[2,79],84:[2,79],85:[2,79]},{33:[2,81]},{23:[2,27],33:[2,27],54:[2,27],65:[2,27],68:[2,27],72:[2,27],75:[2,27],80:[2,27],81:[2,27],82:[2,27],83:[2,27],84:[2,27],85:[2,27]},{23:[2,28],33:[2,28],54:[2,28],65:[2,28],68:[2,28],72:[2,28],75:[2,28],80:[2,28],81:[2,28],82:[2,28],83:[2,28],84:[2,28],85:[2,28]},{23:[2,30],33:[2,30],54:[2,30],68:[2,30],71:106,72:[1,107],75:[2,30]},{23:[2,98],33:[2,98],54:[2,98],68:[2,98],72:[2,98],75:[2,98]},{23:[2,45],33:[2,45],54:[2,45],65:[2,45],68:[2,45],72:[2,45],73:[1,108],75:[2,45],80:[2,45],81:[2,45],82:[2,45],83:[2,45],84:[2,45],85:[2,45],87:[2,45]},{23:[2,44],33:[2,44],54:[2,44],65:[2,44],68:[2,44],72:[2,44],75:[2,44],80:[2,44],81:[2,44],82:[2,44],83:[2,44],84:[2,44],85:[2,44],87:[2,44]},{54:[1,109]},{54:[2,83],65:[2,83],72:[2,83],80:[2,83],81:[2,83],82:[2,83],83:[2,83],84:[2,83],85:[2,83]},{54:[2,85]},{5:[2,13],14:[2,13],15:[2,13],19:[2,13],29:[2,13],34:[2,13],39:[2,13],44:[2,13],47:[2,13],48:[2,13],51:[2,13],55:[2,13],60:[2,13]},{38:55,39:[1,57],43:56,44:[1,58],45:111,46:110,47:[2,76]},{33:[2,70],40:112,65:[2,70],72:[2,70],75:[2,70],80:[2,70],81:[2,70],82:[2,70],83:[2,70],84:[2,70],85:[2,70]},{47:[2,18]},{5:[2,14],14:[2,14],15:[2,14],19:[2,14],29:[2,14],34:[2,14],39:[2,14],44:[2,14],47:[2,14],48:[2,14],51:[2,14],55:[2,14],60:[2,14]},{33:[1,113]},{33:[2,87],65:[2,87],72:[2,87],80:[2,87],81:[2,87],82:[2,87],83:[2,87],84:[2,87],85:[2,87]},{33:[2,89]},{20:74,63:115,64:75,65:[1,43],67:114,68:[2,96],69:116,70:76,71:77,72:[1,78],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{33:[1,117]},{32:118,33:[2,62],74:119,75:[1,120]},{33:[2,59],65:[2,59],72:[2,59],75:[2,59],80:[2,59],81:[2,59],82:[2,59],83:[2,59],84:[2,59],85:[2,59]},{33:[2,61],75:[2,61]},{33:[2,68],37:121,74:122,75:[1,120]},{33:[2,65],65:[2,65],72:[2,65],75:[2,65],80:[2,65],81:[2,65],82:[2,65],83:[2,65],84:[2,65],85:[2,65]},{33:[2,67],75:[2,67]},{23:[1,123]},{23:[2,51],65:[2,51],72:[2,51],80:[2,51],81:[2,51],82:[2,51],83:[2,51],84:[2,51],85:[2,51]},{23:[2,53]},{33:[1,124]},{33:[2,91],65:[2,91],72:[2,91],80:[2,91],81:[2,91],82:[2,91],83:[2,91],84:[2,91],85:[2,91]},{33:[2,93]},{5:[2,22],14:[2,22],15:[2,22],19:[2,22],29:[2,22],34:[2,22],39:[2,22],44:[2,22],47:[2,22],48:[2,22],51:[2,22],55:[2,22],60:[2,22]},{23:[2,99],33:[2,99],54:[2,99],68:[2,99],72:[2,99],75:[2,99]},{73:[1,108]},{20:74,63:125,64:75,65:[1,43],72:[1,35],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{5:[2,23],14:[2,23],15:[2,23],19:[2,23],29:[2,23],34:[2,23],39:[2,23],44:[2,23],47:[2,23],48:[2,23],51:[2,23],55:[2,23],60:[2,23]},{47:[2,19]},{47:[2,77]},{20:74,33:[2,72],41:126,63:127,64:75,65:[1,43],69:128,70:76,71:77,72:[1,78],75:[2,72],78:26,79:27,80:[1,28],81:[1,29],82:[1,30],83:[1,31],84:[1,32],85:[1,34],86:33},{5:[2,24],14:[2,24],15:[2,24],19:[2,24],29:[2,24],34:[2,24],39:[2,24],44:[2,24],47:[2,24],48:[2,24],51:[2,24],55:[2,24],60:[2,24]},{68:[1,129]},{65:[2,95],68:[2,95],72:[2,95],80:[2,95],81:[2,95],82:[2,95],83:[2,95],84:[2,95],85:[2,95]},{68:[2,97]},{5:[2,21],14:[2,21],15:[2,21],19:[2,21],29:[2,21],34:[2,21],39:[2,21],44:[2,21],47:[2,21],48:[2,21],51:[2,21],55:[2,21],60:[2,21]},{33:[1,130]},{33:[2,63]},{72:[1,132],76:131},{33:[1,133]},{33:[2,69]},{15:[2,12],18:[2,12]},{14:[2,26],15:[2,26],19:[2,26],29:[2,26],34:[2,26],47:[2,26],48:[2,26],51:[2,26],55:[2,26],60:[2,26]},{23:[2,31],33:[2,31],54:[2,31],68:[2,31],72:[2,31],75:[2,31]},{33:[2,74],42:134,74:135,75:[1,120]},{33:[2,71],65:[2,71],72:[2,71],75:[2,71],80:[2,71],81:[2,71],82:[2,71],83:[2,71],84:[2,71],85:[2,71]},{33:[2,73],75:[2,73]},{23:[2,29],33:[2,29],54:[2,29],65:[2,29],68:[2,29],72:[2,29],75:[2,29],80:[2,29],81:[2,29],82:[2,29],83:[2,29],84:[2,29],85:[2,29]},{14:[2,15],15:[2,15],19:[2,15],29:[2,15],34:[2,15],39:[2,15],44:[2,15],47:[2,15],48:[2,15],51:[2,15],55:[2,15],60:[2,15]},{72:[1,137],77:[1,136]},{72:[2,100],77:[2,100]},{14:[2,16],15:[2,16],19:[2,16],29:[2,16],34:[2,16],44:[2,16],47:[2,16],48:[2,16],51:[2,16],55:[2,16],60:[2,16]},{33:[1,138]},{33:[2,75]},{33:[2,32]},{72:[2,101],77:[2,101]},{14:[2,17],15:[2,17],19:[2,17],29:[2,17],34:[2,17],39:[2,17],44:[2,17],47:[2,17],48:[2,17],51:[2,17],55:[2,17],60:[2,17]}],defaultActions:{4:[2,1],54:[2,55],56:[2,20],60:[2,57],73:[2,81],82:[2,85],86:[2,18],90:[2,89],101:[2,53],104:[2,93],110:[2,19],111:[2,77],116:[2,97],119:[2,63],122:[2,69],135:[2,75],136:[2,32]},parseError:function(e,t){throw new Error(e)},parse:function(e){var t=[0],r=[null],n=[],i=this.table,o="",s=0,a=0,l=0
this.lexer.setInput(e),this.lexer.yy=this.yy,this.yy.lexer=this.lexer,this.yy.parser=this,void 0===this.lexer.yylloc&&(this.lexer.yylloc={})
var c=this.lexer.yylloc
n.push(c)
var u=this.lexer.options&&this.lexer.options.ranges
"function"==typeof this.yy.parseError&&(this.parseError=this.yy.parseError)
for(var p,h,d,f,m,g,v,y,b,w,k={};;){if(d=t[t.length-1],this.defaultActions[d]?f=this.defaultActions[d]:(null==p&&(w=void 0,"number"!=typeof(w=this.lexer.lex()||1)&&(w=this.symbols_[w]||w),p=w),f=i[d]&&i[d][p]),void 0===f||!f.length||!f[0]){var _=""
if(!l){for(g in b=[],i[d])this.terminals_[g]&&g>2&&b.push("'"+this.terminals_[g]+"'")
_=this.lexer.showPosition?"Parse error on line "+(s+1)+":\n"+this.lexer.showPosition()+"\nExpecting "+b.join(", ")+", got '"+(this.terminals_[p]||p)+"'":"Parse error on line "+(s+1)+": Unexpected "+(1==p?"end of input":"'"+(this.terminals_[p]||p)+"'"),this.parseError(_,{text:this.lexer.match,token:this.terminals_[p]||p,line:this.lexer.yylineno,loc:c,expected:b})}}if(f[0]instanceof Array&&f.length>1)throw new Error("Parse Error: multiple actions possible at state: "+d+", token: "+p)
switch(f[0]){case 1:t.push(p),r.push(this.lexer.yytext),n.push(this.lexer.yylloc),t.push(f[1]),p=null,h?(p=h,h=null):(a=this.lexer.yyleng,o=this.lexer.yytext,s=this.lexer.yylineno,c=this.lexer.yylloc,l>0&&l--)
break
case 2:if(v=this.productions_[f[1]][1],k.$=r[r.length-v],k._$={first_line:n[n.length-(v||1)].first_line,last_line:n[n.length-1].last_line,first_column:n[n.length-(v||1)].first_column,last_column:n[n.length-1].last_column},u&&(k._$.range=[n[n.length-(v||1)].range[0],n[n.length-1].range[1]]),void 0!==(m=this.performAction.call(k,o,a,s,this.yy,f[1],r,n)))return m
v&&(t=t.slice(0,-1*v*2),r=r.slice(0,-1*v),n=n.slice(0,-1*v)),t.push(this.productions_[f[1]][0]),r.push(k.$),n.push(k._$),y=i[t[t.length-2]][t[t.length-1]],t.push(y)
break
case 3:return!0}}return!0}},t={EOF:1,parseError:function(e,t){if(!this.yy.parser)throw new Error(e)
this.yy.parser.parseError(e,t)},setInput:function(e){return this._input=e,this._more=this._less=this.done=!1,this.yylineno=this.yyleng=0,this.yytext=this.matched=this.match="",this.conditionStack=["INITIAL"],this.yylloc={first_line:1,first_column:0,last_line:1,last_column:0},this.options.ranges&&(this.yylloc.range=[0,0]),this.offset=0,this},input:function(){var e=this._input[0]
return this.yytext+=e,this.yyleng++,this.offset++,this.match+=e,this.matched+=e,e.match(/(?:\r\n?|\n).*/g)?(this.yylineno++,this.yylloc.last_line++):this.yylloc.last_column++,this.options.ranges&&this.yylloc.range[1]++,this._input=this._input.slice(1),e},unput:function(e){var t=e.length,r=e.split(/(?:\r\n?|\n)/g)
this._input=e+this._input,this.yytext=this.yytext.substr(0,this.yytext.length-t-1),this.offset-=t
var n=this.match.split(/(?:\r\n?|\n)/g)
this.match=this.match.substr(0,this.match.length-1),this.matched=this.matched.substr(0,this.matched.length-1),r.length-1&&(this.yylineno-=r.length-1)
var i=this.yylloc.range
return this.yylloc={first_line:this.yylloc.first_line,last_line:this.yylineno+1,first_column:this.yylloc.first_column,last_column:r?(r.length===n.length?this.yylloc.first_column:0)+n[n.length-r.length].length-r[0].length:this.yylloc.first_column-t},this.options.ranges&&(this.yylloc.range=[i[0],i[0]+this.yyleng-t]),this},more:function(){return this._more=!0,this},less:function(e){this.unput(this.match.slice(e))},pastInput:function(){var e=this.matched.substr(0,this.matched.length-this.match.length)
return(e.length>20?"...":"")+e.substr(-20).replace(/\n/g,"")},upcomingInput:function(){var e=this.match
return e.length<20&&(e+=this._input.substr(0,20-e.length)),(e.substr(0,20)+(e.length>20?"...":"")).replace(/\n/g,"")},showPosition:function(){var e=this.pastInput(),t=new Array(e.length+1).join("-")
return e+this.upcomingInput()+"\n"+t+"^"},next:function(){if(this.done)return this.EOF
var e,t,r,n,i
this._input||(this.done=!0),this._more||(this.yytext="",this.match="")
for(var o=this._currentRules(),s=0;s<o.length&&(!(r=this._input.match(this.rules[o[s]]))||t&&!(r[0].length>t[0].length)||(t=r,n=s,this.options.flex));s++);return t?((i=t[0].match(/(?:\r\n?|\n).*/g))&&(this.yylineno+=i.length),this.yylloc={first_line:this.yylloc.last_line,last_line:this.yylineno+1,first_column:this.yylloc.last_column,last_column:i?i[i.length-1].length-i[i.length-1].match(/\r?\n?/)[0].length:this.yylloc.last_column+t[0].length},this.yytext+=t[0],this.match+=t[0],this.matches=t,this.yyleng=this.yytext.length,this.options.ranges&&(this.yylloc.range=[this.offset,this.offset+=this.yyleng]),this._more=!1,this._input=this._input.slice(t[0].length),this.matched+=t[0],e=this.performAction.call(this,this.yy,this,o[n],this.conditionStack[this.conditionStack.length-1]),this.done&&this._input&&(this.done=!1),e||void 0):""===this._input?this.EOF:this.parseError("Lexical error on line "+(this.yylineno+1)+". Unrecognized text.\n"+this.showPosition(),{text:"",token:null,line:this.yylineno})},lex:function(){var e=this.next()
return void 0!==e?e:this.lex()},begin:function(e){this.conditionStack.push(e)},popState:function(){return this.conditionStack.pop()},_currentRules:function(){return this.conditions[this.conditionStack[this.conditionStack.length-1]].rules},topState:function(){return this.conditionStack[this.conditionStack.length-2]},pushState:function(e){this.begin(e)},options:{},performAction:function(e,t,r,n){function i(e,r){return t.yytext=t.yytext.substring(e,t.yyleng-r+e)}switch(r){case 0:if("\\\\"===t.yytext.slice(-2)?(i(0,1),this.begin("mu")):"\\"===t.yytext.slice(-1)?(i(0,1),this.begin("emu")):this.begin("mu"),t.yytext)return 15
break
case 1:case 5:return 15
case 2:return this.popState(),15
case 3:return this.begin("raw"),15
case 4:return this.popState(),"raw"===this.conditionStack[this.conditionStack.length-1]?15:(i(5,9),"END_RAW_BLOCK")
case 6:case 22:return this.popState(),14
case 7:return 65
case 8:return 68
case 9:return 19
case 10:return this.popState(),this.begin("raw"),23
case 11:return 55
case 12:return 60
case 13:return 29
case 14:return 47
case 15:case 16:return this.popState(),44
case 17:return 34
case 18:return 39
case 19:return 51
case 20:case 23:return 48
case 21:this.unput(t.yytext),this.popState(),this.begin("com")
break
case 24:return 73
case 25:case 26:case 41:return 72
case 27:return 87
case 28:break
case 29:return this.popState(),54
case 30:return this.popState(),33
case 31:return t.yytext=i(1,2).replace(/\\"/g,'"'),80
case 32:return t.yytext=i(1,2).replace(/\\'/g,"'"),80
case 33:return 85
case 34:case 35:return 82
case 36:return 83
case 37:return 84
case 38:return 81
case 39:return 75
case 40:return 77
case 42:return t.yytext=t.yytext.replace(/\\([\\\]])/g,"$1"),72
case 43:return"INVALID"
case 44:return 5}},rules:[/^(?:[^\x00]*?(?=(\{\{)))/,/^(?:[^\x00]+)/,/^(?:[^\x00]{2,}?(?=(\{\{|\\\{\{|\\\\\{\{|$)))/,/^(?:\{\{\{\{(?=[^\/]))/,/^(?:\{\{\{\{\/[^\s!"#%-,\.\/;->@\[-\^`\{-~]+(?=[=}\s\/.])\}\}\}\})/,/^(?:[^\x00]+?(?=(\{\{\{\{)))/,/^(?:[\s\S]*?--(~)?\}\})/,/^(?:\()/,/^(?:\))/,/^(?:\{\{\{\{)/,/^(?:\}\}\}\})/,/^(?:\{\{(~)?>)/,/^(?:\{\{(~)?#>)/,/^(?:\{\{(~)?#\*?)/,/^(?:\{\{(~)?\/)/,/^(?:\{\{(~)?\^\s*(~)?\}\})/,/^(?:\{\{(~)?\s*else\s*(~)?\}\})/,/^(?:\{\{(~)?\^)/,/^(?:\{\{(~)?\s*else\b)/,/^(?:\{\{(~)?\{)/,/^(?:\{\{(~)?&)/,/^(?:\{\{(~)?!--)/,/^(?:\{\{(~)?![\s\S]*?\}\})/,/^(?:\{\{(~)?\*?)/,/^(?:=)/,/^(?:\.\.)/,/^(?:\.(?=([=~}\s\/.)|])))/,/^(?:[\/.])/,/^(?:\s+)/,/^(?:\}(~)?\}\})/,/^(?:(~)?\}\})/,/^(?:"(\\["]|[^"])*")/,/^(?:'(\\[']|[^'])*')/,/^(?:@)/,/^(?:true(?=([~}\s)])))/,/^(?:false(?=([~}\s)])))/,/^(?:undefined(?=([~}\s)])))/,/^(?:null(?=([~}\s)])))/,/^(?:-?[0-9]+(?:\.[0-9]+)?(?=([~}\s)])))/,/^(?:as\s+\|)/,/^(?:\|)/,/^(?:([^\s!"#%-,\.\/;->@\[-\^`\{-~]+(?=([=~}\s\/.)|]))))/,/^(?:\[(\\\]|[^\]])*\])/,/^(?:.)/,/^(?:$)/],conditions:{mu:{rules:[7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44],inclusive:!1},emu:{rules:[2],inclusive:!1},com:{rules:[6],inclusive:!1},raw:{rules:[3,4,5],inclusive:!1},INITIAL:{rules:[0,1,44],inclusive:!0}}}
function r(){this.yy={}}return e.lexer=t,r.prototype=e,e.Parser=r,new r}()
t.default=r,e.exports=t.default},5861:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=(n=r(3800))&&n.__esModule?n:{default:n}
function o(){this.parents=[]}function s(e){this.acceptRequired(e,"path"),this.acceptArray(e.params),this.acceptKey(e,"hash")}function a(e){s.call(this,e),this.acceptKey(e,"program"),this.acceptKey(e,"inverse")}function l(e){this.acceptRequired(e,"name"),this.acceptArray(e.params),this.acceptKey(e,"hash")}o.prototype={constructor:o,mutating:!1,acceptKey:function(e,t){var r=this.accept(e[t])
if(this.mutating){if(r&&!o.prototype[r.type])throw new i.default('Unexpected node type "'+r.type+'" found when accepting '+t+" on "+e.type)
e[t]=r}},acceptRequired:function(e,t){if(this.acceptKey(e,t),!e[t])throw new i.default(e.type+" requires "+t)},acceptArray:function(e){for(var t=0,r=e.length;t<r;t++)this.acceptKey(e,t),e[t]||(e.splice(t,1),t--,r--)},accept:function(e){if(e){if(!this[e.type])throw new i.default("Unknown type: "+e.type,e)
this.current&&this.parents.unshift(this.current),this.current=e
var t=this[e.type](e)
return this.current=this.parents.shift(),!this.mutating||t?t:!1!==t?e:void 0}},Program:function(e){this.acceptArray(e.body)},MustacheStatement:s,Decorator:s,BlockStatement:a,DecoratorBlock:a,PartialStatement:l,PartialBlockStatement:function(e){l.call(this,e),this.acceptKey(e,"program")},ContentStatement:function(){},CommentStatement:function(){},SubExpression:s,PathExpression:function(){},StringLiteral:function(){},NumberLiteral:function(){},BooleanLiteral:function(){},UndefinedLiteral:function(){},NullLiteral:function(){},Hash:function(e){this.acceptArray(e.pairs)},HashPair:function(e){this.acceptRequired(e,"value")}},t.default=o,e.exports=t.default},6825:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=(n=r(5861))&&n.__esModule?n:{default:n}
function o(){var e=arguments.length<=0||void 0===arguments[0]?{}:arguments[0]
this.options=e}function s(e,t,r){void 0===t&&(t=e.length)
var n=e[t-1],i=e[t-2]
return n?"ContentStatement"===n.type?(i||!r?/\r?\n\s*?$/:/(^|\r?\n)\s*?$/).test(n.original):void 0:r}function a(e,t,r){void 0===t&&(t=-1)
var n=e[t+1],i=e[t+2]
return n?"ContentStatement"===n.type?(i||!r?/^\s*?\r?\n/:/^\s*?(\r?\n|$)/).test(n.original):void 0:r}function l(e,t,r){var n=e[null==t?0:t+1]
if(n&&"ContentStatement"===n.type&&(r||!n.rightStripped)){var i=n.value
n.value=n.value.replace(r?/^\s+/:/^[ \t]*\r?\n?/,""),n.rightStripped=n.value!==i}}function c(e,t,r){var n=e[null==t?e.length-1:t-1]
if(n&&"ContentStatement"===n.type&&(r||!n.leftStripped)){var i=n.value
return n.value=n.value.replace(r?/\s+$/:/[ \t]+$/,""),n.leftStripped=n.value!==i,n.leftStripped}}o.prototype=new i.default,o.prototype.Program=function(e){var t=!this.options.ignoreStandalone,r=!this.isRootSeen
this.isRootSeen=!0
for(var n=e.body,i=0,o=n.length;i<o;i++){var u=n[i],p=this.accept(u)
if(p){var h=s(n,i,r),d=a(n,i,r),f=p.openStandalone&&h,m=p.closeStandalone&&d,g=p.inlineStandalone&&h&&d
p.close&&l(n,i,!0),p.open&&c(n,i,!0),t&&g&&(l(n,i),c(n,i)&&"PartialStatement"===u.type&&(u.indent=/([ \t]+$)/.exec(n[i-1].original)[1])),t&&f&&(l((u.program||u.inverse).body),c(n,i)),t&&m&&(l(n,i),c((u.inverse||u.program).body))}}return e},o.prototype.BlockStatement=o.prototype.DecoratorBlock=o.prototype.PartialBlockStatement=function(e){this.accept(e.program),this.accept(e.inverse)
var t=e.program||e.inverse,r=e.program&&e.inverse,n=r,i=r
if(r&&r.chained)for(n=r.body[0].program;i.chained;)i=i.body[i.body.length-1].program
var o={open:e.openStrip.open,close:e.closeStrip.close,openStandalone:a(t.body),closeStandalone:s((n||t).body)}
if(e.openStrip.close&&l(t.body,null,!0),r){var u=e.inverseStrip
u.open&&c(t.body,null,!0),u.close&&l(n.body,null,!0),e.closeStrip.open&&c(i.body,null,!0),!this.options.ignoreStandalone&&s(t.body)&&a(n.body)&&(c(t.body),l(n.body))}else e.closeStrip.open&&c(t.body,null,!0)
return o},o.prototype.Decorator=o.prototype.MustacheStatement=function(e){return e.strip},o.prototype.PartialStatement=o.prototype.CommentStatement=function(e){var t=e.strip||{}
return{inlineStandalone:!0,open:t.open,close:t.close}},t.default=o,e.exports=t.default},781:(e,t,r)=>{"use strict"
t.__esModule=!0,t.registerDefaultDecorators=function(e){i.default(e)}
var n,i=(n=r(3650))&&n.__esModule?n:{default:n}},3650:(e,t,r)=>{"use strict"
t.__esModule=!0
var n=r(699)
t.default=function(e){e.registerDecorator("inline",(function(e,t,r,i){var o=e
return t.partials||(t.partials={},o=function(i,o){var s=r.partials
r.partials=n.extend({},s,t.partials)
var a=e(i,o)
return r.partials=s,a}),t.partials[i.args[0]]=i.fn,o}))},e.exports=t.default},3800:(e,t)=>{"use strict"
t.__esModule=!0
var r=["description","fileName","lineNumber","endLineNumber","message","name","number","stack"]
function n(e,t){var i=t&&t.loc,o=void 0,s=void 0,a=void 0,l=void 0
i&&(o=i.start.line,s=i.end.line,a=i.start.column,l=i.end.column,e+=" - "+o+":"+a)
for(var c=Error.prototype.constructor.call(this,e),u=0;u<r.length;u++)this[r[u]]=c[r[u]]
Error.captureStackTrace&&Error.captureStackTrace(this,n)
try{i&&(this.lineNumber=o,this.endLineNumber=s,Object.defineProperty?(Object.defineProperty(this,"column",{value:a,enumerable:!0}),Object.defineProperty(this,"endColumn",{value:l,enumerable:!0})):(this.column=a,this.endColumn=l))}catch(e){}}n.prototype=new Error,t.default=n,e.exports=t.default},8843:(e,t,r)=>{"use strict"
function n(e){return e&&e.__esModule?e:{default:e}}t.__esModule=!0,t.registerDefaultHelpers=function(e){i.default(e),o.default(e),s.default(e),a.default(e),l.default(e),c.default(e),u.default(e)},t.moveHelperToHooks=function(e,t,r){e.helpers[t]&&(e.hooks[t]=e.helpers[t],r||delete e.helpers[t])}
var i=n(r(3563)),o=n(r(484)),s=n(r(9585)),a=n(r(9363)),l=n(r(5401)),c=n(r(6007)),u=n(r(9934))},3563:(e,t,r)=>{"use strict"
t.__esModule=!0
var n=r(699)
t.default=function(e){e.registerHelper("blockHelperMissing",(function(t,r){var i=r.inverse,o=r.fn
if(!0===t)return o(this)
if(!1===t||null==t)return i(this)
if(n.isArray(t))return t.length>0?(r.ids&&(r.ids=[r.name]),e.helpers.each(t,r)):i(this)
if(r.data&&r.ids){var s=n.createFrame(r.data)
s.contextPath=n.appendContextPath(r.data.contextPath,r.name),r={data:s}}return o(t,r)}))},e.exports=t.default},484:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=r(699),o=(n=r(3800))&&n.__esModule?n:{default:n}
t.default=function(e){e.registerHelper("each",(function(e,t){if(!t)throw new o.default("Must pass iterator to #each")
var r,n=t.fn,s=t.inverse,a=0,l="",c=void 0,u=void 0
function p(t,r,o){c&&(c.key=t,c.index=r,c.first=0===r,c.last=!!o,u&&(c.contextPath=u+t)),l+=n(e[t],{data:c,blockParams:i.blockParams([e[t],t],[u+t,null])})}if(t.data&&t.ids&&(u=i.appendContextPath(t.data.contextPath,t.ids[0])+"."),i.isFunction(e)&&(e=e.call(this)),t.data&&(c=i.createFrame(t.data)),e&&"object"==typeof e)if(i.isArray(e))for(var h=e.length;a<h;a++)a in e&&p(a,a,a===e.length-1)
else if(global.Symbol&&e[global.Symbol.iterator]){for(var d=[],f=e[global.Symbol.iterator](),m=f.next();!m.done;m=f.next())d.push(m.value)
for(h=(e=d).length;a<h;a++)p(a,a,a===e.length-1)}else r=void 0,Object.keys(e).forEach((function(e){void 0!==r&&p(r,a-1),r=e,a++})),void 0!==r&&p(r,a-1,!0)
return 0===a&&(l=s(this)),l}))},e.exports=t.default},9585:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=(n=r(3800))&&n.__esModule?n:{default:n}
t.default=function(e){e.registerHelper("helperMissing",(function(){if(1!==arguments.length)throw new i.default('Missing helper: "'+arguments[arguments.length-1].name+'"')}))},e.exports=t.default},9363:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=r(699),o=(n=r(3800))&&n.__esModule?n:{default:n}
t.default=function(e){e.registerHelper("if",(function(e,t){if(2!=arguments.length)throw new o.default("#if requires exactly one argument")
return i.isFunction(e)&&(e=e.call(this)),!t.hash.includeZero&&!e||i.isEmpty(e)?t.inverse(this):t.fn(this)})),e.registerHelper("unless",(function(t,r){if(2!=arguments.length)throw new o.default("#unless requires exactly one argument")
return e.helpers.if.call(this,t,{fn:r.inverse,inverse:r.fn,hash:r.hash})}))},e.exports=t.default},5401:(e,t)=>{"use strict"
t.__esModule=!0,t.default=function(e){e.registerHelper("log",(function(){for(var t=[void 0],r=arguments[arguments.length-1],n=0;n<arguments.length-1;n++)t.push(arguments[n])
var i=1
null!=r.hash.level?i=r.hash.level:r.data&&null!=r.data.level&&(i=r.data.level),t[0]=i,e.log.apply(e,t)}))},e.exports=t.default},6007:(e,t)=>{"use strict"
t.__esModule=!0,t.default=function(e){e.registerHelper("lookup",(function(e,t,r){return e?r.lookupProperty(e,t):e}))},e.exports=t.default},9934:(e,t,r)=>{"use strict"
t.__esModule=!0
var n,i=r(699),o=(n=r(3800))&&n.__esModule?n:{default:n}
t.default=function(e){e.registerHelper("with",(function(e,t){if(2!=arguments.length)throw new o.default("#with requires exactly one argument")
i.isFunction(e)&&(e=e.call(this))
var r=t.fn
if(i.isEmpty(e))return t.inverse(this)
var n=t.data
return t.data&&t.ids&&((n=i.createFrame(t.data)).contextPath=i.appendContextPath(t.data.contextPath,t.ids[0])),r(e,{data:n,blockParams:i.blockParams([e],[n&&n.contextPath])})}))},e.exports=t.default},8646:(e,t,r)=>{"use strict"
t.__esModule=!0,t.createNewLookupObject=function(){for(var e=arguments.length,t=Array(e),r=0;r<e;r++)t[r]=arguments[r]
return n.extend.apply(void 0,[Object.create(null)].concat(t))}
var n=r(699)},2038:(e,t,r)=>{"use strict"
t.__esModule=!0,t.createProtoAccessControl=function(e){var t=Object.create(null)
t.constructor=!1,t.__defineGetter__=!1,t.__defineSetter__=!1,t.__lookupGetter__=!1
var r=Object.create(null)
return r.__proto__=!1,{properties:{whitelist:n.createNewLookupObject(r,e.allowedProtoProperties),defaultValue:e.allowProtoPropertiesByDefault},methods:{whitelist:n.createNewLookupObject(t,e.allowedProtoMethods),defaultValue:e.allowProtoMethodsByDefault}}},t.resultIsAllowed=function(e,t,r){return function(e,t){return void 0!==e.whitelist[t]?!0===e.whitelist[t]:void 0!==e.defaultValue?e.defaultValue:(function(e){!0!==o[e]&&(o[e]=!0,i.log("error",'Handlebars: Access has been denied to resolve the property "'+e+'" because it is not an "own property" of its parent.\nYou can add a runtime option to disable the check or this warning:\nSee https://handlebarsjs.com/api-reference/runtime-options.html#options-to-control-prototype-access for details'))}(t),!1)}("function"==typeof e?t.methods:t.properties,r)},t.resetLoggedProperties=function(){Object.keys(o).forEach((function(e){delete o[e]}))}
var n=r(8646),i=function(e){if(e&&e.__esModule)return e
var t={}
if(null!=e)for(var r in e)Object.prototype.hasOwnProperty.call(e,r)&&(t[r]=e[r])
return t.default=e,t}(r(7266)),o=Object.create(null)},890:(e,t)=>{"use strict"
t.__esModule=!0,t.wrapHelper=function(e,t){return"function"!=typeof e?e:function(){return arguments[arguments.length-1]=t(arguments[arguments.length-1]),e.apply(this,arguments)}}},7266:(e,t,r)=>{"use strict"
t.__esModule=!0
var n=r(699),i={methodMap:["debug","info","warn","error"],level:"info",lookupLevel:function(e){if("string"==typeof e){var t=n.indexOf(i.methodMap,e.toLowerCase())
e=t>=0?t:parseInt(e,10)}return e},log:function(e){if(e=i.lookupLevel(e),"undefined"!=typeof console&&i.lookupLevel(i.level)<=e){var t=i.methodMap[e]
console[t]||(t="log")
for(var r=arguments.length,n=Array(r>1?r-1:0),o=1;o<r;o++)n[o-1]=arguments[o]
console[t].apply(console,n)}}}
t.default=i,e.exports=t.default},8226:(e,t)=>{"use strict"
t.__esModule=!0,t.default=function(e){var t="undefined"!=typeof global?global:window,r=t.Handlebars
e.noConflict=function(){return t.Handlebars===e&&(t.Handlebars=r),e}},e.exports=t.default},9771:(e,t,r)=>{"use strict"
t.__esModule=!0,t.checkRevision=function(e){var t=e&&e[0]||1,r=s.COMPILER_REVISION
if(!(t>=s.LAST_COMPATIBLE_COMPILER_REVISION&&t<=s.COMPILER_REVISION)){if(t<s.LAST_COMPATIBLE_COMPILER_REVISION){var n=s.REVISION_CHANGES[r],i=s.REVISION_CHANGES[t]
throw new o.default("Template was precompiled with an older version of Handlebars than the current runtime. Please update your precompiler to a newer version ("+n+") or downgrade your runtime to an older version ("+i+").")}throw new o.default("Template was precompiled with a newer version of Handlebars than the current runtime. Please update your runtime to a newer version ("+e[1]+").")}},t.template=function(e,t){if(!t)throw new o.default("No environment passed to template")
if(!e||!e.main)throw new o.default("Unknown template object: "+typeof e)
e.main.decorator=e.main_d,t.VM.checkRevision(e.compiler)
var r=e.compiler&&7===e.compiler[0],n={strict:function(e,t,r){if(!e||!(t in e))throw new o.default('"'+t+'" not defined in '+e,{loc:r})
return n.lookupProperty(e,t)},lookupProperty:function(e,t){var r=e[t]
return null==r||Object.prototype.hasOwnProperty.call(e,t)||c.resultIsAllowed(r,n.protoAccessControl,t)?r:void 0},lookup:function(e,t){for(var r=e.length,i=0;i<r;i++)if(null!=(e[i]&&n.lookupProperty(e[i],t)))return e[i][t]},lambda:function(e,t){return"function"==typeof e?e.call(t):e},escapeExpression:i.escapeExpression,invokePartial:function(r,n,s){s.hash&&(n=i.extend({},n,s.hash),s.ids&&(s.ids[0]=!0)),r=t.VM.resolvePartial.call(this,r,n,s)
var a=i.extend({},s,{hooks:this.hooks,protoAccessControl:this.protoAccessControl}),l=t.VM.invokePartial.call(this,r,n,a)
if(null==l&&t.compile&&(s.partials[s.name]=t.compile(r,e.compilerOptions,t),l=s.partials[s.name](n,a)),null!=l){if(s.indent){for(var c=l.split("\n"),u=0,p=c.length;u<p&&(c[u]||u+1!==p);u++)c[u]=s.indent+c[u]
l=c.join("\n")}return l}throw new o.default("The partial "+s.name+" could not be compiled when running in runtime-only mode")},fn:function(t){var r=e[t]
return r.decorator=e[t+"_d"],r},programs:[],program:function(e,t,r,n,i){var o=this.programs[e],s=this.fn(e)
return t||i||n||r?o=u(this,e,s,t,r,n,i):o||(o=this.programs[e]=u(this,e,s)),o},data:function(e,t){for(;e&&t--;)e=e._parent
return e},mergeIfNeeded:function(e,t){var r=e||t
return e&&t&&e!==t&&(r=i.extend({},t,e)),r},nullContext:Object.seal({}),noop:t.VM.noop,compilerInfo:e.compiler}
function s(t){var r=arguments.length<=1||void 0===arguments[1]?{}:arguments[1],i=r.data
s._setup(r),!r.partial&&e.useData&&(i=h(t,i))
var o=void 0,a=e.useBlockParams?[]:void 0
function l(t){return""+e.main(n,t,n.helpers,n.partials,i,a,o)}return e.useDepths&&(o=r.depths?t!=r.depths[0]?[t].concat(r.depths):r.depths:[t]),(l=d(e.main,l,n,r.depths||[],i,a))(t,r)}return s.isTop=!0,s._setup=function(o){if(o.partial)n.protoAccessControl=o.protoAccessControl,n.helpers=o.helpers,n.partials=o.partials,n.decorators=o.decorators,n.hooks=o.hooks
else{var s=i.extend({},t.helpers,o.helpers)
!function(e,t){Object.keys(e).forEach((function(r){var n=e[r]
e[r]=function(e,t){var r=t.lookupProperty
return l.wrapHelper(e,(function(e){return i.extend({lookupProperty:r},e)}))}(n,t)}))}(s,n),n.helpers=s,e.usePartial&&(n.partials=n.mergeIfNeeded(o.partials,t.partials)),(e.usePartial||e.useDecorators)&&(n.decorators=i.extend({},t.decorators,o.decorators)),n.hooks={},n.protoAccessControl=c.createProtoAccessControl(o)
var u=o.allowCallsToHelperMissing||r
a.moveHelperToHooks(n,"helperMissing",u),a.moveHelperToHooks(n,"blockHelperMissing",u)}},s._child=function(t,r,i,s){if(e.useBlockParams&&!i)throw new o.default("must pass block params")
if(e.useDepths&&!s)throw new o.default("must pass parent depths")
return u(n,t,e[t],r,0,i,s)},s},t.wrapProgram=u,t.resolvePartial=function(e,t,r){return e?e.call||r.name||(r.name=e,e=r.partials[e]):e="@partial-block"===r.name?r.data["partial-block"]:r.partials[r.name],e},t.invokePartial=function(e,t,r){var n=r.data&&r.data["partial-block"]
r.partial=!0,r.ids&&(r.data.contextPath=r.ids[0]||r.data.contextPath)
var a=void 0
if(r.fn&&r.fn!==p&&function(){r.data=s.createFrame(r.data)
var e=r.fn
a=r.data["partial-block"]=function(t){var r=arguments.length<=1||void 0===arguments[1]?{}:arguments[1]
return r.data=s.createFrame(r.data),r.data["partial-block"]=n,e(t,r)},e.partials&&(r.partials=i.extend({},r.partials,e.partials))}(),void 0===e&&a&&(e=a),void 0===e)throw new o.default("The partial "+r.name+" could not be found")
if(e instanceof Function)return e(t,r)},t.noop=p
var n,i=function(e){if(e&&e.__esModule)return e
var t={}
if(null!=e)for(var r in e)Object.prototype.hasOwnProperty.call(e,r)&&(t[r]=e[r])
return t.default=e,t}(r(699)),o=(n=r(3800))&&n.__esModule?n:{default:n},s=r(6713),a=r(8843),l=r(890),c=r(2038)
function u(e,t,r,n,i,o,s){function a(t){var i=arguments.length<=1||void 0===arguments[1]?{}:arguments[1],a=s
return!s||t==s[0]||t===e.nullContext&&null===s[0]||(a=[t].concat(s)),r(e,t,e.helpers,e.partials,i.data||n,o&&[i.blockParams].concat(o),a)}return(a=d(r,a,e,s,n,o)).program=t,a.depth=s?s.length:0,a.blockParams=i||0,a}function p(){return""}function h(e,t){return t&&"root"in t||((t=t?s.createFrame(t):{}).root=e),t}function d(e,t,r,n,o,s){if(e.decorator){var a={}
t=e.decorator(t,a,r,n&&n[0],o,s,n),i.extend(t,a)}return t}},1373:(e,t)=>{"use strict"
function r(e){this.string=e}t.__esModule=!0,r.prototype.toString=r.prototype.toHTML=function(){return""+this.string},t.default=r,e.exports=t.default},699:(e,t)=>{"use strict"
t.__esModule=!0,t.extend=s,t.indexOf=function(e,t){for(var r=0,n=e.length;r<n;r++)if(e[r]===t)return r
return-1},t.escapeExpression=function(e){if("string"!=typeof e){if(e&&e.toHTML)return e.toHTML()
if(null==e)return""
if(!e)return e+""
e=""+e}return i.test(e)?e.replace(n,o):e},t.isEmpty=function(e){return!e&&0!==e||!(!c(e)||0!==e.length)},t.createFrame=function(e){var t=s({},e)
return t._parent=e,t},t.blockParams=function(e,t){return e.path=t,e},t.appendContextPath=function(e,t){return(e?e+".":"")+t}
var r={"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#x27;","`":"&#x60;","=":"&#x3D;"},n=/[&<>"'`=]/g,i=/[&<>"'`=]/
function o(e){return r[e]}function s(e){for(var t=1;t<arguments.length;t++)for(var r in arguments[t])Object.prototype.hasOwnProperty.call(arguments[t],r)&&(e[r]=arguments[t][r])
return e}var a=Object.prototype.toString
t.toString=a
var l=function(e){return"function"==typeof e}
l(/x/)&&(t.isFunction=l=function(e){return"function"==typeof e&&"[object Function]"===a.call(e)}),t.isFunction=l
var c=Array.isArray||function(e){return!(!e||"object"!=typeof e)&&"[object Array]"===a.call(e)}
t.isArray=c},701:e=>{"use strict"
var t="undefined"!=typeof window?window:"undefined"!=typeof global?global:{}
e.exports=function(e,r){return e in t?t[e]:(t[e]=r,r)}},1678:(e,t,r)=>{"use strict"
var n=r(701)
e.exports=function(e,t,r){var i="__INDIVIDUAL_ONE_VERSION_"+e,o=n(i+"_ENFORCE_SINGLETON",t)
if(o!==t)throw new Error("Can only have one copy of "+e+".\nYou already have version "+o+" installed.\nThis means you cannot install version "+t)
return n(i,r)}},7819:e=>{"use strict"
e.exports=function(e){return"object"==typeof e&&null!==e}},7930:e=>{var t="Expected a function",r=/^\s+|\s+$/g,n=/^[-+]0x[0-9a-f]+$/i,i=/^0b[01]+$/i,o=/^0o[0-7]+$/i,s=parseInt,a="object"==typeof global&&global&&global.Object===Object&&global,l="object"==typeof self&&self&&self.Object===Object&&self,c=a||l||Function("return this")(),u=Object.prototype.toString,p=Math.max,h=Math.min,d=function(){return c.Date.now()}
function f(e){var t=typeof e
return!!e&&("object"==t||"function"==t)}function m(e){if("number"==typeof e)return e
if(function(e){return"symbol"==typeof e||function(e){return!!e&&"object"==typeof e}(e)&&"[object Symbol]"==u.call(e)}(e))return NaN
if(f(e)){var t="function"==typeof e.valueOf?e.valueOf():e
e=f(t)?t+"":t}if("string"!=typeof e)return 0===e?e:+e
e=e.replace(r,"")
var a=i.test(e)
return a||o.test(e)?s(e.slice(2),a?2:8):n.test(e)?NaN:+e}e.exports=function(e,r,n){var i=!0,o=!0
if("function"!=typeof e)throw new TypeError(t)
return f(n)&&(i="leading"in n?!!n.leading:i,o="trailing"in n?!!n.trailing:o),function(e,r,n){var i,o,s,a,l,c,u=0,g=!1,v=!1,y=!0
if("function"!=typeof e)throw new TypeError(t)
function b(t){var r=i,n=o
return i=o=void 0,u=t,a=e.apply(n,r)}function w(e){return u=e,l=setTimeout(_,r),g?b(e):a}function k(e){var t=e-c
return void 0===c||t>=r||t<0||v&&e-u>=s}function _(){var e=d()
if(k(e))return x(e)
l=setTimeout(_,function(e){var t=r-(e-c)
return v?h(t,s-(e-u)):t}(e))}function x(e){return l=void 0,y&&i?b(e):(i=o=void 0,a)}function P(){var e=d(),t=k(e)
if(i=arguments,o=this,c=e,t){if(void 0===l)return w(c)
if(v)return l=setTimeout(_,r),b(c)}return void 0===l&&(l=setTimeout(_,r)),a}return r=m(r)||0,f(n)&&(g=!!n.leading,s=(v="maxWait"in n)?p(m(n.maxWait)||0,r):s,y="trailing"in n?!!n.trailing:y),P.cancel=function(){void 0!==l&&clearTimeout(l),u=0,i=c=o=l=void 0},P.flush=function(){return void 0===l?a:x(d())},P}(e,r,{leading:i,maxWait:r,trailing:o})}},7348:function(e,t){var r,n
n="undefined"!=typeof self?self:this,void 0===(r=function(){return n.MessageBus=function(){"use strict"
var e,t,r,n,i=!1,o=!1,s="xxxxxxxxxxxx4xxxyxxxxxxxxxxxxxxx".replace(/[xy]/g,(function(e){var t=16*Math.random()|0
return("x"===e?t:3&t|8).toString(16)})),a=[],l=0,c=!1,u=[],p=0,h=null,d=0,f=0,m=function(){for(var e,t=["","webkit","ms","moz"],r=0;r<t.length;r++){var n=t[r],i=n+(""===n?"hidden":"Hidden")
void 0!==document[i]&&(e=i)}return function(){return void 0!==e?document[e]:!document.hasFocus}}(),g=function(){try{return localStorage.setItem("mbTestLocalStorage",Date.now()),localStorage.removeItem("mbTestLocalStorage"),!0}catch(e){return!1}}(),v=null===(new XMLHttpRequest).onprogress,y=function(){return e.alwaysLongPoll||(e.shouldLongPollCallback?e.shouldLongPollCallback():!m())},b=function(e){if(!e||0===e.length)return!1
for(var t=0;t<e.length;t++)for(var r=e[t],n=0;n<a.length;n++){var i=a[n]
if(i.channel===r.channel){i.last_id=r.message_id
try{i.func(r.data,r.global_id,r.message_id)}catch(e){console.log&&console.log("MESSAGE BUS FAIL: callback "+i.channel+" caused exception "+e.stack)}}"/__status"===r.channel&&void 0!==r.data[i.channel]&&(i.last_id=r.data[i.channel])}return!0},w=function(e){if(l=0,!c)return b(e)
if(e)for(var t=0;t<e.length;t++)u.push(e[t])
return!1},k=function(t,r){if(!i){var s,a=!1,c=!1,u=!1
n=new Date,f+=1,r.__seq=f
var m=y()&&e.enableLongPolling,b=m&&e.enableChunkedEncoding&&v
p>0&&(p--,b=!1)
var k={"X-SILENCE-LOGGER":"true"}
for(var _ in e.headers)k[_]=e.headers[_]
b||(k["Dont-Chunk"]="true")
var x=b?"text":"json",P=function(e,t){var n="\r\n|\r\n",i=e.indexOf(n,t)
if(-1===i)return t
var o=e.substring(t,i)
o=o.replace(/\r\n\|\|\r\n/g,n)
try{w(JSON.parse(o))}catch(e){console.log&&(console.log("FAILED TO PARSE CHUNKED REPLY"),console.log(r))}return P(e,i+n.length)},S=function(){e.longPoll&&(e.longPoll.abort(),p=30)}
if(!e.ajax)throw new Error("Either jQuery or the ajax adapter must be loaded")
return g&&localStorage.setItem("__mbLastAjax",Date.now()),i=!0,e.ajax({url:e.baseUrl+"message-bus/"+e.clientId+"/poll"+(m?"":"?dlp=t"),data:r,async:!0,dataType:x,type:"POST",headers:k,messageBus:{chunked:b,onProgressListener:function(e){var t=0,r=setTimeout(S,3e3)
return e.onprogress=function(){clearTimeout(r),"application/json; charset=utf-8"===e.getResponseHeader("Content-Type")?b=!1:t=P(e.responseText,t)}}},xhr:function(){var e=jQuery.ajaxSettings.xhr()
return b?(this.messageBus.onProgressListener(e),e):e},success:function(e){b||("string"==typeof e&&(e=JSON.parse(e)),a=w(e))},error:function(e,t){if(429===e.status){var r=parseInt(e.getResponseHeader&&e.getResponseHeader("Retry-After"))||0;(r=r||0)<15&&(r=15),s=r,u=!0}else"abort"===t?c=!0:(l+=1,d+=1)},complete:function(){var r
i=!1
try{u?r=Math.max(e.minPollInterval,1e3*s):a||c?r=e.minPollInterval:(r=e.callbackInterval,l>2?r*=l:y()||(r=e.backgroundCallbackInterval),r>e.maxPollInterval&&(r=e.maxPollInterval),(r-=new Date-n)<100&&(r=100))}catch(e){console.log&&e.message&&console.log("MESSAGE BUS FAIL: "+e.message)}h&&(clearTimeout(h),h=null),o&&(h=setTimeout((function(){h=null,t()}),r)),e.longPoll=null}})}}
return e={minHiddenPollInterval:1500,enableChunkedEncoding:!0,enableLongPolling:!0,callbackInterval:15e3,backgroundCallbackInterval:6e4,minPollInterval:100,maxPollInterval:18e4,callbacks:a,clientId:s,alwaysLongPoll:!1,shouldLongPollCallback:void 0,baseUrl:"/",headers:{},ajax:"undefined"!=typeof jQuery&&jQuery.ajax,diagnostics:function(){console.log("Stopped: "+r+" Started: "+o),console.log("Current callbacks"),console.log(a),console.log("Total ajax calls: "+f+" Recent failure count: "+l+" Total failures: "+d),console.log("Last ajax call: "+(new Date-n)/1e3+" seconds ago")},pause:function(){c=!0},resume:function(){c=!1,b(u),u=[]},stop:function(){r=!0,o=!1,t&&(clearTimeout(t),t=null),h&&(clearTimeout(h),h=null),e.longPoll&&e.longPoll.abort(),e.onVisibilityChange&&(document.removeEventListener("visibilitychange",e.onVisibilityChange),e.onVisibilityChange=null)},start:function(){if(!o){o=!0,r=!1
var n=function(){if(!r)if(0===a.length||function(){if(g&&m()){var t=parseInt(localStorage.getItem("__mbLastAjax"),10),r=Date.now()-t
return r>=0&&r<e.minHiddenPollInterval}return!1}())t||(t=setTimeout((function(){t=null,n()}),parseInt(500+500*Math.random())))
else{for(var i={},o=0;o<a.length;o++)i[a[o].channel]=a[o].last_id
e.longPoll||(e.longPoll=k(n,i))}}
document.addEventListener&&"hidden"in document&&(e.onVisibilityChange=function(){document.hidden||e.longPoll||!h&&!t||(clearTimeout(h),clearTimeout(t),t=null,h=null,n())},document.addEventListener("visibilitychange",e.onVisibilityChange)),n()}},status:function(){if(c)return"paused"
if(o)return"started"
if(r)return"stopped"
throw"Cannot determine current status"},subscribe:function(t,n,i){if(o||r||e.start(),null==i)i=-1
else if("number"!=typeof i)throw"lastId has type "+typeof i+" but a number was expected."
if("string"!=typeof t)throw"Channel name must be a string!"
return a.push({channel:t,func:n,last_id:i}),e.longPoll&&e.longPoll.abort(),n},unsubscribe:function(t,r){var n=!1;-1!==t.indexOf("*",t.length-1)&&(t=t.substr(0,t.length-1),n=!0)
for(var i=!1,o=a.length-1;o>=0;o--){var s,l=a[o]
!(s=n?l.channel.substr(0,t.length)!==t:l.channel!==t)&&r&&l.func!==r&&(s=!0),s||(a.splice(o,1),i=!0)}return i&&e.longPoll&&e.longPoll.abort(),i}}}()}.apply(t,[]))||(e.exports=r)},6568:(e,t,r)=>{var n=r(9698),i=/[\/\+\.]/
e.exports=function(e,t){function r(t){var r=n(t,e,i)
return r&&r.length>=2}return t?r(t.split(";")[0]):r}},5575:e=>{e.exports=function(){var e={},t=e._fns={}
return e.emit=function(e,r,n,i,o,s,a){var l=function(e){for(var r=t[e]?t[e]:[],n=e.indexOf(":"),i=-1===n?[e]:[e.substring(0,n),e.substring(n+1)],o=Object.keys(t),s=0,a=o.length;s<a;s++){var l=o[s]
if("*"===l&&(r=r.concat(t[l])),2===i.length&&i[0]===l){r=r.concat(t[l])
break}}return r}(e)
l.length&&function(e,t,r){for(var n=0,i=t.length;n<i&&t[n];n++)t[n].event=e,t[n].apply(t[n],r)}(e,l,[r,n,i,o,s,a])},e.on=function(e,r){t[e]||(t[e]=[]),t[e].push(r)},e.once=function(t,r){this.on(t,(function n(){r.apply(this,arguments),e.off(t,n)}))},e.off=function(e,t){var r=[]
if(e&&t)for(var n=this._fns[e],i=0,o=n?n.length:0;i<o;i++)n[i]!==t&&r.push(n[i])
r.length?this._fns[e]=r:delete this._fns[e]},e}},8633:(e,t,r)=>{"use strict"
r.r(t),r.d(t,{Component:()=>w,Fragment:()=>b,cloneElement:()=>B,createContext:()=>Z,createElement:()=>g,createRef:()=>y,h:()=>g,hydrate:()=>H,isValidElement:()=>s,options:()=>i,render:()=>D,toChildArray:()=>O})
var n,i,o,s,a,l,c,u,p={},h=[],d=/acit|ex(?:s|g|n|p|$)|rph|grid|ows|mnc|ntw|ine[ch]|zoo|^ord|itera/i
function f(e,t){for(var r in t)e[r]=t[r]
return e}function m(e){var t=e.parentNode
t&&t.removeChild(e)}function g(e,t,r){var i,o,s,a={}
for(s in t)"key"==s?i=t[s]:"ref"==s?o=t[s]:a[s]=t[s]
if(arguments.length>2&&(a.children=arguments.length>3?n.call(arguments,2):r),"function"==typeof e&&null!=e.defaultProps)for(s in e.defaultProps)void 0===a[s]&&(a[s]=e.defaultProps[s])
return v(e,a,i,o,null)}function v(e,t,r,n,s){var a={type:e,props:t,key:r,ref:n,__k:null,__:null,__b:0,__e:null,__d:void 0,__c:null,__h:null,constructor:void 0,__v:null==s?++o:s}
return null!=i.vnode&&i.vnode(a),a}function y(){return{current:null}}function b(e){return e.children}function w(e,t){this.props=e,this.context=t}function k(e,t){if(null==t)return e.__?k(e.__,e.__.__k.indexOf(e)+1):null
for(var r;t<e.__k.length;t++)if(null!=(r=e.__k[t])&&null!=r.__e)return r.__e
return"function"==typeof e.type?k(e):null}function _(e){var t,r
if(null!=(e=e.__)&&null!=e.__c){for(e.__e=e.__c.base=null,t=0;t<e.__k.length;t++)if(null!=(r=e.__k[t])&&null!=r.__e){e.__e=e.__c.base=r.__e
break}return _(e)}}function x(e){(!e.__d&&(e.__d=!0)&&a.push(e)&&!P.__r++||c!==i.debounceRendering)&&((c=i.debounceRendering)||l)(P)}function P(){for(var e;P.__r=a.length;)e=a.sort((function(e,t){return e.__v.__b-t.__v.__b})),a=[],e.some((function(e){var t,r,n,i,o,s
e.__d&&(o=(i=(t=e).__v).__e,(s=t.__P)&&(r=[],(n=f({},i)).__v=i.__v+1,I(s,i,n,t.__n,void 0!==s.ownerSVGElement,null!=i.__h?[o]:null,r,null==o?k(i):o,i.__h),R(r,i),i.__e!=o&&_(i)))}))}function S(e,t,r,n,i,o,s,a,l,c){var u,d,f,m,g,y,w,_=n&&n.__k||h,x=_.length
for(r.__k=[],u=0;u<t.length;u++)if(null!=(m=r.__k[u]=null==(m=t[u])||"boolean"==typeof m?null:"string"==typeof m||"number"==typeof m||"bigint"==typeof m?v(null,m,null,null,m):Array.isArray(m)?v(b,{children:m},null,null,null):m.__b>0?v(m.type,m.props,m.key,null,m.__v):m)){if(m.__=r,m.__b=r.__b+1,null===(f=_[u])||f&&m.key==f.key&&m.type===f.type)_[u]=void 0
else for(d=0;d<x;d++){if((f=_[d])&&m.key==f.key&&m.type===f.type){_[d]=void 0
break}f=null}I(e,m,f=f||p,i,o,s,a,l,c),g=m.__e,(d=m.ref)&&f.ref!=d&&(w||(w=[]),f.ref&&w.push(f.ref,null,m),w.push(d,m.__c||g,m)),null!=g?(null==y&&(y=g),"function"==typeof m.type&&null!=m.__k&&m.__k===f.__k?m.__d=l=E(m,l,e):l=A(e,m,f,_,g,l),c||"option"!==r.type?"function"==typeof r.type&&(r.__d=l):e.value=""):l&&f.__e==l&&l.parentNode!=e&&(l=k(f))}for(r.__e=y,u=x;u--;)null!=_[u]&&("function"==typeof r.type&&null!=_[u].__e&&_[u].__e==r.__d&&(r.__d=k(n,u+1)),F(_[u],_[u]))
if(w)for(u=0;u<w.length;u++)U(w[u],w[++u],w[++u])}function E(e,t,r){var n,i
for(n=0;n<e.__k.length;n++)(i=e.__k[n])&&(i.__=e,t="function"==typeof i.type?E(i,t,r):A(r,i,i,e.__k,i.__e,t))
return t}function O(e,t){return t=t||[],null==e||"boolean"==typeof e||(Array.isArray(e)?e.some((function(e){O(e,t)})):t.push(e)),t}function A(e,t,r,n,i,o){var s,a,l
if(void 0!==t.__d)s=t.__d,t.__d=void 0
else if(null==r||i!=o||null==i.parentNode)e:if(null==o||o.parentNode!==e)e.appendChild(i),s=null
else{for(a=o,l=0;(a=a.nextSibling)&&l<n.length;l+=2)if(a==i)break e
e.insertBefore(i,o),s=o}return void 0!==s?s:i.nextSibling}function C(e,t,r){"-"===t[0]?e.setProperty(t,r):e[t]=null==r?"":"number"!=typeof r||d.test(t)?r:r+"px"}function T(e,t,r,n,i){var o
e:if("style"===t)if("string"==typeof r)e.style.cssText=r
else{if("string"==typeof n&&(e.style.cssText=n=""),n)for(t in n)r&&t in r||C(e.style,t,"")
if(r)for(t in r)n&&r[t]===n[t]||C(e.style,t,r[t])}else if("o"===t[0]&&"n"===t[1])o=t!==(t=t.replace(/Capture$/,"")),t=t.toLowerCase()in e?t.toLowerCase().slice(2):t.slice(2),e.l||(e.l={}),e.l[t+o]=r,r?n||e.addEventListener(t,o?j:L,o):e.removeEventListener(t,o?j:L,o)
else if("dangerouslySetInnerHTML"!==t){if(i)t=t.replace(/xlink[H:h]/,"h").replace(/sName$/,"s")
else if("href"!==t&&"list"!==t&&"form"!==t&&"tabIndex"!==t&&"download"!==t&&t in e)try{e[t]=null==r?"":r
break e}catch(e){}"function"==typeof r||(null!=r&&(!1!==r||"a"===t[0]&&"r"===t[1])?e.setAttribute(t,r):e.removeAttribute(t))}}function L(e){this.l[e.type+!1](i.event?i.event(e):e)}function j(e){this.l[e.type+!0](i.event?i.event(e):e)}function I(e,t,r,n,o,s,a,l,c){var u,p,h,d,m,g,v,y,k,_,x,P=t.type
if(void 0!==t.constructor)return null
null!=r.__h&&(c=r.__h,l=t.__e=r.__e,t.__h=null,s=[l]),(u=i.__b)&&u(t)
try{e:if("function"==typeof P){if(y=t.props,k=(u=P.contextType)&&n[u.__c],_=u?k?k.props.value:u.__:n,r.__c?v=(p=t.__c=r.__c).__=p.__E:("prototype"in P&&P.prototype.render?t.__c=p=new P(y,_):(t.__c=p=new w(y,_),p.constructor=P,p.render=M),k&&k.sub(p),p.props=y,p.state||(p.state={}),p.context=_,p.__n=n,h=p.__d=!0,p.__h=[]),null==p.__s&&(p.__s=p.state),null!=P.getDerivedStateFromProps&&(p.__s==p.state&&(p.__s=f({},p.__s)),f(p.__s,P.getDerivedStateFromProps(y,p.__s))),d=p.props,m=p.state,h)null==P.getDerivedStateFromProps&&null!=p.componentWillMount&&p.componentWillMount(),null!=p.componentDidMount&&p.__h.push(p.componentDidMount)
else{if(null==P.getDerivedStateFromProps&&y!==d&&null!=p.componentWillReceiveProps&&p.componentWillReceiveProps(y,_),!p.__e&&null!=p.shouldComponentUpdate&&!1===p.shouldComponentUpdate(y,p.__s,_)||t.__v===r.__v){p.props=y,p.state=p.__s,t.__v!==r.__v&&(p.__d=!1),p.__v=t,t.__e=r.__e,t.__k=r.__k,t.__k.forEach((function(e){e&&(e.__=t)})),p.__h.length&&a.push(p)
break e}null!=p.componentWillUpdate&&p.componentWillUpdate(y,p.__s,_),null!=p.componentDidUpdate&&p.__h.push((function(){p.componentDidUpdate(d,m,g)}))}p.context=_,p.props=y,p.state=p.__s,(u=i.__r)&&u(t),p.__d=!1,p.__v=t,p.__P=e,u=p.render(p.props,p.state,p.context),p.state=p.__s,null!=p.getChildContext&&(n=f(f({},n),p.getChildContext())),h||null==p.getSnapshotBeforeUpdate||(g=p.getSnapshotBeforeUpdate(d,m)),x=null!=u&&u.type===b&&null==u.key?u.props.children:u,S(e,Array.isArray(x)?x:[x],t,r,n,o,s,a,l,c),p.base=t.__e,t.__h=null,p.__h.length&&a.push(p),v&&(p.__E=p.__=null),p.__e=!1}else null==s&&t.__v===r.__v?(t.__k=r.__k,t.__e=r.__e):t.__e=N(r.__e,t,r,n,o,s,a,c);(u=i.diffed)&&u(t)}catch(e){t.__v=null,(c||null!=s)&&(t.__e=l,t.__h=!!c,s[s.indexOf(l)]=null),i.__e(e,t,r)}}function R(e,t){i.__c&&i.__c(t,e),e.some((function(t){try{e=t.__h,t.__h=[],e.some((function(e){e.call(t)}))}catch(e){i.__e(e,t.__v)}}))}function N(e,t,r,i,o,s,a,l){var c,u,h,d=r.props,f=t.props,g=t.type,v=0
if("svg"===g&&(o=!0),null!=s)for(;v<s.length;v++)if((c=s[v])&&(c===e||(g?c.localName==g:3==c.nodeType))){e=c,s[v]=null
break}if(null==e){if(null===g)return document.createTextNode(f)
e=o?document.createElementNS("http://www.w3.org/2000/svg",g):document.createElement(g,f.is&&f),s=null,l=!1}if(null===g)d===f||l&&e.data===f||(e.data=f)
else{if(s=s&&n.call(e.childNodes),u=(d=r.props||p).dangerouslySetInnerHTML,h=f.dangerouslySetInnerHTML,!l){if(null!=s)for(d={},v=0;v<e.attributes.length;v++)d[e.attributes[v].name]=e.attributes[v].value;(h||u)&&(h&&(u&&h.__html==u.__html||h.__html===e.innerHTML)||(e.innerHTML=h&&h.__html||""))}if(function(e,t,r,n,i){var o
for(o in r)"children"===o||"key"===o||o in t||T(e,o,null,r[o],n)
for(o in t)i&&"function"!=typeof t[o]||"children"===o||"key"===o||"value"===o||"checked"===o||r[o]===t[o]||T(e,o,t[o],r[o],n)}(e,f,d,o,l),h)t.__k=[]
else if(v=t.props.children,S(e,Array.isArray(v)?v:[v],t,r,i,o&&"foreignObject"!==g,s,a,s?s[0]:r.__k&&k(r,0),l),null!=s)for(v=s.length;v--;)null!=s[v]&&m(s[v])
l||("value"in f&&void 0!==(v=f.value)&&(v!==e.value||"progress"===g&&!v)&&T(e,"value",v,d.value,!1),"checked"in f&&void 0!==(v=f.checked)&&v!==e.checked&&T(e,"checked",v,d.checked,!1))}return e}function U(e,t,r){try{"function"==typeof e?e(t):e.current=t}catch(e){i.__e(e,r)}}function F(e,t,r){var n,o
if(i.unmount&&i.unmount(e),(n=e.ref)&&(n.current&&n.current!==e.__e||U(n,null,t)),null!=(n=e.__c)){if(n.componentWillUnmount)try{n.componentWillUnmount()}catch(e){i.__e(e,t)}n.base=n.__P=null}if(n=e.__k)for(o=0;o<n.length;o++)n[o]&&F(n[o],t,"function"!=typeof e.type)
r||null==e.__e||m(e.__e),e.__e=e.__d=void 0}function M(e,t,r){return this.constructor(e,r)}function D(e,t,r){var o,s,a
i.__&&i.__(e,t),s=(o="function"==typeof r)?null:r&&r.__k||t.__k,a=[],I(t,e=(!o&&r||t).__k=g(b,null,[e]),s||p,p,void 0!==t.ownerSVGElement,!o&&r?[r]:s?null:t.firstChild?n.call(t.childNodes):null,a,!o&&r?r:s?s.__e:t.firstChild,o),R(a,e)}function H(e,t){D(e,t,H)}function B(e,t,r){var i,o,s,a=f({},e.props)
for(s in t)"key"==s?i=t[s]:"ref"==s?o=t[s]:a[s]=t[s]
return arguments.length>2&&(a.children=arguments.length>3?n.call(arguments,2):r),v(e.type,a,i||e.key,o||e.ref,null)}function Z(e,t){var r={__c:t="__cC"+u++,__:e,Consumer:function(e,t){return e.children(t)},Provider:function(e){var r,n
return this.getChildContext||(r=[],(n={})[t]=this,this.getChildContext=function(){return n},this.shouldComponentUpdate=function(e){this.props.value!==e.value&&r.some(x)},this.sub=function(e){r.push(e)
var t=e.componentWillUnmount
e.componentWillUnmount=function(){r.splice(r.indexOf(e),1),t&&t.call(e)}}),e.children}}
return r.Provider.__=r.Consumer.contextType=r}n=h.slice,i={__e:function(e,t){for(var r,n,i;t=t.__;)if((r=t.__c)&&!r.__)try{if((n=r.constructor)&&null!=n.getDerivedStateFromError&&(r.setState(n.getDerivedStateFromError(e)),i=r.__d),null!=r.componentDidCatch&&(r.componentDidCatch(e),i=r.__d),i)return r.__E=r}catch(t){e=t}throw e}},o=0,s=function(e){return null!=e&&void 0===e.constructor},w.prototype.setState=function(e,t){var r
r=null!=this.__s&&this.__s!==this.state?this.__s:this.__s=f({},this.state),"function"==typeof e&&(e=e(f({},r),this.props)),e&&f(r,e),null!=e&&this.__v&&(t&&this.__h.push(t),x(this))},w.prototype.forceUpdate=function(e){this.__v&&(this.__e=!0,e&&this.__h.push(e),x(this))},w.prototype.render=b,a=[],l="function"==typeof Promise?Promise.prototype.then.bind(Promise.resolve()):setTimeout,P.__r=0,u=0},9077:(e,t,r)=>{"use strict"
r.r(t),r.d(t,{animateFill:()=>re,createSingleton:()=>Q,default:()=>ue,delegate:()=>te,followCursor:()=>se,hideAll:()=>Y,inlinePositioning:()=>ae,roundArrow:()=>o,sticky:()=>le})
var n=r(2152),i=r(175),o='<svg width="16" height="6" xmlns="http://www.w3.org/2000/svg"><path d="M0 6s1.796-.013 4.67-3.615C5.851.9 6.93.006 8 0c1.07-.006 2.148.887 3.343 2.385C14.233 6.005 16 6 16 6H0z"></svg>',s="tippy-content",a="tippy-backdrop",l="tippy-arrow",c="tippy-svg-arrow",u={passive:!0,capture:!0},p=function(){return document.body}
function h(e,t,r){if(Array.isArray(e)){var n=e[t]
return null==n?Array.isArray(r)?r[t]:r:n}return e}function d(e,t){var r={}.toString.call(e)
return 0===r.indexOf("[object")&&r.indexOf(t+"]")>-1}function f(e,t){return"function"==typeof e?e.apply(void 0,t):e}function m(e,t){return 0===t?e:function(n){clearTimeout(r),r=setTimeout((function(){e(n)}),t)}
var r}function g(e,t){var r=Object.assign({},e)
return t.forEach((function(e){delete r[e]})),r}function v(e){return[].concat(e)}function y(e,t){-1===e.indexOf(t)&&e.push(t)}function b(e){return e.split("-")[0]}function w(e){return[].slice.call(e)}function k(e){return Object.keys(e).reduce((function(t,r){return void 0!==e[r]&&(t[r]=e[r]),t}),{})}function _(){return document.createElement("div")}function x(e){return["Element","Fragment"].some((function(t){return d(e,t)}))}function P(e){return d(e,"MouseEvent")}function S(e){return!(!e||!e._tippy||e._tippy.reference!==e)}function E(e,t){e.forEach((function(e){e&&(e.style.transitionDuration=t+"ms")}))}function O(e,t){e.forEach((function(e){e&&e.setAttribute("data-state",t)}))}function A(e){var t,r=v(e)[0]
return null!=r&&null!=(t=r.ownerDocument)&&t.body?r.ownerDocument:document}function C(e,t,r){var n=t+"EventListener";["transitionend","webkitTransitionEnd"].forEach((function(t){e[n](t,r)}))}function T(e,t){for(var r=t;r;){var n
if(e.contains(r))return!0
r=null==r.getRootNode||null==(n=r.getRootNode())?void 0:n.host}return!1}var L={isTouch:!1},j=0
function I(){L.isTouch||(L.isTouch=!0,window.performance&&document.addEventListener("mousemove",R))}function R(){var e=performance.now()
e-j<20&&(L.isTouch=!1,document.removeEventListener("mousemove",R)),j=e}function N(){var e=document.activeElement
if(S(e)){var t=e._tippy
e.blur&&!t.state.isVisible&&e.blur()}}var U=!("undefined"==typeof window||"undefined"==typeof document||!window.msCrypto),F=Object.assign({appendTo:p,aria:{content:"auto",expanded:"auto"},delay:0,duration:[300,250],getReferenceClientRect:null,hideOnClick:!0,ignoreAttributes:!1,interactive:!1,interactiveBorder:2,interactiveDebounce:0,moveTransition:"",offset:[0,10],onAfterUpdate:function(){},onBeforeUpdate:function(){},onCreate:function(){},onDestroy:function(){},onHidden:function(){},onHide:function(){},onMount:function(){},onShow:function(){},onShown:function(){},onTrigger:function(){},onUntrigger:function(){},onClickOutside:function(){},placement:"top",plugins:[],popperOptions:{},render:null,showOnCreate:!1,touch:!0,trigger:"mouseenter focus",triggerTarget:null},{animateFill:!1,followCursor:!1,inlinePositioning:!1,sticky:!1},{allowHTML:!1,animation:"fade",arrow:!0,content:"",inertia:!1,maxWidth:350,role:"tooltip",theme:"",zIndex:9999}),M=Object.keys(F)
function D(e){var t=(e.plugins||[]).reduce((function(t,r){var n,i=r.name,o=r.defaultValue
return i&&(t[i]=void 0!==e[i]?e[i]:null!=(n=F[i])?n:o),t}),{})
return Object.assign({},e,t)}function H(e,t){var r=Object.assign({},t,{content:f(t.content,[e])},t.ignoreAttributes?{}:function(e,t){return(t?Object.keys(D(Object.assign({},F,{plugins:t}))):M).reduce((function(t,r){var n=(e.getAttribute("data-tippy-"+r)||"").trim()
if(!n)return t
if("content"===r)t[r]=n
else try{t[r]=JSON.parse(n)}catch(e){t[r]=n}return t}),{})}(e,t.plugins))
return r.aria=Object.assign({},F.aria,r.aria),r.aria={expanded:"auto"===r.aria.expanded?t.interactive:r.aria.expanded,content:"auto"===r.aria.content?t.interactive?null:"describedby":r.aria.content},r}function B(e,t){e.innerHTML=t}function Z(e){var t=_()
return!0===e?t.className=l:(t.className=c,x(e)?t.appendChild(e):B(t,e)),t}function V(e,t){x(t.content)?(B(e,""),e.appendChild(t.content)):"function"!=typeof t.content&&(t.allowHTML?B(e,t.content):e.textContent=t.content)}function q(e){var t=e.firstElementChild,r=w(t.children)
return{box:t,content:r.find((function(e){return e.classList.contains(s)})),arrow:r.find((function(e){return e.classList.contains(l)||e.classList.contains(c)})),backdrop:r.find((function(e){return e.classList.contains(a)}))}}function $(e){var t=_(),r=_()
r.className="tippy-box",r.setAttribute("data-state","hidden"),r.setAttribute("tabindex","-1")
var n=_()
function i(r,n){var i=q(t),o=i.box,s=i.content,a=i.arrow
n.theme?o.setAttribute("data-theme",n.theme):o.removeAttribute("data-theme"),"string"==typeof n.animation?o.setAttribute("data-animation",n.animation):o.removeAttribute("data-animation"),n.inertia?o.setAttribute("data-inertia",""):o.removeAttribute("data-inertia"),o.style.maxWidth="number"==typeof n.maxWidth?n.maxWidth+"px":n.maxWidth,n.role?o.setAttribute("role",n.role):o.removeAttribute("role"),r.content===n.content&&r.allowHTML===n.allowHTML||V(s,e.props),n.arrow?a?r.arrow!==n.arrow&&(o.removeChild(a),o.appendChild(Z(n.arrow))):o.appendChild(Z(n.arrow)):a&&o.removeChild(a)}return n.className=s,n.setAttribute("data-state","hidden"),V(n,e.props),t.appendChild(r),r.appendChild(n),i(e.props,e.props),{popper:t,onUpdate:i}}$.$$tippy=!0
var z=1,W=[],K=[]
function X(e,t){var r,i,o,s,a,l,c,d,g=H(e,Object.assign({},F,D(k(t)))),x=!1,S=!1,j=!1,I=!1,R=[],N=m(we,g.interactiveDebounce),M=z++,B=(d=g.plugins).filter((function(e,t){return d.indexOf(e)===t})),Z={id:M,reference:e,popper:_(),popperInstance:null,props:g,state:{isEnabled:!0,isVisible:!1,isDestroyed:!1,isMounted:!1,isShown:!1},plugins:B,clearDelayTimeouts:function(){clearTimeout(r),clearTimeout(i),cancelAnimationFrame(o)},setProps:function(t){if(!Z.state.isDestroyed){se("onBeforeUpdate",[Z,t]),ye()
var r=Z.props,n=H(e,Object.assign({},r,k(t),{ignoreAttributes:!0}))
Z.props=n,ve(),r.interactiveDebounce!==n.interactiveDebounce&&(ce(),N=m(we,n.interactiveDebounce)),r.triggerTarget&&!n.triggerTarget?v(r.triggerTarget).forEach((function(e){e.removeAttribute("aria-expanded")})):n.triggerTarget&&e.removeAttribute("aria-expanded"),le(),oe(),X&&X(r,n),Z.popperInstance&&(Pe(),Ee().forEach((function(e){requestAnimationFrame(e._tippy.popperInstance.forceUpdate)}))),se("onAfterUpdate",[Z,t])}},setContent:function(e){Z.setProps({content:e})},show:function(){var e=Z.state.isVisible,t=Z.state.isDestroyed,r=!Z.state.isEnabled,n=L.isTouch&&!Z.props.touch,i=h(Z.props.duration,0,F.duration)
if(!(e||t||r||n||te().hasAttribute("disabled")||(se("onShow",[Z],!1),!1===Z.props.onShow(Z)))){if(Z.state.isVisible=!0,ee()&&($.style.visibility="visible"),oe(),de(),Z.state.isMounted||($.style.transition="none"),ee()){var o=ne()
E([o.box,o.content],0)}var s,a,c
l=function(){var e
if(Z.state.isVisible&&!I){if(I=!0,$.offsetHeight,$.style.transition=Z.props.moveTransition,ee()&&Z.props.animation){var t=ne(),r=t.box,n=t.content
E([r,n],i),O([r,n],"visible")}ae(),le(),y(K,Z),null==(e=Z.popperInstance)||e.forceUpdate(),se("onMount",[Z]),Z.props.animation&&ee()&&function(e,t){me(e,(function(){Z.state.isShown=!0,se("onShown",[Z])}))}(i)}},a=Z.props.appendTo,c=te(),(s=Z.props.interactive&&a===p||"parent"===a?c.parentNode:f(a,[c])).contains($)||s.appendChild($),Z.state.isMounted=!0,Pe()}},hide:function(){var e=!Z.state.isVisible,t=Z.state.isDestroyed,r=!Z.state.isEnabled,n=h(Z.props.duration,1,F.duration)
if(!(e||t||r)&&(se("onHide",[Z],!1),!1!==Z.props.onHide(Z))){if(Z.state.isVisible=!1,Z.state.isShown=!1,I=!1,x=!1,ee()&&($.style.visibility="hidden"),ce(),fe(),oe(!0),ee()){var i=ne(),o=i.box,s=i.content
Z.props.animation&&(E([o,s],n),O([o,s],"hidden"))}ae(),le(),Z.props.animation?ee()&&function(e,t){me(e,(function(){!Z.state.isVisible&&$.parentNode&&$.parentNode.contains($)&&t()}))}(n,Z.unmount):Z.unmount()}},hideWithInteractivity:function(e){re().addEventListener("mousemove",N),y(W,N),N(e)},enable:function(){Z.state.isEnabled=!0},disable:function(){Z.hide(),Z.state.isEnabled=!1},unmount:function(){Z.state.isVisible&&Z.hide(),Z.state.isMounted&&(Se(),Ee().forEach((function(e){e._tippy.unmount()})),$.parentNode&&$.parentNode.removeChild($),K=K.filter((function(e){return e!==Z})),Z.state.isMounted=!1,se("onHidden",[Z]))},destroy:function(){Z.state.isDestroyed||(Z.clearDelayTimeouts(),Z.unmount(),ye(),delete e._tippy,Z.state.isDestroyed=!0,se("onDestroy",[Z]))}}
if(!g.render)return Z
var V=g.render(Z),$=V.popper,X=V.onUpdate
$.setAttribute("data-tippy-root",""),$.id="tippy-"+Z.id,Z.popper=$,e._tippy=Z,$._tippy=Z
var G=B.map((function(e){return e.fn(Z)})),Y=e.hasAttribute("aria-expanded")
return ve(),le(),oe(),se("onCreate",[Z]),g.showOnCreate&&Oe(),$.addEventListener("mouseenter",(function(){Z.props.interactive&&Z.state.isVisible&&Z.clearDelayTimeouts()})),$.addEventListener("mouseleave",(function(){Z.props.interactive&&Z.props.trigger.indexOf("mouseenter")>=0&&re().addEventListener("mousemove",N)})),Z
function J(){var e=Z.props.touch
return Array.isArray(e)?e:[e,0]}function Q(){return"hold"===J()[0]}function ee(){var e
return!(null==(e=Z.props.render)||!e.$$tippy)}function te(){return c||e}function re(){var e=te().parentNode
return e?A(e):document}function ne(){return q($)}function ie(e){return Z.state.isMounted&&!Z.state.isVisible||L.isTouch||s&&"focus"===s.type?0:h(Z.props.delay,e?0:1,F.delay)}function oe(e){void 0===e&&(e=!1),$.style.pointerEvents=Z.props.interactive&&!e?"":"none",$.style.zIndex=""+Z.props.zIndex}function se(e,t,r){var n
void 0===r&&(r=!0),G.forEach((function(r){r[e]&&r[e].apply(r,t)})),r&&(n=Z.props)[e].apply(n,t)}function ae(){var t=Z.props.aria
if(t.content){var r="aria-"+t.content,n=$.id
v(Z.props.triggerTarget||e).forEach((function(e){var t=e.getAttribute(r)
if(Z.state.isVisible)e.setAttribute(r,t?t+" "+n:n)
else{var i=t&&t.replace(n,"").trim()
i?e.setAttribute(r,i):e.removeAttribute(r)}}))}}function le(){!Y&&Z.props.aria.expanded&&v(Z.props.triggerTarget||e).forEach((function(e){Z.props.interactive?e.setAttribute("aria-expanded",Z.state.isVisible&&e===te()?"true":"false"):e.removeAttribute("aria-expanded")}))}function ce(){re().removeEventListener("mousemove",N),W=W.filter((function(e){return e!==N}))}function ue(t){if(!L.isTouch||!j&&"mousedown"!==t.type){var r=t.composedPath&&t.composedPath()[0]||t.target
if(!Z.props.interactive||!T($,r)){if(v(Z.props.triggerTarget||e).some((function(e){return T(e,r)}))){if(L.isTouch)return
if(Z.state.isVisible&&Z.props.trigger.indexOf("click")>=0)return}else se("onClickOutside",[Z,t])
!0===Z.props.hideOnClick&&(Z.clearDelayTimeouts(),Z.hide(),S=!0,setTimeout((function(){S=!1})),Z.state.isMounted||fe())}}}function pe(){j=!0}function he(){j=!1}function de(){var e=re()
e.addEventListener("mousedown",ue,!0),e.addEventListener("touchend",ue,u),e.addEventListener("touchstart",he,u),e.addEventListener("touchmove",pe,u)}function fe(){var e=re()
e.removeEventListener("mousedown",ue,!0),e.removeEventListener("touchend",ue,u),e.removeEventListener("touchstart",he,u),e.removeEventListener("touchmove",pe,u)}function me(e,t){var r=ne().box
function n(e){e.target===r&&(C(r,"remove",n),t())}if(0===e)return t()
C(r,"remove",a),C(r,"add",n),a=n}function ge(t,r,n){void 0===n&&(n=!1),v(Z.props.triggerTarget||e).forEach((function(e){e.addEventListener(t,r,n),R.push({node:e,eventType:t,handler:r,options:n})}))}function ve(){var e
Q()&&(ge("touchstart",be,{passive:!0}),ge("touchend",ke,{passive:!0})),(e=Z.props.trigger,e.split(/\s+/).filter(Boolean)).forEach((function(e){if("manual"!==e)switch(ge(e,be),e){case"mouseenter":ge("mouseleave",ke)
break
case"focus":ge(U?"focusout":"blur",_e)
break
case"focusin":ge("focusout",_e)}}))}function ye(){R.forEach((function(e){var t=e.node,r=e.eventType,n=e.handler,i=e.options
t.removeEventListener(r,n,i)})),R=[]}function be(e){var t,r=!1
if(Z.state.isEnabled&&!xe(e)&&!S){var n="focus"===(null==(t=s)?void 0:t.type)
s=e,c=e.currentTarget,le(),!Z.state.isVisible&&P(e)&&W.forEach((function(t){return t(e)})),"click"===e.type&&(Z.props.trigger.indexOf("mouseenter")<0||x)&&!1!==Z.props.hideOnClick&&Z.state.isVisible?r=!0:Oe(e),"click"===e.type&&(x=!r),r&&!n&&Ae(e)}}function we(e){var t=e.target,r=te().contains(t)||$.contains(t)
if("mousemove"!==e.type||!r){var n=Ee().concat($).map((function(e){var t,r=null==(t=e._tippy.popperInstance)?void 0:t.state
return r?{popperRect:e.getBoundingClientRect(),popperState:r,props:g}:null})).filter(Boolean);(function(e,t){var r=t.clientX,n=t.clientY
return e.every((function(e){var t=e.popperRect,i=e.popperState,o=e.props.interactiveBorder,s=b(i.placement),a=i.modifiersData.offset
if(!a)return!0
var l="bottom"===s?a.top.y:0,c="top"===s?a.bottom.y:0,u="right"===s?a.left.x:0,p="left"===s?a.right.x:0,h=t.top-n+l>o,d=n-t.bottom-c>o,f=t.left-r+u>o,m=r-t.right-p>o
return h||d||f||m}))})(n,e)&&(ce(),Ae(e))}}function ke(e){xe(e)||Z.props.trigger.indexOf("click")>=0&&x||(Z.props.interactive?Z.hideWithInteractivity(e):Ae(e))}function _e(e){Z.props.trigger.indexOf("focusin")<0&&e.target!==te()||Z.props.interactive&&e.relatedTarget&&$.contains(e.relatedTarget)||Ae(e)}function xe(e){return!!L.isTouch&&Q()!==e.type.indexOf("touch")>=0}function Pe(){Se()
var t=Z.props,r=t.popperOptions,i=t.placement,o=t.offset,s=t.getReferenceClientRect,a=t.moveTransition,c=ee()?q($).arrow:null,u=s?{getBoundingClientRect:s,contextElement:s.contextElement||te()}:e,p=[{name:"offset",options:{offset:o}},{name:"preventOverflow",options:{padding:{top:2,bottom:2,left:5,right:5}}},{name:"flip",options:{padding:5}},{name:"computeStyles",options:{adaptive:!a}},{name:"$$tippy",enabled:!0,phase:"beforeWrite",requires:["computeStyles"],fn:function(e){var t=e.state
if(ee()){var r=ne().box;["placement","reference-hidden","escaped"].forEach((function(e){"placement"===e?r.setAttribute("data-placement",t.placement):t.attributes.popper["data-popper-"+e]?r.setAttribute("data-"+e,""):r.removeAttribute("data-"+e)})),t.attributes.popper={}}}}]
ee()&&c&&p.push({name:"arrow",options:{element:c,padding:3}}),p.push.apply(p,(null==r?void 0:r.modifiers)||[]),Z.popperInstance=(0,n.fi)(u,$,Object.assign({},r,{placement:i,onFirstUpdate:l,modifiers:p}))}function Se(){Z.popperInstance&&(Z.popperInstance.destroy(),Z.popperInstance=null)}function Ee(){return w($.querySelectorAll("[data-tippy-root]"))}function Oe(e){Z.clearDelayTimeouts(),e&&se("onTrigger",[Z,e]),de()
var t=ie(!0),n=J(),i=n[0],o=n[1]
L.isTouch&&"hold"===i&&o&&(t=o),t?r=setTimeout((function(){Z.show()}),t):Z.show()}function Ae(e){if(Z.clearDelayTimeouts(),se("onUntrigger",[Z,e]),Z.state.isVisible){if(!(Z.props.trigger.indexOf("mouseenter")>=0&&Z.props.trigger.indexOf("click")>=0&&["mouseleave","mousemove"].indexOf(e.type)>=0&&x)){var t=ie(!1)
t?i=setTimeout((function(){Z.state.isVisible&&Z.hide()}),t):o=requestAnimationFrame((function(){Z.hide()}))}}else fe()}}function G(e,t){void 0===t&&(t={})
var r=F.plugins.concat(t.plugins||[])
document.addEventListener("touchstart",I,u),window.addEventListener("blur",N)
var n,i=Object.assign({},t,{plugins:r}),o=(n=e,x(n)?[n]:function(e){return d(e,"NodeList")}(n)?w(n):Array.isArray(n)?n:w(document.querySelectorAll(n))).reduce((function(e,t){var r=t&&X(t,i)
return r&&e.push(r),e}),[])
return x(e)?o[0]:o}G.defaultProps=F,G.setDefaultProps=function(e){Object.keys(e).forEach((function(t){F[t]=e[t]}))},G.currentInput=L
var Y=function(e){var t=void 0===e?{}:e,r=t.exclude,n=t.duration
K.forEach((function(e){var t=!1
if(r&&(t=S(r)?e.reference===r:e.popper===r.popper),!t){var i=e.props.duration
e.setProps({duration:n}),e.hide(),e.state.isDestroyed||e.setProps({duration:i})}}))},J=Object.assign({},i.Z,{effect:function(e){var t=e.state,r={popper:{position:t.options.strategy,left:"0",top:"0",margin:"0"},arrow:{position:"absolute"},reference:{}}
Object.assign(t.elements.popper.style,r.popper),t.styles=r,t.elements.arrow&&Object.assign(t.elements.arrow.style,r.arrow)}}),Q=function(e,t){var r
void 0===t&&(t={})
var n,i=e,o=[],s=[],a=t.overrides,l=[],c=!1
function u(){s=i.map((function(e){return v(e.props.triggerTarget||e.reference)})).reduce((function(e,t){return e.concat(t)}),[])}function p(){o=i.map((function(e){return e.reference}))}function h(e){i.forEach((function(t){e?t.enable():t.disable()}))}function d(e){return i.map((function(t){var r=t.setProps
return t.setProps=function(i){r(i),t.reference===n&&e.setProps(i)},function(){t.setProps=r}}))}function f(e,t){var r=s.indexOf(t)
if(t!==n){n=t
var l=(a||[]).concat("content").reduce((function(e,t){return e[t]=i[r].props[t],e}),{})
e.setProps(Object.assign({},l,{getReferenceClientRect:"function"==typeof l.getReferenceClientRect?l.getReferenceClientRect:function(){var e
return null==(e=o[r])?void 0:e.getBoundingClientRect()}}))}}h(!1),p(),u()
var m={fn:function(){return{onDestroy:function(){h(!0)},onHidden:function(){n=null},onClickOutside:function(e){e.props.showOnCreate&&!c&&(c=!0,n=null)},onShow:function(e){e.props.showOnCreate&&!c&&(c=!0,f(e,o[0]))},onTrigger:function(e,t){f(e,t.currentTarget)}}}},y=G(_(),Object.assign({},g(t,["overrides"]),{plugins:[m].concat(t.plugins||[]),triggerTarget:s,popperOptions:Object.assign({},t.popperOptions,{modifiers:[].concat((null==(r=t.popperOptions)?void 0:r.modifiers)||[],[J])})})),b=y.show
y.show=function(e){if(b(),!n&&null==e)return f(y,o[0])
if(!n||null!=e){if("number"==typeof e)return o[e]&&f(y,o[e])
if(i.indexOf(e)>=0){var t=e.reference
return f(y,t)}return o.indexOf(e)>=0?f(y,e):void 0}},y.showNext=function(){var e=o[0]
if(!n)return y.show(0)
var t=o.indexOf(n)
y.show(o[t+1]||e)},y.showPrevious=function(){var e=o[o.length-1]
if(!n)return y.show(e)
var t=o.indexOf(n),r=o[t-1]||e
y.show(r)}
var w=y.setProps
return y.setProps=function(e){a=e.overrides||a,w(e)},y.setInstances=function(e){h(!0),l.forEach((function(e){return e()})),i=e,h(!1),p(),u(),l=d(y),y.setProps({triggerTarget:s})},l=d(y),y},ee={mouseover:"mouseenter",focusin:"focus",click:"click"}
function te(e,t){var r=[],n=[],i=!1,o=t.target,s=g(t,["target"]),a=Object.assign({},s,{trigger:"manual",touch:!1}),l=Object.assign({touch:F.touch},s,{showOnCreate:!0}),c=G(e,a)
function p(e){if(e.target&&!i){var r=e.target.closest(o)
if(r){var s=r.getAttribute("data-tippy-trigger")||t.trigger||F.trigger
if(!r._tippy&&!("touchstart"===e.type&&"boolean"==typeof l.touch||"touchstart"!==e.type&&s.indexOf(ee[e.type])<0)){var a=G(r,l)
a&&(n=n.concat(a))}}}}function h(e,t,n,i){void 0===i&&(i=!1),e.addEventListener(t,n,i),r.push({node:e,eventType:t,handler:n,options:i})}return v(c).forEach((function(e){var t=e.destroy,o=e.enable,s=e.disable
e.destroy=function(e){void 0===e&&(e=!0),e&&n.forEach((function(e){e.destroy()})),n=[],r.forEach((function(e){var t=e.node,r=e.eventType,n=e.handler,i=e.options
t.removeEventListener(r,n,i)})),r=[],t()},e.enable=function(){o(),n.forEach((function(e){return e.enable()})),i=!1},e.disable=function(){s(),n.forEach((function(e){return e.disable()})),i=!0},function(e){var t=e.reference
h(t,"touchstart",p,u),h(t,"mouseover",p),h(t,"focusin",p),h(t,"click",p)}(e)})),c}var re={name:"animateFill",defaultValue:!1,fn:function(e){var t
if(null==(t=e.props.render)||!t.$$tippy)return{}
var r=q(e.popper),n=r.box,i=r.content,o=e.props.animateFill?function(){var e=_()
return e.className=a,O([e],"hidden"),e}():null
return{onCreate:function(){o&&(n.insertBefore(o,n.firstElementChild),n.setAttribute("data-animatefill",""),n.style.overflow="hidden",e.setProps({arrow:!1,animation:"shift-away"}))},onMount:function(){if(o){var e=n.style.transitionDuration,t=Number(e.replace("ms",""))
i.style.transitionDelay=Math.round(t/10)+"ms",o.style.transitionDuration=e,O([o],"visible")}},onShow:function(){o&&(o.style.transitionDuration="0ms")},onHide:function(){o&&O([o],"hidden")}}}},ne={clientX:0,clientY:0},ie=[]
function oe(e){var t=e.clientX,r=e.clientY
ne={clientX:t,clientY:r}}var se={name:"followCursor",defaultValue:!1,fn:function(e){var t=e.reference,r=A(e.props.triggerTarget||t),n=!1,i=!1,o=!0,s=e.props
function a(){return"initial"===e.props.followCursor&&e.state.isVisible}function l(){r.addEventListener("mousemove",p)}function c(){r.removeEventListener("mousemove",p)}function u(){n=!0,e.setProps({getReferenceClientRect:null}),n=!1}function p(r){var n=!r.target||t.contains(r.target),i=e.props.followCursor,o=r.clientX,s=r.clientY,a=t.getBoundingClientRect(),l=o-a.left,c=s-a.top
!n&&e.props.interactive||e.setProps({getReferenceClientRect:function(){var e=t.getBoundingClientRect(),r=o,n=s
"initial"===i&&(r=e.left+l,n=e.top+c)
var a="horizontal"===i?e.top:n,u="vertical"===i?e.right:r,p="horizontal"===i?e.bottom:n,h="vertical"===i?e.left:r
return{width:u-h,height:p-a,top:a,right:u,bottom:p,left:h}}})}function h(){e.props.followCursor&&(ie.push({instance:e,doc:r}),function(e){e.addEventListener("mousemove",oe)}(r))}function d(){0===(ie=ie.filter((function(t){return t.instance!==e}))).filter((function(e){return e.doc===r})).length&&function(e){e.removeEventListener("mousemove",oe)}(r)}return{onCreate:h,onDestroy:d,onBeforeUpdate:function(){s=e.props},onAfterUpdate:function(t,r){var o=r.followCursor
n||void 0!==o&&s.followCursor!==o&&(d(),o?(h(),!e.state.isMounted||i||a()||l()):(c(),u()))},onMount:function(){e.props.followCursor&&!i&&(o&&(p(ne),o=!1),a()||l())},onTrigger:function(e,t){P(t)&&(ne={clientX:t.clientX,clientY:t.clientY}),i="focus"===t.type},onHidden:function(){e.props.followCursor&&(u(),c(),o=!0)}}}},ae={name:"inlinePositioning",defaultValue:!1,fn:function(e){var t,r=e.reference,n=-1,i=!1,o=[],s={name:"tippyInlinePositioning",enabled:!0,phase:"afterWrite",fn:function(i){var s=i.state
e.props.inlinePositioning&&(-1!==o.indexOf(s.placement)&&(o=[]),t!==s.placement&&-1===o.indexOf(s.placement)&&(o.push(s.placement),e.setProps({getReferenceClientRect:function(){return function(e){return function(e,t,r,n){if(r.length<2||null===e)return t
if(2===r.length&&n>=0&&r[0].left>r[1].right)return r[n]||t
switch(e){case"top":case"bottom":var i=r[0],o=r[r.length-1],s="top"===e,a=i.top,l=o.bottom,c=s?i.left:o.left,u=s?i.right:o.right
return{top:a,bottom:l,left:c,right:u,width:u-c,height:l-a}
case"left":case"right":var p=Math.min.apply(Math,r.map((function(e){return e.left}))),h=Math.max.apply(Math,r.map((function(e){return e.right}))),d=r.filter((function(t){return"left"===e?t.left===p:t.right===h})),f=d[0].top,m=d[d.length-1].bottom
return{top:f,bottom:m,left:p,right:h,width:h-p,height:m-f}
default:return t}}(b(e),r.getBoundingClientRect(),w(r.getClientRects()),n)}(s.placement)}})),t=s.placement)}}
function a(){var t
i||(t=function(e,t){var r
return{popperOptions:Object.assign({},e.popperOptions,{modifiers:[].concat(((null==(r=e.popperOptions)?void 0:r.modifiers)||[]).filter((function(e){return e.name!==t.name})),[t])})}}(e.props,s),i=!0,e.setProps(t),i=!1)}return{onCreate:a,onAfterUpdate:a,onTrigger:function(t,r){if(P(r)){var i=w(e.reference.getClientRects()),o=i.find((function(e){return e.left-2<=r.clientX&&e.right+2>=r.clientX&&e.top-2<=r.clientY&&e.bottom+2>=r.clientY})),s=i.indexOf(o)
n=s>-1?s:n}},onHidden:function(){n=-1}}}},le={name:"sticky",defaultValue:!1,fn:function(e){var t=e.reference,r=e.popper
function n(t){return!0===e.props.sticky||e.props.sticky===t}var i=null,o=null
function s(){var a=n("reference")?(e.popperInstance?e.popperInstance.state.elements.reference:t).getBoundingClientRect():null,l=n("popper")?r.getBoundingClientRect():null;(a&&ce(i,a)||l&&ce(o,l))&&e.popperInstance&&e.popperInstance.update(),i=a,o=l,e.state.isMounted&&requestAnimationFrame(s)}return{onMount:function(){e.props.sticky&&s()}}}}
function ce(e,t){return!e||!t||e.top!==t.top||e.right!==t.right||e.bottom!==t.bottom||e.left!==t.left}G.setDefaultProps({render:$})
const ue=G},9423:(e,t,r)=>{var n=r(1384)
e.exports=n},4290:(e,t,r)=>{var n=r(7581)
e.exports=n},8493:(e,t,r)=>{var n=r(2028)
e.exports=n},7150:(e,t,r)=>{var n=r(4290),i=r(9748),o=r(8493),s=r(9423),a=r(976),l=r(6459)
e.exports={diff:n,patch:i,h:o,create:s,VNode:a,VText:l}},9748:(e,t,r)=>{var n=r(3888)
e.exports=n},905:(e,t,r)=>{var n=r(7819),i=r(5731)
function o(e,t,r,n){if(n){var o=n[t]
if(i(o))o.unhook&&o.unhook(e,t,r)
else if("attributes"===t)for(var s in o)e.removeAttribute(s)
else if("style"===t)for(var a in o)e.style[a]=""
else e[t]="string"==typeof o?"":null}}function s(e,t,r,i,o){var s=r?r[i]:void 0
if("attributes"!==i)if(s&&n(s)&&a(s)!==a(o))e[i]=o
else{n(e[i])||(e[i]={})
var l="style"===i?"":void 0
for(var c in o){var u=o[c]
e[i][c]=void 0===u?l:u}}else for(var p in o){var h=o[p]
void 0===h?e.removeAttribute(p):e.setAttribute(p,h)}}function a(e){return Object.getPrototypeOf?Object.getPrototypeOf(e):e.__proto__?e.__proto__:e.constructor?e.constructor.prototype:void 0}e.exports=function(e,t,r){for(var a in t){var l=t[a]
void 0===l?o(e,a,l,r):i(l)?(o(e,a,l,r),l.hook&&l.hook(e,a,r?r[a]:void 0)):n(l)?s(e,0,r,a,l):e[a]=l}}},1384:(e,t,r)=>{var n=r(2957),i=r(905),o=r(5738),s=r(3834),a=r(1506),l=r(9007)
e.exports=function e(t,r){var c=r&&r.document||n,u=r?r.warn:null
if(t=l(t).a,a(t))return t.init()
if(s(t))return c.createTextNode(t.text)
if(!o(t))return u&&u("Item is not a valid virtual dom node",t),null
var p=null===t.namespace?c.createElement(t.tagName):c.createElementNS(t.namespace,t.tagName),h=t.properties
i(p,h)
for(var d=t.children,f=0;f<d.length;f++){var m=e(d[f],r)
m&&p.appendChild(m)}return p}},1311:e=>{var t={}
function r(e,i,o,s,a){if(s=s||{},e){n(o,a,a)&&(s[a]=e)
var l=i.children
if(l)for(var c=e.childNodes,u=0;u<i.children.length;u++){a+=1
var p=l[u]||t,h=a+(p.count||0)
n(o,a,h)&&r(c[u],p,o,s,a),a=h}}return s}function n(e,t,r){if(0===e.length)return!1
for(var n,i,o=0,s=e.length-1;o<=s;){if(i=e[n=(s+o)/2>>0],o===s)return i>=t&&i<=r
if(i<t)o=n+1
else{if(!(i>r))return!0
s=n-1}}return!1}function i(e,t){return e>t?1:-1}e.exports=function(e,t,n,o){return n&&0!==n.length?(n.sort(i),r(e,t,n,o,0)):{}}},8452:(e,t,r)=>{var n=r(905),i=r(1506),o=r(4791),s=r(154)
function a(e,t){"function"==typeof t.destroy&&i(t)&&t.destroy(e)}e.exports=function(e,t,r){var i,l,c=e.type,u=e.vNode,p=e.patch
switch(c){case o.REMOVE:return function(e,t){var r=e.parentNode
return r&&r.removeChild(e),a(e,t),null}(t,u)
case o.INSERT:return function(e,t,r){var n=r.render(t,r)
return e&&e.appendChild(n),e}(t,p,r)
case o.VTEXT:return function(e,t,r,n){var i
if(3===e.nodeType)e.replaceData(0,e.length,r.text),i=e
else{var o=e.parentNode
i=n.render(r,n),o&&i!==e&&o.replaceChild(i,e)}return i}(t,0,p,r)
case o.WIDGET:return function(e,t,r,n){var i,o=s(t,r)
i=o?r.update(t,e)||e:n.render(r,n)
var l=e.parentNode
return l&&i!==e&&l.replaceChild(i,e),o||a(e,t),i}(t,u,p,r)
case o.VNODE:return function(e,t,r,n){var i=e.parentNode,o=n.render(r,n)
return i&&o!==e&&i.replaceChild(o,e),o}(t,0,p,r)
case o.ORDER:return function(e,t){for(var r,n,i,o=e.childNodes,s={},a=0;a<t.removes.length;a++)r=o[(n=t.removes[a]).from],n.key&&(s[n.key]=r),e.removeChild(r)
for(var l=o.length,c=0;c<t.inserts.length;c++)r=s[(i=t.inserts[c]).key],e.insertBefore(r,i.to>=l++?null:o[i.to])}(t,p),t
case o.PROPS:return n(t,p,u.properties),t
case o.THUNK:return i=t,l=r.patch(t,p,r),i&&l&&i!==l&&i.parentNode&&i.parentNode.replaceChild(l,i),l
default:return t}}},3888:(e,t,r)=>{var n=r(2957),i=r(1325),o=r(1384),s=r(1311),a=r(8452)
function l(e,t,r){var i=function(e){var t=[]
for(var r in e)"a"!==r&&t.push(Number(r))
return t}(t)
if(0===i.length)return e
var o=s(e,t.a,i),a=e.ownerDocument
r.document||a===n||(r.document=a)
for(var l=0;l<i.length;l++){var u=i[l]
e=c(e,o[u],t[u],r)}return e}function c(e,t,r,n){if(!t)return e
var o
if(i(r))for(var s=0;s<r.length;s++)o=a(r[s],t,n),t===e&&(e=o)
else o=a(r,t,n),t===e&&(e=o)
return e}e.exports=function e(t,r,n){return(n=n||{}).patch=n.patch&&n.patch!==e?n.patch:l,n.render=n.render||o,n.patch(t,r,n)}},154:(e,t,r)=>{var n=r(1506)
e.exports=function(e,t){return!(!n(e)||!n(t))&&("name"in e&&"name"in t?e.id===t.id:e.init===t.init)}},7774:(e,t,r)=>{"use strict"
var n=r(2612)
function i(e){if(!(this instanceof i))return new i(e)
this.value=e}e.exports=i,i.prototype.hook=function(e,t){n(e)[t.substr(3)]=this.value},i.prototype.unhook=function(e,t){n(e)[t.substr(3)]=void 0}},3302:e=>{"use strict"
function t(e){if(!(this instanceof t))return new t(e)
this.value=e}e.exports=t,t.prototype.hook=function(e,t){e[t]!==this.value&&(e[t]=this.value)}},2028:(e,t,r)=>{"use strict"
var n=r(1325),i=r(976),o=r(6459),s=r(5738),a=r(3834),l=r(1506),c=r(5731),u=r(5242),p=r(4484),h=r(3302),d=r(7774)
function f(e,t,r,i){if("string"==typeof e)t.push(new o(e))
else if("number"==typeof e)t.push(new o(String(e)))
else if(m(e))t.push(e)
else{if(!n(e)){if(null==e)return
throw a={foreignObject:e,parentVnode:{tagName:r,properties:i}},(l=new Error).type="virtual-hyperscript.unexpected.virtual-element",l.message="Unexpected virtual child passed to h().\nExpected a VNode / Vthunk / VWidget / string but:\ngot:\n"+g(a.foreignObject)+".\nThe parent vnode is:\n"+g(a.parentVnode),l.foreignObject=a.foreignObject,l.parentVnode=a.parentVnode,l}for(var s=0;s<e.length;s++)f(e[s],t,r,i)}var a,l}function m(e){return s(e)||a(e)||l(e)||u(e)}function g(e){try{return JSON.stringify(e,null,"    ")}catch(t){return String(e)}}e.exports=function(e,t,r){var o,s,a,l,u,g=[]
return!r&&("string"==typeof(u=t)||n(u)||m(u))&&(r=t,s={}),o=p(e,s=s||t||{}),s.hasOwnProperty("key")&&(a=s.key,s.key=void 0),s.hasOwnProperty("namespace")&&(l=s.namespace,s.namespace=void 0),"INPUT"!==o||l||!s.hasOwnProperty("value")||void 0===s.value||c(s.value)||(s.value=h(s.value)),function(e){for(var t in e)if(e.hasOwnProperty(t)){var r=e[t]
if(c(r))continue
"ev-"===t.substr(0,3)&&(e[t]=d(r))}}(s),null!=r&&f(r,g,o,s),new i(o,s,g,a,l)}},4484:(e,t,r)=>{"use strict"
var n=r(2316),i=/([\.#]?[a-zA-Z0-9\u007F-\uFFFF_:-]+)/,o=/^\.|#/
e.exports=function(e,t){if(!e)return"DIV"
var r,s,a,l,c=!t.hasOwnProperty("id"),u=n(e,i),p=null
for(o.test(u[1])&&(p="DIV"),l=0;l<u.length;l++)(s=u[l])&&(a=s.charAt(0),p?"."===a?(r=r||[]).push(s.substring(1,s.length)):"#"===a&&c&&(t.id=s.substring(1,s.length)):p=s)
return r&&(t.className&&r.push(t.className),t.className=r.join(" ")),t.namespace?p:p.toUpperCase()}},9007:(e,t,r)=>{var n=r(5738),i=r(3834),o=r(1506),s=r(5242)
function a(e,t){var r=e.vnode
if(r||(r=e.vnode=e.render(t)),!(n(r)||i(r)||o(r)))throw new Error("thunk did not return a valid node")
return r}e.exports=function(e,t){var r=e,n=t
return s(t)&&(n=a(t,e)),s(e)&&(r=a(e,null)),{a:r,b:n}}},5242:e=>{e.exports=function(e){return e&&"Thunk"===e.type}},5731:e=>{e.exports=function(e){return e&&("function"==typeof e.hook&&!e.hasOwnProperty("hook")||"function"==typeof e.unhook&&!e.hasOwnProperty("unhook"))}},5738:(e,t,r)=>{var n=r(6717)
e.exports=function(e){return e&&"VirtualNode"===e.type&&e.version===n}},3834:(e,t,r)=>{var n=r(6717)
e.exports=function(e){return e&&"VirtualText"===e.type&&e.version===n}},1506:e=>{e.exports=function(e){return e&&"Widget"===e.type}},6717:e=>{e.exports="2"},976:(e,t,r)=>{var n=r(6717),i=r(5738),o=r(1506),s=r(5242),a=r(5731)
e.exports=u
var l={},c=[]
function u(e,t,r,n,u){this.tagName=e,this.properties=t||l,this.children=r||c,this.key=null!=n?String(n):void 0,this.namespace="string"==typeof u?u:null
var p,h=r&&r.length||0,d=0,f=!1,m=!1,g=!1
for(var v in t)if(t.hasOwnProperty(v)){var y=t[v]
a(y)&&y.unhook&&(p||(p={}),p[v]=y)}for(var b=0;b<h;b++){var w=r[b]
i(w)?(d+=w.count||0,!f&&w.hasWidgets&&(f=!0),!m&&w.hasThunks&&(m=!0),g||!w.hooks&&!w.descendantHooks||(g=!0)):!f&&o(w)?"function"==typeof w.destroy&&(f=!0):!m&&s(w)&&(m=!0)}this.count=h+d,this.hasWidgets=f,this.hasThunks=m,this.hooks=p,this.descendantHooks=g}u.prototype.version=n,u.prototype.type="VirtualNode"},4791:(e,t,r)=>{var n=r(6717)
function i(e,t,r){this.type=Number(e),this.vNode=t,this.patch=r}i.NONE=0,i.VTEXT=1,i.VNODE=2,i.WIDGET=3,i.PROPS=4,i.ORDER=5,i.INSERT=6,i.REMOVE=7,i.THUNK=8,e.exports=i,i.prototype.version=n,i.prototype.type="VirtualPatch"},6459:(e,t,r)=>{var n=r(6717)
function i(e){this.text=String(e)}e.exports=i,i.prototype.version=n,i.prototype.type="VirtualText"},1935:(e,t,r)=>{var n=r(7819),i=r(5731)
function o(e){return Object.getPrototypeOf?Object.getPrototypeOf(e):e.__proto__?e.__proto__:e.constructor?e.constructor.prototype:void 0}e.exports=function e(t,r){var s
for(var a in t){a in r||((s=s||{})[a]=void 0)
var l=t[a],c=r[a]
if(l!==c)if(n(l)&&n(c))if(o(c)!==o(l))(s=s||{})[a]=c
else if(i(c))(s=s||{})[a]=c
else{var u=e(l,c)
u&&((s=s||{})[a]=u)}else(s=s||{})[a]=c}for(var p in r)p in t||((s=s||{})[p]=r[p])
return s}},7581:(e,t,r)=>{var n=r(1325),i=r(4791),o=r(5738),s=r(3834),a=r(1506),l=r(5242),c=r(9007),u=r(1935)
function p(e,t){var r={a:e}
return h(e,t,r,0),r}function h(e,t,r,n){if(e!==t){var c=r[n],p=!1
if(l(e)||l(t))m(e,t,r,n)
else if(null==t)a(e)||(d(e,r,n),c=r[n]),c=b(c,new i(i.REMOVE,e,t))
else if(o(t))if(o(e))if(e.tagName===t.tagName&&e.namespace===t.namespace&&e.key===t.key){var f=u(e.properties,t.properties)
f&&(c=b(c,new i(i.PROPS,e,f))),c=function(e,t,r,n,s){for(var a=e.children,l=function(e,t){var r=y(t),n=r.keys,i=r.free
if(i.length===t.length)return{children:t,moves:null}
var o=y(e),s=o.keys
if(o.free.length===e.length)return{children:t,moves:null}
for(var a=[],l=0,c=i.length,u=0,p=0;p<e.length;p++){var h,d=e[p]
d.key?n.hasOwnProperty(d.key)?(h=n[d.key],a.push(t[h])):(h=p-u++,a.push(null)):l<c?(h=i[l++],a.push(t[h])):(h=p-u++,a.push(null))}for(var f=l>=i.length?t.length:i[l],m=0;m<t.length;m++){var g=t[m]
g.key?s.hasOwnProperty(g.key)||a.push(g):m>=f&&a.push(g)}for(var b,w=a.slice(),k=0,_=[],x=[],P=0;P<t.length;){var S=t[P]
for(b=w[k];null===b&&w.length;)_.push(v(w,k,null)),b=w[k]
b&&b.key===S.key?(k++,P++):S.key?(b&&b.key&&n[b.key]!==P+1?(_.push(v(w,k,b.key)),(b=w[k])&&b.key===S.key?k++:x.push({key:S.key,to:P})):x.push({key:S.key,to:P}),P++):b&&b.key&&_.push(v(w,k,b.key))}for(;k<w.length;)b=w[k],_.push(v(w,k,b&&b.key))
return _.length!==u||x.length?{children:a,moves:{removes:_,inserts:x}}:{children:a,moves:null}}(a,t.children),c=l.children,u=a.length,p=c.length,d=u>p?u:p,f=0;f<d;f++){var m=a[f],g=c[f]
s+=1,m?h(m,g,r,s):g&&(n=b(n,new i(i.INSERT,null,g))),o(m)&&m.count&&(s+=m.count)}return l.moves&&(n=b(n,new i(i.ORDER,e,l.moves))),n}(e,t,r,c,n)}else c=b(c,new i(i.VNODE,e,t)),p=!0
else c=b(c,new i(i.VNODE,e,t)),p=!0
else s(t)?s(e)?e.text!==t.text&&(c=b(c,new i(i.VTEXT,e,t))):(c=b(c,new i(i.VTEXT,e,t)),p=!0):a(t)&&(a(e)||(p=!0),c=b(c,new i(i.WIDGET,e,t)))
c&&(r[n]=c),p&&d(e,r,n)}}function d(e,t,r){g(e,t,r),f(e,t,r)}function f(e,t,r){if(a(e))"function"==typeof e.destroy&&(t[r]=b(t[r],new i(i.REMOVE,e,null)))
else if(o(e)&&(e.hasWidgets||e.hasThunks))for(var n=e.children,s=n.length,c=0;c<s;c++){var u=n[c]
f(u,t,r+=1),o(u)&&u.count&&(r+=u.count)}else l(e)&&m(e,null,t,r)}function m(e,t,r,n){var o=c(e,t),s=p(o.a,o.b);(function(e){for(var t in e)if("a"!==t)return!0
return!1})(s)&&(r[n]=new i(i.THUNK,null,s))}function g(e,t,r){if(o(e)){if(e.hooks&&(t[r]=b(t[r],new i(i.PROPS,e,function(e){var t={}
for(var r in e)t[r]=void 0
return t}(e.hooks)))),e.descendantHooks||e.hasThunks)for(var n=e.children,s=n.length,a=0;a<s;a++){var c=n[a]
g(c,t,r+=1),o(c)&&c.count&&(r+=c.count)}}else l(e)&&m(e,null,t,r)}function v(e,t,r){return e.splice(t,1),{from:t,key:r}}function y(e){for(var t={},r=[],n=e.length,i=0;i<n;i++){var o=e[i]
o.key?t[o.key]=i:r.push(i)}return{keys:t,free:r}}function b(e,t){return e?(n(e)?e.push(t):e=[e,t],e):t}e.exports=p},9698:e=>{"use strict"
function t(e,t){this.text=e=e||"",this.hasWild=~e.indexOf("*"),this.separator=t,this.parts=e.split(t)}t.prototype.match=function(e){var t,r,n=!0,i=this.parts,o=i.length
if("string"==typeof e||e instanceof String)if(this.hasWild||this.text==e){for(r=(e||"").split(this.separator),t=0;n&&t<o;t++)"*"!==i[t]&&(n=t<r.length&&i[t]===r[t])
n=n&&r}else n=!1
else if("function"==typeof e.splice)for(n=[],t=e.length;t--;)this.match(e[t])&&(n[n.length]=e[t])
else if("object"==typeof e)for(var s in n={},e)this.match(s)&&(n[s]=e[s])
return n},e.exports=function(e,r,n){var i=new t(e,n||/[\/\.]/)
return void 0!==r?i.match(r):i}},1325:e=>{var t=Array.isArray,r=Object.prototype.toString
e.exports=t||function(e){return"[object Array]"===r.call(e)}},9229:(e,t,r)=>{var n=r(8223).FilterCSS,i=r(8223).getDefaultWhiteList,o=r(2081),s=new n
function a(e){return e.replace(l,"&lt;").replace(c,"&gt;")}var l=/</g,c=/>/g,u=/"/g,p=/&quot;/g,h=/&#([a-zA-Z0-9]*);?/gim,d=/&colon;?/gim,f=/&newline;?/gim,m=/((j\s*a\s*v\s*a|v\s*b|l\s*i\s*v\s*e)\s*s\s*c\s*r\s*i\s*p\s*t\s*|m\s*o\s*c\s*h\s*a):/gi,g=/e\s*x\s*p\s*r\s*e\s*s\s*s\s*i\s*o\s*n\s*\(.*/gi,v=/u\s*r\s*l\s*\(.*/gi
function y(e){return e.replace(u,"&quot;")}function b(e){return e.replace(p,'"')}function w(e){return e.replace(h,(function(e,t){return"x"===t[0]||"X"===t[0]?String.fromCharCode(parseInt(t.substr(1),16)):String.fromCharCode(parseInt(t,10))}))}function k(e){return e.replace(d,":").replace(f," ")}function _(e){for(var t="",r=0,n=e.length;r<n;r++)t+=e.charCodeAt(r)<32?" ":e.charAt(r)
return o.trim(t)}function x(e){return _(e=k(e=w(e=b(e))))}function P(e){return a(e=y(e))}t.whiteList={a:["target","href","title"],abbr:["title"],address:[],area:["shape","coords","href","alt"],article:[],aside:[],audio:["autoplay","controls","crossorigin","loop","muted","preload","src"],b:[],bdi:["dir"],bdo:["dir"],big:[],blockquote:["cite"],br:[],caption:[],center:[],cite:[],code:[],col:["align","valign","span","width"],colgroup:["align","valign","span","width"],dd:[],del:["datetime"],details:["open"],div:[],dl:[],dt:[],em:[],figcaption:[],figure:[],font:["color","size","face"],footer:[],h1:[],h2:[],h3:[],h4:[],h5:[],h6:[],header:[],hr:[],i:[],img:["src","alt","title","width","height"],ins:["datetime"],li:[],mark:[],nav:[],ol:[],p:[],pre:[],s:[],section:[],small:[],span:[],sub:[],summary:[],sup:[],strong:[],strike:[],table:["width","border","align","valign"],tbody:["align","valign"],td:["width","rowspan","colspan","align","valign"],tfoot:["align","valign"],th:["width","rowspan","colspan","align","valign"],thead:["align","valign"],tr:["rowspan","align","valign"],tt:[],u:[],ul:[],video:["autoplay","controls","crossorigin","loop","muted","playsinline","poster","preload","src","height","width"]},t.getDefaultWhiteList=function(){return{a:["target","href","title"],abbr:["title"],address:[],area:["shape","coords","href","alt"],article:[],aside:[],audio:["autoplay","controls","crossorigin","loop","muted","preload","src"],b:[],bdi:["dir"],bdo:["dir"],big:[],blockquote:["cite"],br:[],caption:[],center:[],cite:[],code:[],col:["align","valign","span","width"],colgroup:["align","valign","span","width"],dd:[],del:["datetime"],details:["open"],div:[],dl:[],dt:[],em:[],figcaption:[],figure:[],font:["color","size","face"],footer:[],h1:[],h2:[],h3:[],h4:[],h5:[],h6:[],header:[],hr:[],i:[],img:["src","alt","title","width","height"],ins:["datetime"],li:[],mark:[],nav:[],ol:[],p:[],pre:[],s:[],section:[],small:[],span:[],sub:[],summary:[],sup:[],strong:[],strike:[],table:["width","border","align","valign"],tbody:["align","valign"],td:["width","rowspan","colspan","align","valign"],tfoot:["align","valign"],th:["width","rowspan","colspan","align","valign"],thead:["align","valign"],tr:["rowspan","align","valign"],tt:[],u:[],ul:[],video:["autoplay","controls","crossorigin","loop","muted","playsinline","poster","preload","src","height","width"]}},t.onTag=function(e,t,r){},t.onIgnoreTag=function(e,t,r){},t.onTagAttr=function(e,t,r){},t.onIgnoreTagAttr=function(e,t,r){},t.safeAttrValue=function(e,t,r,n){if(r=x(r),"href"===t||"src"===t){if("#"===(r=o.trim(r)))return"#"
if("http://"!==r.substr(0,7)&&"https://"!==r.substr(0,8)&&"mailto:"!==r.substr(0,7)&&"tel:"!==r.substr(0,4)&&"data:image/"!==r.substr(0,11)&&"ftp://"!==r.substr(0,6)&&"./"!==r.substr(0,2)&&"../"!==r.substr(0,3)&&"#"!==r[0]&&"/"!==r[0])return""}else if("background"===t){if(m.lastIndex=0,m.test(r))return""}else if("style"===t){if(g.lastIndex=0,g.test(r))return""
if(v.lastIndex=0,v.test(r)&&(m.lastIndex=0,m.test(r)))return""
!1!==n&&(r=(n=n||s).process(r))}return P(r)},t.escapeHtml=a,t.escapeQuote=y,t.unescapeQuote=b,t.escapeHtmlEntities=w,t.escapeDangerHtml5Entities=k,t.clearNonPrintableCharacter=_,t.friendlyAttrValue=x,t.escapeAttrValue=P,t.onIgnoreTagStripAll=function(){return""},t.StripTagBody=function(e,t){"function"!=typeof t&&(t=function(){})
var r=!Array.isArray(e),n=[],i=!1
return{onIgnoreTag:function(s,a,l){if(function(t){return!!r||-1!==o.indexOf(e,t)}(s)){if(l.isClosing){var c="[/removed]",u=l.position+c.length
return n.push([!1!==i?i:l.position,u]),i=!1,c}return i||(i=l.position),"[removed]"}return t(s,a,l)},remove:function(e){var t="",r=0
return o.forEach(n,(function(n){t+=e.slice(r,n[0]),r=n[1]})),t+=e.slice(r)}}},t.stripCommentTag=function(e){for(var t="",r=0;r<e.length;){var n=e.indexOf("\x3c!--",r)
if(-1===n){t+=e.slice(r)
break}t+=e.slice(r,n)
var i=e.indexOf("--\x3e",n)
if(-1===i)break
r=i+3}return t},t.stripBlankChar=function(e){var t=e.split("")
return(t=t.filter((function(e){var t=e.charCodeAt(0)
return!(127===t||t<=31&&10!==t&&13!==t)}))).join("")},t.cssFilter=s,t.getDefaultCSSWhiteList=i},5833:(e,t,r)=>{var n=r(9229),i=r(7794),o=r(7173)
function s(e,t){return new o(t).process(e)}(t=e.exports=s).filterXSS=s,t.FilterXSS=o,function(){for(var e in n)t[e]=n[e]
for(var r in i)t[r]=i[r]}(),"undefined"!=typeof window&&(window.filterXSS=e.exports),"undefined"!=typeof self&&"undefined"!=typeof DedicatedWorkerGlobalScope&&self instanceof DedicatedWorkerGlobalScope&&(self.filterXSS=e.exports)},7794:(e,t,r)=>{var n=r(2081)
function i(e){var t,r=n.spaceIndex(e)
return t=-1===r?e.slice(1,-1):e.slice(1,r+1),"/"===(t=n.trim(t).toLowerCase()).slice(0,1)&&(t=t.slice(1)),"/"===t.slice(-1)&&(t=t.slice(0,-1)),t}function o(e){return"</"===e.slice(0,2)}var s=/[^a-zA-Z0-9\\_:.-]/gim
function a(e,t){for(;t<e.length;t++){var r=e[t]
if(" "!==r)return"="===r?t:-1}}function l(e,t){for(;t<e.length;t++){var r=e[t]
if(" "!==r)return"'"===r||'"'===r?t:-1}}function c(e,t){for(;t>0;t--){var r=e[t]
if(" "!==r)return"="===r?t:-1}}function u(e){return function(e){return'"'===e[0]&&'"'===e[e.length-1]||"'"===e[0]&&"'"===e[e.length-1]}(e)?e.substr(1,e.length-2):e}t.parseTag=function(e,t,r){"use strict"
var n="",s=0,a=!1,l=!1,c=0,u=e.length,p="",h=""
e:for(c=0;c<u;c++){var d=e.charAt(c)
if(!1===a){if("<"===d){a=c
continue}}else if(!1===l){if("<"===d){n+=r(e.slice(s,c)),a=c,s=c
continue}if(">"===d||c===u-1){n+=r(e.slice(s,a)),p=i(h=e.slice(a,c+1)),n+=t(a,n.length,p,h,o(h)),s=c+1,a=!1
continue}if('"'===d||"'"===d)for(var f=1,m=e.charAt(c-f);""===m.trim()||"="===m;){if("="===m){l=d
continue e}m=e.charAt(c-++f)}}else if(d===l){l=!1
continue}}return s<u&&(n+=r(e.substr(s))),n},t.parseAttr=function(e,t){"use strict"
var r=0,i=0,o=[],p=!1,h=e.length
function d(e,r){if(!((e=(e=n.trim(e)).replace(s,"").toLowerCase()).length<1)){var i=t(e,r||"")
i&&o.push(i)}}for(var f=0;f<h;f++){var m,g=e.charAt(f)
if(!1!==p||"="!==g)if(!1===p||f!==i){if(/\s|\n|\t/.test(g)){if(e=e.replace(/\s|\n|\t/g," "),!1===p){if(-1===(m=a(e,f))){d(n.trim(e.slice(r,f))),p=!1,r=f+1
continue}f=m-1
continue}if(-1===(m=c(e,f-1))){d(p,u(n.trim(e.slice(r,f)))),p=!1,r=f+1
continue}}}else{if(-1===(m=e.indexOf(g,f+1)))break
d(p,n.trim(e.slice(i+1,m))),p=!1,r=(f=m)+1}else p=e.slice(r,f),r=f+1,i='"'===e.charAt(r)||"'"===e.charAt(r)?r:l(e,f+1)}return r<e.length&&(!1===p?d(e.slice(r)):d(p,u(n.trim(e.slice(r))))),n.trim(o.join(" "))}},2081:e=>{e.exports={indexOf:function(e,t){var r,n
if(Array.prototype.indexOf)return e.indexOf(t)
for(r=0,n=e.length;r<n;r++)if(e[r]===t)return r
return-1},forEach:function(e,t,r){var n,i
if(Array.prototype.forEach)return e.forEach(t,r)
for(n=0,i=e.length;n<i;n++)t.call(r,e[n],n,e)},trim:function(e){return String.prototype.trim?e.trim():e.replace(/(^\s*)|(\s*$)/g,"")},spaceIndex:function(e){var t=/\s|\n|\t/.exec(e)
return t?t.index:-1}}},7173:(e,t,r)=>{var n=r(8223).FilterCSS,i=r(9229),o=r(7794),s=o.parseTag,a=o.parseAttr,l=r(2081)
function c(e){return null==e}function u(e){(e=function(e){var t={}
for(var r in e)t[r]=e[r]
return t}(e||{})).stripIgnoreTag&&(e.onIgnoreTag&&console.error('Notes: cannot use these two options "stripIgnoreTag" and "onIgnoreTag" at the same time'),e.onIgnoreTag=i.onIgnoreTagStripAll),e.whiteList||e.allowList?e.whiteList=function(e){var t={}
for(var r in e)Array.isArray(e[r])?t[r.toLowerCase()]=e[r].map((function(e){return e.toLowerCase()})):t[r.toLowerCase()]=e[r]
return t}(e.whiteList||e.allowList):e.whiteList=i.whiteList,e.onTag=e.onTag||i.onTag,e.onTagAttr=e.onTagAttr||i.onTagAttr,e.onIgnoreTag=e.onIgnoreTag||i.onIgnoreTag,e.onIgnoreTagAttr=e.onIgnoreTagAttr||i.onIgnoreTagAttr,e.safeAttrValue=e.safeAttrValue||i.safeAttrValue,e.escapeHtml=e.escapeHtml||i.escapeHtml,this.options=e,!1===e.css?this.cssFilter=!1:(e.css=e.css||{},this.cssFilter=new n(e.css))}u.prototype.process=function(e){if(!(e=(e=e||"").toString()))return""
var t=this.options,r=t.whiteList,n=t.onTag,o=t.onIgnoreTag,u=t.onTagAttr,p=t.onIgnoreTagAttr,h=t.safeAttrValue,d=t.escapeHtml,f=this.cssFilter
t.stripBlankChar&&(e=i.stripBlankChar(e)),t.allowCommentTag||(e=i.stripCommentTag(e))
var m=!1
t.stripIgnoreTagBody&&(m=i.StripTagBody(t.stripIgnoreTagBody,o),o=m.onIgnoreTag)
var g=s(e,(function(e,t,i,s,m){var g={sourcePosition:e,position:t,isClosing:m,isWhite:Object.prototype.hasOwnProperty.call(r,i)},v=n(i,s,g)
if(!c(v))return v
if(g.isWhite){if(g.isClosing)return"</"+i+">"
var y=function(e){var t=l.spaceIndex(e)
if(-1===t)return{html:"",closing:"/"===e[e.length-2]}
var r="/"===(e=l.trim(e.slice(t+1,-1)))[e.length-1]
return r&&(e=l.trim(e.slice(0,-1))),{html:e,closing:r}}(s),b=r[i],w=a(y.html,(function(e,t){var r=-1!==l.indexOf(b,e),n=u(i,e,t,r)
return c(n)?r?(t=h(i,e,t,f))?e+'="'+t+'"':e:c(n=p(i,e,t,r))?void 0:n:n}))
return s="<"+i,w&&(s+=" "+w),y.closing&&(s+=" /"),s+">"}return c(v=o(i,s,g))?d(s):v}),d)
return m&&(g=m.remove(g)),g},e.exports=u},9158:(e,t,r)=>{"use strict"
var n=r(2651)
function i(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var o=0
function s(e){return"__private_"+o+++"_"+e}const a=r(3731),l={limit:1,retryDelays:[0,1e3,3e3,5e3],getChunkSize:e=>Math.ceil(e.size/1e4),onStart(){},onProgress(){},onPartComplete(){},onSuccess(){},onError(e){throw e}}
function c(e){if("string"==typeof e)return parseInt(e,10)
if("number"==typeof e)return e
throw new TypeError("Expected a number")}var u=s("aborted"),p=s("initChunks"),h=s("createUpload"),d=s("resumeUpload"),f=s("uploadParts"),m=s("retryable"),g=s("prepareUploadParts"),v=s("uploadPartRetryable"),y=s("uploadPart"),b=s("onPartProgress"),w=s("onPartComplete"),k=s("uploadPartBytes"),_=s("completeUpload"),x=s("abortUpload"),P=s("onError")
function S(){return this.abortController.signal.aborted}function E(){const e=[],t=this.options.getChunkSize(this.file),r=Math.max(5242880,Math.ceil(this.file.size/1e4)),n=Math.max(t,r)
if(0===this.file.size)e.push(this.file)
else for(let i=0;i<this.file.size;i+=n){const t=Math.min(this.file.size,i+n)
e.push(this.file.slice(i,t))}this.chunks=e,this.chunkState=e.map((()=>({uploaded:0,busy:!1,done:!1})))}function O(){return this.createdPromise=Promise.resolve().then((()=>this.options.createMultipartUpload())),this.createdPromise.then((e=>{if(i(this,u)[u]())throw(0,n.createAbortError)()
if("object"!=typeof e||!e||"string"!=typeof e.uploadId||"string"!=typeof e.key)throw new TypeError("AwsS3/Multipart: Got incorrect result from `createMultipartUpload()`, expected an object `{ uploadId, key }`.")
this.key=e.key,this.uploadId=e.uploadId,this.options.onStart(e),i(this,f)[f]()})).catch((e=>{i(this,P)[P](e)}))}async function A(){try{const e=await this.options.listParts({uploadId:this.uploadId,key:this.key})
if(i(this,u)[u]())throw(0,n.createAbortError)()
e.forEach((e=>{const t=e.PartNumber-1
this.chunkState[t]={uploaded:c(e.Size),etag:e.ETag,done:!0},this.parts.some((t=>t.PartNumber===e.PartNumber))||this.parts.push({PartNumber:e.PartNumber,ETag:e.ETag})})),i(this,f)[f]()}catch(e){i(this,P)[P](e)}}function C(){if(this.isPaused)return
if(this.chunkState.every((e=>e.done)))return void i(this,_)[_]()
const e=this.options.limit-this.partsInProgress,t=this.chunkState.filter((e=>e.done)).length,r=this.chunks.length-t
let n=Math.ceil(this.options.limit/2)
if(n>r&&(n=r),e<n)return
const o=[]
for(let i=0;i<this.chunkState.length;i++){const t=this.chunkState[i]
if(!t.done&&!t.busy&&(o.push(i),o.length>=e))break}0!==o.length&&i(this,g)[g](o).then((e=>{o.forEach((t=>{const r=t+1,n={url:e.presignedUrls[r],headers:e.headers}
i(this,v)[v](t,n).then((()=>{i(this,f)[f]()}),(e=>{i(this,P)[P](e)}))}))}))}function T(e){let{before:t,attempt:r,after:o}=e
const{retryDelays:s}=this.options,{signal:l}=this.abortController
t&&t()
const c=e=>r().catch((t=>{if(i(this,u)[u]())throw(0,n.createAbortError)()
if(function(e){if(e.source&&"number"==typeof e.source.status){const{status:t}=e.source
return 0===t||409===t||423===t||t>=500&&t<600}return!1}(t)&&e<s.length)return a(s[e],{signal:l}).then((()=>c(e+1)))
throw t}))
return c(0).then((e=>(o&&o(),e)),(e=>{throw o&&o(),e}))}async function L(e){e.forEach((e=>{this.chunkState[e].busy=!0}))
const t=await i(this,m)[m]({attempt:()=>this.options.prepareUploadParts({key:this.key,uploadId:this.uploadId,partNumbers:e.map((e=>e+1)),chunks:e.reduce(((e,t)=>({...e,[t+1]:this.chunks[t]})),{})})})
if("object"!=typeof(null==t?void 0:t.presignedUrls))throw new TypeError("AwsS3/Multipart: Got incorrect result from `prepareUploadParts()`, expected an object `{ presignedUrls }`.")
return t}function j(e,t){return i(this,m)[m]({before:()=>{this.partsInProgress+=1},attempt:()=>i(this,y)[y](e,t),after:()=>{this.partsInProgress-=1}})}function I(e,t){if(this.chunkState[e].busy=!0,"string"!=typeof(null==t?void 0:t.url))throw new TypeError("AwsS3/Multipart: Got incorrect result for `prePreparedPart`, expected an object `{ url }`.")
const{url:r,headers:o}=t
if(i(this,u)[u]())throw this.chunkState[e].busy=!1,(0,n.createAbortError)()
return i(this,k)[k](e,r,o)}function R(e,t){this.chunkState[e].uploaded=c(t)
const r=this.chunkState.reduce(((e,t)=>e+t.uploaded),0)
this.options.onProgress(r,this.file.size)}function N(e,t){this.chunkState[e].etag=t,this.chunkState[e].done=!0
const r={PartNumber:e+1,ETag:t}
this.parts.push(r),this.options.onPartComplete(r)}function U(e,t,r){const o=this.chunks[e],{signal:s}=this.abortController
let a
const l=new Promise(((e,t)=>{a={resolve:e,reject:t}})),c=new XMLHttpRequest
function u(){s.removeEventListener("abort",p)}function p(){c.abort()}return c.open("PUT",t,!0),r&&Object.keys(r).forEach((e=>{c.setRequestHeader(e,r[e])})),c.responseType="text",s.addEventListener("abort",p),c.upload.addEventListener("progress",(t=>{t.lengthComputable&&i(this,b)[b](e,t.loaded,t.total)})),c.addEventListener("abort",(()=>{u(),this.chunkState[e].busy=!1,a.reject((0,n.createAbortError)())})),c.addEventListener("load",(t=>{if(u(),this.chunkState[e].busy=!1,t.target.status<200||t.target.status>=300){const e=new Error("Non 2xx")
return e.source=t.target,void a.reject(e)}this.chunks[e]=null,i(this,b)[b](e,o.size,o.size)
const r=t.target.getResponseHeader("ETag")
null!==r?(i(this,w)[w](e,r),a.resolve()):a.reject(new Error("AwsS3/Multipart: Could not read the ETag header. This likely means CORS is not configured correctly on the S3 Bucket. See https://uppy.io/docs/aws-s3-multipart#S3-Bucket-Configuration for instructions."))})),c.addEventListener("error",(t=>{u(),this.chunkState[e].busy=!1
const r=new Error("Unknown error")
r.source=t.target,a.reject(r)})),c.send(o),l}async function F(){this.parts.sort(((e,t)=>e.PartNumber-t.PartNumber))
try{const e=await this.options.completeMultipartUpload({key:this.key,uploadId:this.uploadId,parts:this.parts})
this.options.onSuccess(e)}catch(e){i(this,P)[P](e)}}function M(){this.abortController.abort(),this.createdPromise.then((()=>{this.options.abortMultipartUpload({key:this.key,uploadId:this.uploadId})}),(()=>{}))}function D(e){e&&"AbortError"===e.name||this.options.onError(e)}e.exports=class{constructor(e,t){Object.defineProperty(this,P,{value:D}),Object.defineProperty(this,x,{value:M}),Object.defineProperty(this,_,{value:F}),Object.defineProperty(this,k,{value:U}),Object.defineProperty(this,w,{value:N}),Object.defineProperty(this,b,{value:R}),Object.defineProperty(this,y,{value:I}),Object.defineProperty(this,v,{value:j}),Object.defineProperty(this,g,{value:L}),Object.defineProperty(this,m,{value:T}),Object.defineProperty(this,f,{value:C}),Object.defineProperty(this,d,{value:A}),Object.defineProperty(this,h,{value:O}),Object.defineProperty(this,p,{value:E}),Object.defineProperty(this,u,{value:S}),this.options={...l,...t},this.options.getChunkSize||(this.options.getChunkSize=l.getChunkSize),this.file=e,this.abortController=new n.AbortController,this.key=this.options.key||null,this.uploadId=this.options.uploadId||null,this.parts=[],this.createdPromise=Promise.reject(),this.isPaused=!1,this.partsInProgress=0,this.chunks=null,this.chunkState=null,i(this,p)[p](),this.createdPromise.catch((()=>{}))}start(){this.isPaused=!1,this.uploadId?i(this,d)[d]():i(this,h)[h]()}pause(){this.abortController.abort(),this.abortController=new n.AbortController,this.isPaused=!0}abort(e){var t
void 0===e&&(e=void 0),null!=(t=e)&&t.really?i(this,x)[x]():this.pause()}}},4235:(e,t,r)=>{"use strict"
var n=r(3150),i=r(62)
let o
function s(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var a=0
function l(e){return"__private_"+a+++"_"+e}const c=r(4289),u=r(7035),p=r(9906),h=r(4819),d=r(9158)
function f(e){if(e&&e.error){const t=new Error(e.message)
throw Object.assign(t,e.error),t}return e}var m=l("queueRequestSocketToken"),g=l("client"),v=l("requestSocketToken"),y=l("setCompanionHeaders")
o=Symbol.for("uppy test: getClient")
class b extends c{constructor(e,t){super(e,t),Object.defineProperty(this,m,{writable:!0,value:void 0}),Object.defineProperty(this,g,{writable:!0,value:void 0}),Object.defineProperty(this,v,{writable:!0,value:async e=>{const t=new(e.remote.providerOptions.provider?n.Provider:n.RequestClient)(this.uppy,e.remote.providerOptions),r={...this.opts}
return e.tus&&Object.assign(r,e.tus),(await t.post(e.remote.url,{...e.remote.body,protocol:"s3-multipart",size:e.data.size,metadata:e.meta})).token}}),Object.defineProperty(this,y,{writable:!0,value:()=>(s(this,g)[g].setCompanionHeaders(this.opts.companionHeaders),Promise.resolve())}),this.type="uploader",this.id=this.opts.id||"AwsS3Multipart",this.title="AWS S3 Multipart",s(this,g)[g]=new n.RequestClient(e,t)
const r={timeout:3e4,limit:0,retryDelays:[0,1e3,3e3,5e3],createMultipartUpload:this.createMultipartUpload.bind(this),listParts:this.listParts.bind(this),prepareUploadParts:this.prepareUploadParts.bind(this),abortMultipartUpload:this.abortMultipartUpload.bind(this),completeMultipartUpload:this.completeMultipartUpload.bind(this),companionHeaders:{}}
this.opts={...r,...t},this.upload=this.upload.bind(this),this.requests=new i.RateLimitedQueue(this.opts.limit),this.uploaders=Object.create(null),this.uploaderEvents=Object.create(null),this.uploaderSockets=Object.create(null),s(this,m)[m]=this.requests.wrapPromiseFunction(s(this,v)[v])}[o](){return s(this,g)[g]}get client(){return s(this,g)[g]}set client(e){s(this,g)[g]=e}resetUploaderReferences(e,t){void 0===t&&(t={}),this.uploaders[e]&&(this.uploaders[e].abort({really:t.abort||!1}),this.uploaders[e]=null),this.uploaderEvents[e]&&(this.uploaderEvents[e].remove(),this.uploaderEvents[e]=null),this.uploaderSockets[e]&&(this.uploaderSockets[e].close(),this.uploaderSockets[e]=null)}assertHost(e){if(!this.opts.companionUrl)throw new Error("Expected a `companionUrl` option containing a Companion address, or if you are not using Companion, a custom `".concat(e,"` implementation."))}createMultipartUpload(e){this.assertHost("createMultipartUpload")
const t={}
return Object.keys(e.meta).forEach((r=>{null!=e.meta[r]&&(t[r]=e.meta[r].toString())})),s(this,g)[g].post("s3/multipart",{filename:e.name,type:e.type,metadata:t}).then(f)}listParts(e,t){let{key:r,uploadId:n}=t
this.assertHost("listParts")
const i=encodeURIComponent(r)
return s(this,g)[g].get("s3/multipart/".concat(n,"?key=").concat(i)).then(f)}prepareUploadParts(e,t){let{key:r,uploadId:n,partNumbers:i}=t
this.assertHost("prepareUploadParts")
const o=encodeURIComponent(r)
return s(this,g)[g].get("s3/multipart/".concat(n,"/batch?key=").concat(o,"&partNumbers=").concat(i.join(","))).then(f)}completeMultipartUpload(e,t){let{key:r,uploadId:n,parts:i}=t
this.assertHost("completeMultipartUpload")
const o=encodeURIComponent(r),a=encodeURIComponent(n)
return s(this,g)[g].post("s3/multipart/".concat(a,"/complete?key=").concat(o),{parts:i}).then(f)}abortMultipartUpload(e,t){let{key:r,uploadId:n}=t
this.assertHost("abortMultipartUpload")
const i=encodeURIComponent(r),o=encodeURIComponent(n)
return s(this,g)[g].delete("s3/multipart/".concat(o,"?key=").concat(i)).then(f)}uploadFile(e){var t=this
return new Promise(((r,n)=>{let i
const o=new d(e.data,{createMultipartUpload:this.opts.createMultipartUpload.bind(this,e),listParts:this.opts.listParts.bind(this,e),prepareUploadParts:this.opts.prepareUploadParts.bind(this,e),completeMultipartUpload:this.opts.completeMultipartUpload.bind(this,e),abortMultipartUpload:this.opts.abortMultipartUpload.bind(this,e),getChunkSize:this.opts.getChunkSize?this.opts.getChunkSize.bind(this):null,onStart:t=>{const r=this.uppy.getFile(e.id)
this.uppy.setFileState(e.id,{s3Multipart:{...r.s3Multipart,key:t.key,uploadId:t.uploadId}})},onProgress:(t,r)=>{this.uppy.emit("upload-progress",e,{uploader:this,bytesUploaded:t,bytesTotal:r})},onError:t=>{this.uppy.log(t),this.uppy.emit("upload-error",e,t),i.done(),this.resetUploaderReferences(e.id),n(t)},onSuccess:t=>{const n=o,s={body:{...t},uploadURL:t.location}
i.done(),this.resetUploaderReferences(e.id)
const a=this.uppy.getFile(e.id)
this.uppy.emit("upload-success",a||e,s),t.location&&this.uppy.log("Download ".concat(n.file.name," from ").concat(t.location)),r(n)},onPartComplete:t=>{const r=this.uppy.getFile(e.id)
r&&this.uppy.emit("s3-multipart:part-uploaded",r,t)},limit:this.opts.limit||5,retryDelays:this.opts.retryDelays||[],...e.s3Multipart})
this.uploaders[e.id]=o,this.uploaderEvents[e.id]=new u(this.uppy),i=this.requests.run((()=>(e.isPaused||o.start(),()=>{}))),this.onFileRemove(e.id,(t=>{i.abort(),this.resetUploaderReferences(e.id,{abort:!0}),r("upload ".concat(t.id," was removed"))})),this.onCancelAll(e.id,(function(n){let{reason:o}=void 0===n?{}:n
"user"===o&&(i.abort(),t.resetUploaderReferences(e.id,{abort:!0})),r("upload ".concat(e.id," was canceled"))})),this.onFilePause(e.id,(e=>{e?(i.abort(),o.pause()):(i.abort(),i=this.requests.run((()=>(o.start(),()=>{}))))})),this.onPauseAll(e.id,(()=>{i.abort(),o.pause()})),this.onResumeAll(e.id,(()=>{i.abort(),e.error&&o.abort(),i=this.requests.run((()=>(o.start(),()=>{})))})),e.progress.uploadStarted&&e.isRestored||this.uppy.emit("upload-started",e)}))}async uploadRemote(e){this.resetUploaderReferences(e.id),e.progress.uploadStarted&&e.isRestored||this.uppy.emit("upload-started",e)
try{if(e.serverToken)return this.connectToServerSocket(e)
const t=await s(this,m)[m](e)
return this.uppy.setFileState(e.id,{serverToken:t}),this.connectToServerSocket(this.uppy.getFile(e.id))}catch(t){throw this.uppy.emit("upload-error",e,t),t}}connectToServerSocket(e){var t=this
return new Promise(((r,i)=>{let o
const s=e.serverToken,a=h(e.remote.companionUrl),l=new n.Socket({target:"".concat(a,"/api/").concat(s)})
this.uploaderSockets[e.id]=l,this.uploaderEvents[e.id]=new u(this.uppy),this.onFileRemove(e.id,(()=>{o.abort(),l.send("cancel",{}),this.resetUploaderReferences(e.id,{abort:!0}),r("upload ".concat(e.id," was removed"))})),this.onFilePause(e.id,(e=>{e?(o.abort(),l.send("pause",{})):(o.abort(),o=this.requests.run((()=>(l.send("resume",{}),()=>{}))))})),this.onPauseAll(e.id,(()=>{o.abort(),l.send("pause",{})})),this.onCancelAll(e.id,(function(n){let{reason:i}=void 0===n?{}:n
"user"===i&&(o.abort(),l.send("cancel",{}),t.resetUploaderReferences(e.id)),r("upload ".concat(e.id," was canceled"))})),this.onResumeAll(e.id,(()=>{o.abort(),e.error&&l.send("pause",{}),o=this.requests.run((()=>{l.send("resume",{})}))})),this.onRetry(e.id,(()=>{l.isOpen&&(l.send("pause",{}),l.send("resume",{}))})),this.onRetryAll(e.id,(()=>{l.isOpen&&(l.send("pause",{}),l.send("resume",{}))})),l.on("progress",(t=>p(this,t,e))),l.on("error",(t=>{this.uppy.emit("upload-error",e,new Error(t.error)),this.resetUploaderReferences(e.id),o.done(),i(new Error(t.error))})),l.on("success",(t=>{const n={uploadURL:t.url}
this.uppy.emit("upload-success",e,n),this.resetUploaderReferences(e.id),o.done(),r()})),o=this.requests.run((()=>(e.isPaused&&l.send("pause",{}),()=>{})))}))}upload(e){if(0===e.length)return Promise.resolve()
const t=e.map((e=>{const t=this.uppy.getFile(e)
return t.isRemote?this.uploadRemote(t):this.uploadFile(t)}))
return Promise.all(t)}onFileRemove(e,t){this.uploaderEvents[e].on("file-removed",(r=>{e===r.id&&t(r.id)}))}onFilePause(e,t){this.uploaderEvents[e].on("upload-pause",((r,n)=>{e===r&&t(n)}))}onRetry(e,t){this.uploaderEvents[e].on("upload-retry",(r=>{e===r&&t()}))}onRetryAll(e,t){this.uploaderEvents[e].on("retry-all",(()=>{this.uppy.getFile(e)&&t()}))}onPauseAll(e,t){this.uploaderEvents[e].on("pause-all",(()=>{this.uppy.getFile(e)&&t()}))}onCancelAll(e,t){var r=this
this.uploaderEvents[e].on("cancel-all",(function(){r.uppy.getFile(e)&&t(...arguments)}))}onResumeAll(e,t){this.uploaderEvents[e].on("resume-all",(()=>{this.uppy.getFile(e)&&t()}))}install(){const{capabilities:e}=this.uppy.getState()
this.uppy.setState({capabilities:{...e,resumableUploads:!0}}),this.uppy.addPreProcessor(s(this,y)[y]),this.uppy.addUploader(this.upload)}uninstall(){const{capabilities:e}=this.uppy.getState()
this.uppy.setState({capabilities:{...e,resumableUploads:!1}}),this.uppy.removePreProcessor(s(this,y)[y]),this.uppy.removeUploader(this.upload)}}b.VERSION="2.4.1",e.exports=b},1937:(e,t,r)=>{"use strict"
var n=r(8773),i=r(3150),o=r(62)
function s(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var a=0
function l(e){return"__private_"+a+++"_"+e}const c=r(9906),u=r(4819),p=r(7035),h=r(8008),d=r(9854),f=r(9319),m=r(5583)
function g(e,t){if(m(e))return new f(t,e)
const r=new d("Upload error",{cause:t})
return r.request=e,r}var v=l("queueRequestSocketToken"),y=l("getOptions"),b=l("addEventHandlerForFile"),w=l("addEventHandlerIfFileStillExists"),k=l("uploadLocalFile"),_=l("requestSocketToken"),x=l("uploadRemoteFile")
function P(e){var t
const{uppy:r}=this,n=r.getState().xhrUpload
return{...this.opts,...n||{},...e.xhrUpload||{},headers:{...this.opts.headers,...null==n?void 0:n.headers,...null==(t=e.xhrUpload)?void 0:t.headers}}}function S(e,t,r){this.uploaderEvents[t].on(e,(e=>{t===e&&r()}))}function E(e,t,r){var n=this
this.uploaderEvents[t].on(e,(function(){n.uppy.getFile(t)&&r(...arguments)}))}function O(e,t,r){const i=s(this,y)[y](e)
return this.uppy.log("uploading ".concat(t," of ").concat(r)),new Promise(((t,r)=>{const o=i.formData?function(e,t){const r=new FormData
!function(e,t,r){(Array.isArray(r.metaFields)?r.metaFields:Object.keys(t)).forEach((r=>{e.append(r,t[r])}))}(r,e.meta,t)
const n=function(e){return e.data.slice(0,e.data.size,e.meta.type)}(e)
return e.name?r.append(t.fieldName,n,e.meta.name):r.append(t.fieldName,n),r}(e,i):(e=>e.data)(e),a=new XMLHttpRequest
this.uploaderEvents[e.id]=new p(this.uppy)
const l=new h(i.timeout,(()=>{a.abort(),u.done()
const t=new Error(this.i18n("timedOut",{seconds:Math.ceil(i.timeout/1e3)}))
this.uppy.emit("upload-error",e,t),r(t)})),c=(0,n.nanoid)()
a.upload.addEventListener("loadstart",(()=>{this.uppy.log("[AwsS3/XHRUpload] ".concat(c," started"))})),a.upload.addEventListener("progress",(t=>{this.uppy.log("[AwsS3/XHRUpload] ".concat(c," progress: ").concat(t.loaded," / ").concat(t.total)),l.progress(),t.lengthComputable&&this.uppy.emit("upload-progress",e,{uploader:this,bytesUploaded:t.loaded,bytesTotal:t.total})})),a.addEventListener("load",(n=>{if(this.uppy.log("[AwsS3/XHRUpload] ".concat(c," finished")),l.done(),u.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),i.validateStatus(n.target.status,a.responseText,a)){const r=i.getResponseData(a.responseText,a),o=r[i.responseUrlFieldName],s={status:n.target.status,body:r,uploadURL:o}
return this.uppy.emit("upload-success",e,s),o&&this.uppy.log("Download ".concat(e.name," from ").concat(o)),t(e)}const o=i.getResponseData(a.responseText,a),s=g(a,i.getResponseError(a.responseText,a)),p={status:n.target.status,body:o}
return this.uppy.emit("upload-error",e,s,p),r(s)})),a.addEventListener("error",(()=>{this.uppy.log("[AwsS3/XHRUpload] ".concat(c," errored")),l.done(),u.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null)
const t=g(a,i.getResponseError(a.responseText,a))
return this.uppy.emit("upload-error",e,t),r(t)})),a.open(i.method.toUpperCase(),i.endpoint,!0),a.withCredentials=Boolean(i.withCredentials),""!==i.responseType&&(a.responseType=i.responseType),Object.keys(i.headers).forEach((e=>{a.setRequestHeader(e,i.headers[e])}))
const u=this.requests.run((()=>(a.send(o),()=>{l.done(),a.abort()})),{priority:1})
s(this,b)[b]("file-removed",e.id,(()=>{u.abort(),r(new Error("File removed"))})),s(this,w)[w]("cancel-all",e.id,(function(e){let{reason:t}=void 0===e?{}:e
"user"===t&&u.abort(),r(new Error("Upload cancelled"))}))}))}async function A(e){try{if(e.serverToken)return this.connectToServerSocket(e)
const t=await s(this,v)[v](e)
return this.uppy.setFileState(e.id,{serverToken:t}),this.connectToServerSocket(this.uppy.getFile(e.id))}catch(t){throw this.uppy.emit("upload-error",e,t),t}}e.exports=class{constructor(e,t){Object.defineProperty(this,x,{value:A}),Object.defineProperty(this,k,{value:O}),Object.defineProperty(this,w,{value:E}),Object.defineProperty(this,b,{value:S}),Object.defineProperty(this,y,{value:P}),Object.defineProperty(this,v,{writable:!0,value:void 0}),Object.defineProperty(this,_,{writable:!0,value:async e=>{const t=s(this,y)[y](e),r=new(e.remote.providerOptions.provider?i.Provider:i.RequestClient)(this.uppy,e.remote.providerOptions),n=Array.isArray(t.metaFields)?t.metaFields:Object.keys(e.meta)
return e.tus&&Object.assign(t,e.tus),(await r.post(e.remote.url,{...e.remote.body,endpoint:t.endpoint,size:e.data.size,fieldname:t.fieldName,metadata:Object.fromEntries(n.map((t=>[t,e.meta[t]]))),httpMethod:t.method,useFormData:t.formData,headers:t.headers})).token}}),this.uppy=e,this.opts={validateStatus:e=>e>=200&&e<300,...t},this.requests=t[o.internalRateLimitedQueue],this.uploaderEvents=Object.create(null),this.i18n=t.i18n,s(this,v)[v]=this.requests.wrapPromiseFunction(s(this,_)[_])}uploadFile(e,t,r){const n=this.uppy.getFile(e)
if(n.error)throw new Error(n.error)
return n.isRemote?s(this,x)[x](n,t,r):s(this,k)[k](n,t,r)}connectToServerSocket(e){return new Promise(((t,r)=>{const n=s(this,y)[y](e),o=e.serverToken,a=u(e.remote.companionUrl),l=new i.Socket({target:"".concat(a,"/api/").concat(o)})
this.uploaderEvents[e.id]=new p(this.uppy)
const h=this.requests.run((()=>(e.isPaused&&l.send("pause",{}),()=>l.close())))
s(this,b)[b]("file-removed",e.id,(()=>{l.send("cancel",{}),h.abort(),t("upload ".concat(e.id," was removed"))})),s(this,w)[w]("cancel-all",e.id,(function(r){let{reason:n}=void 0===r?{}:r
"user"===n&&(l.send("cancel",{}),h.abort()),t("upload ".concat(e.id," was canceled"))})),s(this,b)[b]("upload-retry",e.id,(()=>{l.send("pause",{}),l.send("resume",{})})),s(this,w)[w]("retry-all",e.id,(()=>{l.send("pause",{}),l.send("resume",{})})),l.on("progress",(t=>c(this,t,e))),l.on("success",(r=>{const i=n.getResponseData(r.response.responseText,r.response),o=i[n.responseUrlFieldName],s={status:r.response.status,body:i,uploadURL:o,bytesUploaded:r.bytesUploaded}
return this.uppy.emit("upload-success",e,s),h.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),t()})),l.on("error",(t=>{const i=t.response,o=i?n.getResponseError(i.responseText,i):new d(t.error.message,{cause:t.error})
this.uppy.emit("upload-error",e,o),h.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),r(o)}))})).catch((t=>(this.uppy.emit("upload-error",e,t),Promise.reject(t))))}}},3633:(e,t,r)=>{"use strict"
var n=r(62),i=r(3150)
let o
function s(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var a=0
function l(e){return"__private_"+a+++"_"+e}const c=r(4289),u=r(1937),p=r(5264),h=r(109)
function d(e,t){const r=e.indexOf("<".concat(t,">")),n=e.indexOf("</".concat(t,">"),r)
return-1!==r&&-1!==n?e.slice(r+t.length+2,n):""}function f(e){if(e&&e.error){const t=new Error(e.message)
throw Object.assign(t,e.error),t}return e}function m(e,t){if(!p(e,t))return
const r=d(e,"Message")
return new Error(r)}let g=!1
var v=l("client"),y=l("requests"),b=l("uploader"),w=l("handleUpload"),k=l("setCompanionHeaders")
o=Symbol.for("uppy test: getClient")
class _ extends c{constructor(e,t){super(e,t),Object.defineProperty(this,v,{writable:!0,value:void 0}),Object.defineProperty(this,y,{writable:!0,value:void 0}),Object.defineProperty(this,b,{writable:!0,value:void 0}),Object.defineProperty(this,w,{writable:!0,value:e=>{const t=Object.create(null)
function r(e){var r
const{id:n}=e
null==(r=t[n])||r.abort()}this.uppy.on("file-removed",r),e.forEach((e=>{const t=this.uppy.getFile(e)
this.uppy.emit("upload-started",t)}))
const n=s(this,y)[y].wrapPromiseFunction((e=>this.opts.getUploadParameters(e))),i=e.length
return Promise.allSettled(e.map(((e,r)=>(t[e]=n(this.uppy.getFile(e)),t[e].then((n=>{delete t[e]
const o=this.uppy.getFile(e)
!function(e,t){if(null==t||"string"!=typeof t.url||"object"!=typeof t.fields&&null!=t.fields)throw new TypeError("AwsS3: got incorrect result from 'getUploadParameters()' for file '".concat(e.name,"', expected an object '{ url, method, fields, headers }' but got '").concat(JSON.stringify(t),"' instead.\nSee https://uppy.io/docs/aws-s3/#getUploadParameters-file for more on the expected format."))
if(null!=t.method&&!/^p(u|os)t$/i.test(t.method))throw new TypeError("AwsS3: got incorrect method from 'getUploadParameters()' for file '".concat(e.name,"', expected  'put' or 'post' but got '").concat(t.method,"' instead.\nSee https://uppy.io/docs/aws-s3/#getUploadParameters-file for more on the expected format."))}(o,n)
const{method:a="post",url:l,fields:c,headers:u}=n,p={method:a,formData:"post"===a.toLowerCase(),endpoint:l,metaFields:c?Object.keys(c):[]}
return u&&(p.headers=u),this.uppy.setFileState(o.id,{meta:{...o.meta,...c},xhrUpload:p}),s(this,b)[b].uploadFile(o.id,r,i)})).catch((r=>{delete t[e]
const n=this.uppy.getFile(e)
return this.uppy.emit("upload-error",n,r),Promise.reject(r)})))))).finally((()=>{this.uppy.off("file-removed",r)}))}}),Object.defineProperty(this,k,{writable:!0,value:()=>(s(this,v)[v].setCompanionHeaders(this.opts.companionHeaders),Promise.resolve())}),this.type="uploader",this.id=this.opts.id||"AwsS3",this.title="AWS S3",this.defaultLocale=h
const r={timeout:3e4,limit:0,metaFields:[],getUploadParameters:this.getUploadParameters.bind(this),companionHeaders:{}}
this.opts={...r,...t},this.i18nInit(),s(this,v)[v]=new i.RequestClient(e,t),s(this,y)[y]=new n.RateLimitedQueue(this.opts.limit)}[o](){return s(this,v)[v]}get client(){return s(this,v)[v]}set client(e){s(this,v)[v]=e}getUploadParameters(e){if(!this.opts.companionUrl)throw new Error("Expected a `companionUrl` option containing a Companion address.")
const t=e.meta.name,{type:r}=e.meta,n=Object.fromEntries(this.opts.metaFields.filter((t=>null!=e.meta[t])).map((t=>["metadata[".concat(t,"]"),e.meta[t].toString()]))),i=new URLSearchParams({filename:t,type:r,...n})
return s(this,v)[v].get("s3/params?".concat(i)).then(f)}install(){const{uppy:e}=this
e.addPreProcessor(s(this,k)[k]),e.addUploader(s(this,w)[w])
const t={fieldName:"file",responseUrlFieldName:"location",timeout:this.opts.timeout,[n.internalRateLimitedQueue]:s(this,y)[y],responseType:"text",getResponseData:this.opts.getResponseData||function(t,r){return p(t,r)?{location:(n=r.responseURL,i=d(t,"Location"),new URL(i,n||void 0).toString()),bucket:d(t,"Bucket"),key:d(t,"Key"),etag:d(t,"ETag")}:"POST"===this.method.toUpperCase()?(g||(e.log("[AwsS3] No response data found, make sure to set the success_action_status AWS SDK option to 201. See https://uppy.io/docs/aws-s3/#POST-Uploads","warning"),g=!0),{location:null}):r.responseURL?{location:r.responseURL.replace(/\?.*$/,"")}:{location:null}
var n,i},getResponseError:m}
t.i18n=this.i18n,s(this,b)[b]=new u(e,t)}uninstall(){this.uppy.removePreProcessor(s(this,k)[k]),this.uppy.removeUploader(s(this,w)[w])}}_.VERSION="2.2.1",e.exports=_},5264:e=>{"use strict"
e.exports=function(e,t){const r=t.headers?t.headers["content-type"]:t.getResponseHeader("Content-Type")
if("string"==typeof r){const t=(n=r,n.replace(/;.*$/,"")).toLowerCase()
if("application/xml"===t||"text/xml"===t)return!0
if("text/html"===t&&/^<\?xml /.test(e))return!0}var n
return!1}},109:e=>{"use strict"
e.exports={strings:{timedOut:"Upload stalled for %{seconds} seconds, aborting."}}},6031:e=>{"use strict"
class t extends Error{constructor(){super("Authorization required"),this.name="AuthError",this.isAuthError=!0}}e.exports=t},3456:(e,t,r)=>{"use strict"
var n=r(3337)
const i=r(4622)
e.exports=class extends i{constructor(e,t){super(e,t),this.provider=t.provider,this.id=this.provider,this.name=this.opts.name||this.id.split("-").map((e=>e.charAt(0).toUpperCase()+e.slice(1))).join(" "),this.pluginId=this.opts.pluginId,this.tokenKey="companion-".concat(this.pluginId,"-auth-token"),this.companionKeysParams=this.opts.companionKeysParams,this.preAuthToken=null}headers(){return Promise.all([super.headers(),this.getAuthToken()]).then((e=>{let[t,r]=e
const n={}
return r&&(n["uppy-auth-token"]=r),this.companionKeysParams&&(n["uppy-credentials-params"]=btoa(JSON.stringify({params:this.companionKeysParams}))),{...t,...n}}))}onReceiveResponse(e){e=super.onReceiveResponse(e)
const t=this.uppy.getPlugin(this.pluginId),r=t.getPluginState().authenticated?401!==e.status:e.status<400
return t.setPluginState({authenticated:r}),e}setAuthToken(e){return this.uppy.getPlugin(this.pluginId).storage.setItem(this.tokenKey,e)}getAuthToken(){return this.uppy.getPlugin(this.pluginId).storage.getItem(this.tokenKey)}async ensurePreAuth(){if(this.companionKeysParams&&!this.preAuthToken&&(await this.fetchPreAuthToken(),!this.preAuthToken))throw new Error("Could not load authentication data required for third-party login. Please try again later.")}authUrl(e){void 0===e&&(e={})
const t=new URLSearchParams(e)
return this.preAuthToken&&t.set("uppyPreAuthToken",this.preAuthToken),"".concat(this.hostname,"/").concat(this.id,"/connect?").concat(t)}fileUrl(e){return"".concat(this.hostname,"/").concat(this.id,"/get/").concat(e)}async fetchPreAuthToken(){if(this.companionKeysParams)try{const e=await this.post("".concat(this.id,"/preauth/"),{params:this.companionKeysParams})
this.preAuthToken=e.token}catch(e){this.uppy.log("[CompanionClient] unable to fetch preAuthToken ".concat(e),"warning")}}list(e){return this.get("".concat(this.id,"/list/").concat(e||""))}logout(){return this.get("".concat(this.id,"/logout")).then((e=>Promise.all([e,this.uppy.getPlugin(this.pluginId).storage.removeItem(this.tokenKey)]))).then((e=>{let[t]=e
return t}))}static initPlugin(e,t,r){if(e.type="acquirer",e.files=[],r&&(e.opts={...r,...t}),t.serverUrl||t.serverPattern)throw new Error("`serverUrl` and `serverPattern` have been renamed to `companionUrl` and `companionAllowedHosts` respectively in the 0.30.5 release. Please consult the docs (for example, https://uppy.io/docs/instagram/ for the Instagram plugin) and use the updated options.`")
if(t.companionAllowedHosts){const r=t.companionAllowedHosts
if(!("string"==typeof r||Array.isArray(r)||r instanceof RegExp))throw new TypeError("".concat(e.id,': the option "companionAllowedHosts" must be one of string, Array, RegExp'))
e.opts.companionAllowedHosts=r}else/^(?!https?:\/\/).*$/i.test(t.companionUrl)?e.opts.companionAllowedHosts="https://".concat(t.companionUrl.replace(/^\/\//,"")):e.opts.companionAllowedHosts=new URL(t.companionUrl).origin
e.storage=e.opts.storage||n}}},4622:(e,t,r)=>{"use strict"
let n
function i(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var o=0
function s(e){return"__private_"+o+++"_"+e}const a=r(274),l=r(9854),c=r(6031)
async function u(e){if(401===e.status)throw new c
const t=e.json()
if(e.status<200||e.status>300){let r="Failed request with status: ".concat(e.status,". ").concat(e.statusText)
try{const e=await t
r=e.message?"".concat(r," message: ").concat(e.message):r,r=e.requestId?"".concat(r," request-Id: ").concat(e.requestId):r}finally{throw new Error(r)}}return t}var p=s("companionHeaders"),h=s("getPostResponseFunc"),d=s("getUrl"),f=s("errorHandler")
n=Symbol.for("uppy test: getCompanionHeaders")
class m{constructor(e,t){Object.defineProperty(this,f,{value:v}),Object.defineProperty(this,d,{value:g}),Object.defineProperty(this,p,{writable:!0,value:void 0}),Object.defineProperty(this,h,{writable:!0,value:e=>t=>e?t:this.onReceiveResponse(t)}),this.uppy=e,this.opts=t,this.onReceiveResponse=this.onReceiveResponse.bind(this),this.allowedHeaders=["accept","content-type","uppy-auth-token"],this.preflightDone=!1,i(this,p)[p]=null==t?void 0:t.companionHeaders}setCompanionHeaders(e){i(this,p)[p]=e}[n](){return i(this,p)[p]}get hostname(){const{companion:e}=this.uppy.getState(),t=this.opts.companionUrl
return(e&&e[t]?e[t]:t).replace(/\/$/,"")}headers(){return Promise.resolve({...m.defaultHeaders,...i(this,p)[p]})}onReceiveResponse(e){const t=this.uppy.getState().companion||{},r=this.opts.companionUrl,{headers:n}=e
return n.has("i-am")&&n.get("i-am")!==t[r]&&this.uppy.setState({companion:{...t,[r]:n.get("i-am")}}),e}preflight(e){return this.preflightDone?Promise.resolve(this.allowedHeaders.slice()):fetch(i(this,d)[d](e),{method:"OPTIONS"}).then((e=>(e.headers.has("access-control-allow-headers")&&(this.allowedHeaders=e.headers.get("access-control-allow-headers").split(",").map((e=>e.trim().toLowerCase()))),this.preflightDone=!0,this.allowedHeaders.slice()))).catch((e=>(this.uppy.log("[CompanionClient] unable to make preflight request ".concat(e),"warning"),this.preflightDone=!0,this.allowedHeaders.slice())))}preflightAndHeaders(e){return Promise.all([this.preflight(e),this.headers()]).then((e=>{let[t,r]=e
return Object.keys(r).forEach((e=>{t.includes(e.toLowerCase())||(this.uppy.log("[CompanionClient] excluding disallowed header ".concat(e)),delete r[e])})),r}))}get(e,t){return this.preflightAndHeaders(e).then((t=>a(i(this,d)[d](e),{method:"get",headers:t,credentials:this.opts.companionCookiesRule||"same-origin"}))).then(i(this,h)[h](t)).then(u).catch(i(this,f)[f]("get",e))}post(e,t,r){const n="post"
return this.preflightAndHeaders(e).then((r=>a(i(this,d)[d](e),{method:n,headers:r,credentials:this.opts.companionCookiesRule||"same-origin",body:JSON.stringify(t)}))).then(i(this,h)[h](r)).then(u).catch(i(this,f)[f](n,e))}delete(e,t,r){const n="delete"
return this.preflightAndHeaders(e).then((r=>a("".concat(this.hostname,"/").concat(e),{method:n,headers:r,credentials:this.opts.companionCookiesRule||"same-origin",body:t?JSON.stringify(t):null}))).then(i(this,h)[h](r)).then(u).catch(i(this,f)[f](n,e))}}function g(e){return/^(https?:|)\/\//.test(e)?e:"".concat(this.hostname,"/").concat(e)}function v(e,t){return r=>{var n
return null!=(n=r)&&n.isAuthError||(r=new l("Could not ".concat(e," ").concat(i(this,d)[d](t)),{cause:r})),Promise.reject(r)}}m.VERSION="2.2.1",m.defaultHeaders={Accept:"application/json","Content-Type":"application/json","Uppy-Versions":"@uppy/companion-client=".concat(m.VERSION)},e.exports=m},7756:(e,t,r)=>{"use strict"
const n=r(4622)
e.exports=class extends n{constructor(e,t){super(e,t),this.provider=t.provider,this.id=this.provider,this.name=this.opts.name||this.id.split("-").map((e=>e.charAt(0).toUpperCase()+e.slice(1))).join(" "),this.pluginId=this.opts.pluginId}fileUrl(e){return"".concat(this.hostname,"/search/").concat(this.id,"/get/").concat(e)}search(e,t){return this.get("search/".concat(this.id,"/list?q=").concat(encodeURIComponent(e)).concat(t?"&".concat(t):""))}}},6116:(e,t,r)=>{"use strict"
let n,i
function o(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var s=0
function a(e){return"__private_"+s+++"_"+e}const l=r(5575)
var c=a("queued"),u=a("emitter"),p=a("isOpen"),h=a("socket"),d=a("handleMessage")
n=Symbol.for("uppy test: getSocket"),i=Symbol.for("uppy test: getQueued"),e.exports=class{constructor(e){Object.defineProperty(this,c,{writable:!0,value:[]}),Object.defineProperty(this,u,{writable:!0,value:l()}),Object.defineProperty(this,p,{writable:!0,value:!1}),Object.defineProperty(this,h,{writable:!0,value:void 0}),Object.defineProperty(this,d,{writable:!0,value:e=>{try{const t=JSON.parse(e.data)
this.emit(t.action,t.payload)}catch(e){console.log(e)}}}),this.opts=e,e&&!1===e.autoOpen||this.open()}get isOpen(){return o(this,p)[p]}[n](){return o(this,h)[h]}[i](){return o(this,c)[c]}open(){o(this,h)[h]=new WebSocket(this.opts.target),o(this,h)[h].onopen=()=>{for(o(this,p)[p]=!0;o(this,c)[c].length>0&&o(this,p)[p];){const e=o(this,c)[c].shift()
this.send(e.action,e.payload)}},o(this,h)[h].onclose=()=>{o(this,p)[p]=!1},o(this,h)[h].onmessage=o(this,d)[d]}close(){var e
null==(e=o(this,h)[h])||e.close()}send(e,t){o(this,p)[p]?o(this,h)[h].send(JSON.stringify({action:e,payload:t})):o(this,c)[c].push({action:e,payload:t})}on(e,t){o(this,u)[u].on(e,t)}emit(e,t){o(this,u)[u].emit(e,t)}once(e,t){o(this,u)[u].once(e,t)}}},3150:(e,t,r)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.Socket=t.SearchProvider=t.RequestClient=t.Provider=void 0
const n=r(4622)
t.RequestClient=n
const i=r(3456)
t.Provider=i
const o=r(7756)
t.SearchProvider=o
const s=r(6116)
t.Socket=s},3337:(e,t)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.getItem=function(e){return Promise.resolve(localStorage.getItem(e))},t.removeItem=function(e){return new Promise((t=>{localStorage.removeItem(e),t()}))},t.setItem=function(e,t){return new Promise((r=>{localStorage.setItem(e,t),r()}))}},4289:(e,t,r)=>{"use strict"
const n=r(2393)
e.exports=class{constructor(e,t){void 0===t&&(t={}),this.uppy=e,this.opts=t}getPluginState(){const{plugins:e}=this.uppy.getState()
return e[this.id]||{}}setPluginState(e){const{plugins:t}=this.uppy.getState()
this.uppy.setState({plugins:{...t,[this.id]:{...t[this.id],...e}}})}setOptions(e){this.opts={...this.opts,...e},this.setPluginState(),this.i18nInit()}i18nInit(){const e=new n([this.defaultLocale,this.uppy.locale,this.opts.locale])
this.i18n=e.translate.bind(e),this.i18nArray=e.translateArray.bind(e),this.setPluginState()}addTarget(){throw new Error("Extend the addTarget method to add your plugin to another plugin's target")}install(){}uninstall(){}render(){throw new Error("Extend the render method to add your plugin to a DOM element")}update(){}afterUpdate(){}}},2839:(e,t,r)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.defaultOptions=t.RestrictionError=t.Restricter=void 0
const n=r(204),i=r(6568)
t.defaultOptions={maxFileSize:null,minFileSize:null,maxTotalFileSize:null,maxNumberOfFiles:null,minNumberOfFiles:null,allowedFileTypes:null,requiredMetaFields:[]}
class o extends Error{constructor(){super(...arguments),this.isRestriction=!0}}t.RestrictionError=o,"undefined"==typeof AggregateError&&(globalThis.AggregateError=class extends Error{constructor(e,t){super(t),this.errors=e}}),t.Restricter=class{constructor(e,t){this.i18n=t,this.getOpts=()=>{const t=e()
if(null!=t.restrictions.allowedFileTypes&&!Array.isArray(t.restrictions.allowedFileTypes))throw new TypeError("`restrictions.allowedFileTypes` must be an array")
return t}}validate(e,t){const{maxFileSize:r,minFileSize:s,maxTotalFileSize:a,maxNumberOfFiles:l,allowedFileTypes:c}=this.getOpts().restrictions
if(l&&t.length+1>l)throw new o("".concat(this.i18n("youCanOnlyUploadX",{smart_count:l})))
if(c&&!c.some((t=>t.includes("/")?!!e.type&&i(e.type.replace(/;.*?$/,""),t):!("."!==t[0]||!e.extension)&&e.extension.toLowerCase()===t.slice(1).toLowerCase()))){const e=c.join(", ")
throw new o(this.i18n("youCanOnlyUploadFileTypes",{types:e}))}if(a&&null!=e.size&&t.reduce(((e,t)=>e+t.size),e.size)>a)throw new o(this.i18n("exceedsSize",{size:n(a),file:e.name}))
if(r&&null!=e.size&&e.size>r)throw new o(this.i18n("exceedsSize",{size:n(r),file:e.name}))
if(s&&null!=e.size&&e.size<s)throw new o(this.i18n("inferiorSize",{size:n(s)}))}validateMinNumberOfFiles(e){const{minNumberOfFiles:t}=this.getOpts().restrictions
if(Object.keys(e).length<t)throw new o(this.i18n("youHaveToAtLeastSelectX",{smart_count:t}))}getMissingRequiredMetaFields(e){const t=new o(this.i18n("missingRequiredMetaFieldOnFile",{fileName:e.name})),{requiredMetaFields:r}=this.getOpts().restrictions,n=Object.prototype.hasOwnProperty,i=[]
for(const o of r)n.call(e.meta,o)&&""!==e.meta[o]||i.push(o)
return{missingFields:i,error:t}}}},9297:(e,t,r)=>{"use strict"
var n=r(8633)
function i(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var o=0
const s=r(535),a=r(6023),l=r(4289)
var c=function(e){return"__private_"+o+++"_"+e}("updateUI")
class u extends l{constructor(){super(...arguments),Object.defineProperty(this,c,{writable:!0,value:void 0})}mount(e,t){const r=t.id,o=s(e)
if(o){this.isTargetDOMEl=!0
const t=document.createElement("div")
return t.classList.add("uppy-Root"),i(this,c)[c]=function(e){let t=null,r=null
return function(){for(var n=arguments.length,i=new Array(n),o=0;o<n;o++)i[o]=arguments[o]
return r=i,t||(t=Promise.resolve().then((()=>(t=null,e(...r))))),t}}((e=>{this.uppy.getPlugin(this.id)&&((0,n.render)(this.render(e),t),this.afterUpdate())})),this.uppy.log("Installing ".concat(r," to a DOM element '").concat(e,"'")),this.opts.replaceTargetContent&&(o.innerHTML=""),(0,n.render)(this.render(this.uppy.getState()),t),this.el=t,o.appendChild(t),t.dir=this.opts.direction||a(t)||"ltr",this.onMount(),this.el}let l
if("object"==typeof e&&e instanceof u)l=e
else if("function"==typeof e){const t=e
this.uppy.iteratePlugins((e=>{e instanceof t&&(l=e)}))}if(l)return this.uppy.log("Installing ".concat(r," to ").concat(l.id)),this.parent=l,this.el=l.addTarget(t),this.onMount(),this.el
this.uppy.log("Not installing ".concat(r))
let p="Invalid target option given to ".concat(r,".")
throw p+="function"==typeof e?" The given target is not a Plugin class. Please check that you're not specifying a React Component instead of a plugin. If you are using @uppy/* packages directly, make sure you have only 1 version of @uppy/core installed: run `npm ls @uppy/core` on the command line and verify that all the versions match and are deduped correctly.":"If you meant to target an HTML element, please make sure that the element exists. Check that the <script> tag initializing Uppy is right before the closing </body> tag at the end of the page. (see https://github.com/transloadit/uppy/issues/1042)\n\nIf you meant to target a plugin, please confirm that your `import` statements or `require` calls are correct.",new Error(p)}update(e){var t,r
null!=this.el&&(null==(t=(r=i(this,c))[c])||t.call(r,e))}unmount(){var e
this.isTargetDOMEl&&(null==(e=this.el)||e.remove()),this.onUnmount()}onMount(){}onUnmount(){}}e.exports=u},7555:(e,t,r)=>{"use strict"
var n=r(8773),i=r(826),o=r(2839)
let s,a
function l(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var c=0
function u(e){return"__private_"+c+++"_"+e}const p=r(2393),h=r(5575),d=r(7930),f=r(8415),m=r(9785),g=r(7316),v=r(9238),y=r(9732),b=r(7565),w=r(5844)
var k=u("plugins"),_=u("restricter"),x=u("storeUnsubscribe"),P=u("emitter"),S=u("preProcessors"),E=u("uploaders"),O=u("postProcessors"),A=u("informAndEmit"),C=u("checkRequiredMetaFieldsOnFile"),T=u("checkRequiredMetaFields"),L=u("assertNewUploadAllowed"),j=u("checkAndCreateFileStateObject"),I=u("startIfAutoProceed"),R=u("addListeners"),N=u("updateOnlineStatus"),U=u("createUpload"),F=u("getUpload"),M=u("removeUpload"),D=u("runUpload")
s=Symbol.for("uppy test: getPlugins"),a=Symbol.for("uppy test: createUpload")
class H{constructor(e){Object.defineProperty(this,D,{value:Y}),Object.defineProperty(this,M,{value:G}),Object.defineProperty(this,F,{value:X}),Object.defineProperty(this,U,{value:K}),Object.defineProperty(this,R,{value:W}),Object.defineProperty(this,I,{value:z}),Object.defineProperty(this,j,{value:$}),Object.defineProperty(this,L,{value:q}),Object.defineProperty(this,T,{value:V}),Object.defineProperty(this,C,{value:Z}),Object.defineProperty(this,A,{value:B}),Object.defineProperty(this,k,{writable:!0,value:Object.create(null)}),Object.defineProperty(this,_,{writable:!0,value:void 0}),Object.defineProperty(this,x,{writable:!0,value:void 0}),Object.defineProperty(this,P,{writable:!0,value:h()}),Object.defineProperty(this,S,{writable:!0,value:new Set}),Object.defineProperty(this,E,{writable:!0,value:new Set}),Object.defineProperty(this,O,{writable:!0,value:new Set}),Object.defineProperty(this,N,{writable:!0,value:this.updateOnlineStatus.bind(this)}),this.defaultLocale=w
const t={id:"uppy",autoProceed:!1,allowMultipleUploads:!0,allowMultipleUploadBatches:!0,debug:!1,restrictions:o.defaultOptions,meta:{},onBeforeFileAdded:e=>e,onBeforeUpload:e=>e,store:f(),logger:i.justErrorsLogger,infoTimeout:5e3}
this.opts={...t,...e,restrictions:{...t.restrictions,...e&&e.restrictions}},e&&e.logger&&e.debug?this.log("You are using a custom `logger`, but also set `debug: true`, which uses built-in logger to output logs to console. Ignoring `debug: true` and using your custom `logger`.","warning"):e&&e.debug&&(this.opts.logger=i.debugLogger),this.log("Using Core v".concat(this.constructor.VERSION)),this.i18nInit(),this.calculateProgress=d(this.calculateProgress.bind(this),500,{leading:!0,trailing:!0}),this.store=this.opts.store,this.setState({plugins:{},files:{},currentUploads:{},allowNewUpload:!0,capabilities:{uploadProgress:y(),individualCancellation:!0,resumableUploads:!1},totalProgress:0,meta:{...this.opts.meta},info:[],recoveredState:null}),l(this,_)[_]=new o.Restricter((()=>this.opts),this.i18n),l(this,x)[x]=this.store.subscribe(((e,t,r)=>{this.emit("state-update",e,t,r),this.updateAll(t)})),this.opts.debug&&"undefined"!=typeof window&&(window[this.opts.id]=this),l(this,R)[R]()}emit(e){for(var t=arguments.length,r=new Array(t>1?t-1:0),n=1;n<t;n++)r[n-1]=arguments[n]
l(this,P)[P].emit(e,...r)}on(e,t){return l(this,P)[P].on(e,t),this}once(e,t){return l(this,P)[P].once(e,t),this}off(e,t){return l(this,P)[P].off(e,t),this}updateAll(e){this.iteratePlugins((t=>{t.update(e)}))}setState(e){this.store.setState(e)}getState(){return this.store.getState()}get state(){return this.getState()}setFileState(e,t){if(!this.getState().files[e])throw new Error("Can’t set state for ".concat(e," (the file could have been removed)"))
this.setState({files:{...this.getState().files,[e]:{...this.getState().files[e],...t}}})}i18nInit(){const e=new p([this.defaultLocale,this.opts.locale])
this.i18n=e.translate.bind(e),this.i18nArray=e.translateArray.bind(e),this.locale=e.locale}setOptions(e){this.opts={...this.opts,...e,restrictions:{...this.opts.restrictions,...e&&e.restrictions}},e.meta&&this.setMeta(e.meta),this.i18nInit(),e.locale&&this.iteratePlugins((e=>{e.setOptions()})),this.setState()}resetProgress(){const e={percentage:0,bytesUploaded:0,uploadComplete:!1,uploadStarted:null},t={...this.getState().files},r={}
Object.keys(t).forEach((n=>{const i={...t[n]}
i.progress={...i.progress,...e},r[n]=i})),this.setState({files:r,totalProgress:0}),this.emit("reset-progress")}addPreProcessor(e){l(this,S)[S].add(e)}removePreProcessor(e){return l(this,S)[S].delete(e)}addPostProcessor(e){l(this,O)[O].add(e)}removePostProcessor(e){return l(this,O)[O].delete(e)}addUploader(e){l(this,E)[E].add(e)}removeUploader(e){return l(this,E)[E].delete(e)}setMeta(e){const t={...this.getState().meta,...e},r={...this.getState().files}
Object.keys(r).forEach((t=>{r[t]={...r[t],meta:{...r[t].meta,...e}}})),this.log("Adding metadata:"),this.log(e),this.setState({meta:t,files:r})}setFileMeta(e,t){const r={...this.getState().files}
if(!r[e])return void this.log("Was trying to set metadata for a file that has been removed: ",e)
const n={...r[e].meta,...t}
r[e]={...r[e],meta:n},this.setState({files:r})}getFile(e){return this.getState().files[e]}getFiles(){const{files:e}=this.getState()
return Object.values(e)}getObjectOfFilesPerState(){const{files:e,totalProgress:t,error:r}=this.getState(),n=Object.values(e),i=n.filter((e=>{let{progress:t}=e
return!t.uploadComplete&&t.uploadStarted})),o=n.filter((e=>!e.progress.uploadStarted)),s=n.filter((e=>e.progress.uploadStarted||e.progress.preprocess||e.progress.postprocess)),a=n.filter((e=>e.progress.uploadStarted)),l=n.filter((e=>e.isPaused)),c=n.filter((e=>e.progress.uploadComplete)),u=n.filter((e=>e.error)),p=i.filter((e=>!e.isPaused)),h=n.filter((e=>e.progress.preprocess||e.progress.postprocess))
return{newFiles:o,startedFiles:s,uploadStartedFiles:a,pausedFiles:l,completeFiles:c,erroredFiles:u,inProgressFiles:i,inProgressNotPausedFiles:p,processingFiles:h,isUploadStarted:a.length>0,isAllComplete:100===t&&c.length===n.length&&0===h.length,isAllErrored:!!r&&u.length===n.length,isAllPaused:0!==i.length&&l.length===i.length,isUploadInProgress:i.length>0,isSomeGhost:n.some((e=>e.isGhost))}}validateRestrictions(e,t){void 0===t&&(t=this.getFiles())
try{return l(this,_)[_].validate(e,t),{result:!0}}catch(e){return{result:!1,reason:e.message}}}checkIfFileAlreadyExists(e){const{files:t}=this.getState()
return!(!t[e]||t[e].isGhost)}addFile(e){l(this,L)[L](e)
const{files:t}=this.getState()
let r=l(this,j)[j](t,e)
return t[r.id]&&t[r.id].isGhost&&(r={...t[r.id],data:e.data,isGhost:!1},this.log("Replaced the blob in the restored ghost file: ".concat(r.name,", ").concat(r.id))),this.setState({files:{...t,[r.id]:r}}),this.emit("file-added",r),this.emit("files-added",[r]),this.log("Added file: ".concat(r.name,", ").concat(r.id,", mime type: ").concat(r.type)),l(this,I)[I](),r.id}addFiles(e){l(this,L)[L]()
const t={...this.getState().files},r=[],n=[]
for(let i=0;i<e.length;i++)try{let n=l(this,j)[j](t,e[i])
t[n.id]&&t[n.id].isGhost&&(n={...t[n.id],data:e[i].data,isGhost:!1},this.log("Replaced blob in a ghost file: ".concat(n.name,", ").concat(n.id))),t[n.id]=n,r.push(n)}catch(e){e.isRestriction||n.push(e)}if(this.setState({files:t}),r.forEach((e=>{this.emit("file-added",e)})),this.emit("files-added",r),r.length>5?this.log("Added batch of ".concat(r.length," files")):Object.keys(r).forEach((e=>{this.log("Added file: ".concat(r[e].name,"\n id: ").concat(r[e].id,"\n type: ").concat(r[e].type))})),r.length>0&&l(this,I)[I](),n.length>0){let e="Multiple errors occurred while adding files:\n"
if(n.forEach((t=>{e+="\n * ".concat(t.message)})),this.info({message:this.i18n("addBulkFilesFailed",{smart_count:n.length}),details:e},"error",this.opts.infoTimeout),"function"==typeof AggregateError)throw new AggregateError(n,e)
{const t=new Error(e)
throw t.errors=n,t}}}removeFiles(e,t){const{files:r,currentUploads:n}=this.getState(),i={...r},o={...n},s=Object.create(null)
function a(e){return void 0===s[e]}e.forEach((e=>{r[e]&&(s[e]=r[e],delete i[e])})),Object.keys(o).forEach((e=>{const t=n[e].fileIDs.filter(a)
0!==t.length?o[e]={...n[e],fileIDs:t}:delete o[e]}))
const l={currentUploads:o,files:i}
0===Object.keys(i).length&&(l.allowNewUpload=!0,l.error=null,l.recoveredState=null),this.setState(l),this.calculateTotalProgress()
const c=Object.keys(s)
c.forEach((e=>{this.emit("file-removed",s[e],t)})),c.length>5?this.log("Removed ".concat(c.length," files")):this.log("Removed files: ".concat(c.join(", ")))}removeFile(e,t){void 0===t&&(t=null),this.removeFiles([e],t)}pauseResume(e){if(!this.getState().capabilities.resumableUploads||this.getFile(e).uploadComplete)return
const t=!this.getFile(e).isPaused
return this.setFileState(e,{isPaused:t}),this.emit("upload-pause",e,t),t}pauseAll(){const e={...this.getState().files}
Object.keys(e).filter((t=>!e[t].progress.uploadComplete&&e[t].progress.uploadStarted)).forEach((t=>{const r={...e[t],isPaused:!0}
e[t]=r})),this.setState({files:e}),this.emit("pause-all")}resumeAll(){const e={...this.getState().files}
Object.keys(e).filter((t=>!e[t].progress.uploadComplete&&e[t].progress.uploadStarted)).forEach((t=>{const r={...e[t],isPaused:!1,error:null}
e[t]=r})),this.setState({files:e}),this.emit("resume-all")}retryAll(){const e={...this.getState().files},t=Object.keys(e).filter((t=>e[t].error))
if(t.forEach((t=>{const r={...e[t],isPaused:!1,error:null}
e[t]=r})),this.setState({files:e,error:null}),this.emit("retry-all",t),0===t.length)return Promise.resolve({successful:[],failed:[]})
const r=l(this,U)[U](t,{forceAllowNewUpload:!0})
return l(this,D)[D](r)}cancelAll(e){let{reason:t="user"}=void 0===e?{}:e
if(this.emit("cancel-all",{reason:t}),"user"===t){const{files:e}=this.getState(),t=Object.keys(e)
t.length&&this.removeFiles(t,"cancel-all"),this.setState({totalProgress:0,error:null,recoveredState:null})}}retryUpload(e){this.setFileState(e,{error:null,isPaused:!1}),this.emit("upload-retry",e)
const t=l(this,U)[U]([e],{forceAllowNewUpload:!0})
return l(this,D)[D](t)}reset(){this.cancelAll(...arguments)}logout(){this.iteratePlugins((e=>{e.provider&&e.provider.logout&&e.provider.logout()}))}calculateProgress(e,t){if(null==e||!this.getFile(e.id))return void this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))
const r=Number.isFinite(t.bytesTotal)&&t.bytesTotal>0
this.setFileState(e.id,{progress:{...this.getFile(e.id).progress,bytesUploaded:t.bytesUploaded,bytesTotal:t.bytesTotal,percentage:r?Math.round(t.bytesUploaded/t.bytesTotal*100):0}}),this.calculateTotalProgress()}calculateTotalProgress(){const e=this.getFiles().filter((e=>e.progress.uploadStarted||e.progress.preprocess||e.progress.postprocess))
if(0===e.length)return this.emit("progress",0),void this.setState({totalProgress:0})
const t=e.filter((e=>null!=e.progress.bytesTotal)),r=e.filter((e=>null==e.progress.bytesTotal))
if(0===t.length){const t=100*e.length,n=r.reduce(((e,t)=>e+t.progress.percentage),0),i=Math.round(n/t*100)
return void this.setState({totalProgress:i})}let n=t.reduce(((e,t)=>e+t.progress.bytesTotal),0)
const i=n/t.length
n+=i*r.length
let o=0
t.forEach((e=>{o+=e.progress.bytesUploaded})),r.forEach((e=>{o+=i*(e.progress.percentage||0)/100}))
let s=0===n?0:Math.round(o/n*100)
s>100&&(s=100),this.setState({totalProgress:s}),this.emit("progress",s)}updateOnlineStatus(){void 0===window.navigator.onLine||window.navigator.onLine?(this.emit("is-online"),this.wasOffline&&(this.emit("back-online"),this.info(this.i18n("connectedToInternet"),"success",3e3),this.wasOffline=!1)):(this.emit("is-offline"),this.info(this.i18n("noInternetConnection"),"error",0),this.wasOffline=!0)}getID(){return this.opts.id}use(e,t){if("function"!=typeof e){const t="Expected a plugin class, but got ".concat(null===e?"null":typeof e,".")+" Please verify that the plugin was imported and spelled correctly."
throw new TypeError(t)}const r=new e(this,t),n=r.id
if(!n)throw new Error("Your plugin must have an id")
if(!r.type)throw new Error("Your plugin must have a type")
const i=this.getPlugin(n)
if(i){const e="Already found a plugin named '".concat(i.id,"'. ")+"Tried to use: '".concat(n,"'.\n")+"Uppy plugins must have unique `id` options. See https://uppy.io/docs/plugins/#id."
throw new Error(e)}return e.VERSION&&this.log("Using ".concat(n," v").concat(e.VERSION)),r.type in l(this,k)[k]?l(this,k)[k][r.type].push(r):l(this,k)[k][r.type]=[r],r.install(),this}getPlugin(e){for(const t of Object.values(l(this,k)[k])){const r=t.find((t=>t.id===e))
if(null!=r)return r}}[s](e){return l(this,k)[k][e]}iteratePlugins(e){Object.values(l(this,k)[k]).flat(1).forEach(e)}removePlugin(e){this.log("Removing plugin ".concat(e.id)),this.emit("plugin-remove",e),e.uninstall&&e.uninstall()
const t=l(this,k)[k][e.type],r=t.findIndex((t=>t.id===e.id));-1!==r&&t.splice(r,1)
const n={plugins:{...this.getState().plugins,[e.id]:void 0}}
this.setState(n)}close(e){let{reason:t}=void 0===e?{}:e
this.log("Closing Uppy instance ".concat(this.opts.id,": removing all files and uninstalling plugins")),this.cancelAll({reason:t}),l(this,x)[x](),this.iteratePlugins((e=>{this.removePlugin(e)})),"undefined"!=typeof window&&window.removeEventListener&&(window.removeEventListener("online",l(this,N)[N]),window.removeEventListener("offline",l(this,N)[N]))}hideInfo(){const{info:e}=this.getState()
this.setState({info:e.slice(1)}),this.emit("info-hidden")}info(e,t,r){void 0===t&&(t="info"),void 0===r&&(r=3e3)
const n="object"==typeof e
this.setState({info:[...this.getState().info,{type:t,message:n?e.message:e,details:n?e.details:null}]}),setTimeout((()=>this.hideInfo()),r),this.emit("info-visible")}log(e,t){const{logger:r}=this.opts
switch(t){case"error":r.error(e)
break
case"warning":r.warn(e)
break
default:r.debug(e)}}restore(e){return this.log('Core: attempting to restore upload "'.concat(e,'"')),this.getState().currentUploads[e]?l(this,D)[D](e):(l(this,M)[M](e),Promise.reject(new Error("Nonexistent upload")))}[a](){return l(this,U)[U](...arguments)}addResultData(e,t){if(!l(this,F)[F](e))return void this.log("Not setting result for an upload that has been removed: ".concat(e))
const{currentUploads:r}=this.getState(),n={...r[e],result:{...r[e].result,...t}}
this.setState({currentUploads:{...r,[e]:n}})}upload(){var e
null!=(e=l(this,k)[k].uploader)&&e.length||this.log("No uploader type plugins are used","warning")
let{files:t}=this.getState()
const r=this.opts.onBeforeUpload(t)
return!1===r?Promise.reject(new Error("Not starting the upload because onBeforeUpload returned false")):(r&&"object"==typeof r&&(t=r,this.setState({files:t})),Promise.resolve().then((()=>l(this,_)[_].validateMinNumberOfFiles(t))).catch((e=>{throw l(this,A)[A](e),e})).then((()=>{if(!l(this,T)[T](t))throw new o.RestrictionError(this.i18n("missingRequiredMetaField"))})).catch((e=>{throw e})).then((()=>{const{currentUploads:e}=this.getState(),r=Object.values(e).flatMap((e=>e.fileIDs)),n=[]
Object.keys(t).forEach((e=>{const t=this.getFile(e)
t.progress.uploadStarted||-1!==r.indexOf(e)||n.push(t.id)}))
const i=l(this,U)[U](n)
return l(this,D)[D](i)})).catch((e=>{throw this.emit("error",e),this.log(e,"error"),e})))}}function B(e,t){const{message:r,details:n=""}=e
e.isRestriction?this.emit("restriction-failed",t,e):this.emit("error",e),this.info({message:r,details:n},"error",this.opts.infoTimeout),this.log("".concat(r," ").concat(n).trim(),"error")}function Z(e){const{missingFields:t,error:r}=l(this,_)[_].getMissingRequiredMetaFields(e)
return!(t.length>0&&(this.setFileState(e.id,{missingRequiredMetaFields:t}),this.log(r.message),this.emit("restriction-failed",e,r),1))}function V(e){let t=!0
for(const r of Object.values(e))l(this,C)[C](r)||(t=!1)
return t}function q(e){const{allowNewUpload:t}=this.getState()
if(!1===t){const t=new o.RestrictionError(this.i18n("noMoreFilesAllowed"))
throw l(this,A)[A](t,e),t}}function $(e,t){const r=m(t),n=b(r,t),i=g(n).extension,s=Boolean(t.isRemote),a=v({...t,type:r})
if(this.checkIfFileAlreadyExists(a)){const e=new o.RestrictionError(this.i18n("noDuplicates",{fileName:n}))
throw l(this,A)[A](e,t),e}const c=t.meta||{}
c.name=n,c.type=r
const u=Number.isFinite(t.data.size)?t.data.size:null
let p={source:t.source||"",id:a,name:n,extension:i||"",meta:{...this.getState().meta,...c},type:r,data:t.data,progress:{percentage:0,bytesUploaded:0,bytesTotal:u,uploadComplete:!1,uploadStarted:null},size:u,isRemote:s,remote:t.remote||"",preview:t.preview}
const h=this.opts.onBeforeFileAdded(p,e)
if(!1===h){const e=new o.RestrictionError("Cannot add the file because onBeforeFileAdded returned false.")
throw this.emit("restriction-failed",t,e),e}"object"==typeof h&&null!==h&&(p=h)
try{const t=Object.keys(e).map((t=>e[t]))
l(this,_)[_].validate(p,t)}catch(e){throw l(this,A)[A](e,p),e}return p}function z(){this.opts.autoProceed&&!this.scheduledAutoProceed&&(this.scheduledAutoProceed=setTimeout((()=>{this.scheduledAutoProceed=null,this.upload().catch((e=>{e.isRestriction||this.log(e.stack||e.message||e)}))}),4))}function W(){const e=(e,t,r)=>{let n=e.message||"Unknown error"
e.details&&(n+=" ".concat(e.details)),this.setState({error:n}),null!=t&&t.id in this.getState().files&&this.setFileState(t.id,{error:n,response:r})}
this.on("error",e),this.on("upload-error",((t,r,n)=>{if(e(r,t,n),"object"==typeof r&&r.message){const e=new Error(r.message)
e.details=r.message,r.details&&(e.details+=" ".concat(r.details)),e.message=this.i18n("failedToUpload",{file:null==t?void 0:t.name}),l(this,A)[A](e)}else l(this,A)[A](r)})),this.on("upload",(()=>{this.setState({error:null})})),this.on("upload-started",(e=>{null!=e&&this.getFile(e.id)?this.setFileState(e.id,{progress:{uploadStarted:Date.now(),uploadComplete:!1,percentage:0,bytesUploaded:0,bytesTotal:e.size}}):this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))})),this.on("upload-progress",this.calculateProgress),this.on("upload-success",((e,t)=>{if(null==e||!this.getFile(e.id))return void this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))
const r=this.getFile(e.id).progress
this.setFileState(e.id,{progress:{...r,postprocess:l(this,O)[O].size>0?{mode:"indeterminate"}:null,uploadComplete:!0,percentage:100,bytesUploaded:r.bytesTotal},response:t,uploadURL:t.uploadURL,isPaused:!1}),null==e.size&&this.setFileState(e.id,{size:t.bytesUploaded||r.bytesTotal}),this.calculateTotalProgress()})),this.on("preprocess-progress",((e,t)=>{null!=e&&this.getFile(e.id)?this.setFileState(e.id,{progress:{...this.getFile(e.id).progress,preprocess:t}}):this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))})),this.on("preprocess-complete",(e=>{if(null==e||!this.getFile(e.id))return void this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))
const t={...this.getState().files}
t[e.id]={...t[e.id],progress:{...t[e.id].progress}},delete t[e.id].progress.preprocess,this.setState({files:t})})),this.on("postprocess-progress",((e,t)=>{null!=e&&this.getFile(e.id)?this.setFileState(e.id,{progress:{...this.getState().files[e.id].progress,postprocess:t}}):this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))})),this.on("postprocess-complete",(e=>{if(null==e||!this.getFile(e.id))return void this.log("Not setting progress for a file that has been removed: ".concat(null==e?void 0:e.id))
const t={...this.getState().files}
t[e.id]={...t[e.id],progress:{...t[e.id].progress}},delete t[e.id].progress.postprocess,this.setState({files:t})})),this.on("restored",(()=>{this.calculateTotalProgress()})),this.on("dashboard:file-edit-complete",(e=>{e&&l(this,C)[C](e)})),"undefined"!=typeof window&&window.addEventListener&&(window.addEventListener("online",l(this,N)[N]),window.addEventListener("offline",l(this,N)[N]),setTimeout(l(this,N)[N],3e3))}function K(e,t){void 0===t&&(t={})
const{forceAllowNewUpload:r=!1}=t,{allowNewUpload:i,currentUploads:o}=this.getState()
if(!i&&!r)throw new Error("Cannot create a new upload: already uploading.")
const s=(0,n.nanoid)()
return this.emit("upload",{id:s,fileIDs:e}),this.setState({allowNewUpload:!1!==this.opts.allowMultipleUploadBatches&&!1!==this.opts.allowMultipleUploads,currentUploads:{...o,[s]:{fileIDs:e,step:0,result:{}}}}),s}function X(e){const{currentUploads:t}=this.getState()
return t[e]}function G(e){const t={...this.getState().currentUploads}
delete t[e],this.setState({currentUploads:t})}async function Y(e){let{currentUploads:t}=this.getState(),r=t[e]
const n=r.step||0,i=[...l(this,S)[S],...l(this,E)[E],...l(this,O)[O]]
try{for(let o=n;o<i.length&&r;o++){const n=i[o],s={...r,step:o}
this.setState({currentUploads:{...t,[e]:s}}),await n(s.fileIDs,e),t=this.getState().currentUploads,r=t[e]}}catch(t){throw l(this,M)[M](e),t}if(r){r.fileIDs.forEach((e=>{const t=this.getFile(e)
t&&t.progress.postprocess&&this.emit("postprocess-complete",t)}))
const n=r.fileIDs.map((e=>this.getFile(e))),i=n.filter((e=>!e.error)),o=n.filter((e=>e.error))
await this.addResultData(e,{successful:i,failed:o,uploadID:e}),t=this.getState().currentUploads,r=t[e]}let o
return r&&(o=r.result,this.emit("complete",o),l(this,M)[M](e)),null==o&&this.log("Not setting result for an upload that has been removed: ".concat(e)),o}H.VERSION="2.3.1",e.exports=H},7565:e=>{"use strict"
e.exports=function(e,t){return t.name?t.name:"image"===e.split("/")[0]?"".concat(e.split("/")[0],".").concat(e.split("/")[1]):"noname"}},3289:(e,t,r)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.Uppy=t.UIPlugin=t.BasePlugin=void 0,Object.defineProperty(t,"debugLogger",{enumerable:!0,get:function(){return n.debugLogger}})
var n=r(826)
e.exports=r(7555)
const i=r(9297)
t.UIPlugin=i
const o=r(4289)
t.BasePlugin=o
const s=r(7555)
t.Uppy=s
const a=r(9297),l=r(4289)
s.Uppy=s,s.UIPlugin=a,s.BasePlugin=l,s.debugLogger=n.debugLogger},5844:e=>{"use strict"
e.exports={strings:{addBulkFilesFailed:{0:"Failed to add %{smart_count} file due to an internal error",1:"Failed to add %{smart_count} files due to internal errors"},youCanOnlyUploadX:{0:"You can only upload %{smart_count} file",1:"You can only upload %{smart_count} files"},youHaveToAtLeastSelectX:{0:"You have to select at least %{smart_count} file",1:"You have to select at least %{smart_count} files"},exceedsSize:"%{file} exceeds maximum allowed size of %{size}",missingRequiredMetaField:"Missing required meta fields",missingRequiredMetaFieldOnFile:"Missing required meta fields in %{fileName}",inferiorSize:"This file is smaller than the allowed size of %{size}",youCanOnlyUploadFileTypes:"You can only upload: %{types}",noMoreFilesAllowed:"Cannot add more files",noDuplicates:"Cannot add the duplicate file '%{fileName}', it already exists",companionError:"Connection with Companion failed",authAborted:"Authentication aborted",companionUnauthorizeHint:"To unauthorize to your %{provider} account, please go to %{url}",failedToUpload:"Failed to upload %{file}",noInternetConnection:"No Internet connection",connectedToInternet:"Connected to the Internet",noFilesFound:"You have no files or folders here",selectX:{0:"Select %{smart_count}",1:"Select %{smart_count}"},allFilesFromFolderNamed:"All files from folder %{name}",openFolderNamed:"Open folder %{name}",cancel:"Cancel",logOut:"Log out",filter:"Filter",resetFilter:"Reset filter",loading:"Loading...",authenticateWithTitle:"Please authenticate with %{pluginName} to select files",authenticateWith:"Connect to %{pluginName}",signInWithGoogle:"Sign in with Google",searchImages:"Search for images",enterTextToSearch:"Enter text to search for images",search:"Search",emptyFolderAdded:"No files were added from empty folder",folderAlreadyAdded:'The folder "%{folder}" was already added',folderAdded:{0:"Added %{smart_count} file from %{folder}",1:"Added %{smart_count} files from %{folder}"}}}},826:(e,t,r)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.justErrorsLogger=t.debugLogger=void 0
const n=r(909),i={debug:()=>{},warn:()=>{},error:function(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
return console.error("[Uppy] [".concat(n(),"]"),...t)}}
t.justErrorsLogger=i
const o={debug:function(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
return console.debug("[Uppy] [".concat(n(),"]"),...t)},warn:function(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
return console.warn("[Uppy] [".concat(n(),"]"),...t)},error:function(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
return console.error("[Uppy] [".concat(n(),"]"),...t)}}
t.debugLogger=o},9732:e=>{"use strict"
e.exports=function(e){if(null==e&&"undefined"!=typeof navigator&&(e=navigator.userAgent),!e)return!0
const t=/Edge\/(\d+\.\d+)/.exec(e)
if(!t)return!0
const r=t[1]
let[n,i]=r.split(".")
return n=parseInt(n,10),i=parseInt(i,10),n<15||15===n&&i<15063||n>18||18===n&&i>=18218}},8515:(e,t,r)=>{"use strict"
const n=r(4289),i=r(9668),o=r(2658)
function s(e){var t,r
return null!=(t=null==(r=e.dataTransfer.types)?void 0:r.some((e=>"Files"===e)))&&t}class a extends n{constructor(e,t){super(e,t),this.addFiles=e=>{const t=e.map((e=>({source:this.id,name:e.name,type:e.type,data:e,meta:{relativePath:e.relativePath||null}})))
try{this.uppy.addFiles(t)}catch(e){this.uppy.log(e)}},this.isFileTransfer=s,this.handleDrop=async e=>{var t,r
if(!this.isFileTransfer(e))return
e.preventDefault(),e.stopPropagation(),clearTimeout(this.removeDragOverClassTimeout),e.currentTarget.classList.remove("uppy-is-drag-over"),this.setPluginState({isDraggingOver:!1}),this.uppy.iteratePlugins((t=>{"acquirer"===t.type&&(null==t.handleRootDrop||t.handleRootDrop(e))}))
let n=!1
const o=await i(e.dataTransfer,{logDropError:e=>{this.uppy.log(e,"error"),n||(this.uppy.info(e.message,"error"),n=!0)}})
o.length>0&&(this.uppy.log("[DropTarget] Files were dropped"),this.addFiles(o)),null==(t=(r=this.opts).onDrop)||t.call(r,e)},this.handleDragOver=e=>{var t,r
this.isFileTransfer(e)&&(e.preventDefault(),e.stopPropagation(),e.dataTransfer.dropEffect="copy",clearTimeout(this.removeDragOverClassTimeout),e.currentTarget.classList.add("uppy-is-drag-over"),this.setPluginState({isDraggingOver:!0}),null==(t=(r=this.opts).onDragOver)||t.call(r,e))},this.handleDragLeave=e=>{var t,r
if(!this.isFileTransfer(e))return
e.preventDefault(),e.stopPropagation()
const{currentTarget:n}=e
clearTimeout(this.removeDragOverClassTimeout),this.removeDragOverClassTimeout=setTimeout((()=>{n.classList.remove("uppy-is-drag-over"),this.setPluginState({isDraggingOver:!1})}),50),null==(t=(r=this.opts).onDragLeave)||t.call(r,e)},this.addListeners=()=>{const{target:e}=this.opts
if(e instanceof Element?this.nodes=[e]:"string"==typeof e&&(this.nodes=o(document.querySelectorAll(e))),!this.nodes&&!this.nodes.length>0)throw new Error('"'.concat(e,'" does not match any HTML elements'))
this.nodes.forEach((e=>{e.addEventListener("dragover",this.handleDragOver,!1),e.addEventListener("dragleave",this.handleDragLeave,!1),e.addEventListener("drop",this.handleDrop,!1)}))},this.removeListeners=()=>{this.nodes&&this.nodes.forEach((e=>{e.removeEventListener("dragover",this.handleDragOver,!1),e.removeEventListener("dragleave",this.handleDragLeave,!1),e.removeEventListener("drop",this.handleDrop,!1)}))},this.type="acquirer",this.id=this.opts.id||"DropTarget",this.title="Drop Target",this.opts={target:null,...t},this.removeDragOverClassTimeout=null}install(){this.setPluginState({isDraggingOver:!1}),this.addListeners()}uninstall(){this.removeListeners()}}a.VERSION="1.1.3",e.exports=a},8415:e=>{"use strict"
var t=0
var r=function(e){return"__private_"+t+++"_"+e}("publish")
class n{constructor(){Object.defineProperty(this,r,{value:i}),this.state={},this.callbacks=[]}getState(){return this.state}setState(e){const t={...this.state},n={...this.state,...e}
this.state=n,function(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}(this,r)[r](t,n,e)}subscribe(e){return this.callbacks.push(e),()=>{this.callbacks.splice(this.callbacks.indexOf(e),1)}}}function i(){for(var e=arguments.length,t=new Array(e),r=0;r<e;r++)t[r]=arguments[r]
this.callbacks.forEach((e=>{e(...t)}))}n.VERSION="2.1.0",e.exports=function(){return new n}},2651:(e,t)=>{"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.createAbortError=t.AbortSignal=t.AbortController=void 0
const{AbortController:r}=globalThis
t.AbortController=r
const{AbortSignal:n}=globalThis
t.AbortSignal=n,t.createAbortError=function(e){return void 0===e&&(e="Aborted"),new DOMException(e,"AbortError")}},9854:(e,t,r)=>{"use strict"
const n=r(2398)
class i extends Error{constructor(e,t){void 0===t&&(t={}),super(e),this.cause=t.cause,this.cause&&n(this.cause,"isNetworkError")&&(this.isNetworkError=this.cause.isNetworkError)}}e.exports=i},7035:e=>{"use strict"
function t(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var r=0
function n(e){return"__private_"+r+++"_"+e}var i=n("emitter"),o=n("events")
e.exports=class{constructor(e){Object.defineProperty(this,i,{writable:!0,value:void 0}),Object.defineProperty(this,o,{writable:!0,value:[]}),t(this,i)[i]=e}on(e,r){return t(this,o)[o].push([e,r]),t(this,i)[i].on(e,r)}remove(){for(const[e,r]of t(this,o)[o].splice(0))t(this,i)[i].off(e,r)}}},9319:e=>{"use strict"
class t extends Error{constructor(e,t){void 0===t&&(t=null),super("This looks like a network error, the endpoint might be blocked by an internet provider or a firewall."),this.cause=e,this.isNetworkError=!0,this.request=t}}e.exports=t},8008:e=>{"use strict"
function t(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var r=0
function n(e){return"__private_"+r+++"_"+e}var i=n("aliveTimer"),o=n("isDone"),s=n("onTimedOut"),a=n("timeout")
e.exports=class{constructor(e,r){Object.defineProperty(this,i,{writable:!0,value:void 0}),Object.defineProperty(this,o,{writable:!0,value:!1}),Object.defineProperty(this,s,{writable:!0,value:void 0}),Object.defineProperty(this,a,{writable:!0,value:void 0}),t(this,a)[a]=e,t(this,s)[s]=r}progress(){t(this,o)[o]||t(this,a)[a]>0&&(clearTimeout(t(this,i)[i]),t(this,i)[i]=setTimeout(t(this,s)[s],t(this,a)[a]))}done(){t(this,o)[o]||(clearTimeout(t(this,i)[i]),t(this,i)[i]=null,t(this,o)[o]=!0)}}},62:(e,t)=>{"use strict"
function r(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}Object.defineProperty(t,"__esModule",{value:!0}),t.internalRateLimitedQueue=t.RateLimitedQueue=void 0
var n=0
function i(e){return"__private_"+n+++"_"+e}function o(){return new Error("Cancelled")}var s=i("activeRequests"),a=i("queuedHandlers"),l=i("paused"),c=i("pauseTimer"),u=i("downLimit"),p=i("upperLimit"),h=i("rateLimitingTimer"),d=i("call"),f=i("queueNext"),m=i("next"),g=i("queue"),v=i("dequeue"),y=i("resume"),b=i("increaseLimit")
function w(e){r(this,s)[s]+=1
let t,n=!1
try{t=e()}catch(e){throw r(this,s)[s]-=1,e}return{abort:()=>{n||(n=!0,r(this,s)[s]-=1,t(),r(this,f)[f]())},done:()=>{n||(n=!0,r(this,s)[s]-=1,r(this,f)[f]())}}}function k(){queueMicrotask((()=>r(this,m)[m]()))}function _(){if(r(this,l)[l]||r(this,s)[s]>=this.limit)return
if(0===r(this,a)[a].length)return
const e=r(this,a)[a].shift(),t=r(this,d)[d](e.fn)
e.abort=t.abort,e.done=t.done}function x(e,t){void 0===t&&(t={})
const n={fn:e,priority:t.priority||0,abort:()=>{r(this,v)[v](n)},done:()=>{throw new Error("Cannot mark a queued request as done: this indicates a bug")}},i=r(this,a)[a].findIndex((e=>n.priority>e.priority))
return-1===i?r(this,a)[a].push(n):r(this,a)[a].splice(i,0,n),n}function P(e){const t=r(this,a)[a].indexOf(e);-1!==t&&r(this,a)[a].splice(t,1)}t.RateLimitedQueue=class{constructor(e){Object.defineProperty(this,v,{value:P}),Object.defineProperty(this,g,{value:x}),Object.defineProperty(this,m,{value:_}),Object.defineProperty(this,f,{value:k}),Object.defineProperty(this,d,{value:w}),Object.defineProperty(this,s,{writable:!0,value:0}),Object.defineProperty(this,a,{writable:!0,value:[]}),Object.defineProperty(this,l,{writable:!0,value:!1}),Object.defineProperty(this,c,{writable:!0,value:void 0}),Object.defineProperty(this,u,{writable:!0,value:1}),Object.defineProperty(this,p,{writable:!0,value:void 0}),Object.defineProperty(this,h,{writable:!0,value:void 0}),Object.defineProperty(this,y,{writable:!0,value:()=>this.resume()}),Object.defineProperty(this,b,{writable:!0,value:()=>{if(r(this,l)[l])r(this,h)[h]=setTimeout(r(this,b)[b],0)
else{r(this,u)[u]=this.limit,this.limit=Math.ceil((r(this,p)[p]+r(this,u)[u])/2)
for(let e=r(this,u)[u];e<=this.limit;e++)r(this,f)[f]()
r(this,p)[p]-r(this,u)[u]>3?r(this,h)[h]=setTimeout(r(this,b)[b],2e3):r(this,u)[u]=Math.floor(r(this,u)[u]/2)}}}),this.limit="number"!=typeof e||0===e?1/0:e}run(e,t){return!r(this,l)[l]&&r(this,s)[s]<this.limit?r(this,d)[d](e):r(this,g)[g](e,t)}wrapPromiseFunction(e,t){var r=this
return function(){for(var n=arguments.length,i=new Array(n),s=0;s<n;s++)i[s]=arguments[s]
let a
const l=new Promise(((n,s)=>{a=r.run((()=>{let t,r
try{r=Promise.resolve(e(...i))}catch(e){r=Promise.reject(e)}return r.then((e=>{t?s(t):(a.done(),n(e))}),(e=>{t?s(t):(a.done(),s(e))})),()=>{t=o()}}),t)}))
return l.abort=()=>{a.abort()},l}}resume(){r(this,l)[l]=!1,clearTimeout(r(this,c)[c])
for(let e=0;e<this.limit;e++)r(this,f)[f]()}pause(e){void 0===e&&(e=null),r(this,l)[l]=!0,clearTimeout(r(this,c)[c]),null!=e&&(r(this,c)[c]=setTimeout(r(this,y)[y],e))}rateLimit(e){clearTimeout(r(this,h)[h]),this.pause(e),this.limit>1&&Number.isFinite(this.limit)&&(r(this,p)[p]=this.limit-1,this.limit=r(this,u)[u],r(this,h)[h]=setTimeout(r(this,b)[b],e))}get isPaused(){return r(this,l)[l]}}
const S=Symbol("__queue")
t.internalRateLimitedQueue=S},2393:(e,t,r)=>{"use strict"
function n(e,t){if(!Object.prototype.hasOwnProperty.call(e,t))throw new TypeError("attempted to use private field on non-instance")
return e}var i=0
const o=r(2398)
function s(e,t,r){const n=[]
return e.forEach((e=>"string"!=typeof e?n.push(e):t[Symbol.split](e).forEach(((e,t,i)=>{""!==e&&n.push(e),t<i.length-1&&n.push(r)})))),n}function a(e,t){const r=/\$/g
let n=[e]
if(null==t)return n
for(const i of Object.keys(t))if("_"!==i){let e=t[i]
"string"==typeof e&&(e=r[Symbol.replace](e,"$$$$")),n=s(n,new RegExp("%\\{".concat(i,"\\}"),"g"),e)}return n}var l=function(e){return"__private_"+i+++"_"+e}("apply")
function c(e){if(null==e||!e.strings)return
const t=this.locale
this.locale={...t,strings:{...t.strings,...e.strings}},this.locale.pluralize=e.pluralize||t.pluralize}e.exports=class{constructor(e){Object.defineProperty(this,l,{value:c}),this.locale={strings:{},pluralize:e=>1===e?0:1},Array.isArray(e)?e.forEach(n(this,l)[l],this):n(this,l)[l](e)}translate(e,t){return this.translateArray(e,t).join("")}translateArray(e,t){if(!o(this.locale.strings,e))throw new Error("missing string: ".concat(e))
const r=this.locale.strings[e]
if("object"==typeof r){if(t&&void 0!==t.smart_count)return a(r[this.locale.pluralize(t.smart_count)],t)
throw new Error("Attempted to use a string with plural forms, but no value was given for %{smart_count}")}return a(r,t)}}},3731:(e,t,r)=>{"use strict"
var n=r(2651)
e.exports=function(e,t){return new Promise(((r,i)=>{var o,s
if(null!=t&&null!=(o=t.signal)&&o.aborted)return i((0,n.createAbortError)())
const a=setTimeout((()=>{c(),r()}),e)
function l(){clearTimeout(a),c(),i((0,n.createAbortError)())}function c(){var e
null==t||null==(e=t.signal)||e.removeEventListener("abort",l)}null==t||null==(s=t.signal)||s.addEventListener("abort",l)}))}},9906:(e,t,r)=>{"use strict"
const n=r(7930)
e.exports=n((function(e,t,r){const{progress:n,bytesUploaded:i,bytesTotal:o}=t
n&&(e.uppy.log("Upload progress: ".concat(n)),e.uppy.emit("upload-progress",r,{uploader:e,bytesUploaded:i,bytesTotal:o}))}),300,{leading:!0,trailing:!0})},274:(e,t,r)=>{"use strict"
const n=r(9319)
e.exports=function(){return fetch(...arguments).catch((e=>{throw"AbortError"===e.name?e:new n(e)}))}},535:(e,t,r)=>{"use strict"
const n=r(9601)
e.exports=function(e,t){return void 0===t&&(t=document),"string"==typeof e?t.querySelector(e):n(e)?e:null}},9238:e=>{"use strict"
function t(e){let t=""
return e.replace(/[^A-Z0-9]/gi,(e=>(t+="-".concat(function(e){return e.charCodeAt(0).toString(32)}(e)),"/")))+t}e.exports=function(e){let r="uppy"
return"string"==typeof e.name&&(r+="-".concat(t(e.name.toLowerCase()))),void 0!==e.type&&(r+="-".concat(e.type)),e.meta&&"string"==typeof e.meta.relativePath&&(r+="-".concat(t(e.meta.relativePath.toLowerCase()))),void 0!==e.data.size&&(r+="-".concat(e.data.size)),void 0!==e.data.lastModified&&(r+="-".concat(e.data.lastModified)),r}},9668:(e,t,r)=>{"use strict"
const n=r(7762),i=r(934)
e.exports=function(e,t){var r
let{logDropError:o=(()=>{})}=void 0===t?{}:t
return null!=(r=e.items)&&r[0]&&"webkitGetAsEntry"in e.items[0]?n(e,o):i(e)}},934:(e,t,r)=>{"use strict"
const n=r(2658)
e.exports=function(e){const t=n(e.files)
return Promise.resolve(t)}},9313:e=>{"use strict"
e.exports=function e(t,r,n,i){let{onSuccess:o}=i
t.readEntries((i=>{const s=[...r,...i]
i.length?setTimeout((()=>{e(t,s,n,{onSuccess:o})}),0):o(s)}),(e=>{n(e),o(r)}))}},6604:e=>{"use strict"
e.exports=function(e){return e.fullPath&&e.fullPath!=="/".concat(e.name)?e.fullPath:null}},7762:(e,t,r)=>{"use strict"
const n=r(6604),i=r(9313),o=r(2658)
e.exports=function(e,t){const r=[],s=[],a=e=>new Promise((o=>{if(e.isFile)e.file((t=>{t.relativePath=n(e),r.push(t),o()}),(e=>{t(e),o()}))
else if(e.isDirectory){const r=e.createReader()
i(r,[],t,{onSuccess:e=>o(Promise.all(e.map(a)))})}}))
return o(e.items).forEach((e=>{const t=e.webkitGetAsEntry()
t&&s.push(a(t))})),Promise.all(s).then((()=>r))}},7316:e=>{"use strict"
e.exports=function(e){const t=e.lastIndexOf(".")
return-1===t||t===e.length-1?{name:e,extension:void 0}:{name:e.slice(0,t),extension:e.slice(t+1)}}},9785:(e,t,r)=>{"use strict"
const n=r(7316),i=r(9279)
e.exports=function(e){var t
if(e.type)return e.type
const r=e.name?null==(t=n(e.name).extension)?void 0:t.toLowerCase():null
return r&&r in i?i[r]:"application/octet-stream"}},4819:e=>{"use strict"
e.exports=function(e){const t=/^(?:https?:\/\/|\/\/)?(?:[^@\n]+@)?(?:www\.)?([^\n]+)/i.exec(e)[1],r=/^http:\/\//i.test(e)?"ws":"wss"
return"".concat(r,"://").concat(t)}},6023:e=>{"use strict"
e.exports=function(e){for(var t;e&&!e.dir;)e=e.parentNode
return null==(t=e)?void 0:t.dir}},909:e=>{"use strict"
function t(e){return e<10?"0".concat(e):e.toString()}e.exports=function(){const e=new Date,r=t(e.getHours()),n=t(e.getMinutes()),i=t(e.getSeconds())
return"".concat(r,":").concat(n,":").concat(i)}},2398:e=>{"use strict"
e.exports=function(e,t){return Object.prototype.hasOwnProperty.call(e,t)}},9601:e=>{"use strict"
e.exports=function(e){return(null==e?void 0:e.nodeType)===Node.ELEMENT_NODE}},5583:e=>{"use strict"
e.exports=function(e){return!!e&&(0!==e.readyState&&4!==e.readyState||0===e.status)}},9279:e=>{"use strict"
e.exports={md:"text/markdown",markdown:"text/markdown",mp4:"video/mp4",mp3:"audio/mp3",svg:"image/svg+xml",jpg:"image/jpeg",png:"image/png",gif:"image/gif",heic:"image/heic",heif:"image/heif",yaml:"text/yaml",yml:"text/yaml",csv:"text/csv",tsv:"text/tab-separated-values",tab:"text/tab-separated-values",avi:"video/x-msvideo",mks:"video/x-matroska",mkv:"video/x-matroska",mov:"video/quicktime",dicom:"application/dicom",doc:"application/msword",docm:"application/vnd.ms-word.document.macroenabled.12",docx:"application/vnd.openxmlformats-officedocument.wordprocessingml.document",dot:"application/msword",dotm:"application/vnd.ms-word.template.macroenabled.12",dotx:"application/vnd.openxmlformats-officedocument.wordprocessingml.template",xla:"application/vnd.ms-excel",xlam:"application/vnd.ms-excel.addin.macroenabled.12",xlc:"application/vnd.ms-excel",xlf:"application/x-xliff+xml",xlm:"application/vnd.ms-excel",xls:"application/vnd.ms-excel",xlsb:"application/vnd.ms-excel.sheet.binary.macroenabled.12",xlsm:"application/vnd.ms-excel.sheet.macroenabled.12",xlsx:"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet",xlt:"application/vnd.ms-excel",xltm:"application/vnd.ms-excel.template.macroenabled.12",xltx:"application/vnd.openxmlformats-officedocument.spreadsheetml.template",xlw:"application/vnd.ms-excel",txt:"text/plain",text:"text/plain",conf:"text/plain",log:"text/plain",pdf:"application/pdf",zip:"application/zip","7z":"application/x-7z-compressed",rar:"application/x-rar-compressed",tar:"application/x-tar",gz:"application/gzip",dmg:"application/x-apple-diskimage"}},750:e=>{"use strict"
e.exports=function(e){const t=[],r=[]
function n(e){t.push(e)}function i(e){r.push(e)}return Promise.all(e.map((e=>e.then(n,i)))).then((()=>({successful:t,failed:r})))}},2658:e=>{"use strict"
e.exports=Array.from},3527:(e,t,r)=>{"use strict"
var n=r(8773),i=r(3150),o=r(62)
const s=r(4289),a=r(9906),l=r(4819),c=r(750),u=r(7035),p=r(8008),h=r(9319),d=r(5583),f=r(5628)
function m(e,t){let r=t
return r||(r=new Error("Upload error")),"string"==typeof r&&(r=new Error(r)),r instanceof Error||(r=Object.assign(new Error("Upload error"),{data:r})),d(e)?(r=new h(r,e),r):(r.request=e,r)}function g(e){return e.data.slice(0,e.data.size,e.meta.type)}class v extends s{constructor(e,t){super(e,t),this.type="uploader",this.id=this.opts.id||"XHRUpload",this.title="XHRUpload",this.defaultLocale=f
const r={formData:!0,fieldName:t.bundle?"files[]":"file",method:"post",metaFields:null,responseUrlFieldName:"url",bundle:!1,headers:{},timeout:3e4,limit:5,withCredentials:!1,responseType:"",getResponseData(t){let r={}
try{r=JSON.parse(t)}catch(t){e.log(t)}return r},getResponseError(e,t){let r=new Error("Upload error")
return d(t)&&(r=new h(r,t)),r},validateStatus:e=>e>=200&&e<300}
if(this.opts={...r,...t},this.i18nInit(),this.handleUpload=this.handleUpload.bind(this),o.internalRateLimitedQueue in this.opts?this.requests=this.opts[o.internalRateLimitedQueue]:this.requests=new o.RateLimitedQueue(this.opts.limit),this.opts.bundle&&!this.opts.formData)throw new Error("`opts.formData` must be true when `opts.bundle` is enabled.")
this.uploaderEvents=Object.create(null)}getOptions(e){const t=this.uppy.getState().xhrUpload,{headers:r}=this.opts,n={...this.opts,...t||{},...e.xhrUpload||{},headers:{}}
return"function"==typeof r?n.headers=r(e):Object.assign(n.headers,this.opts.headers),t&&Object.assign(n.headers,t.headers),e.xhrUpload&&Object.assign(n.headers,e.xhrUpload.headers),n}addMetadata(e,t,r){(Array.isArray(r.metaFields)?r.metaFields:Object.keys(t)).forEach((r=>{e.append(r,t[r])}))}createFormDataUpload(e,t){const r=new FormData
this.addMetadata(r,e.meta,t)
const n=g(e)
return e.name?r.append(t.fieldName,n,e.meta.name):r.append(t.fieldName,n),r}createBundledUpload(e,t){const r=new FormData,{meta:n}=this.uppy.getState()
return this.addMetadata(r,n,t),e.forEach((e=>{const t=this.getOptions(e),n=g(e)
e.name?r.append(t.fieldName,n,e.name):r.append(t.fieldName,n)})),r}upload(e,t,r){const i=this.getOptions(e)
return this.uppy.log("uploading ".concat(t," of ").concat(r)),new Promise(((t,r)=>{this.uppy.emit("upload-started",e)
const o=i.formData?this.createFormDataUpload(e,i):e.data,s=new XMLHttpRequest
let a
this.uploaderEvents[e.id]=new u(this.uppy)
const l=new p(i.timeout,(()=>{s.abort(),a.done()
const t=new Error(this.i18n("timedOut",{seconds:Math.ceil(i.timeout/1e3)}))
this.uppy.emit("upload-error",e,t),r(t)})),c=(0,n.nanoid)()
s.upload.addEventListener("loadstart",(()=>{this.uppy.log("[XHRUpload] ".concat(c," started"))})),s.upload.addEventListener("progress",(t=>{this.uppy.log("[XHRUpload] ".concat(c," progress: ").concat(t.loaded," / ").concat(t.total)),l.progress(),t.lengthComputable&&this.uppy.emit("upload-progress",e,{uploader:this,bytesUploaded:t.loaded,bytesTotal:t.total})})),s.addEventListener("load",(()=>{if(this.uppy.log("[XHRUpload] ".concat(c," finished")),l.done(),a.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),i.validateStatus(s.status,s.responseText,s)){const r=i.getResponseData(s.responseText,s),n=r[i.responseUrlFieldName],o={status:s.status,body:r,uploadURL:n}
return this.uppy.emit("upload-success",e,o),n&&this.uppy.log("Download ".concat(e.name," from ").concat(n)),t(e)}const n=i.getResponseData(s.responseText,s),o=m(s,i.getResponseError(s.responseText,s)),u={status:s.status,body:n}
return this.uppy.emit("upload-error",e,o,u),r(o)})),s.addEventListener("error",(()=>{this.uppy.log("[XHRUpload] ".concat(c," errored")),l.done(),a.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null)
const t=m(s,i.getResponseError(s.responseText,s))
return this.uppy.emit("upload-error",e,t),r(t)})),s.open(i.method.toUpperCase(),i.endpoint,!0),s.withCredentials=i.withCredentials,""!==i.responseType&&(s.responseType=i.responseType),a=this.requests.run((()=>{this.uppy.emit("upload-started",e)
const t=this.getOptions(e)
return Object.keys(t.headers).forEach((e=>{s.setRequestHeader(e,t.headers[e])})),s.send(o),()=>{l.done(),s.abort()}})),this.onFileRemove(e.id,(()=>{a.abort(),r(new Error("File removed"))})),this.onCancelAll(e.id,(e=>{let{reason:t}=e
"user"===t&&a.abort(),r(new Error("Upload cancelled"))}))}))}uploadRemote(e){const t=this.getOptions(e)
return new Promise(((r,n)=>{this.uppy.emit("upload-started",e)
const o={};(Array.isArray(t.metaFields)?t.metaFields:Object.keys(e.meta)).forEach((t=>{o[t]=e.meta[t]})),new(e.remote.providerOptions.provider?i.Provider:i.RequestClient)(this.uppy,e.remote.providerOptions).post(e.remote.url,{...e.remote.body,endpoint:t.endpoint,size:e.data.size,fieldname:t.fieldName,metadata:o,httpMethod:t.method,useFormData:t.formData,headers:t.headers}).then((o=>{const{token:s}=o,c=l(e.remote.companionUrl),p=new i.Socket({target:"".concat(c,"/api/").concat(s),autoOpen:!1})
let h
this.uploaderEvents[e.id]=new u(this.uppy),this.onFileRemove(e.id,(()=>{p.send("cancel",{}),h.abort(),r("upload ".concat(e.id," was removed"))})),this.onCancelAll(e.id,(function(t){let{reason:n}=void 0===t?{}:t
"user"===n&&(p.send("cancel",{}),h.abort()),r("upload ".concat(e.id," was canceled"))})),this.onRetry(e.id,(()=>{p.send("pause",{}),p.send("resume",{})})),this.onRetryAll(e.id,(()=>{p.send("pause",{}),p.send("resume",{})})),p.on("progress",(t=>a(this,t,e))),p.on("success",(n=>{const i=t.getResponseData(n.response.responseText,n.response),o=i[t.responseUrlFieldName],s={status:n.response.status,body:i,uploadURL:o}
return this.uppy.emit("upload-success",e,s),h.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),r()})),p.on("error",(r=>{const i=r.response,o=i?t.getResponseError(i.responseText,i):Object.assign(new Error(r.error.message),{cause:r.error})
this.uppy.emit("upload-error",e,o),h.done(),this.uploaderEvents[e.id]&&(this.uploaderEvents[e.id].remove(),this.uploaderEvents[e.id]=null),n(o)})),h=this.requests.run((()=>(p.open(),e.isPaused&&p.send("pause",{}),()=>p.close())))})).catch((t=>{this.uppy.emit("upload-error",e,t),n(t)}))}))}uploadBundle(e){return new Promise(((t,r)=>{const{endpoint:n}=this.opts,{method:i}=this.opts,o=this.uppy.getState().xhrUpload,s=this.createBundledUpload(e,{...this.opts,...o||{}}),a=new XMLHttpRequest,l=t=>{e.forEach((e=>{this.uppy.emit("upload-error",e,t)}))},c=new p(this.opts.timeout,(()=>{a.abort()
const e=new Error(this.i18n("timedOut",{seconds:Math.ceil(this.opts.timeout/1e3)}))
l(e),r(e)}))
a.upload.addEventListener("loadstart",(()=>{this.uppy.log("[XHRUpload] started uploading bundle"),c.progress()})),a.upload.addEventListener("progress",(t=>{c.progress(),t.lengthComputable&&e.forEach((e=>{this.uppy.emit("upload-progress",e,{uploader:this,bytesUploaded:t.loaded/t.total*e.size,bytesTotal:e.size})}))})),a.addEventListener("load",(n=>{if(c.done(),this.opts.validateStatus(n.target.status,a.responseText,a)){const r=this.opts.getResponseData(a.responseText,a),i={status:n.target.status,body:r}
return e.forEach((e=>{this.uppy.emit("upload-success",e,i)})),t()}const i=this.opts.getResponseError(a.responseText,a)||new Error("Upload error")
return i.request=a,l(i),r(i)})),a.addEventListener("error",(()=>{c.done()
const e=this.opts.getResponseError(a.responseText,a)||new Error("Upload error")
return l(e),r(e)})),this.uppy.on("cancel-all",(function(e){let{reason:t}=void 0===e?{}:e
"user"===t&&(c.done(),a.abort())})),a.open(i.toUpperCase(),n,!0),a.withCredentials=this.opts.withCredentials,""!==this.opts.responseType&&(a.responseType=this.opts.responseType),Object.keys(this.opts.headers).forEach((e=>{a.setRequestHeader(e,this.opts.headers[e])})),a.send(s),e.forEach((e=>{this.uppy.emit("upload-started",e)}))}))}uploadFiles(e){const t=e.map(((t,r)=>{const n=parseInt(r,10)+1,i=e.length
return t.error?Promise.reject(new Error(t.error)):t.isRemote?this.uploadRemote(t,n,i):this.upload(t,n,i)}))
return c(t)}onFileRemove(e,t){this.uploaderEvents[e].on("file-removed",(r=>{e===r.id&&t(r.id)}))}onRetry(e,t){this.uploaderEvents[e].on("upload-retry",(r=>{e===r&&t()}))}onRetryAll(e,t){this.uploaderEvents[e].on("retry-all",(()=>{this.uppy.getFile(e)&&t()}))}onCancelAll(e,t){var r=this
this.uploaderEvents[e].on("cancel-all",(function(){r.uppy.getFile(e)&&t(...arguments)}))}handleUpload(e){if(0===e.length)return this.uppy.log("[XHRUpload] No files to upload!"),Promise.resolve()
0!==this.opts.limit||this.opts[o.internalRateLimitedQueue]||this.uppy.log("[XHRUpload] When uploading multiple files at once, consider setting the `limit` option (to `10` for example), to limit the number of concurrent uploads, which helps prevent memory and network issues: https://uppy.io/docs/xhr-upload/#limit-0","warning"),this.uppy.log("[XHRUpload] Uploading...")
const t=e.map((e=>this.uppy.getFile(e)))
if(this.opts.bundle){if(t.some((e=>e.isRemote)))throw new Error("Can’t upload remote files when the `bundle: true` option is set")
if("function"==typeof this.opts.headers)throw new TypeError("`headers` may not be a function when the `bundle: true` option is set")
return this.uploadBundle(t)}return this.uploadFiles(t).then((()=>null))}install(){if(this.opts.bundle){const{capabilities:e}=this.uppy.getState()
this.uppy.setState({capabilities:{...e,individualCancellation:!1}})}this.uppy.addUploader(this.handleUpload)}uninstall(){if(this.opts.bundle){const{capabilities:e}=this.uppy.getState()
this.uppy.setState({capabilities:{...e,individualCancellation:!0}})}this.uppy.removeUploader(this.handleUpload)}}v.VERSION="2.1.2",e.exports=v},5628:e=>{"use strict"
e.exports={strings:{timedOut:"Upload stalled for %{seconds} seconds, aborting."}}},8773:e=>{e.exports={nanoid:(e=21)=>{let t="",r=e
for(;r--;)t+="useandom-26T198340PX75pxJACKVERYMINDBUSHWOLF_GQZbfghjklqvwyzrict"[64*Math.random()|0]
return t},customAlphabet:(e,t)=>()=>{let r="",n=t
for(;n--;)r+=e[Math.random()*e.length|0]
return r}}}}])

//# sourceMappingURL=chunk.729.b9dddc9ef490a606a608-c4400a7520fd71230df707df4d73fafe0e0be803136972d03f617b417765ff67.map
//!

;
