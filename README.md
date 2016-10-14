# eswitch
#### 开始使用
```
<link rel="stylesheet" href="../dist/eswitch.min.css" />

```
##### 注意：label的for属性一定要指向对应input的id属性，不然将会没有效果
#### 1、默认（default）
```
<div class="e-switch e-default">
	<input type="checkbox" id="switch-default" />
	<label for="switch-default"><span class="e-btn-round"></span></label>
</div>
```
##### 1.1、checked
```
<div class="e-switch e-default">
	<input type="checkbox" id="switch-default3" checked="checked" />
	<label for="switch-default3"><span class="e-btn-round"></span></label>
</div>
```
##### 1.2、disabled
```
<div class="e-switch e-default">
	<input type="checkbox" id="switch-default3" disabled="disabled" />
	<label for="switch-default3"><span class="e-btn-round"></span></label>
</div>
```
##### 1.3、五种样式，分别对应五个class：
e-default、e-primary、e-success、e-info、e-warning、e-danger

##### 1.4、效果
![](http://)

#### 2、e-switch-flat
```
<div class="e-switch-flat e-default">
	<input type="checkbox" id="switch-default" />
	<label for="switch-default">
		<span class="e-btn-flat"></span>
	</label>
</div>
```
##### 2.1、checked
```
<div class="e-switch-flat e-default">
	<input type="checkbox" id="switch-default2" checked="checked" />
	<label for="switch-default2">
		<span class="e-btn-flat"></span>
	</label>
</div>
```
##### 2.2、disabled
```
<div class="e-switch-flat e-default">
	<input type="checkbox" id="switch-default2" disabled="disabled" />
	<label for="switch-default2">
		<span class="e-btn-flat"></span>
	</label>
</div>
```
##### 2.3、添加文字
```
<div class="e-switch-flat e-default">
	<input type="checkbox" id="switch-default" />
	<label for="switch-default">
		<span class="e-on">On</span>
		<span class="e-btn-flat"></span>
		<span class="e-off">Off</span>
	</label>
</div>
```
##### 2.4、效果
![](http://)