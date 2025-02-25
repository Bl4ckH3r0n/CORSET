# CORSET (CORS Exploit Tactics)

## Overview

This repository contains a basic HTML proof of concept (PoC) to demonstrate Cross-Origin Resource Sharing (CORS). CORS is a security feature implemented by web browsers that allows or restricts web pages from making requests to domains other than the one from which the page was served.

In this PoC, we will showcase how a request to a server from a different origin can be allowed or blocked based on the CORS configuration of the server.

## What is CORS?

CORS is a mechanism that allows browsers to request resources from a domain other than the one that served the web page. When making a cross-origin request, the browser will send an "OPTIONS" request to the target server, and if the server supports the requested origin, it will respond with the appropriate headers to allow the request.
