Unit Test:
```
karma start karma.conf.js
```

End-to-end Test:
```
cd ../../json-server/
json-server --watch db.json
cd ../conFusion/
gulp watch
cd test
protractor protractor.conf.js
```
