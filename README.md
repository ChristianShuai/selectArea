jQuery省市县三级联动插件

使用方法：$("#box").selectArea({
    dataType: "id"
});

domSelect: [],	//DOM节点，input['name']的值

domInit: [],//初始化选择框中的值默认:["请选择省份", "请选择城市", "请选择区县"]

errorElement: ".error-area",//错误提示dom节点,默认“.error-area”

dataType: "name",//input中value值类型，默认:name:中文城市名,id:城市代码
