<pre>
SBSTN(1)                  User Commands                   SBSTN(1)
</pre>

<h2>NAME</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn - full-stack developer, self-hosting nerd, breaker of his own stuff
</p>

<h2>SYNOPSIS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;sbstn [--code] [--build] [--harden] [--hack] [--coffee]
</p>

<h2>DESCRIPTION</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;I build things, run them on my own servers and then try to break<br>
&nbsp;&nbsp;&nbsp;&nbsp;them before somebody else does. Backend, frontend, containers,<br>
&nbsp;&nbsp;&nbsp;&nbsp;reverse proxies and the firewall rules in between.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Developer by trade, security by obsession. Every system I ship<br>
&nbsp;&nbsp;&nbsp;&nbsp;gets attacked by me first. If it survives, it goes to production.<br>
&nbsp;&nbsp;&nbsp;&nbsp;If it doesn't, I have learned something and you never hear about it.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<i>Engineering logic, breaking assumptions - running on caffeine.</i>
</p>

<h2>TECH STACK</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Languages:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C#, PHP, JavaScript, Python, Bash, Dart
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Frameworks:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.NET, Symfony, Slim, Flutter
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Data:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MySQL, MariaDB, PostgreSQL
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Infrastructure:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Linux, Docker, Traefik, Nginx, systemd, SSH, Git, self-hosted Forgejo
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Security:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;nmap, Burp Suite, ffuf, Wireshark, fail2ban
</p>

<h2>OPTIONS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;--code<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Development mode. Backend or frontend, whichever needs solving.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;--build<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Containers, pipelines and deployments that survive a reboot.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;--harden<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Least privilege, closed ports, sane defaults. Boring on purpose.
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;--hack<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recon, enumeration, exploitation. Own systems and authorized<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;targets only. See sbstn-sec(8).
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;--coffee<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Raises throughput. Required by all other options.
</p>

<h2>EXAMPLES</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Ship something:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sbstn --code --build
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Find out if it deserved to be shipped:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sbstn --hack --target localhost
</p>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Fix what the previous command found:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sbstn --harden --coffee
</p>

<h2>EXIT STATUS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;&nbsp;&nbsp;&nbsp;shipped<br>
&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;works on my machine<br>
&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;it was DNS<br>
&nbsp;&nbsp;&nbsp;&nbsp;130&nbsp;&nbsp;out of coffee
</p>

<h2>FILES</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;~/.ssh/config<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Longer than it should be.<br>
&nbsp;&nbsp;&nbsp;&nbsp;/etc/fail2ban/jail.local<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Where uninvited guests go.<br>
&nbsp;&nbsp;&nbsp;&nbsp;docker-compose.yml<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The actual documentation.
</p>

<h2>BUGS</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;Names servers after fictional characters. Reads changelogs for fun.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Cannot leave a default password alone. Will not be fixed.
</p>

<h2>SEE ALSO</h2>
<p>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.7.md">sbstn(7)</a> - Developer philosophy<br>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/thisissbstn/thisissbstn/blob/main/man/sbstn.conf.5.md">sbstn.conf(5)</a> - Configuration and defaults<br>
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
sbstn 2.0                       2026                      SBSTN(1)
</pre>
