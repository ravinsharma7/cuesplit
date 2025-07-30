# cuesplit
Code splitting for cuelang code.

# Why code splitting for cuelang
- make it easy to separate cue code without manual editing.
- reuse code from the command line without separate build process or creating another git project
- perform asynchronous/parallelized tasks without sacrificing unification checks after `cue eval`.
- code splitting also assist creating mono repos that share cuelang code without duplicating code.

# Footnote
- this project exists to support [cuerun](https://github.com/ravinsharma7/cuerun) functionality. split dependencies and code for `cue cmd tasks`.
- seperating them into a sub project helps me to focus without conflating the functionality between the boundaries.
- seperating them as another project also allows its binaries size to be seperated from upstream project.
- There is a [proposal](https://github.com/cue-lang/cue/issues/165) to add `cue query` syntax, which can query cue using some query syntax. if the query syntax can do that, this project might be sunsetted, or use that to build additional tooling on top of it.
  
# How to use
TBD
