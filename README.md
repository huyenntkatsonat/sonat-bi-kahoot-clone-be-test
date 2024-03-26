## Install artillery
npm install -g artillery@latest

## Run the test 
artillery run testfilename -o outputfilename

Eg. artillery run load-test.yml -o load-report.json

## Convert json report into html
artillery report load-report.json
