
# TikTokAPI接口，用户粉丝列表采集

> **针对开放隐私设置，关注/粉丝列表对外可见的用户有效**




**请求API：**
```http
http://主机地址/tk/user/followers?token=xxx&uid=6754915036232582149&cursor=1631063752
```


**请求方式：**
```http
GET
```



**参数：**

| 参数名 | 必选 | 类型 | 说明 |
| --- | --- | --- | --- |
| token | 是 | string | 接口授权码 |
| uid | 是 | int | 用户的user_id，非TK号，[点击查看获取方法](https://www.yuque.com/books/share/d37ad7e7-95b0-4535-ad74-2cb5f639e99f/opsoz9) |
| cursor | 否 | int | 翻页游标，根据结果返回的min_time传入作为下一页翻页参数，初始为0 |

​

**status_code状态码：**

| status_code**状态码** | **说明** |
| --- | --- |
| 2096 | 由于该用户隐私设置，列表不可见 |
| 2065 | 用户不存在 |

​

​

**返回示例**
```json

{
	"code": 200,
	"msg": "成功",
	"data": {
		"max_time": 1631063752,
		"min_time": 1631063752,
		"has_more": true,
		"myself_user_id": "0",
		"offset": 20,
		"extra": {
			"fatal_item_ids": [],
			"logid": "202109080115520102450220261546B838",
			"now": 1631063752000
		},
		"log_pb": {
			"impr_id": "202109080115520102450220261546B838"
		},
		"status_code": 0,
		"rec_has_more": true,
		"total": 8229668,
		"followers": [
			{
				"react_setting": 0,
				"stitch_setting": 0,
				"aweme_count": 0,
				"twitter_id": "",
				"user_canceled": false,
				"ins_id": "",
				"homepage_bottom_toast": null,
				"mutual_relation_avatars": null,
				"avatar_thumb": {
					"height": 720,
					"uri": "tiktok-obj\/7005362653325426689",
					"url_list": [
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tiktok-obj\/7005362653325426689.webp?x-expires=1631149200&x-signature=VO80wq2dLYsKLeewVzFsiAU1wMI%3D",
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tiktok-obj\/7005362653325426689.jpeg?x-expires=1631149200&x-signature=2sY5jKPzvlyQrtRBVgGvoiAeezw%3D"
					],
					"width": 720
				},
				"live_verify": 0,
				"enterprise_verify_reason": "",
				"follower_status": 0,
				"comment_setting": 0,
				"custom_verify": "",
				"avatar_medium": {
					"uri": "tiktok-obj\/7005362653325426689",
					"url_list": [
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tiktok-obj\/7005362653325426689.webp?x-expires=1631149200&x-signature=ql2w6NkfY3jMIvWIHhQY5T5VFEY%3D",
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tiktok-obj\/7005362653325426689.jpeg?x-expires=1631149200&x-signature=Qn18EA1MOLpPJM7YJM008XVGRRs%3D"
					],
					"width": 720,
					"height": 720
				},
				"bold_fields": null,
				"is_ad_fake": false,
				"has_email": false,
				"create_time": 0,
				"user_period": 0,
				"avatar_larger": {
					"uri": "tiktok-obj\/7005362653325426689",
					"url_list": [
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tiktok-obj\/7005362653325426689.webp?x-expires=1631149200&x-signature=S2KtrGmhT68Tc88cKo0TKmrQEKM%3D",
						"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tiktok-obj\/7005362653325426689.jpeg?x-expires=1631149200&x-signature=E8o3Ip3o1G9rsA8V53iRxBaQxfI%3D"
					],
					"width": 720,
					"height": 720
				},
				"has_facebook_token": false,
				"share_info": {
					"share_weibo_desc": "",
					"share_desc": "",
					"share_title": "",
					"share_qrcode_url": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"share_title_myself": "",
					"share_title_other": "",
					"share_desc_info": "",
					"share_url": ""
				},
				"video_icon": {
					"url_list": [],
					"width": 720,
					"height": 720,
					"uri": ""
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
				"follow_status": 0,
				"room_id": 0,
				"total_favorited": 0,
				"with_fusion_shop_entry": false,
				"qa_status": 0,
				"youtube_channel_id": "",
				"live_agreement_time": 0,
				"avatar_uri": "tiktok-obj\/7005362653325426689",
				"short_id": "0",
				"user_rate": 1,
				"download_prompt_ts": 0,
				"language": "",
				"live_agreement": 0,
				"is_phone_binded": false,
				"reflow_page_uid": 0,
				"verify_info": "",
				"ad_cover_url": null,
				"tw_expire_time": 0,
				"shield_follow_notice": 0,
				"followers_detail": null,
				"gender": 0,
				"verification_type": 1,
				"events": null,
				"has_insights": false,
				"item_list": null,
				"youtube_channel_title": "",
				"status": 1,
				"live_commerce": false,
				"shield_digg_notice": 0,
				"platform_sync_info": null,
				"google_account": "",
				"reflow_page_gid": 0,
				"sec_uid": "MS4wLjABAAAAhjvKRC2R-0dLFbp-ycs9Pkr_ICiXbUVf2qTWQ9Qi4UsD-mJZl1Z1rWohOylie18T",
				"white_cover_url": null,
				"special_lock": 1,
				"commerce_user_level": 0,
				"prevent_download": false,
				"type_label": null,
				"search_highlight": null,
				"nickname": "mqyeq",
				"follower_count": 0,
				"bind_phone": "",
				"secret": 0,
				"user_tags": null,
				"with_commerce_entry": false,
				"with_shop_entry": false,
				"uid": "7005153156116071425",
				"show_image_bubble": false,
				"is_star": false,
				"avatar_300x300": {
					"height": 720,
					"uri": "tiktok-obj\/7005362653325426689",
					"url_list": [
						"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/7005362653325426689~c5_300x300.webp?x-expires=1631149200&x-signature=KyRJqgqHimaqQ7Db0i2ZqO7sv3U%3D",
						"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/7005362653325426689~c5_300x300.jpeg?x-expires=1631149200&x-signature=l9Ng%2BPpVJ5ap6Tv2mvYsCQ0m0n8%3D"
					],
					"width": 720
				},
				"favoriting_count": 0,
				"can_set_geofencing": null,
				"following_count": 3,
				"authority_status": 0,
				"twitter_name": "",
				"need_recommend": 0,
				"duet_setting": 0,
				"is_block": false,
				"hide_search": false,
				"comment_filter_status": 0,
				"original_musician": {
					"music_count": 0,
					"music_used_count": 0,
					"digg_count": 0
				},
				"accept_private_policy": false,
				"birthday": "1900-01-01",
				"has_twitter_token": false,
				"account_region": "",
				"download_setting": 0,
				"cha_list": null,
				"region": "CN",
				"user_mode": 1,
				"cv_level": "",
				"need_points": null,
				"shield_comment_notice": 0,
				"is_discipline_member": false,
				"unique_id_modify_time": 1631063752,
				"share_qrcode_uri": "",
				"signature": "",
				"unique_id": "mqyeq",
				"has_orders": false,
				"has_youtube_token": false,
				"youtube_expire_time": 0,
				"avatar_168x168": {
					"uri": "tiktok-obj\/7005362653325426689",
					"url_list": [
						"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/7005362653325426689~c5_168x168.webp?x-expires=1631149200&x-signature=%2F4HhcPj1fwn%2FkFEOEWaKz%2F8p8HQ%3D",
						"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/7005362653325426689~c5_168x168.jpeg?x-expires=1631149200&x-signature=NP8Dq4HhkhSpWwrqG2A7oMc2YNE%3D"
					],
					"width": 720,
					"height": 720
				},
				"apple_account": 0,
				"relative_users": null,
				"fb_expire_time": 0,
				"geofencing": []
			},
			{
				"avatar_medium": {
					"uri": "musically-maliva-obj\/6977509749222801414",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_720x720.webp?x-expires=1631149200&x-signature=ofVBSXfRNGAe71s0vIs5oIhH%2BYs%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_720x720.jpeg?x-expires=1631149200&x-signature=WM5SwcfmsDDXZc4G4BLxkXE7Mxs%3D"
					],
					"width": 720,
					"height": 720
				},
				"live_commerce": false,
				"share_qrcode_uri": "",
				"relative_users": null,
				"youtube_channel_id": "",
				"youtube_channel_title": "",
				"favoriting_count": 4639,
				"has_youtube_token": false,
				"share_info": {
					"share_desc": "",
					"share_title": "",
					"share_qrcode_url": {
						"url_list": [],
						"width": 720,
						"height": 720,
						"uri": ""
					},
					"share_title_myself": "",
					"share_title_other": "",
					"share_desc_info": "",
					"share_url": "",
					"share_weibo_desc": ""
				},
				"video_icon": {
					"uri": "",
					"url_list": [],
					"width": 720,
					"height": 720
				},
				"room_id": 0,
				"comment_setting": 0,
				"hide_search": false,
				"has_facebook_token": false,
				"tw_expire_time": 0,
				"user_mode": 1,
				"with_shop_entry": false,
				"white_cover_url": null,
				"nickname": "liajoseph5",
				"signature": "",
				"custom_verify": "",
				"commerce_user_level": 0,
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
				"type_label": null,
				"uid": "6977504145574577157",
				"gender": 0,
				"avatar_uri": "musically-maliva-obj\/6977509749222801414",
				"cv_level": "",
				"download_setting": 0,
				"download_prompt_ts": 0,
				"has_insights": false,
				"aweme_count": 0,
				"unique_id": "liajoseph5",
				"has_email": false,
				"create_time": 0,
				"shield_digg_notice": 0,
				"has_twitter_token": false,
				"accept_private_policy": false,
				"status": 1,
				"show_image_bubble": false,
				"follower_status": 0,
				"sec_uid": "MS4wLjABAAAAkZDGdPES3JzrODS204l5uiMKxch6KsoigWIOPjSPj01sZRXts4mejbwK3d-MS9mg",
				"following_count": 255,
				"live_verify": 0,
				"verification_type": 1,
				"is_ad_fake": false,
				"followers_detail": null,
				"bind_phone": "",
				"shield_comment_notice": 0,
				"twitter_id": "",
				"need_recommend": 0,
				"youtube_expire_time": 0,
				"unique_id_modify_time": 1631063752,
				"google_account": "",
				"authority_status": 0,
				"ins_id": "",
				"avatar_300x300": {
					"uri": "musically-maliva-obj\/6977509749222801414",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_300x300.webp?x-expires=1631149200&x-signature=8F2d7%2FndzKk5Q1e%2FhpnuWYw3iIQ%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_300x300.jpeg?x-expires=1631149200&x-signature=xjhIp7WCmVZ4zTNABCQsjV9RopU%3D"
					],
					"width": 720,
					"height": 720
				},
				"qa_status": 0,
				"can_set_geofencing": null,
				"bold_fields": null,
				"prevent_download": false,
				"user_canceled": false,
				"duet_setting": 0,
				"avatar_168x168": {
					"uri": "musically-maliva-obj\/6977509749222801414",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_168x168.webp?x-expires=1631149200&x-signature=e1e12RHGEKKn3ZaT%2FzKyoIOzjYo%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_168x168.jpeg?x-expires=1631149200&x-signature=K0Y7aNjrQh6TOkpWD9SX3GUbw4w%3D"
					],
					"width": 720,
					"height": 720
				},
				"original_musician": {
					"music_count": 0,
					"music_used_count": 0,
					"digg_count": 0
				},
				"enterprise_verify_reason": "",
				"is_discipline_member": false,
				"fb_expire_time": 0,
				"apple_account": 0,
				"comment_filter_status": 0,
				"reflow_page_gid": 0,
				"ad_cover_url": null,
				"region": "CN",
				"geofencing": [],
				"is_block": false,
				"user_rate": 1,
				"need_points": null,
				"is_star": false,
				"homepage_bottom_toast": null,
				"live_agreement": 0,
				"user_period": 0,
				"reflow_page_uid": 0,
				"react_setting": 0,
				"stitch_setting": 0,
				"item_list": null,
				"live_agreement_time": 0,
				"follower_count": 21,
				"special_lock": 1,
				"account_region": "",
				"avatar_larger": {
					"uri": "musically-maliva-obj\/6977509749222801414",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_1080x1080.webp?x-expires=1631149200&x-signature=ule8usJZuoWG45kf2SO9NUYG3Ds%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_1080x1080.jpeg?x-expires=1631149200&x-signature=GJHMzp7XOFJa5axyJza2aXr2u5g%3D"
					],
					"width": 720,
					"height": 720
				},
				"avatar_thumb": {
					"uri": "musically-maliva-obj\/6977509749222801414",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_100x100.webp?x-expires=1631149200&x-signature=C%2BahaKoeqRXfWGZq49E9r%2FLUmXc%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/6977509749222801414~c5_100x100.jpeg?x-expires=1631149200&x-signature=xiL3sxAbffZadHzzJdvkZPYI4HE%3D"
					],
					"width": 720,
					"height": 720
				},
				"shield_follow_notice": 0,
				"events": null,
				"cha_list": null,
				"birthday": "1900-01-01",
				"verify_info": "",
				"with_commerce_entry": false,
				"short_id": "0",
				"with_fusion_shop_entry": false,
				"twitter_name": "",
				"user_tags": null,
				"platform_sync_info": null,
				"has_orders": false,
				"is_phone_binded": false,
				"language": "",
				"secret": 0,
				"search_highlight": null,
				"follow_status": 0,
				"total_favorited": 0,
				"mutual_relation_avatars": null
			}
		]
	}
}

```
