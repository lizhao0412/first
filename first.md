**Hello World**项目是计算机编程历史悠久的传统。这是一个简单的练习，让你开始学习新的东西。让我们开始使用GitHub！

您将学习如何：

* 创建并使用存储库
* 启动并管理一个新的分支
* 更改文件并将其推送到GitHub作为提交
* 打开并合并拉请求

# 什么是GitHub？

GitHub是用于版本控制和协作的代码托管平台。它可以让您和其他人在任何地方一起工作。

本教程教你如GitHub必需资源，分支，提交和拉请求。您将创建自己的Hello World存储库，并学习GitHub的Pull Request工作流程，这是一种流行的创建和查看代码的方式。

**无需编码**

要完成本教程，您需要一个[GitHub.com帐户](https://github.com/)和Internet访问。您不需要知道如何编写代码，使用命令行或安装Git（版本控制软件GitHub是基于Git的）。

> 提示：在单独的浏览器窗口（或选项卡）中打开本指南，以便在完成教程中的步骤时可以看到该指南。

# 步骤1.创建一个存储库
一个**库**通常用于举办单个项目。存储库可以包含文件夹和文件，图像，视频，电子表格和数据集 - 项目需要的任何内容。我们建议您添加一个自述文件或一个包含项目信息的文件。在创建新的存储库的同时，GitHub可以轻松添加一个。它还提供其他常见选项，如许可证文件。

您的`hello-world`存储库可以是您存储想法，资源，甚至与他人共享和讨论事物的地方。

**创建新的存储库**

1.在右上角，您的头像或识别符旁边，单击 然后选择新建存储库。  
2.命名您的存储库`hello-world`。  
3.写一个简短的描述。  
4.选择**使用README初始化此存储库**。

![](https://guides.github.com/activities/hello-world/create-new-repo.png)

单击**创建存储库**。<img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f389.png" width='15'>

# 步骤2.创建一个分支

**分支**是在不同版本的存储库上工作的方式。

默认情况下，您的存储库有一个分支，`master`它被认为是最终分支。我们使用分支机构进行实验并进行编辑`master`。

当您从分支机构创建分支机构`master`时，您正在制作一个副本或快照`master`。如果有人在您在分支机构工作时对`master`进行了更改，则可以提取更新。

该图显示：

* 该`master`分支
* 一个新的分支叫`feature`（因为我们在这个分支上做'功能工作'）
* 在`feature`合并入`master`之前所需要的过程

![](https://guides.github.com/activities/hello-world/branching.png)

你有没有保存不同版本的文件？就像是：

* `story.txt`
* `story-joe-edit.txt`
* `story-joe-edit-reviewed.txt`
分支机构在GitHub资源库中完成类似的目标。

在GitHub这里，我们的开发人员，作家和设计师使用分支机构为了保护错误修复和功能工作与我们的`master`（生产）分支机构分离开来。当变更准备就绪时，他们会将其分支合并入`master`。

**创建一个新的分支**

1.转到您的新仓库`hello-world`。  
2.点击文件列表顶部的分支：`master`。  
3.`readme-edits`在新的分支文本框中键入一个分支名称。  
4.选择蓝色**创建分支**框，或者在键盘上点击“Enter”。

![](https://guides.github.com/activities/hello-world/readme-edits.gif)

现在你有两个分支，`master`和`readme-edits`。他们看起来完全一样，但用不了多久！接下来，我们将添加我们对新分支的更改。

# 第三步.制作和提交更改

好样的！现在，你在`readme-edits`分支的代码视图中，它是`master`的副本。我们来进行一些编辑。

在GitHub上，保存的更改被称为提交。每个提交都有一个相关的提交消息，这是一个描述为什么进行特定更改的描述。提交消息捕获您的更改的历史记录，因此其他贡献者可以了解您所做的工作以及为什么。

**制作和提交更改**

1.点击`README.md`文件。  
2.点击<img src="https://github.com/lizhao0412/project/blob/master/31~6@XX39GPS0HWZG%7DM2E~Q.png?raw=true" width='15'>铅笔图标在文件视图的右上角进行编辑。  
3.在编辑中，写一下你自己。  
4.编写一条描述您更改的提交消息。  
5.单击**提交更改**按钮。

![](https://guides.github.com/activities/hello-world/commit.png)

这些更改将仅作为您的`readme-edits`分支上的README文件，因此现在该分支包含与`master`不同的内容。

# 步骤4.打开拉请求

很好的编辑！现在您已经在分支机构中对`master`进行了更改，您可以打开一个拉动请求。

拉请求是GitHub合作的核心。当您打开一个拉动请求时，您提出了更改，并请求某人审核并提取您的贡献，并将其合并到其分支中。拉请求显示来自两个分支的内容的差异或差别。更改，添加和减法显示为绿色和红色。

一旦提交，你可以打开一个拉动请求并开始讨论，甚至在代码完成之前。

通过在您的拉动请求信息中使用GitHub的[@mention system](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar)系统，您可以询问特定人员或团队，无论他们是在大厅与你相距10个时区。

您甚至可以在自己的存储库中打开提取请求，并自行合并。在开展大型项目之前，了解GitHub Flow是一个很好的方式。

**打开一个拉动请求以更改README**

点击图片查看大图

|分步|截图|
|:--:|:--:|
|点击<img src="https://github.com/lizhao0412/project/blob/master/46_VYY7@EXDH%5B(UT9(8%5D53E.png?raw=true" width='15'>**拉取请求**标签，然后从拉请求页面，单击绿色**新拉请求**按钮。|![](https://guides.github.com/activities/hello-world/pr-tab.gif)|
|选择您制作的分支，`readme-edits`与`master`（原始）进行比较。|![](https://guides.github.com/activities/hello-world/pick-branch.png)|
|查看比较页面上的差异更改，确保它们是您要提交的。|![](https://guides.github.com/activities/hello-world/diff.png)|
|当您确信这些是您要提交的更改时，请点击大的绿色**创建拉请求**按钮。|![](https://guides.github.com/activities/hello-world/create-pr.png)|
|给你的拉请求一个标题，并写一个简短的描述你的更改。|![](https://guides.github.com/activities/hello-world/pr-form.png)|

完成您的消息后，单击**创建提取**请求！

> **提示**：您可以使用[表情符号](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji)和[拖放图片和GIF](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/)到意见和引入请求。

# 步骤5.合并您的拉请求

在最后一步中，现在是将您的更改和`readme-edits`分支一起合并到您的分支`master`分支机构中。

1.单击绿色合并拉取请求按钮将更改合并到`master`。  
2.单击**确认合并**。  
3.继续删除分支，因为它的更改已经被并入，删除请使用紫色框中的**删除分支**按钮。

![](https://guides.github.com/activities/hello-world/merge-button.png)

![](https://guides.github.com/activities/hello-world/delete-button.png)

# 庆祝！

完成本教程后，您已经学会了在GitHub上创建项目并提出请求！<img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f389.png" width='15'><img src="https://assets-cdn.github.com/images/icons/emoji/octocat.png" width='15'><img src="https://assets-cdn.github.com/images/icons/emoji/unicode/26a1.png" width='15'>

这是您在本教程中完成的工作：

* 创建了一个开源存储库
* 开始和管理一个新的分支
* 更改了一个文件，并将这些更改提交给GitHub
* 打开并合并拉请求

看看你的GitHub配置文件，你会看到你的新[贡献广场](https://help.github.com/articles/viewing-contributions-on-your-profile/)！

要了解更多关于Pull Request功能的信息，我们建议您阅读“ [GitHub流程指南](https://guides.github.com/introduction/flow/)”。您也可以访问[GitHub Explore](https://github.com/explore)并参与开源项目<img src="https://assets-cdn.github.com/images/icons/emoji/octocat.png" width='15'>

> **提示**：有关如何开始使用GitHub的详细信息，请参阅我们的其他[指南](https://guides.github.com/)，[YouTube频道](http://youtube.com/githubguides)和[随选培训](https://services.github.com/on-demand/)。

