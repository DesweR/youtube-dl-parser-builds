**YouTube-DL Parser 0.3 - console parser for youtube-dl**

Args:
<pre>
<b>-url</b>  "url"               - required!
<b>-domens</b> [path]            - accept domens from domens.txt
<b>-include</b> [path]           - accept url from urls-in.txt
<b>-exclude</b> [path]           - not accept url from urls-ex.txt
<b>-useragent</b> "user-agent"   - custom user-agent
<b>-cookies</b> [path]           - use cookies, for export use: https://addons.mozilla.org/firefox/addon/cookies-txt/
<b>-single</b>                   - get only single video/audio
<b>-playlist</b>                 - get only playlist
<b>-title</b>                    - get title
<b>-locale</b>                   - set custom locale (en/ru/...)
<b>-server</b> [secs]            - start cache-sever [with lifetime]
<b>-server-start</b> [secs]      - start cache-sever without wait [with lifetime]
<b>-proxy-start</b>              - start proxy-sever
<b>-proxy-stop</b>               - stop proxy-sever
<b>-kill-clients</b>             - kill all youtube-dl-parser, except cache-sever
</pre>
Without args - kill all youtube-dl-parser

Use DebugView to view logs
