# scroll-to-top
A scroll page/container to top button made with Vue2

一个点一下就能自动滚动到顶的小按钮。


## 使用

```
npm i vue-scroll-to-top
```

在 Vue 页面里

```
import ScrollToTop from '@/components/ScrollToTop'
components: { ScrollToTop },

&lt;template&gt;
   &lt;scroll-to-top right="150px"&gt;&lt;/scroll-to-top&gt;
&lt;/template&gt;
```

## 参数

1. scrollBox: // 滚动条所在的DOM对象或其选择器
    type: [String, Object],
    required: false,
    default: '.app-main'</pre>
    
2. animationTime: // 滚动到顶部的动画时间，单位为毫秒，100 到 200 之间。默认值为 150
    type: Number,
    required: false,
    default: 150</pre>
    
3. right: // 距离右边多远
    type: String,
    required: false,
    default: "100px"</pre>
    
4. bottom: // 距离下边多远
    type: String,
    required: false,
    default: "100px</pre>
    
