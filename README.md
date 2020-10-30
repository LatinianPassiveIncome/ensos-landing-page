# Enso Buro - Static Landing Page

## To upload to G-cloud

This project runs on `enso.buro@gmail.com`. To check which credential accounts you have, run:

```
gcloud auth list
```

To set up a new configuration, run:

`gcloud init`

I've already set a configuration for `enso-buro` on my pc. You can set one yourself by following the instructions of `gcloud init` and logging into `enso.buro@gmail.com`.

Then run:
```
npm run deploy
```
I've initially chose the region as (15) `us-east1`, for no particular educated reason.

## Git

Repo: `git@github.com:LatinianPassiveIncome/ensos-landing-page.git`
Main branch: Now github has default `main`, instead of `master`

## Sources / References
Since we do not have any node application running, I've uploaded an `app.yaml` with python27. Why? I followed this [ref](https://medium.com/codingurukul/how-to-deploy-web-app-on-google-app-engine-dcef5f53e89a). I also know that the Standard App Engine environment does (or did not in the past) support python3.
