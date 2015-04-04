google-auth
================

This fork was created because the Google official `<google-signin>`, while quite comprehensive and powerful,
was not granular enough for the purposes which I needed.


`<google-auth></google-auth>` offers a granular and composable take. Use it as a building block to construct services which use multiple social login providers.

This is nothing more than a stripped down version of the official component with no default display or session management. The intended use case is for an application
which uses social login to allow quick account creation. In this context the extra features of the official component are actively unwanted.
Very few additive changes exist in this fork, although the imperative calling of signin and singout through the component now return promises.


**If you are looking to use google as you primary login provider and are not planning on mixing in other providers or a local auth strategy, you are probably better off using the
[signin button](http://googlewebcomponents.github.io/google-signin/components/google-signin/)**


See the [component page](http://themallen.github.io/google-signin) for documentation.
