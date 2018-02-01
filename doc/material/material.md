# 1. 概述

- Material Design核心思想：Google认为现实世界中的材质触感是可以通过**纸片**的隐喻来表达的，想将物理世界的体验带进屏幕。去掉现实中的杂质和随机性，保留其最原始纯净的形态、空间关系、变化与过渡，配合虚拟世界的灵活特性，还原最贴近真实的体验，达到简洁与直观的效果。
  	 
	![](images/materialdesign-goals-landingimage_large_mdpi.png)

- 设计原则：实体感（**光效、表面质感、运动感**）

	 ![](images/materialdesign-principles-layersquares_large_mdpi.png)

- 设计环境：三维世界

	![](images/xyz.png)

- Material 属性：
	1. Z轴厚度为1dp，x、y轴高度、宽度均可改变
	
		![](images/2.png)
		
		<font color=#259b24 >上图（可取）</font>
		
		![](images/3.png)
		
		<font color=#e51c23 >上图（不可取）</font>

	2. 高度和阴影：阴影是由于相对高度（Z轴位置）而产生
	
		![](images/4.gif)

	3. 内容是被以任何形状和颜附在材料上面，并不会增加材料的厚度
		
		![](images/5.gif)

	4. 内容展示要被限制在材料范围里
		
		![](images/6.gif)
	
	5. 材料是实物，输入事件只影响材料的前景，不能穿过材料下面底部
		
		![](images/4.png)
		
		<font color=#259b24 >上图（可取）</font>
		
		![](images/5.png)
		
		<font color=#e51c23 >上图（不可取）</font>
	
	6. 利用不同的高度区分材料的层叠，防止占用相同的空间点
		
		![](images/6.png)
		
		<font color=#259b24 >上图（可取）</font>
		
		![](images/7.png)
		
		<font color=#e51c23 >上图（不可取）</font>
	
	7. 材料不能穿过其他材料
		
		![](images/7.gif)
		
		<font color=#e51c23 >上图（不可取）</font>

	8. 材料应该仅沿着它的水平面增长和收缩，决不能弯曲或折叠
		
		![](images/8.gif)
		
		<font color=#259b24 >上图（可取）</font>
		
		![](images/9.gif)
		
		<font color=#e51c23 >上图（不可取）</font>
	
	9. 材料可以分割和合并
		
		![](images/10.gif)
		
		<font color=#259b24 >上图（可取）</font>

- 高度和阴影：注意区分开层级，根据高度，进行深浅上色以达到阴影的效果
	
	![](images/2014101413.png)

	![](images/11.gif)

	![](images/3_7.png)
		
	<font color=#259b24 >上图（可取）</font>

	![](images/3_5.png)
		
	<font color=#e51c23 >上图（不可取）</font>
		
	![](images/3_6.png)
		
	<font color=#e51c23 >上图（不可取）</font>

- 各元素参考阴影：静态和动态两种情况下对比
	
	1. 应用条：4dp
	
		![](images/3_11.png)

	2. 浮动按钮：静态：2dp；敲击状态：8dp

		![](images/3_12.png)

	3. 浮动动作按钮（FAB）：静态：6dp；敲击状态：12dp
	
		![](images/3_14.png)

	4. 卡片：静态：2dp；选中状态：8dp	
		
		![](images/3_16.png)

	5. 菜单和子菜单：菜单：8dp；子菜单：9dp（为子菜单增加 1dp）

		![](images/3_18.png)

	6. 对话框：24dp

		![](images/3_19.png)

	7. 导航抽屉和右抽屉：16dp

		![](images/3_20.png)

	8. 刷新按钮：3dp

		![](images/3_22.png)

	9. 快速查询/搜索条：静止状态：2dp；滚动状态：3dp

		![](images/3_23.png)

	10. 切换按钮：1dp

		![](images/3_26.png)