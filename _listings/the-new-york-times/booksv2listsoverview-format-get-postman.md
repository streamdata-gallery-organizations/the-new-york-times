{
  "info": {
    "name": "New York Times Best Seller List Overview",
    "_postman_id": "a8089700-aceb-4abc-b6e8-8a510d30e361",
    "description": "The overview service returns the top 5 books for all the Best Sellers lists.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "books",
      "item": [
        {
          "id": "9cab336a-df27-45cc-bb05-4918e2461e01",
          "name": "GET_lists-overview-format",
          "request": {
            "url": "http://api.nytimes.com/svc/books/v2/lists/overview.json?api-key=%7B%7D&format=format&published_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The overview service returns the top 5 books for all the Best Sellers lists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "085053f7-fecf-44de-bb0b-09c95ba16665"
            }
          ]
        }
      ]
    }
  ]
}