{
  "info": {
    "name": "Google Safe Browsing API List Threats",
    "_postman_id": "79359c1c-4543-4749-9e4f-646cc5d443dc",
    "description": "Lists the Safe Browsing threat lists available for download.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "threats",
      "item": [
        {
          "id": "d5ada42f-016c-4061-954c-d85ad678a649",
          "name": "safebrowsing.threatLists.list",
          "request": {
            "url": "http://safebrowsing.googleapis.com/v4/threatLists",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the Safe Browsing threat lists available for download"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75645f24-3510-4c9f-ad83-38aea7804868"
            }
          ]
        }
      ]
    }
  ]
}