<h1>基于Next.js和Node.js的电子产品电商网站及管理后台</h1>

<p><b>基于Next.js和Node.js的电子产品电商网站及管理后台</b> 是一个使用Next.js、Node.js和MySQL开发的<b>免费电商商店</b>。该应用程序完全从头开始构建（自定义设计），并且完全响应式。
Singitronic 是一个现代化的在线商店，专门销售各种电子产品。该项目的目标是创建一个现代化的Web应用程序，<b>遵循软件工程的关键阶段</b>。
我创建了这个在线商店作为我的软件工程学院考试的一部分，与 <b>Bojan Cesnak</b> - <a href="https://github.com/cesnak02" target="_blank">@cesnak02</a> 合作。除了应用程序，我们还创建了详细的<b>40页软件工程文档</b>。我们将在仓库描述中介绍文档的主要部分。软件工程文档的主要资源是Singidunum大学教授Violeta Tomašević的书籍《Razvoj aplikativnog softvera》。此外，Violeta Tomašević和Petar Kresoja的大学讲座在应用程序的实现过程中也给了我们很大的帮助。</p>

<h2>2. 软件工程过程</h2>
<p>在软件的设计和建模过程中，我们决定使用瀑布模型（cascade model）。我们选择它是因为它的简单性、易于项目监控和易于应用。瀑布模型可能是最古老的已发布模型。它最早于1970年发布，代表了高层次的抽象。模型中的各个阶段按顺序连接，模型本身组织得很好，只有在完成前一个阶段后才能进入下一个阶段。</p>

![cascade model photo](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/2c8546ba-b57f-4467-9db9-d09cec46beb2)

<h3>2.1. 定义里程碑</h3>
<p>里程碑是项目中的关键事件，告诉我们某个任务必须在什么日期完成。在这个阶段，我们为软件工程过程中的每个阶段定义了我们的里程碑。</p>
<h3>2.2. Plaky - 项目管理应用程序</h3>
<p>Plaky应用程序用于项目管理和项目跟踪。它是一个免费的应用程序，便于团队成员之间的协作，并支持一键导出项目报告。</p>

![plaky image](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/f670fe69-1037-4b8c-a522-047534398e0a)

<h2>3. 需求分析</h2>
<h3>3.1. 软件需求规范</h3>
<p>在这个阶段，我们定义了整个应用程序的所有功能性和非功能性软件需求。我们还定义了系统与环境的连接要求以及系统应满足的性能要求。</p>
<h3>3.2. 使用用例图建模系统</h3>
<p>用例图详细描述了系统在不同情况下的功能。它描述了每个情况中的步骤和参与者。用例图被用作进一步设计、实现和测试软件的基础。</p>

![use case diagram github](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/dc578826-4031-4b53-b54c-0c8af3e1710e)

<p>上图代表我们的<b>电商网站用例图</b>。在这里，我们还为管理员和用户定义了主要成功场景和替代场景。</p>
<h2>4. 系统设计</h2>
<p>系统设计是软件工程阶段，将概念和需求转化为具体的软件结构。它是定义软件系统的架构、组件和交互的战略过程，以满足特定的功能性和非功能性需求。在这个阶段，我们写了关于系统架构的类型。我们定义了前端和后端，并写了关于应用程序中前端和后端的结构。我们定义了数据结构、数据库结构和应用程序中的重要类型。</p>

<h2>5. 软件实现</h2>
<p>软件实现是将软件设计转化为功能性软件系统的过程。这是所有编程开始的地方。
在软件实现阶段，重要的是要注意内部文档。此文档包括提供组件基本信息和代码特定部分解释的标题和注释。由于这些元素，我们更容易管理代码，并且更好地理解我们所做的事情，这有助于更高效的工作和维护软件项目。</p>

![products component comments](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/86c22295-64c6-4328-a17a-8f4f0820b8f1)

<h2>6. 测试</h2>
<p>测试是由测试团队执行的正式过程，目的是确定测试程序的逻辑正确性和目的性。测试的重要性很大，因为它显著减少了软件公司在交付给客户后由于错误和软件故障而产生的损失。<b>我们手动完成了整个测试过程，并详细记录了所有内容。</b></p>

![testing script](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/abb8b25e-89e3-4c1e-a195-fff350d7405f)

<p>测试脚本代表测试执行的指令，清楚地展示了测试是如何一步一步进行的。它们提供了对测试的完全控制，因此，如果发生某些错误或取消，可以重复测试条件并将系统再次引导到该错误或取消。这是必要的，以确定问题的根源。
如上图所示，我们根据测试ID、输入数据、指令、预期结果、实际结果、附加评论、组件、方法和测试技术记录了每个测试示例。目前，我们的测试脚本有超过350个手动测试示例。</p>

![errors in testing script](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/507fa099-2039-47ce-a38b-209166a8d5c4)

