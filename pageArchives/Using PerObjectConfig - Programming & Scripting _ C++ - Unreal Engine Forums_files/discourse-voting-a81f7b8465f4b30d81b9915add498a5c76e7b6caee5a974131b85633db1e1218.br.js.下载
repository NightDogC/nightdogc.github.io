define("discourse/plugins/discourse-topic-voting/discourse/feature-voting-route-map",["exports"],(function(t){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var e={resource:"user",path:"users/:username",map(){this.route("userActivity",{path:"activity",resetNamespace:!0},(function(){this.route("votes")}))}}
t.default=e})),define("discourse/plugins/discourse-topic-voting/discourse/initializers/discourse-topic-voting",["exports","I18n","discourse/lib/plugin-api","discourse/models/nav-item"],(function(t,e,o,i){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var s={name:"discourse-topic-voting",initialize(){(0,o.withPluginApi)("0.8.32",(t=>{if(t.container.lookup("site-settings:main").voting_enabled){t.container.lookup("controller:full-page-search").sortOrders.pushObject({name:e.default.t("search.most_votes"),id:5,term:"order:votes"}),t.addNavigationBarItem({name:"votes",before:"top",customFilter:t=>t&&t.can_vote,customHref:(t,e)=>{const o=i.default.pathFor("latest",e)
return"".concat(o,"?order=votes")},forceActive:(t,e,o)=>{const i=o.currentRoute.queryParams
return i&&1===Object.keys(i).length&&"votes"===i.order}}),t.addNavigationBarItem({name:"my_votes",before:"top",customFilter:e=>e&&e.can_vote&&t.getCurrentUser(),customHref:(t,e)=>{const o=i.default.pathFor("latest",e)
return"".concat(o,"?state=my_votes")},forceActive:(t,e,o)=>{const i=o.currentRoute.queryParams
return i&&1===Object.keys(i).length&&"my_votes"===i.state}})}})),(0,o.withPluginApi)("0.11.7",(t=>{t.container.lookup("site-settings:main").voting_enabled&&t.addSearchSuggestion("order:votes")}))}}
t.default=s})),define("discourse/plugins/discourse-topic-voting/discourse/pre-initializers/extend-category-for-voting",["exports","I18n","discourse/lib/plugin-api"],(function(t,e,o){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var i={name:"extend-category-for-voting",before:"inject-discourse-objects",initialize(){(0,o.withPluginApi)("0.8.4",(t=>function(t){t.addPostClassesCallback((t=>{if(1===t.post_number&&t.can_vote)return["voting-post"]})),t.includePostAttributes("can_vote"),t.addTagsHtmlCallback((t=>{if(!t.can_vote)return
let o=[],i=""
t.user_voted&&(i=" title='".concat(e.default.t("topic_voting.voted"),"'"))
let s=t.user_voted?" voted":""
return o.push("<a href='".concat(t.url,"' class='list-vote-count vote-count-").concat(t.vote_count," discourse-tag simple").concat(s,"'").concat(i,">")),o.push(e.default.t("topic_voting.votes",{count:t.vote_count})),o.push("</a>"),o.length>0?o.join(""):void 0}),{priority:-100})}(t))),(0,o.withPluginApi)("0.8.30",(t=>t.addCategorySortCriteria("votes")))}}
t.default=i})),define("discourse/plugins/discourse-topic-voting/discourse/routes/user-activity-votes",["exports","discourse/routes/user-topic-list","discourse/models/user-action","I18n"],(function(t,e,o,i){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var s=e.default.extend({userActionType:o.default.TYPES.topics,model(){return this.store.findFiltered("topicList",{filter:"topics/voted-by/"+this.modelFor("user").get("username_lower")}).then((t=>(t.set("emptyState",this.emptyState()),t)))},emptyState(){const t=this.modelFor("user")
return{title:this.isCurrentUser(t)?i.default.t("topic_voting.no_votes_title_self"):i.default.t("topic_voting.no_votes_title_others",{username:t.username}),body:""}}})
t.default=s})),define("discourse/plugins/discourse-topic-voting/discourse/templates/connectors/category-custom-settings/feature-voting-settings",["exports","@ember/template-factory"],(function(t,e){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var o=(0,e.createTemplateFactory)({id:"UE4yqKur",block:'[[[10,"h3"],[12],[1,[28,[35,0],["topic_voting.title"],null]],[13],[1,"\\n"],[10,"section"],[14,0,"field"],[12],[1,"\\n  "],[10,0],[14,0,"enable-topic-voting"],[12],[1,"\\n    "],[10,"label"],[14,0,"checkbox-label"],[12],[1,"\\n      "],[1,[28,[35,1],null,[["type","checked"],["checkbox",[33,2,["custom_fields","enable_topic_voting"]]]]]],[1,"\\n      "],[1,[28,[35,0],["topic_voting.allow_topic_voting"],null]],[1,"\\n    "],[13],[1,"\\n  "],[13],[1,"\\n"],[13],[1,"\\n"]],[],false,["i18n","input","category"]]',moduleName:"discourse/plugins/discourse-topic-voting/discourse/templates/connectors/category-custom-settings/feature-voting-settings.hbs",isStrictMode:!1})
t.default=o})),define("discourse/plugins/discourse-topic-voting/discourse/templates/connectors/topic-above-post-stream/topic-title-voting",["exports","@ember/template-factory"],(function(t,e){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var o=(0,e.createTemplateFactory)({id:"tD5blP9U",block:'[[[41,[33,1,["can_vote"]],[[[41,[33,1,["postStream","loaded"]],[[[41,[33,1,["postStream","firstPostPresent"]],[[[1,"      "],[10,0],[14,0,"voting title-voting"],[12],[1,"\\n        "],[1,[28,[35,2],null,[["widget","args","showLogin"],["vote-box",[33,1],[28,[37,3],["showLogin"],null]]]]],[1,"\\n      "],[13],[1,"\\n"]],[]],null]],[]],null]],[]],null]],[],false,["if","model","mount-widget","route-action"]]',moduleName:"discourse/plugins/discourse-topic-voting/discourse/templates/connectors/topic-above-post-stream/topic-title-voting.hbs",isStrictMode:!1})
t.default=o})),define("discourse/plugins/discourse-topic-voting/discourse/templates/connectors/user-activity-bottom/user-voted-topics",["exports","@ember/template-factory"],(function(t,e){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var o=(0,e.createTemplateFactory)({id:"ADmxLmRN",block:'[[[41,[33,1,["voting_show_votes_on_profile"]],[[[6,[39,2],null,[["route"],["userActivity.votes"]],[["default"],[[[[1,"    "],[1,[28,[35,3],["heart"],null]],[1," "],[1,[28,[35,4],["topic_voting.vote_title_plural"],null]],[1,"\\n"]],[]]]]]],[]],null]],[],false,["if","siteSettings","link-to","d-icon","i18n"]]',moduleName:"discourse/plugins/discourse-topic-voting/discourse/templates/connectors/user-activity-bottom/user-voted-topics.hbs",isStrictMode:!1})
t.default=o})),define("discourse/plugins/discourse-topic-voting/discourse/widgets/remove-vote",["exports","I18n","discourse/widgets/widget","discourse-common/lib/icon-library"],(function(t,e,o,i){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var s=(0,o.createWidget)("remove-vote",{tagName:"div.remove-vote",buildClasses:()=>"vote-option",html:()=>[(0,i.iconNode)("times"),e.default.t("topic_voting.remove_vote")],click(){this.sendWidgetAction("removeVote")}})
t.default=s})),define("discourse/plugins/discourse-topic-voting/discourse/widgets/vote-box",["exports","I18n","discourse/widgets/widget","discourse/lib/ajax","discourse/widgets/raw-html","discourse/lib/ajax-error"],(function(t,e,o,i,s,r){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var n=(0,o.createWidget)("vote-box",{tagName:"div.voting-wrapper",buildKey:()=>"vote-box",buildClasses(){if(this.siteSettings.voting_show_who_voted)return"show-pointer"},defaultState:()=>({allowClick:!0,initialVote:!1}),html(t,o){let i=[this.attach("vote-count",t),this.attach("vote-button",t),this.attach("vote-options",t)]
if(o.votesAlert>0){const t="<div class='voting-popup-menu vote-options popup-menu'>"+e.default.t("topic_voting.votes_left",{count:o.votesAlert,path:this.currentUser.get("path")+"/activity/votes"})+"</div>"
i.push(new s.default({html:t}))}return i},hideVotesAlert(){this.state.votesAlert&&(this.state.votesAlert=null,this.scheduleRerender())},click(){this.hideVotesAlert()},clickOutside(){this.hideVotesAlert()},addVote(){let t=this.attrs,e=this.state
return(0,i.ajax)("/voting/vote",{type:"POST",data:{topic_id:t.id}}).then((o=>{t.set("vote_count",o.vote_count),t.set("user_voted",!0),this.currentUser.setProperties({votes_exceeded:!o.can_vote,votes_left:o.votes_left}),o.alert&&(e.votesAlert=o.votes_left),t.set("who_voted",o.who_voted),e.allowClick=!0,this.scheduleRerender()})).catch(r.popupAjaxError)},removeVote(){let t=this.attrs,e=this.state
return(0,i.ajax)("/voting/unvote",{type:"POST",data:{topic_id:t.id}}).then((o=>{t.set("vote_count",o.vote_count),t.set("user_voted",!1),this.currentUser.setProperties({votes_exceeded:!o.can_vote,votes_left:o.votes_left}),t.set("who_voted",o.who_voted),e.allowClick=!0,this.scheduleRerender()})).catch(r.popupAjaxError)}})
t.default=n})),define("discourse/plugins/discourse-topic-voting/discourse/widgets/vote-button",["exports","I18n","discourse/widgets/widget","virtual-dom"],(function(t,e,o,i){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var s=(0,o.createWidget)("vote-button",{tagName:"div",buildClasses(t){let e=""
return e=t.closed?"voting-closed":t.user_voted?this.currentUser&&this.currentUser.votes_exceeded?"vote-limited nonvote":"vote":"nonvote",this.siteSettings.voting_show_who_voted&&(e+=" show-pointer"),e},buildButtonTitle(t){return this.currentUser?t.closed?e.default.t("topic_voting.voting_closed_title"):t.user_voted?e.default.t("topic_voting.voted_title"):this.currentUser.votes_exceeded?e.default.t("topic_voting.voting_limit"):e.default.t("topic_voting.vote_title"):t.vote_count?e.default.t("topic_voting.anonymous_button",{count:t.vote_count}):e.default.t("topic_voting.anonymous_button",{count:1})},html(t){return(0,i.h)("button",{attributes:{title:this.currentUser?e.default.t("topic_voting.votes_left_button_title",{count:this.currentUser.votes_left}):""},className:"btn btn-primary vote-button"},this.buildButtonTitle(t))},click(){if(!this.currentUser)return this.sendWidgetAction("showLogin"),void $.cookie("destination_url",window.location.href)
this.attrs.closed||!this.parentWidget.state.allowClick||this.attrs.user_voted||this.currentUser.votes_exceeded||(this.parentWidget.state.allowClick=!1,this.parentWidget.state.initialVote=!0,this.sendWidgetAction("addVote")),(this.attrs.user_voted||this.currentUser.votes_exceeded)&&$(".vote-options").toggleClass("hidden")},clickOutside(){$(".vote-options").addClass("hidden"),this.parentWidget.state.initialVote=!1}})
t.default=s})),define("discourse/plugins/discourse-topic-voting/discourse/widgets/vote-count",["exports","discourse/widgets/widget","discourse-common/lib/get-url","virtual-dom","discourse/lib/ajax"],(function(t,e,o,i,s){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var r=(0,e.createWidget)("vote-count",{tagName:"div.vote-count-wrapper",buildKey:()=>"vote-count",buildClasses(){if(0===this.attrs.vote_count)return"no-votes"},defaultState:()=>({whoVotedUsers:null}),html(t){let e=(0,i.h)("div.vote-count",t.vote_count.toString()),o=null
this.siteSettings.voting_show_who_voted&&this.state.whoVotedUsers&&this.state.whoVotedUsers.length>0&&(o=this.attach("small-user-list",{users:this.state.whoVotedUsers,addSelf:t.liked,listClassName:"regular-votes"}))
let s=[e]
return o&&s.push((0,i.h)("div.who-voted.popup-menu.voting-popup-menu",[o])),s},click(){if(!this.currentUser)return this.sendWidgetAction("showLogin"),void $.cookie("destination_url",window.location.href)
if(this.siteSettings.voting_show_who_voted&&this.attrs.vote_count>0){if(null===this.state.whoVotedUsers)return this.getWhoVoted()
$(".who-voted").toggle()}},clickOutside(){$(".who-voted").hide()},getWhoVoted(){return(0,s.ajax)("/voting/who",{type:"GET",data:{topic_id:this.attrs.id}}).then((t=>{this.state.whoVotedUsers=t.map(n)}))}})
function n(t){return{template:t.avatar_template,username:t.username,post_url:t.post_url,url:(0,o.default)("/u/")+t.username.toLowerCase()}}t.default=r})),define("discourse/plugins/discourse-topic-voting/discourse/widgets/vote-options",["exports","I18n","discourse/widgets/widget","virtual-dom"],(function(t,e,o,i){"use strict"
Object.defineProperty(t,"__esModule",{value:!0}),t.default=void 0
var s=(0,o.createWidget)("vote-options",{tagName:"div.vote-options",buildClasses:()=>"voting-popup-menu popup-menu hidden",html(t){let o=[]
return t.user_voted?o.push(this.attach("remove-vote",t)):this.currentUser&&this.currentUser.votes_exceeded&&!t.user_voted&&o.push([(0,i.h)("div",e.default.t("topic_voting.reached_limit")),(0,i.h)("p",(0,i.h)("a",{href:this.currentUser.get("path")+"/activity/votes"},e.default.t("topic_voting.list_votes")))]),o}})
t.default=s}))

//# sourceMappingURL=discourse-voting-a4cbee34297634a5b1f1444247a2b1a98af16c23af37581add8c9283ec8cdd26.map
//!

;
