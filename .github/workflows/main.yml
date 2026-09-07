name: LongCat Task

on:
  schedule:
    - cron: '*/15 * * * *'
  workflow_dispatch:

jobs:
  run-task:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v4
      
      - name: Run script
        run: echo "Hello LongCat AI"
