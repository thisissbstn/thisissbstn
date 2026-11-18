<pre>
SBSTN-SEC(8)          System Administration           SBSTN-SEC(8)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn-sec - offensive mode, rules of engagement
</p>

<h2>SYNOPSIS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn --hack --target &lt;mine-or-authorized&gt; [--report]
</p>

<h2>DESCRIPTION</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;I come from development and operations, which means I know where<br>
&nbsp;&nbsp;&nbsp;&nbsp;the bodies are buried: the forgotten admin route, the debug flag<br>
&nbsp;&nbsp;&nbsp;&nbsp;in production, the container running as root. I look for those<br>
&nbsp;&nbsp;&nbsp;&nbsp;in my own systems first.
</p>

<h2>METHOD</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;1. Recon - what is exposed, what should not be.<br>
&nbsp;&nbsp;&nbsp;&nbsp;2. Enumerate - services, versions, endpoints, parameters.<br>
&nbsp;&nbsp;&nbsp;&nbsp;3. Exploit - prove it, don't just suspect it.<br>
&nbsp;&nbsp;&nbsp;&nbsp;4. Harden - close it, then test the fix.<br>
&nbsp;&nbsp;&nbsp;&nbsp;5. Write it down - an undocumented finding comes back.
</p>

<h2>FOCUS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Web applications and APIs, authentication and session handling,<br>
&nbsp;&nbsp;&nbsp;&nbsp;container and reverse proxy setups, exposed services on Linux hosts.
</p>

<h2>RULES OF ENGAGEMENT</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Own systems and explicit permission only. No exceptions.<br>
&nbsp;&nbsp;&nbsp;&nbsp;No data leaves the target that does not have to.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Findings go to the owner first.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Curiosity is not authorization.
</p>

<h2>DEFENSE</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Key-only SSH, fail2ban, least privilege, network segmentation,<br>
&nbsp;&nbsp;&nbsp;&nbsp;automatic updates, monitoring that actually pages someone.
</p>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn">sbstn(1)</a> - User commands<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.7.md">sbstn(7)</a> - Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.conf.5.md">sbstn.conf(5)</a> - Configuration and defaults<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.service.8.md">sbstn.service(8)</a> - Runtime behavior and lifecycle<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn-cli.md">sbstn-cli</a> - Command-line help<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/caffeine.7.md">caffeine(7)</a> - Unofficial dependency
</p>

<h2>AUTHOR</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn
</p>

<pre>
sbstn 2.0                    2026                     SBSTN-SEC(8)
</pre>
