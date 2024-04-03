# LGPL licensed components remediation ideas

In the series of how to remediate open source SW issues, let's discuss what one needs to take into consideration when components under LGPL are found. 

Normally LGPL licensed components are found in every audit - luckily these are not that tricky, but there are some things one needs to find out:

1. Are there any modifications in the component?
1. How is the component linked?
    - Static linking or
    - Dynamic linking

Now, if there are any modifications, one needs to package the modified code and make it available under LGPL if requested. Of course if the modifications are for example bug fixes a good practice is to contribute them upstream.

For second point if static linking is used, is it possible to use dynamic linking instead?

If static linking is the only option, then LGPL behaves like a strong copyleft license.


Disclaimer #1: I am not a lawyer and this is just an example. Seek legal advice if in doubt!

Disclaimer #2: Above are only some ideas how to remediate.


Edited from the original source: https://www.linkedin.com/posts/jarikoivisto_opensource-lawyer-software-activity-6786264134523600896-P4fr
