{
  "info": {
    "name": "New York Times Best Seller List Names",
    "_postman_id": "f594c19b-aafe-448b-861f-2259b9211ea9",
    "description": "The names service returns a list of Best Sellers list names. It includes in the response the type of list (weekly or monthly) and when it was first published and last published. Lists have been added and removed over time. For example the Food and Diet list was added in 2013 and the Children???s Chapter Books list was removed in 2012. The response also includes the list_name_encoded which you use when calling the details service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "books",
      "item": [
        {
          "id": "33385526-a072-4d37-b96e-db21dbbe2e05",
          "name": "GET_lists-names-format",
          "request": {
            "url": "http://api.nytimes.com/svc/books/v2/lists/names.json?api-key=%7B%7D&format=format",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The names service returns a list of Best Sellers list names"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40edde3e-3589-49a3-a37f-0d4bb9b2cd3e"
            }
          ]
        }
      ]
    }
  ]
}