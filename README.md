# CURLQuery PHP Class

## Description
A simple OO PHP wrapper class for cURL.

## Usage
     // init CURLQuery object with an URL :
     $curlQuery = new CURLQuery( 'http://www.google.com/' );

     // use any PHP cURL options :
     $curlQuery->CURLOPT_RETURNTRANSFER = 1;

     // get response :
     $response = $curlQuery->doRequest();

