# MaSVF Wiki on Eleventy Garden

See [MaSVF Wiki](https://github.com/peterkaminski/masvf-wiki) and [Eleventy Garden](https://github.com/binyamin/eleventy-garden) for background.

Let's see how they might work together!

Three ideas:

* Include the wiki into an Eleventy Garden `notes` directory as a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules). How easy it will be to do automated deployments with a submodule?
* Have a script (Python or other) that copies the wiki into an Eleventy Garden `notes` directory. A little clunky, but I think that would work well in automated deployments.
* Include the whole eleventy-garden superstructure in the wiki repo. Yuck, that would be a pain for other people not using Eleventy Garden and would distract from the intended interoperability for which MaSVF Wiki is chartered.
