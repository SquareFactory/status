**Platform status:**

**Known issues**

- issue: datasets might not contain the underscore character

**2021-06-30 (v1.2.1)**

- **BREAKING CHANGE**: we are rotated all the datasets credentials to use the new `C2-XXXXXXXXX` format
- feature: file explorers now have a _parent directory_ button
- feature: project manager is now accessible directly through the project dashboard
- fixed: datasets credentials were sometimes incorrect
- fixed: the running experiment durations calculation were incorrect
- fixed: re-run experiment submit button now works as expected

**2021-06-28 (v1.2.0)**

- feature: experiments now supports custom datasets, code and artifacts mount points
- feature: experiment artifacts can now be downloaded
- feature: implement [experiments batching](https://docs.csquare.run/docs/experiments/run-an-experiment/#experiments-batching)
- feature: update [quickstart page](https://csquare.run/quickstart) to a brand new design
- feature: implement personal tokens management
- fixed: directories and files are now sorted alphabetically in dataset explorer
- fixed: prevent experiments experiments logs duplication

**2021-06-24**

- fixed: datasets creation sometimes fails
