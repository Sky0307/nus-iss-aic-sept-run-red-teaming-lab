# This is the lab for AIC - Red Teaming

## Activate the virtual env `vpromptfoo`
1. `cd promptfoo`
2. `source ./bin/activate`
to deactivate: `deactivate`

to run the promptfoo config yaml:
`promptfoo redteam generate -c “/path/to/config/file/you/want/to/use”`

to generate the results:
`promptfoo redteam eval --verbose -j 1 -o results.csv`    

-j 1 means use only 1 thread i.e. no concurrency    
-o filename outputs the results to the specified file.
