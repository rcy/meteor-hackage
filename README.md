hackage
=======

Hack meteor packages more easily.

```
16:32 <neobii> I want to make something that will make exiting
               packages easier to modify and make pull requests
16:33 <neobii> cause a lot of times you are working on something
               and then you find a bug in the package
16:33 <neobii> but that means you have to fork that package
               somewhere else etc etc
23:22 <rcy> ok, thats a fun project
```

## usage

```
meteor create myapp
cd myapp
meteor add iron:router
hackage iron:router
```

At this point we have a iron:router fork with source in
`myapp/packages/iron-router` which we can hack on in the context of
our application and easily make pull requests.
