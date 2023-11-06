# TokTik by Thanawat

Thanawat as in Thanawin and Nawat. Thanawat is not a real person. He can't hurt you :)

We have the following repos:

- [Deployment](https://github.com/thanawat-toktik/toktik-deployment)
- [Frontend](https://github.com/thanawat-toktik/toktik-frontend)
- [Backend](https://github.com/thanawat-toktik/toktik-backend)
- [Converter](https://github.com/thanawat-toktik/toktik-vid-convert)
- [Chunker](https://github.com/thanawat-toktik/toktik-vid-chonker)
- [Thumbnailer](https://github.com/thanawat-toktik/toktik-thumbnail)
- [2-line Dockerfile crontab](https://github.com/thanawat-toktik/toktik-scheduler)

To run the app, please clone the deployment repository. Ensure that you have Kubernetes installed and `kubectl` works. Ensure also that you have access to the private packages. Then, you can run the app on local by simply running the following commands.

```sh
cd /path/to/cloned/deployment/repo
kubectl apply -f ./k8s
```
