This is AdTech data analysis.

The data are presented in the file test_bundle_dataset.cvs and have the following structure:

- `bundle` - app ID. There are 2 bundle types: numeric (e.g., 1550782147) for iOS and string (e.g., com.miui.cleaner) for Android.
- `channel_type` - traffic source type: `app`, `ctv`, `web`, `mob_web`.
- `ssp` - name of the SSP where traffic was biught.
- `bid` - number of bids.
- `imps` - number of impressions.

There are 3 tasks to analyse data with `channel_type==app`:

1. Present bundle, bid and imp number distribution by OS for each SSP.
2. Present SSP distribution by bundles and number of bids and calculate imps for bundles with 5 SSPs available
3. Determine SSP with unique traffic.