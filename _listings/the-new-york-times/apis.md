---
name: The New York Times
x-slug: the-new-york-times
description: 'The New York Times: Find breaking news, multimedia, reviews & opinion
  on Washington, business, sports, movies, travel, books, jobs, education, real estate,
  cars & more at nytimes.com.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
x-kinRank: "9"
x-alexaRank: "117"
tags: The New York Times
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/apis.md
specificationVersion: "0.14"
apis:
- name: New York Times Top Stories
  x-api-slug: new-york-times
  description: The Top Stories API returns a list of articles and associated images
    currently on the specified section.  Support JSON and JSONP.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//topstories/v2/{section}.{format}
  tags: News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/topstoriesv2section-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/topstoriesv2section-format-get-openapi.md
- name: New York Times Article Search
  x-api-slug: new-york-times
  description: Article SearchWith the Article Search API, you can search New York
    Times articles from Sept. 18, 1851 to today, retrieving headlines, abstracts,
    lead paragraphs, links to associated multimedia and other article.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//search/v2/articlesearch.json
  tags: News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/searchv2articlesearch-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/searchv2articlesearch-json-get-openapi.md
- name: New York Times Best Seller History List
  x-api-slug: new-york-times
  description: The Best Sellers history service returns books and their history on
    the NYT Best Sellers lists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//books/v2/lists/best-sellers/history.json
  tags: Books
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsbestsellershistory-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsbestsellershistory-json-get-openapi.md
- name: New York Times Best Seller List
  x-api-slug: new-york-times
  description: The Books API has services for getting information about The New York
    Times Best Sellers Lists and Book Reviews.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//books/v2/lists.{format}
  tags: News,Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2lists-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2lists-format-get-openapi.md
- name: New York Times Best Seller List by Date
  x-api-slug: new-york-times
  description: You can optionally request an overview for a specific published date
    using the published_date query parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//books/v2/lists/{date}/{list}.json
  tags: Books
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsdatelist-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsdatelist-json-get-openapi.md
- name: New York Times Best Seller List Overview
  x-api-slug: new-york-times
  description: The overview service returns the top 5 books for all the Best Sellers
    lists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//books/v2/lists/overview.{format}
  tags: Books
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsoverview-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsoverview-format-get-openapi.md
- name: New York Times Best Seller List Names
  x-api-slug: new-york-times
  description: "The names service returns a list of Best Sellers list names. It includes
    in the response the type of list (weekly or monthly) and when it was first published
    and last published. Lists have been added and removed over time. For example the
    Food and Diet list was added in 2013 and the Children\u2019s Chapter Books list
    was removed in 2012. The response also includes the list_name_encoded which you
    use when calling the details service."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//books/v2/lists/names.{format}
  tags: Books
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsnames-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/booksv2listsnames-format-get-openapi.md
- name: New York Times Geographic API
  x-api-slug: new-york-times
  description: The Geographic API extends the Semantic API, using a linked data approach
    to enhance location concepts used in The New York Times' controlled vocabulary
    and data resources which combine them with the GeoNames database, an authoritative
    and free to use database of global geographical places, names and features.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//query.json
  tags: News,Geo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/query-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/query-json-get-openapi.md
- name: New York Times Most Shared by Section & Time Period
  x-api-slug: new-york-times
  description: With the Most Popular API, you can get links and metadata for the blog
    posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//mostpopular/v2/mostshared/{section}/{time-period}.json
  tags: News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostsharedsectiontimeperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostsharedsectiontimeperiod-json-get-openapi.md
- name: New York Times Most Emailed by Section & Time Period
  x-api-slug: new-york-times
  description: With the Most Popular API, you can get links and metadata for the blog
    posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//mostpopular/v2/mostemailed/{section}/{time-period}.json
  tags: News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostemailedsectiontimeperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostemailedsectiontimeperiod-json-get-openapi.md
- name: New York Times Most Viewed by Section & Time Period
  x-api-slug: new-york-times
  description: With the Most Popular API, you can get links and metadata for the blog
    posts and articles that are most frequently e-mailed, shared and viewed by NYTimes.co
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//mostpopular/v2/mostviewed/{section}/{time-period}.json
  tags: News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostviewedsectiontimeperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/mostpopularv2mostviewedsectiontimeperiod-json-get-openapi.md
