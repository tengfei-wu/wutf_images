## wutf_images

我的图床仓库

## CDN jsdelivr加速github图床

如何把图片放到github repo不再赘述。图片路径格式如下：

```yaml
https://raw.githubusercontent.com/{user}/{repo}/main/{folderpath}/{filename}
```
如果希望使用jsdelivr的CDN，需要将上面图片路径转换为：

```yaml
https://cdn.jsdelivr.net/gh/{user}/{repo}/{folderpath}/{filename}
```
举例如下：

```python
## github原链接
https://raw.githubusercontent.com/tengfei-wu/wutf_images/main/emqx/deploy_1.5918cfd9.png
## 使用cdn加速链接：
https://cdn.jsdelivr.net/gh/tengfei-wu/wutf_images/emqx/deploy_1.5918cfd9.png
```
