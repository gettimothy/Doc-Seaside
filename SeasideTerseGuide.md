
# Table of Contents

1.  [SeasideTerseGuide](#orgd2979e6)
    1.  [Introduction](#org309b703)
    2.  [Todo](#org66ac0da)
    3.  [Builder](#org40d3cbe)
    4.  [RequestHandlerBrowser](#org7c5eb1a)
    5.  [Bibliography](#orgb90470a)


<a id="orgd2979e6"></a>

# SeasideTerseGuide


<a id="org309b703"></a>

## Introduction

    Doits for Seaside 


<a id="org66ac0da"></a>

## Todo

    
    WAJsonCanvas class builder.


<a id="org40d3cbe"></a>

## Builder

    
    This is a convenience class which provides a result of a rendering operation as a string. It is expected to be used like this:
    
    WAHtmlCanvas builder render: [ :html |
    	html anchor
    		url: 'htttp://www.seaside.st';
    		with: 'Seaside Homepage' ]
     '<a href="htttp://www.seaside.st">Seaside Homepage</a>' 
    See WABuilderCanvasTest for more examples.


<a id="org7c5eb1a"></a>

## RequestHandlerBrowser

    
    I am the Seaside Request Handler Browser, a user interface to Seaside's 
    request handler tree and configuration for each handler.
    
    Start me with
    
    	WARequestHandlerBrowser open


<a id="orgb90470a"></a>

## Bibliography

    https://github.com/gettimothy/Doc-Seaside

