# GeoWebCacheSource
用于将geocache切片单独在ol3上加载。
#调用示例
```
	var road= new ol.layer.Tile({
         visible:true,
         source: new GeoWebCacheSource({
				tileRoot:'cite_road',
				format:'png',
				srid:'epsg:900913'
		})
    })
```
tileRoot：离线瓦片存放根目录
format:切片格式
srid：切片坐标系，支持900913和4326切片方式

在线体验地址:http://freegis.github.io/examples/GeoWebCacheLayer/Map.html
