# dependency-injecting

Description:

- design pattern that has its roots in Java. It have service for complementatin needed dependencies.


- with reflect-metadata package we are able to extract specyfic metadata from objects( which are added ther for example when decorator is added, so we will use the decorator later).
- we are creating decorator factory that is function returning decorator, and adding types.
- creating dependencies.

Installation:

- $npm i $ tsc <file.ts> $ node <file.js>

Usage:

moarDeps.doSth();

moarDeps.noDeps.doSth();

moarDeps.oneDep.doSth();

moarDeps.oneDep.noDeps.doSth();


>>>> I'm MoarDeps!
I'm NoDeps!
I'm OneDep!
I'm NoDeps!

Easily addaptive code

Contributing:

You and your ideas are more than welcome here! You can grab issues, or just fork It and show me the results of your imagination.

Adam Tomaś

License: GNU GPLv3
