### <font color = yellow>向已建好的仓库中上传文件：</font>

1. 先在要上传文件文件夹下使用git，在命令行输入：

   ```shell
   git clone https://github/用户名/仓库名.git
   ```

2. 进入在本地复制的仓库文件夹下：

   ```shell
   cd note(仓库名)
   ```

3. 把note文件夹下面的文件都添加进来

   ```c++
   git add *
   ```

4. git  commit -m "提交信息"

   ```shell
   git commit -m "20230421"
   ```

5. 提交(记得开加速器)

   ```shell
   git push -u origin main
   ```

   

### <font color = yellow> 新建仓库并上传文件：</font>

1. 先在github中创建一个新的仓库，并记录仓库地址：
   一般都只是后面的仓库名会变：
2. 然后重复上面的步骤





### <font color = Aqua>如果出现：</font>

```shell
fatal: unable to access 'https://github.com/xilengs/test.git/': The requested UR
L returned error: 502
```

可能是因为之前用过代理，先取消代理，再重复上述步骤：

```shell
git config --global --unset http.proxy
```

