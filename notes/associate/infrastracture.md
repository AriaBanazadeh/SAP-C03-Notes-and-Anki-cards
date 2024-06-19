AWS infrasatraucture can be broken down into **regions** and **edge-locations**.

Each region is separated from other regions in the sense that if it fails other regions wont fail with it. 

EAch region is composed of multiple **availability zones**.

Global resilient -> The service doesn't rely on any single or mulitple regions. in case of regional failure it would still function

Region resilient -> It relies on multiple regions but if avialiabilty zones stopped wokring it would still work

Availiability zone resilient -> It rlies on avaiiliability zones and it'll stop working if they fail

Each region has a region code and also a region name. Region code is used in CLI.
AWS edged locations are used for **distribution**

