A sample todos rhomobile app
---

Install
===

```
$ gem install rhodes
```

Run
===

Run with RhoSimulator


Add this to `build.yml` file

```
env:
    paths:
        rhosimulator: <RhoSimulator folder>
```

Then, Run

```
$ rake run:android:rhosimulator 
$ rake run:iphone:rhosimulator
```
