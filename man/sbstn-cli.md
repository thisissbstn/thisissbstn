<pre>
SBSTN-CLI(1)              User Commands               SBSTN-CLI(1)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn-cli - command-line help
</p>

<h2>USAGE</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn [OPTIONS] [TARGET]
</p>

<h2>OPTIONS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--code&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>write software<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--build&nbsp;&nbsp;&nbsp;&nbsp;</code>ship it in containers<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--harden&nbsp;&nbsp;&nbsp;</code>lock it down<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--hack&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>break it, with permission<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--coffee&nbsp;&nbsp;&nbsp;</code>refill<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--verbose&nbsp;&nbsp;</code>explain every decision<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--dry-run&nbsp;&nbsp;</code>think first<br>
&nbsp;&nbsp;&nbsp;&nbsp;<code>--help&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>you are here
</p>

<h2>EXAMPLES</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn --code --build<br>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn --hack --target localhost --verbose<br>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn --harden --dry-run
</p>

<h2>NOTES</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;There is no --force. Ask nicely or bring coffee.
</p>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn">sbstn(1)</a> - User commands<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.7.md">sbstn(7)</a> - Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.conf.5.md">sbstn.conf(5)</a> - Configuration and defaults<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.service.8.md">sbstn.service(8)</a> - Runtime behavior and lifecycle<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-sec.8.md">sbstn-sec(8)</a> - Offensive mode, rules of engagement<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/caffeine.7.md">caffeine(7)</a> - Unofficial dependency
</p>

<h2>AUTHOR</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn
</p>

<pre>
sbstn 2.0                    2026                     SBSTN-CLI(1)
</pre>
