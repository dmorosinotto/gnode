
0.0.3 / 2013-10-31
==================

  * gnode: avoid adding the --harmony_generators flag when not supported
  * fallback: set `process.execPath` and `process.argv[0]` to the gnode binary
  * fallback, index: include the regenerator runtime immediately

0.0.2 / 2013-10-30
==================

  * fallback: add proper REPL support
  * fallback: add stdin piping support

0.0.1 / 2013-10-30
==================

  * gitignore: ignore ?.js files
  * gnode: add support for flags on gnode
  * gnode: move the --harmony_generators flag out into a variable
  * gnode: fall back to process.argv[0] for the node process
  * README++
  * add .gitignore
  * fallback: throw an error for REPL / stdin mode for now
  * gnode: only set GNODE_ENTRY_POINT if a 3rd argument was passed in
  * gnode: mark as executable
  * gnode: add comment
  * fallback: clean up the GNODE_ENTRY_POINT env variable
  * gnode: drop the "flag" stuff for now
  * initial commit
