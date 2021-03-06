---
id: bd7188d8c242eddfaeb5bd13
title: 用热图可视化数据
challengeType: 3
forumTopicId: 301466
---

# --description--

**目标：** 在 [CodePen.io](https://codepen.io) 上实现一个功能类似 <https://codepen.io/freeCodeCamp/full/JEXgeY> 的 App。

在满足以下[需求](https://en.wikipedia.org/wiki/User_story)并能通过所有测试的前提下，你可以根据自己的喜好来美化你的 app。

你可以使用 HTML、JavaScript、CSS、以及基于 svg 的 D3 可视化库来完成这个挑战。该任务需要使用 D3 的坐标轴属性生成坐标轴，这个属性会自动生成沿轴的刻度。这些刻度是通过 D3 测试所必需的，因为它们的位置是用来确定图表元素的对齐方式。你可以在这里 <https://github.com/d3/d3/blob/master/API.md#axes-d3-axis> 获取关于生成坐标轴的信息。每次测试查询的元素都必须是非虚拟 DOM。 如果你使用了前端框架（例如 Vue），那么对于动态的内容测试结果可能不准确。我们希望最终能够兼容这些框架，但 D3 项目目前还不支持它们。

**需求 #1：** 我的热度图应该有一个具有`id="title"`属性的标题。

**需求 #2：** 我的热度图应该有一个具有`id="title"`属性的描述内容。

**需求 #3：** 我的热度图应该有一个具有`id="x-axis"`属性的 x 轴。

**需求 #4：** 我的热度图应该有一个具有`id="y-axis"`属性的 y 轴。

**需求 #5：** 我的热度图应该有一些`rect`元素来展示数据，他们具有`class="cell"`属性。

**需求 #6：** 这些单元格元素至少应该有 4 种不同的填充颜色。

**需求 #7：** 每个单元格元素都有这些属性`data-month`，`data-year`，`data-temp`，包含了它们相应的月份，年份和温度值。

**需求 #8：** 每个元素的`data-month`，`data-year`属性应该在数据范围内。

**需求 #9：** 我的热度图应该具有与 y 轴上的相应月份对齐的单元格。

**需求 #10：** 我的热度图应该具有与 x 轴上相应年份对齐的单元格。

**需求 #11：** 我的热度图应该在 y 轴上有多个刻度标签，并带有完整的月份名称。

**需求 #12：** 我的热度图应该在 x 轴上有多个刻度标签，年份在 1754 到 2015 之间。

**需求 #13：** 我的热度图应该有一个具有`id="legend"`属性的图例。

**需求 #14：** 我的图例应该包含一些`rect`元素。

**需求 #15：** 图例中的这些`rect`元素应该至少使用 4 种不同的填充颜色。

**需求 #16：** 我可以将鼠标悬停在某个区域上，并查看具有`id="tooltip"`属性的提示框，它会显示有关该区域的更多信息。

**需求 #17：** 我的提示框应该有一个`data-year`属性，它对应了当前激活区域的`data-year`属性。

以下是完成此项目所需的数据：`https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/global-temperature.json`

你可以 fork [这个 CodePen pen 项目](https://codepen.io/freeCodeCamp/pen/MJjpwO)来构建你的项目。或者你可以在任何你喜欢的环境中使用以下 CDN 链接来运行测试：`https://gitcdn.link/repo/freeCodeCamp/testable-projects-fcc/master/build/bundle.js`.

一旦你完成了本项目并且该项目所有测试运行通过，请提交项目的 URL。

# --hints--


# --solutions--

