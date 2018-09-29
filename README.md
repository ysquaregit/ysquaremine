# ysquaremine
This repo is to mine twitter data for disease classification based on geography.

The files contain Tweet Streaming code based on Tweety extraction package 

TwitterDisease_map1- module does the maping of various disease to its talked country 
TwitterDisease_Map1Count - module does the maping of the max talked about disease to its country respectivelty 


Data used from twitter are 
 The tweet and the location it was tweeted from 
 
 The location is changed to its coordinates (geoCoded) then the geocode are reversed to get a specific country for the tweet
 
 package used :
 Tweety
 reverse_geocode
 geopy.geocoders 
