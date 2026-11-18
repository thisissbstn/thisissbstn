<pre>
SBSTN.CONF(5)              File Formats              SBSTN.CONF(5)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn.conf - configuration and defaults
</p>

<h2>DESCRIPTION</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Default settings. Most can be overridden with good arguments,<br>
&nbsp;&nbsp;&nbsp;&nbsp;some only with coffee.
</p>

<h2>DEFAULTS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;editor = vscode<br>
&nbsp;&nbsp;&nbsp;&nbsp;shell = bash<br>
&nbsp;&nbsp;&nbsp;&nbsp;theme = dark<br>
&nbsp;&nbsp;&nbsp;&nbsp;os = linux<br>
&nbsp;&nbsp;&nbsp;&nbsp;indent = spaces<br>
&nbsp;&nbsp;&nbsp;&nbsp;deploy = docker compose up -d<br>
&nbsp;&nbsp;&nbsp;&nbsp;permit_root_login = no<br>
&nbsp;&nbsp;&nbsp;&nbsp;password_auth = no<br>
&nbsp;&nbsp;&nbsp;&nbsp;open_ports = as few as possible<br>
&nbsp;&nbsp;&nbsp;&nbsp;trust = zero<br>
&nbsp;&nbsp;&nbsp;&nbsp;coffee = black
</p>

<h2>ENVIRONMENT</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;SBSTN_MODE<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dev, ops or sec. Usually all three.<br>
&nbsp;&nbsp;&nbsp;&nbsp;SBSTN_DEBUG<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Always on. Read the logs.<br>
&nbsp;&nbsp;&nbsp;&nbsp;SBSTN_TZ<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Europe/Berlin
</p>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn">sbstn(1)</a> - User commands<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.7.md">sbstn(7)</a> - Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.service.8.md">sbstn.service(8)</a> - Runtime behavior and lifecycle<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-sec.8.md">sbstn-sec(8)</a> - Offensive mode, rules of engagement<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-cli.md">sbstn-cli</a> - Command-line help<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/caffeine.7.md">caffeine(7)</a> - Unofficial dependency
</p>

<h2>AUTHOR</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn
</p>

<pre>
sbstn 2.0                    2026                    SBSTN.CONF(5)
</pre>
