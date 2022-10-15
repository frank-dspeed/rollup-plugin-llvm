# rollup-plugin-llvm
Compiler Feedback Interface Implementation for rollup 1:1 API for LLVM 

## Why?
LLVM is a Set of Tools written in c and c++ mostly and also rust but it got no module system this rollup plugin implements a ECMAScript driven llvm api as rollup plugin to get used with diffrent generateBundle hooks like rollup-plugin-c it allows to implement any language as also create modules for that language with rollup and its plugin system. 

Mainly used by https://github.com/stealify to enable modular platform builds of any code.

see also: rollup-plugin-gcc it is the same for gcc and rollup generateBundle hooks can use both llvm and gcc.

this is also a good starting point for a rust module system and tool chain.