<p>在软件测试过程中，我们记录了错误报告表单中发现的每个错误。如上图所示，每个错误都有其唯一的错误ID和详细的错误描述，包含：识别错误的日期、解决错误的日期、错误优先级、错误类型、文件名、测试阶段。</p>

<h3>6.1. 临时测试</h3>
<p>在应用程序中添加每个新功能后的第一步是临时测试。临时测试在非正式的氛围中进行。开发人员向小组展示代码，然后进行讨论。小组成员提问，开发人员回答，一起分析他们认为重要的各个实现方面，并尝试发现错误。
我们通过在每次添加新功能后检查代码并进行长时间的讨论来应用这种方法，并讨论可能出现的问题。</p>

<h3>6.2. 组件系统层次结构</h3>
<p>应用程序组件的组件系统层次结构是我们在Figma设计工具中创建的应用程序所有组件的完整草图。这个草图在测试时对我们非常重要，因为它提供了组件测试顺序的洞察。下图代表了我们从鸟瞰角度看到的组件系统层次结构：</p>

![application component system](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/6d4a009f-746e-4627-a0fd-acf6fc0f15de)

<h3>6.3. 单元测试</h3>
<p>我们应用程序的单元测试包括测试单个功能或应用程序组件，以确保每个组件都能独立正常工作。单元测试的目标是在开发的早期阶段识别和纠正错误，增加代码的可靠性，并促进未来应用程序的维护。</p>

![unit testing stats english](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/94ec4f61-698e-4954-ba35-1336e939864a)

<p>如上图所示，我们在103个总错误中发现了75个单元测试错误，这使得我们的单元测试效率最高，达到72.8%。在单元测试过程中，我们使用了黑盒和白盒方法。我们使用的测试技术是：</p>
<p>黑盒方法：</p>
<ol>
  <li><p>等价划分</p></li>
  <li><p>边界值分析 - BVA</p></li>
</ol>
<p>白盒方法：</p>
<ol>
  <li><p>语句覆盖</p></li>
  <li><p>决策覆盖</p></li>
  <li><p>条件覆盖</p></li>
</ol>

<h3>6.4. 集成测试</h3>
<p>在集成测试中，我们使用了“从下到上集成”的方法。这是集成测试中非常常用的方法。这种方法从系统层次结构中组织的主要程序所在的组件开始。测试从层次结构中位于最低级别的所有组件开始进行单元测试。然后，测试调用先前测试过的组件的下一个级别的组件。</p>

![integration testing stats eng](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/4375373b-b67d-4a11-bee4-ff55325c2db7)

<p>如上图所示，我们在103个总错误中发现了28个集成测试错误，这使得我们的集成测试效率为27.2%。</p>

<h3>6.5. 端到端测试</h3>
<p>端到端测试是最高级别的最终测试。它检查系统作为一个整体是否符合客户设定的规范请求。由于大多数功能性需求已经在较低级别的测试中得到验证，现在重点是非功能性需求，如速度、可靠性、效率等。</p>

<h3>6.6. 指定时间间隔的错误记录</h3>
<p>在测试过程中，我们按天记录了发现的错误。下图帮助我们了解测试的进展情况。</p>

![diagram about erros by days](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/1b99f3f8-d344-48a5-a973-6764b7e3f7bf)

<p>如上图所示，错误的数量逐日增加，因此测试必须继续。在4天的测试中，我们总共发现了103个错误。</p>

<h3>6.7. 错误分析</h3>
<p>在测试过程中，我们还进行了错误报告表单，这在测试的介绍章节中已经提到。该文档帮助我们显著记录了应用程序中最常见的错误类型，如下图所示。</p>

![error frequency](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/d90292b7-579d-4267-a88d-485ee70dc275)

<h2>Singitronic – 主要功能</h2>
<p>Singitronic 是一个基于Next.js和Node.js的全栈电商网站，带有<b>免费源代码</b>。我们的应用程序带有完全功能的管理面板，并且完全开源。我们的<b>免费在线商店网站</b>完全响应式并手动测试。您可以将我们的电商项目用作下一个项目的模板或样板。我们的电商商店模板和Next.js电商主题完全定制，满足您的所有需求。它可供<b>免费下载</b>，并可用作您未来项目的电商示例。</p>
<h3>Next.js 适合电商吗？</h3>
<p>Next.js 目前是开发自定义电商解决方案的最佳方式之一。它的优势包括提高性能、SEO友好、易于开发和部署、出色的开发者体验以及处理多功能和可扩展项目的能力。通过利用Next.js，开发者可以创建引人注目的Web应用程序，提供卓越的用户体验，同时保持最佳性能。</p>

<h2>逐步视频教程运行应用程序</h2>

