```bash
$ aws cloudformation deploy --template-file template.yaml --stack-name kakoten-front-prod --parameter-overrides $(cat prod.cfg)
```
