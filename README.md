# mypost-ui-testing

A _Docker_ container for MyPost frontend _e2e_ and _karma_ testing using _ng-cli_.

Created for internal use; extends the `mypost-ui-ngx` container.

Includes:
```
java-8-openjdk-amd64
google-chrome
chromium-browser
```

To build a default container from the `Dockerfile` run:
```
docker build -t benboarder/mypost-ui-testing:latest .
```

To use the latest version run:
```
docker pull benboarder:mypost-ui-testing
```
