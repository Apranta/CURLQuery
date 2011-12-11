# CURLQuery PHP Class

## Description
A simple OO PHP wrapper class for cURL.

## Usage
     <?php
     
     require 'CURLQuery.php';
     
     // init CURLQuery object with an URL :
     $curlQuery = new CURLQuery( 'http://en.wikipedia.org/wiki/CURL' );

     // use any PHP cURL options :
     $curlQuery->CURLOPT_RETURNTRANSFER = 1;
     
     // get response :
     $response = $curlQuery->doRequest();
  
     // output response :
     echo $response;
     
     ?>

