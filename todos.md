# Todos

## 1 Rate Limiting

Server still need to process request to check for rate limiting.  

The client request reaches server and then server checks for the rate limiting.  
My question is - any client can still bombard server with its requests, server will deny once rate limiting is reached but the point is request still reaches the server and server has to do work for the rate limit checks, this will keep the server busy all the time.  

## 2 DDoS Attack

## 3 Hot Path

A hot path is the most frequently executed, time-critical, or busiest part of a system or code.  

For example, hot path queries, how to optimize them?

## 4 Observability

Observability is the ability to understand a system's internal state by analysing its  
external outputs.

## 5 Chaos Monkey (by Netflix)

https://netflix.github.io/chaosmonkey/

## 6 Amazon SWF

## 7 browser security model - CORS, XSS, CSRF, RCE (Remote Code Execution)
