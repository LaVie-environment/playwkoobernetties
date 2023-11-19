Resolutions:

```
    use nslookup to perform a manual DNS resolution test for registry-1.docker.io
    The service is in the default namespace, hence the 'k8sbook.default.svc.cluster.local' which is the full dns name was used.
```

Issues Encountered:

```
    kubelet  Failed to pull image "nigelpoulton/web-app:1.0": rpc error: code = Unknown desc = failed to pull and unpack image "docker.io/nigelpoulton/web-app:1.0": failed to resolve reference "docker.io/nigelpoulton/web-app:1.0": failed to do request: Head "https://registry-1.docker.io/v2/nigelpoulton/web-app/manifests/1.0": dial tcp: lookup registry-1.docker.io on 192.168.42.2:53: server misbehaving

```