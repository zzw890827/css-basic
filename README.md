### 知识点
1. 通过 text-transform 属性转换字体
   - none: 防止任何转型。
   - uppercase: 将所有文本转为大写。
   - uppercase: 将所有文本转为大写。
   - capitalize: 转换所有单词让其首字母大写。
   - full-width: 将所有字形转换成固定宽度的正方形，类似于等宽字体，允许对齐。拉丁字符以及亚洲语言字形（如中文，日文，韩文）
2. 文本装饰：通过 text-decoration 属性设置或者取消字体上的文本装饰，我们一般会使用这个属性去掉链接上的默认下划线。
   - none: 取消已经存在的任何文本装饰。
   - underline: 文本下划线。
   - overline: 文本上划线。
   - line-through: 穿过文本的线。
3. 行高：通过 line-height 属性来设置文本每行之间的高。浏览器默认字体大小为:16 px，而浏览器默认行高为：18 px。行高=上间距+文字大小+下间距。上下间距是相等的，如果字体大小为 20 px，它的父元素 div 的高度为 40 px，那么我们只需要设置行高为 40 px，就可以使文字相对于 div 盒子垂直居中。 
4. font简写：`{font:font-style  font-weight  font-size/line-height  font-family}`
5. 用 list-style-type 设置用于列表的项目符号的类型，例如无序列表的方形或圆形项目符号，或有序列表的数字，字母或罗马数字。
   - disc 无序列表的默认值，实心圆。
   - circle 空心圆。
   - square 实心方块。
   - square 实心方块。
   - lower-alpha 小写英文字母。
   - upper-alpha 大写英文字母。
