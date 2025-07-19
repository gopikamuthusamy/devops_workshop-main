name: Run Docker Build
on: [push]
jobs:
  run-docker:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v3
        
      - name: Run Docker Build
        run: docker image -t python