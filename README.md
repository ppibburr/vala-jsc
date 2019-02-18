To use with webkit2gtk-web-extension you must add this in your code...  
```vala
[CCode (cname="webkit_frame_get_js_context")]
extern JSC.Context get_js_context(WebKit.Frame f);
```