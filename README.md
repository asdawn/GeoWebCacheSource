# GeoWebCacheSource
用于将GeoWebCache切片单独在ol3上加载。
##调用示例
var road= new ol.layer.Tile({
                visible:true,
                source: new GeoWebCacheSource({
					tileRoot:'cite_road',
					format:'png',
					srid:'epsg:900913'
				})
            })
            
tileRoot:离线图片的根目录地址
format:切片格式
srid:切片坐标系，只支持4326和900913/3857/102100
在线体验地址:http://freegis.github.io/examples/GeoWebCacheLayer/Map.html
