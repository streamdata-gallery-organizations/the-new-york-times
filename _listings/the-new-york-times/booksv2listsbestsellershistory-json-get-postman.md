{
  "info": {
    "name": "New York Times Best Seller History List",
    "_postman_id": "b48d08bb-18ac-4d87-8d14-e4384142ee73",
    "description": "The Best Sellers history service returns books and their history on the NYT Best Sellers lists.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "books",
      "item": [
        {
          "id": "3321d5f6-30c6-4d61-9bc7-4e6e97fadc53",
          "name": "GET_lists-best-sellers-history-json",
          "request": {
            "url": "http://api.nytimes.com/svc/books/v2/lists/best-sellers/history.json?age-group=%7B%7D&author=%7B%7D&contributor=%7B%7D&isbn=%7B%7D&price=%7B%7D&publisher=%7B%7D&title=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Best Sellers history service returns books and their history on the NYT Best Sellers lists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "609198c3-3352-4b82-8e37-e61316aadcc6"
            }
          ]
        }
      ]
    }
  ]
}