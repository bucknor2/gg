---
title: Authentication
position_number: 2
parameters:
  - name:
    content:
content_markdown: >-
  You need to be authenticated for all API requests. You can generate an API key
  in your developer dashboard.
  Add the API key to all requests as a GET parameter.
  Nothing will work unless you include this API key
  {: .error}
left_code_blocks:
  - code_block:
    title:
    language:
right_code_blocks:
  - code_block: c(1:3)
    title: R
    language: bash
  - code_block: ' curl http://api.myapp.com/books?token=YOUR_APP_KEY'
    title: Curl
    language: bash

    
          
            
    

          
    
    
  
---
