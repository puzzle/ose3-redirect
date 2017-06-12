# OSE3 Redirect

Simply redirect all incoming traffic to `$REDIRECT` (must be set in build config)

```
oc new-app centos/nginx-18-centos7~https://github.com/puzzle/ose3-redirect.git
oc set env bc/ose3-redirect REDIRECT=domain.ch
```

