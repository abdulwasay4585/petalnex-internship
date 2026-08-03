# Lead Processing Workflow

## Overview

This project automates lead processing using n8n. It receives lead data
through a webhook, validates the input, enriches it using an external
API, stores it in Google Sheets, and notifies the sales team through
Gmail.

## Workflow

``` text
Webhook
   ↓
Clean Lead
   ↓
Validate (IF)
   ↓
HTTP Request (Random User API)
   ↓
Edit Fields
   ↓
Google Sheets
   ↓
Gmail
   ↓
Respond to Webhook
```

## Technologies

-   n8n Cloud
-   Webhook
-   HTTP Request
-   Google Sheets
-   Gmail
-   Random User API
-   Postman

## Features

-   Receives new leads
-   Validates input data
-   Enriches lead information
-   Saves data to Google Sheets
-   Sends email notifications
-   Returns a success or error response

## Sample Input

``` json
{
  "name": "Ali Ahmed",
  "email": "ali@gmail.com",
  "company": "ABC Ltd",
  "phone": "03121234567"
}
```

## Output

On success:

``` json
{
  "success": true,
  "message": "Lead Processed Successfully"
}
```

On failure:

``` json
{
  "success": false,
  "message": "Invalid Lead"
}
```

## Conclusion

This workflow demonstrates a complete lead processing automation by
integrating webhooks, an external API, Google Sheets, and Gmail into a
single n8n workflow.
