#Introduction

I wanted to create this space to gather random bits of information from conferences, web authors, web sites. Things that others have done and found good.
Accumulate all this goodness in one place and then sift through it and examine what different tools or process might be appropriate for my situation.
Clearly there are so many tools and process flows available. Some will work for us and some won't without (ahem) change.
This is not intended to be a recommendation of any tools, sites or process other than for my own purposes.

### High level needs

Sketches of a workflow in Spain. At a very high level here are some things we need to accomplish

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

    Build tools will be the starter for the process. The following are Java.
    Admittedly I didn't spend time searching for workflows built on Cruise Control or Clear Case
    either for that matter. But then why would I?
    We do know that Jenkins can call or start child processes or trigger workflows.

    1. Jenkins - widely adopted, lots of plugins, coming soon to a theater new you?
    2. Cruise Control - smaller user base, less plugins. Current state.


#### Measure

    There are lots of tools to get measurements and do other tricks. Some are free some not so much.

    1. [WebPageTest](http://www.webpagetest.org)<http://www.webpagetest.org>
    2. [Catchpoint](http://www.catchpoint.com)
    3. [Sitespeed.io](http://www.sitespeed.io)
    4. Pagespeed
    5. [YSlow](http://www.yslow.com)

#### Task Runners

    Several options here. Gulp seems to be easier to understand and use. Not saying that Grunt is bad it's just
    some people like peas and others like carrorts. If you can't find a Gulp task to do what a Grunt task can you can
    always go get the Node package (npm) gulp-grunt and add it to your project.


#### References

    Some of the too many links and references found on the interwebs.





