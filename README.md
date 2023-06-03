app.js->app.vue
router(设置主页) /home
home ['./views/home/index.vue']
|	
|	(加载组件)
|
|--> import Menuleft from '../../components/menuleft.vue'
|	|
|	| 	(路由)
|	|
|	|--> home ['./views/home/index.vue']
|	|--> goods ['./views/goods/index.vue']
|		|
|		|  (加载组件)
|		|
| 		|--> import Menuleft from '../../components/menuleft.vue'
|		|--> import HeadModule from '../../views/goods/head.vue'
|		|	|
|		|	|
|		|	|
|		|	|--> cart ['./views/cart/index.vue']
|  		|--> import ViewsModule from '../../views/goods/views.vue'
|
|--> import HeadModule from '../../components/head.vue'
|	|
|	|	(路由)
|	|
|	|--> cart ['./views/cart/index.vue']
|		|
|		|	(加载组件)
|		|
| 		|--> import Confirm from '../../components/confirm.vue'
|
|--> import LoginModule from '../../views/home/login.vue'|	|
|	|	(路由)
|	|
|	|--> register ['./views/register.vue']
|		|
|		|
|		|
|		|--> login ['./views/login.vue']
|
|--> import ViewsModule from '../../views/home/views.vue'
	|
	|	(加载组件)
	|
	|--> import MarketsModule from '../../views/home/markets.vue'
 	|--> import PromotionsModule from '../../views/home/promotions.vue'
	|	|
	|	|	(路由)
	|	|
	|	|--> timelimit ['./views/timelimit/index.vue']
	|		|
	|		|	(加载组件)
	|		|
	|		|-->   import ListModule from './list.vue'
  	|	
	|--> import GoodsModule from '../../views/home/goods.vue'  
	|	|
	|	|	(路由)
	|	|
	|	|--> goods ['./views/goods/index.vue']
	|		|
	|		|	(加载组件)
	|		|
	|		|-->  import Menuleft from'../../components/menuleft.vue'
	|		|-->	import HeadModule from '../../views/goods/head.vue'
	|		|	|
	|		|	| (路由)
	|		|	|
	|		|	|--> cart ['./views/cart/index.vue']
	|		|
 	|		|-->	import ViewsModule from 						|		|-->	'../../views/goods/views.vue'
	|	
	|--> import ShowcaseModule from '../../views/home/showcase.vue'
 	|--> import DownModule from '../../views/home/down.vue'


