<pre>
                          (                             (     (
   (        (     *   ) )\ )                (         )\ )  )\ )
   )\       )\  ` )  /((()/( (   (   (      )\   (   (()/( (()/(
((((_)(   (((_)  ( )(_))/(_)))\  )\  )\   (((_)  )\   /(_)) /(_))
 )\ _ )\  )\___ (_(_())(_)) ((_)((_)((_)  )\___ ((_) (_))  (_))
 (_)_\(_)((/ __||_   _||_ _|\ \ / / | __|((/ __|| __|| |   | |
  / _ \   | (__   | |   | |  \ V /  | _|  | (__ | _| | |__ | |__
 /_/ \_\   \___|  |_|  |___|  \_/   |___|  \___||___||____||____|
</pre>

## Pro-tips
### Foreman's dev mode
We recommend using "Procfile" for foreman:

    bundle exec foreman start -f Procfile

This starts the following services:

* `bundle exec jekyll serve --watch`
* `bundle exec guard`

Then view the site at [http://localhost:4000](http://localhost:4000/)