[https://www.youtube.com/watch?v=Ry0aOMws0gE](https://www.youtube.com/watch?v=Ry0aOMws0gE)

<h2>使用说明</h2>
<ol>
  <li><p>要运行应用程序，您首先需要在计算机上下载并安装Node.js和npm。以下是安装教程的链接：<a href="https://www.youtube.com/watch?v=4FAtFwKVhn0" target="_blank">https://www.youtube.com/watch?v=4FAtFwKVhn0</a>。您也可以在这里下载它们：<a href="https://nodejs.org/en" target="_blank">https://nodejs.org/en</a></p></li>
  <li><p>在计算机上安装Node.js和npm后，您需要下载并安装MySQL。以下是安装MySQL的教程链接：<a target="_blank" href="https://www.youtube.com/watch?v=BxdSUGBs0gM&t=212s">https://www.youtube.com/watch?v=BxdSUGBs0gM&t=212s</a>。您可以在这里下载MySQL：<a href="https://dev.mysql.com/downloads/installer/" target="_blank">https://dev.mysql.com/downloads/installer/</a></p></li>
  <li><p>此步骤是可选的，但如果您没有数据库管理应用程序，强烈推荐使用。因为HeidiSQL对初学者友好且比其他数据库管理选项更易于使用。以下是下载和安装HeidiSQL的教程链接：<a href="https://www.youtube.com/watch?v=oJ24MyLeiPs" target="_blank">https://www.youtube.com/watch?v=oJ24MyLeiPs</a>，您可以在这里下载它：<a href="https://www.heidisql.com" target="_blank">https://www.heidisql.com</a></p></li>
  <li><p>在计算机上安装所有需要的程序后，您需要下载项目。下载项目后，您需要解压缩它。</p></li>
  <li><p>解压缩项目后，您需要在代码编辑器中打开项目文件夹，并在根目录中创建一个名为.env的文件。</p></li>
  <li><p>您需要在.env文件中放入以下代码，并将username和password替换为您的MySQL用户名和密码：</p></li>
</ol>

```
DATABASE_URL="mysql://username:password@localhost:3306/singitronic_nextjs"
NEXTAUTH_SECRET=12D16C923BA17672F89B18C1DB22A
NEXTAUTH_URL=http://localhost:3000
```

<p>7. 完成后，您需要在server文件夹中创建另一个.env文件，并放入与前一个.env文件中使用的相同的DATABASE_URL：</p>

```
DATABASE_URL="mysql://username:password@localhost:3306/singitronic_nextjs"
```

<p>8. 现在，您需要在项目根文件夹中打开您选择的终端并输入：</p>

```
npm install
```

<p>9. 现在，您需要使用终端导航到server文件夹并安装所有内容：</p>

```
cd server
npm install
```

<p>10. 您现在需要运行Prisma迁移。确保您在server文件夹中并输入：</p>

```
npx prisma migrate dev
```

<p>11. 接下来是插入演示数据。为此，您需要转到server/utills文件夹并调用insertDemoData.js：</p>

```
cd utills
node insertDemoData.js
```

<p>12. 现在，您可以返回到server文件夹并运行后端：</p>

```
cd ..
node app.js
```

<p>13. 在后端运行时，您需要打开另一个终端（不要停止后端）。在第二个终端中，您需要确保在项目根文件夹中并输入以下内容：</p>

```
npm run dev
```

<p>14. 打开 <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> 并查看实时效果！</p>

<h2>项目截图</h2>

<h3>首页</h3>

![singitronic home page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a48c092d-1f19-4bae-a480-0b5862630e1c)

<h3>商店页面</h3>

![singitronic shop page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/1133effb-0511-40c6-aee5-119404c5af34)

<h3>单个产品页面</h3>

![singitronic single product page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/443ea3e2-4d32-4d15-aa3b-436cbae0eade)

<h3>注册页面</h3>

![singitronic register page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/0052cc90-d61a-4a8c-b8d8-02cee1b45d13)

<h3>登录页面</h3>

![singitronic logic page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/7a377bb3-330f-43a4-860f-400bf7aa0f97)

<h3>搜索页面</h3>

![singitronic search page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/384c7f55-16ee-4966-b612-a34f5506af51)

<h3>愿望清单页面</h3>

![singitronic wishlist page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a20568d6-12fb-42e6-a5ef-583f6e79229a)

<h3>购物车页面</h3>

![singitronic cart page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/b9d326be-342c-4f6a-af64-34794f6c39eb)

<h3>结账页面</h3>

![singitronic checkout page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/a458d931-9df2-4e3d-bf3f-702c1a3ba9e9)

<h3>管理后台 - 所有订单页面</h3>

![singitronic admin orders page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/498b07f4-422c-46c5-b2e4-ed2a93306b7a)

<h3>管理后台 - 所有产品页面</h3>

![singitronic admin products page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/e26822ab-6c7e-4474-9161-288a5bb3476f)

<h3>管理后台 - 所有分类页面</h3>

![singitronic admin categories page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/9e4a54d7-5bbb-4f1b-bdab-43c1079510e1)

<h3>管理后台 - 所有用户页面</h3>

![singitronic admin users page](https://github.com/Kuzma02/Electronics-eCommerce-Shop-With-Admin-Dashboard-NextJS-NodeJS/assets/138793624/e14e8f2c-4377-42fd-b89b-d4868cc11b11)