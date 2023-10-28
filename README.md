# Template: Monorepo CI

A basic setup to run different github actions for different packages in a monorepo setup.


We have two packages:

```txt
 root                 
 └─packages/          
   ├─package-1
   | └─content.txt
   └─package-2
     └─content.txt
```

Each package containes a `content.txt`.
The two github actions are configured to trigger only if something in their package changed
