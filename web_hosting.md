<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->

# Online activities: Website Hosting - Servers

## Summary of Issue: 

Hosting a website or a web service has an environmental impact. On this page, we provide a link to a service that estimates the cost of a website and a list of services that offer green web hosting or servers.

## Questions Raised:

In this page, we try to address the following issues:

1. "What is the carbon footprint for web hosting and web services?"
2. "Are there more sustainable hosting services that can be recommended?"

## Present situation

NIME.org is a fully static site built on Jekyll and forum.nime.org is a Discourse instance which requires a VPS ([video discussing setup as of July 2020](https://youtu.be/8p5HJh-DwBk)). At present we use the following hosting services:

- **Proceedings**: static data hosting (presently in an Amazon S3 bucket in US East N. Virginia region)
- **nime.org**: continuous integration from jekyll source on GitHub + static web hosting (presently hosted on Netlify free tier)
- **forum.nime.org**: virtual private server (presently hosted on DigitalOcean 1vCPU/1GB VPS in FRA1 region).

NIME does not use any traditional shared hosting services.

## Present Sustainability Notes

- **Digital Ocean**, does not have a sustainability statement, but users have been tracking energy sources for individual data centres. The FRA1 data centre appears to use 100% renewable energy ([source](https://www.digitalocean.com/community/questions/what-kind-of-electricity-do-you-run-on))
- **Amazon AWS**, has a goal of 100% renewable energy by 2025 ([source](https://sustainability.aboutamazon.com/environment/the-cloud)), not clear what the energy mix is for particular data centers. May be desirable to reduce use of AWS, both from a cost and sustainability perspective.
- **Netlify** has a [sustainability statement](https://www.netlify.com/sustainability/), which focuses on efficient computation of web services, not on achieving 100% renewable energy, they note that their [distributed infrastructure](https://community.netlify.com/t/is-netlify-powered-by-renewable-energy/3951) makes it hard to measure renewable energy usage. Could replace, but any use of cached/CDN backed static website could likely have the same issues and this is desirable for serving our main page to a global audience.

The proceedings (and supplementary files) requires around 20GB of disk space and bandwidth requirements are 80-120GB per month.

## Information and recommendations (TL;DR)

You can check the  impact of your website: https://www.websitecarbon.com/

-----

## Notes

Below a list of services that offer green hosting alternatives.


|Name          | Link                       |  How is it green  |   cost web hosting | Server         |      
|------------- | -------------              | -------------     |  -------------     |-------------   |
|       kualo  |https://www.kualo.co.uk     | 100% Green Powered|  3 (10gb)- 10 (50gb)/month| 24 month|
|netcetera     |https://www.netcetera.co.uk/| Zero Carbon Datacentre https://www.netcetera.co.uk/datacentre/#green| 3 (5gb) 6.60 (20 gb) per month https://www.netcetera.co.uk/hosting/ | 55 (8 tb 512gb ram) 110 (10 tb 128 gb ram)|
|erjjio|https://erjjiostudios.com/green-web-hosting/| 100% renewable energy, optimise it to reduce its carbon emissions, and plant trees on your behalf every month, partenship with https://edenprojects.org/|5(10 GB)/month'7 (Unlimited disk storage)||
|aiso|https://www.aiso.net/| solar panel system, according to their count is the equivalent of planting 8 acres of trees per year. Every hosting account with AISO is green and powered by on-site solar.| $6.25 (10 GB )|10 (30gb 1gb ram), 45 (50 gb  4 gb ram) (many packages, two are examples)|
|raidboxes|https://raidboxes.io/|https://raidboxes.io/it/wordpress-green-hosting/  reforestation of Eden Reforestation Projects, support the Get Mads initiative, rely on sustainable, certified green electricity from hydropower, (only wordpress)|15 per month (1wordpress website 5gb ssd)|-|
|greennet|https://www.greennet.org.uk/|Our primary servers are located in a London datacentre which buys its electricity from Scottish Power Renewables, generated from British on-shore and off-shore wind as well as some tidal and wave power sources.| £108.00 inc. VAT per year (1bg)||
|greenhost|https://greenhost.net/| 100% Renewable energy from local windmills Wooden, sustainable office building  Participating in multiple sustainability projects https://greenhost.net/blog/2018/02/22/making-greenhost-even-greener/| € 51.00 / year (1000 MB ), € 108.00 / year 5 GB  https://greenhost.net/products/hosting/|€ 5.75 / month  (5 GB )https://greenhost.net/products/vps/
|acornhost|https://www.acornhost.com/|Our web hosting is powered by 100% green energy from wind and solar sources. As a company, we also embrace sustainable practices like recycling and tele-commuting. |$8.95 5GB space 100 GB bandwidth||
|s-4.host|https://s-4.host/|100% Renewable energy,Heat recovery and reuse for 25,000 homes,  we will plant a tree in your name, stay with us for a year and we will plant three more, Ethical partnerships https://s-4.host/sustainability/|50,000 visits €10 per month||

## Contributor(s): 

- [Raul Masu](mailto:raul@raulmasu.org)
- [Charles Martin]() NIME webmaster

