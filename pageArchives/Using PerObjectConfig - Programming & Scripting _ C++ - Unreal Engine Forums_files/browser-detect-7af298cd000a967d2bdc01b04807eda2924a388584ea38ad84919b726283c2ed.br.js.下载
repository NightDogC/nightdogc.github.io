/* eslint-disable no-var */ // `let` is not supported in very old browsers

(function () {
  if (!window.WeakMap || !window.Promise || typeof globalThis === "undefined") {
    window.unsupportedBrowser = true;
  } else {
    // Some implementations of `WeakMap.prototype.has` do not accept false
    // values and Ember's `isClassicDecorator` sometimes does that (it only
    // checks for `null` and `undefined`).
    try {
      new WeakMap().has(0);
    } catch (err) {
      window.unsupportedBrowser = true;
    }
    var match = window.navigator.userAgent.match(/Firefox\/([0-9]+)\./);
    var firefoxVersion = match ? parseInt(match[1], 10) : null;
    if (firefoxVersion && firefoxVersion < 89) {
      // prior to v89, Firefox has bugs with document.execCommand("insertText")
      // https://bugzil.la/1220696
      window.unsupportedBrowser = true;
    }
  }
})();
//# sourceMappingURL=browser-detect-114c7bc9bb4ceb75092d909e7f5d8be0fd5c8a555d3e358734b96324288c9279.map
//!

;
