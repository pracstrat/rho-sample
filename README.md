A sample todos rhomobile app
---

Install
===

```
$ gem install rhodes
```

Run
===
```
$ rake run:<platform>
```

Run with RhoSimulator

Add this to `build.yml` file
```
env:
    paths:
        rhosimulator: <RhoSimulator folder>
```

Run RhoSimulator to simulate specific platform:

```
$ rake run:android:rhosimulator 
$ rake run:iphone:rhosimulator
```
