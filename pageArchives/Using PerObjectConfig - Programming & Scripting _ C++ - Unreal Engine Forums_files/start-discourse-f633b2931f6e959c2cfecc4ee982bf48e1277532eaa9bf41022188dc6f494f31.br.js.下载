document.addEventListener("discourse-booted", e => {
  performance.mark("discourse-booted");
  const config = e.detail;
  const app = require("".concat(config.modulePrefix, "/app"))["default"].create(config);
  app.start();
});

(function () {
  if (window.unsupportedBrowser) {
    throw "Unsupported browser detected";
  }

  // TODO: Remove this and have resolver find the templates
  const discoursePrefix = "discourse/templates/";
  const adminPrefix = "admin/templates/";
  const wizardPrefix = "wizard/templates/";
  const discoursePrefixLength = discoursePrefix.length;
  const pluginRegex = /^discourse\/plugins\/([^\/]+)\//;
  const themeRegex = /^discourse\/theme-([^\/]+)\//;
  Object.keys(requirejs.entries).forEach(function (key) {
    var _key$match, _key$match2;
    let templateKey;
    let pluginName;
    let themeId;
    if (key.startsWith(discoursePrefix)) {
      templateKey = key.slice(discoursePrefixLength);
    } else if (key.startsWith(adminPrefix) || key.startsWith(wizardPrefix)) {
      templateKey = key;
    } else if ((pluginName = (_key$match = key.match(pluginRegex)) === null || _key$match === void 0 ? void 0 : _key$match[1]) && key.includes("/templates/") && require(key).default.__id // really is a template
    ) {
      // This logic mimics the old sprockets compilation system which used to
      // output templates directly to `Ember.TEMPLATES` with this naming logic
      templateKey = key.slice("discourse/plugins/".concat(pluginName, "/").length);
      templateKey = templateKey.replace("discourse/templates/", "");
      templateKey = "javascripts/".concat(templateKey);
    } else if ((themeId = (_key$match2 = key.match(themeRegex)) === null || _key$match2 === void 0 ? void 0 : _key$match2[1]) && key.includes("/templates/")) {
      // And likewise for themes - this mimics the old logic
      templateKey = key.slice("discourse/theme-".concat(themeId, "/").length);
      templateKey = templateKey.replace("discourse/templates/", "");
      if (!templateKey.startsWith("javascripts/")) {
        templateKey = "javascripts/".concat(templateKey);
      }
    }
    if (templateKey) {
      Ember.TEMPLATES[templateKey] = require(key).default;
    }
  });
  window.__widget_helpers = require("discourse-widget-hbs/helpers").default;

  // TODO: Eliminate this global
  window.virtualDom = require("virtual-dom");
  let element = document.querySelector("meta[name=\"discourse/config/environment\"]");
  const config = JSON.parse(decodeURIComponent(element.getAttribute("content")));
  const event = new CustomEvent("discourse-booted", {
    detail: config
  });
  document.dispatchEvent(event);
})();
//# sourceMappingURL=start-discourse-b94509ccce217641ecdc9879dab7dc98039f8151ac53551cc03ef1571f70e4c5.map
//!

;
