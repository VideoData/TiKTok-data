#  TikTok话题详情

# 联系方式：[点击主页查看](https://github.com/VideoData) 

#  请求Api：
```java
http://主机地址/tk/challenge/detail?token=xxx&ch_id=2087230 
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| ch_id     | string     | 话题id     | 


#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"ch_info": {
			"sub_type": 0,
			"hashtag_profile": "https:\/\/p16-amd-va.tiktokcdn.com\/obj\/musically-maliva-obj\/b2c66f8cb3c8b8ea1c5849a82965d5dc",
			"banner_list": null,
			"extra_attr": {
				"is_live": false
			},
			"is_challenge": 0,
			"view_count": 345523145,
			"cid": "2087230",
			"schema": "aweme:\/\/aweme\/challenge\/detail?cid=2087230",
			"author": {
				"type_label": null,
				"ad_cover_url": null,
				"homepage_bottom_toast": null,
				"white_cover_url": null,
				"search_highlight": null,
				"platform_sync_info": null,
				"geofencing": null,
				"cover_url": null,
				"can_set_geofencing": null,
				"mutual_relation_avatars": null,
				"followers_detail": null,
				"item_list": null,
				"relative_users": null,
				"user_tags": null,
				"bold_fields": null,
				"cha_list": null,
				"need_points": null,
				"events": null
			},
			"user_count": 9572,
			"connect_music": [],
			"collect_stat": 0,
			"allow_upload_cover": true,
			"is_commerce": false,
			"is_strong_music": false,
			"search_highlight": null,
			"share_info": {
				"share_quote": "",
				"share_weibo_desc": "Check out #olympian on TikTok!",
				"share_desc": "Check out #olympian on TikTok!",
				"share_title": "It is a becoming a big trend on TikTok now! Click here: olympian",
				"bool_persist": 0,
				"share_title_myself": "",
				"share_title_other": "",
				"share_url": "https:\/\/m.tiktok.com\/h5\/share\/tag\/2087230.html?name=olympian&u_code=0&language=en&_d=dk4e43gkjcg74h&share_challenge_id=2087230&source=h5_m",
				"share_signature_url": "",
				"share_signature_desc": "",
				"share_desc_info": "Check out #olympian on TikTok!"
			},
			"type": 2,
			"cha_attrs": null,
			"cha_name": "Olympian",
			"desc": "Whether you're going for gold in Tokyo, or training at home for the future, here's to each and every #Olympian.",
			"is_pgcshow": false,
			"show_items": null
		},
		"status_code": 0,
		"rec_list": null,
		"slide_list": null,
		"dynamic_list": null,
		"extra": {
			"now": 1629096404000,
			"fatal_item_ids": [],
			"logid": "202108160646440102450702051900E764"
		},
		"log_pb": {
			"impr_id": "202108160646440102450702051900E764"
		}
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
