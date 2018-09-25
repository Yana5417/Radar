####微信小程序canvas画雷达图
####功能：
  #####1.可绘制多边形
  #####2.可完全填充绘制图形
####调用方式：
    new Radar({
      canvasId: 'radarCanvas', // dom
      colors, // 绘制的颜色 []
      width: 260, // 绘制宽度
      height: 180, // 绘制高度
      categories: titleArr.reverse(), // 绘制标题
      data: countArr.reverse(), // 绘制数据比例
      initrad: initrad, // 绘制角度
    });
