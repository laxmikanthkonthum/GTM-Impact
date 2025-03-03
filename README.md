# Impact Technical Assessment 2025

**Overview**
This project demonstrates how to integrate Google Tag Manager (GTM) with a simple HTML page and capture query parameters from the URL and send it to GTM's data layer. When a button is clicked, the captured parameters are sent as part of an API request, and the response is logged in the console.

**How It Works**

1.  GTM is initialized in the head and noscript sections.
2.  Captures and stores query parameters (key and value) in dataLayer.
3.  When the button is clicked, the script retrieves the most recent stored values from dataLayer.
4.  If valid values exist, an API request is made to https://httpbin.org/get with the parameters.
5.  The response is logged in the console.

**How to Use**

1.  Open the webpage with query parameters in the URL, e.g.: https://laxmikanthkonthum.github.io/GTM-Impact/?key=test_key&value=test_value
2.  Click the "Click Here!" button.
3.  Open the browser console to see the logged API response.
