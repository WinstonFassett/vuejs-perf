This is a fork of [vuejs.org](https://github.com/vuejs/vuejs.org) to attempt to investigate/optimize KnockoutJS performance issues.

Changes  
* Use rateLimit to throttle evaluation of filteredItems, which drives the loop in the UI.

Test here:  
http://winstonfassett.github.io/vuejs-perf/perf/todomvc-benchmark/index.html

Specify an "r" value in the querystring for repetitions:  
http://winstonfassett.github.io/vuejs-perf/perf/todomvc-benchmark/index.html?r=10

See the patched Knockout test app here:  
http://winstonfassett.github.io/vuejs-perf/perf/todomvc-benchmark/todomvc/knockoutjs/index.html

Original test can be run here:  
http://vuejs.org/perf/todomvc-benchmark/
