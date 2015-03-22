#Introduction

I wanted to create this space to gather random bits of information from conferences, web authors, web sites. Things that others have done and found good.
Accumulate all this goodness in one place and then sift through it and examine what different tools or process might be appropriate for my situation.
Clearly there are so many tools and process flows available. Some will work for us and some won't without (ahem) change.
This is not intended to be a recommendation of any tools, sites or process other than for my own purposes.

##Sketches of a workflow in Spain

###At a very high level here are some things we need to accomplish

1. Some build process completes
2. The build process completion triggers an event of calls on a module to initialize
3. this module or process then fires off s series of tasks
4. after these tasks complete results are generated
5. these results (metrics) are saved somewhere, somehow
6. these metrics (can be) compared to metrics from previous builds to show directional change or stasis
7. cumulative results should be available to interested teams or individuals in various formats (graphs, tabular data)

### Tools
    How do we get there -

#### Build

    Build tools will be the starter for the process. These are Java.
    Admittedly I didn't spend time searching for workflows built on Cruise Control or Clear Case either for that matter. But then why would I?
    We do know that Jenkins can call or start child processes or trigger workflows.

    1. Jenkins - widely adopted, lots of plugins, coming soon to a theater new you?
    2. Cruise Control - smaller user base, less plugins. Current state.


#### Measure

    There are lots of tools to get measurements and do other tricks. Some are free some not so much.

    1. WebPageTest
    2. Catchpoint
    3. Sitespeed.io
    4. Pagespeed
    5. YSlow




