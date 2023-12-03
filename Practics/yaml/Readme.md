| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | create pod nginx in yaml format with name "app", label "run:app" | create pod nginx | [app.yaml](app.yaml) |
| app-livenessProbe.yaml | create pod nginx in yaml format with name "app-livenessprob" namespace "demo" , with livenessProbe | pod  with livenessProbe | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create pod nginx in yaml format with name "app-readinessprob" , with livenessProbe and  readinessProbe | pod  with livenessProbe and readinessprob | [app-readinessProbe.yaml](app-readinessProbe.yaml) |
| app-volumeMounts.yaml | create pod nginx in yaml format with name "app-volume", with livenessProbe,   readinessProbe, volumeMounts and volumes named "data" | pod with volumeMounts | [app-volumeMounts.yaml](app-volumeMounts.yaml) |
| app-cronjob.yaml | create cronjob in yaml  with name "app-cronjob" which can display every five minutes "Hello, world" in bash | cretate cronjob | [app-cronjob.yaml](app-cronjob.yaml) |
| app-job.yaml | create job in yaml  with name "app-job-rsync" which can reserve copy of "data-input" folder | create Job | [app-job.yaml](app-job.yaml) |
| app-multicontainer.yaml | create pod in yaml  with name "app-multi-containers" which contains two containers: nginx and debian | create multicontainer | [app-multicontainer.yaml](app-multicontainer.yaml) |