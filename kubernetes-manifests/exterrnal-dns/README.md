# External DNS

## external-dns.json

```bash
$ wget https://raw.githubusercontent.com/kubernetes-sigs/aws-alb-ingress-controller/v1.1.6/docs/examples/external-dns.yaml
```

modify the followings,
- Set `namespace: kube-system` to namespaced resources
- `external-dns`'s image tag, update version.

## Documents

- [external\-dns/aws\.md at master · kubernetes\-sigs/external\-dns](https://github.com/kubernetes-sigs/external-dns/blob/master/docs/tutorials/aws.md#iam-permissions)
- [Setup \- AWS ALB Ingress Controller](https://kubernetes-sigs.github.io/aws-alb-ingress-controller/guide/external-dns/setup/#role-permissions)
