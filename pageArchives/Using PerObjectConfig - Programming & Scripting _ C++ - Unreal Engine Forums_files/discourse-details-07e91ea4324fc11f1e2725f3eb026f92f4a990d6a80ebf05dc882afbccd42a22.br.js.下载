define("discourse/plugins/discourse-details/initializers/apply-details",["exports","I18n","discourse/lib/plugin-api"],(function(e,t,i){"use strict"
function s(e){e.decorateCooked((e=>$("details",e)),{id:"discourse-details"}),e.addToolbarPopupMenuOptionsCallback((()=>({action:"insertDetails",icon:"caret-right",label:"details.title"}))),e.modifyClass("controller:composer",{pluginId:"discourse-details",actions:{insertDetails(){this.toolbarEvent.applySurround("\n"+'[details="'.concat(t.default.t("composer.details_title"),'"]')+"\n","\n[/details]\n","details_text",{multiline:!1})}}})}Object.defineProperty(e,"__esModule",{value:!0}),e.default=void 0
var l={name:"apply-details",initialize(){(0,i.withPluginApi)("0.8.7",s)}}
e.default=l})),define("discourse/plugins/discourse-details/lib/discourse-markdown/details",["exports"],(function(e){"use strict"
Object.defineProperty(e,"__esModule",{value:!0}),e.setup=function(e){e.allowList(["summary","summary[title]","details","details[open]","details.elided"]),e.registerPlugin((e=>{e.block.bbcode.ruler.push("details",t)}))}
const t={tag:"details",before(e,t){const i=t.attrs
e.push("bbcode_open","details",1),e.push("bbcode_open","summary",1),e.push("text","",0).content=i._default||"",e.push("bbcode_close","summary",-1)},after(e){e.push("bbcode_close","details",-1)}}}))

//# sourceMappingURL=discourse-details-e4a2ec69813260036b8699980554d20a89b2c572b322a27a59fb4472da86a387.map
//!

;
