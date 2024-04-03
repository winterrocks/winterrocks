# Embedded CC-BY-SA snippets remediation ideas

In case you have had your software codebase audited for open source components, you might have seen that there are hundreds if not thousands of line items in the audit report. 

The question is what you should be doing with those?

An example: CC BY-SA snippet (typically from StackOverflow) in a proprietary code, what can you do to fix this issue? 

Some ideas:
1. Is code copy-pasted or is the source used as an inspiration? Inspiration (no copy-paste) -> normally o.k.
1. Is the code very generic? -> if yes, normally o.k. 
1. Find out if StackOverflow is not the original source of the snippet. If snippet is originally coming from a source that has a permissive license -> typically o.k. 
1. Is your proprietary component something that can be open sourced?

    If yes -> package the component and make ready for release

    If no -> Remove and rewrite (a common remediation action)

Disclaimer #1: I am not a lawyer and this is just an example. Seek for legal advice if in doubt!

Disclaimer #2: Above are only some ideas how to remediate.

CC BY-SA: [Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/)


Edited from the original source: https://www.linkedin.com/posts/jarikoivisto_opensourcesoftware-oss-foss-activity-6776151135741874176-0WFL
