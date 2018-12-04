# China Regions

中华人民共和国县以上省市地区行政区划数据, 提供 `JSON`, `SQL`, `JS (ES6)`, `CSV` 等数据格式.

本数据来自[中华人民共和国民政部][1], 爬虫自动监测数据更新并生成新的数据文件.

最后更新于 2018-11-22. ([源网页][2])

## Intro

The People's Republic of China regions data, provide `JSON`, `SQL`, `JS (ES6)`, `CSV` data format.

The data that is from [Ministry of Civil Affairs of the People's Republic of China][1], the crawler will monitor the update of data and generate data files automatic.

Latest upated at 2018-11-22. ([Source][2])

## Structure
```bash
data
├── csv
│   ├── cities.csv
│   ├── districts.csv
│   └── provinces.csv
├── js
│   ├── regions.js 		# 省市区全部数据
│   └── regions.object.js 	# 省市区全部数据 (对象)
├── json
│   ├── cities.json
│   ├── cities.object.json
│   ├── districts.json
│   ├── districts.object.json
│   ├── provinces.json
│   ├── provinces.object.json
│   ├── regions.json 			# 省市区全部数据
│   └── regions.object.json 		# 省市区全部数据 (对象)
│   └── regions.object.flat.json 	# 省市区全部数据 (扁平对象)
│   └── regions.object.flat.full.json 	# 省市区全部数据 (扁平对象含父级)
└── sql
    ├── cities.sql
    ├── districts.sql
    ├── provinces.sql
    └── regions.sql 		# 省市区全部数据
```

## References

- [中华人民共和国行政区划代码][1]
- [Administrative divisions of China][3]

[1]: http://www.mca.gov.cn/article/sj/xzqh/2018/
[2]: http://www.mca.gov.cn/article/sj/xzqh/2018/201804-12/20181011221630.html
[3]: https://en.wikipedia.org/wiki/Administrative_divisions_of_China
