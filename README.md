
``` sh
# Deploymentの作成
$ kubectl apply -f C:/kubernetes/deployment.yaml
deployment.apps/nginx-deploy created

# 確認
$ kubectl get pods

# Serviceの作成
$ kubectl apply -f C:/kubernetes/service.yaml
service/nginx-service created 

# 確認
$ kubectl get services

# 動作確認
http://localhost:30000/ にアクセス


# その他コマンド
https://kubernetes.io/ja/docs/reference/kubectl/cheatsheet/

```
