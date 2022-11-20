define("discourse/plugins/discourse-narrative-bot/initializers/new-user-narrative",["exports","discourse-common/utils/decorators","discourse/lib/ajax","discourse/lib/offset-calculator","discourse/lib/is-element-in-viewport","discourse/lib/plugin-api"],(function(e,t,i,r,s,o){"use strict"
Object.defineProperty(e,"__esModule",{value:!0}),e.default=void 0
const n="new-user-narrative"
function a(e){var o,a
const c=e.container.lookup("service:message-bus"),l=e.getCurrentUser(),u=e.container.lookup("service:app-events")
var d,p,b,h,g,m
e.modifyClass("component:site-header",{pluginId:n,didInsertElement(){this._super(...arguments),this.dispatch("header:search-context-trigger","header")}}),e.modifyClass("controller:topic",(o=(0,t.debounce)(500),a={pluginId:n,_modifyBookmark(e,t){return t&&-2===t.user_id&&!t.bookmarked?(0,i.ajax)("/bookmarks",{type:"POST",data:{post_id:t.id}}).then((e=>{t.setProperties({"topic.bookmarked":!0,bookmarked:!0,bookmark_id:e.id}),t.appEvents.trigger("post-stream:refresh",{id:this.id})})):this._super(e,t)},subscribe(){this._super(...arguments),this.messageBus.subscribe("/topic/".concat(this.model.id),(e=>{const t=this.model
if(t.isPrivateMessage&&this.currentUser&&this.currentUser.id!==e.user_id&&-2===e.user_id&&"created"===e.type){const i=e.post_number,r=t.get("highest_post_number")<=i,s=i-t.currentPost
r&&s>0&&s<7&&this._scrollToDiscobotPost(e.post_number)}}))},_scrollToDiscobotPost(e){const t=document.querySelector(".topic-post article#post_".concat(e))
if(!t||(0,s.default)(t))return
const i=t.getBoundingClientRect()
window.scrollTo({top:window.scrollY+i.top-(0,r.headerOffset)(),behavior:"smooth"})}},d=a,p="_scrollToDiscobotPost",b=[o],h=Object.getOwnPropertyDescriptor(a,"_scrollToDiscobotPost"),g=a,m={},Object.keys(h).forEach((function(e){m[e]=h[e]})),m.enumerable=!!m.enumerable,m.configurable=!!m.configurable,("value"in m||m.initializer)&&(m.writable=!0),m=b.slice().reverse().reduce((function(e,t){return t(d,p,e)||e}),m),g&&void 0!==m.initializer&&(m.value=m.initializer?m.initializer.call(g):void 0,m.initializer=void 0),void 0===m.initializer&&(Object.defineProperty(d,p,m),m=null),a)),e.attachWidgetAction("header","headerSearchContextTrigger",(function(){this.site.mobileView?this.state.skipSearchContext=!1:(this.state.contextEnabled=!0,this.state.searchContextType="topic")})),c&&l&&c.subscribe("/new_user_narrative/tutorial_search",(()=>{u.trigger("header:search-context-trigger")}))}var c={name:"new-user-narrative",initialize(e){e.lookup("service:site-settings").discourse_narrative_bot_enabled&&(0,o.withPluginApi)("0.8.7",a)}}
e.default=c}))

//# sourceMappingURL=discourse-narrative-bot-f56718e21dac2a1cfe740d43a258d2fb41d05c532de895c5c1533a417e805acd.map
//!

;