- name: New York Times Move Review Search
  x-api-slug: new-york-times
  description: With the Movie Reviews API, you can search New York Times movie reviews
    by keyword and get lists of NYT Critics' Picks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//movies/v2/reviews/search.json
  tags: Movies,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/moviesv2reviewssearch-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/moviesv2reviewssearch-json-get-openapi.md
- name: New York Times The Semantic API
  x-api-slug: new-york-times
  description: The Semantic API complements the Articles API. With the Semantic API,
    you get access to the long list of people, places, organizations and other locations,
    entities and descriptors that make up the controlled vocabulary used as metadata
    by The New York Times (sometimes referred to as Times Tags and used for Times
    Topics pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//name/{concept-type}/{specific-concept}.json
  tags: Semantics,News
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/nameconcepttypespecificconcept-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/nameconcepttypespecificconcept-json-get-openapi.md
- name: New York Times Times Tag
  x-api-slug: new-york-times
  description: With the TimesTags API, you can mine the riches of the New York Times
    tag set. The TimesTags service matches your query to the controlled vocabularies
    that fuel NYTimes.com metadata. You supply a string of characters, and the service
    returns a ranked list of suggested terms.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc//timestags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/timestags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/timestags-get-openapi.md
- name: New York Times
  x-api-slug: new-york-times
  description: 'The New York Times: Find breaking news, multimedia, reviews & opinion
    on Washington, business, sports, movies, travel, books, jobs, education, real
    estate, cars & more at nytimes.com.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18820-new-york-times.jpg
  humanURL: http://nytimes.com
  baseURL: https://api.nytimes.com//svc
  tags: The New York Times
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/the-new-york-times/master/_listings/the-new-york-times/openapi.md
x-common:
- type: x-application-gallery
  url: http://developer.nytimes.com/gallery
- type: x-application-management
  url: http://developer.nytimes.com/apps/mykeys
- type: x-base
  url: http://api.nytimes.com
- type: x-curated-source
  url: http://bits.blogs.nytimes.com/2016/01/27/lyft-agrees-to-settle-class-action-lawsuit-with-california-drivers/
- type: x-blog
  url: http://open.blogs.nytimes.com/
- type: x-blog-rss
  url: http://open.blogs.nytimes.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/newyorktimes
- type: x-curated-source
  url: http://dealbook.nytimes.com/2013/06/04/salesforce-to-buy-exacttarget-for-2-5-billion/
- type: x-developer
  url: http://developer.nytimes.com
- type: x-documentation
  url: http://developer.nytimes.com/docs
- type: x-email
  url: ayuda@nytimes.com
- type: x-email
  url: accessibility@nytimes.com
- type: x-events
  url: http://developers.nytimes.com/events/
- type: x-explorer
  url: http://developer.nytimes.com/io-docs
- type: x-forum
  url: http://developer.nytimes.com/forum
- type: x-forum-rss
  url: http://developer.nytimes.com/forum.rss
- type: x-jobs
  url: http://developers.nytimes.com/careers/
- type: x-blog-rss
  url: http://www.nytimes.com/services/xml/rss/nyt/Technology.xml
- type: x-privacy
  url: http://www.nytimes.com/content/help/rights/privacy/policy/privacy-policy.html
- type: x-curated-source
  url: http://rss.nytimes.com/c/34625/f/640387/s/4ef17202/sc/13/l/0L0Snytimes0N0C20A160C0A40C150Ctechnology0Cmicrosoft0Esues0Eus0Eover0Eorders0Ebarring0Eit0Efrom0Erevealing0Esurveillance0Bhtml0Dpartner0Frss0Gemc0Frss/story01.htm
- type: x-selfservice-registration
  url: https://myaccount.nytimes.com/register
- type: x-terms-of-service
  url: http://developer.nytimes.com/Api_terms_of_use
- type: x-terms-of-service
  url: https://developer.nytimes.com/tou
- type: x-twitter
  url: https://twitter.com/nytimes
- type: x-website
  url: http://nytimes.com
- type: x-website
  url: http://nytimes.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---