# Ruby Performance Tools

## Terms

- Wall time

- CPU time

## Benchmark

- [evanphx/benchmark-ips](https://github.com/evanphx/benchmark-ips)
- [piotrmurach/benchmark-trend](https://github.com/piotrmurach/benchmark-trend)
- [piotrmurach/benchmark-malloc](https://github.com/piotrmurach/benchmark-malloc)
- [benchmark-driver/benchmark-driver](https://github.com/benchmark-driver/benchmark-driver)

## Trace

- [tmm1/rbtrace](https://github.com/tmm1/rbtrace)

## Profiling

- [rbspy/rbspy](https://github.com/rbspy/rbspy)
  Sampling profiler for Ruby.

- [ruby built-in profiler](https://github.com/ruby/ruby/blob/trunk/lib/profiler.rb)

- [tmm1/perftools.rb](https://github.com/tmm1/perftools.rb) for Ruby < 2.1

- [tmm1/stackprof](https://github.com/tmm1/stackprof)

- [ruby-prof/ruby-prof](https://github.com/ruby-prof/ruby-prof)

  C extension, support GraphViz.

- [tmm1/rblineprof](https://github.com/tmm1/rblineprof)

- [SamSaffron/flamegraph](https://github.com/SamSaffron/flamegraph)

#### Rack-based app

- [MiniProfiler/rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler)

## Memory

- [ko1/allocation_tracer](https://github.com/ko1/allocation_tracer)

- [SamSaffron/memory_profiler](https://github.com/SamSaffron/memory_profiler)

- [schneems/get_process_mem](https://github.com/schneems/get_process_mem)

## GC

- [ko1/gc_tracer](https://github.com/ko1/gc_tracer)
- [tmm1/gctools](https://github.com/tmm1/gctools) for Ruby 2.1, [not recommend for Ruby 2.5](https://github.com/tmm1/gctools/issues/16)

## Monitoring

- [Prometheus Ruby Client](https://github.com/prometheus/client_ruby)

- [Simple Graphite](https://github.com/imeyer/simple-graphite)

- [Raindrops](https://bogomips.org/raindrops/)

## Talks on performance, memories

- ["Performance Matters" by Emery Berger](https://www.youtube.com/watch?v=r-TLSBdHe1A)
- [RailsConf 2017: Your App Server Config is Wrong by Nate Berkopec](https://www.youtube.com/watch?v=itbExaPqNAE)
- [RailsConf 2017: Panel: Performance... performance](https://www.youtube.com/watch?v=SMxlblLe_Io)
- [RubyConf 2016: Halve Your Memory Usage With These 12 Weird Tricks](https://www.youtube.com/watch?v=kZcqyuPeDao)
- [Memory Fragmentation and Bloat in Ruby](https://www.youtube.com/watch?v=eBmM-yWPeMw)
- [How to Performance (at GORUCO in NYC)](https://speakerdeck.com/eileencodes/how-to-performance-at-goruco-in-nyc)

## Reading materials

* [Ruby 2.1: Out-of-Band GC](http://tmm1.net/ruby21-oobgc/)
* [Ruby 2.1: RGenGC](http://tmm1.net/ruby21-rgengc/)
* [Ruby 2.1: objspace.so](http://tmm1.net/ruby21-objspace/)
* [Ruby 2.1: Profiling Ruby](http://tmm1.net/ruby21-profiling/)
* [Ruby 2.1: Process.setproctitle()](http://tmm1.net/ruby21-process-setproctitle/)
* [Ruby 2.1: Process.clock_gettime()](http://tmm1.net/ruby21-process-clock_gettime/)
* [Ruby 2.1: Method Cache](http://tmm1.net/ruby21-method-cache/)
* [Nothing Lasts Forever: Symbol Collection in Ruby 2.2](http://www.schneems.com/2015/01/19/ruby-22-symbol-gc.html)
* [Unraveling String Key Performance in Ruby 2.2](http://www.schneems.com/2014/11/26/unraveling-string-key-performance.html)
* [36% smaller Rails memory footprint through Benchmarking](http://www.schneems.com/2014/11/07/i-ram-what-i-ram.html)
* [Benchmarking Rack Middleware](http://www.schneems.com/2014/10/31/benchmarking-rack-middleware.html)
* [Why does my App's Memory Use Grow Over Time?](https://www.schneems.com/2019/11/07/why-does-my-apps-memory-usage-grow-asymptotically-over-time/)

## People (A-Z)

* [Aaron Patterson (@tenderlove)](https://twitter.com/tenderlove)
* [Charles Nutter (@headius)](https://twitter.com/headius)
* [Chris Seaton (@ChrisGSeaton)](https://twitter.com/ChrisGSeaton)
* [Eileen M. Uchitelle (@eileencodes)](https://twitter.com/eileencodes)
* [Hongli Lai (@honglilai)](https://twitter.com/honglilai)
* [k0kubun (@k0kubun)](https://twitter.com/k0kubun)
* [Nate Berkopec (@nateberkopec)](https://twitter.com/nateberkopec)
* [Richard Schneeman 🤠 (@schneems)](https://twitter.com/schneems)
* [Sam Saffron (@samsaffron)](https://twitter.com/samsaffron)
* [Noah Gibbs (@codefolio)](https://twitter.com/codefolio)
