---
layout: default
title: Aprender sobre el mejor software de minería Bitcoin
description: Aprender sobre el mejor software de minería Bitcoin
toc:
  nc: Network Consensus
  bw: Bitcoin Wallet Software
  fa: Free Bitcoin Mining Applications
  windows: Windows Mining Software
  osx: Mac OSX Mining Software
  asic: ASIC Bitcoin Mining Software
  cloud: Bitcoin Cloud Mining Software
---

<h1>Bitcoin Mining Software Guide</h1>
<img src="/images/bitcoin-chart-going-up-arrow.jpg" alt="bitcoin chart going up arrow" width="700" height="247"/>

{% include page-toc.html %}

<p>While the actual process of Bitcoin mining is handled by the <a href="/bitcoin-mining-hardware/">Bitcoin mining hardware</a> itself, special Bitcoin mining software is needed to connect your Bitcoin miners to the blockchain and your Bitcoin mining pool as well, if you are part of a Bitcoin mining pool.
<p>The software delivers the work to the miners and receives the completed work from the miners and relays that information back to the blockchain and your mining pool. The best Bitcoin mining software can run on almost any operating system, such as OSX, Windows, Linux, and has even been ported to work on a Raspberry Pi with some modifications for drivers depending on your mining setup.
<p>Not only does the Bitcoin mining software relay the input and output of your Bitcoin miners to the blockchain, but it also monitors them and displays general statistics such as the temperature, hashrate, fan speed, and average speed of the Bitcoin miner.
<p>There are a few different types of Bitcoin mining software out there and each have their own advantages and disadvantages, so be sure to read up on the various mining software out there.
<h2 id="nc">Network Consensus</h2>
<center><img src="/images/bitcoin-network-consensus.jpg" alt="bitcoin network consensus"></center>
<p>If you solo-mine, meaning you do not mine <a href="/bitcoin-mining-pools/">with a Bitcoin mining pool</a>, then you will need to ensure that you are in consensus with the Bitcoin network. The best way is to use the <a href="http://bitcoin.org/en/download">official BitCore client</a>.
<p>If you participate in a <a href="/bitcoin-mining-pools/">Bitcoin mining pool</a> then you will want to ensure that they are engaging in behavior that is in agreement with your philosophy towards Bitcoin.
<p>How much bandwidth does Bitcoin mining take? If you are <a href="/bitcoin-mining-pools/">mining with a pool</a> then the amount should be negligible with about 10MB/day. However, what you do need is exceptional connectivity so that you get any updates on the work as fast as possible.
<p>For example, some rogue developers have threatened to release software that could hard-fork the network which would likely result in tremendous financial damage.
<p>Therefore, it is your duty to make sure that any Bitcoin mining power you direct to a mining pool does not attempt to enforce network consensus rules you disagree with.
<h2 id="bw">Bitcoin Wallet Software</h2>
<p>The whole point of mining bitcoins is to earn them!
<p>But once you earn them then where do you keep them safe and secure? For a <a href="https://www.weusecoins.com/en/find-the-best-bitcoin-wallet/">Bitcoin wallet</a> we <b>highly recommend</b> using one where you hold your own private keys in contrast to to a hosted wallet like Coinbase or Circle.
<ul><li><a href="http://breadwallet.com/">Breadwallet</a> - easy to use mobile Bitcoin wallet</li>
<li><a href="https://copay.io/">Copay</a> - easy to use mobile Bitcoin wallet</li>
<li><a href="https://bitcoinarmory.com/">Armory</a> - highly secure desktop Bitcoin wallet</li></ul>
<p>You will also need to be able to buy and <a href="https://www.weusecoins.com/how-to-sell-bitcoins/">sell your Bitcoins</a>.
<p>Once mined Bitcoin becomes like a currency that can be purchased, used in transactions or even traded like with this <a href="http://www.avatrade.com/trading-info/range-of-markets/bitcoin">Bitcoin trading platform</a>.
<p>For this we recommend:
<ul>
<li><a href="https://www.kraken.com/">Kraken</a> - The largest European exchange with same-day SEPA</li>
<li><a href="http://geni.us/localbitcoins">Local Bitcoins</a> - This fantastic service allows you to search for people in your community willing to sell bitcoins to you directly. But be careful!</li>
</ul>
<center><iframe width="700" height="394" src="https://www.youtube.com/embed/MH2i9pudQgk" frameborder="0" allowfullscreen></iframe></center>
<h2 id="fa"><em>Examples of the best Bitcoin mining software for Windows, Linux and Mac OSX:</em></h2>

<div class="mining-software-wrap">
{% for software in site.data.software %}
{% if software.cats contains 'best' %}
{% include software.html %}
{% endif %}
{% endfor %}
</div>

