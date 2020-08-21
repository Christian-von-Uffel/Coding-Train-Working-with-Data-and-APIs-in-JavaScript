# Working with Data and APIs in Javascript

## fetch()

Fetch is a function (and API??) that lets you fetch things on the web: data, images, etc.

Used for fetching external resources.

Why would you want to fetch an external resource instead of hosting one yourself? Maybe you're not the owner of that resource. Maybe that resource can be changed or updated over time, and therefore using the fetch API would let you call the latest version of the asset you'd like to use, or maybe it's just the easiest way to grab a resource in the moment.

Details on the function is written up in depth on Mozilla's MDN docs here:
https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API

The syntax for using the fetch function/API is as follows:

You call the fetch function and enter the resource location as the parameter. You then call the "then" function as a followup to do whatever you want to come next.

### Comments on the Coding Train Tutorial for Fetch

This was an unusually lackluster tutorial from Coding Train. Not only did he not explain why we would use fetch instead of just loading the resources directly, he also didn't say why we wouldn't want to use fetch or the limitations of using fetch.
