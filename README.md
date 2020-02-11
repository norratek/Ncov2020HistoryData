# Ncov2020HistoryData
大家使用example.csv作为模板上传数据<br>

通过后台的批处理软件，将文件的中的各省市数据导入到数据库，数据接口对所有人开放<br>
三个接口例子：<br>
获取所有历史数据：
http://ncov.nosensor.com:8080/api/<br>
获取某一天的历史数据：
http://ncov.nosensor.com:8080/api/date=2020-02-09<br>
获取某市的所有历史数据：
http://ncov.nosensor.com:8080/api/city=武汉<br>
获取某省的所有历史数据：
http://ncov.nosensor.com:8080/api/province=湖北<br>
获取全国省市级卫健委的网站链接：
http://ncov.nosensor.com:8080/links<br>
获取某个省、市、县、区的地址定位信息：
http://ncov.nosensor.com:8080/loc=杭州

目前做了一个简单的应用：<br>
http://ncov.nosensor.com