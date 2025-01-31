# Protocol for Use Cases 

## Which scenario ?

To advance my research, we want to collect bug scenarios defined as follows:
(i) an original code version that, when executed, produces both an expected behavior and result;
(ii) a set of code changes;
(iii) a new code version incorporating these changes;
and (iv) running the new code version results in \textit{unexpected} behavior relative to the original (that we call \textit{bug} in the remainder of this paper), potentially causing (a) errors or (b) different behavior that operates but deviates from the orignal intended functionality.

### Criteria for Selecting this Bugs Scenario in my Research

In the context of this research, the following criteria apply to echo bugs:

 - Deterministic Behavior: The bug must produce consistent and reproducible results.

 - Compatible Versions: Both versions of the project must run on Pahro 12 or 13.

 - Baseline Independence: Bugs related to baselines are excluded.

- It must be programmatically reproducible( e.g we can start the program same of ``` Transcript open``` ) .


### How to share your scenario

You can add a problem to this repo and complete the templates.

If you have any questions, please send them to remi.dufloer@inria.fr
