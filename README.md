{% include header.html %}

Working on my own blue zone! :-)

![](https://media.licdn.com/dms/image/C4D03AQG6BcwZrH-ytA/profile-displayphoto-shrink_200_200/0?e=1554336000&v=beta&t=I8tJMtcmzSqlw5dJVCMUpQ_JgR3whYC4SO_BCXKMAJs)

![](https://media.licdn.com/dms/image/C4D16AQEh5uPtaIzs0g/profile-displaybackgroundimage-shrink_350_1400/0?e=1554336000&v=beta&t=vkWwLvGi7ZTqOFTx9TjO7DuP-FhwYwpxVmw6oVuxxp4)

[View](https://orzanna.de/) | [Edit](https://github.com/orschiro/Orschiro/edit/master/README.md) | [Comment](https://orzanna.de/#leave-a-comment)

# Table of Contents

* TOC
{:toc}

# Essential Linux software I cannot work without

- Flameshot for screenshot annotation
- Rofi to launch apps and switch windows
- Xfce as my desktop environment
- Telegram Desktop for its tray icon to stay up to date with new messages
- Chrome browser (yes...)
- Crontab as my hourly live saver

# Chrome dark mode

Hands down the best extension I have come across to darken any website without excessive memory or CPU use. It's called [Dark Reader Dark](https://chrome.google.com/webstore/detail/dark-reader-dark/kbbbldgkhcpkmmjbjelmkjkchibeklng). Totally recommendable!

# Reddit bookmarklet one click create rss feed

Use the following bookmarklet to create an RSS feed based on the Reddit thread you're looking at. Handy to subscribe to it using any kind of RSS reader!

```
javascript:(function(){document.location+='/.rss'}());
```

![](https://i.imgur.com/H4YbQYh.png)

# Best Chrome extensions

Hands on the best Chrome extensions I have found:

![](https://i.imgur.com/oIAvl7H.png)
![](https://i.imgur.com/dYc4npo.png)

# Rofi Xfce window switcher and application launcher

Found [Rofi](https://github.com/DaveDavenport/rofi/) to be the best way to quickly switch windows and launch apps on Xfce. I mapped the following command to the Super key.

```
rofi -combi-modi window,drun -theme Arc-Dark -show combi -modi combi
```

# Blue zone longevity best practices lessons learned

- Drinking a glass of good (organic) red wine from time to time is not bad
- Drinking one or two cups of coffee a day is not bad either
- Never skip a decent breakfast
- Eat a good lunch around 12-13 o clock
- Eat a small dinner around 17-18 o clock
- Eat salt in moderation
- Try to avoid sugar
- Try to avoid processed / industrial food
- Focus on legumes, seasonal vegetables, nuts and good oil from your region
- Try to be in motion for 2-3 hours a day
- Walking is the best sport
- Sleep sufficiently
- Eat good carbs (artesanal pasta) and avoid bad carbs (white bread, industrial pasta and potatoes)

# Feedly RSS tips and tricks best practices

- Add an unread counter to your Chrome toolbar using [this extension](https://olsh.me/Feedly-Notifier/)
- Tweak this extension to open Feedly on extension icon click
- Disable Feedly auto mark as read on scroll
- Tweak sources to directly open source on click
- Get yourself used to using the X (mark as read and hide)
- IMPORTANT: Don't feel any pressure getting your unread counter down to 0

# Github Pages Table of Contents README.md

See this nice automatically generated table of content / index above? Yes, it's possible to have that in a README.md that's hosted on Github Pages. Add `markdown: kramdown` to your `_config.yml` and subsequently the following snippet where you want your TOC to appear in the README. 

```
# Table of Contents

* TOC
{:toc}
```

# Fix dnfdragora Fedora Xfce update nofifier

I found the Fedora Xfce update notifier dnfdragora to never work properly out of the box. I added the two following lines to my `crontab -e` to fix this.

```
0 * * * * dnfdragora --exit && killall dnfdragora-updater
5 */3 * * * export DISPLAY=:0 && dnfdragora-updater
```

![](https://i.imgur.com/lvAfzUN.png)

# Aktive Communities GamersGlobal & Caschys Blog via Feedly folgen

Warum lese ich bestimmte Seiten gerne? Weil sie eine aktive Community haben, die viele Kommentare postet. So lese ich z.B. gerne [GamersGlobal](https://www.gamersglobal.de/), wenn es um Spielethemen geht und [Caschys Blog](https://stadt-bremerhaven.de/) für Technik- und Internetthemen. Da wird immer rege diskutiert und kommentiert. Oftmals spannender und interessanter als der Artikel selbst. :-)

So, nächste Frage. Wie am besten diese beiden Seiten filtern, um nur über Highlights informiert zu werden und nicht mit Inhalten geflutet zu werden? GamersGlobal bietet einen [Highlights-RSS-Feed](https://www.gamersglobal.de/feeds/highlights) an. Caschys Blog leider nicht.

Ich hab trotzdem mal beides in Feedly eingepflegt. Feedly gibt mir für Caschys Blog ein Gefühl dafür, was gerade popular und trending ist. So sieht das ganze bei mir aus.

![](https://i.imgur.com/56UeKbO.png)

# Fastest way to search your Linux terminal 

Install [fzf](https://github.com/junegunn/fzf) and press `Ctrl + R` to search your command line history. Amazing stuff!

![](https://i.imgur.com/vw0QXj9.gif)

# Blauzone Blue Zone Mannheim

Wie lebt man eine sogenannte [Blue zone](https://en.wikipedia.org/wiki/Blue_Zone) / Blauzone im deutschen Mannheim? Genau das will ich in den nächsten Monaten herausfinden. Fest steht, auf den Wochenmarkt gehen, viel im Wald spazieren und einen eigenen Garten beackern. 

Was Ernährung angeht, das muss ich noch herausfinden, wie man das am besten in Mannheim / Deutschland macht.

# Age of Empires 2 HD on Fedora Linux

Works great on Fedora 28. Just install Steam, enable Proton Beta settings for all games and then rename the `AoK HD.exe` to `Launcher.exe` in the folder `/home/username/.local/share/Steam/steamapps/common/Age2HD`.

# Alt + Q Switch Tabs Keyboard Shortcut for Google Chrome

Very easy way to switch between two open tabs. Just press Alt + Q. All you have to do is install this extension:

[Install](https://chrome.google.com/webstore/detail/alt-%20-q-switch-tabs-keybo/odhjcgnlbagjllfbilicalpigimhdcll)

# Seeking cloud Virtual Machine users Compensation: $150.00

Do you work in cloud cloud computing and have VM experience? The Microsoft Azure team is looking to speak with users about a new Azure networking feature and collect feedback that will help influence the feature before it is released to the public.

[Start survey](https://app.respondent.io/projects/view/5c426abc06dc1a002ccd4090/seeking-cloud-virtual-machine-users/robertorzanna-dc40dda76f3b)

# Seeking those responsible for managing customer communication channels Compensation: $100.00

We’re looking to speak with professionals responsible for managing multiple communication channels (e.g. email, SMS, push) to converse with customers. Specifically, those who have evaluated, purchased, and implemented “integrated suites” or “best of breed” solutions.

[Start survey](https://app.respondent.io/projects/view/5c3e62790a3662002bca347d/seeking-those-responsible-for-managing-customer-communication-channels/robertorzanna-dc40dda76f3b)

# Fedora 29: switch from suspend to hibernate automatically

Jan wrote the excellent blog post [Hibernate after suspend (on Fedora)](https://kcore.org/2017/12/22/hibernate-after-suspend-on-fedora/) that is still fully applicable to Fedora 29. Follow the instructions to have your laptop switch from suspend to hibernate automatically after 30 minutes. Very useful if normally you just close your lid to suspend and then open the lid again within 30 minutes.

But what if not? Then your battery would just drain down. Better to send it to hibernation after 30 minutes.

# The best Xfce distros

Want to test some of the [Xfce](http://xfce.org/) flagships? Here they are. It used to be [Xubuntu](https://xubuntu.org/) but nowadays great spins of Xfce are available from [Manjaro](https://manjaro.org/get-manjaro/), [Linux Mint](https://linuxmint.com/download.php), and [Fedora](https://spins.fedoraproject.org/xfce/).

If you want to try some nichy distros, then go ahead with Arch, [Salix](https://www.salixos.org/download.html) (Slackware), [Xebian](http://www.xebian.org/) or [Devuan](https://devuan.org/os/) (Debian) or [MX Linux](https://mxlinux.org/download-links).

Source: [Reddit](https://www.reddit.com/r/xfce/comments/7tsgi3/does_xfce_have_a_flagship_distro_like_fedora_is/)

# Talk with us about your global sourcing experience $100.00 / 60 minute(s)

We're a world scale B2B platform with hundreds of thousands of buyers and suppliers. We'd like to work with you to provide better marketplace for global sourcing.Talk with us about how do you do and what do you want when sourcing globally.

[Participate now](https://app.respondent.io/projects/view/5c41431cc8404b00265f5047/talk-with-us-about-your-global-sourcing-experience/robertorzanna-dc40dda76f3b)

# Understanding testing practices in software teams $130.00 / 60 minute(s)

We're seeking to understand how software teams go about testing the quality of their products and the tools they use. During this session, we would ask you about your role, your team, how you do testing on a day to day basis. And with your consent, we would like to see how you use the tools.

[Paricipate now](https://app.respondent.io/projects/view/5c415768ff8f000027c57e22/understanding-testing-practices-in-software-teams/robertorzanna-dc40dda76f3b)

# Learn entertaining Australian English

[Unmade.fm](https://www.unmade.fm/) great podcast to listen to two guys speaking in their Australian English in a very entertaining way. Totally recommendable! And they do have a [Patreon page](https://www.patreon.com/unmadeFM) to support them with a monthly donation.

# Seeking data science professionals to take ~20 minute survey $35.00 / 20 minute(s)

We're looking for data science professionals to tell us about what they do, the tools they use, and to provide feedback on related product features. You should have a good understanding of the overall data science process at your company.

[Participate now](https://app.respondent.io/r/robertorzanna-dc40dda76f3b)

# Seeking individuals who currently use a CMS at work $30.00 / 15 minute(s)

What are the most and least important features of a CMS when it comes to your organization's marketing efforts? Join our study to share your input on content management systems and how you'd like to see these tools evolve.

[Participate now](https://app.respondent.io/r/robertorzanna-dc40dda76f3b)

# Promising ETFs to track more closely

The below are showing a positive rate for the last weeks.

- LU0458538880 / A0YCZ3 FAIR WORLD FONDS +0,78 %
- IE00B4ND3602 / A1KWPQ ISHARES PHYS.MET.... +4,91 %
- LU0488317701 / ETF091 C.S.-NYSE AR.GO.B...	+1,66 %

# Gewinne 1000€ Grundeinkommen
Willst du mit mir den Sozialstaat der Zukunft ausprobieren? Dann lass uns zusammen bei dieser Verlosung mitmachen und jeweils ein einjähriges Grundeinkommen von 1.000 Euro im Monat gewinnen. Link zur Teilnahme > [Klick](www.meinbge.de/fuer-dich/f17431bcf77ddfa8fd0d)

![grundeinkommen](https://www.mein-grundeinkommen.de/assets/campaigns/referral/fuer-alle-ba03fa67b0d39921a3ada05c78371db77b2712694ff7ac5e74080cd411391676.png)

{% include body.html %}

# Leave a comment

{% include disqus.html %}
