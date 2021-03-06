通过项目 `Functional-Light-JS` 为例展示一次完整的翻译流程。 
### 一、把项目 Fork 到自己的仓库
### 二、认识 Issue 的各种状态
 在[目标翻译项目的 Issues 中](https://github.com/ikcamp/Functional-Light-JS/issues)提供了目前可认领分配的任务，任务采用文章的完整路径命名，同时可在列表中查看任务状态，如图所示。

![Issues列表](http://upload-images.jianshu.io/upload_images/1561693-af2aed51ffaa780b.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

 列表文章名称后面跟随着当前任务的状态，任务在进行到不同的阶段，Master 会根据进展情况进行手动状态同步，可变更的任务状态分为６种，如图所示。

![Labels的６种状态](http://upload-images.jianshu.io/upload_images/1561693-baa1163c6562f768.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 三、翻译认领
译者开始在 Issues 中选择准备认领的翻译任务，并在 Issue 下留言并附上翻译完成时间（格式：`翻译认领-2017-06-20`），Master 会确认认领并修改 Issue 状态为`正在翻译`。

![翻译认领.jpeg](http://upload-images.jianshu.io/upload_images/1561693-aaee23b3079fd146.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240) 

### 四、开始翻译

译者认领结束之后准备开始翻译，以 `foreword.md` 为例，Github 进入自己刚刚 fork 的仓库，找到：`Functional-Light-JS/2017.md`，选择 `Edit this file` ，如图所示。

![Edit this file](http://upload-images.jianshu.io/upload_images/1561693-8223509f752fa7da.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


Github 提供了在线编辑的功能，以在线功能为例，译者进入 `foreword.md` 的修改页面，开始翻译并产生修改信息（这里可能在 Commit 时并没有翻译完成，没关系，流程一致），选择 `Create a new branch for this commit and start a pull request`，并在分支名称栏填写对应的 Issue 名产生分支，如图所示。


![产生差异并创建分支](http://upload-images.jianshu.io/upload_images/1561693-d47f7a0d2151c4b5.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


单击上图中 `Propose file change` 绿色按钮，创建分支，译者确认是否发起 `Pull request`   。如果译者在本次创建分支的同时完成了翻译，可以直接跳到 `Pull request` 流程，否则译者需要自行回到创建的分支翻译文章，**直到翻译结束后**发起 `Pull request`，如下图所示。


![分支创建完毕，判断是否需要发起 Pull request](http://upload-images.jianshu.io/upload_images/1561693-2e35a3e110128ac4.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 五、完成翻译，发起 Pull request

译者在自建的分支翻译结束后，发起 `Pull request`，如下图所示。

![发起一个Pull request](http://upload-images.jianshu.io/upload_images/1561693-a93d18af5cc43ad8.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


创建一个新的 Pull Request 页面，选择 base 为 原项目的 `zh-cn` 主干，选择 compare 为创建的翻译文章分支（此处为`Functional-Light-JS/foreword.md`）。如下图：


![新建 Pull Request](http://upload-images.jianshu.io/upload_images/1561693-10d5aa43121b7937.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


如上图，单击底部的`Create pull request`绿色按钮，创建 PR。在 PR  上留言 `初稿翻译完成`，**并附上对应的Issue链接**， Master 收到留言会修改 Issue 的属性。


![翻译完成](http://upload-images.jianshu.io/upload_images/1561693-dd2be4fc70a3d134.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 六、认领校对
校对者前往 PR 留言认领校对，并附上校对完成时间（格式： `认领校对-2017-07-01`），Master 收到留言会确认校对的授权工作。此时，校对者就可以开始校对工作了。


![校对列表](http://upload-images.jianshu.io/upload_images/1561693-a568183ce7b0f6eb.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![校对认领](http://upload-images.jianshu.io/upload_images/1561693-96ab65d1f28119d6.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 七、开始校对
前往 `Pull request` 页面列表内选择认领的 PR，进入页面，点选`Files changed`查看变更内容，校对在问题行上填写批注建议。如下图所示。


![在PR中校对文章](http://upload-images.jianshu.io/upload_images/1561693-691db179469504ff.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 八、校对完成
校对者完成校对后，在该PR下留言`校对完成`，项目的 Master 确认并通知译者前往 PR 查看校对者留言信息，译者根据留言修改译文。译者自身确认修改完毕后，进入该 PR，留言`修改完毕`。（这里小组长要确保译者按照 PR 执行了对应修改，并确保译文的质量）。

![校对完成](http://upload-images.jianshu.io/upload_images/1561693-3207d2e37c3b2194.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 八、翻译完成
项目 Master 看到  PR  内的`修改完毕`留言，执行对应 PR 的合并，整块流程结束。