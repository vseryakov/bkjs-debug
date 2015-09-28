# Debugging module for node and backendjs

# Usage

 - `rungc()` - run V8 garbage collector on demand
 - `setsegv()` - install SEGV signal handler to show crash backtrace
 - `setbacktrace()` - install special V8-aware backtrace handler
 - `backtrace()` - show V8 backtrace from current position
 - `heapSnapshot(file)` - dump current memory heap snapshot into a file

# Author 

Vlad Seryakov

