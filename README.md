#kgbnodes [![Build Status](https://travis-ci.org/kingbin/kgbnodes.png?branch=master)](http://travis-ci.org/kingbin/kgbnodes)

* **[Azure Site Running mongodb backed kgbnodes](http://kgbnodes.azurewebsites.net/)**
(gives an error on the mongodb cmd which is a good thing)


* **[mongodb db collections on kgbnodes](http://kgbnodes.azurewebsites.net/Collections)**
(collections on a mongodb)


#notes

#####Azure:
* It doesn't matter what you set in the start attribute, azure will automatically run app.js even though it uses package.json for dependencies.
* Any further pull requests after hooking up to MongoLab require a stop & start of the azure website for the db connection to reconnect.

