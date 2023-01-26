19 - learning automation + more



Valencia -> UCF CS


<!--START_SECTION:waka--><!--END_SECTION:waka-->

name: Work Stats Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.waka_39336938-a4e6-4a62-981b-0d4591396472 }}
