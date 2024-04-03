# Embedded GPL (or other copyleft) component remediation ideas

In the series of sharing some open source issue remediation ideas, this time let's discuss what to do if in your code audit an embedded GPL component is found in your proprietary code. 

An embedded strong copyleft (e.g. GPLv2) item is an issue you need to act and the faster the better. Unfortunately the remediation options are quite limited:

1. Consider if the proprietary code can be open sourced. If yes, package the code and make available if asked or release proactively
1. If code cannot be open sourced the option is to get rid of the embedded strong copyleft component / snippet and this can be achieved by
    - Remove and rewrite (cleanroom)
    - Remove and replace with a component with similar functionality, but under a permissive license (BSD, MIT or similar)

Disclaimer #1: I am not a lawyer and this is just an example. Seek legal advice if in doubt!

Disclaimer #2: Above are only some ideas how to remediate.

Edited from the original source: https://www.linkedin.com/posts/jarikoivisto_opensource-lawyer-software-activity-6778236007973191680-1TOK
