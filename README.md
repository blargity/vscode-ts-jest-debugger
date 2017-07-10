# VSCode Typescript Jest Debugger issue

Reproduction case to demonstrate trouble with getting VSCode to debug Typescript Jest Tests.

This is a much simplified example of our configuration on a much larger project.

## Getting started

1. Clone the repository
2. Run `yarn`
3. Open VSCode
4. Run the `Tests` configuration

## Expected Behaviour

Jest tests run successfully and are able to be debugged

## Actual Behaviour

Unable to tell what's going on, tests don't seem to run. Even if I play with the configuration 4 different ways, I still cannot get the debugger to work.

What I'm trying to do is put a breakpoint in `add.test.ts` and see it get hit and no matter what I try I'm unable to do so.

Also with this configuration I'm unable to debug with the VSCode Chrome debugger and can't tell what's going on on there either, but am able to debug
in Chrome itself if I just load the URL from webpack dev server.
