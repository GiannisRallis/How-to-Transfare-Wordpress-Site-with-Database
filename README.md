# How-to-Transfare-Wordpress-Site-with-Database
Cpanel Migration 

<h2 id="step-1">Step 1: Duplicate the site</h2>
<p>The first thing to do when you want to move WordPress to a new server is to create a backup of the site (which then can be taken to the new host and restored there). You can then use an <a href="https://www.codeinwp.com/blog/best-online-cloud-backup-services/">online cloud solution</a> to keep your backup safe.</p>
<p>There are many methods of getting that done. There are even services in the market that will take care of the process for you, not to mention tens of different plugins that promise smooth backup/restore experiences. If you are looking for a way to deal with multiple sites, please check our <a href="https://www.codeinwp.com/blog/backup-multiple-wordpress-sites/">Best Tools to Backup Multiple WordPress Sites</a>.</p>
<p>Here, we&rsquo;re going to focus on one of the best solutions of them all. A couple of reasons:</p>
<ul>
<li>it can be used on <a href="https://www.codeinwp.com/blog/best-wordpress-hosting/">all hosts</a></li>
<li>it&rsquo;s free</li>
<li>it does work hiccup-free</li>
</ul>
<p>That solution is called <a href="https://wordpress.org/plugins/duplicator/" target="_blank" rel="noopener">Duplicator</a> &ndash; a WordPress plugin. It&rsquo;s been getting a lot of good press on the web, and for a very good reason. It simply. Does. Work.</p>
<div class="wp-pic-wrapper aligncenter large" style="margin: 20px 0;">
<div id="wp-pic-duplicator" class="wp-pic large plugin ">
<div class="wp-pic-large">
<div class="wp-pic-large-content"><a class="wp-pic-asset-bg" title="WordPress.org Plugin Page" href="https://wordpress.org/plugins/duplicator/" target="_blank" rel="nofollow noopener">
<div class="wp-pic-half-first">
<p class="wp-pic-author">Author(s): <a href="http://www.snapcreek.com/duplicator/" rel="nofollow noopener">Snap Creek</a></p>
<p class="wp-pic-version">Current Version: 1.4.1</p>
<p class="wp-pic-updated">Last Updated: May 26, 2021</p>
<p><a class="wp-pic-dl-link" title="Direct download" href="https://downloads.wordpress.org/plugin/duplicator.1.4.1.zip" rel="nofollow noopener">duplicator.1.4.1.zip</a></p>
</div>
<div class="wp-pic-half-last">
<div class="wp-pic-bottom">
<div class="wp-pic-bar"><a class="wp-pic-rating" title="Ratings" href="https://wordpress.org/support/view/plugin-reviews/duplicator" target="_blank" rel="nofollow noopener"> 98%<em>Ratings</em> </a> <a class="wp-pic-downloaded" title="Direct download" href="https://downloads.wordpress.org/plugin/duplicator.1.4.1.zip" target="_blank" rel="nofollow noopener"> 1,000,000+<em>Installs</em> </a> <a class="wp-pic-requires" title="WordPress.org Plugin Page" href="https://wordpress.org/plugins/duplicator/" target="_blank" rel="nofollow noopener"> WP 4.0+<em>Requires</em> </a></div>
</div>
</div>
</div>
</div>
</div>
</div>
<p>Okay, so get Duplicator installed to begin. The installation process is standard, so no surprises there.</p>
<p>With the plugin ready, go to Duplicator and click on the <strong>Create New</strong> button next to <strong>Packages</strong>:</p>
<p><img class="aligncenter size-full wp-image-46464" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:282/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/create-new.png" alt="Move WordPress to a new server or host: first create a new backup" width="1698" height="683" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1698/h:683/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/create-new.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="282" /></p>
<p>On the next screen, you can review the parameters of the backup if you want to, but that&rsquo;s not mandatory. If you&rsquo;re in a hurry, simply click on <strong>Next</strong>.</p>
<p><img class="aligncenter size-full wp-image-46465" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:357/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/next.png" alt="next" width="1686" height="858" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1686/h:858/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/next.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="357" /></p>
<p>The next section is where Duplicator scans through your current hosting setup and evaluates how compatible that setup is in order to allow the backup to be made hassle-free.</p>
<p>You might see a notice <em>here and there</em> depending on your host but, in most cases, you don&rsquo;t need to worry about those. Duplicator also gives you some tips on how to get these all cleared and proceed with the backup.</p>
<p>If you see any notices, check the <strong>Yes</strong> field and then click on the <strong>Build</strong> button. If there are no notices, you can click on the <strong>Build</strong> button right away.</p>
<p><img class="aligncenter size-full wp-image-46466" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:671/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/build.jpg" alt="build" width="1690" height="1616" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1569/h:1500/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/build.jpg" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="671" /></p>
<p>This is where Duplicator does its magic . The backup process might take a while depending on the size of your site. <strong>You need to keep the window open until it finishes!</strong></p>
<p><img class="aligncenter size-full wp-image-46467" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:316/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/backup.png" alt="backup" width="1692" height="764" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1692/h:764/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/backup.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="316" /></p>
<p>When the backup finishes, you&rsquo;ll see a confirmation screen like this:</p>
<p><img class="aligncenter size-full wp-image-46468" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:341/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/download.png" alt="download" width="1690" height="823" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1690/h:823/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/download.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="341" /></p>
<p>Download the installer file and the archive containing the backup. You&rsquo;ll need it when going through the next steps on your way to move WordPress to a new server.</p>
<div class="su-divider su-divider-style-dotted" style="margin: 40px 0; border-width: 1px; border-color: #999999;">&nbsp;</div>
<h2 id="step-2">Step 2: Get your new host ready</h2>
<p>&nbsp;Have you chosen your WordPress compatible hosting? If not, <a href="https://www.codeinwp.com/blog/wordpress-hosting-survey-results/">our survey</a> information can help you make the decision.</p>
<p>Before your new host can receive the backup, you need to get it prepared by taking care of a couple of things:</p>
<ul>
<li>add your domain name to the server</li>
<li>create a blank database for the site</li>
<li>(optional) duplicate your email addresses</li>
</ul>
<p>We&rsquo;ll cover how to do all that next:</p>
<p>Most web hosts use cPanel to enable users to set up their hosting environments on their own, without having to understand what&rsquo;s going on under the hood. If your new host uses a different management panel, you might want to contact the support so that they can handle those three tasks for you.</p>
<p>Your host should have provided you with login details to cPanel during signup. Look for that email in your inbox. Some hosts let you go to cPanel directly from the main client area. For example:</p>
<div class="su-accordion su-u-trim">
<div class="su-spoiler su-spoiler-style-fancy su-spoiler-icon-plus su-spoiler-closed" data-scroll-offset="0" data-anchor-in-url="no">&nbsp;</div>
<div class="su-spoiler su-spoiler-style-fancy su-spoiler-icon-plus su-spoiler-closed" data-scroll-offset="0" data-anchor-in-url="no">
<div class="su-spoiler-title" tabindex="0" role="button">&nbsp;</div>
<div class="su-spoiler-content su-u-clearfix su-u-trim">&nbsp;</div>
</div>
</div>
<h3>Add your domain name to the new server</h3>
<div class="su-row">
<div class="su-column su-column-size-1-3">
<div class="su-column-inner su-u-clearfix su-u-trim">
<p>Once you&rsquo;ve logged in to cPanel, go to the <strong>DOMAINS</strong> section and click on <strong>Addon Domains</strong>:</p>
</div>
</div>
<div class="su-column su-column-size-2-3">
<div class="su-column-inner su-u-clearfix su-u-trim"><img class="aligncenter size-full wp-image-46471" style="box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 459px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:459/h:158/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/addon-domains.png" alt="addon domains" width="1444" height="498" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1444/h:498/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/addon-domains.png" data-opt-lazy-loaded="true" data-opt-otimized-width="459" data-opt-optimized-height="158" /></div>
</div>
</div>
<div class="su-row">
<div class="su-column su-column-size-1-3">
<div class="su-column-inner su-u-clearfix su-u-trim">
<p>Enter <a href="https://www.codeinwp.com/blog/best-domain-name-generators/">your domain name</a> into the <strong>New Domain Name</strong> field. The other two fields will be filled out automatically. Click on <strong>Add Domain</strong>.</p>
</div>
</div>
<div class="su-column su-column-size-2-3">
<div class="su-column-inner su-u-clearfix su-u-trim"><img class="aligncenter size-full wp-image-46472" style="box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 459px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:459/h:327/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/new-domain.png" alt="new domain" width="978" height="698" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:978/h:698/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/new-domain.png" data-opt-lazy-loaded="true" data-opt-otimized-width="459" data-opt-optimized-height="327" /></div>
</div>
</div>
<p>After a second, you&rsquo;ll see your new domain on the list. At this stage, the server is ready to welcome your domain name and website.</p>
<p><img class="aligncenter size-full wp-image-46473" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:76/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/domain-ready.png" alt="domain ready" width="1926" height="211" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1926/h:211/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/domain-ready.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="76" /></p>
<h3>Create a new database</h3>
<p>The next thing we need to do in order to move WordPress to a new server is create a blank database. This will be the new home for your site&rsquo;s data.</p>
<div class="su-row">
<div class="su-column su-column-size-1-3">
<div class="su-column-inner su-u-clearfix su-u-trim">
<p>To add a new database in cPanel, scroll down to the <strong>DATABASES</strong> section and click on <strong>MySQL Database Wizard</strong>.</p>
</div>
</div>
<div class="su-column su-column-size-2-3">
<div class="su-column-inner su-u-clearfix su-u-trim"><img class="aligncenter size-full wp-image-46474" style="box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 459px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:459/h:197/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/database-wizard.png" alt="database wizard" width="1444" height="620" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1444/h:620/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/database-wizard.png" data-opt-lazy-loaded="true" data-opt-otimized-width="459" data-opt-optimized-height="197" /></div>
</div>
</div>
<p>This is a helpful step-by-step interface that will guide you through the process of setting up a new database.</p>
<ul>
<li><em>Step 1</em> is about picking a name for your database.</li>
</ul>
<p><img class="aligncenter size-full wp-image-46475" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:277/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/db-name.png" alt="db name" width="966" height="382" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:966/h:382/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/db-name.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="277" /></p>
<ul>
<li><em>Step 2</em> is about creating user accounts that will then be able to access that new database. That new user account is how WordPress accesses the database back and forth. Fill out the required fields and note down the login and <a href="https://www.codeinwp.com/blog/best-password-manager/">password</a> somewhere. You&rsquo;ll need those later on.</li>
</ul>
<p><img class="aligncenter size-full wp-image-46476" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:427/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/db-user.png" alt="db user" width="1330" height="810" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1330/h:810/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/db-user.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="427" /></p>
<ul>
<li><em>Step 3</em> is the final one, and it&rsquo;s where you need to assign your new user account to the new database. Simply select <strong>All PRIVILEGES</strong> and click on <strong>Next Step</strong>.</li>
</ul>
<p><img class="aligncenter size-full wp-image-46477" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:816/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/db-assign.png" alt="db assign" width="1266" height="1472" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1266/h:1472/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/db-assign.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="816" /></p>
<p>The new database has just been added!</p>
<h3>(Optional) move your email address to the new server</h3>
<p>Most users will have at least one custom email set up under their domain name. Do you? In other words, do you have an email like <code>name@YOURDOMAIN.com</code>?</p>
<p>If so, read this section. If not, skip to the next step.</p>
<p>When you move WordPress to a new server, you&rsquo;re effectively moving your domain name to the new host as well, so all your emails will start arriving at that new host.</p>
<p>However, if you don&rsquo;t set up your email accounts on the new server correctly, those emails will either get lost somewhere or be marked as <em>&ldquo;undelivered: recipient doesn&rsquo;t exist.&rdquo;</em> I&rsquo;m guessing that&rsquo;s not what you want.</p>
<p>Luckily, preventing this is quite simple:</p>
<div class="su-row">
<div class="su-column su-column-size-1-3">
<div class="su-column-inner su-u-clearfix su-u-trim">
<p>In cPanel, scroll down to the <strong>EMAIL</strong> section and click on <strong>Email Accounts</strong>:</p>
</div>
</div>
<div class="su-column su-column-size-2-3">
<div class="su-column-inner su-u-clearfix su-u-trim"><img class="aligncenter size-full wp-image-46478" style="box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 459px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:459/h:151/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/email-accounts.png" alt="email accounts" width="1446" height="476" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1446/h:476/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/email-accounts.png" data-opt-lazy-loaded="true" data-opt-otimized-width="459" data-opt-optimized-height="151" /></div>
</div>
</div>
<p>Click on the <strong>+ Create</strong> button that&rsquo;s on the right.</p>
<p><img class="aligncenter size-full wp-image-46479" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:240/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/create-email.png" alt="create email" width="1944" height="666" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1944/h:666/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/create-email.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="240" /></p>
<p>What we&rsquo;re going to do now is add your existing email addresses to the new server.</p>
<p>Here&rsquo;s the form:</p>
<p><img class="aligncenter size-full wp-image-46480" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:702/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/email-add-form.png" alt="email add form" width="1480" height="1480" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1480/h:1480/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/email-add-form.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="702" /></p>
<ul>
<li><strong>Domain</strong> &ndash; select your new domain name &ndash; the one you&rsquo;re moving</li>
<li><strong>Username</strong> &ndash; this is important(!), you need to enter the same username that you used with your previous host; for example, if your email is <code>mark@YOURDOMAIN.com</code> then the username is <code>mark</code></li>
<li><strong>Password</strong> &ndash; a new password, doesn&rsquo;t need to be the same as the old one</li>
<li><strong>Storage Space</strong> &ndash; best set to <strong>Unlimited</strong></li>
</ul>
<p>Click on <strong>+ Create</strong> to finalize the setup.</p>
<p>&nbsp;</p>
<p>-&gt; If you have more emails set on your old host, repeat the process for each one.</p>
<p>You should see your email on the list.</p>
<p><img class="aligncenter size-full wp-image-46481" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:94/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/existing-emails.png" alt="existing emails" width="1932" height="259" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1932/h:259/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/existing-emails.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="94" /></p>
<p>At this stage, your new host is ready to welcome any incoming mail addressed to your domain.</p>
<div class="su-divider su-divider-style-dotted" style="margin: 40px 0; border-width: 1px; border-color: #999999;">&nbsp;</div>
<h2 id="step-3">Step 3: Upload the site to the new host</h2>
<p>With the domain name and database ready (and email as well), we can now upload your entire site backup to the new server.</p>
<div class="su-row">
<div class="su-column su-column-size-1-3">
<div class="su-column-inner su-u-clearfix su-u-trim">
<p>To do that, in cPanel scroll down to the <strong>FILES</strong> section and click on <strong>File Manager</strong>:</p>
</div>
</div>
<div class="su-column su-column-size-2-3">
<div class="su-column-inner su-u-clearfix su-u-trim"><img class="aligncenter size-full wp-image-46482" style="box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 459px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:459/h:113/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/file-manager.png" alt="file manager" width="1436" height="354" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1436/h:354/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/file-manager.png" data-opt-lazy-loaded="true" data-opt-otimized-width="459" data-opt-optimized-height="113" /></div>
</div>
</div>
<p>Navigate to the directory that&rsquo;s been created for the new domain name &ndash; the one you&rsquo;re transferring in. In most cases, that&rsquo;s going to be something like <code>public_html/YOURDOMAIN.com</code>.</p>
<p><img class="aligncenter size-full wp-image-46483" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:314/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/path.jpg" alt="path" width="2034" height="910" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:2000/h:895/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/path.jpg" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="314" /></p>
<p>Once there, simply upload your site&rsquo;s archive &ndash; the one you&rsquo;ve got from Duplicator. Remember to upload both the archive (zip) and the <code>installer.php</code> file. This is the directory where everything will end up when you move WordPress to a new server.</p>
<p><img class="aligncenter size-full wp-image-46484" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:162/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/upload.png" alt="upload" width="1012" height="234" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1012/h:234/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/upload.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="162" /></p>
<div class="su-divider su-divider-style-dotted" style="margin: 40px 0; border-width: 1px; border-color: #999999;">&nbsp;</div>
<h2 id="step-4">Step 4: Edit your local hosts file</h2>
<p>At this stage, you&rsquo;re almost ready to perform the final import of your website and transfer over all its files and data.</p>
<p>However! Before you can do that, you need to be able to access the new server via the browser from your local computer. This does sound fairly simple in itself, but there&rsquo;s one problem that we need to address:</p>
<p>Right now, your domain hasn&rsquo;t been officially redirected to the new server &ndash; we haven&rsquo;t done it yet to prevent downtime, and we&rsquo;re only going to do that at the very last moment. This is all fine and dandy, but it also means that your new server is basically <em>invisible</em> to the public (including you) and cannot be accessed directly.</p>
<p>To work around that, you can configure your local computer to go to the new server manually when looking for your website domain.</p>
<p>Here&rsquo;s how to do that:</p>
<p>First, go back to cPanel and see what your new server&rsquo;s IP address is. This piece of info is usually visible in the sidebar. Example:</p>
<p><img class="aligncenter size-full wp-image-46485" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:244/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/server-ip.jpg" alt="server ip" width="2042" height="711" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:2000/h:696/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/server-ip.jpg" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="244" /></p>
<p>Note this address down somewhere; you&rsquo;ll need it in a minute.</p>
<div class="su-accordion su-u-trim">
<div class="su-spoiler su-spoiler-style-fancy su-spoiler-icon-plus su-spoiler-closed" data-scroll-offset="0" data-anchor-in-url="no">
<div class="su-spoiler-title" tabindex="0" role="button"><strong>How to edit the hosts file on Windows: </strong></div>
<div class="su-spoiler-content su-u-clearfix su-u-trim">
<p>The <code>hosts</code> file can be found in <code>C:\Windows\System32\drivers\etc</code>. It may be hidden, so you might want to adjust the <em>file display settings</em> to see it.</p>
<p>The <code>hosts</code> file has no extension but it&rsquo;s in plain text format, which means that you can open it with Notepad.</p>
<p>At the very end of this file add a new line like this:</p>
<p><code>YOUR.SERVER.IP.ADDRESS YOURDOMAIN.com</code></p>
<p>For example:</p>
<p><code>10.21.11.192 YOURDOMAIN.com</code></p>
<p>Save the file.</p>
</div>
</div>
<div class="su-spoiler su-spoiler-style-fancy su-spoiler-icon-plus su-spoiler-closed" data-scroll-offset="0" data-anchor-in-url="no">
<div class="su-spoiler-title" tabindex="0" role="button"><strong>How to edit the hosts file on Mac: </strong></div>
<div class="su-spoiler-content su-u-clearfix su-u-trim">
<p>Fire up the Terminal app. You can find it via App Launcher.</p>
<p>Type in <code>sudo nano /etc/hosts</code> and hit enter.</p>
<p>Enter your admin password and hit enter.</p>
<p>You&rsquo;re now in the Nano text editor and you have the hosts file open.</p>
<p>&nbsp;</p>
<p>Position the cursor at the bottom using the arrow keys.</p>
<p>At the very end of this file add a new line like this:</p>
<p><code>YOUR.SERVER.IP.ADDRESS YOURDOMAIN.com</code></p>
<p>For example:</p>
<p><code>10.21.11.192 YOURDOMAIN.com</code></p>
<p>Once you have the line there, hold down the &ldquo;Control&rdquo; and &ldquo;O&rdquo; keys to save the file, then &ldquo;Control&rdquo; and &ldquo;X&rdquo; to exit.</p>
</div>
</div>
</div>
<p>From now on, when you try to navigate to your site from your web browser, you&rsquo;ll be taken straight to the new server.</p>
<p>&nbsp;Let&rsquo;s emphasize that only you can access your site&rsquo;s new server like that. Everyone else will still go to your old server when they try to view the site. So from their point of view, you didn&rsquo;t move WordPress to a new server just yet.</p>
<div class="su-divider su-divider-style-dotted" style="margin: 40px 0; border-width: 1px; border-color: #999999;">&nbsp;</div>
<h2 id="step-5">Step 5: Install site via online installer</h2>
<p>Fire up your browser and navigate to <code>YOURDOMAIN.com/installer.php</code>.</p>
<p>Once you do that, you&rsquo;ll see the main interface of the installer. All you need to do here is accept the terms and click on <strong>Next</strong>.</p>
<p><img class="aligncenter size-full wp-image-46487" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:471/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/duplicator-installer.png" alt="duplicator installer" width="1022" height="686" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:1022/h:686/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/duplicator-installer.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="471" /></p>
<p>The next step is where you&rsquo;ll need to enter the connection details of your new database &ndash; the blank one you created a couple of minutes ago.</p>
<p><img class="aligncenter size-full wp-image-46488" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:666/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/db-setup.png" alt="db setup" width="901" height="856" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:901/h:856/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/db-setup.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="666" /></p>
<p>For most hosts, the <strong>Host</strong> value should be set to <code>localhost</code>. Click on <strong>Test Database</strong> when you have all the fields filled in.</p>
<p>If all went well, you should see this:</p>
<p><img class="aligncenter size-full wp-image-46489" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:215/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/db-success.png" alt="db success" width="913" height="280" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:913/h:280/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/db-success.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="215" /></p>
<p>You can click on <strong>Next</strong> to proceed, and then confirm the popup message to run the installer.</p>
<p>Click <strong>Next</strong> again on the next screen to confirm the site title and URL.</p>
<p>After a couple of seconds, the installation should be complete. Here&rsquo;s what the final confirmation message usually looks like when you manage to move WordPress to a new server:</p>
<p><img class="aligncenter size-full wp-image-46490" style="margin: 40px auto; box-shadow: rgba(0, 0, 0, 0.5) 0px 0px 8px 2px; max-width: 702px;" src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:702/h:517/q:90/dpr:1.3/https://www.codeinwp.com/wp-content/uploads/2014/01/duplicator-success.png" alt="Move WordPress to a new server or host: Duplicator success!" width="987" height="727" data-opt-src="https://iotvnaw69daj.i.optimole.com/AXVzL2w.n2y9~6666f/w:987/h:727/q:90/https://www.codeinwp.com/wp-content/uploads/2014/01/duplicator-success.png" data-opt-lazy-loaded="true" data-opt-otimized-width="702" data-opt-optimized-height="517" /></p>
<p>It&rsquo;s a good idea to check the box labeled, &ldquo;Auto delete installer files &hellip;&rdquo;</p>
<p>Click on <strong>Admin Login</strong> to access the WordPress dashboard of the site on the new host. All your WordPress accounts are the same as they were before moving the site to the new host.</p>
<p>After you log in, you&rsquo;ll see a confirmation that the installer files have been removed. You probably don&rsquo;t need the Duplicator plugin anymore so go ahead and deactivate/delete it.</p>
<p>You can see your website on the new server in all its glory when you navigate to <code>YOURDOMAIN.com</code>. Just keep in mind that it&rsquo;s just you seeing it right now (it&rsquo;s not yet been made public on the web) &ndash; this is due to the <em>hosts</em> file thing that we talked about a minute ago. Let&rsquo;s address this in the final step:</p>