<h1>Additional Free Bitcoin Mining Applications</h1>

<div class="mining-software-wrap">
{% for software in site.data.software %}
{% include software.html %}
{% endfor %}
</div>

<h1 id="windows">Best Bitcoin Mining Software Windows</h1>

<div class="mining-software-wrap">
{% for software in site.data.software %}
{% if software.os contains 'windows' %}
{% include software.html %}
{% endif %}
{% endfor %}
</div>

<h1 id="osx">Best Bitcoin Mining Software Mac OSX</h1>

<div class="mining-software-wrap">
{% for software in site.data.software %}
{% if software.os contains 'mac' %}
{% include software.html %}
{% endif %}
{% endfor %}
</div>

<h1 id="asic">ASIC Bitcoin Mining Software</h1>

<div class="mining-software-wrap">
{% for software in site.data.software %}
{% if software.cats contains 'asic' %}
{% include software.html %}
{% endif %}
{% endfor %}
</div>

<h2 id="cloud">Bitcoin Cloud Mining Software</h2>
<div class="mining-software-wrap">
<p>Being listed in this section is NOT an endorsement of these services. There have been a tremendous amount of Bitcoin cloud mining scams.</p>

{% for service in site.data.cloud %}
{% if service.desc_btc != null %}
<p class="cloud-mining-info">
<b>{% if service.url != null %}<a rel="nofollow" href="{{ service.url }}">{{ service.company }}</a>: {% else %}{{ service.company }}: {% endif %}</b>{{ service.desc_btc }}
</p>
{% endif %}
{% endfor %}
</div>

<h2>TRANSCRIPT - Do it yourself with Bitcoin mining software</h2>
<p>What's going on every one?  This is Fredand this Part 2 of our DIY Bitcoin Miner.  Today, we're going to take a look at software.

<p>Okay, so the first thing that you need to do before you could start Bitcoin mining is to sign up for a Bitcoin wallet.  Now there’s a lot of wallets that you could choose from but I prefer Circle.  Now let’s head over and set up an account.  All you have to do is enter in your email and choose a password.

<p>Once you log in to your account you will see a summary of your Bitcoin balance and transactions.  But before you can receive any Bitcoins you need to set up a Bitcoin address.  You could do so by clicking account settings.

<p>Once you are on the account settings page go ahead and click Bitcoin Addresses.  From there click Create New Address.  This generates a long string of numbers and letters.  This is the address that we will need to enter into our mining pool.  So let's take a look at that now.

<p>There are many mining pools that you can choose from, but I prefer BitMinter as my primary pool and Slush’s pool as my backup.  Just create an account whichever one you choose and log in.  Your account details page will normally have an auto cash out option.

<p>This is where we will enter in our wallet address that we created earlier.  When you have mined enough Bitcoins to meet the threshold it would automatically be transferred to your Bitcoin wallet.

<p>Next, go up top to the My Account drop down and select Workers.  This worker information is what you need to input into the mining software so that you get credit for the work that is done.  You do not need to secure this information with a difficult username or password because anyone that uses this information will be giving you credit.

<p>Now let's take a look at setting up the mining software.  As mentioned in Part 1 of the series we'll be using the MinePeon operating system.  This can be downloaded from sourceforge.net.

<p>Now this is the image that we will need to write onto our SD card.  Another software that we need to download is called the Win32 Disk Imager.  This can also be found on sourceforge.net.  This is the software that we will use to write the MinePeon image onto our SD card.

<p>Once you have downloaded both files insert your SD card into your computer.  Then open up Win32 Disk Imager.  Simply select the location of your MinePeon image then select the correct drive for your SD card.  All you have to do now is click write.  This will write the MinePeon image on to your SD card.  Insert the SD card into your Raspberry Pi as shown on Part 1 of the series then power up the unit.

<p>Now sign in to MinePeon by typing in the network IP address into your browser.  The easiest way to find this IP address is by logging in to your router and looking for the device called MinePeon.  You will then be prompted to enter in your MinePeon's username and password.  The default setting for this is MinePeon for the username, peon for the password.  You will see a security warning but do not be alarmed.  This is perfectly normal so proceed anyways.  You will then be asked to re-enter the username and password.

<p>So again, MinePeon is the username peon is the password.  You are now finally in MinePeon's dashboard.  This is where you can monitor the performance of your mining rig.  Head up top and click pools.  This page allows you to set up your mining pools.  As you can see I have BitMinter as my primary pool and Slush’s pool as my secondary.  Just enter in the URL of your mining pool, the username and password if you have one.

<p>Then go ahead and submit your settings.  You may need to reboot MinePeon after any changes.  Great job every one.  You are now officially mining for Bitcoins.

<p>All right, so that should be everything that you need to start Bitcoin mining.
