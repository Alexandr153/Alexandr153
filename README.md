<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ "waka_f52e18cc-7da9-49de-a23c-31de3e9aa2ed" }}
          GH_TOKEN: ${{ "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" }}
<!--END_SECTION:waka-->
