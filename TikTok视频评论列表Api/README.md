#  TikTok视频评论列表Api


#  请求Api：
```java
http://主机地址/tk/video/comments?token=xxx&aweme_id=6993829555089706245&cursor=20
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| aweme_id     | string     | 视频id     | 
| cursor     | int     | 翻页游标     | 


#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"status_code": 0,
		"comments": [
			{
				"cid": "6996843253702542081",
				"text": "What👁👄👁",
				"aweme_id": "6993829555089706245",
				"create_time": 1629079535,
				"digg_count": 0,
				"status": 1,
				"user": {
					"uid": "6934915800185177094",
					"short_id": "0",
					"nickname": "Love you guys",
					"gender": 0,
					"signature": "Join the cult NOW else you will have diabetes",
					"avatar_larger": {
						"uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.webp?x-expires=1629180000&x-signature=Z8uS5H%2BTtnsIgNHC6wyi13vljTw%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.jpeg?x-expires=1629180000&x-signature=Ju20PnHKHVaLp4o5nWk%2BUcWbEAg%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.webp?x-expires=1629180000&x-signature=21QlvW8Mq6jxp8J%2Fp%2BNyoxKEiGE%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.jpeg?x-expires=1629180000&x-signature=910eOWE1GAPfZ6dJB%2Fwz%2BhMgExE%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.webp?x-expires=1629180000&x-signature=YaZbg1jPPCcCR0%2BKsWnFAN0dYOs%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e.jpeg?x-expires=1629180000&x-signature=wu3%2Fu%2BmDuNc9CPcx%2B74dEHT8VH4%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 0,
					"following_count": 0,
					"follower_count": 0,
					"favoriting_count": 0,
					"total_favorited": 0,
					"is_block": false,
					"hide_search": false,
					"custom_verify": "",
					"unique_id": "the.king.of.drip",
					"bind_phone": "",
					"special_lock": 1,
					"need_recommend": 0,
					"has_facebook_token": false,
					"has_twitter_token": false,
					"fb_expire_time": 0,
					"tw_expire_time": 0,
					"has_youtube_token": false,
					"youtube_expire_time": 0,
					"room_id": 0,
					"live_verify": 0,
					"authority_status": 0,
					"verify_info": "",
					"shield_follow_notice": 0,
					"shield_digg_notice": 0,
					"shield_comment_notice": 0,
					"with_commerce_entry": false,
					"verification_type": 1,
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "AU",
					"account_region": "",
					"commerce_user_level": 0,
					"live_agreement": 0,
					"platform_sync_info": null,
					"with_shop_entry": false,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1629095840,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"ins_id": "",
					"google_account": "",
					"youtube_channel_id": "",
					"youtube_channel_title": "",
					"apple_account": 0,
					"with_fusion_shop_entry": false,
					"is_phone_binded": false,
					"accept_private_policy": false,
					"twitter_id": "",
					"twitter_name": "",
					"user_canceled": false,
					"has_email": false,
					"live_agreement_time": 0,
					"status": 1,
					"create_time": 0,
					"avatar_uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 0,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 1,
					"download_setting": 0,
					"download_prompt_ts": 1626420179,
					"react_setting": 0,
					"live_commerce": false,
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
					"language": "en",
					"has_insights": false,
					"item_list": null,
					"user_mode": 1,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e~c5_168x168.webp?x-expires=1629180000&x-signature=B91%2FgQ6pWEkFsZa%2Bj3lpUa43BaA%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e~c5_168x168.jpeg?x-expires=1629180000&x-signature=DVXxqGYwYjwMOJVraY2Hc6n5XWs%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e~c5_300x300.webp?x-expires=1629180000&x-signature=kb24F18c20bQW1QtlXHUHCpSyrg%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tos-alisg-avt-0068\/456fc97e0268cbb0eac63bd27ddc641e~c5_300x300.jpeg?x-expires=1629180000&x-signature=mubBJjECrWpgy7mOe645dZJxgNE%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAALfzNUTkB7DDrNAH23btGJVlUkHEh1lKziZOvgf77LMsmdSd31WQQhq5k98n7o_ua",
					"need_points": null,
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 0,
					"bold_fields": null,
					"qa_status": 0,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"reply_id": "0",
				"user_digged": 0,
				"reply_comment": null,
				"text_extra": [],
				"reply_comment_total": 0,
				"reply_to_reply_id": "0",
				"is_author_digged": false,
				"stick_position": 0,
				"user_buried": false,
				"label_list": null,
				"author_pin": false,
				"no_show": false,
				"collect_stat": 0
			},
			{
				"cid": "6996897023341953798",
				"text": "And it’s only 50 thousand calories",
				"aweme_id": "6993829555089706245",
				"create_time": 1629092045,
				"digg_count": 0,
				"status": 1,
				"user": {
					"uid": "6913379353075254278",
					"short_id": "0",
					"nickname": "Xeon ccl",
					"gender": 0,
					"signature": "Nah bro u really thought Ezra was better than grant are you stupid?",
					"avatar_larger": {
						"uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_1080x1080.webp?x-expires=1629180000&x-signature=hSrtGlzM7Lnfj37klb2lD%2BscVhM%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=gHowuLg9WSxhmqc%2BB7B33aK0EpA%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_100x100.webp?x-expires=1629180000&x-signature=GWX7MfiPA6elyLa4cLbt4B2aCK4%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_100x100.jpeg?x-expires=1629180000&x-signature=081dCsrEGKiXO%2BynNxGyHOeRtYg%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_720x720.webp?x-expires=1629180000&x-signature=nqKpA8dT5kOVD8x3UozdhtXQKes%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_720x720.jpeg?x-expires=1629180000&x-signature=iClbCHb6tp%2FAImcK%2FCx6BxRMHrY%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 0,
					"following_count": 0,
					"follower_count": 0,
					"favoriting_count": 0,
					"total_favorited": 0,
					"is_block": false,
					"hide_search": true,
					"custom_verify": "",
					"unique_id": "xeon_ccl",
					"bind_phone": "",
					"special_lock": 1,
					"need_recommend": 0,
					"has_facebook_token": false,
					"has_twitter_token": false,
					"fb_expire_time": 0,
					"tw_expire_time": 0,
					"has_youtube_token": false,
					"youtube_expire_time": 0,
					"room_id": 0,
					"live_verify": 0,
					"authority_status": 0,
					"verify_info": "",
					"shield_follow_notice": 0,
					"shield_digg_notice": 0,
					"shield_comment_notice": 0,
					"with_commerce_entry": false,
					"verification_type": 1,
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "US",
					"account_region": "",
					"commerce_user_level": 0,
					"live_agreement": 0,
					"platform_sync_info": null,
					"with_shop_entry": false,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1629095840,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"ins_id": "",
					"google_account": "",
					"youtube_channel_id": "UCkxnvGapYABCm5g2OmcYfbQ",
					"youtube_channel_title": "xeon ccl",
					"apple_account": 0,
					"with_fusion_shop_entry": false,
					"is_phone_binded": false,
					"accept_private_policy": false,
					"twitter_id": "",
					"twitter_name": "",
					"user_canceled": false,
					"has_email": false,
					"live_agreement_time": 0,
					"status": 1,
					"create_time": 0,
					"avatar_uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 3,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 1,
					"download_setting": 3,
					"download_prompt_ts": 0,
					"react_setting": 3,
					"live_commerce": false,
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
					"language": "en",
					"has_insights": false,
					"item_list": null,
					"user_mode": 1,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_168x168.webp?x-expires=1629180000&x-signature=TkL3O9PZ%2BmjsJ8yhGYTLBzmzDng%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_168x168.jpeg?x-expires=1629180000&x-signature=KowtWURwTNkphQEZ9sXJO3QZin4%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_300x300.webp?x-expires=1629180000&x-signature=yUE6SC96CYDBOM4FC%2B3uq7mnW88%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/418187443f03b796904e0f2da0908156~c5_300x300.jpeg?x-expires=1629180000&x-signature=8Rxj3ZHoT4vfOyH4va%2By4NmcxV0%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAbywzZwK_9j-c4KdU3ZROXiLCiEv5EsXNHiQtClgwHQAgXdIkIIH6CTnk7RTyWLNn",
					"need_points": null,
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 3,
					"bold_fields": null,
					"qa_status": 0,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"reply_id": "0",
				"user_digged": 0,
				"reply_comment": null,
				"text_extra": [],
				"reply_comment_total": 0,
				"reply_to_reply_id": "0",
				"is_author_digged": false,
				"stick_position": 0,
				"user_buried": false,
				"label_list": null,
				"author_pin": false,
				"no_show": false,
				"collect_stat": 0
			}
		],
		"cursor": 40,
		"has_more": 1,
		"reply_style": 2,
		"total": 98124,
		"extra": {
			"now": 1629095840000,
			"fatal_item_ids": null
		},
		"log_pb": {
			"impr_id": "2021081606372001024516412901004215"
		},
		"top_gifts": null,
		"alias_comment_deleted": false
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
