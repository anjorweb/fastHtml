# fastHtml
一个简单的psd直接导出html的工具

**适合单页面且采用DOM结构布局的H5页面，基于Canvas的H5请使用Flash2x+AnnieJS!**

**导出前的准备**

先对psd里图层做整理，文字要栅格化图层，图层也要栅格化，剪切蒙版也要格式化掉，只保留基本图层和分组结构

**使用**

``npm install //安装包 ``

``node app {psd文件路径} //文件路径参数可选，默认文件是001.psd``