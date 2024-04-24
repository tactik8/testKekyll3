# Jekyll on Replit

This is a barebone template to get you started with Jekyll static site generator on Replit. It's ready to go so you can just hit run and start coding!

## Running the repl

Simply hit run!

## Installing Additional packages

To add packages to your Jekyll repl, we recommend using the Replit packager interface in the left sidebar or using `bundle install` in the shell. Check out the [Bundle docs here](https://bundler.io/v2.3/#getting-started).

To add gem-based theme, search for the theme using the Replit packager interface.

To add a regular theme, add the necessary folders(_layouts, _data, and _include) and files in the main home directory. Add your posts in the _posts directory.

**Warning: Avoid using `gem install` to add packages.**

Beacuse Jekyll repls use [Bundle](https://bundler.io/) under the hood to provide a consistent environment that tracks and installs the exact gems and versions needed, we recommend using `bundle install` instead of `gem install`, which may not work as expected.

## Help

If you need help you might be able to find an answer on our [docs](https://docs.replit.com) page. Feel free to report bugs and give us feedback [here](https://replit.com/support).