# Open Data

[The Open Data Handbook](http://opendatahandbook.org/en/index.html)

[Tim Berners-Lee (www founder) TED talk](http://www.ted.com/talks/tim_berners_lee_the_year_open_data_went_worldwide?language=en)

> Do you know exactly how much of your tax money is spent on street lights or on cancer research? What is the shortest, safest and most scenic bicycle route from your home to your work? And what is in the air that you breathe along the way? Where in your region will you find the best job opportunities and the highest number of fruit trees per capita? When can you influence decisions about topics you deeply care about, and whom should you talk to?

> New technologies now make it possible to build the services to answer these questions automatically. Much of the data you would need to answer these questions is generated by public bodies. However, often the data required is not yet available in a form which is easy to use. This book is about how to unlock the potential of official and other information to enable new services, to improve the lives of citizens and to make government and society work better.

> The notion of open data and specifically open government data - information, public or otherwise, which anyone is free to access and re-use for any purpose - has been around for some years. In 2009 open data started to become visible in the mainstream, with various governments (such as the USA, UK, Canada and New Zealand) announcing new initiatives towards opening up their public information.

Open Data may come in the form of a whole static database (CSV, EXCEL, TXT etc.), or it may be served as an API. An API will require some kind of request structure, such as location for a weather report, and should describe the structure of the response to expect. The open data documentation should also explain whether it includes geospatial information, and how frequently it is refreshed (if appropriate).

## Mashups, Web Mining, Harvesting, ... 

Web mining is defined as the use of data mining, text mining, and information retrieval techniques to extract useful patterns and knowledge from the Web.

A [mashup](http://en.wikipedia.org/wiki/Mashup_(web_application_hybrid), in web development, is a web page, or web application, that uses content from more than one source to create a single new service displayed in a single graphical interface. The term implies easy, fast integration, frequently using open application programming interfaces (open API) and data sources to produce enriched results that were not necessarily the original reason for producing the raw source data. The main characteristics of a mashup are combination, visualization, and aggregation. 

## Big Data

[Big data](http://en.wikipedia.org/wiki/Big_data) is an all-encompassing term for any collection of data sets so large and complex that it becomes difficult to process them using traditional data processing applications.

The world's technological per-capita capacity to store information has roughly doubled every 40 months since the 1980s; as of 2012, every day 2.5 exabytes (2.5×1018) of data were created; as of 2014, every day 2.3 zettabytes (2.3×1021) of data were created. In addition to volume, data is increasing in velocity and variety. This is partly due to the increased quantity and detail of sensing in the environment, and partly due to the increased amount of information derivable from connecting existing data. 

Operating on big data presents many technical challenges, exceeding the capacities of ordinary computing systems. Massively parallel architectures such as Google's MapReduce (see the open source Hadoop implementation) divide queries and processes in parallel (the map step) and later combine and deliver results (the reduce step). 

The vastness also permits new methods: inductive statistics and nonlinear system identification can infer laws (relationships, causal effects) from very noisy data sources, revealing relationships and supporting prediction. It constitutes a new wave of purely statistical artificial intelligence (see Google Translate and Watson). 

It has attracted billions of dollars of research funding in the last decade. 

The ethical and organizational challenge is determining who should own big data initiatives. Apart from the apparent difficulties in keeping personal data private, analysis of massive quantities of anonymous data may be enough to identify and deeply characterize individuals and groups. Analysis of massive quantities of anonymous search terms may be enough to predict major socio-political and economic events. 

Many believe that big data spells the end of theory. However critics point out that analytic algorithms can only predict a future similar to the past; but if system dynamics change, only theory can make predictions for the future. Combining analytics and theory is possible through simulations. Big science has also been criticized for lack of rigour, risk of bias, and buzzword mythology.

## Open Government Data APIs

[Open Government Across Canada](http://open.canada.ca/en/maps/open-data-canada)

[Ontario open data catalogue](http://www.ontario.ca/government/open-data-ontario)

[Open Data - Toronto](http://www1.toronto.ca/wps/portal/contentonly?vgnextoid=9e56e03bb8d1e310VgnVCM10000071d60f89RCRD) -- 311 (potholes, graffiti), bike share, off-street parking, TTC arrivals, etc.

[US government](https://www.data.gov/developers/apis)

[General governmental data](http://dev.socrata.com)

[United Nations, UNICEF, WHO](https://www.undata-api.org)

## Web-based Data/Service APIs

[Quick response test](http://httpbin.org)

There are now many open data application program interfaces (APIs) online for you to try. Many of them will require that you sign up to receive an ID. Not all are free. 

**Remember that many services will not expect you to be making large numbers or high rates of requests, and may even blacklist you if you try to do so.** Make your requests only as frequently as they are expected to change, and cache and re-use your results. 

**Also be sure to check that the data license is compatible with your intended use -- stay legal!**

[Weather](http://openweathermap.org/API) and [more options](http://superdevresources.com/weather-forecast-api-for-developing-apps/)

Example maxurl  request for openweathermap:

	{
		"http_method" : "get",
		"url" : "http://api.openweathermap.org/data/2.5/weather?q=Toronto&mode=json",
		"parse_type" : "json"
	}

[Google Data APIs](https://developers.google.com/gdata/docs/directory) -- includes Picasa, YouTube, Maps, Translate etc.
x
[Open Street Map](http://wiki.openstreetmap.org/wiki/API)

[NASA](http://open.nasa.gov/developer/)

### Aggregators

[ProgrammableWeb: "The world's largest API repository"](http://www.programmableweb.com/apis/directory)

[Datahub, the free, powerful data management platform from the Open Knowledge Foundation](http://datahub.io)

[DataLook is all about finding and sharing data-driven projects for social good](http://datalook.io)

[Many more examples from this blog post](http://blog.visual.ly/data-sources/)

---

### Acquiring data that has already been collected about you. 

Most major online services have an API, and many allow you to acquire data surrounding your activity. If you have a Google site, Android/iOS app, or even a Unity game, you might already be collecting data via [Google Analytics](https://developers.google.com/analytics/devguides/collection). If you host a site or code repository at [Github](https://developer.github.com/v3/), they have some great APIs you can use. Similarly for accessing your [Facebook data](https://developers.facebook.com/docs/graph-api/overview/). Look further afield-- even your bank might have an API you can use, or offer you the option to download transaction histories as a static database. 

Your phone is a rich source of personal data. [You can probably browse your phone's location history here](https://maps.google.com/locationhistory/b/0/) -- however there is not currently a working API to download this en masse. [(A possible workaround is described here)](https://shkspr.mobi/blog/2014/04/extracting-your-own-location-information-from-google-the-hard-way/). 

### Flickr

1. (Get an API key](https://www.flickr.com/services/apps/create/apply)
- You'll need to use an existing Yahoo/Flickr account, or sign up for one.
- Choose the *non-commercial* option
- Pick a name. Choose wisely -- you won't be able to change it. 
2. Copy the API key and secret!
3. Make sure you have [read the terms and conditions](https://www.flickr.com/services/api/tos/). In particular:
- Flickr users own the photos, and can set their own restrictions. You must abide by them.
- Best practice is to not cache images for more than 24 hours
- You must not use the images for commercial gain, nor to break any law.
- You shall place the following notice prominently on your application: "This product uses the Flickr API but is not endorsed or certified by Flickr."
4. The Flickr API works a little bit differently and instead of JSON it works with JSONP (JSON with Padding). The difference between these two formats is that JSONP returns a name of a function in its response and this function will handle the response data in your code.

### Google Maps

- [Some lovely examples](https://developers.google.com/maps/documentation/javascript/)
- Pretty generous: "If your site or application generates 25 000 map loads or more each day, for more than 90 consecutive days, we’ll get in touch with you to talk about payment."
- [Tutorial](https://developers.google.com/maps/documentation/javascript/tutorial)

[![xkcd](http://imgs.xkcd.com/comics/api.png)](https://xkcd.com/1481/)