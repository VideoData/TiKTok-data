# TikTokAPI接口，用户橱窗商品列表


### 请求Api


```http
http://主机地址/tk/user/videos2?/tk/user/products?token=xxx&sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1
```



### 请求方式


```http
GET
```



### 参数
**​**


| 参数名 | 必选 | 类型 | 说明 |
| --- | --- | --- | --- |
| token | 是 | string | 接口授权码 |
| sec_uid | 是 | int | 用户的sec_uid，非抖音号、uid |
| cursor | 否 | int | 翻页游标，根据结果返回的cursor传入作为下一页翻页参数，初始为0 |




### 返回示例


```json
{
	"code": 200,
	"msg": "成功",
	"data": {
		"status_code": 0,
		"status_msg": "",
		"products": [
			{
				"product_id": "1729382817718699099",
				"title": "You Are The Sun High Gloss",
				"currency_unit": "USD",
				"price": 1600,
				"market_price": 16000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc317?sub_id=TTEC&utm_source=TTEC&variant=40937243902156",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png",
					"url_list": [
						"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhN6gdcYJ12fz6-nurcNCtif3yaq412f24cf72153294ca412bbe23078a9f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FksRotPHVBuBeAA10E_PzHh-yfj39606d35ebf2d29dd307cc172b9486630.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FksRotPHVBuBeAA10E_PzHh-yfj39606d35ebf2d29dd307cc172b9486630.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FksRotPHVBuBeAA10E_PzHh-yfj39606d35ebf2d29dd307cc172b9486630.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FovhW9jWpjSBc1VRSvAhpY6UUJa7ddc942f604cfaf3579aaa6584af1e515.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FovhW9jWpjSBc1VRSvAhpY6UUJa7ddc942f604cfaf3579aaa6584af1e515.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FovhW9jWpjSBc1VRSvAhpY6UUJa7ddc942f604cfaf3579aaa6584af1e515.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$16.00",
				"format_market_price": "$16.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc317?sub_id=TTEC&utm_source=TTEC&variant=40937243902156",
				"string_price": "16",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998171717873174273&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998171717873174273%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "16",
				"floor_price": "16",
				"source_from": 1,
				"is_hide": false
			},
			{
				"product_id": "1729382817719354459",
				"title": "I'M The Catch High Gloss",
				"currency_unit": "USD",
				"price": 1600,
				"market_price": 16000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc342?sub_id=TTEC&utm_source=TTEC&variant=40937244262604",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png",
					"url_list": [
						"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fopx6YXAEikRW9lLbR_BFCYqaXl_a31154b4bee1fc5f6e3f35a622b0f9dd.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FtLm-2XQjrO98HKHDACa34s02SLx050b107ffc49a8314ddb05718b2f4050.png",
						"url_list": [
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FtLm-2XQjrO98HKHDACa34s02SLx050b107ffc49a8314ddb05718b2f4050.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FtLm-2XQjrO98HKHDACa34s02SLx050b107ffc49a8314ddb05718b2f4050.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FizGwMjOP-zCnPR1tvbZ0-t8s3VQ1e7fb52af57c350bc7f6de646be42426.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FizGwMjOP-zCnPR1tvbZ0-t8s3VQ1e7fb52af57c350bc7f6de646be42426.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FizGwMjOP-zCnPR1tvbZ0-t8s3VQ1e7fb52af57c350bc7f6de646be42426.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$16.00",
				"format_market_price": "$16.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc342?sub_id=TTEC&utm_source=TTEC&variant=40937244262604",
				"string_price": "16",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998213213867312897&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998213213867312897%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "16",
				"floor_price": "16",
				"source_from": 1,
				"is_hide": false
			},
			{
				"product_id": "1729382817731413083",
				"title": "Slept On High Gloss",
				"currency_unit": "USD",
				"price": 1600,
				"market_price": 16000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc335?sub_id=TTEC&utm_source=TTEC&variant=40937243836620",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png",
					"url_list": [
						"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FoOmlKIUi6CBhHbANOoHCE__WHcYd4a9d07c3eba47beac9cce76f240f85f.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FvglODvyHOUYYmbXg9uOvKTATTLwc330a14a82c580f49257919ab845c634.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FvglODvyHOUYYmbXg9uOvKTATTLwc330a14a82c580f49257919ab845c634.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FvglODvyHOUYYmbXg9uOvKTATTLwc330a14a82c580f49257919ab845c634.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fh337OcLr9oLYFlCKxBjKqQw0cLD19d779a53f64e2548c7f62acf3503fb1.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fh337OcLr9oLYFlCKxBjKqQw0cLD19d779a53f64e2548c7f62acf3503fb1.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fh337OcLr9oLYFlCKxBjKqQw0cLD19d779a53f64e2548c7f62acf3503fb1.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$16.00",
				"format_market_price": "$16.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc335?sub_id=TTEC&utm_source=TTEC&variant=40937243836620",
				"string_price": "16",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998213229126272770&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998213229126272770%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "16",
				"floor_price": "16",
				"source_from": 1,
				"is_hide": false
			},
			{
				"product_id": "1729382818459714651",
				"title": "Koko K High Gloss",
				"currency_unit": "USD",
				"price": 1600,
				"market_price": 16000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc326?sub_id=TTEC&utm_source=TTEC&variant=40937244328140",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png",
					"url_list": [
						"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fs9OENKMu8m3eXewTJBaJmMqgQD_60c29f08086eaf7b822d2f63506253c3.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fnrnr8gExBM38AHbibUqncL1Lf088f0cf152ebd1e8f17dcd6381fe492a3b.png",
						"url_list": [
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fnrnr8gExBM38AHbibUqncL1Lf088f0cf152ebd1e8f17dcd6381fe492a3b.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fnrnr8gExBM38AHbibUqncL1Lf088f0cf152ebd1e8f17dcd6381fe492a3b.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fj7e5-oKkh-NRc80JUFJCh6GPMAm3ade3d4650d286ff46a683240e7dd454.png",
						"url_list": [
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fj7e5-oKkh-NRc80JUFJCh6GPMAm3ade3d4650d286ff46a683240e7dd454.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fj7e5-oKkh-NRc80JUFJCh6GPMAm3ade3d4650d286ff46a683240e7dd454.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$16.00",
				"format_market_price": "$16.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc326?sub_id=TTEC&utm_source=TTEC&variant=40937244328140",
				"string_price": "16",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998211519041521410&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998211519041521410%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "16",
				"floor_price": "16",
				"source_from": 1,
				"is_hide": false
			},
			{
				"product_id": "1729382818511881307",
				"title": "Posie K Matte Liquid Lipstick",
				"currency_unit": "USD",
				"price": 1700,
				"market_price": 17000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/matte-liquid-lipstick-kc188?sub_id=TTEC&utm_source=TTEC&variant=40937246621900",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png",
					"url_list": [
						"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FrRUFJcoP4OrakVUwqU7HWP7BHYr4c84286089f569923165a684081886bf.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fro_8G3Hkxgt4QGHFTeUkoxcqA2dc228dfa68ab82a43c160a6797ef27b4c.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fro_8G3Hkxgt4QGHFTeUkoxcqA2dc228dfa68ab82a43c160a6797ef27b4c.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fro_8G3Hkxgt4QGHFTeUkoxcqA2dc228dfa68ab82a43c160a6797ef27b4c.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Frxul8oFdxFMY6PaYdWnU2YREB_000f84ab7ce015f5e6288f8633f04cecc.png",
						"url_list": [
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Frxul8oFdxFMY6PaYdWnU2YREB_000f84ab7ce015f5e6288f8633f04cecc.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Frxul8oFdxFMY6PaYdWnU2YREB_000f84ab7ce015f5e6288f8633f04cecc.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/FgFq9huMSzEM6_bTto4nvGYVIVBP6f6fd55ef0b98666fd0e7419aca49781.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FgFq9huMSzEM6_bTto4nvGYVIVBP6f6fd55ef0b98666fd0e7419aca49781.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FgFq9huMSzEM6_bTto4nvGYVIVBP6f6fd55ef0b98666fd0e7419aca49781.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$17.00",
				"format_market_price": "$17.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/matte-liquid-lipstick-kc188?sub_id=TTEC&utm_source=TTEC&variant=40937246621900",
				"string_price": "17",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998213229126190850&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998213229126190850%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "17",
				"floor_price": "17",
				"source_from": 1,
				"is_hide": false
			},
			{
				"product_id": "1729382818619556955",
				"title": "Posie K High Gloss",
				"currency_unit": "USD",
				"price": 1600,
				"market_price": 16000000,
				"detail_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc336?sub_id=TTEC&utm_source=TTEC&variant=40937243705548",
				"source": "Shopify",
				"cover": {
					"uri": "cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png",
					"url_list": [
						"https:\/\/p21-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
						"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
					]
				},
				"images": [
					{
						"uri": "cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png",
						"url_list": [
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/FhebxIKDPKLB4pnIA4XhlkmBrInWb28f60e2bd298e8fb0a09177b153d267.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fmu1dTNs2g7ekfPk6Jl0tS2inETIeaf9d0d70460bcf1468d901355508d02.png",
						"url_list": [
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fmu1dTNs2g7ekfPk6Jl0tS2inETIeaf9d0d70460bcf1468d901355508d02.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fmu1dTNs2g7ekfPk6Jl0tS2inETIeaf9d0d70460bcf1468d901355508d02.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					},
					{
						"uri": "cmp-ecom-global-sg\/Fq2R0fiXYr0R2FDASsGWDWl39s1P5b015029ed4ee2a31e8cf9cad04b9bea.png",
						"url_list": [
							"https:\/\/p16-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fq2R0fiXYr0R2FDASsGWDWl39s1P5b015029ed4ee2a31e8cf9cad04b9bea.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?",
							"https:\/\/p19-oec-va.ibyteimg.com\/cmp-ecom-global-sg\/Fq2R0fiXYr0R2FDASsGWDWl39s1P5b015029ed4ee2a31e8cf9cad04b9bea.png~tplv-o3syd03w52-resize-jpeg:800:800.jpeg?"
						]
					}
				],
				"elastic_title": "",
				"status": 1,
				"in_shop": true,
				"addition_id": "0",
				"format_price": "$16.00",
				"format_market_price": "$16.00",
				"currency_format": {
					"currency_symbol": "$",
					"decimal_place": 2,
					"decimal_symbol": ".",
					"separator": ",",
					"separator_index": [
						3,
						6,
						9,
						12,
						15,
						18
					]
				},
				"platform": 100,
				"origin_url": "https:\/\/kylieskin-com.myshopify.com\/products\/high-gloss-kc336?sub_id=TTEC&utm_source=TTEC&variant=40937243705548",
				"string_price": "16",
				"schema": "aweme:\/\/lynxview?channel=ads_landing_page_pdp&bundle=page%2Ftemplate.js&hide_nav_bar=1&product_id=6998213229126174466&catalog_id=6953508370812913410&source_page=ShowWindow&seller_sec_uid=MS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1&first_source_page=ShowWindow&scene=OrganicPdp&fallback_url=http%3A%2F%2Fsg.immers.page%2Finstant_page%2Fpage%2F6950840888801100033%3Fhide_nav_bar%3D1%26should_full_screen%3D1%26hide_source%3D1%26product_id%3D6998213229126174466%26catalog_id%3D6953508370812913410%26source_page%3DShowWindow%26seller_sec_uid%3DMS4wLjABAAAADpTDmwZgzzqZ8TXJe7qKKZ1Pb4cdIL8pFhihtax7uTZ5u5FEsogBkRIYgBEQ3jG1%26first_source_page%3DShowWindow%26scene%3DOrganicPdp",
				"celling_price": "16",
				"floor_price": "16",
				"source_from": 1,
				"is_hide": false
			}
		],
		"has_more": true,
		"total": 47,
		"cursor": 20,
		"sub_tab": 0,
		"live_ids": null,
		"kol_status": 1,
		"entrance_name": "TikTok Shop",
		"entrance": 2,
		"priority_region": "US",
		"log_pb": {
			"impr_id": "202109080817010101890741604290E498"
		},
		"protocol_popups_content": {
			"show_popups": false,
			"protocol_content": ""
		},
		"no_product_status": 1,
		"get_started_schema": "aweme:\/\/ec\/dj\/creator_center"
	}
}
```
