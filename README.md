## Redirection using meta tag

**Meta tag redirection is a straightforward redirecting methods if we want our users to land on alternate website in some critical situations or it can be intentional.**


### syntax:
`<meta http-equiv="refresh" content="0; URL="target-page-url">`

**refresh**
: for redirection, value of `http-equiv=""` is set to *refresh*. This indicate that the page should refresh or redirected after a specified time.

`content=""`
: This provides information or instruction related to redirection process. Like it specifies time after which redirection has to be performed, and the url of target webpage in `URL=""` section.

**For example -**
`<meta http-equiv="refresh" content="3; URL="https://www.google.com/">`

This *meta* tag will tell the browser to redirect to *google.com* webpage after 3 seconds.