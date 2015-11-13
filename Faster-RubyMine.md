**Rationale**

We want RubyMine to be as fast as possible.
There are a number of improvements that can make a big difference to the out of the box experience.

**Mechanism**

1. Increase Memory
1. Don't index all project directories
1. Disable plugins that you aren't going to use

**Increase Memory**

Edit the `rubymine.vmoptions` file located in `~/Library/Preferences/RubyMine80` as follows:

    -Xms2g
    -Xmx2g (or 4g)

Essentially you want to give RubyMine a 2GB JVM.
If you have an especially large project and you want to run code inspections for the whole project,
you may have to increase the maximum memory allocation to 4GB.

**Don't Index All Project Directories**

See [[Exclude Directories]]. Do _not_ skip this step.