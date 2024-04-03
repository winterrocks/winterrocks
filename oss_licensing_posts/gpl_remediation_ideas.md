# Components under GPL: ideas how to remediate

In the series of sharing some open source issue remediation ideas, this time let's discuss what to do if in your code audit there are some full strong copyleft (e.g. GPL) components. This is a quite typical thing and therefore these components must be used properly. For these components you should find out:

1. Is the component running in a separate process?
1. How is the component accessed?
    - Inter-process communication (IPC), e.g. sockets, pipes typically o.k.
1. Is intimate knowledge needed about the GPL component?
1. Are there modifications?

If all above are o.k., i.e.
1. Yes
1. Component is accessed via IPC
1. No
1. No
Then normally the use is o.k., if not consider the following:

- Can the same functionality be found in another component that has a permissive license
- Can the proprietary code be released?
- Contact the code owner and ask to purchase a commercial license, but this carries a risk of revealing the potential GPL violation.

Disclaimer #1: I am not a lawyer and this is just an example. Seek legal advice if in doubt!

Disclaimer #2: Above are only some ideas on how to remediate.



Edited from the original source: https://www.linkedin.com/posts/jarikoivisto_opensource-lawyer-software-activity-6780799910900965376-Vgz8
