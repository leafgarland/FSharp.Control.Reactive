### New in 2.4.0 - (Released 2014/10/14)
Updates courtesty of marklam:

* Changed the distinct functions to take F# functions
* Added a version of ofSeq which uses a scheduler (ofSeqOn)
* Reordered the parameters to scanInit to be more composable
* Corrected some spellings and added some tests

### New in 2.3.7 - (Released 2014/10/14)
* Updated to Rx 2.2.5
* Updated Paket bootstrapper

### New in 2.3.6 - (Released 2014/10/13)
* Now generating docs!

### New in 2.3.0 - (Released 2014/09/26)
* Add QueryBuilder
* Add many more wrappers to Rx from F#, thanks to Jared Hester!

**Breaking changes**
* New namespace is `FSharp.Control.Reactive`
* `Observable` module is no longer auto-opened with the namespace
* `Observable.zip` now takes parameters in the "correct" order of `obs1` then `obs2`
* `Observable.subscribe` has moved to `Observable.subscribeWithCallbacks`
* `Observable.subscribe` now takes the `onNext` callback only

**TODO**
* Add tests
* Add docs

### New in 2.2.131002 - (Released 2013/10/02)
* Restructure modules and namespaces to comply with F# coding guidelines

### New in 2.1.131002 - (Released 2013/10/02)
* Release of F# wrappers for Rx

### New in 2.0.121121-rc - (Released 2012/11/21)
* Release candidate for F# wrappers for Rx based on Rx 2.0-rtm

### New in 2.0.6-rc - (Released 2012/07/26)
* Initial NuGet release of F# wrappers for Rx 2.0-rc
