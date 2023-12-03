| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | create pod nginx in yaml format with name "app", label "run:app" | create pod nginx | [app.yaml](app.yaml) |
| app-livenessProbe.yaml | create pod nginx in yaml format with name "app-livenessprob" namespace "demo" , with livenessProbe | pod  with livenessProbe | [app-livenessProbe.yaml](app-livenessProbe.yaml) |
| app-readinessProbe.yaml | create pod nginx in yaml format with name "app-readinessprob" , with livenessProbe and  readinessProbe | pod  with livenessProbe and readinessprob | [app-readinessProbe.yaml](app-readinessProbe.yaml) |