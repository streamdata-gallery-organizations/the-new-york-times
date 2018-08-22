---
swagger: "2.0"
x-collection-name: The New York Times
x-complete: 0
info:
  title: The New York Times Best Seller History List
  description: The Best Sellers history service returns books and their history on
    the NYT Best Sellers lists.
  termsOfService: https://developer.nytimes.com/tou
  version: 2.0.0
host: api.nytimes.com
basePath: /svc
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /topstories/v2/{section}.{format}:
    get:
      summary: Top Stories
      description: The Top Stories API returns a list of articles and associated images
        currently on the specified section.  Support JSON and JSONP.
      operationId: the-top-stories-api-returns-a-list-of-articles-and-associated-images-currently-on-the-specified-sect
      x-api-path-slug: topstoriesv2section-format-get
      parameters:
      - in: query
        name: callback
        description: The name of the function the API call results will be passed
          to
      - in: path
        name: format
        description: if this is JSONP or JSON
      - in: path
        name: section
        description: The section the story appears in
      responses:
        200:
          description: OK
      tags:
      - News
  /search/v2/articlesearch.json:
    get:
      summary: Article Search
      description: Article SearchWith the Article Search API, you can search New York
        Times articles from Sept. 18, 1851 to today, retrieving headlines, abstracts,
        lead paragraphs, links to associated multimedia and other article.
      operationId: article-search-requests-use-the-following-uri-structure
      x-api-path-slug: searchv2articlesearch-json-get
      parameters:
      - in: query
        name: api-key
        description: The API key
        type: string
        format: string
      - in: query
        name: begin_date
        description: 'Format: YYYYMMDD Restricts responses to results with publication
          dates of the date specified or later'
      - in: query
        name: end_date
        description: 'Format: YYYYMMDD Restricts responses to results with publication
          dates of the date specified or earlier'
      - in: query
        name: facet_field
        description: Comma-delimited list of facetsSpecifies the sets of facet values
          to include in the facets array at the end of response, which collects the
          facet values from all the search results
      - in: query
        name: facet_filter
        description: When set to true, facet counts will respect any applied filters
          (fq, date range, etc
      - in: query
        name: fl
        description: Comma-delimited list of fields (no limit)  Limits the fields
          returned in your search results
      - in: query
        name: fq
        description: Filtered search query using standard Lucene syntax
      - in: query
        name: hl
        description: Enables highlighting in search results
      - in: query
        name: page
        description: The value of page corresponds to a set of 10 results (it does
          not indicate the starting number of the result set)
      - in: query
        name: q
        description: Search query term
      - in: query
        name: sort
        description: By default, search results are sorted by their relevance to the
          query term (q)
      responses:
        200:
          description: OK
      tags:
      - News
  /books/v2/lists/best-sellers/history.json:
    get:
      summary: Best Seller History List
      description: The Best Sellers history service returns books and their history
        on the NYT Best Sellers lists.
      operationId: GET_lists-best-sellers-history-json
      x-api-path-slug: booksv2listsbestsellershistory-json-get
      parameters:
      - in: query
        name: age-group
        description: The target age group for the best seller
      - in: query
        name: author
        description: The author of the best seller
      - in: query
        name: contributor
        description: The author of the best seller, as well as other contributors
          such as the illustrator (to search or sort by author name only, use author
          instead)
      - in: query
        name: isbn
        description: International Standard Book Number, 10 or 13 digitsA best seller
          may have both 10-digit and 13-digit ISBNs, and may have multiple ISBNs of
          each type
      - in: query
        name: price
        description: The publishers list price of the best seller, including decimal
          point
      - in: query
        name: publisher
        description: The standardized name of the publisher
      - in: query
        name: title
        description: The title of the best sellerWhen searching, you can specify a
          portion of a title or a full title
      responses:
        200:
          description: OK
      tags:
      - Books
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---