A sample todos rhomobile app
---

Install(gem)
===

```
$ gem install rhodes
```

Run with [RhoSimulator](http://docs.rhomobile.com/rhodes/simulator)
===

If you have `rhodes` gem, then RhoSimulator is installed already

* Install(Mac)

[http://rhosimulator.s3.amazonaws.com/RhoSimulatorMac.zip](http://rhosimulator.s3.amazonaws.com/RhoSimulatorMac.zip)


* Add follow to `build.yml` file

```
env:
    paths:
        rhosimulator: <RhoSimulator folder>
```

* Run

```
$ rake run:android:rhosimulator 
$ rake run:iphone:rhosimulator
```
