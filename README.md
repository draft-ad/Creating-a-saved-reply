AliyunSLBFullAccess(:
{
  "Version": "1",
  "Statement": [
    {
      "Action": "ocs:Describe*",
      "Resource": "*",
      "Effect": "Allow"
    }
  ]
}Memcache_AliyunSupportFullAccess_(OCS){
  "Version": "1",
  "Statement": [
    {
      "Action": "support:*",
      "Resource": "*",
      "Effect": "Allow"
    }
  ]
}
WombatEventListenerCommon.prototype.listeners = null;
WombatEventListenerCommon.prototype.console = null;
WombatEventListenerCommon.prototype.fireEvent = function(a, c) {
    var b, d = [], g = function() {
        d.push(this.index)
    };
    for (b = 0; b < this.listeners.length; ++b)
        if (this.listeners[b].name === a) {
            var e = {
                name: a,
                callback: this.listeners[b].callback,
                object: c,
                index: b,
                removeCallback: g,
                meta: {}
            }, f = null;
            try {
                this._shouldCall(e) && (f = this.listeners[b].callback(c))
            } catch (h) {
                this._onError(e, h)
            }
            this._afterCall(e, f)
        }
    for (b = 0; b < d; ++b)
        this.listeners.splice(d[b] - b, 1), this.console.log("Invalid handler was removed for message:" + a + ". Probably document was destroyed, and it's normal behavior. Or handler returns 'removeEventListener' result.")
};
WombatEventListenerCommon.prototype.addListener：
$axure.internal(function($ax) {
    var _actionHandlers = {};
    var _action = $ax.action = {};

    var queueTypes = _action.queueTypes = {
        none: 0,
        move: 1,
        setState: 2,
        fade: 3,
        resize: 4,
        rotate: 5
    };

    var animationQueue = {};
v1.7.1 jquery.com | jquery.org/license */
(function(a,
// ******* Flyout|    // |file:///Users/admin/Documents/Axure/HTML/Untitled/page_3.html
1
{
2
  "Version": "1",#: SLB
)Creating-a-saved-reply
