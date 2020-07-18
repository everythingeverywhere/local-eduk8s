# local-eduk8s
To stand up eduk8s locally on minikube


Clone GitHub repo:

```copy
git clone
```

Deploy the minkube cluster and [eduk8s](https://docs.eduk8s.io/):

```copy
cd ./local-eduks8 && ./deploy.sh
```

> Add or delete workshops in `deploy.sh` at the bottom of the file like the example.

You can check eduk8s and retrieve the training session and password  with:

```
/.deploy_check.sh
```



Delete the cluster and eduk8s

```copy
./delete.sh
```

