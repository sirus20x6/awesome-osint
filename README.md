# Awesome OSINT [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://github.com/jivoi/awesome-osint/raw/master/osint_logo.png" align="right" width="100">](https://github.com/jivoi/awesome-osint)

A curated list of amazingly awesome open source intelligence tools and resources.
[Open-source intelligence (OSINT)](https://en.wikipedia.org/wiki/Open-source_intelligence) is intelligence collected from publicly available sources.
In the intelligence community (IC), the term "open" refers to overt, publicly available sources (as opposed to covert or clandestine sources). 

This list is to help all of those who are into Cyber Threat Intellience (CTI), threat hunting, or OSINT. From beginners to advanced. 

Happy hacking and hunting 🧙‍♂️

## 📖 Table of Contents

 - [🔍 General Search](#-general-search)
 - [🤖 Google Dorks](#-google-dorks-tools)
 - [🌐 Main National Search Engines](#-main-national-search-engines)
 - [🔄 Meta Search](#-meta-search)
 - [🔒 Privacy Focused Search Engines](#-privacy-focused-search-engines)
 - [💧 Data Breach Search Engines](#-databreach-search-engines)
 - [🎯 Specialty Search Engines](#-specialty-search-engines)
 - [🕶️ Dark Web Search Engines](#-dark-web-search-engines)
 - [👁️ Visual Search and Clustering Search Engines](#-visual-search-and-clustering-search-engines)
 - [🔗 Similar Sites Search](#-similar-sites-search)
 - [📄 Document and Slides Search](#-document-and-slides-search)
 - [🎭 Threat Actor Search](#-threat-actor-search)
 - [⚡ Live Cyber Attack Maps](#-live-cyberthreat-maps)
 - [📁 File Search](#-file-search)
 - [📋 Pastebins](#-pastebins)
 - [💻 Code Search](#-code-search)
 - [📱 Major Social Networks](#-major-social-networks)
 - [⚡ Real-Time Search, Social Media Search, and General Social Media Tools](#-real-time-search-social-media-search-and-general-social-media-tools)
 - [🛠️ Social Media Tools](#social-media-tools)
   - [🐦 Twitter](#-twitter)
   - [👤 Facebook](#-facebook)
   - [📸 Instagram](#-instagram)
   - [📌 Pinterest](#-pinterest)
   - [🔴 Reddit](#-reddit)
   - [🇷🇺 VKontakte](#-vkontakte)
   - [✏️ Tumblr](#-tumblr)
   - [💼 LinkedIn](#-linkedin)
   - [✈️ Telegram](#-telegram)
   - [🎮 Steam](#-steam)
   - [🐙 GitHub](#-github)
   - [🎵 TikTok](#-tiktok)
   - [💬 Discord](#-discord)
   - [🐘 Mastodon / Fediverse](#-mastodon--fediverse)
 - [📝 Blog Search](#-blog-search)
 - [💬 Forums and Discussion Boards Search](#-forums-and-discussion-boards-search)
 - [🔎 Username Check](#-username-check)
 - [👥 People Investigations](#-people-investigations)
 - [📧 Email Search / Email Check](#-email-search--email-check)
 - [📞 Phone Number Research](#-phone-number-research)
- [🚗 Vehicle / Automobile Research](#-vehicle--automobile-research)
 - [🎓 Expert Search](#-expert-search)
 - [🏢 Company Research](#-company-research)
 - [👔 Job Search Resources](#-job-search-resources)
 - [❓ Q&A Sites](#-qa-sites)
 - [🖥️ Domain and IP Research](#-domain-and-ip-research)
 - [🔑 Keywords Discovery and Research](#-keywords-discovery-and-research)
 - [⏳ Web History and Website Capture](#-web-history-and-website-capture)
 - [🗣️ Language Tools](#-language-tools)
 - [🖼️ Image Search](#-image-search)
 - [🔬 Image Analysis](#-image-analysis)
 - [🎥 Video Search and Other Video Tools](#-video-search-and-other-video-tools)
 - [📚 Academic Resources and Grey Literature](#-academic-resources-and-grey-literature)
 - [🌍 Geospatial Research and Mapping Tools](#-geospatial-research-and-mapping-tools)
 - [📰 News](#-news)
 - [📡 News Digest and Discovery Tools](#-news-digest-and-discovery-tools)
 - [✅ Fact Checking](#-fact-checking)
 - [📊 Data and Statistics](#-data-and-statistics)
 - [👀 Web Monitoring](#-web-monitoring)
 - [🧭 Browsers](#-browsers)
 - [📥 Offline Browsing](#-offline-browsing)
 - [🛡️ VPN Services](#-vpn-services)
 - [📈 Infographics and Data Visualization](#-infographics-and-data-visualization)
 - [🕸️ Social Network Analysis](#-social-network-analysis)
 - [🔐 Privacy and Encryption Tools](#-privacy-and-encryption-tools)
 - [🔤 DNS](#-dns)
 - [⚓ Maritime](#-maritime)
 - [✈️ Aviation / Flight Tracking](#-aviation--flight-tracking)
 - [🪙 Cryptocurrency / Blockchain](#-cryptocurrency--blockchain)
 - [🧰 Other Tools](#-other-tools)
 - [🕵️ Threat Intelligence](#-threat-intelligence)
 - [🎮 Gaming Platforms](#-gaming-platforms)
 - [🎵 Music Streaming Services](#-music-streaming-services)
 - [🎬 OSINT Videos](#-osint-videos)
 - [✍️ OSINT Blogs](#-osint-blogs)
 - [📦 Other Resources](#-other-resources)
 - [⭐ Related Awesome Lists](#-related-awesome-lists)
* <img src="https://www.google.com/s2/favicons?domain=duckduckgo.com&sz=16" width="16" height="16"> [DuckDuckGo](https://duckduckgo.com/) - Privacy-focused search engine that doesn't track users or filter results based on search history.
* <img src="https://www.google.com/s2/favicons?domain=search.brave.com&sz=16" width="16" height="16"> [Brave Search](https://search.brave.com/) - Independent privacy search engine with its own index, no tracking.
* <img src="https://www.google.com/s2/favicons?domain=haveibeenpwned.com&sz=16" width="16" height="16"> [Have I Been Pwned](https://haveibeenpwned.com/) - Check if your email or phone has been compromised in a data breach.
* <img src="https://www.google.com/s2/favicons?domain=dehashed.com&sz=16" width="16" height="16"> [DeHashed](https://dehashed.com/) - Search engine for leaked credentials and personal information from data breaches.
* <img src="https://www.google.com/s2/favicons?domain=leakcheck.io&sz=16" width="16" height="16"> [LeakCheck](https://leakcheck.io/) - Breach search engine with email, username, phone, and keyword lookups.
* <img src="https://www.google.com/s2/favicons?domain=breachdirectory.org&sz=16" width="16" height="16"> [BreachDirectory](https://breachdirectory.org/) - Free breach search with partial password reveals.
* [DarkSearch](https://darksearch.io/) - Dark web search engine with a free API for researchers.
* [Haystak](http://haystak5njsmn2hqkewecpaxetahtwhsbsa64jom2k22z5afxhnpxfid.onion) - Tor search engine claiming to index over 1.5 billion pages.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [OnionSearch](https://github.com/megadose/OnionSearch) - Python script to scrape URLs from multiple .onion search engines.
* [Torch](http://xmh57jrknzkhv6y3ls3ubitzfqnkrwxhopf5aygthi7d6rplyvk3noyd.onion) - One of the oldest and largest Tor search engines.
* <img src="https://www.google.com/s2/favicons?domain=nitter.net&sz=16" width="16" height="16"> [Nitter](https://nitter.net/) - Privacy-focused Twitter frontend used by OSINT practitioners to browse without an account.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [snscrape](https://github.com/JustAnotherArchivist/snscrape) - Social network scraper supporting Twitter, Facebook, Instagram, Reddit, and more.
* <img src="https://www.google.com/s2/favicons?domain=whopostedwhat.com&sz=16" width="16" height="16"> [Who Posted What](https://whopostedwhat.com/) - Facebook keyword search by date range, built by Henk van Ess.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [CrossLinked](https://github.com/m8sec/CrossLinked) - LinkedIn enumeration tool to extract employee names for username generation.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [linkedin2username](https://github.com/initstring/linkedin2username) - Generate username lists from LinkedIn company employee listings.
* <img src="https://www.google.com/s2/favicons?domain=www.linkedin.com&sz=16" width="16" height="16"> [LinkedIn Sales Navigator](https://www.linkedin.com/sales/) - Advanced people and company search with filters for lead generation and OSINT.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Skiptracer](https://github.com/xillwillx/skiptracer) - OSINT framework for people search and investigation.
* <img src="https://www.google.com/s2/favicons?domain=clearbit.com&sz=16" width="16" height="16"> [Clearbit Connect](https://clearbit.com/) - Email enrichment tool that finds company and person details from an email address.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Ignorant](https://github.com/megadose/ignorant) - Check if a phone number is registered on various platforms without alerting the owner.
* <img src="https://www.google.com/s2/favicons?domain=numverify.com&sz=16" width="16" height="16"> [NumVerify](https://numverify.com/) - Global phone number validation and lookup API supporting 232 countries.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [DNSRecon](https://github.com/darkoperator/dnsrecon) - DNS enumeration script for zone transfers, brute-force, and SRV record discovery.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner that can scan the entire Internet in under 5 minutes.
* <img src="https://www.google.com/s2/favicons?domain=nmap.org&sz=16" width="16" height="16"> [Nmap](https://nmap.org/) - The industry-standard network scanner for host discovery, port scanning, and service detection.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Subfinder](https://github.com/projectdiscovery/subfinder) - Fast passive subdomain enumeration tool using multiple online sources.
* <img src="https://www.google.com/s2/favicons?domain=www.whoxy.com&sz=16" width="16" height="16"> [Whoxy](https://www.whoxy.com/) - Reverse WHOIS lookup service with historical WHOIS records and company search.
* <img src="https://www.google.com/s2/favicons?domain=www.invid-project.eu&sz=16" width="16" height="16"> [InVID / WeVerify](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) - Browser plugin for image and video verification, reverse search, and metadata analysis.
* <img src="https://www.google.com/s2/favicons?domain=www.invid-project.eu&sz=16" width="16" height="16"> [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) - Standard tool for video verification, keyframe extraction, and reverse frame search.
* [Copernicus Open Access Hub](https://scihub.copernicus.eu/) - Free Sentinel satellite imagery for environmental monitoring and geospatial analysis.
* <img src="https://www.google.com/s2/favicons?domain=earthengine.google.com&sz=16" width="16" height="16"> [Google Earth Engine](https://earthengine.google.com/) - Planetary-scale geospatial analysis platform with petabytes of satellite imagery.
* <img src="https://www.google.com/s2/favicons?domain=overpass-turbo.eu&sz=16" width="16" height="16"> [Overpass Turbo](https://overpass-turbo.eu/) - Web-based query tool for OpenStreetMap data, essential for geolocation investigations.
* <img src="https://www.google.com/s2/favicons?domain=www.planet.com&sz=16" width="16" height="16"> [Planet](https://www.planet.com/) - Daily satellite imagery of the entire Earth with free tiers for researchers.
* <img src="https://www.google.com/s2/favicons?domain=factcheck.afp.com&sz=16" width="16" height="16"> [AFP Fact Check](https://factcheck.afp.com/) - Agence France-Presse's dedicated fact-checking service covering global misinformation.
* <img src="https://www.google.com/s2/favicons?domain=idir.uta.edu&sz=16" width="16" height="16"> [ClaimBuster](https://idir.uta.edu/claimbuster/) - AI-powered tool for detecting and scoring check-worthy factual claims.
* [Google Fact Check Explorer](https://toolbox.google.com/factcheck/explorer) - Searches fact-checks from dozens of verified organizations worldwide.
* <img src="https://www.google.com/s2/favicons?domain=www.politifact.com&sz=16" width="16" height="16"> [PolitiFact](https://www.politifact.com/) - Pulitzer Prize-winning fact-checking site rating the accuracy of political claims.
* <img src="https://www.google.com/s2/favicons?domain=www.reuters.com&sz=16" width="16" height="16"> [Reuters Fact Check](https://www.reuters.com/fact-check/) - Reuters' dedicated fact-checking unit debunking misinformation.
* <img src="https://www.google.com/s2/favicons?domain=www.equasis.org&sz=16" width="16" height="16"> [EquasisSearch](https://www.equasis.org/) - International ship safety and quality information database run by the EU and France.
* <img src="https://www.google.com/s2/favicons?domain=www.fleetmon.com&sz=16" width="16" height="16"> [FleetMon](https://www.fleetmon.com/) - Vessel tracking, port calls, and maritime analytics platform.
* <img src="https://www.google.com/s2/favicons?domain=www.marinetraffic.com&sz=16" width="16" height="16"> [MarineTraffic](https://www.marinetraffic.com/) - The most widely used real-time vessel tracking platform with AIS data worldwide.
* <img src="https://www.google.com/s2/favicons?domain=www.myshiptracking.com&sz=16" width="16" height="16"> [myShipTracking](https://www.myshiptracking.com/) - Free real-time ship tracking with port and vessel search.
* <img src="https://www.google.com/s2/favicons?domain=www.vesselfinder.com&sz=16" width="16" height="16"> [VesselFinder](https://www.vesselfinder.com/) - Free AIS vessel tracking with ship positions, port arrivals, and voyage history.
* <img src="https://www.google.com/s2/favicons?domain=cytoscape.org&sz=16" width="16" height="16"> [Cytoscape](https://cytoscape.org/) - Open-source platform for complex network analysis and visualization.
* <img src="https://www.google.com/s2/favicons?domain=www.ibm.com&sz=16" width="16" height="16"> [i2 Analyst's Notebook](https://www.ibm.com/products/i2-analysts-notebook) - Industry-standard link analysis and data visualization for intelligence analysts.
* <img src="https://www.google.com/s2/favicons?domain=www.maltego.com&sz=16" width="16" height="16"> [Maltego](https://www.maltego.com/) - Interactive data mining and link analysis tool for mapping relationships between entities.
* <img src="https://www.google.com/s2/favicons?domain=nodexl.com&sz=16" width="16" height="16"> [NodeXL](https://nodexl.com/) - Network analysis and visualization template for Excel, popular for social media research.
* <img src="https://www.google.com/s2/favicons?domain=abuse.ch&sz=16" width="16" height="16"> [Abuse.ch](https://abuse.ch/) - Community-driven threat intelligence hub providing URLhaus, MalwareBazaar, ThreatFox, and more.
* <img src="https://www.google.com/s2/favicons?domain=www.misp-project.org&sz=16" width="16" height="16"> [MISP](https://www.misp-project.org/) - Open-source threat intelligence and sharing platform used by CSIRTs and SOCs worldwide.
* <img src="https://www.google.com/s2/favicons?domain=attack.mitre.org&sz=16" width="16" height="16"> [MITRE ATT&CK](https://attack.mitre.org/) - Comprehensive knowledge base of adversary tactics, techniques, and procedures (TTPs).
* [PhishTank](https://www.phishtank.com/) - Collaborative clearing house for phishing URL verification and data.
* <img src="https://www.google.com/s2/favicons?domain=www.recordedfuture.com&sz=16" width="16" height="16"> [Recorded Future](https://www.recordedfuture.com/) - AI-powered threat intelligence platform aggregating data from the open, deep, and dark web.
* <img src="https://www.google.com/s2/favicons?domain=thehive-project.org&sz=16" width="16" height="16"> [TheHive](https://thehive-project.org/) - Open-source security incident response platform designed for SOCs and CSIRTs.
* <img src="https://www.google.com/s2/favicons?domain=threatfox.abuse.ch&sz=16" width="16" height="16"> [ThreatFox](https://threatfox.abuse.ch/) - IOC sharing platform for malware-related indicators of compromise.

## [↑](#-table-of-contents) 🤝 Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) if you wish to add tools or resources. Feel free to help 🥰 us grow this list with great resources.

## [↑](#-table-of-contents) 🙏 Credits

This list was taken partially taken from [i-inteligence's](http://www.i-intelligence.eu) [OSINT Tools and Resources Handbook](http://www.i-intelligence.eu/open-source-intelligence-tools-and-resources-handbook/).

Thanks to our main contributors
[jivoi EK_](https://github.com/jivoi) & 
[spmedia](https://github.com/spmedia)

## [↑](#-table-of-contents) 🔍 General Search

*The main search engines used by users.*

* <img src="https://www.google.com/s2/favicons?domain=search.aol.com&sz=16" width="16" height="16"> [Aol](https://search.aol.com) - The web for America.
* <img src="https://www.google.com/s2/favicons?domain=www.ask.com&sz=16" width="16" height="16"> [Ask](https://www.ask.com) - Ask something and get a answer.
* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing](https://www.bing.com) - Microsoft´s search engine.
* <img src="https://www.google.com/s2/favicons?domain=search.brave.com&sz=16" width="16" height="16"> [Brave](https://search.brave.com) - a private, independent, and transparent search engine.
* <img src="https://www.google.com/s2/favicons?domain=www.goodsearch.com&sz=16" width="16" height="16"> [Goodsearch](https://www.goodsearch.com) - a search engine for shopping deals online.
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Search](https://www.google.com) - Most popular search engine.
* <img src="https://www.google.com/s2/favicons?domain=www.instya.com&sz=16" width="16" height="16"> [Instya](https://www.instya.com) -  You can searching shopping sites, dictionaries, answer sites, news, images, videos and much more.
* <img src="https://www.google.com/s2/favicons?domain=www.impersonal.me&sz=16" width="16" height="16"> [Impersonal.me](http://www.impersonal.me)
* [Lycos](https://www.lycos.com) - A search engine for pictures, videos, news and products.
* <img src="https://www.google.com/s2/favicons?domain=www.mojeek.com&sz=16" width="16" height="16"> [Mojeek](https://www.mojeek.com/) - A growing independent search engine which does not track you.
* <img src="https://www.google.com/s2/favicons?domain=www.perplexity.ai&sz=16" width="16" height="16"> [Perplexity](https://www.perplexity.ai) - AI-powered search engine with source citations.
* <img src="https://www.google.com/s2/favicons?domain=www.phind.com&sz=16" width="16" height="16"> [Phind](https://www.phind.com) - AI search engine optimized for developers and technical questions.
* <img src="https://www.google.com/s2/favicons?domain=www.search.com&sz=16" width="16" height="16"> [Search.com](https://www.search.com) - Search the Web by searching the best engines from one place.
* <img src="https://www.google.com/s2/favicons?domain=www.wolframalpha.com&sz=16" width="16" height="16"> [Wolfram Alpha](https://www.wolframalpha.com) - Wolfram Alpha is a computational knowledge engine (answer engine) developed by Wolfram Alpha. It will compute expert-level answers using Wolfram’s breakthrough
algorithms, knowledgebase and AI technology.
* <img src="https://www.google.com/s2/favicons?domain=www.yahoo.com&sz=16" width="16" height="16"> [Yahoo! Search](https://www.yahoo.com) -  The search engine that helps you find exactly what you're looking for.
* <img src="https://www.google.com/s2/favicons?domain=you.com&sz=16" width="16" height="16"> [YOU](https://you.com) - AI search engine.

## [↑](#-google-dorks-tools) 🤖 Google Dorks Tools

*Google Dorks Tools*

* <img src="https://www.google.com/s2/favicons?domain=dorkgenius.com&sz=16" width="16" height="16"> [DorkGenius](https://dorkgenius.com/) - DorkGenius is the ultimate tool for generating custom search queries for Google, Bing, and DuckDuckGo. - Our cutting-edge app uses the power of AI to help you create advanced search queries that can find exactly what you're looking for on the web.
* <img src="https://www.google.com/s2/favicons?domain=www.dorkgpt.com&sz=16" width="16" height="16"> [DorkGPT](https://www.dorkgpt.com/) - Generate Google Dorks with AI.
* <img src="https://www.google.com/s2/favicons?domain=www.exploit-db.com&sz=16" width="16" height="16"> [Google Hacking Database (GHDB)](https://www.exploit-db.com/google-hacking-database) - The GHDB is an index of search queries (we call them dorks) used to find publicly available information, intended for pentesters and security researchers.
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [SearchDorks](https://kriztalz.sh/search-dorks/) - Generate Search Engine (Google, FOFA, Shodan, Censys, ZoomEye) Dorks using AI.

## [↑](#-table-of-contents) 🌐 Main National Search Engines

*Localized search engines by country.*

* <img src="https://www.google.com/s2/favicons?domain=www.alleba.com&sz=16" width="16" height="16"> [Alleba (Philippines)](http://www.alleba.com) - Philippines search engine
* <img src="https://www.google.com/s2/favicons?domain=www.baidu.com&sz=16" width="16" height="16"> [Baidu (China)](http://www.baidu.com) - The major search engine used in China
* <img src="https://www.google.com/s2/favicons?domain=www.daum.net&sz=16" width="16" height="16"> [Daum (South Korea)](https://www.daum.net/)
* <img src="https://www.google.com/s2/favicons?domain=www.eniro.se&sz=16" width="16" height="16"> [Eniro (Sweden)](http://www.eniro.se)
* <img src="https://www.google.com/s2/favicons?domain=gerdoo.me&sz=16" width="16" height="16"> [Gerdoo (Iran)](http://gerdoo.me)
* [Goo (Japan)](http://www.goo.ne.jp)
* <img src="https://www.google.com/s2/favicons?domain=www.najdi.si&sz=16" width="16" height="16"> [Najdi (Slovenia)](http://www.najdi.si)
* <img src="https://www.google.com/s2/favicons?domain=www.naver.com&sz=16" width="16" height="16"> [Naver (South Korea)](http://www.naver.com)
* <img src="https://www.google.com/s2/favicons?domain=www.onet.pl&sz=16" width="16" height="16"> [Onet.pl (Poland)](http://www.onet.pl)
* <img src="https://www.google.com/s2/favicons?domain=www.orange.fr&sz=16" width="16" height="16"> [Orange (France)](http://www.orange.fr)
* <img src="https://www.google.com/s2/favicons?domain=www.parseek.com&sz=16" width="16" height="16"> [Parseek (Iran)](http://www.parseek.com)
* <img src="https://www.google.com/s2/favicons?domain=www.sapo.pt&sz=16" width="16" height="16"> [SAPO (Portugal)](http://www.sapo.pt)
* <img src="https://www.google.com/s2/favicons?domain=www.search.ch&sz=16" width="16" height="16"> [Search.ch (Switzerland)](http://www.search.ch)
* <img src="https://www.google.com/s2/favicons?domain=seznam.cz&sz=16" width="16" height="16"> [Seznam(Czech Republic)](https://seznam.cz)
* <img src="https://www.google.com/s2/favicons?domain=www.sogou.com&sz=16" width="16" height="16"> [SoGou (China)](http://www.sogou.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.walla.co.il&sz=16" width="16" height="16"> [Walla (Israel)](http://www.walla.co.il)
* <img src="https://www.google.com/s2/favicons?domain=www.yandex.com&sz=16" width="16" height="16"> [Yandex (Russia)](http://www.yandex.com)
* <img src="https://www.google.com/s2/favicons?domain=zarebin.ir&sz=16" width="16" height="16"> [Zarebin (Iran)](http://zarebin.ir)

## [↑](#-table-of-contents) 🔄 Meta Search

*Lesser known and used search engines.*

* <img src="https://www.google.com/s2/favicons?domain=all-io.net&sz=16" width="16" height="16"> [All-in-One](http://all-io.net)
* <img src="https://www.google.com/s2/favicons?domain=www.alltheinternet.com&sz=16" width="16" height="16"> [AllTheInternet](http://www.alltheinternet.com)
* <img src="https://www.google.com/s2/favicons?domain=www.etools.ch&sz=16" width="16" height="16"> [Etools](http://www.etools.ch)
* <img src="https://www.google.com/s2/favicons?domain=www.faganfinder.com&sz=16" width="16" height="16"> [FaganFinder](http://www.faganfinder.com/engines)
* <img src="https://www.google.com/s2/favicons?domain=www.goofram.com&sz=16" width="16" height="16"> [Goofram](http://www.goofram.com)
* <img src="https://www.google.com/s2/favicons?domain=www.izito.com&sz=16" width="16" height="16"> [iZito](http://www.izito.com)
* <img src="https://www.google.com/s2/favicons?domain=www.myallsearch.com&sz=16" width="16" height="16"> [Myallsearch](http://www.myallsearch.com)
* <img src="https://www.google.com/s2/favicons?domain=www.qwant.com&sz=16" width="16" height="16"> [Qwant](http://www.qwant.com) - French search engine that relies on Microsoft Bing.
* <img src="https://www.google.com/s2/favicons?domain=swisscows.com&sz=16" width="16" height="16"> [Swisscows](https://swisscows.com/)

## [↑](#-table-of-contents) 🔒 Privacy Focused Search Engines

*Search engines that focuses on anonymization,privacy.*
  
* <img src="https://www.google.com/s2/favicons?domain=duckduckgo.com&sz=16" width="16" height="16"> [DuckDuckGo](https://duckduckgo.com) - an Internet search engine that emphasizes protecting searchers' privacy.
* <img src="https://www.google.com/s2/favicons?domain=search.disconnect.me&sz=16" width="16" height="16"> [Disconnect Search](https://search.disconnect.me/) - Stop search engines from tracking your searches.
* <img src="https://www.google.com/s2/favicons?domain=gibiru.com&sz=16" width="16" height="16"> [Gibiru](https://gibiru.com/) - Gibiru provides “uncensored search results” without collecting personal data like logging users’ IP addresses or search queries.
* <img src="https://www.google.com/s2/favicons?domain=kagi.com&sz=16" width="16" height="16"> [Kagi Search](https://kagi.com/) - Liberate your search. Free of ads. Free of surveillance. Your time respected. You are the customer, never the product.
* <img src="https://www.google.com/s2/favicons?domain=www.mojeek.com&sz=16" width="16" height="16"> [Mojeek](https://www.mojeek.com/) - Mojeek is a growing independent search engine which does not track you.
* <img src="https://www.google.com/s2/favicons?domain=presearch.com&sz=16" width="16" height="16"> [Presearch](https://presearch.com/) - Presearch is a decentralized, community-driven search engine that protects your privacy and rewards you when you search.
* <img src="https://www.google.com/s2/favicons?domain=www.qwant.com&sz=16" width="16" height="16"> [Qwant](https://www.qwant.com/) - The search engine that respects your privacy.
* <img src="https://www.google.com/s2/favicons?domain=www.startpage.com&sz=16" width="16" height="16"> [Startpage](https://www.startpage.com/) - The world’s most private search engine.
* <img src="https://www.google.com/s2/favicons?domain=swisscows.com&sz=16" width="16" height="16"> [swisscows](https://swisscows.com/en) - Anonymous search engine, a family-friendly, privacy-focused search engine based in Switzerland.

## [↑](#-table-of-contents) 💧 Data Breach Search Engines

*Search engines that can be used to check if your data's been breached*

* <img src="https://www.google.com/s2/favicons?domain=credenshow.com&sz=16" width="16" height="16"> [CredenShow](https://credenshow.com/) - Identify your compromised credentials before others do.
* <img src="https://www.google.com/s2/favicons?domain=haveibeenransom.com&sz=16" width="16" height="16"> [HIB Ransomed](https://haveibeenransom.com/) - Because people have the right to know if their data has been leaked.
* <img src="https://www.google.com/s2/favicons?domain=heroic.com&sz=16" width="16" height="16"> [HEROIC.NOW](https://heroic.com/) - Has your data been leaked on the dark web? Scan your identities for FREE.
* <img src="https://www.google.com/s2/favicons?domain=iknowyour.dad&sz=16" width="16" height="16"> [IKnowYour.Dad](https://iknowyour.dad/) - Data Breach Search Engine.
* <img src="https://www.google.com/s2/favicons?domain=stealseek.io&sz=16" width="16" height="16"> [StealSeek](https://stealseek.io/) - Powerful search engine designed to help you find and analyze data breaches.
* <img src="https://www.google.com/s2/favicons?domain=venacus.com&sz=16" width="16" height="16"> [Venacus](https://venacus.com/) - Search for your data breaches and get notified when your data is compromised.

## [↑](#-table-of-contents) 🎯 Speciality Search Engines

*Search engines for specific information or topics.*

* <img src="https://www.google.com/s2/favicons?domain=www.2lingual.com&sz=16" width="16" height="16"> [2lingual Search](http://www.2lingual.com)
* [Abusech](https://hunting.abuse.ch) - Hunt across all abuse.ch platforms with one simple query
* <img src="https://www.google.com/s2/favicons?domain=www.abuseipdb.com&sz=16" width="16" height="16"> [Abuseipdb](https://www.abuseipdb.com/) - Repository of abuses reported by system administrators for IPs, Domains, and subnets
* <img src="https://www.google.com/s2/favicons?domain=bevigil.com&sz=16" width="16" height="16"> [BeVigil](https://bevigil.com/search) - Search for assets like Subdomains, URLs, Parameters in mobile applications
* <img src="https://www.google.com/s2/favicons?domain=bgp.tools&sz=16" width="16" height="16"> [BGP.tools](https://bgp.tools) - Modern BGP toolkit for network reconnaissance and analysis.
* <img src="https://www.google.com/s2/favicons?domain=bgp.he.net&sz=16" width="16" height="16"> [BGP.he.net](https://bgp.he.net) - Free BGP and network intelligence toolkit
* [Biznar](http://biznar.com)
* <img src="https://www.google.com/s2/favicons?domain=brightcloud.com&sz=16" width="16" height="16"> [BrightCloud](https://brightcloud.com/tools/url-ip-lookup.php) - Checks the reputation, category, and potential threats associated with a URL or IP address.
* <img src="https://www.google.com/s2/favicons?domain=browserleaks.com&sz=16" width="16" height="16"> [Browserleaks](https://browserleaks.com/) - BrowserLeaks tests your browser for privacy and fingerprinting leaks
* <img src="https://www.google.com/s2/favicons?domain=search.censys.io&sz=16" width="16" height="16"> [Censys](https://search.censys.io/) - Searcher that monitors and analyzes devices.
* <img src="https://www.google.com/s2/favicons?domain=www.certkit.io&sz=16" width="16" height="16"> [CertKit Certificate Search](https://www.certkit.io/tools/ct-logs/) - Fast search for public SSL/TLS certificate records.
* <img src="https://www.google.com/s2/favicons?domain=talosintelligence.com&sz=16" width="16" height="16"> [Cisco Talos Intelligence](https://talosintelligence.com/reputation_center) - IP and Domain Reputation Center for real-time threat detection
* <img src="https://www.google.com/s2/favicons?domain=citeseer.ist.psu.edu&sz=16" width="16" height="16"> [CiteSeerX](http://citeseer.ist.psu.edu)
* <img src="https://www.google.com/s2/favicons?domain=radar.cloudflare.com&sz=16" width="16" height="16"> [Cloudflare Radar](https://radar.cloudflare.com) - Internet traffic patterns, attacks, and technology trends.
* <img src="https://www.google.com/s2/favicons?domain=www.criminalip.io&sz=16" width="16" height="16"> [Criminal IP](https://www.criminalip.io/) - Cyber Threat Intelligence Search Engine and Attack Surface Management(ASM) platform
* [CRT Certificate Search](https://crt.sh) - Allows you to search for public SSL/TLS certificates recorded in Certificate Transparency logs
* <img src="https://www.google.com/s2/favicons?domain=en.fofa.info&sz=16" width="16" height="16"> [FOFA](https://en.fofa.info/) - Asset search and analysis tool.
* <img src="https://www.google.com/s2/favicons?domain=fullhunt.io&sz=16" width="16" height="16"> [FullHunt](https://fullhunt.io/) -FullHunt identifies and secures your External Attack Surface.
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Custom Search](http://www.google.com/cse)
* <img src="https://www.google.com/s2/favicons?domain=grayhatwarfare.com&sz=16" width="16" height="16"> [GrayhatWarfare](https://grayhatwarfare.com/) - Searches and indexes open Amazon S3 buckets, allowing users to find and explore potentially exposed data.
* <img src="https://www.google.com/s2/favicons?domain=viz.greynoise.io&sz=16" width="16" height="16"> [GreyNoise](https://viz.greynoise.io/) - Search Exposed Internet assets, Malicious IP's.
* <img src="https://www.google.com/s2/favicons?domain=www.harmari.com&sz=16" width="16" height="16"> [Harmari (Unified Listings Search)](https://www.harmari.com/search/unified)
* <img src="https://www.google.com/s2/favicons?domain=hunter.how&sz=16" width="16" height="16"> [Hunter Search Engine](https://hunter.how/) - Search Exposed Internet assets, open web directories and many more.
* <img src="https://www.google.com/s2/favicons?domain=intelx.io&sz=16" width="16" height="16"> [Intelligence X](https://intelx.io/tools) - Paid OSINT Tool Allowing users to search for information across various sources including the dark web and public data leaks.
* <img src="https://www.google.com/s2/favicons?domain=archive.org&sz=16" width="16" height="16"> [Internet Archive](https://archive.org/)
* <img src="https://www.google.com/s2/favicons?domain=www.islegitsite.com&sz=16" width="16" height="16"> [Islegitsite](https://www.islegitsite.com/) - Checks if a website is trustworthy by analyzing its reputation, domain, and security based on public sources.
* <img src="https://www.google.com/s2/favicons?domain=bazaar.abuse.ch&sz=16" width="16" height="16"> [MalwareBazaar](https://bazaar.abuse.ch/browse/) - Search and download confirmed malware samples by hash, family, tag, and other criteria.
* <img src="https://www.google.com/s2/favicons?domain=www.mmnt.ru&sz=16" width="16" height="16"> [Mamont](https://www.mmnt.ru/)
* <img src="https://www.google.com/s2/favicons?domain=millionshort.com&sz=16" width="16" height="16"> [Million Short](https://millionshort.com)
* <img src="https://www.google.com/s2/favicons?domain=app.netlas.io&sz=16" width="16" height="16"> [Netlas.io](https://app.netlas.io/)
* <img src="https://www.google.com/s2/favicons?domain=search.odin.io&sz=16" width="16" height="16"> [ODIN](https://search.odin.io/) - Used to search for Hosts, CVEs & Exposed Buckets/Files and shows a website is vulnerable or not. 10 Free Searches Per Day.
* <img src="https://www.google.com/s2/favicons?domain=aleph.occrp.org&sz=16" width="16" height="16"> [OCCRP Aleph](https://aleph.occrp.org/)
* [ONYPHE](https://search.onyphe.io/) - OSINT engine indexing exposed assets and services across the internet.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Search Abuseipdb](https://github.com/oseasfr/search-abuseipdb) - Tool to query IPs, ranges and ASN blocks in AbuseIPDB via API with CIDR notation.
* <img src="https://www.google.com/s2/favicons?domain=dashboard.shadowserver.org&sz=16" width="16" height="16"> [Shadowserver](https://dashboard.shadowserver.org/) - Dashboard with global statistics on cyber threats collected by the Shadowserver Foundation.
* <img src="https://www.google.com/s2/favicons?domain=www.shodan.io&sz=16" width="16" height="16"> [Shodan](https://www.shodan.io/) - Shodan is a search engine for the IOT(Internet of Things) that allows you to search variety of servers that are connected to the internet using various searching filters.
* [WIPO](https://www3.wipo.int/branddb/en/)
* <img src="https://www.google.com/s2/favicons?domain=worldwidescience.org&sz=16" width="16" height="16"> [WorldWideScience.org](http://worldwidescience.org)
* <img src="https://www.google.com/s2/favicons?domain=wpscan.com&sz=16" width="16" height="16"> [Wpscan](https://wpscan.com) - Scan your WordPress site and get an instant report on its security.
* <img src="https://www.google.com/s2/favicons?domain=yaraify.abuse.ch&sz=16" width="16" height="16"> [YARAif](https://yaraify.abuse.ch/scan/) - Collaborative YARA engine providing open threat intelligence through file pattern matching.
* [Zanran](http://zanran.com)
* <img src="https://www.google.com/s2/favicons?domain=www.zoomeye.ai&sz=16" width="16" height="16"> [ZoomEye](https://www.zoomeye.ai/) - ZoomEye is a cyberspace search engine for IPs, domains, internet asset discovery, and exposure analysis of servers, routers, and webcams.

## [↑](#-table-of-contents) 🕶️ Dark Web Search Engines
* [Ahmia](https://ahmia.fi)
* [Aleph Open Search](https://open-search.aleph-networks.eu)

## [↑](#-table-of-contents) 👁️ Visual Search and Clustering Search Engines

*Search engines that scrape multiple sites (Google, Yahoo, Bing, Goo, etc) at the same time and return results.*

* <img src="https://www.google.com/s2/favicons?domain=search.carrot2.org&sz=16" width="16" height="16"> [Carrot2](https://search.carrot2.org) - Organizes your search results into topics.
* <img src="https://www.google.com/s2/favicons?domain=www.zapmeta.com&sz=16" width="16" height="16"> [Zapmeta](http://www.zapmeta.com)

## [↑](#-table-of-contents) 🔗 Similar Sites Search

*Find websites that are similar. Good for business competition research.*

* <img src="https://www.google.com/s2/favicons?domain=www.similarsites.com&sz=16" width="16" height="16"> [SimilarSites](http://www.similarsites.com) - Discover websites that are similar to each other
* <img src="https://www.google.com/s2/favicons?domain=www.siteslike.com&sz=16" width="16" height="16"> [SitesLike](http://www.siteslike.com) - Find similar websites by category

## [↑](#-table-of-contents) 📄 Document and Slides Search

*Search for data located on PDFs, Word documents, presentation slides, and more.*

* <img src="https://www.google.com/s2/favicons?domain=www.documentcloud.org&sz=16" width="16" height="16"> [DocumentCloud](https://www.documentcloud.org) - Platform for analyzing, annotating, and publishing documents.
* <img src="https://www.google.com/s2/favicons?domain=epsteinexposed.com&sz=16" width="16" height="16"> [Epstein Exposed](https://epsteinexposed.com) - Comprehensive searchable database of 2M+ DOJ Epstein case documents, 1,700+ persons, flight logs, emails, and network graph visualization.
* [Find-pdf-doc](http://www.findpdfdoc.com)
* <img src="https://www.google.com/s2/favicons?domain=www.freefullpdf.com&sz=16" width="16" height="16"> [Free Full PDF](http://www.freefullpdf.com)
* <img src="https://www.google.com/s2/favicons?domain=offshoreleaks.icij.org&sz=16" width="16" height="16"> [Offshore Leak Database](https://offshoreleaks.icij.org)
* [RECAP Archive](https://www.courtlistener.com/recap/) - Public archive of PACER court documents.
* <img src="https://www.google.com/s2/favicons?domain=www.scribd.com&sz=16" width="16" height="16"> [Scribd](http://www.scribd.com)
* <img src="https://www.google.com/s2/favicons?domain=www.slideshare.net&sz=16" width="16" height="16"> [SlideShare](http://www.slideshare.net)

## [↑](#-threat-actor-search) 🎭 Threat Actor Search

*Search for Threat actors and their associated information.*

* <img src="https://www.google.com/s2/favicons?domain=docs.google.com&sz=16" width="16" height="16"> [APT Groups and Operations](https://docs.google.com/spreadsheets/u/0/d/1H9_xaxQHpWaa4O_Son4Gx0YOIzlcBWMsdvePFX68EKU/pubhtml?pli=1#) - Know about Threat Actors, sponsored countries, their tools, methods, etc.
* [APTWiki](https://apt.threatradar.net/) - Historical wiki with 214 actor entries.
* <img src="https://www.google.com/s2/favicons?domain=gti.bi.zone&sz=16" width="16" height="16"> [Bi.Zone](https://gti.bi.zone/) - 148 threat groups with detailed TTPs.
* <img src="https://www.google.com/s2/favicons?domain=breach-hq.com&sz=16" width="16" height="16"> [BreachHQ](https://breach-hq.com/threat-actors) - Provides a list of all known cyber threat actors also referred to as malicious actors, APT groups or hackers.
* [Cybergeist](https://cybergeist.io/threat-actor) - Cybergeist.io generates intelligence profiles about key threats and threat context that is actively being discussed and reported upon across the internet.
* <img src="https://www.google.com/s2/favicons?domain=darkwebinformer.com&sz=16" width="16" height="16"> [Dark Web Informer](https://darkwebinformer.com/threat-actor-database/) - Tracking 854 Threat Actors as of 29th of May 2025.
* <img src="https://www.google.com/s2/favicons?domain=apt.etda.or.th&sz=16" width="16" height="16"> [ETDA](https://apt.etda.or.th/cgi-bin/listgroups.cgi) - Search for Threat Actor groups and their tools.
* [FortiGuard Labs](https://www.fortiguard.com/threat-actor) - Powered by FortiGuard Labs, our Threat Actor Encyclopedia provides actionable insights, helping security teams prepare and streamline advanced threat hunting and response.
* [KNOWLEDGENOW](https://know.netenrich.com/content/track/threat-actor) - Trending Threats.
* <img src="https://www.google.com/s2/favicons?domain=lazarus.day&sz=16" width="16" height="16"> [lazarusholic](https://lazarus.day/actors/) - Total 203 threat actors.
* [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/actors) - Get List of threat actor groups.
* <img src="https://www.google.com/s2/favicons?domain=www.misp-galaxy.org&sz=16" width="16" height="16"> [MISP Galaxy](https://www.misp-galaxy.org/360net/) - Known or estimated adversary groups as identified by 360.net.
* <img src="https://www.google.com/s2/favicons?domain=openhunting.io&sz=16" width="16" height="16"> [OPENHUNTING.IO](https://openhunting.io/threat-library) - Threat Library Collecting Information.
* <img src="https://www.google.com/s2/favicons?domain=socradar.io&sz=16" width="16" height="16"> [SOCRadar LABS](https://socradar.io/labs/threat-actor/) - Know threat actor tactics, techniques, and past activities. Access detailed profiles and track their activities.Keep up with the latest threats and Tactics, Techniques, and Procedures (TTPs).
* <img src="https://www.google.com/s2/favicons?domain=cds.thalesgroup.com&sz=16" width="16" height="16"> [Thales](https://cds.thalesgroup.com/en/cyberthreat/attacks-page) - Find Threat actor groups in a graphical attack explorer.

## [↑](#-live-cyberthreat-maps) ⚡ Live Cyber Threat Maps

*Live Cyber Threat Maps helps to know attacks carried out in visualized format.*

* [Bitdefender Threat Map](https://threatmap.bitdefender.com/) - Cyberthreat Real Time Map by Bitdefender.
* [BunkerWeb Live Cyber Attack Threat Map](https://threatmap.bunkerweb.io/) - Live cyber attack blocked by BunkerWeb, the open source and next generation Web Application Firewall.
* <img src="https://www.google.com/s2/favicons?domain=threatmap.checkpoint.com&sz=16" width="16" height="16"> [Check Point Live Cyber Threat Map](https://threatmap.checkpoint.com/) - Explore the top cyber threats of 2025, including ransomware, infostealers, and cloud vulnerabilities.
* <img src="https://www.google.com/s2/favicons?domain=talosintelligence.com&sz=16" width="16" height="16"> [Cisco Talos Intelligence](https://talosintelligence.com/ebc_spam) -
* [Fortiguard Labs](https://fortiguard.fortinet.com/threat-map) - FortiGuard Outbreak Alerts provides key information about on-going cybersecurity attack with significant ramifications affecting numerous companies, organizations and industries.
* <img src="https://www.google.com/s2/favicons?domain=www.hcltech.com&sz=16" width="16" height="16"> [HCL Threat Map](https://www.hcltech.com/hcl-threat-map) - Cyber Threat Map by HCLTech.
* <img src="https://www.google.com/s2/favicons?domain=exchange.xforce.ibmcloud.com&sz=16" width="16" height="16"> [IBM X-Force Exchange Current Malicious Activity](https://exchange.xforce.ibmcloud.com/activity/map) -
* <img src="https://www.google.com/s2/favicons?domain=www.imperva.com&sz=16" width="16" height="16"> [Imperva Live Threat Map](https://www.imperva.com/cyber-threat-attack-map/) - A real-time global view of DDoS attacks, hacking attempts, and bot assaults mitigated by Imperva security services.
* <img src="https://www.google.com/s2/favicons?domain=cybermap.kaspersky.com&sz=16" width="16" height="16"> [Kaspersky Cyberthreat live Map](https://cybermap.kaspersky.com/) - Find out if you are under cyber-attack here.
* <img src="https://www.google.com/s2/favicons?domain=www.lionic.com&sz=16" width="16" height="16"> [LIONIC Cyber Threat Map](https://www.lionic.com/monitoring/) -
* <img src="https://www.google.com/s2/favicons?domain=horizon.netscout.com&sz=16" width="16" height="16"> [NETSCOUT Cyber Threat Map](https://horizon.netscout.com/) - Real-Time DDoS Attack Map
* <img src="https://www.google.com/s2/favicons?domain=livethreatmap.radware.com&sz=16" width="16" height="16"> [Radware Live Cyber Threat Map](https://livethreatmap.radware.com/) - Radware's Live Threat Map presents near real-time information about cyberattacks as they occur, based on our global threat deception network.
* <img src="https://www.google.com/s2/favicons?domain=securegateway.com&sz=16" width="16" height="16"> [Secure Gateway Live Cyber Threat Map](https://securegateway.com/map/v5/) -
* <img src="https://www.google.com/s2/favicons?domain=cds.thalesgroup.com&sz=16" width="16" height="16"> [Thale's Cyberthreat Map](https://cds.thalesgroup.com/en/cyberthreat/hitmap) - Discover cybersecurity trends with Thales' Cyberthreat map. Explore targeted areas, frequent attacks, affected sectors, and prevalent malware.
* <img src="https://www.google.com/s2/favicons?domain=threatseye.io&sz=16" width="16" height="16"> [ThreatsEye | Live Cyber Threat Map](https://threatseye.io/threats-map) - Real-time visualization of global cyber attacks and threats. Monitor live cyber security incidents, attack origins, targets, and threat categories worldwide.
* <img src="https://www.google.com/s2/favicons?domain=threatlabz.zscaler.com&sz=16" width="16" height="16"> [Zscaler Global Threat Map Dashboard](https://threatlabz.zscaler.com/cloud-insights/threat-map-dashboard) - Illustrates those we've seen in the past 24 hours, consisting of threats detected by our antivirus engines, malware and advanced persistent threats.


## [↑](#-table-of-contents) 📁 File Search

*Search for all kind of files.*

* <img src="https://www.google.com/s2/favicons?domain=www.eyedex.org&sz=16" width="16" height="16"> [eyedex](https://www.eyedex.org/) - Open directory search engine.
* <img src="https://www.google.com/s2/favicons?domain=www.dedigger.com&sz=16" width="16" height="16"> [de digger](https://www.dedigger.com/) - is a website that allows you to find any types of files that are publicly available in a Google Drive.
* [FileListing](https://filelisting.com/)
* [FilePursuit](https://filepursuit.com/)
* <img src="https://www.google.com/s2/favicons?domain=filesec.io&sz=16" width="16" height="16"> [Filesec.io](https://filesec.io/) - Central resource cataloging malicious file extensions, their risks, OS and mitigations.
* [Find Security Contacts] https://findsecuritycontacts.com - Public index listing security contacts (emails, policies, etc.) extracted from domains security.txt files.
* <img src="https://www.google.com/s2/favicons?domain=meawfy.com&sz=16" width="16" height="16"> [Meawfy](https://meawfy.com/) - Advanced Mega.nz File Search Engine. Search and discover files from Mega.nz with our intelligent crawler technology. Access over 9 million indexed files instantly.
* <img src="https://www.google.com/s2/favicons?domain=www.searchftps.net&sz=16" width="16" height="16"> [NAPALM FTP Indexer](https://www.searchftps.net/)
* <img src="https://www.google.com/s2/favicons?domain=odcrawler.xyz&sz=16" width="16" height="16"> [ODCrawler](https://odcrawler.xyz/) - A search engine for open directories. Find millions of publicly available files!
* <img src="https://www.google.com/s2/favicons?domain=searchfiles.de&sz=16" width="16" height="16"> [SearchFiles.de](https://searchfiles.de/)

## [↑](#-table-of-contents) 📋 Pastebins

*Find information that has been uploaded to Pastebin & alternative pastebin-type sites*

* <img src="https://www.google.com/s2/favicons?domain=0bin.net&sz=16" width="16" height="16"> [0bin](https://0bin.net)
* [BeanPaste](https://beanpaste.fun/) - A tiny way to share text.
* <img src="https://www.google.com/s2/favicons?domain=bpa.st&sz=16" width="16" height="16"> [bpaste](https://bpa.st/) - Welcome to bpaste, this site is a pastebin. It allows you to share code with others.
* <img src="https://www.google.com/s2/favicons?domain=paste.centos.org&sz=16" width="16" height="16"> [CentOS Pastebin Service](https://paste.centos.org/) - Stikked is an Open-Source PHP Pastebin, with the aim of keeping a simple and easy to use user interface.
* <img src="https://www.google.com/s2/favicons?domain=Cl1p.net&sz=16" width="16" height="16"> [cl1p](https://Cl1p.net) - The Internet Clipboard.
* <img src="https://www.google.com/s2/favicons?domain=commie.io&sz=16" width="16" height="16"> [commie](https://commie.io/) - commie is a pastebin script with line commenting support.
* <img src="https://www.google.com/s2/favicons?domain=ctxt.io&sz=16" width="16" height="16"> [Context](https://ctxt.io/) - Share whatever you see with others in seconds.
* <img src="https://www.google.com/s2/favicons?domain=Controlc.com&sz=16" width="16" height="16"> [ControlC Pastebin](https://Controlc.com) - The easiest way to host your text.
* <img src="https://www.google.com/s2/favicons?domain=cryptobin.co&sz=16" width="16" height="16"> [Cryptobin](https://cryptobin.co/) - The Ultimate Secure Pastebin
* <img src="https://www.google.com/s2/favicons?domain=cutapaste.net&sz=16" width="16" height="16"> [Cutapaste](https://cutapaste.net/) - Short Code and Share.
* <img src="https://www.google.com/s2/favicons?domain=defuse.ca&sz=16" width="16" height="16"> [Defuse](https://defuse.ca/pastebin.htm) - Encrypted Pastebin - Keep your data private and secure!
* <img src="https://www.google.com/s2/favicons?domain=doxbin.net&sz=16" width="16" height="16"> [doxbin](https://doxbin.net/) - A dox style pastebin ran by hackers.
* [dpaste2](https://Dpaste.org)
* <img src="https://www.google.com/s2/favicons?domain=Dpaste.com&sz=16" width="16" height="16"> [dpaste](https://Dpaste.com)
* <img src="https://www.google.com/s2/favicons?domain=pastebin.fi&sz=16" width="16" height="16"> [Etusivu](https://pastebin.fi/) - It's an open source clone of pastebin.com. Default Language is Finnish.
* <img src="https://www.google.com/s2/favicons?domain=friendpaste.com&sz=16" width="16" height="16"> [Friendpaste](https://friendpaste.com/) - Paste stuff to your friends.
* <img src="https://www.google.com/s2/favicons?domain=gist.github.com&sz=16" width="16" height="16"> [GitHub gist](https://gist.github.com)
* <img src="https://www.google.com/s2/favicons?domain=hashb.in&sz=16" width="16" height="16"> [HashBin](https://hashb.in/#Q===) - HashBin is a paste bin that never sees the contents of its pastes.
* <img src="https://www.google.com/s2/favicons?domain=www.toptal.com&sz=16" width="16" height="16"> [hastebin](https://www.toptal.com/developers/hastebin/)
* <img src="https://www.google.com/s2/favicons?domain=Ideone.com&sz=16" width="16" height="16"> [ideone](https://Ideone.com)
* <img src="https://www.google.com/s2/favicons?domain=Ivpaste.com&sz=16" width="16" height="16"> [ivpaste](https://Ivpaste.com)
* <img src="https://www.google.com/s2/favicons?domain=Jsbin.com&sz=16" width="16" height="16"> [jsbin](https://Jsbin.com)
* <img src="https://www.google.com/s2/favicons?domain=Justpaste.it&sz=16" width="16" height="16"> [justpaste](https://Justpaste.it)
* <img src="https://www.google.com/s2/favicons?domain=katb.in&sz=16" width="16" height="16"> [Katbin](https://katb.in) - Small, lightweight pastebin.
* [Linkode(alpha)](https://linkode.org/) - Linkode is the useful pastebin!
* <img src="https://www.google.com/s2/favicons?domain=logpasta.com&sz=16" width="16" height="16"> [Logpasta](https://logpasta.com/) - Simple, secure log paste service. Command line mode based.
* <img src="https://www.google.com/s2/favicons?domain=lesma.eu&sz=16" width="16" height="16"> [lesma.eu](https://lesma.eu/) - Simple paste app friendly with browser and command line.
* <img src="https://www.google.com/s2/favicons?domain=nachricht.co&sz=16" width="16" height="16"> [Nachricht](https://nachricht.co/) - With Nachricht.co you can send self-destructive and encrypted one-way messages over the Internet. You don't even need to miss out the messenger or social network of your choice. We are an independent, secure and fully free service!
* [NoPaste](https://nopaste.boris.sh/) - NoPaste is an open-source website similar to Pastebin where you can store any piece of code, and generate links for easy sharing.
* <img src="https://www.google.com/s2/favicons?domain=nopaste.net&sz=16" width="16" height="16"> [nopaste.net](https://nopaste.net/) - nopaste.net is a temporary file host, nopaste and clipboard across machines. You can upload files or text and share the link with others.
* <img src="https://www.google.com/s2/favicons?domain=notes.io&sz=16" width="16" height="16"> [Notes](https://notes.io/) - fast.easy.short.
* [nekobin](https://nekobin.com/) - Paste code, save and share the link!
* <img src="https://www.google.com/s2/favicons?domain=paste1.com&sz=16" width="16" height="16"> [New Paste](https://paste1.com/) - I wanna paste because typing is so boring!
* <img src="https://www.google.com/s2/favicons?domain=n0paste.eu&sz=16" width="16" height="16"> [n0paste](https://n0paste.eu/) - Paste and share your code online.
* [OTS- One Time Secrets](https://ots.hackliberty.org/) - An encrypted pastebin site. No login needed!
* <img src="https://www.google.com/s2/favicons?domain=paaster.io&sz=16" width="16" height="16"> [paaster](https://paaster.io/) - Paaster is a secure and user-friendly pastebin application that prioritizes privacy and simplicity. With end-to-end encryption and paste history, Paaster ensures that your pasted code remains confidential and accessible.
* <img src="https://www.google.com/s2/favicons?domain=pastbin.net&sz=16" width="16" height="16"> [PastBin.net](https://pastbin.net/) - Similar to Pastebin website where you can store code/text online for a set period of time and share to anyone anywhere. Search Option Available.
* <img src="https://www.google.com/s2/favicons?domain=pastebin.pl&sz=16" width="16" height="16"> [Pastebin](https://pastebin.pl/) - Store code/text online for a set period of time and share to anybody on earth.
* [Pastebin.cz](https://www.pastebin.cz/en/) - A simple Pastebin.
* [Paste.Cash](https://www.paste.cash/) - Paste.CASH Is a privacy respected and encrypted pastebin hosted by Cash Hosting. Every paste are encrypted using 256 bits AES.
* <img src="https://www.google.com/s2/favicons?domain=paste.centos.org&sz=16" width="16" height="16"> [paste.centos](https://paste.centos.org)
* <img src="https://www.google.com/s2/favicons?domain=Paste.debian.net&sz=16" width="16" height="16"> [paste.debian](https://Paste.debian.net)
* [paste.in.ua](https://paste.in.ua/) - Simple pastebin.
* <img src="https://www.google.com/s2/favicons?domain=Paste.kde.org&sz=16" width="16" height="16"> [paste.kde](https://Paste.kde.org)
* [Paste.Monster](https://paste.monster/) - Share your thoughts online. API Available.
* [paste.ubuntu](https://paste.ubuntu.com)
* <img src="https://www.google.com/s2/favicons?domain=pastequest.com&sz=16" width="16" height="16"> [Paste.Quest](https://pastequest.com/) - Copy and Paste text online to share with anyone anywhere. Use the password option to add a password to the pasted information.
* <img src="https://www.google.com/s2/favicons?domain=www.pastery.net&sz=16" width="16" height="16"> [Pastery](https://www.pastery.net/) - The sweetest pastebin in the world!
* <img src="https://www.google.com/s2/favicons?domain=pastesite.net&sz=16" width="16" height="16"> [PasteSite.Net](https://pastesite.net/) - The new generation pastebin.
* <img src="https://www.google.com/s2/favicons?domain=paste.sh&sz=16" width="16" height="16"> [paste.sh](https://paste.sh/) - This is an encrypted paste site. Simply type or paste code here and share the URL. Saving is Automatic.
* <img src="https://www.google.com/s2/favicons?domain=www.pasteshr.com&sz=16" width="16" height="16"> [PasteShr](https://www.pasteshr.com/) - Store any text online for easy sharing. Search option available!
* <img src="https://www.google.com/s2/favicons?domain=tor.link&sz=16" width="16" height="16"> [Pastebin - Tor Link](https://tor.link/paste/new) - Paste text to store or share with others.
* <img src="https://www.google.com/s2/favicons?domain=rentry.co&sz=16" width="16" height="16"> [Rentry](https://rentry.co/) - Rentry.co is a markdown paste service service with preview, custom urls and editing. Fast, simple and free.
* <img src="https://www.google.com/s2/favicons?domain=safenote.co&sz=16" width="16" height="16"> [SafeNote](https://safenote.co/) - SafeNote is a free web-based service that allows you to share a note or a file with confidentiality. There is no way to spying on you even to a hacker.
* <img src="https://www.google.com/s2/favicons?domain=scrt.link&sz=16" width="16" height="16"> [scrt.link](https://scrt.link/) - Share a Secret with a link that only works one time and then self-destructs.
* <img src="https://www.google.com/s2/favicons?domain=snippet.host&sz=16" width="16" height="16"> [snippet.host](https://snippet.host/) - Minimal text and code snippet hosting.
* [Spacebin](https://spaceb.in/) - Spacebin is a modern Pastebin server implemented in Go and is capable of serving notes, novels, code, or any other form of text.
* <img src="https://www.google.com/s2/favicons?domain=textbin.net&sz=16" width="16" height="16"> [TextBin](https://textbin.net/) - Secure pastebin where you can paste and store any type of text or code snippets online and share it with your friends.
* <img src="https://www.google.com/s2/favicons?domain=textbin.online&sz=16" width="16" height="16"> [Textbin-Code](https://textbin.online/) - SECURE YOUR CODE!
* [TutPaste](https://tutpaste.com/) - Welcome to our fast and free online paste tool. Paste and share your text or code snippets with anyone, anywhere, no registration required.
* <img src="https://www.google.com/s2/favicons?domain=vaultb.in&sz=16" width="16" height="16"> [vaultbin](https://vaultb.in/) - Vaultbin is a blazingly fast and secure alternative to Pastebin and Hastebin.
* <img src="https://www.google.com/s2/favicons?domain=www.verybin.com&sz=16" width="16" height="16"> [Verybin](https://www.verybin.com/) - Anonymous and encrypted pastebin. Data is encrypted/decrypted in the browser using 256 bits AES and no IP address logged.
* <img src="https://www.google.com/s2/favicons?domain=write.as&sz=16" width="16" height="16"> [Write.as](https://write.as/) - Type words, put them on the internet.
* [ZBin](https://zbin.dev/) - Private & Secure Pastebin.
* <img src="https://www.google.com/s2/favicons?domain=sebsauvage.net&sz=16" width="16" height="16"> [ZeroBin](https://sebsauvage.net/paste/) - ZeroBin is a minimalist, opensource online pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256 bits AES.


## [↑](#-table-of-contents) 💻 Code Search

*Search by website source code*

* <img src="https://www.google.com/s2/favicons?domain=analyzeid.com&sz=16" width="16" height="16"> [AnalyzeID](https://analyzeid.com/) - Find Other Websites Owned By The Same Person
* <img src="https://www.google.com/s2/favicons?domain=codefinder.dev&sz=16" width="16" height="16"> [Code Finder](https://codefinder.dev/) - The ultimate search engine for finding GitHub repositories
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [GitHub Code Search](https://github.com/search?type=code) - GitHub's enhanced code search with advanced filtering.
* <img src="https://www.google.com/s2/favicons?domain=grep.app&sz=16" width="16" height="16"> [grep.app](https://grep.app/) - Searches code from the entire github public repositories for a given specific string or using regular expression.
* <img src="https://www.google.com/s2/favicons?domain=nerdydata.com&sz=16" width="16" height="16"> [NerdyData](https://nerdydata.com) - Search engine for source code.
* <img src="https://www.google.com/s2/favicons?domain=publicwww.com&sz=16" width="16" height="16"> [PublicWWW](https://publicwww.com/)
* <img src="https://www.google.com/s2/favicons?domain=codefinder.org&sz=16" width="16" height="16"> [Reposearch](http://codefinder.org/)
* [SearchCode](https://searchcode.com) - Help find real world examples of functions, API's and libraries across 10+ sources.
* <img src="https://www.google.com/s2/favicons?domain=www.sourcebot.dev&sz=16" width="16" height="16"> [Sourcebot](https://www.sourcebot.dev/) - Index thousands of repos on your machine and search through them in a fast, powerful, and modern web interface.
* <img src="https://www.google.com/s2/favicons?domain=sourcegraph.com&sz=16" width="16" height="16"> [SourceGraph](https://sourcegraph.com/search) - Search code from millions of open source repositories.

## [↑](#-table-of-contents) 📱 Major Social Networks

* <img src="https://www.google.com/s2/favicons?domain=bsky.app&sz=16" width="16" height="16"> [Bluesky](https://bsky.app) - Decentralized social network built on the AT Protocol.
* <img src="https://www.google.com/s2/favicons?domain=www.draugiem.lv&sz=16" width="16" height="16"> [Draugiem (Latvia)](https://www.draugiem.lv)
* <img src="https://www.google.com/s2/favicons?domain=www.facebook.com&sz=16" width="16" height="16"> [Facebook](http://www.facebook.com)
* <img src="https://www.google.com/s2/favicons?domain=www.instagram.com&sz=16" width="16" height="16"> [Instagram](https://www.instagram.com)
* <img src="https://www.google.com/s2/favicons?domain=www.linkedin.com&sz=16" width="16" height="16"> [Linkedin](https://www.linkedin.com)
* <img src="https://www.google.com/s2/favicons?domain=mixi.jp&sz=16" width="16" height="16"> [Mixi (Japan)](https://mixi.jp)
* <img src="https://www.google.com/s2/favicons?domain=ok.ru&sz=16" width="16" height="16"> [Odnoklassniki (Russia)](http://ok.ru)
* <img src="https://www.google.com/s2/favicons?domain=www.pinterest.com&sz=16" width="16" height="16"> [Pinterest](http://www.pinterest.com) - is an image sharing social media service used to easly discover, share and save ideas using visual representation.
* <img src="https://www.google.com/s2/favicons?domain=qzone.qq.com&sz=16" width="16" height="16"> [Qzone (China)](http://qzone.qq.com)
* <img src="https://www.google.com/s2/favicons?domain=www.reddit.com&sz=16" width="16" height="16"> [Reddit](https://www.reddit.com)
* <img src="https://www.google.com/s2/favicons?domain=www.taringa.net&sz=16" width="16" height="16"> [Taringa (Latin America)](http://www.taringa.net)
* <img src="https://www.google.com/s2/favicons?domain=www.threads.net&sz=16" width="16" height="16"> [Threads](https://www.threads.net) - Text-based conversation app from Meta.
* <img src="https://www.google.com/s2/favicons?domain=www.gotinder.com&sz=16" width="16" height="16"> [Tinder](https://www.gotinder.com)
* <img src="https://www.google.com/s2/favicons?domain=www.tumblr.com&sz=16" width="16" height="16"> [Tumblr](https://www.tumblr.com)
* <img src="https://www.google.com/s2/favicons?domain=twitter.com&sz=16" width="16" height="16"> [Twitter](https://twitter.com)
* <img src="https://www.google.com/s2/favicons?domain=weibo.com&sz=16" width="16" height="16"> [Weibo (China)](http://weibo.com)
* <img src="https://www.google.com/s2/favicons?domain=vk.com&sz=16" width="16" height="16"> [VKontakte](https://vk.com)
* <img src="https://www.google.com/s2/favicons?domain=www.xing.com&sz=16" width="16" height="16"> [Xing](https://www.xing.com)

## [↑](#-table-of-contents) ⚡ Real-Time Search, Social Media Search, and General Social Media Tools

* <img src="https://www.google.com/s2/favicons?domain=www.audiense.com&sz=16" width="16" height="16"> [Audiense](https://www.audiense.com) - Tool to identify relevant audience, discover actionable insights and inform strategies to grow your business.
* [Bottlenose](http://bottlenose.com)
* <img src="https://www.google.com/s2/favicons?domain=www.brandwatch.com&sz=16" width="16" height="16"> [Brandwatch](https://www.brandwatch.com)
* <img src="https://www.google.com/s2/favicons?domain=buffer.com&sz=16" width="16" height="16"> [Buffer](https://buffer.com)
* <img src="https://www.google.com/s2/favicons?domain=buzzsumo.com&sz=16" width="16" height="16"> [Buzz sumo](http://buzzsumo.com) - "Use our content insights to generate ideas, create high-performing content, monitor your performance and identify influencers."
* <img src="https://www.google.com/s2/favicons?domain=castrickclues.com&sz=16" width="16" height="16"> [Castrick](https://castrickclues.com) - Find social media accounts with email, username and phone number
* <img src="https://www.google.com/s2/favicons?domain=epieos.com&sz=16" width="16" height="16"> [Epieos](https://epieos.com) - Search for social accounts with e-mail and phone
* <img src="https://www.google.com/s2/favicons?domain=www.geocreepy.com&sz=16" width="16" height="16"> [Geocreepy](http://www.geocreepy.com)
* <img src="https://www.google.com/s2/favicons?domain=hootsuite.com&sz=16" width="16" height="16"> [Hootsuite](http://hootsuite.com)
* <img src="https://www.google.com/s2/favicons?domain=www.idcrawl.com&sz=16" width="16" height="16"> [IDCrawl](https://www.idcrawl.com/) - Search for a name in popular social networks.
* <img src="https://www.google.com/s2/favicons?domain=klear.com&sz=16" width="16" height="16"> [Klear](http://klear.com)
* [Kribrum](https://kribrum.io/)
* <img src="https://www.google.com/s2/favicons?domain=go.mail.ru&sz=16" width="16" height="16"> [Mail.Ru Social Network Search](https://go.mail.ru/search_social)
* <img src="https://www.google.com/s2/favicons?domain=mustbepresent.com&sz=16" width="16" height="16"> [MustBePresent](http://mustbepresent.com)
* <img src="https://www.google.com/s2/favicons?domain=www.netvibes.com&sz=16" width="16" height="16"> [Netvibes](http://www.netvibes.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Oblivion](https://github.com/loseys/Oblivion)
* [OpinionCrawl](http://www.opinioncrawl.com)
* <img src="https://www.google.com/s2/favicons?domain=predictasearch.com&sz=16" width="16" height="16"> [Predicta Search](https://predictasearch.com) - Search for social accounts with e-mail and phone
* <img src="https://www.google.com/s2/favicons?domain=www.rivaliq.com&sz=16" width="16" height="16"> [Rival IQ](https://www.rivaliq.com)
* [Social DownORNot](http://social.downornot.com)
* <img src="https://www.google.com/s2/favicons?domain=www.social-searcher.com&sz=16" width="16" height="16"> [Social Searcher](http://www.social-searcher.com)
* <img src="https://www.google.com/s2/favicons?domain=www.socialbakers.com&sz=16" width="16" height="16"> [SocialBakers](http://www.socialbakers.com)
* <img src="https://www.google.com/s2/favicons?domain=socialblade.com&sz=16" width="16" height="16"> [SocialBlade](http://socialblade.com)
* <img src="https://www.google.com/s2/favicons?domain=tagboard.com&sz=16" width="16" height="16"> [Tagboard](https://tagboard.com)
* <img src="https://www.google.com/s2/favicons?domain=www.uvrx.com&sz=16" width="16" height="16"> [UVRX](http://www.uvrx.com/social.html)
* [WATools](https://watools.io/)

## 🛠️ Social Media Tools

### [↑](#-table-of-contents) 🐦 Twitter

* <img src="https://www.google.com/s2/favicons?domain=www.exportdata.io&sz=16" width="16" height="16"> [ExportData](https://www.exportdata.io/) - Data export tool for historical tweets, followers & followings and historical trends.
* <img src="https://www.google.com/s2/favicons?domain=foller.me&sz=16" width="16" height="16"> [Foller.me](http://foller.me)
* [MyTweetAlerts](https://www.mytweetalerts.com/) - A tool to create custom email alerts based on Twitter search.
* <img src="https://www.google.com/s2/favicons?domain=onemilliontweetmap.com&sz=16" width="16" height="16"> [OneMillionTweetMap](http://onemilliontweetmap.com)
* <img src="https://www.google.com/s2/favicons?domain=ritetag.com&sz=16" width="16" height="16"> [RiteTag](https://ritetag.com)
* <img src="https://www.google.com/s2/favicons?domain=www.twittersentiment.appspot.com&sz=16" width="16" height="16"> [Sentiment140](http://www.twittersentiment.appspot.com)
* <img src="https://www.google.com/s2/favicons?domain=tagdef.com&sz=16" width="16" height="16"> [Tagdef](https://tagdef.com)
* <img src="https://www.google.com/s2/favicons?domain=trends24.in&sz=16" width="16" height="16"> [Trends24](http://trends24.in)
* <img src="https://www.google.com/s2/favicons?domain=twchat.com&sz=16" width="16" height="16"> [TwChat](http://twchat.com)
* <img src="https://www.google.com/s2/favicons?domain=mapd.csail.mit.edu&sz=16" width="16" height="16"> [TweetMap](http://mapd.csail.mit.edu/tweetmap)
* <img src="https://www.google.com/s2/favicons?domain=worldmap.harvard.edu&sz=16" width="16" height="16"> [TweetMap](http://worldmap.harvard.edu/tweetmap)
* <img src="https://www.google.com/s2/favicons?domain=twitter.com&sz=16" width="16" height="16"> [Twitter Advanced Search](https://twitter.com/search-advanced?lang=en)
* <img src="https://www.google.com/s2/favicons?domain=www.twitteraudit.com&sz=16" width="16" height="16"> [Twitter Audit](https://www.twitteraudit.com)
* <img src="https://www.google.com/s2/favicons?domain=tweetreports.com&sz=16" width="16" height="16"> [Twitter Chat Schedule](http://tweetreports.com/twitter-chat-schedule)
* [Twitter Search](http://search.twitter.com)

### [↑](#-table-of-contents) 👤 Facebook

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Facebook Friend List Scraper](https://github.com/narkopolo/fb_friend_list_scraper) - Tool for scraping large Facebook friend lists without being rate-limited.
* <img src="https://www.google.com/s2/favicons?domain=search.fb.com&sz=16" width="16" height="16"> [Facebook Search](http://search.fb.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.fanpagekarma.com&sz=16" width="16" height="16"> [Fanpage Karma](http://www.fanpagekarma.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Fb-sleep-stats](https://github.com/sqren/fb-sleep-stats) - Use Facebook to track your friends’ sleeping habits.
* <img src="https://www.google.com/s2/favicons?domain=randomtools.io&sz=16" width="16" height="16"> [Find my Facebook ID](https://randomtools.io) - To find your Facebook personal numeric ID for facebook graph API operations, fb:admins, social plugins.
* <img src="https://www.google.com/s2/favicons?domain=haveibeenzuckered.com&sz=16" width="16" height="16"> [haveibeenzuckered](https://haveibeenzuckered.com/) - A large dataset containing 533 million Facebook accounts was made available for download. The data was obtained by exploiting a vulnerability that was, according to Facebook, corrected in August 2019. Check if a telephone number is present within the Facebook data breach.
* <img src="https://www.google.com/s2/favicons?domain=lookup-id.com&sz=16" width="16" height="16"> [Lookup-ID.com](https://lookup-id.com) - Looking for your Facebook profile ID / Group ID / Page ID.
* <img src="https://www.google.com/s2/favicons?domain=searchisback.com&sz=16" width="16" height="16"> [SearchIsBack](https://searchisback.com)
* <img src="https://www.google.com/s2/favicons?domain=www.wolframalpha.com&sz=16" width="16" height="16"> [Wolfram Alpha Facebook Report](http://www.wolframalpha.com/input/?i=facebook+report)

### [↑](#-table-of-contents) 📸 Instagram

* <img src="https://www.google.com/s2/favicons?domain=www.dolphinradar.com&sz=16" width="16" height="16"> [Dolphin Radar](https://www.dolphinradar.com/web-viewer-for-instagram) - An Instagram Post Viewer lets you view posts, stories, and profiles from public accounts with ease. Free viewer limit: 1.
* <img src="https://www.google.com/s2/favicons?domain=iconosquare.com&sz=16" width="16" height="16"> [Iconosquare](http://iconosquare.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [instagram_monitor](https://github.com/misiektoja/instagram_monitor) - Tool for real-time tracking of Instagram users' activities and profile changes with support for email alerts, CSV logging, showing media in the terminal, anonymous story downloads and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [InstagramPrivSniffer](https://github.com/obitouka/InstagramPrivSniffer) - Views Instagram PRIVATE ACCOUNT'S media without login 😱.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Osintgram](https://github.com/Datalux/Osintgram) - Osintgram offers an interactive shell to perform analysis on Instagram account of any users by its nickname.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Osintgraph](https://github.com/XD-MHLOO/Osintgraph) - Tool that maps your target’s Instagram data and relationships in Neo4j for social network analysis.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Toutatis](https://github.com/megadose/toutatis) - a tool that allows you to extract information from instagrams accounts such as s, phone numbers and more

### [↑](#-table-of-contents) 📌 Pinterest

* <img src="https://www.google.com/s2/favicons?domain=pingroupie.com&sz=16" width="16" height="16"> [Pingroupie](http://pingroupie.com)
* <img src="https://www.google.com/s2/favicons?domain=chromewebstore.google.com&sz=16" width="16" height="16"> [Pinterest Pin Stats](https://chromewebstore.google.com/detail/pinterest-pin-stats-sort/mcmkeopcpbfgjlakblglpcccpodbjkel) - Display hidden Pinterest stats for each pin.

### [↑](#-table-of-contents) 🔴 Reddit

*Tools to help discover more about a reddit user or subreddit.*

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Arctic Shift](https://github.com/ArthurHeitmann/arctic_shift) - A tool for accessing and interacting with large dumps of Reddit data, offering an API and web interface for research and moderation purposes.
* <img src="https://www.google.com/s2/favicons?domain=imgur.com&sz=16" width="16" height="16"> [Imgur](http://imgur.com/search?q=) - The most popular image hosting website used by redditors.
* [Mostly Harmless](http://kerrick.github.io/Mostly-Harmless/#features) - Mostly Harmless looks up the page you are currently viewing to see if it has been submitted to reddit.
* [Pushshift API](https://pushshift.io/) - A powerful API that provides access to historical Reddit data, including posts, comments, and metadata for analysis and research—more information [here](https://www.reddit.com/r/pushshift/).
* <img src="https://www.google.com/s2/favicons?domain=pullpush.io&sz=16" width="16" height="16"> [Pullpush](https://pullpush.io/) - PullPush is a service for the indexing and retrieval of content that Reddit users have submitted to Reddit. Helpful for finding deleted/removed posts & comments.
* <img src="https://www.google.com/s2/favicons?domain=the-eye.eu&sz=16" width="16" height="16"> [REDARCS](https://the-eye.eu/redarcs/) - Reddit archives 2005-2023.
* [Reddit Archive](http://www.redditarchive.com) - Historical archives of reddit posts.
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [Reddit Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb) - Enhances your reddit experience.
* [Reddit User Analyser](https://atomiks.github.io/reddit-user-analyser/) - reddit user account analyzer.
* <img src="https://www.google.com/s2/favicons?domain=redditmetis.com&sz=16" width="16" height="16"> [RedditMetis](https://redditmetis.com/) - RedditMetis is a Reddit user analysis tool to see the summary and statistics for a Reddit account, including top posts and user activity etc.
* [Subreddits](http://subreddits.org) - Discover new subreddits.
* <img src="https://www.google.com/s2/favicons?domain=redditcommentsearch.com&sz=16" width="16" height="16"> [Reddit Comment Search](https://redditcommentsearch.com/) - Analyze a reddit users by comment history.
* <img src="https://www.google.com/s2/favicons?domain=universalscammerlist.com&sz=16" width="16" height="16"> [Universal Scammer List](https://universalscammerlist.com/) - This acts as the website-portion for the subreddit /r/universalscammerlist. That subreddit, in conjuction with this website and a reddit bot, manages a list of malicious reddit accounts and minimizes the damage they can deal. This list is referred to as the "USL" for short.
* <img src="https://www.google.com/s2/favicons?domain=randomtools.io&sz=16" width="16" height="16"> [Reddit Comment Lookup](https://randomtools.io/reddit-comment-search/) - Search for reddit comments by reddit username.


### [↑](#-table-of-contents) 🇷🇺 VKontakte

*Perform various OSINT on Russian social media site VKontakte.*

* <img src="https://www.google.com/s2/favicons?domain=vk.com&sz=16" width="16" height="16"> [Дезертир](http://vk.com/app3046467)
* <img src="https://www.google.com/s2/favicons?domain=vk.barkov.net&sz=16" width="16" height="16"> [Barkov.net](http://vk.barkov.net)
* <img src="https://www.google.com/s2/favicons?domain=vk5.city4me.com&sz=16" width="16" height="16"> [VK5](http://vk5.city4me.com)
* <img src="https://www.google.com/s2/favicons?domain=vk.com&sz=16" width="16" height="16"> [VK Community Search](http://vk.com/communities)
* <img src="https://www.google.com/s2/favicons?domain=vk.com&sz=16" width="16" height="16"> [VK People Search](http://vk.com/people)
* <img src="https://www.google.com/s2/favicons?domain=vk.watch&sz=16" width="16" height="16"> [VK.watch](https://vk.watch/)

### [↑](#-table-of-contents) 📱 WhatsApp

*[2Chat](https://2chat.co/tools/whatsapp-checker) - Check if a number is on WhatsApp.
*[Groupio](https://en.groupio.app/) - Find and search WhatsApp groups.
*[Whatsapp CheckLeaked](https://whatsapp.checkleaked.cc/) - WhatsApp Number Search & Profile Photo Checker. API Option Available.

### [↑](#-table-of-contents) ✏️ Tumblr

* <img src="https://www.google.com/s2/favicons?domain=www.tumblr.com&sz=16" width="16" height="16"> [Tumblr Search](http://www.tumblr.com/search)

### [↑](#-table-of-contents) 💼 LinkedIn

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [the-endorser](https://github.com/eth0izzle/the-endorser) - Tool that allows you to draw out relationships between people on LinkedIn via endorsements/skills.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [LinkedInDumper](https://github.com/l4rm4nd/LinkedInDumper) - Script to dump/scrape/extract company employees info from LinkedIn API.

### [↑](#-table-of-contents) ✈️ Telegram

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [CCTV](https://github.com/IvanGlinkin/CCTV) - Close-Circuit Telegram Vision revolutionizes location tracking with its open-source design and Telegram API integration. Offering precise tracking within 50-100 meters, users can monitor others in real-time for logistics or safety, redefining how we navigate our surroundings.
* <img src="https://www.google.com/s2/favicons?domain=groupda.com&sz=16" width="16" height="16"> [GroupDa](https://groupda.com/telegram/group/search) - Can be used for Searching Telegram Channels. Search by Category, Countries and Language.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Maltego Telegram](https://github.com/vognik/maltego-telegram) - Rich Set of Entities & Transforms for OSINT on Telegram with Maltego.
* <img src="https://www.google.com/s2/favicons?domain=www.telegram-finder.io&sz=16" width="16" height="16"> [Telegram Finder](https://www.telegram-finder.io/) - A tool to find Telegram users by their phone number, linkedin url or email.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Telerecon](https://github.com/sockysec/Telerecon) - A reconnaissance framework for researching and investigating Telegram.
* <img src="https://www.google.com/s2/favicons?domain=tgramsearch.com&sz=16" width="16" height="16"> [TgramSearch](https://tgramsearch.com/) - Convenient search for Telegram channels, as well as a structured catalog with over 700000 Telegram channels. Available in 8+ Languages.
* [tgworld](https://tg.world/) - The Global Search System TG.World will help you find Channels, Groups and Bots in Telegram in any language and for any country in the world!
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Telegram Channel Joiner](https://github.com/spmedia/Telegram-Channel-Joiner) - grow your Free and Premium Telegram accounts easily with this channel joiner script.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Telepahty](https://github.com/proseltd/Telepathy-Community) - Telepathy is a tool that archives Telegram chats and analyzes communication patterns within the app. By providing insights into user interactions, message frequency, and content trends, Telepathy helps investigators understand the dynamics and relationships within Telegram groups and channels.
* <img src="https://www.google.com/s2/favicons?domain=teleteg.com&sz=16" width="16" height="16"> [Teleteg](https://teleteg.com/) - The ultimate Telegram search engine. 10 results for free plan.
* <img src="https://www.google.com/s2/favicons?domain=cse.google.com&sz=16" width="16" height="16"> [Telegago](https://cse.google.com/cse?q=+&cx=006368593537057042503:efxu7xprihg#gsc.tab=0&gsc.q=%20&gsc.page=1) - A Google Advanced Search specifically for finding public and private Telegram Channels and Chatrooms.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Telegram Nearby Map](https://github.com/tejado/telegram-nearby-map) - Webapp based on OpenStreetMap and the official Telegram library to find the position of nearby users.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Telegram channels scraper TeleGraphite ](https://github.com/hamodywe/telegram-scraper-TeleGraphite) - Telegram Scraper & JSON Exporter & telegram channels scraper.
* <img src="https://www.google.com/s2/favicons?domain=telesearch.me&sz=16" width="16" height="16"> [TeleSearch](https://telesearch.me/) - Search and find your desired Telegram channels, groups, bots and games quickly and easily with Telesearch​.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [TeleTracker](https://github.com/tsale/TeleTracker) - TeleTracker is a simple set of Python scripts designed for anyone investigating Telegram channels. It helps you send messages quickly and gather useful channel information easily.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [TOsint](https://github.com/drego85/tosint) - Tosint (Telegram OSINT) is a powerful tool designed to extract valuable information from Telegram bots and channels. It serves as an essential resource for security researchers, investigators, and anyone interested in gathering insights from various Telegram entities.

**Telegram Bots**
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [AgentFNS_Bot](https://t.me/AgentFNS_bot) — Free instant counterparty check using official data (INN/OGRN).
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [AVinfoBot](https://t.me/AVskp_Bot) — Used-car history via plate/VIN/phone.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [AvtoNomer](https://t.me/avtonomerbot) — Finds vehicle photos by plate via platesmania.com.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [avtogram_bot](https://telegram.me/ABTOGRAMBOT) — Paid car reports (VIN/plate): accidents, fines, liens.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [avtocodbot](https://t.me/avtocodbot) — Paid VIN/plate lookup.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [bmi_np_bot](https://t.me/MNProbot) — Identifies phone-number operator and basic info.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [ChatSearchRobot](https://t.me/ChatSearchRobot) — Finds chats with similar topics; 709k+ VK chats.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [ClerkBot](https://t.me/clerksecretbot) — Phone + username lookup; vehicle info.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [creationdatebot](https://t.me/creationdatebot) — Approx. Telegram account creation date.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [CryptoBot](https://t.me/CryptoBot) — Anonymous crypto wallet.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [datXpert](https://telegram.me/datxpertbot) — Leak search via IntelX.
* <img src="https://www.google.com/s2/favicons?domain=detectiva.link&sz=16" width="16" height="16"> [Detectiva](http://detectiva.link/rezervBot) — Phone/email lookup with 6 search types.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Discord Sensor](https://telegram.me/discordsensorbot) — Retrieves Discord account data.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [dCallsBot](https://t.me/dCallsBot) — Anonymous calls, masking, eSIM/DID.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [EasyVIN](https://t.me/EasyVINbot) — Cheap VIN/plate history check.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [egrul_bot](https://t.me/egrul_bot) — Free counterparty-check bot.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [EyeTON](https://telegram.me/istoneyebot) — TON wallet graph + linked profiles.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [FindStickerCreator](https://t.me/SPOwnerBot) — Finds creator of any Telegram sticker pack.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Фари](https://telegram.me/faribybot) — VIN-history lookup from getcar.by.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [GeoMacFinder](https://t.me/geomacbot) — Finds Wi-Fi AP location by MAC/BSSID.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [getChatList](https://telegram.me/getchatlistbot) — Shows user’s group list.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Getairplane](https://telegram.me/getairplane_bot) — Phone → flight history (20 years).
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [GetSendGifts](https://telegram.me/GetSendGiftsProBot) — Shows who sent Telegram gifts.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [HimeraSearch](https://t.me/HimeraNeGBL8Pro1dp_Search_bot) — OSINT/HUMINT search: phones, emails, vehicles, people, courts.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Insight](https://t.me/ibhld_bot) — Shows interests based on subscriptions.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [InstaAnonym](https://t.me/instaanonymbot) — Anonymous Instagram/VK viewer.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [InstaBot](https://telegram.me/InstaBot) — Downloads Instagram media.
* <img src="https://www.google.com/s2/favicons?domain=infotrackpeople.org&sz=16" width="16" height="16"> [ITP Infotrack](https://infotrackpeople.org/) — People, vehicle, property lookup.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Leak OSINT](https://telegram.me/Leak_SSINTbot) — Phone-number leakage check.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Maigret OSINT bot](https://t.me/osint_maigret_bot) — Username search on 1,366 sites.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [mnp_bot](https://t.me/mnp_bot) — Phone operator + region.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [MotherSearchBot](https://t.me/MotherSearchBot) — Google-like Telegram search.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [NEUROAUTOSEARCH](https://t.me/noblackAuto_bot) — Car DB search + neural networks.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [OkSearch](https://telegram.me/OkSearchBot) — Search channels, bots, groups by keyword.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [OpenDataUABot](https://t.me/OpenDataUABot) — Ukrainian OSINT bot.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [OPENLOAD Bot](https://t.me/OPENLOADTOPBOT) — Semi-automated OSINT/vuln scanning suite.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Osintkit](https://t.me/osintkit_check_bot) — Ukrainian lookup: passport, tax ID, email, phone, address, vehicles, Telegram.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [PasswordSearch](https://telegram.me/PasswordSearchBot) — Shows leaked passwords for an email.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [PimEyes](https://telegram.me/pimeyesbot) — Face-search across social networks.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [RegDateBot](https://t.me/regdate_clone_bot) — Registration date by ID/forward.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [SangMata (beta)](https://t.me/SangMata_beta_bot) — Name-change history via /search_id.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [SangMataInfo_bot](https://t.me/SangMataInfo_bot) — Username change history.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [SaveYoutubeBot](https://t.me/SaveYoutubeBot) — Finds and downloads YouTube videos.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Search_firm_bot](https://t.me/Search_firm_bot) — Searches organizations, banks, postal codes.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Searchforchats](https://telegram.me/searchforchatsbot) — Searches chats by keywords.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Sherlock](https://t.me/Getcontact123qwerty_bot?start=_ref_jGW8Sa_iEmG9V) — Name/phone/email search + vehicle data.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [ShtrafKZBot](https://t.me/ShtrafKZBot) — Fines, taxes, penalties; traffic violations.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [SMS Activate](https://t.me/PrivatePhoneBot) — Virtual numbers from 50+ countries.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [SpyGGbot](https://telegram.me/SpyGGbot) — TON balances, NFT owners, Fragment usernames.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [Surftg_bot](https://t.me/surftg_bot) — Searches Telegram messages.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [TuriBot](https://t.me/TuriBot) — Resolves username from Telegram ID.
* <img src="https://www.google.com/s2/favicons?domain=telegram.me&sz=16" width="16" height="16"> [Unamer](https://telegram.me/unamer_bot) — Username ownership history.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [username_to_id_bot](https://t.me/username_to_id_bot) — Returns user/chat/channel/bot ID.
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [UsInfoBot](https://t.me/usinfobot) — Resolves username from ID (inline).
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [WhoisDomBot](https://t.me/WhoisDomBot) — Whois lookup for domains/IPs + dig/trace.

### [↑](#-table-of-contents) 🎮 Steam

* <img src="https://www.google.com/s2/favicons?domain=osint-steam.vercel.app&sz=16" width="16" height="16"> [OSINT-Steam](https://osint-steam.vercel.app/en) - An [open-source](https://github.com/Berchez/OSINT-steam) tool that returns public information, such as friends list and possible locations, from Steam profiles.

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Steam-OSINT](https://github.com/matiash26/steam-osint) - Open-source OSINT tool for accurate mutual friends analysis on Steam, supporting full friend lists.

### [↑](#-table-of-contents) 🐙 GitHub

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [github_monitor](https://github.com/misiektoja/github_monitor) - Tool for real-time tracking of GitHub users' activities including profile and repository changes with support for email alerts, CSV logging, detection when a user blocks or unblocks you and more
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [GithubRecon](https://kriztalz.sh/github-recon/) - Lookup Github users by username or email and gather associated data.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Shotstars](https://github.com/snooppr/shotstars) - An advanced tool for checking GitHub repositories, with star statistics, including fake star analysis and data visualization.


### [↑](#-table-of-contents) 🎵 TikTok

* <img src="https://www.google.com/s2/favicons?domain=www.tiktok.com&sz=16" width="16" height="16"> [TikTok Search](https://www.tiktok.com/search) - Native TikTok search for users, videos, sounds, and hashtags.
* <img src="https://www.google.com/s2/favicons?domain=tikfinity.zerody.one&sz=16" width="16" height="16"> [Tikfinity](https://tikfinity.zerody.one/) - TikTok live stream analytics and monitoring.
* [TikTok Timestamp](https://bellingcat.github.io/tiktok-timestamp/) - Extract exact upload timestamp from TikTok video URLs.

### [↑](#-table-of-contents) 💬 Discord

* [Discord History Tracker](https://dht.chylex.com/) - Browser script to save chat history in Discord servers and DMs.
* [DiscordLeaks](https://discordleaks.unicornriot.ninja/) - Searchable database of leaked Discord chat logs from extremist servers.
* <img src="https://www.google.com/s2/favicons?domain=disboard.org&sz=16" width="16" height="16"> [Disboard](https://disboard.org/) - Public Discord server listing and search engine.

### [↑](#-table-of-contents) 🐘 Mastodon / Fediverse

* [instances.social](https://instances.social/) - Directory of Mastodon instances with statistics and filters.
* <img src="https://www.google.com/s2/favicons?domain=fedi.directory&sz=16" width="16" height="16"> [Fedi.Directory](https://fedi.directory/) - Curated directory of interesting Fediverse accounts to follow.
* [FediFinder](https://fedifinder.glitch.me/) - Find your Twitter follows on Mastodon and the Fediverse.

## [↑](#-table-of-contents) 📝 Blog Search

* [BlogSearchEngine](http://www.blogsearchengine.org)
* <img src="https://www.google.com/s2/favicons?domain=www.notey.com&sz=16" width="16" height="16"> [Notey](http://www.notey.com) - Blog post search engine.
* <img src="https://www.google.com/s2/favicons?domain=www.twingly.com&sz=16" width="16" height="16"> [Twingly](http://www.twingly.com)

## [↑](#-table-of-contents) 💬 Forums and Discussion Boards Search

* <img src="https://www.google.com/s2/favicons?domain=4chansearch.com&sz=16" width="16" height="16"> [4chan Search](https://4chansearch.com/)
* <img src="https://www.google.com/s2/favicons?domain=boardreader.com&sz=16" width="16" height="16"> [Boardreader](http://boardreader.com)
* [Built With Flarum](https://builtwithflarum.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.facebook.com&sz=16" width="16" height="16"> [Facebook Groups](https://www.facebook.com)
* <img src="https://www.google.com/s2/favicons?domain=groups.google.com&sz=16" width="16" height="16"> [Google Groups](https://groups.google.com)
* <img src="https://www.google.com/s2/favicons?domain=www.linkedin.com&sz=16" width="16" height="16"> [Linkedin Groups](http://www.linkedin.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ning.com&sz=16" width="16" height="16"> [Ning](http://www.ning.com)
* <img src="https://www.google.com/s2/favicons?domain=groups.yahoo.com&sz=16" width="16" height="16"> [Yahoo Groups](https://groups.yahoo.com)

## [↑](#-table-of-contents) 🔎 Username Check

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Blackbird](https://github.com/p1ngul1n0/blackbird) - Search a username across over 600+ websites.
* [CheckUser](https://checkuser.vercel.app/) - search username across social networks
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Cupidcr4wl](https://github.com/OSINTI4L/cupidcr4wl) - Username and phone number search tool that crawls adult content platforms to see if a targeted account or person is present.
* <img src="https://www.google.com/s2/favicons?domain=www.digitalfootprintcheck.com&sz=16" width="16" height="16"> [Digital Footprint Check](https://www.digitalfootprintcheck.com/free-checker.html)  - Check for registered username on 100s of sites for free.
* <img src="https://www.google.com/s2/favicons?domain=www.idcrawl.com&sz=16" width="16" height="16"> [IDCrawl](https://www.idcrawl.com/username) - Search for a username in popular social networks.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Maigret](https://github.com/soxoj/maigret) - Collect a dossier on a person by username.
* <img src="https://www.google.com/s2/favicons?domain=www.namechk.com&sz=16" width="16" height="16"> [Name Chk](http://www.namechk.com) - Check over 30 domains and more than 90 social media account platforms.
* [Name Checkr](http://www.namecheckr.com) - checks a domain and username across many platforms.
* <img src="https://www.google.com/s2/favicons?domain=namecheckup.com&sz=16" width="16" height="16"> [Name Checkup](https://namecheckup.com) - is a search tool that allows you to check the avilability of a givrn username from all over the social media. Inaddition it also sllows you to check the avilability of a given domain name.
* [NameKetchup](https://nameketchup.com) - checks domain name and username in popular social media sites and platforms.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [NexFil](https://github.com/thewhiteh4t/nexfil) - checks username from almost all social network sites.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Seekr](https://github.com/seekr-osint/seekr) A multi-purpose all in one toolkit for gathering and managing OSINT-Data with a neat web-interface. Can be used for note taking and username checking.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Sherlock](https://github.com/sherlock-project/sherlock) - Search for a username in multiple platforms/websites.
* <img src="https://www.google.com/s2/favicons?domain=sherlockeye.io&sz=16" width="16" height="16"> [SherlockEye](https://sherlockeye.io/) - Search for publicly available information connected to a username, uncovering associated profiles and activities across the web.
* [Trace](https://trace.manus.space) - Real-time OSINT platform to search usernames, emails, phone numbers, and full names across 600+ platforms with breach detection and AI risk scoring.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Snoop](https://github.com/snooppr/snoop/blob/master/README.en.md) - Search for a nickname on the web (OSINT world)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Social Analyzer](https://github.com/qeeqbox/social-analyzer) - API, CLI, and Web App for analyzing and finding a person's profile in 1000 social media \ websites
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [user-scanner](https://github.com/kaifcodec/user-scanner.git) — Check a username's presence across dev/social/gaming/creator site
* <img src="https://www.google.com/s2/favicons?domain=www.usersearch.org&sz=16" width="16" height="16"> [User Search](http://www.usersearch.org) - Find someone by username, email, phone number or picture across Social Networks, Dating Sites, Forums, Crypto Forums, Chat Sites and Blogs, 3000+ sites Supported!
* <img src="https://www.google.com/s2/favicons?domain=www.user-searcher.com&sz=16" width="16" height="16"> [User Searcher](https://www.user-searcher.com) - User-Searcher is a powerful and free tool to help you search username in 2000+ websites.
* [WhatsMyName](https://whatsmyname.app/) - check for usernames across many different platforms.


## [↑](#-table-of-contents) 👥 People Investigations

* <img src="https://www.google.com/s2/favicons?domain=www.192.com&sz=16" width="16" height="16"> [192 (UK)](http://www.192.com) - Search by person, business, address. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=www.411.com&sz=16" width="16" height="16"> [411 (US)](http://www.411.com) - Search by person, phone number, address, and business. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=www.ancestry.com&sz=16" width="16" height="16"> [Ancestry](http://www.ancestry.com) - Premium data, free trial with credit card.
* <img src="https://www.google.com/s2/favicons?domain=www.apollo.io&sz=16" width="16" height="16"> [Apollo.io](https://www.apollo.io/) - Free B2B Phone Number & Email Finder. 1200 credits per user/year for free plan.
* <img src="https://www.google.com/s2/favicons?domain=www.backgroundchecks.com&sz=16" width="16" height="16"> [BeenVerified](https://www.backgroundchecks.com/solutions/beenverified)
* <img src="https://www.google.com/s2/favicons?domain=www.blackbookonline.info&sz=16" width="16" height="16"> [Black Book Online](https://www.blackbookonline.info) - Free. Nationwide directory of public record lookups.
* <img src="https://www.google.com/s2/favicons?domain=www.canada411.ca&sz=16" width="16" height="16"> [Canada411](http://www.canada411.ca) - Search by person, phone number, and business. Free.
* <img src="https://www.google.com/s2/favicons?domain=www.classmates.com&sz=16" width="16" height="16"> [Classmates](http://www.classmates.com) - High-school focused people search. Free acounts allow creating a profile and viewing other members. Premium account required to contact other members.
* <img src="https://www.google.com/s2/favicons?domain=contactout.com&sz=16" width="16" height="16"> [ContactOut](https://contactout.com/) - Unlock the world's most accurate contact data. Find emails & phone for 300M professionals.
* <img src="https://www.google.com/s2/favicons?domain=clustrmaps.com&sz=16" width="16" height="16"> [Clustermaps](https://clustrmaps.com/) - Find people and address information associated with them
* <img src="https://www.google.com/s2/favicons?domain=www.crunchbase.com&sz=16" width="16" height="16"> [CrunchBase](http://www.crunchbase.com) - Business information database, with a focus on investment, acquisition, and executive data. Ancillary focus on market research and connecting founders and investors.
* <img src="https://www.google.com/s2/favicons?domain=facecheck.id&sz=16" width="16" height="16"> [FaceCheck.ID](https://facecheck.id) - Search the internet by face.
* <img src="https://www.google.com/s2/favicons?domain=familysearch.org&sz=16" width="16" height="16"> [Family Search](https://familysearch.org) - Popular genealogy site. Free, but registration required. Funded by The Church Of Jesus Christ of Latter-day Saints.
* <img src="https://www.google.com/s2/favicons?domain=familytreenow.com&sz=16" width="16" height="16"> [FamilyTreeNow](https://familytreenow.com) - Research family and geneology, no registration required, can search addresses, phone numbers, and email addresses as well as associations.
* <img src="https://www.google.com/s2/favicons?domain=www.bop.gov&sz=16" width="16" height="16"> [Federal Bureau of Prisons - Inmate Locator (US)](http://www.bop.gov/inmateloc) - Search federal inmates incarcerated from 1982 to the present.
* <img src="https://www.google.com/s2/favicons?domain=www.fold3.com&sz=16" width="16" height="16"> [Fold3 (US Military Records)](http://www.fold3.com) - Search military records. Search filters limited with free access. Premium access requires subscription.
* <img src="https://www.google.com/s2/favicons?domain=www.genealogybank.com&sz=16" width="16" height="16"> [Genealogy Bank](http://www.genealogybank.com) - Premium data, free trial with credit card.
* <img src="https://www.google.com/s2/favicons?domain=www.genealogylinks.net&sz=16" width="16" height="16"> [Genealogy Links](http://www.genealogylinks.net) - Genealogy directory with over 50K links.
* <img src="https://www.google.com/s2/favicons?domain=homemetry.com&sz=16" width="16" height="16"> [Homemetry](https://homemetry.com) - Reverse address search and allows searching for properties for sale/rent..
* <img src="https://www.google.com/s2/favicons?domain=infotracer.com&sz=16" width="16" height="16"> [InfoTracer](https://infotracer.com/) - Search for people. (Searches are paid)
* <img src="https://www.google.com/s2/favicons?domain=www.judyrecords.com&sz=16" width="16" height="16"> [Judyrecords](https://www.judyrecords.com/) - Free. Nationwide search of 400 million+ United States court cases.
* <img src="https://www.google.com/s2/favicons?domain=www.kompass.com&sz=16" width="16" height="16"> [Kompass](http://www.kompass.com) - Business directory and search.
* <img src="https://www.google.com/s2/favicons?domain=mugshots.com&sz=16" width="16" height="16"> [Mugshots](https://mugshots.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.opensanctions.org&sz=16" width="16" height="16"> [OpenSanctions](https://www.opensanctions.org/search/) - Information on sanctions and public office holders.
* <img src="https://www.google.com/s2/favicons?domain=www.peekyou.com&sz=16" width="16" height="16"> [PeekYou](https://www.peekyou.com/) - PeekYou offers the ability to search for people with checks done against more sites. Can check for arrest records as well.
* <img src="https://www.google.com/s2/favicons?domain=reunion.com&sz=16" width="16" height="16"> [Reunion](http://reunion.com) - People search. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=socialcatfish.com&sz=16" width="16" height="16"> [Socialcatfish](https://socialcatfish.com/) - Superextensive people search which works worldwide. Searches are done from 200 Billion records.
* <img src="https://www.google.com/s2/favicons?domain=www.searchbug.com&sz=16" width="16" height="16"> [SearchBug](http://www.searchbug.com) - People search. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=www.spokeo.com&sz=16" width="16" height="16"> [Spokeo](http://www.spokeo.com) - People search. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=surfface.com&sz=16" width="16" height="16"> [Surfface](https://surfface.com) - Face search and people finder that links faces to social media profiles and other public data.
* <img src="https://www.google.com/s2/favicons?domain=www.nationalarchives.gov.uk&sz=16" width="16" height="16"> [The National Archives (UK)](http://www.nationalarchives.gov.uk) - Search UK national archives.
* <img src="https://www.google.com/s2/favicons?domain=unicourt.com&sz=16" width="16" height="16"> [UniCourt](https://unicourt.com/) - Limited free searches, premium data upsell. Nationwide search of 100 million+ United States court cases.
* <img src="https://www.google.com/s2/favicons?domain=www.ukphonebook.com&sz=16" width="16" height="16"> [UK Phone Book](https://www.ukphonebook.com/) - Search people in a similar way as 192.com
* <img src="https://www.google.com/s2/favicons?domain=www.vinelink.com&sz=16" width="16" height="16"> [VineLink](https://www.vinelink.com/#state-selection) - Inmate search and notification service for victims of crime, linked to multiple correctional facilities' booking systems in the U.S.
* <img src="https://www.google.com/s2/favicons?domain=voterrecords.com&sz=16" width="16" height="16"> [Voter Records](https://voterrecords.com/) - Free political research tool to study more than 100 Million US voter records.
* <img src="https://www.google.com/s2/favicons?domain=www.whitepages.com&sz=16" width="16" height="16"> [White Pages (US)](http://www.whitepages.com) - People search. Limited free info, premium data upsell.
* <img src="https://www.google.com/s2/favicons?domain=www.zabasearch.com&sz=16" width="16" height="16"> [ZabaSearch](https://www.zabasearch.com/)

## [↑](#-table-of-contents) 📧 Email Search / Email Check

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Blackbird](https://github.com/p1ngul1n0/blackbird) - Search for accounts associated with a given email across various platforms.
* <img src="https://www.google.com/s2/favicons?domain=blacklistchecker.com&sz=16" width="16" height="16"> [Blacklist Checker](https://blacklistchecker.com/) - Blacklist Checker is anemail blacklist checker, monitor and API that checks 100+ blacklists in seconds
* <img src="https://www.google.com/s2/favicons?domain=dehashed.com&sz=16" width="16" height="16"> [DeHashed](https://dehashed.com/) - DeHashed helps prevent ATO with our extensive data set & breach notification solution. Match employee and consumer logins against the world’s largest repository of aggregated publicly available assets leaked from third-party breaches. Secure passwords before criminals can abuse stolen information, and protect your enterprise.
* <img src="https://www.google.com/s2/favicons?domain=www.email-validator.net&sz=16" width="16" height="16"> [Email Address Validator](http://www.email-validator.net)  - Improve deliverability, reduce bounce rates, prevent fraud and minimize funnel leaks.
* <img src="https://www.google.com/s2/favicons?domain=email-format.com&sz=16" width="16" height="16"> [Email Format](http://email-format.com) - is a website that allows you to find email address formats used by different companies.
* <img src="https://www.google.com/s2/favicons?domain=www.polished.app&sz=16" width="16" height="16"> [Email Permutator](https://www.polished.app/email-permutator/) - a powerful tool designed to aid professionals in generating a range of potential email addresses for a specific contact.
* <img src="https://www.google.com/s2/favicons?domain=tools.verifyemailaddress.io&sz=16" width="16" height="16"> [EmailHippo](https://tools.verifyemailaddress.io) - is an email address verification platform that will check whether a given email address exist or not.
* [EmailRep](https://emailrep.io) - Email address reputation and risk scoring service.
* <img src="https://www.google.com/s2/favicons?domain=tools.epieos.com&sz=16" width="16" height="16"> [Epieos Tools](https://tools.epieos.com) - Collection of OSINT tools for email investigations.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Ghunt](https://github.com/mxrch/GHunt) - Investigate Google emails and documents.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Gitrecon](https://github.com/atiilla/gitrecon) - Node.js tool to scan GitHub repositories for exposed email addresses and names.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [h8mail](https://github.com/khast3x/h8mail) - Password Breach Hunting and Email OSINT, locally or using premium services. Supports chasing down related email.
* <img src="https://www.google.com/s2/favicons?domain=haveibeenpwned.com&sz=16" width="16" height="16"> [Have I Been Pwned](https://haveibeenpwned.com) - Search across multiple data breaches to see if your email address has been compromised.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Holehe](https://github.com/megadose/holehe) - allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function.
* <img src="https://www.google.com/s2/favicons?domain=hunter.io&sz=16" width="16" height="16"> [Hunter](https://hunter.io) - Hunter lets you find email addresses in seconds and connect with the people that matter for your business.
* <img src="https://www.google.com/s2/favicons?domain=infostealers.info&sz=16" width="16" height="16"> [InfoStealers](https://infostealers.info/en/info) - Indexes darknet-exposed infostealer logs and makes them searchable and actionable for security teams, investigators, researchers, and digital forensics professionals.
* <img src="https://www.google.com/s2/favicons?domain=intelbase.is&sz=16" width="16" height="16"> [IntelBase](https://intelbase.is/) - Forensics platform focused on reverse email lookup and email data enrichment.
* <img src="https://www.google.com/s2/favicons?domain=leakcheck.io&sz=16" width="16" height="16"> [LeakCheck](https://leakcheck.io/) - Data Breach Search Engine with 7.5B+ entries collected from more than 3000 databases. Search by e-mail, username, keyword, password or corporate domain name.
* <img src="https://www.google.com/s2/favicons?domain=leakradar.io&sz=16" width="16" height="16"> [LeakRadar](https://leakradar.io/) - Scans for compromised emails and domains in stealer logs, offering proactive breach prevention and real-time alerts.
* <img src="https://www.google.com/s2/favicons?domain=mailtester.com&sz=16" width="16" height="16"> [MailTester](http://mailtester.com) - hunt for emails and improve your email deliverability
* <img src="https://www.google.com/s2/favicons?domain=minervaosint.com&sz=16" width="16" height="16"> [Minerva OSINT](https://minervaosint.com) - Email search tool that finds and aggregates data on a target email from over a hundred websites.
* <img src="https://www.google.com/s2/favicons?domain=multirbl.valli.org&sz=16" width="16" height="16"> [Multirbl](https://multirbl.valli.org/dnsbl-lookup) - MultiRBL Valli checks if an IP or domain is listed on multiple public RBLs (blacklists) simultaneously.
* <img src="https://www.google.com/s2/favicons?domain=mxtoolbox.com&sz=16" width="16" height="16"> [mxtoolbox](https://mxtoolbox.com/) - Free online tools to investigate/troubleshoot email server issues.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [OSINTEye](https://github.com/atiilla/OsintEye) - OSINT Eye: A WPF Desktop Application for GitHub Intelligence, Social Media Reconnaissance, and Subdomain Discovery
* [Peepmail](http://www.samy.pl/peepmail) - is a tool that allows you to discover business email addresses for users, even if their email address may not be publicly available or shared.
* <img src="https://www.google.com/s2/favicons?domain=pipl.com&sz=16" width="16" height="16"> [Pipl](https://pipl.com) - a provider of identity solutions.
* <img src="https://www.google.com/s2/favicons?domain=reacher.email&sz=16" width="16" height="16"> [Reacher](https://reacher.email) - Real-time email verification API, written in Rust, 100% open-source.
* <img src="https://www.google.com/s2/favicons?domain=sherlockeye.io&sz=16" width="16" height="16"> [SherlockEye](https://sherlockeye.io/) - Search for publicly available data linked to an email address across multiple sources on the internet.
* <img src="https://www.google.com/s2/favicons?domain=snov.io&sz=16" width="16" height="16"> [Snov.io](https://snov.io/email-finder) - Find email addresses on any website.
* <img src="https://www.google.com/s2/favicons?domain=check.spamhaus.org&sz=16" width="16" height="16"> [Spamhaus](https://check.spamhaus.org/) - Lookup Reputation Checker.
* <img src="https://www.google.com/s2/favicons?domain=thatsthem.com&sz=16" width="16" height="16"> [ThatsThem](https://thatsthem.com/reverse-email-lookup) - Reverse Email Lookup.
* <img src="https://www.google.com/s2/favicons?domain=www.toofr.com&sz=16" width="16" height="16"> [Toofr](https://www.toofr.com) - Find Anyone’s Email Address in Seconds.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [user-scanner](https://github.com/kaifcodec/user-scanner.git) - Takes an email, scan on various popular sites, games and retrieve info if the email is registered there or not.
* <img src="https://www.google.com/s2/favicons?domain=verify-email.org&sz=16" width="16" height="16"> [Verify Email](http://verify-email.org) - The fastest and most accurate email verification tool.
* <img src="https://www.google.com/s2/favicons?domain=www.voilanorbert.com&sz=16" width="16" height="16"> [VoilaNorbert](https://www.voilanorbert.com) - Find anyone's contact information for lead research or talent acquisition.

## [↑](#-table-of-contents) 📞 Phone Number Research

* [CallerID Test](https://calleridtest.com/) - Get caller ID and telco carrier information back from a phone number.
* <img src="https://www.google.com/s2/favicons?domain=www.emobiletracker.com&sz=16" width="16" height="16"> [EmobileTracker.com](https://www.emobiletracker.com/) - a service specifically designed to Track Mobile Number, Location on Google Map including information such as the owner's Name,Location,Country,Telecom provider.
* <img src="https://www.google.com/s2/favicons?domain=freecarrierlookup.com&sz=16" width="16" height="16"> [FreeCarrierLookup](https://freecarrierlookup.com/) - enter a phone number and we'll return the carrier name and whether the number is wireless or landline. We also return the email-to-SMS and email-to-MMS gateway addresses for USA and Canadian* phone numbers.
* <img src="https://www.google.com/s2/favicons?domain=www.infobel.com&sz=16" width="16" height="16"> [Infobel](https://www.infobel.com/) - Search 164+ million records across 73 countries for companies and individuals. Find places, local service providers, their contact details, reviews, opening hours and more.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [InMobPrefix](https://github.com/hstsethi/in-mob-prefix) - Dataset, charts, models about mobile phone numbers prefixes in India along with their respective state, operator.
* <img src="https://www.google.com/s2/favicons?domain=www.phonevalidator.com&sz=16" width="16" height="16"> [Phone Validator](https://www.phonevalidator.com/index.aspx) - Pretty accurate phone lookup service, particularly good against Google Voice numbers.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) - Advanced information gathering & OSINT framework for phone numbers.
* <img src="https://www.google.com/s2/favicons?domain=www.reversephonecheck.com&sz=16" width="16" height="16"> [Reverse Phone Check](https://www.reversephonecheck.com) - Look up names, addresses, phone numbers, or emails and anonymously discover information about yourself, family, friends, or old schoolmates. Powered by infotracer.com
* <img src="https://www.google.com/s2/favicons?domain=www.reversephonelookup.com&sz=16" width="16" height="16"> [Reverse Phone Lookup](http://www.reversephonelookup.com/) - Detailed information about phone carrier, region, service provider, and switch information.
* <img src="https://www.google.com/s2/favicons?domain=www.searchpeoplefree.com&sz=16" width="16" height="16"> [SearchPeopleFREE](https://www.searchpeoplefree.com/phone-lookup) - a reverse name, address, email address, or phone lookup that allows you to discover the owner of a phone number or who lives at an address.
* <img src="https://www.google.com/s2/favicons?domain=spydialer.com&sz=16" width="16" height="16"> [Spy Dialer](http://spydialer.com/) - Get the voicemail of a cell phone & owner name lookup.
* <img src="https://www.google.com/s2/favicons?domain=sync.me&sz=16" width="16" height="16"> [Sync.ME](https://sync.me/) - a caller ID and spam blocker app.
* [Truecaller](https://truecaller.com) - Global reverse phone number search.
* <img src="https://www.google.com/s2/favicons?domain=www.twilio.com&sz=16" width="16" height="16"> [Twilio](https://www.twilio.com/docs/lookup/v2-api) - Look up a phone numbers carrier type, location, etc. Twilio offers free accounts that come with credits you can use with their API. Each lookup is only ~$0.01-$0.02 typically on US and CAN numbers.
* <img src="https://www.google.com/s2/favicons?domain=www.usphonebook.com&sz=16" width="16" height="16"> [USPhoneBook](https://www.usphonebook.com/) - Reverse phone and address lookups and leading data.

## [↑](#-table-of-contents) 🚗 Vehicle / Automobile Research

* <img src="https://www.google.com/s2/favicons?domain=www.faxvin.com&sz=16" width="16" height="16"> [FaxVIN](https://www.faxvin.com/) - Vehicle History Reports. A license plate lookup tool that returns info like VIN, make & model of vehicle, age, and numerous other details.
* <img src="https://www.google.com/s2/favicons?domain=epicvin.com&sz=16" width="16" height="16"> [EpicVIN](https://epicvin.com/) - Vehicle reports are compiled from various data sources, including historical accident records from state agencies and other entities like NMVTIS. License plate lookup that returns VIN and car millage.

## [↑](#-table-of-contents) 🎓 Expert Search

* <img src="https://www.google.com/s2/favicons?domain=academia.edu&sz=16" width="16" height="16"> [Academia](http://academia.edu) - is a platform for sharing academic research.
* <img src="https://www.google.com/s2/favicons?domain=www.expertisefinder.com&sz=16" width="16" height="16"> [ExpertiseFinder](http://www.expertisefinder.com)
* <img src="https://www.google.com/s2/favicons?domain=expertpages.com&sz=16" width="16" height="16"> [ExpertPages](http://expertpages.com)
* <img src="https://www.google.com/s2/favicons?domain=www.experts.com&sz=16" width="16" height="16"> [Experts.com](http://www.experts.com)
* <img src="https://www.google.com/s2/favicons?domain=www.helpareporter.com&sz=16" width="16" height="16"> [HARO](http://www.helpareporter.com)
* [Licenseplates](http://www.worldlicenseplates.com/)
* [GlobalExperts](http://www.theglobalexperts.org)
* <img src="https://www.google.com/s2/favicons?domain=www.idealist.org&sz=16" width="16" height="16"> [Idealist](http://www.idealist.org)
* <img src="https://www.google.com/s2/favicons?domain=www.innocentive.com&sz=16" width="16" height="16"> [Innocentive](http://www.innocentive.com)
* [Internet Experts](http://www.internetexperts.info)
* <img src="https://www.google.com/s2/favicons?domain=www.loc.gov&sz=16" width="16" height="16"> [Library of Congress: Ask a Librarian](http://www.loc.gov/rr/askalib)
* [Maven](http://www.maven.co)
* <img src="https://www.google.com/s2/favicons?domain=muckrack.com&sz=16" width="16" height="16"> [MuckRack](http://muckrack.com) - Extensive database of U.S. government public records obtained through federal and state public records requests. Automated tool that will make public records requests and follow up until records are obtained on your behalf.
* <img src="https://www.google.com/s2/favicons?domain=www.nsaspeaker.org&sz=16" width="16" height="16"> [National Speakers Association](http://www.nsaspeaker.org)
* <img src="https://www.google.com/s2/favicons?domain=www.newswise.com&sz=16" width="16" height="16"> [Newswise](http://www.newswise.com)
* <img src="https://www.google.com/s2/favicons?domain=oedci.uspto.gov&sz=16" width="16" height="16"> [Patent Attorneys/Agent Search](https://oedci.uspto.gov/OEDCI/) - Official listing of U.S. attorneys qualified to represent individuals in U.S. patent office proceedings.
* [PRNewswire](https://prnmedia.prnewswire.com)
* <img src="https://www.google.com/s2/favicons?domain=www.researcherid.com&sz=16" width="16" height="16"> [ReseacherID](http://www.researcherid.com)
* [SheSource](http://www.shesource.org)
* <img src="https://www.google.com/s2/favicons?domain=www.sources.com&sz=16" width="16" height="16"> [Sources](http://www.sources.com)
* <img src="https://www.google.com/s2/favicons?domain=trexpertwitness.com&sz=16" width="16" height="16"> [TRExpertWitness](https://trexpertwitness.com)
* <img src="https://www.google.com/s2/favicons?domain=www.zintro.com&sz=16" width="16" height="16"> [Zintro](https://www.zintro.com)

## [↑](#-table-of-contents) 🏢 Company Research

* <img src="https://www.google.com/s2/favicons?domain=www.allstocks.com&sz=16" width="16" height="16"> [AllStocksLinks](http://www.allstocks.com/links)
* <img src="https://www.google.com/s2/favicons?domain=www.bbb.org&sz=16" width="16" height="16"> [Better Business Bureau](http://www.bbb.org)
* <img src="https://www.google.com/s2/favicons?domain=www.bizeurope.com&sz=16" width="16" height="16"> [Bizeurope](http://www.bizeurope.com)
* <img src="https://www.google.com/s2/favicons?domain=www.bloomberg.com&sz=16" width="16" height="16"> [Bloomberg](http://www.bloomberg.com/research/company/overview/overview.asp)
* <img src="https://www.google.com/s2/favicons?domain=www.brownbook.net&sz=16" width="16" height="16"> [BrownBook](https://www.brownbook.net/)
* <img src="https://www.google.com/s2/favicons?domain=www.bvdinfo.com&sz=16" width="16" height="16"> [Bureau Van Dijk](http://www.bvdinfo.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ebscohost.com&sz=16" width="16" height="16"> [Business Source](https://www.ebscohost.com/academic/business-source-complete)
* <img src="https://www.google.com/s2/favicons?domain=www.canada.ca&sz=16" width="16" height="16"> [Canadian Business Research](https://www.canada.ca/en/services/business/research.html)
* <img src="https://www.google.com/s2/favicons?domain=case.law&sz=16" width="16" height="16"> [Caselaw Access Project](https://case.law/) - Collection of full text of historical (not up-to-date) cases from United States state appellate courts.
* <img src="https://www.google.com/s2/favicons?domain=www.commercial-register.sg.ch&sz=16" width="16" height="16"> [Company Registration Round the World](http://www.commercial-register.sg.ch/home/worldwide.html)
* <img src="https://www.google.com/s2/favicons?domain=www.comparably.com&sz=16" width="16" height="16"> [Company Research Resources by Country Comparably](https://www.comparably.com)
* <img src="https://www.google.com/s2/favicons?domain=competeshark.com&sz=16" width="16" height="16"> [CompeteShark](http://competeshark.com)
* <img src="https://www.google.com/s2/favicons?domain=www.corporateinformation.com&sz=16" width="16" height="16"> [Corporate Information](http://www.corporateinformation.com) - Aggregated information from publicly available sources on publicly traded companies worldwide.
* <img src="https://www.google.com/s2/favicons?domain=www.corporationwiki.com&sz=16" width="16" height="16"> [CorporationWiki](https://www.corporationwiki.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.crunchbase.com&sz=16" width="16" height="16"> [CrunchBase](https://www.crunchbase.com) - Detailed information on startup businesses, with a specific focus on funding sources and funding procedures used by specific businesses.
* [Data.com Connect](https://connect.data.com)
* <img src="https://www.google.com/s2/favicons?domain=www.edgar-online.com&sz=16" width="16" height="16"> [EDGAR U.S. Securities and Exchange Commission Filings](http://www.edgar-online.com) - Periodic reports and extensive corporate disclosures from all businesses publicly traded in the United States.
* <img src="https://www.google.com/s2/favicons?domain=www.europages.co.uk&sz=16" width="16" height="16"> [Europages](http://www.europages.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.ebr.org&sz=16" width="16" height="16"> [European Business Register](http://www.ebr.org)
* <img src="https://www.google.com/s2/favicons?domain=www.ezilon.com&sz=16" width="16" height="16"> [Ezilon](http://www.ezilon.com)
* [Factiva](https://global.factiva.com)
* <img src="https://www.google.com/s2/favicons?domain=www.forbes.com&sz=16" width="16" height="16"> [Forbes Global 2000](http://www.forbes.com/global2000/)
* <img src="https://www.google.com/s2/favicons?domain=www.glassdoor.com&sz=16" width="16" height="16"> [Glassdoor](https://www.glassdoor.com)
* <img src="https://www.google.com/s2/favicons?domain=globaledge.msu.edu&sz=16" width="16" height="16"> [globalEdge](http://globaledge.msu.edu)
* [GoodFirms](https://www.goodfirms.co/)
* <img src="https://www.google.com/s2/favicons?domain=www.guidestar.org&sz=16" width="16" height="16"> [GuideStar](http://www.guidestar.org)
* <img src="https://www.google.com/s2/favicons?domain=www.hoovers.com&sz=16" width="16" height="16"> [Hoovers](http://www.hoovers.com)
* <img src="https://www.google.com/s2/favicons?domain=www.inc.com&sz=16" width="16" height="16"> [Inc. 5000](http://www.inc.com/inc5000)
* <img src="https://www.google.com/s2/favicons?domain=www.judyrecords.com&sz=16" width="16" height="16"> [Judyrecords](https://www.judyrecords.com/) - Free. Nationwide search of 400 million+ United States court cases.
* <img src="https://www.google.com/s2/favicons?domain=www.icaew.com&sz=16" width="16" height="16"> [Knowledge guide to international company registration](http://www.icaew.com/en/library/subject-gateways/business-management/company-administration/knowledge-guide-international-company-registration)
* <img src="https://www.google.com/s2/favicons?domain=www.linkedin.com&sz=16" width="16" height="16"> [Linkedin](https://www.linkedin.com) - Commonly used social-media platform with a focus on professional profiles and recruitment. Spans a wide variety of industries. Very useful for gathering information on what specific individuals are active within an entity.
* [Mergent Intellect](http://www.mergentintellect.com)
* <img src="https://www.google.com/s2/favicons?domain=www.mergentonline.com&sz=16" width="16" height="16"> [Mergent Online](http://www.mergentonline.com/login.php)
* <img src="https://www.google.com/s2/favicons?domain=en.wikipedia.org&sz=16" width="16" height="16"> [National Company Registers](https://en.wikipedia.org/wiki/List_of_company_registers)
* <img src="https://www.google.com/s2/favicons?domain=opencorporates.com&sz=16" width="16" height="16"> [OpenCorporates](https://opencorporates.com) - Global search of registered corporate entities and their associated individual officers or investors.
* <img src="https://www.google.com/s2/favicons?domain=register.openownership.org&sz=16" width="16" height="16"> [OpenOwnership Register](https://register.openownership.org/)
* [Orbis directory](http://orbisdirectory.bvdinfo.com/version-20161014/OrbisDirectory/Companies)
* <img src="https://www.google.com/s2/favicons?domain=www.gov.uk&sz=16" width="16" height="16"> [Overseas Company Registers](https://www.gov.uk/government/publications/overseas-registries/overseas-registries)
* <img src="https://www.google.com/s2/favicons?domain=www.plunkettresearchonline.com&sz=16" width="16" height="16"> [Plunkett Research](http://www.plunkettresearchonline.com)
* <img src="https://www.google.com/s2/favicons?domain=www.scoot.co.uk&sz=16" width="16" height="16"> [Scoot](http://www.scoot.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.semrush.com&sz=16" width="16" height="16"> [SEMrush](https://www.semrush.com)
* <img src="https://www.google.com/s2/favicons?domain=serpstat.com&sz=16" width="16" height="16"> [Serpstat](https://serpstat.com)
* <img src="https://www.google.com/s2/favicons?domain=www.spyfu.com&sz=16" width="16" height="16"> [SpyFu](http://www.spyfu.com)
* <img src="https://www.google.com/s2/favicons?domain=thewebco.ai&sz=16" width="16" height="16"> [TheWebCo](https://thewebco.ai) - The single source of people intelligence.
* <img src="https://www.google.com/s2/favicons?domain=unicourt.com&sz=16" width="16" height="16"> [UniCourt](https://unicourt.com/) - Limited free searches, premium data upsell. Nationwide search of 100 million+ United States court cases.
* <img src="https://www.google.com/s2/favicons?domain=www.vault.com&sz=16" width="16" height="16"> [Vault](http://www.vault.com) - Well-known ranking of largest United States Corporations.
* <img src="https://www.google.com/s2/favicons?domain=www.xing.com&sz=16" width="16" height="16"> [Xing](http://www.xing.com)
* <img src="https://www.google.com/s2/favicons?domain=youcontrol.com.ua&sz=16" width="16" height="16"> [YouControl](https://youcontrol.com.ua/en/)

## [↑](#-table-of-contents) 👔 Job Search Resources

* <img src="https://www.google.com/s2/favicons?domain=www.beyond.com&sz=16" width="16" height="16"> [Beyond](http://www.beyond.com)
* <img src="https://www.google.com/s2/favicons?domain=www.campuscareercenter.com&sz=16" width="16" height="16"> [CampusCareerCenter](http://www.campuscareercenter.com)
* <img src="https://www.google.com/s2/favicons?domain=www.careerbuilder.com&sz=16" width="16" height="16"> [CareerBuilder](http://www.careerbuilder.com)
* <img src="https://www.google.com/s2/favicons?domain=www.collegerecruiter.com&sz=16" width="16" height="16"> [College Recruiter](https://www.collegerecruiter.com)
* <img src="https://www.google.com/s2/favicons?domain=losangeles.craigslist.org&sz=16" width="16" height="16"> [Craiglist](http://losangeles.craigslist.org)
* [CVFox](http://www.cvfox.com)
* <img src="https://www.google.com/s2/favicons?domain=www.dice.com&sz=16" width="16" height="16"> [Dice](http://www.dice.com)
* <img src="https://www.google.com/s2/favicons?domain=www.eluta.ca&sz=16" width="16" height="16"> [Eluta (Canada)](http://www.eluta.ca)
* <img src="https://www.google.com/s2/favicons?domain=www.eurojobs.com&sz=16" width="16" height="16"> [Eurojobs](https://www.eurojobs.com)
* [Fish4Jobs](http://www.fish4.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.glassdoor.com&sz=16" width="16" height="16"> [Glassdoor](https://www.glassdoor.com)
* <img src="https://www.google.com/s2/favicons?domain=www.headhunter.com&sz=16" width="16" height="16"> [Headhunter](http://www.headhunter.com)
* <img src="https://www.google.com/s2/favicons?domain=www.indeed.com&sz=16" width="16" height="16"> [Indeed](http://www.indeed.com) - is an online job searching website that gives job seekers free access to search for a job, post their resumes, and research companies.
* <img src="https://www.google.com/s2/favicons?domain=www.jobs.pl&sz=16" width="16" height="16"> [Jobs (Poland)](http://www.jobs.pl)
* <img src="https://www.google.com/s2/favicons?domain=www.jobsite.co.uk&sz=16" width="16" height="16"> [Jobsite (UK)](http://www.jobsite.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.linkedin.com&sz=16" width="16" height="16"> [Linkedin](https://www.linkedin.com)
* <img src="https://www.google.com/s2/favicons?domain=www.monster.com&sz=16" width="16" height="16"> [Monster](http://www.monster.com)
* <img src="https://www.google.com/s2/favicons?domain=www.naukri.com&sz=16" width="16" height="16"> [Naukri (India)](http://www.naukri.com)
* <img src="https://www.google.com/s2/favicons?domain=recruitin.net&sz=16" width="16" height="16"> [RecruitEm](https://recruitin.net/)
* <img src="https://www.google.com/s2/favicons?domain=www.reed.co.uk&sz=16" width="16" height="16"> [Reed (UK)](http://www.reed.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.seek.com.au&sz=16" width="16" height="16"> [Seek (Australia)](http://www.seek.com.au)
* <img src="https://www.google.com/s2/favicons?domain=www.simplyhired.com&sz=16" width="16" height="16"> [SimplyHired](http://www.simplyhired.com)
* <img src="https://www.google.com/s2/favicons?domain=www.xing.com&sz=16" width="16" height="16"> [Xing](http://www.xing.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ziprecruiter.com&sz=16" width="16" height="16"> [ZipRecruiter](https://www.ziprecruiter.com)

## [↑](#-table-of-contents) ❓ Q&A Sites

* <img src="https://www.google.com/s2/favicons?domain=www.answers.com&sz=16" width="16" height="16"> [Answers.com](http://www.answers.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ask.com&sz=16" width="16" height="16"> [Ask](http://www.ask.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ehow.com&sz=16" width="16" height="16"> [eHow](http://www.ehow.com)
* <img src="https://www.google.com/s2/favicons?domain=www.quora.com&sz=16" width="16" height="16"> [Quora](http://www.quora.com)
* <img src="https://www.google.com/s2/favicons?domain=stackexchange.com&sz=16" width="16" height="16"> [StackExchange](http://stackexchange.com)
* <img src="https://www.google.com/s2/favicons?domain=answers.yahoo.com&sz=16" width="16" height="16"> [Yahoo Answers](http://answers.yahoo.com)
* <img src="https://www.google.com/s2/favicons?domain=otvet.mail.ru&sz=16" width="16" height="16"> [Ответы](https://otvet.mail.ru/)

## [↑](#-table-of-contents) 🖥️ Domain and IP Research

* <img src="https://www.google.com/s2/favicons?domain=db.aa419.org&sz=16" width="16" height="16"> [aa419 Fake Sites Database](https://db.aa419.org/fakebankslist.php) - The site lists fraudulent websites, such as fake banks and online scams, identified by the Artists Against 419 community.
* <img src="https://www.google.com/s2/favicons?domain=www.accuranker.com&sz=16" width="16" height="16"> [Accuranker](https://www.accuranker.com)
* [ahrefs](https://ahrefs.com) - A tool for backlink research, organic traffic research, keyword research, content marketing & more.
* <img src="https://www.google.com/s2/favicons?domain=tenantresolution.pingcastle.com&sz=16" width="16" height="16"> [Azure Tenant Resolution by PingCastle](https://tenantresolution.pingcastle.com) - Search for Azure Tenant using its domain name or its ID
* [Bgpview.io](https://bgpview.io) - The website bgpview.io allows you to look up detailed information about ASNs, IPs, and BGP routes on the internet.
* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing Webmaster Tools](http://www.bing.com/toolbox/webmaster)
* <img src="https://www.google.com/s2/favicons?domain=www.browserling.com&sz=16" width="16" height="16"> [Browserling](https://www.browserling.com) - Browserling is an online sandbox that lets users safely test potentially malicious links across browsers and operating systems in real time.
* <img src="https://www.google.com/s2/favicons?domain=builtwith.com&sz=16" width="16" height="16"> [BuiltWith](http://builtwith.com) - is a website that will help you find out all the technologies used to build a particular websites.
* [Central Ops](http://centralops.net)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Crypto Scam & Crypto Phishing URL Threat Intel Feed](https://github.com/spmedia/Crypto-Scam-and-Crypto-Phishing-Threat-Intel-Feed) - A fresh feed of crypto phishing and crypto scam websites. Automatically updated daily.
* <img src="https://www.google.com/s2/favicons?domain=dedicatedornot.com&sz=16" width="16" height="16"> [Dedicated or Not](http://dedicatedornot.com)
* <img src="https://www.google.com/s2/favicons?domain=completedns.com&sz=16" width="16" height="16"> [DNS History](https://completedns.com/dns-history/)
* <img src="https://www.google.com/s2/favicons?domain=dnsdumpster.com&sz=16" width="16" height="16"> [DNSDumpster](https://dnsdumpster.com) - is a website that will help you discover hosts related to a specific domain.
* <img src="https://www.google.com/s2/favicons?domain=www.dnsstuff.com&sz=16" width="16" height="16"> [DNSStuff](http://www.dnsstuff.com)
* <img src="https://www.google.com/s2/favicons?domain=dnsviz.net&sz=16" width="16" height="16"> [DNSViz](http://dnsviz.net)
* <img src="https://www.google.com/s2/favicons?domain=www.domaincrawler.com&sz=16" width="16" height="16"> [Domain Crawler](http://www.domaincrawler.com)
* [Domain Dossier](http://centralops.net/co/DomainDossier.aspx)
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [DomainRecon](https://kriztalz.sh/domain-recon/) - Retrieve DNS records, subdomains, SSL certificates and WHOIS / RDAP data for a given website.
* [Domain Tools](http://whois.domaintools.com) - Whois lookup and domain/ip historical data.
* [Easy whois](https://www.easywhois.com)
* <img src="https://www.google.com/s2/favicons?domain=exonerator.torproject.org&sz=16" width="16" height="16"> [Exonera Tor](https://exonerator.torproject.org) - A database of IP addresses that have been part of the Tor network. It answers the question whether there was a Tor relay running on a given IP address on a given date.
* <img src="https://www.google.com/s2/favicons?domain=focsec.com&sz=16" width="16" height="16"> [Focsec](https://focsec.com) - Threat Intelligence API that detects if a IP address is associated with a VPN, Proxy, TOR or Bots.
* <img src="https://www.google.com/s2/favicons?domain=follow.net&sz=16" width="16" height="16"> [Follow.net](http://follow.net)
* <img src="https://www.google.com/s2/favicons?domain=fullhunt.io&sz=16" width="16" height="16"> [Fullhunt](https://fullhunt.io/) - FullHunt is an OSINT tool focused on identifying and protecting internet-exposed assets.
* <img src="https://www.google.com/s2/favicons?domain=app.graphystories.com&sz=16" width="16" height="16"> [GraphyStories](http://app.graphystories.com)
* <img src="https://www.google.com/s2/favicons?domain=www.hudsonrock.com&sz=16" width="16" height="16"> [Hudson Rock](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) - is a free cybercrime intelligence toolkit to check exposure in Infostealer malware infection.
* <img src="https://www.google.com/s2/favicons?domain=www.hybrid-analysis.com&sz=16" width="16" height="16"> [Hybrid Analysis](https://www.hybrid-analysis.com) - Online service for detailed and free analysis of suspicious files and URLs.
* <img src="https://www.google.com/s2/favicons?domain=www.hypestat.com&sz=16" width="16" height="16"> [HypeStat](https://www.hypestat.com)
* <img src="https://www.google.com/s2/favicons?domain=lookup.icann.org&sz=16" width="16" height="16"> [Icann Lookup](https://lookup.icann.org/en/lookup) - The site allows you to look up domain registration information (WHOIS) on the internet
* <img src="https://www.google.com/s2/favicons?domain=www.infosniper.net&sz=16" width="16" height="16"> [Infosniper](http://www.infosniper.net)
* <img src="https://www.google.com/s2/favicons?domain=ismalicious.com&sz=16" width="16" height="16"> [isMalicious](https://ismalicious.com) - Threat intelligence platform aggregating malicious IP and domain data from multiple security feeds with real-time reputation scoring and threat categorization.
* <img src="https://www.google.com/s2/favicons?domain=www.intodns.com&sz=16" width="16" height="16"> [intoDNS](http://www.intodns.com)
* <img src="https://www.google.com/s2/favicons?domain=ip2geolocation.com&sz=16" width="16" height="16"> [IP 2 Geolocation](http://ip2geolocation.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ip2location.com&sz=16" width="16" height="16"> [IP 2 Location](http://www.ip2location.com/demo.aspx)
* <img src="https://www.google.com/s2/favicons?domain=db-ip.com&sz=16" width="16" height="16"> [IP Geolocation API DB-IP](https://db-ip.com) - Pprovides IP geolocation and intelligence.
* <img src="https://www.google.com/s2/favicons?domain=www.ipchecking.com&sz=16" width="16" height="16"> [IP Checking](http://www.ipchecking.com)
* <img src="https://www.google.com/s2/favicons?domain=www.iplocation.net&sz=16" width="16" height="16"> [IP Location](https://www.iplocation.net) - is used for mapping of an IP address or MAC address to the real-world geographic location of an Internet-connected computing or a mobile device.
* <img src="https://www.google.com/s2/favicons?domain=iplocation.io&sz=16" width="16" height="16"> [IP Location.io](https://iplocation.io) - IPLocation.io allows you to check the location of an IP for free
* <img src="https://www.google.com/s2/favicons?domain=www.ipfingerprints.com&sz=16" width="16" height="16"> [IPFingerprints](http://www.ipfingerprints.com) - is used to find the approximate geographic location of an IP address along with some other useful information including ISP, TimeZone, Area Code, State.
* <img src="https://www.google.com/s2/favicons?domain=www.ipvoid.com&sz=16" width="16" height="16"> [IPVoid](http://www.ipvoid.com) - IP address toolset.
* <img src="https://www.google.com/s2/favicons?domain=www.isp.tools&sz=16" width="16" height="16"> [ISP.Tools](https://www.isp.tools) - Is a free platform offering network diagnostic tools (ping, traceroute, MTR, DNS, WHOIS, HTTP, etc.) tailored for ISPs and infrastructure professionals.
* <img src="https://www.google.com/s2/favicons?domain=www.kloth.net&sz=16" width="16" height="16"> [Kloth](http://www.kloth.net/services)
* <img src="https://www.google.com/s2/favicons?domain=majestic.com&sz=16" width="16" height="16"> [Majestic](https://majestic.com) - Find out who links to your website.
* [Mark Monitor WHOIS](https://whois-webform.markmonitor.com/whois/) - Displays domain registration information.
* <img src="https://www.google.com/s2/favicons?domain=www.maxmind.com&sz=16" width="16" height="16"> [MaxMind](https://www.maxmind.com)
* <img src="https://www.google.com/s2/favicons?domain=metadefender.com&sz=16" width="16" height="16"> [MetaDefender](https://metadefender.com) - Threat analysis service for URLs, files, certificates, domains, and suspicious hashes.
* <img src="https://www.google.com/s2/favicons?domain=toolbar.netcraft.com&sz=16" width="16" height="16"> [Netcraft Site Report](http://toolbar.netcraft.com/site_report?url=undefined#last_reboot) - is an online database that will provide you a report with detail information about a particular website and the history associated with it.
* <img src="https://www.google.com/s2/favicons?domain=www.openlinkprofiler.org&sz=16" width="16" height="16"> [OpenLinkProfiler](http://www.openlinkprofiler.org/)
* [PageGlimpse](http://www.pageglimpse.com)
* <img src="https://www.google.com/s2/favicons?domain=pentest-tools.com&sz=16" width="16" height="16"> [Pentest-Tools.com](https://pentest-tools.com/information-gathering/google-hacking) - uses advanced search operators (Google Dorks) to find juicy information about target websites.
* <img src="https://www.google.com/s2/favicons?domain=phishstats.info&sz=16" width="16" height="16"> [PhishStats](https://phishstats.info/)
* <img src="https://www.google.com/s2/favicons?domain=pulsedive.com&sz=16" width="16" height="16"> [Pulsedive](https://pulsedive.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ssllabs.com&sz=16" width="16" height="16"> [Qualys SSL Check](https://www.ssllabs.com/ssltest/) - SSL Test configuration compliance.
* <img src="https://www.google.com/s2/favicons?domain=www.quantcast.com&sz=16" width="16" height="16"> [Quantcast](https://www.quantcast.com)
* <img src="https://www.google.com/s2/favicons?domain=www.quicksprout.com&sz=16" width="16" height="16"> [Quick Sprout](https://www.quicksprout.com)
* <img src="https://www.google.com/s2/favicons?domain=redirectdetective.com&sz=16" width="16" height="16"> [RedirectDetective](http://redirectdetective.com)
* <img src="https://www.google.com/s2/favicons?domain=remote.12dt.com&sz=16" width="16" height="16"> [Remote DNS Lookup](https://remote.12dt.com)
* <img src="https://www.google.com/s2/favicons?domain=www.robtex.com&sz=16" width="16" height="16"> [Robtex](https://www.robtex.com) - is an IP address and domain name based researching websites that offers multiple services such as Reverse DNS Lookup, Whois, and AS Macros.
* <img src="https://www.google.com/s2/favicons?domain=sameid.net&sz=16" width="16" height="16"> [SameID](http://sameid.net)
* <img src="https://www.google.com/s2/favicons?domain=securitytrails.com&sz=16" width="16" height="16"> [SecurityTrails](https://securitytrails.com/dns-trails) - API to search current and historical DNS records, current and historical WHOIS, technologies used by sites and whois search for phone, email, address, IPs etc.
* <img src="https://www.google.com/s2/favicons?domain=subdomainradar.io&sz=16" width="16" height="16"> [SubDomainRadar.io](https://subdomainradar.io) - Fast subdomain finder with multiple search modes and the most extensive data sources, offering real-time notifications.
* <img src="https://www.google.com/s2/favicons?domain=www.semrush.com&sz=16" width="16" height="16"> [SEMrush](https://www.semrush.com)
* [SEO Chat Tools](http://tools.seochat.com)
* <img src="https://www.google.com/s2/favicons?domain=seotoolsforexcel.com&sz=16" width="16" height="16"> [SEOTools for Excel](http://seotoolsforexcel.com)
* <img src="https://www.google.com/s2/favicons?domain=www.similarweb.com&sz=16" width="16" height="16"> [Similar Web](https://www.similarweb.com) - Compare any website traffic statistics & analytics.
* <img src="https://www.google.com/s2/favicons?domain=smallseotools.com&sz=16" width="16" height="16"> [SmallSEOTools](http://smallseotools.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Squatm3gator](https://github.com/david3107/squatm3gator) - Enumerate available domains generated modifying the original domain name through different cybersquatting techniques
* <img src="https://www.google.com/s2/favicons?domain=www.statscrop.com&sz=16" width="16" height="16"> [StatsCrop](http://www.statscrop.com)
* [TinyScan](https://www.tiny-scan.com) - Another powerful URL scan tool that provides comprehensive information about any given URL. Get insights into IP address, location, screenshots, technology stack, performance metrics, and more.
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [TracerouteVisualizer](https://kriztalz.sh/traceroute-visualizer/) - An online tool that displays your mtr / traceroute / flyingroutes output on a map for visual analysis.
* <img src="https://www.google.com/s2/favicons?domain=urldna.io&sz=16" width="16" height="16"> [urlDNA](https://urldna.io/) -  Unleash website insights! urldna.io analyzes url, monitors brands and track phishing sites.
* <img src="https://www.google.com/s2/favicons?domain=urlhaus.abuse.ch&sz=16" width="16" height="16"> [URLhaus](https://urlhaus.abuse.ch) - URLhaus shares malicious URLs to combat malware and botnet threats
* <img src="https://www.google.com/s2/favicons?domain=urlquery.net&sz=16" width="16" height="16"> [urlQuery](http://urlquery.net)
* <img src="https://www.google.com/s2/favicons?domain=urlscan.io&sz=16" width="16" height="16"> [urlscan](https://urlscan.io/) -  is a free service to scan and analyse websites.
* <img src="https://www.google.com/s2/favicons?domain=www.urlvoid.com&sz=16" width="16" height="16"> [URLVoid](http://www.urlvoid.com) - Analyzes a website through multiple blacklist engines and online reputation tools to facilitate the detection of fraudulent and malicious websites.
* [Validin](https://app.validin.com/) - Website and API to search current and historical DNS records for free
* [Verisign](http://dnssec-debugger.verisignlabs.com)
* <img src="https://www.google.com/s2/favicons?domain=viewdns.info&sz=16" width="16" height="16"> [ViewDNS.info](http://viewdns.info)
* <img src="https://www.google.com/s2/favicons?domain=www.virustotal.com&sz=16" width="16" height="16"> [Virus Total](https://www.virustotal.com/) - Analyse suspicious domains, IPs URLs and files to detect malware and other breaches
* <img src="https://www.google.com/s2/favicons?domain=webboar.com.w3snoop.com&sz=16" width="16" height="16"> [w3snoop](http://webboar.com.w3snoop.com) - is a website that gives you a free and comprehensive report about a specific website.
* <img src="https://www.google.com/s2/favicons?domain=web-check.as93.net&sz=16" width="16" height="16"> [Web-Check](https://web-check.as93.net/) - All-in-one tool for viewing website and server meta data.
* <img src="https://www.google.com/s2/favicons?domain=webmeup.com&sz=16" width="16" height="16"> [WebMeUp](http://webmeup.com) - is the Web's freshest and fastest growing backlink index, and the primary source of backlink data for SEO PowerSuite.
* [Webscore](https://garvit835.github.io/WebScore/) - Enter a website URL to check its legitimacy.
* <img src="https://www.google.com/s2/favicons?domain=webscout.io&sz=16" width="16" height="16"> [Webscout](https://webscout.io/)  - A Swiss Army knife for scaled intelligence and metadata on IP addresses and domains.
* <img src="https://www.google.com/s2/favicons?domain=website.informer.com&sz=16" width="16" height="16"> [Website Informer](http://website.informer.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [WebsiteTechMiner.py](https://github.com/cybersader/WebsiteTechMiner-py) - automates gathering website profiling data into a CSV from the "BuiltWith" or "Wappalyzer" API for tech stack information, technographic data, website reports, website tech lookups, website architecture lookups, etc.
* <img src="https://www.google.com/s2/favicons?domain=whatismyipaddress.com&sz=16" width="16" height="16"> [WhatIsMyIPAddress](http://whatismyipaddress.com)
* <img src="https://www.google.com/s2/favicons?domain=who.is&sz=16" width="16" height="16"> [Who.is](https://who.is/) - Domain whois information.
* [Whois Arin Online](https://whois.arin.net) - is a web service for Whois data contained within ARIN's registration database
* <img src="https://www.google.com/s2/favicons?domain=www.whoishostingthis.com&sz=16" width="16" height="16"> [WhoIsHostingThis](http://www.whoishostingthis.com)
* <img src="https://www.google.com/s2/favicons?domain=www.whoismind.com&sz=16" width="16" height="16"> [WhoisMind](http://www.whoismind.com)
* <img src="https://www.google.com/s2/favicons?domain=whoisology.com&sz=16" width="16" height="16"> [Whoisology](https://whoisology.com)
* <img src="https://www.google.com/s2/favicons?domain=whoisrequest.com&sz=16" width="16" height="16"> [WhoIsRequest](http://whoisrequest.com)
* <img src="https://www.google.com/s2/favicons?domain=wigle.net&sz=16" width="16" height="16"> [WiGLE](https://wigle.net/) - Wi-fi "wardriving" database. Contains a global map containing crowdsourced information on the location, name, and other properties of wi-fi networks. Software available to download to contribute data to the public infoset.
* <img src="https://www.google.com/s2/favicons?domain=www.yougetsignal.com&sz=16" width="16" height="16"> [You Get Signal](http://www.yougetsignal.com)

## [↑](#-table-of-contents) 🔑 Keywords Discovery and Research

* <img src="https://www.google.com/s2/favicons?domain=adwords.google.com&sz=16" width="16" height="16"> [Google Adwords](http://adwords.google.com) - Get monthly keyword volume data and stats.
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Trends](https://www.google.com/trends) - See how many users are searching for specific keywords.
* <img src="https://www.google.com/s2/favicons?domain=www.keyworddiscovery.com&sz=16" width="16" height="16"> [Keyword Discovery](http://www.keyworddiscovery.com)
* <img src="https://www.google.com/s2/favicons?domain=www.keywordspy.com&sz=16" width="16" height="16"> [Keyword Spy](http://www.keywordspy.com)
* <img src="https://www.google.com/s2/favicons?domain=keywordtool.io&sz=16" width="16" height="16"> [KeywordTool](http://keywordtool.io)
* <img src="https://www.google.com/s2/favicons?domain=www.onelook.com&sz=16" width="16" height="16"> [One Look Reverse Dictionary](http://www.onelook.com/reverse-dictionary.shtml)
* <img src="https://www.google.com/s2/favicons?domain=www.soovle.com&sz=16" width="16" height="16"> [Soovle](http://www.soovle.com)
* <img src="https://www.google.com/s2/favicons?domain=ubersuggest.org&sz=16" width="16" height="16"> [Ubersuggest](http://ubersuggest.org)
* <img src="https://www.google.com/s2/favicons?domain=www.wordtracker.com&sz=16" width="16" height="16"> [Word Tracker](https://www.wordtracker.com)
* <img src="https://www.google.com/s2/favicons?domain=wordstat.yandex.com&sz=16" width="16" height="16"> [Yandex Wordstat](https://wordstat.yandex.com)

## [↑](#-table-of-contents) ⏳ Web History and Website Capture

* <img src="https://www.google.com/s2/favicons?domain=archive.is&sz=16" width="16" height="16"> [Archive.is](http://archive.is) - is a website that allows you to archive a snapshot of you websites that will always remains online evenif the original page disappears.
* <img src="https://www.google.com/s2/favicons?domain=softbytelabs.com&sz=16" width="16" height="16"> [BlackWidow](http://softbytelabs.com/wp/blackwidow/)
* <img src="https://www.google.com/s2/favicons?domain=www.cachedpages.com&sz=16" width="16" height="16"> [CashedPages](http://www.cachedpages.com)
* [CachedView](http://cachedview.com)
* <img src="https://www.google.com/s2/favicons?domain=stored.website&sz=16" width="16" height="16"> [stored.website](https://stored.website)
* <img src="https://www.google.com/s2/favicons?domain=archive.org&sz=16" width="16" height="16"> [Wayback Machine](http://archive.org/web/web.php) - Explore the history of a website.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Wayback Machine Archiver](https://github.com/jsvine/waybackpack)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [waybackpy](https://github.com/akamhy/waybackpy) - Python package & CLI tool that interfaces the Wayback Machine APIs.

## [↑](#-table-of-contents) 🗣️ Language Tools

* see the [Awesome Translations list](https://github.com/mbiesiad/awesome-translations#tools)

## [↑](#-table-of-contents) 🖼️ Image Search

* <img src="https://www.google.com/s2/favicons?domain=image.baidu.com&sz=16" width="16" height="16"> [Baidu Images](https://image.baidu.com)
* [Betaface](https://www.betaface.com/demo.html)
* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing Images](https://www.bing.com/images)
* <img src="https://www.google.com/s2/favicons?domain=clarify.io&sz=16" width="16" height="16"> [Clarify](https://clarify.io)
* <img src="https://www.google.com/s2/favicons?domain=www.duplichecker.com&sz=16" width="16" height="16"> [Dupli Checker](https://www.duplichecker.com/reverse-image-search.php) - You can search for an image by uploading + with URL or typing the keyword or any word you want to explore related to images.
* <img src="https://www.google.com/s2/favicons?domain=facecheck.id&sz=16" width="16" height="16"> [FaceCheck.ID](https://facecheck.id) - Facial recognition search engine.
* [Faceagle](https://faceagle.com/) - Faceagle is a face recognition search engine.
* <img src="https://www.google.com/s2/favicons?domain=flickr.com&sz=16" width="16" height="16"> [Flickr](https://flickr.com/search/)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [GeoSpyer](https://github.com/atiilla/geospy "Original service: https://geospy.web.app/") - Python tool using Graylark's AI-powered geo-location service to uncover the location where photos were taken.
* <img src="https://www.google.com/s2/favicons?domain=images.google.com&sz=16" width="16" height="16"> [Google Image](https://images.google.com)
* <img src="https://www.google.com/s2/favicons?domain=lens.google.com&sz=16" width="16" height="16"> [Google Lens](https://lens.google.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.imageidentify.com&sz=16" width="16" height="16"> [Image Identification Project](https://www.imageidentify.com)
* [Image Raider](https://www.imageraider.com) - is our reverse image search tool for completing individual searches. When you upload an image to this page, we'll scour the internet to find its source and all of the other pages where it has been posted.
* <img src="https://www.google.com/s2/favicons?domain=kartavision.com&sz=16" width="16" height="16"> [KartaVision](https://kartavision.com/) - search engine for KartaView imagery. It supports natural-language search and search by image
* <img src="https://www.google.com/s2/favicons?domain=lenso.ai&sz=16" width="16" height="16"> [Lenso.ai](https://lenso.ai) - Reverse image search tool with facial recognition, created for finding people, similar images, copies of photos, identical places and more.
* <img src="https://www.google.com/s2/favicons?domain=search.lycos.com&sz=16" width="16" height="16"> [Lycos Image Search](https://search.lycos.com)
* <img src="https://www.google.com/s2/favicons?domain=photobucket.com&sz=16" width="16" height="16"> [PhotoBucket](https://photobucket.com)
* <img src="https://www.google.com/s2/favicons?domain=www.pictriev.com&sz=16" width="16" height="16"> [PicTriev](http://www.pictriev.com) - a face search engine.
* <img src="https://www.google.com/s2/favicons?domain=pimeyes.com&sz=16" width="16" height="16"> [PimEyes](https://pimeyes.com) - an online face search engine that goes through the Internet to find pictures containing given faces.
* <img src="https://www.google.com/s2/favicons?domain=www.pixsy.com&sz=16" width="16" height="16"> [Pixsy](https://www.pixsy.com/) - Take back control of your images. See where & how your images are being used online!
* <img src="https://www.google.com/s2/favicons?domain=search4faces.com&sz=16" width="16" height="16"> [Search4faces](https://search4faces.com/) - a service for searching people on the Internet by photo.
* <img src="https://www.google.com/s2/favicons?domain=surfface.com&sz=16" width="16" height="16"> [Surfface](https://surfface.com) - face search and people finder indexing social profiles and public images from social media and the web.
* <img src="https://www.google.com/s2/favicons?domain=tineye.com&sz=16" width="16" height="16"> [TinEye](https://tineye.com) - Reverse image search engine.
* <img src="https://www.google.com/s2/favicons?domain=images.search.yahoo.com&sz=16" width="16" height="16"> [Yahoo Image Search](https://images.search.yahoo.com)
* <img src="https://www.google.com/s2/favicons?domain=www.yandex.com&sz=16" width="16" height="16"> [Yandex Images](https://www.yandex.com/images)

## [↑](#-table-of-contents) 🔬 Image Analysis

* <img src="https://www.google.com/s2/favicons?domain=www.diffchecker.com&sz=16" width="16" height="16"> [DiffChecker](https://www.diffchecker.com/image-diff/)
* <img src="https://www.google.com/s2/favicons?domain=exifeditor.io&sz=16" width="16" height="16"> [EXIFEditor.io](https://exifeditor.io) - In-browser EXIF image metadata editor, viewer, and analysis tool.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [ExifLooter](https://github.com/aydinnyunus/exiflooter)
* [ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool)
* <img src="https://www.google.com/s2/favicons?domain=29a.ch&sz=16" width="16" height="16"> [Forensically](https://29a.ch/photo-forensics/)
* [FotoForensics](http://www.fotoforensics.com)
* <img src="https://www.google.com/s2/favicons?domain=geospy.web.app&sz=16" width="16" height="16"> [GeoSpy](https://geospy.web.app/) - AI based image osint tool
* [ImgOps](https://imgops.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.impulseadventure.com&sz=16" width="16" height="16"> [ImpulseAdventure](http://www.impulseadventure.com/photo/jpeg-snoop.html)
* [Jeffreys Image Metadata Viewer](http://exif.regex.info/)
* <img src="https://www.google.com/s2/favicons?domain=jimpl.com&sz=16" width="16" height="16"> [JIMPL](https://jimpl.com/) - Online EXIF data viewer
* <img src="https://www.google.com/s2/favicons?domain=sourceforge.net&sz=16" width="16" height="16"> [JPEGsnoop](https://sourceforge.net/projects/jpegsnoop)
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [Metadata Viewer](https://kriztalz.sh/metadata-viewer/) - Online EXIF data viewer.
* <img src="https://www.google.com/s2/favicons?domain=profileimageintel.com&sz=16" width="16" height="16"> [ProfileImageIntel](https://profileimageintel.com/) - Social media and WhatsApp profile image tool to find when a profile image was uploaded.

## [↑](#-table-of-contents) 🎥 Video Search and Other Video Tools

* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing Videos](http://www.bing.com/?scope=video)
* <img src="https://www.google.com/s2/favicons?domain=clarify.io&sz=16" width="16" height="16"> [Clarify](http://clarify.io)
* <img src="https://www.google.com/s2/favicons?domain=www.clipblast.com&sz=16" width="16" height="16"> [Clip Blast](http://www.clipblast.com)
* <img src="https://www.google.com/s2/favicons?domain=www.dailymotion.com&sz=16" width="16" height="16"> [DailyMotion](http://www.dailymotion.com)
* <img src="https://www.google.com/s2/favicons?domain=deturl.com&sz=16" width="16" height="16"> [Deturl](http://deturl.com) - Download a YouTube video from any web page.
* <img src="https://www.google.com/s2/favicons?domain=www.downloadhelper.net&sz=16" width="16" height="16"> [DownloadHelper](http://www.downloadhelper.net) - Download any video from any websites, it just works!
* <img src="https://www.google.com/s2/favicons?domain=www.earthcam.com&sz=16" width="16" height="16"> [Earthcam](http://www.earthcam.com) - EarthCam is the leading network of live streaming webcams for tourism and entertainment.
* <img src="https://www.google.com/s2/favicons?domain=filmot.com&sz=16" width="16" height="16"> [Filmot](https://filmot.com/) - Search within YouTube subtitles. Indexing over 573 million captions across 528 million videos and 45 million channels.
* [Find YouTube Video](https://findyoutubevideo.thetechrobo.ca/) - Searches currently 5 YouTube archives for specific videos by ID, which is really useful for finding deleted or private YouTube videos.
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [Frame by Frame](https://chrome.google.com/webstore/detail/frame-by-frame/cclnaabdfgnehogonpeddbgejclcjneh/) - Browser plugin that allows you to watch YouTube videos frame by frame.
* [Geosearch](http://www.geosearchtool.com)
* <img src="https://www.google.com/s2/favicons?domain=insecam.org&sz=16" width="16" height="16"> [Insecam](http://insecam.org/) - Live cameras directory
* <img src="https://www.google.com/s2/favicons?domain=archive.org&sz=16" width="16" height="16"> [Internet Archive: Open Source Videos](https://archive.org/details/opensource_movies)
* [Metacafe](http://www.metacafe.com)
* <img src="https://www.google.com/s2/favicons?domain=www.metatube.com&sz=16" width="16" height="16"> [Metatube](http://www.metatube.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Tubuep](https://github.com/bibanon/tubeup) - Downloads online videos via yt-dlp, then reuploads them to the Internet Archive for preservation. Note: if you would like to archive comments too, you need to install version 0.0.33 and use the --get-comments flag, however you will still have the new yt-dlp fixes and features, but existing tubeup bugs cannot be fixed, unless you do manual work.
* <img src="https://www.google.com/s2/favicons?domain=www.veoh.com&sz=16" width="16" height="16"> [Veoh](http://www.veoh.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Video Stabilization Methods](https://github.com/yaochih/awesome-video-stabilization)
* <img src="https://www.google.com/s2/favicons?domain=vimeo.com&sz=16" width="16" height="16"> [Vimeo](https://vimeo.com)
* <img src="https://www.google.com/s2/favicons?domain=video.search.yahoo.com&sz=16" width="16" height="16"> [Yahoo Video Search](http://video.search.yahoo.com)
* <img src="https://www.google.com/s2/favicons?domain=mattw.io&sz=16" width="16" height="16"> [YouTube Geofind](https://mattw.io/youtube-geofind/)
* <img src="https://www.google.com/s2/favicons?domain=mattw.io&sz=16" width="16" height="16"> [YouTube Metadata](https://mattw.io/youtube-metadata/)
* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [YouTube](https://www.youtube.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [yt-dlp](https://github.com/yt-dlp/yt-dlp/) - Downloads videos from almost any online platform, along with information, thumbnails, subtitles, descriptions, and comments (comments only on a select few sites like Youtube and a few small sites). If a site is not supported, or a useful or crucial piece of metadata, including comments, is missing, create an issue.

## [↑](#-table-of-contents) 📚 Academic Resources and Grey Literature

* <img src="https://www.google.com/s2/favicons?domain=www.academia.edu&sz=16" width="16" height="16"> [Academia](https://www.academia.edu)
* [Academic Journals](http://www.academicjournals.org)
* <img src="https://www.google.com/s2/favicons?domain=www.ajol.info&sz=16" width="16" height="16"> [African Journal Online](http://www.ajol.info) -  is the world's largest and preeminent platform of African-published scholarly journals
* <img src="https://www.google.com/s2/favicons?domain=ascelibrary.org&sz=16" width="16" height="16"> [American Society of Civil Engineers](http://ascelibrary.org)
* [Base](http://www.base-search.net)
* <img src="https://www.google.com/s2/favicons?domain=www.bibsonomy.org&sz=16" width="16" height="16"> [Bibsonomy](http://www.bibsonomy.org)
* <img src="https://www.google.com/s2/favicons?domain=core.ac.uk&sz=16" width="16" height="16"> [Core](https://core.ac.uk/search)
* <img src="https://www.google.com/s2/favicons?domain=www.elsevier.com&sz=16" width="16" height="16"> [Elsevier](https://www.elsevier.com)
* <img src="https://www.google.com/s2/favicons?domain=scholar.google.com&sz=16" width="16" height="16"> [Google Scholar](https://scholar.google.com)
* <img src="https://www.google.com/s2/favicons?domain=greyguide.isti.cnr.it&sz=16" width="16" height="16"> [Grey Guide](http://greyguide.isti.cnr.it)
* [Grey Literature Strategies](http://greylitstrategies.info)
* <img src="https://www.google.com/s2/favicons?domain=csulb.libguides.com&sz=16" width="16" height="16"> [Grey Literature – List of Gateways](http://csulb.libguides.com/graylit)
* <img src="https://www.google.com/s2/favicons?domain=www.greynet.org&sz=16" width="16" height="16"> [GreyNet International](http://www.greynet.org)
* [HighWire: Free Online Full-text Articles](http://highwire.stanford.edu/lists/freeart.dtl)
* [Journal Guide](https://www.journalguide.com)
* <img src="https://www.google.com/s2/favicons?domain=journalseek.net&sz=16" width="16" height="16"> [Journal Seek](http://journalseek.net)
* <img src="https://www.google.com/s2/favicons?domain=www.jstor.org&sz=16" width="16" height="16"> [JSTOR](http://www.jstor.org) - Search over 10 million academic journal articles, books, and primary sources.
* [Lazy Scholar](http://www.lazyscholar.org)
* <img src="https://www.google.com/s2/favicons?domain=www.tib.eu&sz=16" width="16" height="16"> [Leibniz Information Centre For Science and Technology University Library](https://www.tib.eu/en/search-discover/) - indexes all reports of German publicly funded projects and many scientific papers.
* [Microsoft Academic](http://academic.research.microsoft.com)
* <img src="https://www.google.com/s2/favicons?domain=www.nrcresearchpress.com&sz=16" width="16" height="16"> [NRC Research Press](http://www.nrcresearchpress.com)
* <img src="https://www.google.com/s2/favicons?domain=oa.mg&sz=16" width="16" height="16"> [OA.mg](http://oa.mg) A database of over 240 million scientific works, with PDFs for all Open Access papers in their catalogue (~ 40 million)
* [Open Access Scientific Journals](http://www.pagepress.org)
* <img src="https://www.google.com/s2/favicons?domain=www.opengrey.eu&sz=16" width="16" height="16"> [Open Grey](http://www.opengrey.eu)
* [Oxford Journals](http://www.oxfordjournals.org)
* <img src="https://www.google.com/s2/favicons?domain=www.ncbi.nlm.nih.gov&sz=16" width="16" height="16"> [PubMed](http://www.ncbi.nlm.nih.gov/pubmed) - Search more than 27 millions citations for biomedical literature from MEDLINE, life science journals, and online books.
* [Quetzal Search](https://www.quetzal-search.info)
* <img src="https://www.google.com/s2/favicons?domain=www.researchgate.net&sz=16" width="16" height="16"> [Research Gate](http://www.researchgate.net)
* <img src="https://www.google.com/s2/favicons?domain=online.sagepub.com&sz=16" width="16" height="16"> [SAGE Journals](http://online.sagepub.com)
* <img src="https://www.google.com/s2/favicons?domain=www.thescipub.com&sz=16" width="16" height="16"> [Science Publications](http://www.thescipub.com)
* <img src="https://www.google.com/s2/favicons?domain=www.sciencedirect.com&sz=16" width="16" height="16"> [ScienceDirect](http://www.sciencedirect.com)
* [ScienceDomain](http://www.sciencedomain.org)
* <img src="https://www.google.com/s2/favicons?domain=www.scirp.org&sz=16" width="16" height="16"> [SCIRP](http://www.scirp.org)
* <img src="https://www.google.com/s2/favicons?domain=link.springer.com&sz=16" width="16" height="16"> [Springer](http://link.springer.com)
* <img src="https://www.google.com/s2/favicons?domain=www.tandfonline.com&sz=16" width="16" height="16"> [Taylor & Francis Online](http://www.tandfonline.com)
* <img src="https://www.google.com/s2/favicons?domain=opensyllabusproject.org&sz=16" width="16" height="16"> [The Open Syllabus Project](http://opensyllabusproject.org/)
* [Wiley](http://eu.wiley.com)
* <img src="https://www.google.com/s2/favicons?domain=www.wdl.org&sz=16" width="16" height="16"> [World Digital Library](http://www.wdl.org)
* <img src="https://www.google.com/s2/favicons?domain=worldwidescience.org&sz=16" width="16" height="16"> [World Science](http://worldwidescience.org)
* [Zetoc](http://zetoc.jisc.ac.uk)


## [↑](#-table-of-contents) 🌍 Geospatial Research and Mapping Tools

* <img src="https://www.google.com/s2/favicons?domain=apify.com&sz=16" width="16" height="16"> [Apify's Google Maps Scraper](https://apify.com/compass/crawler-google-places)
* <img src="https://www.google.com/s2/favicons?domain=livingatlas.arcgis.com&sz=16" width="16" height="16"> [ArcGIS](https://livingatlas.arcgis.com/en/browse/)
* <img src="https://www.google.com/s2/favicons?domain=atlas.co&sz=16" width="16" height="16"> [Atlas](https://atlas.co)
* [Atlasify](http://www.atlasify.com)
* <img src="https://www.google.com/s2/favicons?domain=map.baidu.com&sz=16" width="16" height="16"> [Baidu Maps](https://map.baidu.com/)
* <img src="https://www.google.com/s2/favicons?domain=batchgeo.com&sz=16" width="16" height="16"> [Batchgeo](http://batchgeo.com)
* [Beholder](https://beholder.me) - Real-time global OSINT threat map aggregating aircraft, vessel, and satellite tracking with natural disaster, conflict, and environmental data on an interactive 3D globe.
* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing Maps](http://www.bing.com/maps)
* <img src="https://www.google.com/s2/favicons?domain=cartodb.com&sz=16" width="16" height="16"> [CartoDB](https://cartodb.com)
* <img src="https://www.google.com/s2/favicons?domain=colorbrewer2.org&sz=16" width="16" height="16"> [Colorbrewer](http://colorbrewer2.org)
* <img src="https://www.google.com/s2/favicons?domain=crowdmap.com&sz=16" width="16" height="16"> [CrowdMap](https://crowdmap.com)
* [CTLRQ Address Lookup](https://ctrlq.org/maps/address)
* <img src="https://www.google.com/s2/favicons?domain=www.digikam.org&sz=16" width="16" height="16"> [digiKam](https://www.digikam.org/)
* <img src="https://www.google.com/s2/favicons?domain=dominoc925-pages.appspot.com&sz=16" width="16" height="16"> [Dominoc925](https://dominoc925-pages.appspot.com/mapplets/cs_mgrs.html)
* <img src="https://www.google.com/s2/favicons?domain=www.mapchannels.com&sz=16" width="16" height="16"> [DualMaps](https://www.mapchannels.com/dualmaps7/map.htm)
* <img src="https://www.google.com/s2/favicons?domain=www.esri.com&sz=16" width="16" height="16"> [Esri](http://www.esri.com)
* <img src="https://www.google.com/s2/favicons?domain=www.flashearth.com&sz=16" width="16" height="16"> [Flash Earth](http://www.flashearth.com)
* <img src="https://www.google.com/s2/favicons?domain=geogig.org&sz=16" width="16" height="16"> [GeoGig](http://geogig.org)
* <img src="https://www.google.com/s2/favicons?domain=geoinfer.com&sz=16" width="16" height="16"> [GeoInfer](https://geoinfer.com) - Image geolocation tool, no EXIF data required.
* <img src="https://www.google.com/s2/favicons?domain=geoguessr.ai&sz=16" width="16" height="16"> [GeoGuessr.ai](https://geoguessr.ai) - AI-powered geolocation tool for identifying locations from images.
* <img src="https://www.google.com/s2/favicons?domain=www.geonames.org&sz=16" width="16" height="16"> [GeoNames](http://www.geonames.org)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Earth Pro](https://www.google.com/intl/en/earth/versions/#earth-pro)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Earth](http://www.google.com/earth)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Maps](https://www.google.com/maps)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google My Maps](https://www.google.com/maps/about/mymaps)
* <img src="https://www.google.com/s2/favicons?domain=www.gpsvisualizer.com&sz=16" width="16" height="16"> [GPSVisualizer](http://www.gpsvisualizer.com)
* <img src="https://www.google.com/s2/favicons?domain=grass.osgeo.org&sz=16" width="16" height="16"> [GrassGIS](http://grass.osgeo.org)
* <img src="https://www.google.com/s2/favicons?domain=here.com&sz=16" width="16" height="16"> [Here](http://here.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Hyperlapse](https://github.com/TeehanLax/Hyperlapse.js)
* [Inspire Geoportal](http://inspire-geoportal.ec.europa.eu)
* <img src="https://www.google.com/s2/favicons?domain=www.instantstreetview.com&sz=16" width="16" height="16"> [Instant Google Street View](http://www.instantstreetview.com)
* <img src="https://www.google.com/s2/favicons?domain=www.instantatlas.com&sz=16" width="16" height="16"> [InstantAtlas](http://www.instantatlas.com)
* <img src="https://www.google.com/s2/favicons?domain=kartaview.org&sz=16" width="16" height="16"> [KartaView](https://kartaview.org/map/)
* [Kartograph](http://kartograph.org)
* <img src="https://www.google.com/s2/favicons?domain=leafletjs.com&sz=16" width="16" height="16"> [Leaflet](http://leafletjs.com)
* <img src="https://www.google.com/s2/favicons?domain=liveuamap.com&sz=16" width="16" height="16"> [Liveuamap](https://liveuamap.com/)
* <img src="https://www.google.com/s2/favicons?domain=maps.co&sz=16" width="16" height="16"> [Map Maker](https://maps.co)
* <img src="https://www.google.com/s2/favicons?domain=mapalist.com&sz=16" width="16" height="16"> [MapAList](http://mapalist.com)
* <img src="https://www.google.com/s2/favicons?domain=www.mapbox.com&sz=16" width="16" height="16"> [MapBox](https://www.mapbox.com)
* <img src="https://www.google.com/s2/favicons?domain=mapchart.net&sz=16" width="16" height="16"> [Mapchart.net](https://mapchart.net)
* <img src="https://www.google.com/s2/favicons?domain=www.mapchecking.com&sz=16" width="16" height="16"> [MapChecking](https://www.mapchecking.com/)
* [Maperitive](http://maperitive.net)
* <img src="https://www.google.com/s2/favicons?domain=maphub.net&sz=16" width="16" height="16"> [MapHub](https://maphub.net)
* <img src="https://www.google.com/s2/favicons?domain=www.mapillary.com&sz=16" width="16" height="16"> [Mapillary](https://www.mapillary.com/app/)
* <img src="https://www.google.com/s2/favicons?domain=mapjam.com&sz=16" width="16" height="16"> [MapJam](http://mapjam.com)
* <img src="https://www.google.com/s2/favicons?domain=mapline.com&sz=16" width="16" height="16"> [Mapline](https://mapline.com)
* <img src="https://www.google.com/s2/favicons?domain=www.mapquest.com&sz=16" width="16" height="16"> [Mapquest](https://www.mapquest.com)
* <img src="https://www.google.com/s2/favicons?domain=modestmaps.com&sz=16" width="16" height="16"> [Modest Maps](http://modestmaps.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [NGA GEOINT](https://github.com/ngageoint)
* <img src="https://www.google.com/s2/favicons?domain=www.openstreetmap.org&sz=16" width="16" height="16"> [Open Street Map](http://www.openstreetmap.org)
* <img src="https://www.google.com/s2/favicons?domain=openlayers.org&sz=16" width="16" height="16"> [OpenLayers](http://openlayers.org)
* <img src="https://www.google.com/s2/favicons?domain=www.lib.utexas.edu&sz=16" width="16" height="16"> [Perry Castaneda Library](https://www.lib.utexas.edu/maps)
* <img src="https://www.google.com/s2/favicons?domain=www.pic2map.com&sz=16" width="16" height="16"> [Pic2Map](https://www.pic2map.com/)
* [Polymaps](http://polymaps.org)
* <img src="https://www.google.com/s2/favicons?domain=qgis.org&sz=16" width="16" height="16"> [QGIS](http://qgis.org)
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [QuickMaps](https://chrome.google.com/webstore/detail/quick-maps/bgbojmobaekecckmomemopckmeipecij)
* <img src="https://www.google.com/s2/favicons?domain=www.sasgis.org&sz=16" width="16" height="16"> [SAS Planet](http://www.sasgis.org/sasplaneta/)  - Software used to view, download and stitch satellite images.
* <img src="https://www.google.com/s2/favicons?domain=satellites.pro&sz=16" width="16" height="16"> [Satellites Pro](https://satellites.pro/)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [SatIntel](https://github.com/ANG13T/SatIntel)
* <img src="https://www.google.com/s2/favicons?domain=scribblemaps.com&sz=16" width="16" height="16"> [Scribble Maps](http://scribblemaps.com)
* <img src="https://www.google.com/s2/favicons?domain=www.sentinel-hub.com&sz=16" width="16" height="16"> [Sentinel Hub](https://www.sentinel-hub.com/explore/sentinelplayground/)
* <img src="https://www.google.com/s2/favicons?domain=soar.earth&sz=16" width="16" height="16"> [SOAR](https://soar.earth/)
* <img src="https://www.google.com/s2/favicons?domain=storymaps.arcgis.com&sz=16" width="16" height="16"> [StoryMaps](http://storymaps.arcgis.com/en)
* <img src="https://www.google.com/s2/favicons?domain=www.suncalc.org&sz=16" width="16" height="16"> [SunCalc](https://www.suncalc.org/)
* <img src="https://www.google.com/s2/favicons?domain=www.tableausoftware.com&sz=16" width="16" height="16"> [Tableau](http://www.tableausoftware.com)
* <img src="https://www.google.com/s2/favicons?domain=earthexplorer.usgs.gov&sz=16" width="16" height="16"> [USGS (EarthExplorer)](https://earthexplorer.usgs.gov/)
* <img src="https://www.google.com/s2/favicons?domain=www.viamichelin.com&sz=16" width="16" height="16"> [ViaMichelin](http://www.viamichelin.com)
* <img src="https://www.google.com/s2/favicons?domain=www.mgmaps.com&sz=16" width="16" height="16"> [View in Google Earth](http://www.mgmaps.com/kml/#view)
* <img src="https://www.google.com/s2/favicons?domain=wikimapia.org&sz=16" width="16" height="16"> [Wikimapia](http://wikimapia.org)
* <img src="https://www.google.com/s2/favicons?domain=www.windy.com&sz=16" width="16" height="16"> [Windy](https://www.windy.com/)
* <img src="https://www.google.com/s2/favicons?domain=worldmap.harvard.edu&sz=16" width="16" height="16"> [WorldMap Harvard](http://worldmap.harvard.edu)
* [Worldwide OSINT Tools Map](https://cipher387.github.io/osintmap/) - A global map of databases and OSINT sources by applicable location.
* <img src="https://www.google.com/s2/favicons?domain=maps.yahoo.com&sz=16" width="16" height="16"> [Yahoo Maps](https://maps.yahoo.com)
* <img src="https://www.google.com/s2/favicons?domain=www.zeemaps.com&sz=16" width="16" height="16"> [Zeemaps](https://www.zeemaps.com)
* <img src="https://www.google.com/s2/favicons?domain=zoom.earth&sz=16" width="16" height="16"> [Zoom Earth](https://zoom.earth/)

## [↑](#-table-of-contents) 📰 News

* <img src="https://www.google.com/s2/favicons?domain=www.1stheadlines.com&sz=16" width="16" height="16"> [1st Headlines](http://www.1stheadlines.com)
* <img src="https://www.google.com/s2/favicons?domain=www.abyznewslinks.com&sz=16" width="16" height="16"> [ABYZNewsLinks](http://www.abyznewslinks.com)
* <img src="https://www.google.com/s2/favicons?domain=www.afp.com&sz=16" width="16" height="16"> [Agence France-Presse (AFP)](http://www.afp.com)
* <img src="https://www.google.com/s2/favicons?domain=www.allyoucanread.com&sz=16" width="16" height="16"> [AllYouCanRead](http://www.allyoucanread.com)
* [AP](http://hosted.ap.org)
* <img src="https://www.google.com/s2/favicons?domain=www.bbc.co.uk&sz=16" width="16" height="16"> [BBC News](http://www.bbc.co.uk/news)
* <img src="https://www.google.com/s2/favicons?domain=www.bing.com&sz=16" width="16" height="16"> [Bing News](http://www.bing.com/news)
* <img src="https://www.google.com/s2/favicons?domain=edition.cnn.com&sz=16" width="16" height="16"> [CNN](http://edition.cnn.com)
* [Cyber Alert](http://www.cyberalert.com)
* [DailyEarth](http://dailyearth.com)
* [DPA International](http://www.dpa-international.com)
* <img src="https://www.google.com/s2/favicons?domain=www.euronews.com&sz=16" width="16" height="16"> [Euronews](http://www.euronews.com)
* <img src="https://www.google.com/s2/favicons?domain=www.dowjones.com&sz=16" width="16" height="16"> [Factiva](http://www.dowjones.com/factiva)
* <img src="https://www.google.com/s2/favicons?domain=www.france24.com&sz=16" width="16" height="16"> [France24](http://www.france24.com)
* <img src="https://www.google.com/s2/favicons?domain=news.google.com&sz=16" width="16" height="16"> [Google News](https://news.google.com)
* <img src="https://www.google.com/s2/favicons?domain=news.google.com&sz=16" width="16" height="16"> [Google News Print Archive](http://news.google.com/newspapers)
* [HeadlineSpot](http://www.headlinespot.com)
* <img src="https://www.google.com/s2/favicons?domain=www.itar-tass.com&sz=16" width="16" height="16"> [Itar-Tass](http://www.itar-tass.com)
* <img src="https://www.google.com/s2/favicons?domain=www.listofnewspapers.com&sz=16" width="16" height="16"> [List of Newspapers.com](http://www.listofnewspapers.com)
* <img src="https://www.google.com/s2/favicons?domain=www.magportal.com&sz=16" width="16" height="16"> [MagPortal](http://www.magportal.com)
* <img src="https://www.google.com/s2/favicons?domain=newsmap.jp&sz=16" width="16" height="16"> [News Map](http://newsmap.jp)
* <img src="https://www.google.com/s2/favicons?domain=www.newsnow.co.uk&sz=16" width="16" height="16"> [News Now](http://www.newsnow.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=www.newseum.org&sz=16" width="16" height="16"> [Newseum - Today Front Pages](http://www.newseum.org/todaysfrontpages)
* <img src="https://www.google.com/s2/favicons?domain=www.newslink.org&sz=16" width="16" height="16"> [Newslink](http://www.newslink.org)
* [NewsLookup](http://www.newslookup.com)
* [Newspaper Map](http://newspapermap.com)
* <img src="https://www.google.com/s2/favicons?domain=www.newspaperindex.com&sz=16" width="16" height="16"> [Newspaperindex](http://www.newspaperindex.com)
* <img src="https://www.google.com/s2/favicons?domain=www.newspapers.com&sz=16" width="16" height="16"> [Newspapers.com](http://www.newspapers.com)
* <img src="https://www.google.com/s2/favicons?domain=www.newswhip.com&sz=16" width="16" height="16"> [NewsWhip](http://www.newswhip.com)
* <img src="https://www.google.com/s2/favicons?domain=www.onlinenewspapers.com&sz=16" width="16" height="16"> [OnlineNewspapers](http://www.onlinenewspapers.com)
* <img src="https://www.google.com/s2/favicons?domain=www.thepaperboy.com&sz=16" width="16" height="16"> [Paperboy](http://www.thepaperboy.com)
* <img src="https://www.google.com/s2/favicons?domain=www.prnewswire.com&sz=16" width="16" height="16"> [PR Newswire](http://www.prnewswire.com)
* <img src="https://www.google.com/s2/favicons?domain=www.pressreader.com&sz=16" width="16" height="16"> [Press Reader](http://www.pressreader.com)
* <img src="https://www.google.com/s2/favicons?domain=www.reuters.com&sz=16" width="16" height="16"> [Reuters](http://www.reuters.com)
* <img src="https://www.google.com/s2/favicons?domain=www.silobreaker.com&sz=16" width="16" height="16"> [Silobreaker](http://www.silobreaker.com)
* <img src="https://www.google.com/s2/favicons?domain=www.topix.com&sz=16" width="16" height="16"> [Topix](http://www.topix.com)
* <img src="https://www.google.com/s2/favicons?domain=wn.com&sz=16" width="16" height="16"> [WorldNews](http://wn.com)
* <img src="https://www.google.com/s2/favicons?domain=www.world-newspapers.com&sz=16" width="16" height="16"> [World-Newspapers](http://www.world-newspapers.com)
* <img src="https://www.google.com/s2/favicons?domain=news.yahoo.com&sz=16" width="16" height="16"> [Yahoo News](http://news.yahoo.com)

## [↑](#-table-of-contents) 📡 News Digest and Discovery Tools

* [Flipboard](https://flipboard.com)
* <img src="https://www.google.com/s2/favicons?domain=www.inshorts.com&sz=16" width="16" height="16"> [Inshorts](https://www.inshorts.com)
* <img src="https://www.google.com/s2/favicons?domain=newsinshorts.com&sz=16" width="16" height="16"> [Newsinshorts](http://newsinshorts.com)
* [Nod](http://get-nod.com)
* [Reeder](http://reederapp.com)
* <img src="https://www.google.com/s2/favicons?domain=www.newswhip.com&sz=16" width="16" height="16"> [Spike](http://www.newswhip.com)
* <img src="https://www.google.com/s2/favicons?domain=storyful.com&sz=16" width="16" height="16"> [Storyful](http://storyful.com)
* <img src="https://www.google.com/s2/favicons?domain=www.superdesk.org&sz=16" width="16" height="16"> [Superdesk](https://www.superdesk.org)
* <img src="https://www.google.com/s2/favicons?domain=trooclick.com&sz=16" width="16" height="16"> [Trooclick](http://trooclick.com)

## [↑](#-table-of-contents) ✅ Fact Checking


* <img src="https://www.google.com/s2/favicons?domain=captainfact.io&sz=16" width="16" height="16"> [Captin Fact](https://captainfact.io/)
* <img src="https://www.google.com/s2/favicons?domain=meedan.com&sz=16" width="16" height="16"> [Check](https://meedan.com/check)
* [Emergent](http://www.emergent.info)
* <img src="https://www.google.com/s2/favicons?domain=www.factcheck.org&sz=16" width="16" height="16"> [Fact Check](http://www.factcheck.org)
* <img src="https://www.google.com/s2/favicons?domain=fullfact.org&sz=16" width="16" height="16"> [Full Fact](https://fullfact.org)
* <img src="https://www.google.com/s2/favicons?domain=www.snopes.com&sz=16" width="16" height="16"> [Snopes](http://www.snopes.com) - The definitive Internet reference source for urban legends, folklore, myths, rumors, and misinformation.
* <img src="https://www.google.com/s2/favicons?domain=verificationhandbook.com&sz=16" width="16" height="16"> [Verification Handbook](http://verificationhandbook.com)

## [↑](#-table-of-contents) 📊 Data and Statistics

* [AGOA Data Center](http://agoa.info)
* <img src="https://www.google.com/s2/favicons?domain=aiddata.org&sz=16" width="16" height="16"> [AidData](http://aiddata.org)
* <img src="https://www.google.com/s2/favicons?domain=aws.amazon.com&sz=16" width="16" height="16"> [AWS Public Datasets](http://aws.amazon.com/datasets)
* <img src="https://www.google.com/s2/favicons?domain=www.bis.org&sz=16" width="16" height="16"> [Bank for International Settlements Statistics](http://www.bis.org/statistics/index.htm)
* <img src="https://www.google.com/s2/favicons?domain=www.lib.berkeley.edu&sz=16" width="16" height="16"> [Berkely Library: Data Lab](http://www.lib.berkeley.edu/libraries/data-lab)
* <img src="https://www.google.com/s2/favicons?domain=www.bp.com&sz=16" width="16" height="16"> [BP Statistical Review of World Energy](http://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy.html)
* [Center for International Earth Science Information Network](http://www.ciesin.org)
* <img src="https://www.google.com/s2/favicons?domain=www.cepii.fr&sz=16" width="16" height="16"> [CEPII](http://www.cepii.fr/CEPII/en/welcome.asp)
* <img src="https://www.google.com/s2/favicons?domain=www.cia.gov&sz=16" width="16" height="16"> [CIA World Factbook](https://www.cia.gov/the-world-factbook/)
* [Data.gov.uk](https://data.gov.uk)
* <img src="https://www.google.com/s2/favicons?domain=wiki.dbpedia.org&sz=16" width="16" height="16"> [DBPedia](http://wiki.dbpedia.org)
* [European Union Open Data Portal](http://open-data.europa.eu/en/data)
* <img src="https://www.google.com/s2/favicons?domain=ec.europa.eu&sz=16" width="16" height="16"> [Eurostat](http://ec.europa.eu/eurostat)
* <img src="https://www.google.com/s2/favicons?domain=developers.google.com&sz=16" width="16" height="16"> [Freebase](https://developers.google.com/freebase)
* <img src="https://www.google.com/s2/favicons?domain=www.gapminder.org&sz=16" width="16" height="16"> [Gapminder World](http://www.gapminder.org/data)
* <img src="https://www.google.com/s2/favicons?domain=globaledge.msu.edu&sz=16" width="16" height="16"> [globalEDGE Database of International Business Statistics](http://globaledge.msu.edu/tools-and-data/dibs)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Finance](https://www.google.com/finance)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Public Data Explorer](http://www.google.com/publicdata/directory)
* <img src="https://www.google.com/s2/favicons?domain=open.canada.ca&sz=16" width="16" height="16"> [Government of Canada Open Data](http://open.canada.ca/en)
* <img src="https://www.google.com/s2/favicons?domain=www.ihs.com&sz=16" width="16" height="16"> [HIS Piers](https://www.ihs.com/products/piers.html)
* <img src="https://www.google.com/s2/favicons?domain=hdr.undp.org&sz=16" width="16" height="16"> [Human Development Reports](http://hdr.undp.org/en/global-reports)
* <img src="https://www.google.com/s2/favicons?domain=www.ilo.org&sz=16" width="16" height="16"> [ILO World Employment and Social Outlook Trends](http://www.ilo.org/global/research/global-reports/weso/2015/lang--en/index.htm)
* <img src="https://www.google.com/s2/favicons?domain=www.ilo.org&sz=16" width="16" height="16"> [ILOSTAT](http://www.ilo.org/ilostat/faces/oracle/webcenter/portalapp/pagehierarchy/Page137.jspx?_afrLoop=443508925711569&clean=true#%40%3F_afrLoop%3D443508925711569%26clean%3Dtrue%26_adf.ctrl-state%3Dl4dwldaf3_9)
* <img src="https://www.google.com/s2/favicons?domain=www.imf.org&sz=16" width="16" height="16"> [IMF World Economic Outlook Database](http://www.imf.org/external/ns/cs.aspx?id=28)
* <img src="https://www.google.com/s2/favicons?domain=www.indexmundi.com&sz=16" width="16" height="16"> [Index Mundi](http://www.indexmundi.com)
* <img src="https://www.google.com/s2/favicons?domain=www.iea.org&sz=16" width="16" height="16"> [International Energy Agency Statistics](http://www.iea.org/statistics)
* <img src="https://www.google.com/s2/favicons?domain=www.bls.gov&sz=16" width="16" height="16"> [International Labour Comparisons](http://www.bls.gov/fls/chartbook.htm)
* [International Trade Center](http://www.intracen.org/ByCountry.aspx)
* <img src="https://www.google.com/s2/favicons?domain=junar.com&sz=16" width="16" height="16"> [Junar](http://junar.com)
* <img src="https://www.google.com/s2/favicons?domain=knoema.com&sz=16" width="16" height="16"> [Knoema](https://knoema.com)
* <img src="https://www.google.com/s2/favicons?domain=landmatrix.org&sz=16" width="16" height="16"> [LandMatrix](http://landmatrix.org)
* <img src="https://www.google.com/s2/favicons?domain=www.latinobarometro.org&sz=16" width="16" height="16"> [Latinobarometro](http://www.latinobarometro.org)
* <img src="https://www.google.com/s2/favicons?domain=www.lib.umich.edu&sz=16" width="16" height="16"> [Library, University of Michigan: Statistics and Datasets](http://www.lib.umich.edu/browse/Statistics%20and%20Data%20Sets)
* <img src="https://www.google.com/s2/favicons?domain=www.nationmaster.com&sz=16" width="16" height="16"> [Nation Master](http://www.nationmaster.com/statistics)
* <img src="https://www.google.com/s2/favicons?domain=www.oecd.org&sz=16" width="16" height="16"> [OECD Aid Database](http://www.oecd.org/dac/stats/data.htm)
* <img src="https://www.google.com/s2/favicons?domain=data.oecd.org&sz=16" width="16" height="16"> [OECD Data](https://data.oecd.org)
* <img src="https://www.google.com/s2/favicons?domain=www.oecd-ilibrary.org&sz=16" width="16" height="16"> [OECD Factbook](http://www.oecd-ilibrary.org/economics/oecd-factbook_18147364)
* [Open Data Network](http://www.opendatanetwork.com)
* [Paul Hensel’s General Informational Data Page](http://www.paulhensel.org/dataintl.html)
* <img src="https://www.google.com/s2/favicons?domain=www.rug.nl&sz=16" width="16" height="16"> [Penn World Table](http://www.rug.nl/research/ggdc/data/pwt/pwt-8.1)
* <img src="https://www.google.com/s2/favicons?domain=www.pewinternet.org&sz=16" width="16" height="16"> [Pew Research Center](http://www.pewinternet.org/datasets)
* <img src="https://www.google.com/s2/favicons?domain=www.prb.org&sz=16" width="16" height="16"> [Population Reference Bureau Data Finder](http://www.prb.org/DataFinder.aspx)
* <img src="https://www.google.com/s2/favicons?domain=www.prsgroup.com&sz=16" width="16" height="16"> [PRS Risk Indicators](http://www.prsgroup.com)
* <img src="https://www.google.com/s2/favicons?domain=www.sesric.org&sz=16" width="16" height="16"> [SESRIC Basic Social and Economic Indicators](http://www.sesric.org/baseind.php)
* <img src="https://www.google.com/s2/favicons?domain=www.sesric.org&sz=16" width="16" height="16"> [SESRIC Databases](http://www.sesric.org/databases-index.php)
* <img src="https://www.google.com/s2/favicons?domain=www.statista.com&sz=16" width="16" height="16"> [Statista](http://www.statista.com)
* <img src="https://www.google.com/s2/favicons?domain=atlas.cid.harvard.edu&sz=16" width="16" height="16"> [The Atlas of Economic Complexity](http://atlas.cid.harvard.edu)
* [The Data and Story Library](http://lib.stat.cmu.edu/DASL)
* <img src="https://www.google.com/s2/favicons?domain=www.tradingeconomics.com&sz=16" width="16" height="16"> [Trading Economics](http://www.tradingeconomics.com)
* <img src="https://www.google.com/s2/favicons?domain=www.transparency.org&sz=16" width="16" height="16"> [Transparency.org Corruption Perception Index](http://www.transparency.org/cpi2015)
* <img src="https://www.google.com/s2/favicons?domain=comtrade.un.org&sz=16" width="16" height="16"> [UN COMTRADE Database](http://comtrade.un.org)
* <img src="https://www.google.com/s2/favicons?domain=data.un.org&sz=16" width="16" height="16"> [UN Data](http://data.un.org)
* <img src="https://www.google.com/s2/favicons?domain=unctad.org&sz=16" width="16" height="16"> [UNCTAD Country Fact Sheets](http://unctad.org/en/Pages/DIAE/World%20Investment%20Report/Country-Fact-Sheets.aspx)
* <img src="https://www.google.com/s2/favicons?domain=unctad.org&sz=16" width="16" height="16"> [UNCTAD Investment Country Profiles](http://unctad.org/en/Pages/Publications/Investment-country-profiles.aspx)
* <img src="https://www.google.com/s2/favicons?domain=unctadstat.unctad.org&sz=16" width="16" height="16"> [UNCTAD STAT](http://unctadstat.unctad.org)
* <img src="https://www.google.com/s2/favicons?domain=hdr.undp.org&sz=16" width="16" height="16"> [UNDPs Human Development Index](http://hdr.undp.org/en/data)
* <img src="https://www.google.com/s2/favicons?domain=w3.unece.org&sz=16" width="16" height="16"> [UNECE](http://w3.unece.org/PXWeb/en)
* [UNESCO Institute for Statistics](http://uis.unesco.org)
* <img src="https://www.google.com/s2/favicons?domain=www.unido.org&sz=16" width="16" height="16"> [UNIDO Statistical Databases](http://www.unido.org/resources/statistics/statistical-databases.html)
* <img src="https://www.google.com/s2/favicons?domain=unstats.un.org&sz=16" width="16" height="16"> [UNStats Social Indicators](http://unstats.un.org/unsd/demographic/products/socind)
* <img src="https://www.google.com/s2/favicons?domain=www.pcr.uu.se&sz=16" width="16" height="16"> [Upsala Conflict Data Program](http://www.pcr.uu.se/research/UCDP)
* <img src="https://www.google.com/s2/favicons?domain=www.usa.gov&sz=16" width="16" height="16"> [US Data and Statistics](https://www.usa.gov/statistics)
* <img src="https://www.google.com/s2/favicons?domain=vizala.com&sz=16" width="16" height="16"> [Vizala](https://vizala.com)
* <img src="https://www.google.com/s2/favicons?domain=www.who.int&sz=16" width="16" height="16"> [WHO Data](http://www.who.int/gho/en)
* <img src="https://www.google.com/s2/favicons?domain=data.worldbank.org&sz=16" width="16" height="16"> [World Bank Data](http://data.worldbank.org)
* <img src="https://www.google.com/s2/favicons?domain=datatopics.worldbank.org&sz=16" width="16" height="16"> [World Bank Data](http://datatopics.worldbank.org/consumption/home)
* <img src="https://www.google.com/s2/favicons?domain=www.doingbusiness.org&sz=16" width="16" height="16"> [World Bank Doing Business](http://www.doingbusiness.org)
* <img src="https://www.google.com/s2/favicons?domain=www.enterprisesurveys.org&sz=16" width="16" height="16"> [World Bank Enterprise Surveys](http://www.enterprisesurveys.org)
* [World Bank Investing Across Borders](http://iab.worldbank.org)
* <img src="https://www.google.com/s2/favicons?domain=wits.worldbank.org&sz=16" width="16" height="16"> [World Integrated Trade Solution](http://wits.worldbank.org)
* <img src="https://www.google.com/s2/favicons?domain=www.wto.org&sz=16" width="16" height="16"> [WTO Statistics](https://www.wto.org/english/res_e/statis_e/statis_e.htm)
* [Zanran](http://zanran.com)

## [↑](#-table-of-contents) 👀 Web Monitoring

* <img src="https://www.google.com/s2/favicons?domain=alltop.com&sz=16" width="16" height="16"> [Alltop](http://alltop.com)
* <img src="https://www.google.com/s2/favicons?domain=www.awasu.com&sz=16" width="16" height="16"> [Awasu](http://www.awasu.com)
* [Bridge.Leslibres](https://bridge.leslibres.org)
* <img src="https://www.google.com/s2/favicons?domain=bridge.suumitsu.eu&sz=16" width="16" height="16"> [Bridge.Suumitsu](https://bridge.suumitsu.eu)
* [ChangeDetection.io](https://changedetection.io)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [ChangeDetection.io Open Source](https://github.com/dgtlmoon/changedetection.io)
* <img src="https://www.google.com/s2/favicons?domain=www.changedetect.com&sz=16" width="16" height="16"> [ChangeDetect](http://www.changedetect.com)
* <img src="https://www.google.com/s2/favicons?domain=www.changedetection.com&sz=16" width="16" height="16"> [ChangeDetection](http://www.changedetection.com)
* <img src="https://www.google.com/s2/favicons?domain=bitreading.com&sz=16" width="16" height="16"> [Deltafeed](http://bitreading.com/deltafeed)
* <img src="https://www.google.com/s2/favicons?domain=digg.com&sz=16" width="16" height="16"> [DiggReader](http://digg.com/login?next=%2Freader)
* <img src="https://www.google.com/s2/favicons?domain=www.qsensei.com&sz=16" width="16" height="16"> [FeedBooster](http://www.qsensei.com)
* [Feederator](http://www.feederator.org)
* <img src="https://www.google.com/s2/favicons?domain=feed.exileed.com&sz=16" width="16" height="16"> [Feed Exileed](http://feed.exileed.com)
* <img src="https://www.google.com/s2/favicons?domain=feed.janicek.co&sz=16" width="16" height="16"> [Feed Filter Maker](http://feed.janicek.co)
* <img src="https://www.google.com/s2/favicons?domain=www.feedly.com&sz=16" width="16" height="16"> [Feedly](http://www.feedly.com)
* <img src="https://www.google.com/s2/favicons?domain=www.feedreader.com&sz=16" width="16" height="16"> [FeedReader](http://www.feedreader.com)
* <img src="https://www.google.com/s2/favicons?domain=fetchrss.com&sz=16" width="16" height="16"> [FetchRSS](http://fetchrss.com)
* [Flipboard](http://flipboard.com)
* [FollowThatPage](http://www.followthatpage.com)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Google Alerts](http://www.google.com/alerts) - A content change detection and notification service.
* <img src="https://www.google.com/s2/favicons?domain=www.infominder.com&sz=16" width="16" height="16"> [InfoMinder](http://www.infominder.com/webminder)
* <img src="https://www.google.com/s2/favicons?domain=en.mention.com&sz=16" width="16" height="16"> [Mention](https://en.mention.com)
* <img src="https://www.google.com/s2/favicons?domain=www.netvibes.com&sz=16" width="16" height="16"> [Netvibes](http://www.netvibes.com)
* <img src="https://www.google.com/s2/favicons?domain=newsblur.com&sz=16" width="16" height="16"> [Newsblur](http://newsblur.com)
* <img src="https://www.google.com/s2/favicons?domain=www.jetbrains.com&sz=16" width="16" height="16"> [OmeaReader](http://www.jetbrains.com/omea/reader)
* <img src="https://www.google.com/s2/favicons?domain=onwebchange.com&sz=16" width="16" height="16"> [OnWebChange](http://onwebchange.com)
* [Reeder](http://reederapp.com)
* <img src="https://www.google.com/s2/favicons?domain=bridge.suumitsu.eu&sz=16" width="16" height="16"> [RSS Bridge](https://bridge.suumitsu.eu)
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [RSS Feed Reader](https://chrome.google.com/webstore/detail/rss-feed-reader/pnjaodmkngahhkoihejjehlcdlnohgmp)
* [RSS Micro](http://www.rssmicro.com)
* [RSS Search Engine](http://ctrlq.org/rss)
* [RSS Search Hub](http://www.rsssearchhub.com)
* <img src="https://www.google.com/s2/favicons?domain=www.rssowl.org&sz=16" width="16" height="16"> [RSSOwl](http://www.rssowl.org)
* <img src="https://www.google.com/s2/favicons?domain=selfoss.aditu.de&sz=16" width="16" height="16"> [Selfoss](http://selfoss.aditu.de)
* <img src="https://www.google.com/s2/favicons?domain=www.silobreaker.com&sz=16" width="16" height="16"> [Silobreaker](http://www.silobreaker.com)
* <img src="https://www.google.com/s2/favicons?domain=www.talkwalker.com&sz=16" width="16" height="16"> [Talkwalker](http://www.talkwalker.com)
* <img src="https://www.google.com/s2/favicons?domain=theoldreader.com&sz=16" width="16" height="16"> [The Old Reader](http://theoldreader.com)
* <img src="https://www.google.com/s2/favicons?domain=versionista.com&sz=16" width="16" height="16"> [versionista](http://versionista.com)
* <img src="https://www.google.com/s2/favicons?domain=visualping.io&sz=16" width="16" height="16"> [visualping](https://visualping.io)
* <img src="https://www.google.com/s2/favicons?domain=www.getwebreader.com&sz=16" width="16" height="16"> [WebReader](http://www.getwebreader.com)
* <img src="https://www.google.com/s2/favicons?domain=www.aignes.com&sz=16" width="16" height="16"> [WebSite Watcher](http://www.aignes.com/index.htm)
* <img src="https://www.google.com/s2/favicons?domain=winds.getstream.io&sz=16" width="16" height="16"> [Winds](http://winds.getstream.io)

## [↑](#-table-of-contents) 🧭 Browsers

* [Atom](https://browser.ru/)
* <img src="https://www.google.com/s2/favicons?domain=brave.com&sz=16" width="16" height="16"> [Brave](https://brave.com) - is an open-source web browser that allows you to completely block ads and website trackers.
* <img src="https://www.google.com/s2/favicons?domain=www.bromite.org&sz=16" width="16" height="16"> [Bromite](https://www.bromite.org/) - Bromite is a Chromium fork with ad blocking and enhanced privacy; take back your browser. Works only on Android.
* <img src="https://www.google.com/s2/favicons?domain=www.centbrowser.com&sz=16" width="16" height="16"> [CentBrowser](http://www.centbrowser.com)
* <img src="https://www.google.com/s2/favicons?domain=www.google.com&sz=16" width="16" height="16"> [Chrome](https://www.google.com/chrome)
* <img src="https://www.google.com/s2/favicons?domain=www.comodo.com&sz=16" width="16" height="16"> [Comodo Dragon](https://www.comodo.com/home/browsers-toolbars/browser.php)
* <img src="https://www.google.com/s2/favicons?domain=coowon.com&sz=16" width="16" height="16"> [Coowon](http://coowon.com)
* <img src="https://www.google.com/s2/favicons?domain=icecatbrowser.org&sz=16" width="16" height="16"> [Gnu Icecat](https://icecatbrowser.org/) -
* <img src="https://www.google.com/s2/favicons?domain=www.microsoft.com&sz=16" width="16" height="16"> [Edge](https://www.microsoft.com/en-us/windows/microsoft-edge/microsoft-edge)
* <img src="https://www.google.com/s2/favicons?domain=www.mozilla.org&sz=16" width="16" height="16"> [Firefox](https://www.mozilla.org)
* <img src="https://www.google.com/s2/favicons?domain=librewolf.net&sz=16" width="16" height="16"> [LibreWolf](https://librewolf.net) - Privacy-focused Firefox fork with enhanced security defaults.
* <img src="https://www.google.com/s2/favicons?domain=www.maxthon.com&sz=16" width="16" height="16"> [Maxthon](http://www.maxthon.com)
* <img src="https://www.google.com/s2/favicons?domain=mullvad.net&sz=16" width="16" height="16"> [Mullvad Browser](https://mullvad.net/en/browser) - Privacy-focused browser developed in collaboration with Tor Project.
* <img src="https://www.google.com/s2/favicons?domain=www.opera.com&sz=16" width="16" height="16"> [Opera](http://www.opera.com)
* <img src="https://www.google.com/s2/favicons?domain=www.apple.com&sz=16" width="16" height="16"> [Safari](http://www.apple.com/safari)
* <img src="https://www.google.com/s2/favicons?domain=www.fenrir-inc.com&sz=16" width="16" height="16"> [Sleipnir](http://www.fenrir-inc.com/jp/sleipnir)
* <img src="https://www.google.com/s2/favicons?domain=www.slimjet.com&sz=16" width="16" height="16"> [Slimjet](http://www.slimjet.com)
* <img src="https://www.google.com/s2/favicons?domain=www.srware.net&sz=16" width="16" height="16"> [SRWare Iron](http://www.srware.net/en/software_srware_iron.php)
* <img src="https://www.google.com/s2/favicons?domain=www.torproject.org&sz=16" width="16" height="16"> [Tor Browser](https://www.torproject.org/projects/torbrowser.html.en) - Tor is a free software that prevents people from learning your location or browsing habits by letting you communicate anonymously on the Internet.
* <img src="https://www.google.com/s2/favicons?domain=www.torchbrowser.com&sz=16" width="16" height="16"> [Torch](http://www.torchbrowser.com)
* <img src="https://www.google.com/s2/favicons?domain=www.ucweb.com&sz=16" width="16" height="16"> [UCBrowser](http://www.ucweb.com)
* <img src="https://www.google.com/s2/favicons?domain=vivaldi.com&sz=16" width="16" height="16"> [Vivaldi](https://vivaldi.com) - Powerful, Private and Personal Web Browser.
* <img src="https://www.google.com/s2/favicons?domain=www.waterfox.net&sz=16" width="16" height="16"> [Waterfox](https://www.waterfox.net/) - Fast and Private Web Browser. Get privacy out of the box with Waterfox.
* <img src="https://www.google.com/s2/favicons?domain=browser.yandex.com&sz=16" width="16" height="16"> [Yandex Browser](https://browser.yandex.com/desktop/main)

## [↑](#-table-of-contents) 📥 Offline Browsing

* <img src="https://www.google.com/s2/favicons?domain=www.microsystools.com&sz=16" width="16" height="16"> [A1 Website Download](http://www.microsystools.com/products/website-download) - Download entire websites to disk.
* <img src="https://www.google.com/s2/favicons?domain=www.cyotek.com&sz=16" width="16" height="16"> [Cyotek WebCopy](http://www.cyotek.com/cyotek-webcopy) - is a free tool for automatically downloading the content of a website onto your local device.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [gmapcatcher](https://github.com/heldersepu/gmapcatcher)
* [Hooey webprint](http://www.hooeeywebprint.com.s3-website-us-east-1.amazonaws.com/download.html)
* <img src="https://www.google.com/s2/favicons?domain=www.httrack.com&sz=16" width="16" height="16"> [HTTrack](http://www.httrack.com) - Allows you to download a World Wide Web site from the Internet to a local directory, building recursively all directories, getting HTML, images, and other files from the server to your computer.
* <img src="https://www.google.com/s2/favicons?domain=offliberty.com&sz=16" width="16" height="16"> [Offliberty](http://offliberty.com) -  is a website that lets you access any online content without a permanent Internet connection.
* <img src="https://www.google.com/s2/favicons?domain=metaproductsrevolver.com&sz=16" width="16" height="16"> [Resolver](https://metaproductsrevolver.com)
* [SiteSucker](http://ricks-apps.com/osx/sitesucker/index.html)
* <img src="https://www.google.com/s2/favicons?domain=www.proxy-offline-browser.com&sz=16" width="16" height="16"> [WebAssistant](http://www.proxy-offline-browser.com/download.html)
* <img src="https://www.google.com/s2/favicons?domain=www.tensons.com&sz=16" width="16" height="16"> [Website Ripper Copier](http://www.tensons.com/products/websiterippercopier)

## [↑](#-table-of-contents) 🛡️ VPN Services

* [OffShore.cat](https://offshore.cat/vpn) - list of vpns for the privacy conscious
* <img src="https://www.google.com/s2/favicons?domain=torrentfreak.com&sz=16" width="16" height="16"> [TorrentFreak List of VPNs](https://torrentfreak.com/vpn-services-anonymous-review-2017-170304/)
* <img src="https://www.google.com/s2/favicons?domain=thatoneprivacysite.net&sz=16" width="16" height="16"> [VPN Comparison by That One Privacy Guy](https://thatoneprivacysite.net/) - is a summary list of top best VPN services.

## [↑](#-table-of-contents) 📈 Infographics and Data Visualization

* <img src="https://www.google.com/s2/favicons?domain=www.aeontimeline.com&sz=16" width="16" height="16"> [Aeon](http://www.aeontimeline.com)
* [Arbor.js](http://arborjs.org)
* [Beaker](http://beakernotebook.com)
* <img src="https://www.google.com/s2/favicons?domain=www.befunky.com&sz=16" width="16" height="16"> [Befunky](https://www.befunky.com)
* <img src="https://www.google.com/s2/favicons?domain=www.bizint.com&sz=16" width="16" height="16"> [Bizint](http://www.bizint.com)
* <img src="https://www.google.com/s2/favicons?domain=cacoo.com&sz=16" width="16" height="16"> [Cacoo](https://cacoo.com)
* <img src="https://www.google.com/s2/favicons?domain=www.canva.com&sz=16" width="16" height="16"> [Canva](https://www.canva.com)
* <img src="https://www.google.com/s2/favicons?domain=www.chartjs.org&sz=16" width="16" height="16"> [Chart.js](http://www.chartjs.org) - a javascript library that allows you to create charts easly
* <img src="https://www.google.com/s2/favicons?domain=www.chartblocks.com&sz=16" width="16" height="16"> [chartblocks](http://www.chartblocks.com)
* <img src="https://www.google.com/s2/favicons?domain=circos.ca&sz=16" width="16" height="16"> [Circos](http://circos.ca)
* <img src="https://www.google.com/s2/favicons?domain=creately.com&sz=16" width="16" height="16"> [creately](http://creately.com)
* <img src="https://www.google.com/s2/favicons?domain=square.github.io&sz=16" width="16" height="16"> [Crossfilter](http://square.github.io/crossfilter)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [csvkit](https://github.com/wireservice/csvkit)
* <img src="https://www.google.com/s2/favicons?domain=d3js.org&sz=16" width="16" height="16"> [D3js](https://d3js.org) - is a powerful data visualization javascript library.
* <img src="https://www.google.com/s2/favicons?domain=datavizcatalogue.com&sz=16" width="16" height="16"> [Data Visualization Catalogue](http://datavizcatalogue.com)
* <img src="https://www.google.com/s2/favicons?domain=datawrapper.de&sz=16" width="16" height="16"> [Datawrapper](https://datawrapper.de)
* <img src="https://www.google.com/s2/favicons?domain=www.dropmark.com&sz=16" width="16" height="16"> [Dropmark](http://www.dropmark.com)
* <img src="https://www.google.com/s2/favicons?domain=dygraphs.com&sz=16" width="16" height="16"> [dygraphs](http://dygraphs.com)
* <img src="https://www.google.com/s2/favicons?domain=www.easel.ly&sz=16" width="16" height="16"> [easely](http://www.easel.ly)
* [Exhibit](http://www.simile-widgets.org/exhibit)
* <img src="https://www.google.com/s2/favicons?domain=www.flotcharts.org&sz=16" width="16" height="16"> [Flot](http://www.flotcharts.org)
* <img src="https://www.google.com/s2/favicons?domain=www.fusioncharts.com&sz=16" width="16" height="16"> [FusionCharts](http://www.fusioncharts.com)
* <img src="https://www.google.com/s2/favicons?domain=developers.google.com&sz=16" width="16" height="16"> [Google Developers: Charts](https://developers.google.com/chart)
* <img src="https://www.google.com/s2/favicons?domain=spark.apache.org&sz=16" width="16" height="16"> [GraphX](http://spark.apache.org/graphx)
* <img src="https://www.google.com/s2/favicons?domain=www.highcharts.com&sz=16" width="16" height="16"> [Highcharts](http://www.highcharts.com)
* <img src="https://www.google.com/s2/favicons?domain=charts.hohli.com&sz=16" width="16" height="16"> [Hohli](http://charts.hohli.com)
* <img src="https://www.google.com/s2/favicons?domain=infogr.am&sz=16" width="16" height="16"> [Infogr.am](https://infogr.am)
* <img src="https://www.google.com/s2/favicons?domain=inkscape.org&sz=16" width="16" height="16"> [Inkscape](https://inkscape.org)
* <img src="https://www.google.com/s2/favicons?domain=philogb.github.io&sz=16" width="16" height="16"> [Java Infovis Toolkit](http://philogb.github.io/jit)
* <img src="https://www.google.com/s2/favicons?domain=jpgraph.net&sz=16" width="16" height="16"> [JpGraph](http://jpgraph.net)
* [jqPlot](http://www.jqplot.com) - A Versatile and Expandable jQuery Plotting Plugin.
* <img src="https://www.google.com/s2/favicons?domain=knoema.com&sz=16" width="16" height="16"> [Knoema](https://knoema.com)
* <img src="https://www.google.com/s2/favicons?domain=leafletjs.com&sz=16" width="16" height="16"> [Leaflet](http://leafletjs.com) - an open-source JavaScript library for mobile-friendly interactive maps.
* <img src="https://www.google.com/s2/favicons?domain=linkurio.us&sz=16" width="16" height="16"> [Linkuroius](http://linkurio.us)
* [Listify](http://listify.okfnlabs.org) - Turn a Google spreadsheet into a beautiful, searchable listing in seconds.
* <img src="https://www.google.com/s2/favicons?domain=www.localfocus.nl&sz=16" width="16" height="16"> [LocalFocus](https://www.localfocus.nl)
* <img src="https://www.google.com/s2/favicons?domain=www.lucidchart.com&sz=16" width="16" height="16"> [Lucidchart](https://www.lucidchart.com) - the intelligent diagramming application that brings teams together to make better decisions and build the future.
* <img src="https://www.google.com/s2/favicons?domain=mapline.com&sz=16" width="16" height="16"> [Mapline](https://mapline.com)
* <img src="https://www.google.com/s2/favicons?domain=www.nodebox.net&sz=16" width="16" height="16"> [Nodebox](https://www.nodebox.net) - a family of tools gives you the leverage to create generative design the way you want.
* <img src="https://www.google.com/s2/favicons?domain=observablehq.com&sz=16" width="16" height="16"> [Observable](https://observablehq.com/) - a modern way to create powerful, performant, polyglot data apps built on open source.
* <img src="https://www.google.com/s2/favicons?domain=openlayers.org&sz=16" width="16" height="16"> [OpenLayers](http://openlayers.org) - A high-performance, feature-packed library for all your mapping needs.
* [Palladio](http://hdlab.stanford.edu/palladio) - Visualize complex historical data with ease.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Perspective](https://github.com/finos/perspective) - interactive data visualization and analytics component, well-suited for large, streaming and static datasets.
* <img src="https://www.google.com/s2/favicons?domain=piktochart.com&sz=16" width="16" height="16"> [Piktochart](https://piktochart.com)
* <img src="https://www.google.com/s2/favicons?domain=www.pixxa.com&sz=16" width="16" height="16"> [Pixxa](http://www.pixxa.com)
* <img src="https://www.google.com/s2/favicons?domain=plot.ly&sz=16" width="16" height="16"> [Plotly](https://plot.ly)
* <img src="https://www.google.com/s2/favicons?domain=www.preceden.com&sz=16" width="16" height="16"> [Preceden](https://www.preceden.com/) - Create a Visual Timeline About Any Topic
* <img src="https://www.google.com/s2/favicons?domain=www.visualintelligence.co.nz&sz=16" width="16" height="16"> [QlikView](https://www.visualintelligence.co.nz/qlikview)
* <img src="https://www.google.com/s2/favicons?domain=www.quadrigram.com&sz=16" width="16" height="16"> [Quadrigram](http://www.quadrigram.com)
* [Raphael](http://dmitrybaranovskiy.github.io/raphael)
* <img src="https://www.google.com/s2/favicons?domain=raw.densitydesign.org&sz=16" width="16" height="16"> [RAW](http://raw.densitydesign.org)
* <img src="https://www.google.com/s2/favicons?domain=www.viseyes.org&sz=16" width="16" height="16"> [Shanti Interactive](http://www.viseyes.org)
* <img src="https://www.google.com/s2/favicons?domain=snappa.io&sz=16" width="16" height="16"> [Snappa](https://snappa.io)
* [StoryMap](https://storymap.knightlab.com)
* <img src="https://www.google.com/s2/favicons?domain=public.tableau.com&sz=16" width="16" height="16"> [Tableau Public](https://public.tableau.com)
* <img src="https://www.google.com/s2/favicons?domain=www.tableau.com&sz=16" width="16" height="16"> [Tableau](http://www.tableau.com)
* <img src="https://www.google.com/s2/favicons?domain=tagul.com&sz=16" width="16" height="16"> [Tagul](https://tagul.com)
* [Textures.js](https://riccardoscalco.github.io/textures)
* [Tik-tok](https://datanews.github.io/tik-tok)
* <img src="https://www.google.com/s2/favicons?domain=www.tiki-toki.com&sz=16" width="16" height="16"> [Tiki-toki](http://www.tiki-toki.com)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Timeflow](https://github.com/FlowingMedia/TimeFlow/wiki)
* <img src="https://www.google.com/s2/favicons?domain=timeline.knightlab.com&sz=16" width="16" height="16"> [Timeline](http://timeline.knightlab.com)
* [Timeline](http://www.simile-widgets.org/timeline)
* <img src="https://www.google.com/s2/favicons?domain=www.timetoast.com&sz=16" width="16" height="16"> [Timetoast](http://www.timetoast.com)
* <img src="https://www.google.com/s2/favicons?domain=venngage.com&sz=16" width="16" height="16"> [Venngage](https://venngage.com)
* <img src="https://www.google.com/s2/favicons?domain=visjs.org&sz=16" width="16" height="16"> [Vis.js](http://visjs.org)
* <img src="https://www.google.com/s2/favicons?domain=www.visme.co&sz=16" width="16" height="16"> [Visme](http://www.visme.co)
* <img src="https://www.google.com/s2/favicons?domain=visualizefree.com&sz=16" width="16" height="16"> [Visualize Free](http://visualizefree.com)
* <img src="https://www.google.com/s2/favicons?domain=vizualize.me&sz=16" width="16" height="16"> [Visualize.me](http://vizualize.me)
* [visually](http://create.visual.ly)
* <img src="https://www.google.com/s2/favicons?domain=www.dotmatics.com&sz=16" width="16" height="16"> [Vortex](http://www.dotmatics.com/products/vortex)
* <img src="https://www.google.com/s2/favicons?domain=www.zingchart.com&sz=16" width="16" height="16"> [ZingChart](http://www.zingchart.com)

## [↑](#-table-of-contents) 🕸️ Social Network Analysis

* <img src="https://www.google.com/s2/favicons?domain=gephi.org&sz=16" width="16" height="16"> [Gephi](https://gephi.org) - is an open-source graph and network visualization software.
* <img src="https://www.google.com/s2/favicons?domain=www.casos.cs.cmu.edu&sz=16" width="16" height="16"> [ORA](http://www.casos.cs.cmu.edu/projects/ora/software.php)
* <img src="https://www.google.com/s2/favicons?domain=www.fmsasg.com&sz=16" width="16" height="16"> [Sentinel Visualizer](http://www.fmsasg.com)
* <img src="https://www.google.com/s2/favicons?domain=vis.occrp.org&sz=16" width="16" height="16"> [Visual Investigative Scenarios](https://vis.occrp.org)
* <img src="https://www.google.com/s2/favicons?domain=wynyardgroup.com&sz=16" width="16" height="16"> [Wynyard Group](https://wynyardgroup.com)

## [↑](#-table-of-contents) 🔐 Privacy and Encryption Tools

* <img src="https://www.google.com/s2/favicons?domain=www.abine.com&sz=16" width="16" height="16"> [Abine](https://www.abine.com)
* <img src="https://www.google.com/s2/favicons?domain=adium.im&sz=16" width="16" height="16"> [Adium](https://adium.im)
* <img src="https://www.google.com/s2/favicons?domain=bitwarden.com&sz=16" width="16" height="16"> [Bitwarden](https://bitwarden.com) - Open-source password manager with cross-platform support.
* [boxcryptor](https://www.boxcryptor.com)
* <img src="https://www.google.com/s2/favicons?domain=www.piriform.com&sz=16" width="16" height="16"> [CCleaner](https://www.piriform.com/ccleaner)
* <img src="https://www.google.com/s2/favicons?domain=chatsecure.org&sz=16" width="16" height="16"> [Chatsecure](https://chatsecure.org)
* <img src="https://www.google.com/s2/favicons?domain=disconnect.me&sz=16" width="16" height="16"> [Disconnect](https://disconnect.me)
* <img src="https://www.google.com/s2/favicons?domain=donottrack.us&sz=16" width="16" height="16"> [Do Not Track](http://donottrack.us)
* <img src="https://www.google.com/s2/favicons?domain=duckduckgo.com&sz=16" width="16" height="16"> [Duck Duck Go Search Engine](https://duckduckgo.com)
* [EncSF MP](http://encfsmp.sourceforge.net)
* <img src="https://www.google.com/s2/favicons?domain=www.epicbrowser.com&sz=16" width="16" height="16"> [Epic Privacy Browser](https://www.epicbrowser.com)
* <img src="https://www.google.com/s2/favicons?domain=eraser.heidi.ie&sz=16" width="16" height="16"> [Eraser](http://eraser.heidi.ie)
* <img src="https://www.google.com/s2/favicons?domain=support.apple.com&sz=16" width="16" height="16"> [FileVault](https://support.apple.com/en-us/HT204837)
* <img src="https://www.google.com/s2/favicons?domain=www.ghostery.com&sz=16" width="16" height="16"> [Ghostery](https://www.ghostery.com)
* <img src="https://www.google.com/s2/favicons?domain=www.gnupg.org&sz=16" width="16" height="16"> [GNU PG](https://www.gnupg.org/download/index.html)
* <img src="https://www.google.com/s2/favicons?domain=gpgtools.org&sz=16" width="16" height="16"> [GPG Tools](https://gpgtools.org)
* <img src="https://www.google.com/s2/favicons?domain=guardianproject.info&sz=16" width="16" height="16"> [Guardian Project](https://guardianproject.info)
* <img src="https://www.google.com/s2/favicons?domain=www.guerrillamail.com&sz=16" width="16" height="16"> [Guerrilla Mail](https://www.guerrillamail.com)
* <img src="https://www.google.com/s2/favicons?domain=www.hotspotshield.com&sz=16" width="16" height="16"> [Hotspot Shield](https://www.hotspotshield.com)
* <img src="https://www.google.com/s2/favicons?domain=www.eff.org&sz=16" width="16" height="16"> [HTTPs Everywhere](https://www.eff.org/https-everywhere/)
* <img src="https://www.google.com/s2/favicons?domain=geti2p.net&sz=16" width="16" height="16"> [I2P](https://geti2p.net)
* <img src="https://www.google.com/s2/favicons?domain=justdelete.me&sz=16" width="16" height="16"> [justdeleteme](http://justdelete.me)
* <img src="https://www.google.com/s2/favicons?domain=keepass.info&sz=16" width="16" height="16"> [KeePass Password Safe](http://keepass.info) - is a free and open-source password manager that uses the most secure encryption algorithms to safegard your passwords.
* <img src="https://www.google.com/s2/favicons?domain=lastpass.com&sz=16" width="16" height="16"> [Lastpass](https://lastpass.com)
* <img src="https://www.google.com/s2/favicons?domain=lockbin.com&sz=16" width="16" height="16"> [Lockbin](https://lockbin.com)
* <img src="https://www.google.com/s2/favicons?domain=mailbox.org&sz=16" width="16" height="16"> [Mailbox](https://mailbox.org)
* <img src="https://www.google.com/s2/favicons?domain=www.mailvelope.com&sz=16" width="16" height="16"> [Mailvelope](https://www.mailvelope.com)
* <img src="https://www.google.com/s2/favicons?domain=masterpasswordapp.com&sz=16" width="16" height="16"> [Master Password](http://masterpasswordapp.com)
* <img src="https://www.google.com/s2/favicons?domain=nixory.sourceforge.net&sz=16" width="16" height="16"> [Nixory](http://nixory.sourceforge.net)
* <img src="https://www.google.com/s2/favicons?domain=noscript.net&sz=16" width="16" height="16"> [NoScript](https://noscript.net)
* <img src="https://www.google.com/s2/favicons?domain=www.opendns.com&sz=16" width="16" height="16"> [Open DNS](https://www.opendns.com/home-internet-security)
* <img src="https://www.google.com/s2/favicons?domain=www.enigmail.net&sz=16" width="16" height="16"> [Open PGP](https://www.enigmail.net/index.php/en)
* <img src="https://www.google.com/s2/favicons?domain=oscobo.co.uk&sz=16" width="16" height="16"> [Oscobo Search Engine](https://oscobo.co.uk)
* <img src="https://www.google.com/s2/favicons?domain=ossec.github.io&sz=16" width="16" height="16"> [OSSEC](https://ossec.github.io)
* <img src="https://www.google.com/s2/favicons?domain=panopticlick.eff.org&sz=16" width="16" height="16"> [Panopticlick](https://panopticlick.eff.org)
* <img src="https://www.google.com/s2/favicons?domain=forums.peerblock.com&sz=16" width="16" height="16"> [Peerblock](http://forums.peerblock.com)
* <img src="https://www.google.com/s2/favicons?domain=www.pidgin.im&sz=16" width="16" height="16"> [Pidgin](https://www.pidgin.im)
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [Pixel Block](https://chrome.google.com/webstore/detail/pixelblock/jmpmfcjnflbcoidlgapblgpgbilinlem)
* <img src="https://www.google.com/s2/favicons?domain=privacy.com&sz=16" width="16" height="16"> [Privacy.com](https://privacy.com) - Virtual payment cards for online privacy and security.
* <img src="https://www.google.com/s2/favicons?domain=www.eff.org&sz=16" width="16" height="16"> [Privacy Badger](https://www.eff.org/privacybadger)
* <img src="https://www.google.com/s2/favicons?domain=privazer.com&sz=16" width="16" height="16"> [Privazer](http://privazer.com)
* <img src="https://www.google.com/s2/favicons?domain=protonmail.com&sz=16" width="16" height="16"> [Proton Mail](https://protonmail.com)
* <img src="https://www.google.com/s2/favicons?domain=www.qubes-os.org&sz=16" width="16" height="16"> [Qubes](https://www.qubes-os.org) - a security-focused desktop operating system that aims to provide security through isolation.
* <img src="https://www.google.com/s2/favicons?domain=chrome.google.com&sz=16" width="16" height="16"> [Script Safe](https://chrome.google.com/webstore/detail/scriptsafe/oiigbmnaadbkfbmpbfijlflahbdbdgdf?hl=en)
* <img src="https://www.google.com/s2/favicons?domain=securesha.re&sz=16" width="16" height="16"> [Securesha](https://securesha.re)
* <img src="https://www.google.com/s2/favicons?domain=www.silentcircle.com&sz=16" width="16" height="16"> [Silent circle](https://www.silentcircle.com)
* <img src="https://www.google.com/s2/favicons?domain=signal.org&sz=16" width="16" height="16"> [Signal](https://signal.org) - End-to-end encrypted messaging and calls.
* <img src="https://www.google.com/s2/favicons?domain=www.snort.org&sz=16" width="16" height="16"> [Snort](https://www.snort.org)
* <img src="https://www.google.com/s2/favicons?domain=spideroak.com&sz=16" width="16" height="16"> [Spideroak](https://spideroak.com)
* <img src="https://www.google.com/s2/favicons?domain=www.pelock.com&sz=16" width="16" height="16"> [Steganography Online Codec](https://www.pelock.com/products/steganography-online-codec)
* <img src="https://www.google.com/s2/favicons?domain=ssd.eff.org&sz=16" width="16" height="16"> [Surveilliance Self Defense](https://ssd.eff.org)
* [Tails](https://tails.boum.org)
* <img src="https://www.google.com/s2/favicons?domain=www.thunderbird.net&sz=16" width="16" height="16"> [Thunderbird](https://www.thunderbird.net/en-US/)
* <img src="https://www.google.com/s2/favicons?domain=www.torproject.org&sz=16" width="16" height="16"> [Tor Project](https://www.torproject.org)
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [uBlock Origin](https://github.com/gorhill/uBlock)
* <img src="https://www.google.com/s2/favicons?domain=wickr.com&sz=16" width="16" height="16"> [Wickr](https://wickr.com)
* <img src="https://www.google.com/s2/favicons?domain=www.mywot.com&sz=16" width="16" height="16"> [WOT](https://www.mywot.com)
* [ZMail](http://zmail.sourceforge.net)

## [↑](#-table-of-contents) 🔤 DNS
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Amass](https://github.com/owasp-amass/amass) - The amass tool searches Internet data sources, performs brute force subdomain enumeration, searches web archives, and uses machine learning to generate additional subdomain name guesses. DNS name resolution is performed across many public servers so the authoritative server will see the traffic coming from different locations. Written in Go.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Columbus Project](https://github.com/elmasy-com/columbus) - Columbus Project is an advanced subdomain discovery service with fast, powerful and easy to use API.
* <img src="https://www.google.com/s2/favicons?domain=www.merklemap.com&sz=16" width="16" height="16"> [Merklemap](https://www.merklemap.com/) - Discover and enumerate all subdomains associated with a website, including those not publicly advertised. Works by ingesting certificate transparency logs.

## [↑](#-table-of-contents) ⚓ Maritime

* <img src="https://www.google.com/s2/favicons?domain=www.vesselfinder.com&sz=16" width="16" height="16"> [VesselFinder](https://www.vesselfinder.com) - a FREE AIS vessel tracking web site. VesselFinder displays real time ship positions and marine traffic detected by global AIS network.


## [↑](#-table-of-contents) ✈️ Aviation / Flight Tracking

*Tools for tracking aircraft, flights, and aviation data.*

* <img src="https://www.google.com/s2/favicons?domain=www.adsbexchange.com&sz=16" width="16" height="16"> [ADS-B Exchange](https://www.adsbexchange.com/) - Unfiltered ADS-B flight tracking — no government or airline censorship of military/private flights.
* <img src="https://www.google.com/s2/favicons?domain=www.flightaware.com&sz=16" width="16" height="16"> [FlightAware](https://www.flightaware.com/) - Flight tracking and data platform with live maps, flight status, and airport information.
* <img src="https://www.google.com/s2/favicons?domain=www.flightradar24.com&sz=16" width="16" height="16"> [FlightRadar24](https://www.flightradar24.com/) - The most popular real-time flight tracker with coverage from 35,000+ ADS-B and MLAT receivers.
* <img src="https://www.google.com/s2/favicons?domain=opensky-network.org&sz=16" width="16" height="16"> [OpenSky Network](https://opensky-network.org/) - Non-profit providing open air traffic surveillance data collected by a global sensor network.
* <img src="https://www.google.com/s2/favicons?domain=www.planespotters.net&sz=16" width="16" height="16"> [Planespotters.net](https://www.planespotters.net/) - Aircraft photo database with registration, airline, and fleet information.
* <img src="https://www.google.com/s2/favicons?domain=adsb.one&sz=16" width="16" height="16"> [ADS-B One](https://adsb.one/) - Community-driven ADS-B aggregator providing unfiltered global flight data via free API.
* [Beholder](https://beholder.me) - Real-time global OSINT threat map aggregating aircraft, vessel, and satellite tracking with natural disaster, conflict, and environmental data on an interactive 3D globe.


## [↑](#-table-of-contents) 🪙 Cryptocurrency / Blockchain

*Tools for investigating cryptocurrency transactions, wallets, and blockchain activity.*

* <img src="https://www.google.com/s2/favicons?domain=www.blockchain.com&sz=16" width="16" height="16"> [Blockchain.com Explorer](https://www.blockchain.com/explorer) - Bitcoin and multi-chain blockchain explorer for transaction and address lookups.
* <img src="https://www.google.com/s2/favicons?domain=www.breadcrumbs.app&sz=16" width="16" height="16"> [Breadcrumbs](https://www.breadcrumbs.app/) - Blockchain investigation tool for tracing cryptocurrency transactions and identifying wallets.
* <img src="https://www.google.com/s2/favicons?domain=crystalblockchain.com&sz=16" width="16" height="16"> [Crystal Blockchain](https://crystalblockchain.com/) - Blockchain analytics platform for compliance, investigation, and risk assessment.
* <img src="https://www.google.com/s2/favicons?domain=etherscan.io&sz=16" width="16" height="16"> [Etherscan](https://etherscan.io/) - Ethereum blockchain explorer for transactions, tokens, smart contracts, and wallet analytics.
* [OXT](https://oxt.me/) - Bitcoin blockchain analysis tool with transaction graphs, wallet clustering, and privacy metrics.
* <img src="https://www.google.com/s2/favicons?domain=www.walletexplorer.com&sz=16" width="16" height="16"> [Wallet Explorer](https://www.walletexplorer.com/) - Bitcoin wallet clustering and tracking tool that groups addresses by owner.


## [↑](#-table-of-contents) 🧰 Other Tools

* <img src="https://www.google.com/s2/favicons?domain=aadinternals.com&sz=16" width="16" height="16"> [aadinternals](https://aadinternals.com/osint) - Provides tools and insights for advanced analysis and security testing of Azure Active Directory (AAD) and Microsoft 365.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [ArkhamMirror](https://github.com/mantisfury/ArkhamMirror) - Local-first AI document intelligence with offline RAG, contradiction detection, knowledge graphs, and vision AI table extraction.
* <img src="https://www.google.com/s2/favicons?domain=online-barcode-reader.inliteresearch.com&sz=16" width="16" height="16"> [Barcode Reader](http://online-barcode-reader.inliteresearch.com) - Decode barcodes in C#, VB, Java, C\C++, Delphi, PHP and other languages.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [BeVigil-CLI](https://github.com/Bevigil/BeVigil-OSINT-CLI) - A unified command line interface and python library for using BeVigil OSINT API to search for assets such as subdomains, URLs, applications indexed from mobile applications.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Cyberbro](https://github.com/stanfrbd/cyberbro) - A self-hosted application, available as a Dockerized, for effortless searching and reputation checking of observables. Extracts IoCs from raw input and check their reputation using multiple services.
* <img src="https://www.google.com/s2/favicons?domain=cybergordon.com&sz=16" width="16" height="16"> [CyberGordon](https://cybergordon.com) - CyberGordon is a threat intelligence search engine. It leverages 30+ sources.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [CrowdSec](https://github.com/crowdsecurity/crowdsec) - An open source, free, and collaborative IPS/IDS software written in Go, able to analyze visitor behavior & provide an adapted response to all kinds of attacks.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Datasploit](https://github.com/DataSploit/datasploit) - Tool to perform various OSINT techniques on usernames, emails addresses, and domains.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Dehashed CLI](https://github.com/hmaverickadams/DeHashed-API-Tool) - Command-line tool for searching breach databases via DeHashed API.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Discoshell](https://github.com/foozzi/discoshell) - A simple discovery script that uses popular tools like subfinder, amass, puredns, alterx, massdns and others
* <img src="https://www.google.com/s2/favicons?domain=www.dorkgpt.com&sz=16" width="16" height="16"> [Dorkgpt](https://www.dorkgpt.com) - Artificial intelligence that generates advanced search queries to find specific or hidden information on the internet.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [DuckDuckGo URL scraper](https://github.com/its0x08/duckduckgo) - A simple DuckDuckGo URL scraper.
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [FaviconHash](https://kriztalz.sh/favicon-hash/) - Generate favicon hashes of a website for use on Shodan, VirusTotal, Censys, ZoomEye or FOFA.
* <img src="https://www.google.com/s2/favicons?domain=find.osint-tool.com&sz=16" width="16" height="16"> [Find osint tool](https://find.osint-tool.com) - Searches multiple OSINT tools to find information across various sources.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [FOCA](https://github.com/ElevenPaths/FOCA) - Tool to find metadata and hidden information in the documents.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Glit](https://github.com/shadawck/glit) -  Retrieve all mails of users related to a git repository, a git user or a git organization.
* <img src="https://www.google.com/s2/favicons?domain=greynoise.io&sz=16" width="16" height="16"> [Greynoise](https://greynoise.io/) - "Anti-Threat Intelligence" Greynoise characterizes the background noise of the internet, so the user can focus on what is actually important.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [IntelHub](https://github.com/tomsec8/IntelHub) – Browser-based open-source OSINT extension. All analysis runs locally (no servers). Features include text profiler, metadata analyzer, site & archive analysis, reverse image search, crypto/telegram analyzers.
* <img src="https://www.google.com/s2/favicons?domain=www.hunch.ly&sz=16" width="16" height="16"> [Hunchly](https://www.hunch.ly/) - Hunchly is a web capture tool designed specifically for online investigations.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [IntellyWeave](https://github.com/vericle/intellyweave)  - AI-powered OSINT platform with GLiNER entity extraction, Mapbox 3D geospatial visualization, and multi-agent archive research across 30+ international archives.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [LinkScope Client](https://github.com/AccentuSoft/LinkScope_Client) - LinkScope Client Github repository.
* <img src="https://www.google.com/s2/favicons?domain=accentusoft.com&sz=16" width="16" height="16"> [LinkScope](https://accentusoft.com/) - LinkScope is an open source intelligence (OSINT) graphical link analysis tool and automation platform for gathering and connecting information for investigative tasks.
* <img src="https://www.google.com/s2/favicons?domain=www.maltego.com&sz=16" width="16" height="16"> [Maltego](https://www.maltego.com/) - Maltego is an open source intelligence (OSINT) and graphical link analysis tool for gathering and connecting information for investigative tasks.
* <img src="https://www.google.com/s2/favicons?domain=developer.mozilla.org&sz=16" width="16" height="16"> [Mozilla HTTP Observatory](https://developer.mozilla.org/en-US/observatory) - Observatory⁩ enhances web security by analyzing compliance with best security practices.
* <img src="https://www.google.com/s2/favicons?domain=obsidian.md&sz=16" width="16" height="16"> [Obsidian](https://obsidian.md) - Knowledge base and note-taking tool ideal for OSINT case management.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [OpenRefine](https://github.com/OpenRefine) - Free & open source power tool for working with messy data and improving it.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Orbit](https://github.com/s0md3v/Orbit) - Draws relationships between crypto wallets with recursive crawling of transaction history.
* [OSINT Framework](http://osintframework.com/) - Web based framework for OSINT.
* <img src="https://www.google.com/s2/favicons?domain=www.osint-tool.com&sz=16" width="16" height="16"> [OSINT-Tool](https://www.osint-tool.com/) - A browser extension that gives you access to a suite of OSINT utilities (Dehashed, Epieos, Domaintools, Exif data, Reverse image search, etc) directly on any webpage you visit.
* <img src="https://www.google.com/s2/favicons?domain=osint.sh&sz=16" width="16" height="16"> [OSINT.SH](https://osint.sh/) - Information Gathering Toolset.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [OsintStalker](https://github.com/milo2012/osintstalker) - Python script for Facebook and geolocation OSINT.
* <img src="https://www.google.com/s2/favicons?domain=www.outwit.com&sz=16" width="16" height="16"> [Outwit](http://www.outwit.com) - Find, grab and organize all kinds of data and media from online sources.
* <img src="https://www.google.com/s2/favicons?domain=kriztalz.sh&sz=16" width="16" height="16"> [PGPKeyAnalyser](https://kriztalz.sh/pgp-key-analyser/) - Analyse and view the details of a PGP key online without having to download the asc file.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Photon](https://github.com/s0md3v/Photon) - Crawler designed for OSINT
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Pyba](https://github.com/fauvidoTechnologies/PyBrowserAutomation/) - A browser automation framework which requires low-code to search the web and perform OSINT using DFS and BFS modes, ideal for exploratory tasks.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [pygreynoise](https://github.com/GreyNoise-Intelligence/pygreynoise) - Greynoise Python Library
* <img src="https://www.google.com/s2/favicons?domain=quickcode.io&sz=16" width="16" height="16"> [QuickCode](https://quickcode.io/) - Python and R data analysis environment.
* <img src="https://www.google.com/s2/favicons?domain=www.routerpasswords.com&sz=16" width="16" height="16"> [Router Passwords](https://www.routerpasswords.com) - Online database of default router passwords.
* <img src="https://www.google.com/s2/favicons?domain=serpapi.com&sz=16" width="16" height="16"> [SerpApi](https://serpapi.com/) - Scrapes Google search and 25+ search engines with ease and retruns a raw JSON. Supports 10 API wrappers.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [SerpScan](https://github.com/Alaa-abdulridha/SerpScan) - Powerful PHP script designed to allow you to leverage the power of dorking straight from the comfort of your command line. Analyzes data from Google, Bing, Yahoo, Yandex, and Badiu.
* <img src="https://www.google.com/s2/favicons?domain=sintelix.com&sz=16" width="16" height="16"> [Sintelix](https://sintelix.com/) - Sintelix is an open source intelligence (OSINT) and graphical link analysis tool for gathering and connecting information for investigative tasks.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [sn0int](https://github.com/kpcyrd/sn0int) - Semi-automatic OSINT framework and package manager.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [SpiderFoot](https://github.com/smicallef/spiderfoot) - SpiderFoot Github repository.
* <img src="https://www.google.com/s2/favicons?domain=www.spiderfoot.net&sz=16" width="16" height="16"> [SpiderFoot](https://www.spiderfoot.net) - SpiderFoot is an open source intelligence (OSINT) automation platform with over 200 modules for threat intelligence, attack surface monitoring, security assessments and asset discovery.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [SpiderSuite](https://github.com/3nock/SpiderSuite) - An advance, cross-platform, GUI web security crawler.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Sub3 Suite](https://github.com/3nock/sub3suite) - A research-grade suite of tools for intelligence gathering & target mapping with both active and passive(100+ modules) intelligence gathering capabilities.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [The Harvester](https://github.com/laramies/theHarvester) - Gather emails, subdomains, hosts, employee names, open ports and banners from different public sources like search engines, PGP key servers and SHODAN computer database.
* [Unfurl](https://dfir.blog/unfurl/) - Unfurl analyzes and breaks down URLs into useful forensic components for digital investigation.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Waybackurls](https://github.com/tomnomnom/waybackurls) - Fetch all URLs known by the Wayback Machine for a domain.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Zen](https://github.com/s0md3v/Zen) - Find email addresses of Github users urls and other data effortlessly


## [↑](#-table-of-contents) 🕵️ Threat Intelligence

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [Threat Actor Usernames Scrape](https://github.com/spmedia/Threat-Actor-Usernames-Scrape) - A collection of fresh intel and 350k+ threat actor usernames scraped from various cybercrime sources & forums.
* <img src="https://www.google.com/s2/favicons?domain=www.gitguardian.com&sz=16" width="16" height="16"> [GitGuardian - Public GitHub Monitoring](https://www.gitguardian.com/monitor-public-github-for-secrets) - Monitor public GitHub repositories in real time. Detect secrets and sensitive information to prevent hackers from using GitHub as a backdoor to your business.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [OnionScan](https://github.com/s-rah/onionscan) - Free and open source tool for investigating the Dark Web. Its main goal is to help researchers and investigators monitor and track Dark Web sites.
* <img src="https://www.google.com/s2/favicons?domain=onion.ail-project.org&sz=16" width="16" height="16"> [onion-lookup](https://onion.ail-project.org/) - Free online service and API for checking the existence of Tor hidden services (.onion address) and retrieving their associated metadata. onion-lookup relies on an private AIL instance to obtain the metadata.
* [OTX AlienVault](https://otx.alienvault.com/) - Open Threat Exchange is the neighborhood watch of the global intelligence community. It enables private companies, independent security researchers, and government agencies to openly collaborate and share the latest information about emerging threats, attack methods, and malicious actors, promoting greater security across the entire community.
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [PhishingSecLists](https://github.com/spmedia/PhishingSecLists) - This list is to be used with web scanning tools (Gobuster, ffuf, Burp Suite, DirBuster). These lists are specifically tailored and designed for fuzzing phishing, crypto scam landing pages, and other malicious sketch af websites. You can gain vaulable intel on successful hits.
* [REScure Threat Intel Feed](https://rescure.fruxlabs.com/) - REScure is an independent threat intelligence project which we undertook to enhance our understanding of distributed systems, their integration, the nature of threat intelligence and how to efficiently collect, store, consume, distribute it.

## [↑](#-table-of-contents) 🎮 Gaming Platforms

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [lol_monitor](https://github.com/misiektoja/lol_monitor) - Tool for real-time tracking of LoL (League of Legends) players gaming activities including detection when a user starts or finishes a match with support for email alerts, CSV logging, playtime stats and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [psn_monitor](https://github.com/misiektoja/psn_monitor) - Tool for real-time tracking of Sony Playstation (PSN) players gaming activities including detection when a user gets online/offline or plays games with support for email alerts, CSV logging, playtime stats and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [steam_monitor](https://github.com/misiektoja/steam_monitor) - Tool for real-time tracking of Steam players' gaming activities including detection when a user gets online/offline or plays games with support for email alerts, CSV logging, playtime stats and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [xbox_monitor](https://github.com/misiektoja/xbox_monitor) - Tool for real-time tracking of Xbox Live players gaming activities including detection when a user gets online/offline or plays games with support for email alerts, CSV logging, playtime stats and more

## [↑](#-table-of-contents) 🎵 Music Streaming Services

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [lastfm_monitor](https://github.com/misiektoja/lastfm_monitor) - Tool for real-time tracking of Last.fm users' listening activity including detection when user gets online & offline, pauses or resumes playback, all played songs, its duration, skipped songs, with optional auto-play, email alerts, CSV logging, session stats and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [spotify_profile_monitor](https://github.com/misiektoja/spotify_profile_monitor) - Tool for real-time tracking of Spotify users' activities and profile changes, including playlists, with support for email alerts, CSV logging, showing media in the terminal, detection of profile picture changes and more
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [spotify_monitor](https://github.com/misiektoja/spotify_monitor) - Tool for real-time tracking of Spotify friends' listening activity including detection when user gets online & offline, played songs, its duration, skipped songs, with optional auto-play, email alerts, CSV logging, session stats and more

## [↑](#-table-of-contents) 🎬 OSINT Videos

* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [Amazing mind reader reveals his ‘gift’](https://www.youtube.com/watch?v=F7pYHN9iC9I)
* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [Bendobrown](https://www.youtube.com/c/Bendobrown)
* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [Data to Go](https://www.youtube.com/watch?v=_YRs28yBYuI)
* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [SANS OSINT Summit 2021 (Playlist)](https://www.youtube.com/playlist?list=PLs4eo9Tja8bj3jJvv42LxOkhc2_ylpS9y)
* <img src="https://www.google.com/s2/favicons?domain=www.youtube.com&sz=16" width="16" height="16"> [See how easily freaks can take over your life](https://www.youtube.com/watch?v=Rn4Rupla11M)

## [↑](#-table-of-contents) ✍️ OSINT Blogs

* <img src="https://www.google.com/s2/favicons?domain=www.bellingcat.com&sz=16" width="16" height="16"> [Bellingcat](https://www.bellingcat.com/)
* <img src="https://www.google.com/s2/favicons?domain=www.einvestigator.com&sz=16" width="16" height="16"> [eInvestigator](https://www.einvestigator.com/)
* <img src="https://www.google.com/s2/favicons?domain=inteltechniques.com&sz=16" width="16" height="16"> [IntelTechniques](https://inteltechniques.com/)
* <img src="https://www.google.com/s2/favicons?domain=nixintel.info&sz=16" width="16" height="16"> [NixIntel](https://nixintel.info/)
* <img src="https://www.google.com/s2/favicons?domain=www.osinttechniques.com&sz=16" width="16" height="16"> [OSINT Techniques](https://www.osinttechniques.com/blog)
* <img src="https://www.google.com/s2/favicons?domain=publication.osintambition.org&sz=16" width="16" height="16"> [OSINT Ambition Publication](https://publication.osintambition.org/)
* <img src="https://www.google.com/s2/favicons?domain=www.osintteam.com&sz=16" width="16" height="16"> [OSINT Team](https://www.osintteam.com/)
* <img src="https://www.google.com/s2/favicons?domain=osintcurio.us&sz=16" width="16" height="16"> [OSINTCurious](https://osintcurio.us/)
* <img src="https://www.google.com/s2/favicons?domain=sector035.nl&sz=16" width="16" height="16"> [Sector035](https://sector035.nl/)
* <img src="https://www.google.com/s2/favicons?domain=www.skopenow.com&sz=16" width="16" height="16"> [Skopenow](https://www.skopenow.com/news)
* [Sleuth For The Truth](http://sleuthforthetruth.com/)
* <img src="https://www.google.com/s2/favicons?domain=blog.sociallinks.io&sz=16" width="16" height="16"> [Social Links](https://blog.sociallinks.io/)

## [↑](#-table-of-contents) 📦 Other Resources

* <img src="https://www.google.com/s2/favicons?domain=www.aware-online.com&sz=16" width="16" height="16"> [Aware-online.com](https://www.aware-online.com/en/osint-tools) - Curated collection of OSINT tools and methodologies for investigations.
* <img src="https://www.google.com/s2/favicons?domain=bit.ly&sz=16" width="16" height="16"> [Bellingcat's Online Investigation Toolkit](http://bit.ly/bcattools)
* <img src="https://www.google.com/s2/favicons?domain=docs.google.com&sz=16" width="16" height="16"> [Bellingcat Online Researcher Survey: Tool Wishes](https://docs.google.com/spreadsheets/d/1vNJRMrlwI7i06diBJtRJWrvt4YuPOqlbUV5o00P_YmE/edit#gid=1378107220) — Wishlist of OSINT tools from a February Bellingcat survey.
* <img src="https://www.google.com/s2/favicons?domain=cipherstick.tech&sz=16" width="16" height="16"> [Cipherstick](https://cipherstick.tech) - Free OSINT Puzzles - No Account Needed!
* <img src="https://www.google.com/s2/favicons?domain=www.osintdojo.com&sz=16" width="16" height="16"> [OSINT Dojo](https://www.osintdojo.com/resources/)
* <img src="https://www.google.com/s2/favicons?domain=t.me&sz=16" width="16" height="16"> [OSINT Belarus](https://t.me/s/osintby)
* <img src="https://www.google.com/s2/favicons?domain=www.bellingcat.com&sz=16" width="16" height="16"> [These Are the Tools Open Source Researchers Say They Need](https://www.bellingcat.com/resources/2022/08/12/these-are-the-tools-open-source-researchers-say-they-need/) — Results of a survey Bellingcat conducted in February 2022.
* <img src="https://www.google.com/s2/favicons?domain=osintupdates.com&sz=16" width="16" height="16"> [OSINT Updates - a free weekly newsletter for OSINTers](https://osintupdates.com/)

## [↑](#-table-of-contents) ⭐ Related Awesome Lists

* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-anti-forensic](https://github.com/remiflavien1/awesome-anti-forensic) by @remiflavien1
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-ctf](https://github.com/apsdehal/awesome-ctf) by @apsdehal
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-forensics](https://github.com/Cugu/awesome-forensics) by @cugu
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-hacking](https://github.com/carpedm20/awesome-hacking) by @carpedm20
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-honeypots](https://github.com/paralax/awesome-honeypots) by @paralax
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-incident-response](https://github.com/meirwah/awesome-incident-response) by @meirwah
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-lockpicking](https://github.com/fabacab/awesome-lockpicking) by @fabacab
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis) by @rshipp
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-pentest](https://github.com/enaqx/awesome-pentest) by @enaqx
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-privacy](https://github.com/Lissy93/awesome-privacy/) by @Lissy93
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-sec-talks](https://github.com/PaulSec/awesome-sec-talks) by @PaulSec
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-security](https://github.com/sbilly/awesome-security) by @sbilly
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence) by @hslatman
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [infosec reference](https://github.com/rmusser01/Infosec_Reference) by @rmusser01
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [personal-security-checklist](https://github.com/Lissy93/personal-security-checklist) by @Lissy93
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [SecLists](https://github.com/danielmiessler/SecLists) by @danielmiessler
* <img src="https://www.google.com/s2/favicons?domain=github.com&sz=16" width="16" height="16"> [security-list](https://github.com/zbetcheckin/Security_list) by @zbetcheckin

## License

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license.
