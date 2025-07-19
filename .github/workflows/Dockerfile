name: Run Docker Build
on: [push]
jobs:
  run-Docker Build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Run Docker Build
        run: Docker Build -t python
