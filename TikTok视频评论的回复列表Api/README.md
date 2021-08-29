#  TikTok视频评论的回复列表Api

# 联系方式：[点击主页查看](https://github.com/VideoData) 

#  请求Api：
```java
http://主机地址/video/comment_reply?token=xxx&aweme_id=6993829555089706245&cursor=0&cid=6993850213266637574
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| aweme_id     | int     | 视频id     | 
| cid     | int     | 评论id     | 
| cursor     | int     | 翻页游标     | 


#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"has_more": 1,
		"total": 22,
		"extra": {
			"now": 1629096138000,
			"fatal_item_ids": [],
			"logid": "202108160642180102450651922200B460"
		},
		"log_pb": {
			"impr_id": "202108160642180102450651922200B460"
		},
		"status_code": 0,
		"comments": [
			{
				"reply_id": "6993850213266637574",
				"reply_comment": null,
				"user_buried": false,
				"user": {
					"fb_expire_time": 0,
					"geofencing": [],
					"stitch_setting": 0,
					"follow_status": 0,
					"live_agreement": 0,
					"google_account": "",
					"with_fusion_shop_entry": false,
					"ad_cover_url": null,
					"avatar_168x168": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_168x168.webp?x-expires=1629180000&x-signature=A6U%2FiN%2FU6Anj7%2By1ejSoW0aEqNs%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_168x168.jpeg?x-expires=1629180000&x-signature=7U2ujR8xuxjINuxQDUgzBJ0LUBE%3D"
						]
					},
					"user_tags": null,
					"has_twitter_token": false,
					"authority_status": 0,
					"platform_sync_info": null,
					"user_period": 0,
					"search_highlight": null,
					"download_prompt_ts": 0,
					"live_commerce": false,
					"avatar_300x300": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_300x300.webp?x-expires=1629180000&x-signature=ZnWgJ8JA%2B6rUAzw0tWWCq%2BVMEa0%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_300x300.jpeg?x-expires=1629180000&x-signature=dqEwXsWWw2M2ittecsp8kpZN2qg%3D"
						]
					},
					"relative_users": null,
					"cha_list": null,
					"has_facebook_token": false,
					"enterprise_verify_reason": "",
					"status": 1,
					"favoriting_count": 0,
					"follower_status": 0,
					"special_lock": 1,
					"verification_type": 1,
					"secret": 0,
					"shield_follow_notice": 0,
					"followers_detail": null,
					"user_canceled": false,
					"create_time": 0,
					"avatar_larger": {
						"uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_1080x1080.webp?x-expires=1629180000&x-signature=JIgr%2FhYj3XsvG8miwUIP1qfRcMI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=R8wTHuRbHbqp3l8dqrngPuq3h%2B0%3D"
						],
						"width": 720,
						"height": 720
					},
					"custom_verify": "",
					"live_verify": 0,
					"mutual_relation_avatars": null,
					"twitter_id": "",
					"avatar_medium": {
						"height": 720,
						"uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_720x720.webp?x-expires=1629180000&x-signature=o2F%2F4Kt8IowRgzzxEEsbwFkRduU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_720x720.jpeg?x-expires=1629180000&x-signature=kIAsSmxK36N7g%2FfpoxZbb8f96zc%3D"
						],
						"width": 720
					},
					"is_block": false,
					"aweme_count": 0,
					"has_youtube_token": false,
					"youtube_channel_title": "",
					"need_points": null,
					"bold_fields": null,
					"total_favorited": 0,
					"hide_search": false,
					"bind_phone": "",
					"account_region": "",
					"is_discipline_member": false,
					"short_id": "0",
					"avatar_thumb": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_100x100.webp?x-expires=1629180000&x-signature=nBhtjBVwt2csUP8Y1HXuwWiZRf8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0~c5_100x100.jpeg?x-expires=1629180000&x-signature=i3jA7i9dnrwltYUJX2%2FAKc9JeXg%3D"
						]
					},
					"youtube_channel_id": "",
					"uid": "6789547695084569606",
					"youtube_expire_time": 0,
					"user_rate": 1,
					"white_cover_url": null,
					"item_list": null,
					"has_orders": false,
					"duet_setting": 0,
					"sec_uid": "MS4wLjABAAAAjUqT27ycbfvW3U_m4tqEhnHvdvuxi-fo_MDQ_MFR7LBZx8zovwlHMr9OMXBCKr7h",
					"avatar_uri": "tos-maliva-avt-0068\/c415b829da38a10d986a8f5553f944a0",
					"download_setting": 0,
					"type_label": null,
					"apple_account": 0,
					"show_image_bubble": false,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"language": "en",
					"region": "US",
					"commerce_user_level": 0,
					"shield_digg_notice": 0,
					"prevent_download": false,
					"is_star": false,
					"with_commerce_entry": false,
					"has_insights": false,
					"live_agreement_time": 0,
					"reflow_page_uid": 0,
					"homepage_bottom_toast": null,
					"qa_status": 0,
					"react_setting": 0,
					"comment_filter_status": 0,
					"follower_count": 0,
					"need_recommend": 0,
					"has_email": false,
					"user_mode": 1,
					"can_set_geofencing": null,
					"following_count": 0,
					"unique_id_modify_time": 1629096138,
					"is_phone_binded": false,
					"events": null,
					"gender": 0,
					"twitter_name": "",
					"reflow_page_gid": 0,
					"birthday": "1900-01-01",
					"shield_comment_notice": 0,
					"ins_id": "",
					"is_ad_fake": false,
					"nickname": "Matthew Ramos Vélez 12",
					"verify_info": "",
					"accept_private_policy": false,
					"signature": "gat",
					"unique_id": "matthe22",
					"cv_level": "",
					"tw_expire_time": 0,
					"room_id": 0,
					"with_shop_entry": false,
					"comment_setting": 0,
					"cover_url": [
						{
							"uri": "tiktok-obj\/1613727517271041",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1613727517271041"
							],
							"width": 720,
							"height": 720
						}
					]
				},
				"no_show": false,
				"aweme_id": "6993829555089706245",
				"create_time": 1628382831,
				"digg_count": 1,
				"is_author_digged": false,
				"label_list": null,
				"text": "😃",
				"status": 1,
				"reply_to_reply_id": "0",
				"collect_stat": 0,
				"cid": "6993850988705366790",
				"user_digged": 0,
				"text_extra": []
			},
			{
				"reply_to_reply_id": "0",
				"collect_stat": 0,
				"text": "stfu it looks good and its not like hes gonna eat the whole thing",
				"aweme_id": "6993829555089706245",
				"status": 1,
				"reply_id": "6993850213266637574",
				"create_time": 1628382877,
				"reply_comment": null,
				"user_buried": false,
				"label_list": null,
				"cid": "6993851188534067974",
				"user": {
					"live_verify": 0,
					"shield_follow_notice": 0,
					"has_orders": false,
					"accept_private_policy": false,
					"user_tags": null,
					"birthday": "1900-01-01",
					"shield_digg_notice": 0,
					"is_phone_binded": false,
					"avatar_uri": "musically-maliva-obj\/6975980575211388934",
					"react_setting": 0,
					"has_insights": false,
					"need_recommend": 0,
					"youtube_channel_id": "",
					"user_period": 0,
					"relative_users": null,
					"total_favorited": 0,
					"fb_expire_time": 0,
					"is_ad_fake": false,
					"google_account": "",
					"comment_setting": 0,
					"avatar_larger": {
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/6975980575211388934",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_1080x1080.webp?x-expires=1629180000&x-signature=Vc2LfkH2NJBDfvzoCfmzHQwFSVU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=5AjPzkg%2FPR88%2FPshwyUP0sBFZis%3D"
						]
					},
					"youtube_expire_time": 0,
					"show_image_bubble": false,
					"live_agreement_time": 0,
					"bind_phone": "",
					"language": "en",
					"ad_cover_url": null,
					"mutual_relation_avatars": null,
					"custom_verify": "",
					"enterprise_verify_reason": "",
					"commerce_user_level": 0,
					"reflow_page_gid": 0,
					"follower_count": 0,
					"ins_id": "",
					"verification_type": 1,
					"sec_uid": "MS4wLjABAAAAVuh2lh4itopMZFBvoFSV-slwJF6PFgowMzdK2cf5QpmSKZq5J90oabH-m_7bGzfp",
					"short_id": "0",
					"comment_filter_status": 0,
					"cha_list": null,
					"can_set_geofencing": null,
					"has_twitter_token": false,
					"authority_status": 0,
					"twitter_name": "",
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/6975980575211388934",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_300x300.webp?x-expires=1629180000&x-signature=4WXnylxXfja6p%2Bc7q0DN8OsWpBc%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_300x300.jpeg?x-expires=1629180000&x-signature=5WDVEC7%2ByZBbcpyySbxbgCq6a8U%3D"
						],
						"width": 720,
						"height": 720
					},
					"cover_url": [
						{
							"uri": "tiktok-obj\/1613727517271041",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1613727517271041"
							],
							"width": 720,
							"height": 720
						}
					],
					"homepage_bottom_toast": null,
					"special_lock": 1,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"geofencing": [],
					"with_fusion_shop_entry": false,
					"user_canceled": false,
					"item_list": null,
					"follow_status": 0,
					"is_discipline_member": false,
					"aweme_count": 0,
					"is_block": false,
					"youtube_channel_title": "",
					"following_count": 0,
					"platform_sync_info": null,
					"avatar_168x168": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_168x168.webp?x-expires=1629180000&x-signature=pgYHoEJTj%2Bt0VxzsKGcgc3rowaE%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_168x168.jpeg?x-expires=1629180000&x-signature=AYWoymRJFL5XPn9Har%2BO5vF8%2FjY%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/6975980575211388934"
					},
					"nickname": "esme",
					"prevent_download": false,
					"user_rate": 1,
					"cv_level": "",
					"type_label": null,
					"search_highlight": null,
					"avatar_thumb": {
						"height": 720,
						"uri": "musically-maliva-obj\/6975980575211388934",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_100x100.webp?x-expires=1629180000&x-signature=B7GMJyPgowmVvm7YRePHBag%2BO%2BQ%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_100x100.jpeg?x-expires=1629180000&x-signature=gs%2F7XzOOOItKcZOzyK7jhWjPTq4%3D"
						],
						"width": 720
					},
					"hide_search": false,
					"apple_account": 0,
					"has_email": false,
					"secret": 0,
					"is_star": false,
					"need_points": null,
					"has_youtube_token": false,
					"verify_info": "",
					"create_time": 0,
					"duet_setting": 0,
					"uid": "6975975973633573894",
					"favoriting_count": 0,
					"live_agreement": 0,
					"white_cover_url": null,
					"with_commerce_entry": false,
					"followers_detail": null,
					"region": "US",
					"account_region": "",
					"bold_fields": null,
					"events": null,
					"has_facebook_token": false,
					"twitter_id": "",
					"reflow_page_uid": 0,
					"stitch_setting": 0,
					"with_shop_entry": false,
					"unique_id_modify_time": 1629096138,
					"qa_status": 0,
					"tw_expire_time": 0,
					"live_commerce": false,
					"status": 1,
					"download_setting": 0,
					"user_mode": 1,
					"unique_id": "killvff",
					"follower_status": 0,
					"avatar_medium": {
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/6975980575211388934",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_720x720.webp?x-expires=1629180000&x-signature=7xYGrWh7TVxn4HCV6eeRtz1aBbk%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6975980575211388934~c5_720x720.jpeg?x-expires=1629180000&x-signature=jWa%2Bnk70aSI0hLaooHLddDASWY4%3D"
						]
					},
					"room_id": 0,
					"gender": 0,
					"signature": "",
					"shield_comment_notice": 0,
					"download_prompt_ts": 0
				},
				"is_author_digged": false,
				"no_show": false,
				"digg_count": 3,
				"user_digged": 0,
				"text_extra": []
			}
		],
		"cursor": 20
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
