Wikimedia Foundation Traffic Analyst task
============
If you're reading this, it's because you're applying for the Traffic Analyst role at the Wikimedia Foundation. Or because you work at the Wikimedia Foundation. Or because you were bored and on google.

Whichever it is, the below sections may be of some interest.

The scenario
================================================================================================
The Product Development team has asked you to give them some information about how people use our sites.
In particular, they're interested by:

1. How long do people spend on Wikipedia in a single session?
2. How many events happen in each session?
3. How much time do people spend per event within a session?

After much [wailing and gnashing of teeth](https://en.wikipedia.org/wiki/Data_wrangling), you extract a dataset,
stored imaginatively at <code>traffic_dataset.tsv</code> of unique identifiers and timestamps, down to 1-second
resolutions.

The questions
================================================================================================

Work out a way of splitting events into sessions, answer *one* of the three Product questions above, visualise the
result, and tell us:

1. How did you go about dividing user events into sessions?
2. Why did you pick this approach?
3. What other approaches did you consider, and why did you discount them?
4. Why did you pick the visualisation form that you did?
5. What other forms did you consider, and why did you discount them?

The process
================================================================================================
Take the provided dataset, answer the provided questions. You have 3 business days to work on this task. Please submit your solution (the codebase you used, your visualisation and the answers to the questions) to okeyes@wikimedia.org. Alternatively, you can share your solution with us as a link to a stand-alone repo (not forked from traffic_task).
