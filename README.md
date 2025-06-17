# GitOps / Flux

## Sample deploy

> export GITHUB_TOKEN=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  
> export GITHUB_USER=neilnx3  
> flux bootstrap github --owner=$GITHUB_USER --repository=gitops-workshop --branch=main --path=./clusters/my-cluster --components-extra=image-reflector-controller,image-automation-controller --personal  
