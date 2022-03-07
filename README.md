# sveltekit-292-break
Demos a break in behaviour between sveltekit 291 and 292.

To see the failing case:

 1. cd sveltekit-app
 2. npm run install
 3. npm run build

You will see an error about being unable to find package lodash

To see it work with version 291, change the sveltekit version in `sveltekit-app/package.json` to 291, then run

 1. npm run install
 2. npm run build

The build will work
