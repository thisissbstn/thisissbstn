<pre>
SBSTN.SERVICE(8)      System Administration       SBSTN.SERVICE(8)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn.service - runtime behavior and lifecycle
</p>

<h2>UNIT</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;[Unit]<br>
&nbsp;&nbsp;&nbsp;&nbsp;Description=Full-stack developer with a security habit<br>
&nbsp;&nbsp;&nbsp;&nbsp;Requires=caffeine.service<br>
&nbsp;&nbsp;&nbsp;&nbsp;After=network-online.target
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;[Service]<br>
&nbsp;&nbsp;&nbsp;&nbsp;ExecStartPre=/usr/bin/coffee --black<br>
&nbsp;&nbsp;&nbsp;&nbsp;ExecStart=/usr/bin/sbstn --code --build --harden<br>
&nbsp;&nbsp;&nbsp;&nbsp;ExecReload=/usr/bin/sbstn --hack --target self<br>
&nbsp;&nbsp;&nbsp;&nbsp;Restart=on-failure<br>
&nbsp;&nbsp;&nbsp;&nbsp;NoNewPrivileges=true<br>
&nbsp;&nbsp;&nbsp;&nbsp;ProtectSystem=strict
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;[Install]<br>
&nbsp;&nbsp;&nbsp;&nbsp;WantedBy=multi-user.target
</p>

<h2>LIFECYCLE</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;start - coffee, logs, then code.<br>
&nbsp;&nbsp;&nbsp;&nbsp;reload - break it, fix it, document it.<br>
&nbsp;&nbsp;&nbsp;&nbsp;stop - rarely clean. Open tabs survive.<br>
&nbsp;&nbsp;&nbsp;&nbsp;restart - after sleep. Uptime is not a personality.
</p>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn">sbstn(1)</a> - User commands<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.7.md">sbstn(7)</a> - Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.conf.5.md">sbstn.conf(5)</a> - Configuration and defaults<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-sec.8.md">sbstn-sec(8)</a> - Offensive mode, rules of engagement<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-cli.md">sbstn-cli</a> - Command-line help<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/caffeine.7.md">caffeine(7)</a> - Unofficial dependency
</p>

<h2>AUTHOR</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn
</p>

<pre>
sbstn 2.0                  2026                   SBSTN.SERVICE(8)
</pre>
