* install devcontainers cli:
`npm install -g @devcontainers/cli`
* 
docs: [link](https://github.com/devcontainers/cli)

* build base devcontianer in base_devcontainer folder: `devcontainer build --workspace-folder .`
```View build details: docker-desktop://dashboard/build/desktop-linux/desktop-linux/tsnte32oc4br871pwistdhme6
{"outcome":"success","imageName":["vsc-base_devcontainer-4d798f77395be3f1f63e7c635e3eb315d234531aaa92c4f771a528ffa3670c8a-features"]}
```
* run second devconainter using built image (via cli) in parent_devcontainer folder: `devcontainer up  --workspace-folder .`
* to connect to a running container: `docker exec -it <contianer id> bash`
