SR-Sidekiq
==============

SR-Sidekiq is merely a fork of Sidekiq (v4.1.2).  All ruby code is the same with the exception that one or more classes have been modified to be more restrictive of what arguments can be passed in.

Specifically, workers can only receive numerical arguments to their `perform` methods.

All credits are directed to [Sidekiq](http://sidekiq.org/). This fantastic gem is authored by: Mike Perham, [@mperham](https://twitter.com/mperham) / [@sidekiq](https://twitter.com/sidekiq), [http://www.mikeperham.com](http://www.mikeperham.com) / [http://www.contribsys.com](http://www.contribsys.com)
