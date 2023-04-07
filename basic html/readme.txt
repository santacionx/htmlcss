 Networking and the Internet background

how internet works ? 

Internet History
    > 1958 bell labs modem
    > 1961- mit packet switching
    > 1968- arpanet
    > 1972 - ulca chat university internet nodes
    > 1974-vint cerf tcp

    server
    client
    isp's (tier1 isp)
    dns
    datacenter (aws, google cloud...)
 
 
web protocols
        tcp/ip 
        http
        dhcp
        ftp
        ssh
        smtp

web address 
    domain name - tld (icann)

ip address

        32 it, 4 word address (ipv4)
        unique defines a server , a cient, a node, or a router

        ipv6 - 128 bit (16 octet)

        ip allows:

            subnets
            gateways
            private isp

mac address

    hardware (network interface ) address : const for life time 
    used by all ieee 802 network technology

components of the web

    web pages : html,pdf,txt,contains style scripts... opened on browser
    web sites : collection of webpages
    web servers : host website 1 server multiple website, single website on multiple servers
    search engines
    application layer : thats what we work

web server architecture

        load balancer: assign application server to user requested
        application server : multiple servers after assigner server this server access the database and stores caches

search engines
    crawling 

how web technologies work ?

        hardware
        os
        server framework
        containers/servlets
        server applications

server side framework

        java 
        spring
        play
        jboss

        python
        flask
        django
        bottle

        ruby 
            rails

        php
        codeigniter
        laravel

        node.js 
            express
            hapi.js

client side framework

        html(markup)

        css (styling)
            sass
            less

        javascipt(scripting/events)
            jQuery
            angular
            react
            backbone
            knockout

Server side database

    RDBMS
        mysql
        postgres
        oracle
        ms database
    NOSQL
        Mongodb
        couchdb
        memcache
        redis

client side storage
 
     local storage
     session storagecookies
     indexedDB
     cookies 
     cache

Types of websites
    static websites
        all html contents is created and save on server
    dynamic website 
        conent is generated on demand for each user
    Responsive 
        reacts to user, and his screen size

RestFUL API's
 
     GET,POST,PUT,DELETE,PATCH

DATA EXCHANGE FORMATS
        JSON
        XML
        
WEB SITE DESIGN PRINCIPLES

        REACTIVE websites
        SINGLE-PAGE applications
        MVC, MVP,MVVM, MV,architecture
        WEB APP framework

LATEST DEVELOPMENTS

    virtual dom 
    shadowdom
    sockets 
    pub/subnets
    push notifications
    browser native api's (location and user data)


html : HYPER TEXT MARKUP LANGUAGE
current version: HTML5
    HYPERTEXT: LINKING OF MULTIPLE pages
    markup : USING TAGS WE CAN TELL ITS A PARAGRAPH, BUTTONS...
    TAGS: USED FOR markup

html page structure 
2 parts 
. head
. body
!doctype : tell using html 5
<html></html> tell its a startof html page and end of html page
tags: must start with alphabet or underscore
body tag used after head tag