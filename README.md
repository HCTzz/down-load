# up-load

> 下拉刷新组件【2020-10-26】


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

如需对功能进行调整，请修改源码重新打包。

#example

```
props: {
	onRefresh: {
	  type: Function,
	  required: false
	},
	rollEle:{
	  type:String,
	  required:false
	}
},
<down-load :on-refresh="onRefresh" roll-ele="#swiper-slide">
	<ul>
		<li v-for="i in list" :key="i">
			{{i}}
		</li>
	</ul>
</down-load>
```