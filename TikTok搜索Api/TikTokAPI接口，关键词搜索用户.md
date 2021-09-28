

# TikTokAPI接口，关键词搜索用户

### 请求Api
```http
http://主机地址/tiktok/search_for/user?keyword=funny&count=28&token=xxx
```




### 请求方式
```http
GET
```
### 参数
| 字段 | 类型 | 说明 |
| --- | --- | --- |
| token | string | 接口授权码 |
| keyword | string | 搜索关键词 |
| cursor | string | 翻页游标，根据结果返回的cursor传入作为下一页翻页参数，初始为0 |


### 返回示例

```json
{
	"code": 200,
	"msg": "成功",
	"data": {
		"type": 1,
		"user_list": [
			{
				"user_info": {
					"uid": "6613926240453148678",
					"short_id": "0",
					"nickname": "Huda Beauty💄",
					"gender": 0,
					"signature": "Founder of Huda Beauty & Wishful",
					"avatar_larger": {
						"uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_1080x1080.webp?x-expires=1628776800&x-signature=z%2BSWkI4FuYBhLTJA6rE4%2FsM0kjM%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_1080x1080.jpeg?x-expires=1628776800&x-signature=eYEtOtuQtoncsjaqsVJczI9SMo4%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_100x100.webp?x-expires=1628776800&x-signature=ofCmfcibZjsppfCk%2F5FAPpgA3e8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_100x100.jpeg?x-expires=1628776800&x-signature=VIE%2Fb%2BdKgM3ZjxmY6DUY4OOmVJY%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_720x720.webp?x-expires=1628776800&x-signature=KOvohFAbCFwuLyrZQugMhtrUnQM%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_720x720.jpeg?x-expires=1628776800&x-signature=bKKmGMKa6yFA1oSqglzaPbGEdRM%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 324,
					"following_count": 154,
					"follower_count": 5479588,
					"favoriting_count": 10246,
					"total_favorited": 98989516,
					"is_block": false,
					"hide_search": false,
					"custom_verify": "",
					"unique_id": "hudabeauty",
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
					"share_info": {
						"share_url": "",
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
						"share_desc_info": ""
					},
					"with_commerce_entry": false,
					"verification_type": 1,
					"original_musician": {
						"music_count": 0,
						"music_used_count": 0,
						"digg_count": 0
					},
					"enterprise_verify_reason": "verified account",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "US",
					"account_region": "",
					"commerce_user_level": 2,
					"live_agreement": 0,
					"platform_sync_info": null,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1628691262,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"ins_id": "hudabeauty",
					"google_account": "",
					"youtube_channel_id": "UCRSvEADlY-caz3sfDNwvR1A",
					"youtube_channel_title": "Huda Beauty",
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
					"avatar_uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 0,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 17,
					"download_setting": 0,
					"download_prompt_ts": 1583780956,
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
					"share_qrcode_uri": "",
					"item_list": null,
					"user_mode": 1,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_168x168.webp?x-expires=1628776800&x-signature=qD0IhzpiscuufrPyjgdJK7hd40Y%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_168x168.jpeg?x-expires=1628776800&x-signature=rxqLadscgYwCk53M8cWI4USA1NY%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_300x300.webp?x-expires=1628776800&x-signature=wcUKdX29gxeKXzpI2DatbApTDKU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/a9e9abbd9fc8e402b097a527223f630b~c5_300x300.jpeg?x-expires=1628776800&x-signature=P4FtMn6VmQ%2BXK9TXvd%2BsGy3%2ByZM%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAUpRG8iW2MhXVncQ_Q6ZPp95JEbGbb3Ud7t6xeNXYqFXc9VkGLe00zpLrZm4Gt2Kl",
					"need_points": null,
					"name_field": "unique_id",
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 0,
					"bold_fields": null,
					"is_private_account": 0,
					"search_user_name": "hudabeauty",
					"search_user_desc": "Huda Beauty💄",
					"qa_status": 1,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"position": null,
				"uniqid_position": null,
				"effects": null,
				"musics": null,
				"items": null,
				"mix_list": null,
				"challenges": null
			},
			{
				"user_info": {
					"uid": "6558418321485414402",
					"short_id": "0",
					"nickname": "Beauty khan",
					"gender": 0,
					"signature": "team_a1_kolkata\n   Thank you so much guys Mujhe Itna Pyar Dene ke Liye🥰",
					"avatar_larger": {
						"uri": "tiktok-obj\/1663562703760386",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tiktok-obj\/1663562703760386.webp?x-expires=1628776800&x-signature=c%2B0Xe9NLIc%2FZD%2BDhPdKYi8014po%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/1080x1080\/tiktok-obj\/1663562703760386.jpeg?x-expires=1628776800&x-signature=RpbPYJJRqh4eNwIxG8f7YHeRbF0%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "tiktok-obj\/1663562703760386",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tiktok-obj\/1663562703760386.webp?x-expires=1628776800&x-signature=PgI0hpLx%2BUcA6mON8Edu3OQGJ6A%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/100x100\/tiktok-obj\/1663562703760386.jpeg?x-expires=1628776800&x-signature=8WUnuayt1A1agidYC78qTWcVjkg%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "tiktok-obj\/1663562703760386",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tiktok-obj\/1663562703760386.webp?x-expires=1628776800&x-signature=4ndJMLfl0hiKZggLYCRHabxwDQ4%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/aweme\/720x720\/tiktok-obj\/1663562703760386.jpeg?x-expires=1628776800&x-signature=6w2NqC6wVC%2FiIY9J0SK1vHYjmY4%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 2066,
					"following_count": 40,
					"follower_count": 21448741,
					"favoriting_count": 12882,
					"total_favorited": 641591930,
					"is_block": false,
					"hide_search": false,
					"custom_verify": "Popular creator",
					"unique_id": "cutybeautykhan",
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
					"share_info": {
						"share_url": "",
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
						"share_desc_info": ""
					},
					"with_commerce_entry": false,
					"verification_type": 1,
					"original_musician": {
						"music_count": 0,
						"music_used_count": 0,
						"digg_count": 0
					},
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "IN",
					"account_region": "",
					"commerce_user_level": 0,
					"live_agreement": 0,
					"platform_sync_info": null,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1628691262,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"ins_id": "cuty_beauty_khan",
					"google_account": "",
					"youtube_channel_id": "UCKs5_LJdb4SF_G-ohNUD6CQ",
					"youtube_channel_title": "Beauty Khan",
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
					"avatar_uri": "tiktok-obj\/1663562703760386",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 0,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 17,
					"download_setting": 0,
					"download_prompt_ts": 1561751008,
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
					"share_qrcode_uri": "",
					"item_list": null,
					"user_mode": 0,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "tiktok-obj\/1663562703760386",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/1663562703760386~c5_168x168.webp?x-expires=1628776800&x-signature=cz4km0N5Xo%2B7YX2uf81yHJykLQs%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/1663562703760386~c5_168x168.jpeg?x-expires=1628776800&x-signature=vBanSSgLPt%2BakWN7ynFLoYvFYGU%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "tiktok-obj\/1663562703760386",
						"url_list": [
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/1663562703760386~c5_300x300.webp?x-expires=1628776800&x-signature=9UR4TBeCWsCbA1QSouZO7N%2B6WPg%3D",
							"https:\/\/p16-sign-sg.tiktokcdn.com\/tiktok-obj\/1663562703760386~c5_300x300.jpeg?x-expires=1628776800&x-signature=nyqEdDubuCVdbx8WxT%2FfFZtwlBk%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAGJDhiA5KZsKc_v17VMGFG0fJ0GPTtKqyCkcJVy0W_19ROtEs92VaG4j_TZErCeLW",
					"need_points": null,
					"name_field": "unique_id",
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 0,
					"bold_fields": null,
					"is_private_account": 0,
					"search_user_name": "cutybeautykhan",
					"search_user_desc": "Beauty khan",
					"qa_status": 0,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"position": null,
				"uniqid_position": null,
				"effects": null,
				"musics": null,
				"items": null,
				"mix_list": null,
				"challenges": null
			},
			{
				"user_info": {
					"uid": "6815754188875842565",
					"short_id": "0",
					"nickname": "beauty",
					"gender": 0,
					"signature": "The products in my video are in the link below👇👇",
					"avatar_larger": {
						"uri": "musically-maliva-obj\/1666453706193925",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_1080x1080.webp?x-expires=1628776800&x-signature=q0Mpg6fmA%2B16cqXY8zoQAfCnLmc%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_1080x1080.jpeg?x-expires=1628776800&x-signature=6yvl8A%2F0YzHxym9fUp%2BOeOVi3Gs%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "musically-maliva-obj\/1666453706193925",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_100x100.webp?x-expires=1628776800&x-signature=97yd1DAkdhJ0M6QJHxvQF%2FgTxKs%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_100x100.jpeg?x-expires=1628776800&x-signature=rAu0eSImVU4iGLwQ18pAgGSunfo%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "musically-maliva-obj\/1666453706193925",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_720x720.webp?x-expires=1628776800&x-signature=yOUfX8iKYMdPPFYRQJVJkFwc9lk%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_720x720.jpeg?x-expires=1628776800&x-signature=B%2F77Vh8cRMWfouDye3bqTPLOxxc%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 393,
					"following_count": 23,
					"follower_count": 271590,
					"favoriting_count": 835,
					"total_favorited": 4494369,
					"is_block": false,
					"hide_search": false,
					"custom_verify": "",
					"unique_id": "wonderlifebeauty1",
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
					"share_info": {
						"share_url": "",
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
						"share_desc_info": ""
					},
					"with_commerce_entry": false,
					"verification_type": 1,
					"original_musician": {
						"music_count": 0,
						"music_used_count": 0,
						"digg_count": 0
					},
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "US",
					"account_region": "",
					"commerce_user_level": 0,
					"live_agreement": 0,
					"platform_sync_info": null,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1628691262,
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
					"avatar_uri": "musically-maliva-obj\/1666453706193925",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 0,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 1,
					"download_setting": 0,
					"download_prompt_ts": 1608193942,
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
					"share_qrcode_uri": "",
					"item_list": null,
					"user_mode": 1,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/1666453706193925",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_168x168.webp?x-expires=1628776800&x-signature=UNi1iDHj4%2BUScvUHeB6nPeYyBmM%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_168x168.jpeg?x-expires=1628776800&x-signature=EOVAHSeQxYMDcoIU%2BN86t0guxns%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/1666453706193925",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_300x300.webp?x-expires=1628776800&x-signature=vi6HiF66ZEA0FWPfaSiQOUKrstg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1666453706193925~c5_300x300.jpeg?x-expires=1628776800&x-signature=u6Ad8nqsOZYbzjM1e%2BWlQFrQqhU%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAA9fBLXjUC3S76N6XwfAdm-Ah31E9a0l-QKeSicxjJVHH11Pqqhdr-Q-exOTHy-LBd",
					"need_points": null,
					"name_field": "unique_id",
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 0,
					"bold_fields": null,
					"is_private_account": 0,
					"search_user_name": "wonderlifebeauty1",
					"search_user_desc": "beauty",
					"qa_status": 0,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"position": null,
				"uniqid_position": null,
				"effects": null,
				"musics": null,
				"items": null,
				"mix_list": null,
				"challenges": null
			},
			{
				"user_info": {
					"uid": "6840322637332923397",
					"short_id": "0",
					"nickname": "beauty",
					"gender": 0,
					"signature": "Follow me ❤️❤️❤️",
					"avatar_larger": {
						"uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_1080x1080.webp?x-expires=1628776800&x-signature=2QNA6K9i%2FcwGHTJ9aDO9jaKQqz8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_1080x1080.jpeg?x-expires=1628776800&x-signature=1Q9S0WVpsU9Ga%2FvN0mqz3%2Bugd38%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_100x100.webp?x-expires=1628776800&x-signature=MOwaZpIpwi25y2hHyiwwikwKNIE%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_100x100.jpeg?x-expires=1628776800&x-signature=On6jUS2LZz4jK9ZPg3A8GqccrdU%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_720x720.webp?x-expires=1628776800&x-signature=SajICvipfso%2B6ZpYm0Kvy%2Bu2d9E%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_720x720.jpeg?x-expires=1628776800&x-signature=YE0GwYy3K1sam7kAh7UFFk67xCM%3D"
						],
						"width": 720,
						"height": 720
					},
					"birthday": "1900-01-01",
					"follow_status": 0,
					"aweme_count": 423,
					"following_count": 0,
					"follower_count": 360744,
					"favoriting_count": 1,
					"total_favorited": 3386285,
					"is_block": false,
					"hide_search": false,
					"custom_verify": "",
					"unique_id": "onebeautyyy",
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
					"share_info": {
						"share_url": "",
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
						"share_desc_info": ""
					},
					"with_commerce_entry": false,
					"verification_type": 1,
					"original_musician": {
						"music_count": 0,
						"music_used_count": 0,
						"digg_count": 0
					},
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "US",
					"account_region": "",
					"commerce_user_level": 0,
					"live_agreement": 0,
					"platform_sync_info": null,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1628691262,
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
					"avatar_uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
					"follower_status": 0,
					"comment_setting": 0,
					"duet_setting": 0,
					"reflow_page_gid": 0,
					"reflow_page_uid": 0,
					"user_rate": 1,
					"download_setting": 0,
					"download_prompt_ts": 0,
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
					"share_qrcode_uri": "",
					"item_list": null,
					"user_mode": 1,
					"user_period": 0,
					"is_star": false,
					"cv_level": "",
					"type_label": null,
					"ad_cover_url": null,
					"comment_filter_status": 0,
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_168x168.webp?x-expires=1628776800&x-signature=nD9NH55ay6qSbysogB6n72MpG3o%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_168x168.jpeg?x-expires=1628776800&x-signature=Z2M7DWRrnm05VcBEpzgni76vpCE%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_300x300.webp?x-expires=1628776800&x-signature=hTu8wglsdsgoyCbzCxsn4Ldfe1c%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/68307bfcb20b06eea412a28b03f1fefe~c5_300x300.jpeg?x-expires=1628776800&x-signature=mSwotn3BvkZ0514ByAUq%2FzERDm8%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAuDq8bqJrG1vTWOGNbM4kiBsoBcc2Obh56xcBeLa9cvJ5hA_blYe0Nop6ouWBL_ow",
					"need_points": null,
					"name_field": "unique_id",
					"homepage_bottom_toast": null,
					"can_set_geofencing": null,
					"white_cover_url": null,
					"user_tags": null,
					"stitch_setting": 0,
					"bold_fields": null,
					"is_private_account": 0,
					"search_user_name": "onebeautyyy",
					"search_user_desc": "beauty",
					"qa_status": 0,
					"search_highlight": null,
					"mutual_relation_avatars": null,
					"events": null
				},
				"position": null,
				"uniqid_position": null,
				"effects": null,
				"musics": null,
				"items": null,
				"mix_list": null,
				"challenges": null
			}
		],
		"challenge_list": null,
		"music_list": null,
		"cursor": 10,
		"has_more": 1,
		"status_code": 0,
		"qc": "",
		"rid": "202108111414220102450110691D18DD42",
		"log_pb": {
			"impr_id": "202108111414220102450110691D18DD42"
		},
		"extra": {
			"now": 1628691262000,
			"logid": "202108111414220102450110691D18DD42",
			"fatal_item_ids": [],
			"search_request_id": ""
		},
		"input_keyword": "beauty",
		"global_doodle_config": {
			"keyword": "beauty",
			"search_channel": "musically_user",
			"new_source": ""
		}
	}
}
```
