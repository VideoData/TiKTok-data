
# TikTokAPI接口，关键词搜索视频

**请求API：**
```http
http://主机地址/tk/search/videos?token=xxx&keyword=beauty
```
**​**

**请求方式：**
```http
GET
```
**​**

**参数：**

| 参数名 | 必选 | 类型 | 说明 |
| --- | --- | --- | --- |
| token | 是 | string | 接口授权码 |
| keyword | 是 | string | 搜索关键词 |
| cursor | 否 | int | 翻页游标，根据结果返回的cursor传入作为下一页翻页参数，初始为0 |
| sort | 否 | int | 排序类型，最多点赞传入1，最新发布传入2，默认综合排序0 |
| ctime | 否 | int | 发布时间，半年内传入183，一周内传入7，一天内传入1，默认不限0 |





**​**

**返回示例**
```json
{
	"code": 200,
	"msg": "成功",
	"data": {
		"status_code": 0,
		"aweme_list": [
			{
				"aweme_id": "6932229950720216325",
				"desc": "Bye furry friend🐻 #skincare #beauty",
				"create_time": 1614035575,
				"author": {
					"uid": "6752887346621023238",
					"short_id": "0",
					"nickname": "Truly Beauty",
					"gender": 0,
					"signature": "☆ not your average clean beauty ☆\n\n10% off: TIKTOK",
					"avatar_larger": {
						"uri": "musically-maliva-obj\/1660653234929669",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_1080x1080.webp?x-expires=1628773200&x-signature=4EJb26lRr4J8m5jo53RXjVgwJXE%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_1080x1080.jpeg?x-expires=1628773200&x-signature=5Gve%2FfJmi3Fm9rReMqvJsgkVRng%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "musically-maliva-obj\/1660653234929669",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_100x100.webp?x-expires=1628773200&x-signature=2rpE61fUb5jjNc8cnPhMRbx5FcY%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_100x100.jpeg?x-expires=1628773200&x-signature=4TRggBiwphk4bb3Bc3jKpSq%2BXcM%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "musically-maliva-obj\/1660653234929669",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_720x720.webp?x-expires=1628773200&x-signature=6XFXSNB2fssSuW4T%2FIOFRYu140U%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_720x720.jpeg?x-expires=1628773200&x-signature=BVUg2MsfRVSoedCRVSzRUK%2FSY1M%3D"
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
					"unique_id": "trulybeauty",
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
					"verification_type": 0,
					"enterprise_verify_reason": "verified account",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "PH",
					"account_region": "",
					"commerce_user_level": 2,
					"live_agreement": 0,
					"platform_sync_info": null,
					"with_shop_entry": false,
					"is_discipline_member": false,
					"secret": 0,
					"has_orders": false,
					"prevent_download": false,
					"show_image_bubble": false,
					"geofencing": [],
					"unique_id_modify_time": 1628690108,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"ins_id": "trulybeauty",
					"google_account": "",
					"youtube_channel_id": "UCKEW0ZRDVYfSHnD5UlwMrvA",
					"youtube_channel_title": "Truly Beauty",
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
					"avatar_uri": "musically-maliva-obj\/1660653234929669",
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
							"uri": "musically-maliva-obj\/1612555907887110",
							"url_list": [
								"https:\/\/p16-amd-va.tiktokcdn.com\/obj\/musically-maliva-obj\/1612555907887110"
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
					"comment_filter_status": 1,
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/1660653234929669",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_168x168.webp?x-expires=1628773200&x-signature=5iR2yIx9%2FL0ZXwuBTzZtjMLHe8Q%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_168x168.jpeg?x-expires=1628773200&x-signature=WC43TLQmQq8fZg6Gj01tCNqcI4g%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/1660653234929669",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_300x300.webp?x-expires=1628773200&x-signature=KCFlwbcilCI9tssxe1vHFuod2Ko%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_300x300.jpeg?x-expires=1628773200&x-signature=e8uHqsel17r2iJle7LFJqsYcWBU%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAABVkGXkbl2NZzQG7uyOggHxa-IObbd2kiVDQ8LJJ-2qlhMmGLULrAeYAdqzMNedXr",
					"need_points": null,
					"name_field": "unique_id",
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
				"music": {
					"id": 6800370846696212482,
					"id_str": "6800370846696212482",
					"title": "Swaggy",
					"author": "Fluorescent Canyon",
					"album": "Hip Hop + R&B",
					"cover_hd": {
						"uri": "tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8~c5_1080x1080.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_large": {
						"uri": "tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8~c5_720x720.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_medium": {
						"uri": "tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8~c5_200x200.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_thumb": {
						"uri": "tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8~c5_100x100.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-ve-2774\/75f5630c567544f6b1d3401800924dfb",
						"url_list": [
							"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-ve-2774\/75f5630c567544f6b1d3401800924dfb"
						],
						"width": 720,
						"height": 720
					},
					"schema_url": "",
					"source_platform": 10033,
					"start_time": 0,
					"end_time": 0,
					"duration": 60,
					"extra": "{\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0,\"aed_music_dur\":60,\"is_ugc_mapping\":false,\"has_edited\":0}",
					"user_count": 0,
					"position": null,
					"collect_stat": 0,
					"status": 1,
					"offline_desc": "",
					"owner_nickname": "",
					"is_original": false,
					"mid": "6800370846696212482",
					"binded_challenge_id": 0,
					"redirect": false,
					"is_restricted": false,
					"author_deleted": false,
					"is_del_video": false,
					"is_video_self_see": false,
					"owner_handle": "",
					"author_position": null,
					"prevent_download": false,
					"strong_beat_url": {
						"uri": "https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/40e50a8bb9b94f758c53e6ad0bcc652c",
						"url_list": [
							"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/40e50a8bb9b94f758c53e6ad0bcc652c"
						],
						"width": 720,
						"height": 720
					},
					"unshelve_countries": null,
					"prevent_item_download_status": 0,
					"external_song_info": [],
					"preview_start_time": 0,
					"preview_end_time": 0,
					"is_commerce_music": false,
					"is_original_sound": false,
					"audition_duration": 60,
					"shoot_duration": 60,
					"reason_type": 0,
					"artists": [],
					"lyric_short_position": null,
					"mute_share": false,
					"tag_list": null,
					"dmv_auto_show": false,
					"is_author_artist": false,
					"is_pgc": true,
					"is_matched_metadata": false,
					"is_audio_url_with_cookie": false,
					"matched_song": {
						"id": "6800370411813996546",
						"author": "Fluorescent Canyon",
						"title": "Swaggy",
						"h5_url": "",
						"cover_medium": {
							"uri": "tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8",
							"url_list": [
								"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/ee3cbfc8361247a2a42a90503c0b01a8~c5_200x200.jpeg"
							],
							"width": 720,
							"height": 720
						}
					},
					"video_duration": 60,
					"search_highlight": null
				},
				"cha_list": [
					{
						"cid": "504245",
						"cha_name": "SkinCare",
						"desc": "S is for Skincare",
						"schema": "aweme:\/\/aweme\/challenge\/detail?cid=504245",
						"author": {
							"followers_detail": null,
							"platform_sync_info": null,
							"geofencing": null,
							"cover_url": null,
							"item_list": null,
							"type_label": null,
							"ad_cover_url": null,
							"relative_users": null,
							"cha_list": null,
							"need_points": null,
							"homepage_bottom_toast": null,
							"can_set_geofencing": null,
							"white_cover_url": null,
							"user_tags": null,
							"bold_fields": null,
							"search_highlight": null,
							"mutual_relation_avatars": null,
							"events": null
						},
						"user_count": 0,
						"share_info": {
							"share_url": "https:\/\/m.tiktok.com\/h5\/share\/tag\/504245.html?name=skincare&u_code=0&language=en&_d=dk4e43gkjcg74h&share_challenge_id=504245&source=h5_m",
							"share_weibo_desc": "Check out #skincare on TikTok!",
							"share_desc": "Check out #skincare on TikTok!",
							"share_title": "It is a becoming a big trend on TikTok now! Click here: skincare",
							"bool_persist": 0,
							"share_title_myself": "",
							"share_title_other": "",
							"share_signature_url": "",
							"share_signature_desc": "",
							"share_quote": "",
							"share_desc_info": "Check out #skincare on TikTok!"
						},
						"connect_music": [],
						"type": 2,
						"sub_type": 0,
						"is_pgcshow": false,
						"collect_stat": 0,
						"is_challenge": 0,
						"view_count": 0,
						"is_commerce": false,
						"hashtag_profile": "musically-maliva-obj\/9642f0674a37fe1338addde313f6ee42",
						"cha_attrs": null,
						"banner_list": null,
						"extra_attr": {
							"is_live": false
						},
						"show_items": null,
						"search_highlight": null
					}
				],
				"video": {
					"play_addr": {
						"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/d745b264219778180f0613520238b159\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/458a0a72e145725c5827dc9c20d081aa\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=f1e92c9851d84629ae65f0e5349fe4a7"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044fb0000c0q3kp2hjeqih4hvvdcg_h264_540p_1644771",
						"data_size": 5551515,
						"file_hash": "f26440efe1818cc8a9a7e4e2807b541e",
						"file_cs": "c:0-23334-1d5d"
					},
					"cover": {
						"uri": "tos-maliva-p-0068\/5e923a4960ea449096013333739ca8d7",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/5e923a4960ea449096013333739ca8d7?x-expires=1628708400&x-signature=xG%2Bb%2BgfRZRLwJZrr0qKi7SFD7Gc%3D"
						],
						"width": 720,
						"height": 720
					},
					"height": 1024,
					"width": 576,
					"dynamic_cover": {
						"uri": "tos-maliva-p-0068\/6c2b5c4c45804ec5982ad68996010cb1_1614035577",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/6c2b5c4c45804ec5982ad68996010cb1_1614035577?x-expires=1628708400&x-signature=PmUoiVOovI%2FK5xu8PiqF70d0rLg%3D"
						],
						"width": 720,
						"height": 720
					},
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577~tplv-tiktokx-360p.webp?x-expires=1628708400&x-signature=XYntNXwm7oSWtF%2Big8dV%2BmLyKk8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577~tplv-tiktokx-360p.jpeg?x-expires=1628708400&x-signature=VJFkC4Zpd0sAvJpfkHDICcBIdc8%3D"
						],
						"width": 720,
						"height": 720
					},
					"ratio": "540p",
					"download_addr": {
						"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/f6c1c0acc736ce506a1fb53c670c2581\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/f7d6bdf41a66fe5a46dca6ef246cc93f\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_amazing&quality_type=4&source=SEARCH"
						],
						"width": 720,
						"height": 720,
						"data_size": 5933361
					},
					"has_watermark": true,
					"bit_rate": [
						{
							"gear_name": "normal_540_0",
							"quality_type": 20,
							"bit_rate": 1644771,
							"play_addr": {
								"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/d745b264219778180f0613520238b159\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/458a0a72e145725c5827dc9c20d081aa\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=f1e92c9851d84629ae65f0e5349fe4a7"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044fb0000c0q3kp2hjeqih4hvvdcg_h264_540p_1644771",
								"data_size": 5551515,
								"file_hash": "f26440efe1818cc8a9a7e4e2807b541e",
								"file_cs": "c:0-23334-1d5d"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						},
						{
							"gear_name": "lower_540_0",
							"quality_type": 24,
							"bit_rate": 908213,
							"play_addr": {
								"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/cca562e677ee0896265a6896f4cec620\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/9694b36ba53b4d37847a6eaddd0d2aee\/?a=1233&br=1772&bt=886&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amd5N2xoa3M2MzMzZTczM0ApZzdlODtnaTxoNzw1NzQ0ZGdgc2VlbmcvaG5gLS1jMTZzc2JjXjNgY2FhMV40LTE0M2E6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/292cf4316ad410232a8afaa0d7f14a2d\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/9694b36ba53b4d37847a6eaddd0d2aee\/?a=1233&br=1772&bt=886&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amd5N2xoa3M2MzMzZTczM0ApZzdlODtnaTxoNzw1NzQ0ZGdgc2VlbmcvaG5gLS1jMTZzc2JjXjNgY2FhMV40LTE0M2E6Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=ad16174420974ae49dfddf8c56ba4fde"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044fb0000c0q3kp2hjeqih4hvvdcg_h264_540p_908213",
								"data_size": 3065448,
								"file_hash": "ae3a5b6ddb204e3d4852d88d3011e05b",
								"file_cs": "c:0-23334-9319"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						},
						{
							"gear_name": "lowest_540_0",
							"quality_type": 25,
							"bit_rate": 652914,
							"play_addr": {
								"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/1c0cf0c9c4cd4355011f478cca52b916\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/1b7e8ff131f14b239c8147b992dbe071\/?a=1233&br=1274&bt=637&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amd5N2xoa3M2MzMzZTczM0ApOjMzOzs6Nzw7Nzk5PDo7Nmdgc2VlbmcvaG5gLS1jMTZzc2IzYS5fMzViMzUzLzUuM146Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/16f5daab173da189a92f7409a687d6fe\/61142b36\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/1b7e8ff131f14b239c8147b992dbe071\/?a=1233&br=1274&bt=637&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amd5N2xoa3M2MzMzZTczM0ApOjMzOzs6Nzw7Nzk5PDo7Nmdgc2VlbmcvaG5gLS1jMTZzc2IzYS5fMzViMzUzLzUuM146Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=3a867198626648869e48768b810d067e"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044fb0000c0q3kp2hjeqih4hvvdcg_h264_540p_652914",
								"data_size": 2203750,
								"file_hash": "76b98c7dfe6a7ed543a8721a7d6fafb7",
								"file_cs": "c:0-23334-ba89"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						}
					],
					"duration": 27002,
					"download_suffix_logo_addr": {
						"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/f6c1c0acc736ce506a1fb53c670c2581\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/f7d6bdf41a66fe5a46dca6ef246cc93f\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_amazing&quality_type=4&source=SEARCH"
						],
						"width": 720,
						"height": 720,
						"data_size": 5933361
					},
					"has_download_suffix_logo_addr": true,
					"is_h265": 0,
					"cdn_url_expired": 0,
					"need_set_token": false,
					"AiCover": {
						"uri": "tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd?x-expires=1628708400&x-signature=vdqitmxVEBqbTkXXhvfZTAO8f8A%3D"
						],
						"width": 720,
						"height": 720
					},
					"CoverTsp": 0,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044fb0000c0q3kp2hjeqih4hvvdcg\",\"url_list\":[\"https:\/\/v19-us.tiktokcdn.com\/f6c1c0acc736ce506a1fb53c670c2581\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233\\u0026br=3446\\u0026bt=1723\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgkjT3-I\\u0026l=20210811135508010191062197330D805B\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v39-us.tiktokcdn.com\/f7d6bdf41a66fe5a46dca6ef246cc93f\/61142b36\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233\\u0026br=3446\\u0026bt=1723\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgkjT3-I\\u0026l=20210811135508010191062197330D805B\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_amazing\\u0026quality_type=4\\u0026source=SEARCH\"],\"width\":720,\"height\":720,\"data_size\":5933361}}",
					"is_callback": true,
					"tags": null,
					"big_thumbs": null,
					"is_bytevc1": 0,
					"ai_static_cover": {
						"uri": "tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd?x-expires=1628708400&x-signature=vdqitmxVEBqbTkXXhvfZTAO8f8A%3D"
						],
						"width": 720,
						"height": 720
					},
					"ai_dynamic_cover": {
						"uri": "tos-maliva-p-0068\/d5090965f3f34ebdb7aa5582c18bb487",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/d5090965f3f34ebdb7aa5582c18bb487?x-expires=1628708400&x-signature=eJTBbjZCsZOUdvByAraIvLlCcXY%3D"
						],
						"width": 720,
						"height": 720
					},
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/cdffdd3546fa454587fff788cbd247a4",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/cdffdd3546fa454587fff788cbd247a4?x-expires=1628708400&x-signature=rkYoQYi0F5IYhctZ%2FNwtO9EcG7s%3D"
						],
						"width": 720,
						"height": 720
					}
				},
				"share_url": "https:\/\/m.tiktok.com\/v\/6932229950720216325.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6932229950720216325&source=h5_m",
				"user_digged": 0,
				"statistics": {
					"aweme_id": "6932229950720216325",
					"comment_count": 21992,
					"digg_count": 1256636,
					"download_count": 20546,
					"play_count": 16509966,
					"share_count": 56460,
					"forward_count": 0,
					"lose_count": 0,
					"lose_comment_count": 0,
					"whatsapp_share_count": 11726
				},
				"status": {
					"aweme_id": "6932229950720216325",
					"is_delete": false,
					"allow_share": true,
					"allow_comment": true,
					"is_private": false,
					"with_goods": false,
					"private_status": 0,
					"in_reviewing": false,
					"reviewed": 1,
					"self_see": false,
					"is_prohibited": false,
					"download_status": 0,
					"review_result": {
						"review_status": 0
					}
				},
				"rate": 12,
				"text_extra": [
					{
						"start": 19,
						"end": 28,
						"type": 1,
						"hashtag_name": "skincare",
						"hashtag_id": "504245",
						"is_commerce": false
					},
					{
						"start": 29,
						"end": 36,
						"type": 1,
						"hashtag_name": "beauty",
						"hashtag_id": "5393",
						"is_commerce": false
					}
				],
				"is_top": 0,
				"label_top": {
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					],
					"width": 720,
					"height": 720
				},
				"share_info": {
					"share_url": "https:\/\/m.tiktok.com\/v\/6932229950720216325.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6932229950720216325&source=h5_m",
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out Truly Beauty’s video! #TikTok > ",
					"share_desc": "Check out Truly Beauty's video! #TikTok",
					"share_title": "Check out Truly Beauty’s video! #TikTok > ",
					"bool_persist": 0,
					"share_title_myself": "",
					"share_title_other": "",
					"share_link_desc": "",
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_quote": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out Truly Beauty’s video! #TikTok > "
				},
				"distance": "",
				"video_labels": [],
				"is_vr": false,
				"duration": 27002,
				"aweme_type": 0,
				"cmt_swt": false,
				"image_infos": null,
				"risk_infos": {
					"vote": false,
					"warn": false,
					"risk_sink": false,
					"type": 0,
					"content": ""
				},
				"is_relieve": false,
				"sort_label": "",
				"position": null,
				"uniqid_position": null,
				"author_user_id": 6752887346621023238,
				"bodydance_score": 0,
				"geofencing": [],
				"is_hash_tag": 1,
				"is_pgcshow": false,
				"region": "US",
				"video_text": [],
				"collect_stat": 0,
				"label_top_text": null,
				"group_id": "6931868403590237445",
				"prevent_download": false,
				"nickname_position": null,
				"challenge_position": null,
				"item_comment_settings": 0,
				"with_promotional_music": false,
				"long_video": null,
				"item_duet": 0,
				"item_react": 0,
				"without_watermark": false,
				"desc_language": "en",
				"interaction_stickers": null,
				"misc_info": "{}",
				"origin_comment_ids": null,
				"commerce_config_data": null,
				"distribute_type": 1,
				"video_control": {
					"allow_download": true,
					"share_type": 1,
					"show_progress_bar": 0,
					"draft_progress_bar": 0,
					"allow_duet": true,
					"allow_react": true,
					"prevent_download_type": 0,
					"allow_dynamic_wallpaper": true,
					"timer_status": 1,
					"allow_music": true,
					"allow_stitch": true
				},
				"has_vs_entry": false,
				"commerce_info": {
					"auction_ad_invited": false,
					"with_comment_filter_words": false,
					"adv_promotable": true
				},
				"need_vs_entry": false,
				"is_preview": 0,
				"anchors": null,
				"hybrid_label": null,
				"geofencing_regions": null,
				"have_dashboard": false,
				"is_story": 0,
				"item_stitch": 0,
				"cover_labels": null,
				"mask_infos": [],
				"bottom_bar": {
					"content": "Keep watching Learn videos",
					"icon": {
						"uri": "musically-maliva-obj\/learn_feed_icon.png",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/obj\/musically-maliva-obj\/learn_feed_icon.png"
						],
						"width": 720,
						"height": 720
					},
					"type": 0
				},
				"search_desc": "Bye furry friend🐻 #skincare #beauty",
				"search_highlight": [],
				"playlist_blocked": false,
				"green_screen_materials": null,
				"need_trim_step": false
			},
			{
				"aweme_id": "6985955634940480773",
				"desc": "#greenscreenvideo l need new ones #Beauty #Beautiful",
				"create_time": 1626544550,
				"author": {
					"uid": "6985871004531524614",
					"short_id": "0",
					"nickname": "piaopiao34",
					"gender": 0,
					"signature": "Thank you 🙏 follow",
					"avatar_larger": {
						"uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_1080x1080.webp?x-expires=1628773200&x-signature=teJ52T%2BaBYr%2BWt4ndc9xmSlgQZg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_1080x1080.jpeg?x-expires=1628773200&x-signature=06G5qI61fTo0kw4zQbmtwfQHwB0%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_thumb": {
						"uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_100x100.webp?x-expires=1628773200&x-signature=d3RmN%2B7XD%2FwpiY%2B4odo5XUO15J8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_100x100.jpeg?x-expires=1628773200&x-signature=EEZEybV27wsFtloKDssfAWpn3%2Bs%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_720x720.webp?x-expires=1628773200&x-signature=YscUL0MixflUubWjXEemv9OWz0w%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_720x720.jpeg?x-expires=1628773200&x-signature=LYjgt3vYMrlMIlIwPXLuwxhwFFQ%3D"
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
					"unique_id": "piaopiao34",
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
					"verification_type": 0,
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
					"unique_id_modify_time": 1628690108,
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
					"avatar_uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
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
							"uri": "musically-maliva-obj\/1612555907887110",
							"url_list": [
								"https:\/\/p16-amd-va.tiktokcdn.com\/obj\/musically-maliva-obj\/1612555907887110"
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
						"uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_168x168.webp?x-expires=1628773200&x-signature=7sQodwmPsuW4%2FKwzCs1YIv0IAs8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_168x168.jpeg?x-expires=1628773200&x-signature=fujtMcuye8IYfLzfe%2B55evuTTFk%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_300x300": {
						"uri": "tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_300x300.webp?x-expires=1628773200&x-signature=0DjoUcQeRxowUWU1%2Bf4SIkTrXD8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/25f5f5978a84b109637caa2ce5c0a744~c5_300x300.jpeg?x-expires=1628773200&x-signature=hL0IqIRtHaXfYoGZSMvtl9mAVD4%3D"
						],
						"width": 720,
						"height": 720
					},
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAOQ6jwSMbJ_KxEABgTX-jiB9a490uJWyPRR6vR7m1DAVTuQbwQlUVc12D6JeuYae9",
					"need_points": null,
					"name_field": "unique_id",
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
				"music": {
					"id": 6975111026215881478,
					"id_str": "6975111026215881478",
					"title": "original sound - fbadvs",
					"author": "Tik Toker",
					"album": "",
					"cover_hd": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.webp?x-expires=1628773200&x-signature=OiwO2vQzFcCUf%2FPikbQq2VHziFA%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.jpeg?x-expires=1628773200&x-signature=nQ8FeGB0ysKg37MgsjxfqXW%2BXLE%3D"
						],
						"width": 720,
						"height": 720
					},
					"cover_large": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.webp?x-expires=1628773200&x-signature=OiwO2vQzFcCUf%2FPikbQq2VHziFA%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.jpeg?x-expires=1628773200&x-signature=nQ8FeGB0ysKg37MgsjxfqXW%2BXLE%3D"
						],
						"width": 720,
						"height": 720
					},
					"cover_medium": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_720x720.webp?x-expires=1628773200&x-signature=%2B86anEEljvx%2F9hJ8XWjJoLkQZAI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_720x720.jpeg?x-expires=1628773200&x-signature=pb1iPkgDdKYUMQy8UL%2BnQDc59zA%3D"
						],
						"width": 720,
						"height": 720
					},
					"cover_thumb": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_100x100.webp?x-expires=1628773200&x-signature=oF93m1W6wKvl4A9myHwYfmDF7fU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_100x100.jpeg?x-expires=1628773200&x-signature=0aJFLwGyxZ%2FWzmONgDDJuiIAgxw%3D"
						],
						"width": 720,
						"height": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/musically-maliva-obj\/6975111192054336261.mp3",
						"url_list": [
							"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/musically-maliva-obj\/6975111192054336261.mp3"
						],
						"width": 720,
						"height": 720
					},
					"schema_url": "",
					"source_platform": 72,
					"start_time": 0,
					"end_time": 0,
					"duration": 15,
					"extra": "{\"is_ugc_mapping\":true,\"has_edited\":0,\"reviewed\":0,\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0}",
					"user_count": 0,
					"position": null,
					"collect_stat": 0,
					"status": 1,
					"offline_desc": "",
					"owner_id": "6975043839439700997",
					"owner_nickname": "Tik Toker",
					"is_original": false,
					"mid": "6975111026215881478",
					"binded_challenge_id": 0,
					"redirect": false,
					"is_restricted": false,
					"author_deleted": false,
					"is_del_video": false,
					"is_video_self_see": false,
					"owner_handle": "fbadvs",
					"author_position": null,
					"prevent_download": false,
					"unshelve_countries": null,
					"prevent_item_download_status": 0,
					"external_song_info": [],
					"sec_uid": "MS4wLjABAAAAzWAkqXJzQGs2tBUXDrrvT5rWxhgXgud2wMOlG0MVTEU1cub9g0v1vQ3OqSb9sbnf",
					"avatar_thumb": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_100x100.webp?x-expires=1628773200&x-signature=oF93m1W6wKvl4A9myHwYfmDF7fU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_100x100.jpeg?x-expires=1628773200&x-signature=0aJFLwGyxZ%2FWzmONgDDJuiIAgxw%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_720x720.webp?x-expires=1628773200&x-signature=%2B86anEEljvx%2F9hJ8XWjJoLkQZAI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_720x720.jpeg?x-expires=1628773200&x-signature=pb1iPkgDdKYUMQy8UL%2BnQDc59zA%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_large": {
						"uri": "musically-maliva-obj\/1594805258216454",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.webp?x-expires=1628773200&x-signature=OiwO2vQzFcCUf%2FPikbQq2VHziFA%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1594805258216454~c5_1080x1080.jpeg?x-expires=1628773200&x-signature=nQ8FeGB0ysKg37MgsjxfqXW%2BXLE%3D"
						],
						"width": 720,
						"height": 720
					},
					"preview_start_time": 0,
					"preview_end_time": 0,
					"is_commerce_music": true,
					"is_original_sound": true,
					"audition_duration": 15,
					"shoot_duration": 15,
					"reason_type": 0,
					"artists": [],
					"lyric_short_position": null,
					"mute_share": false,
					"tag_list": null,
					"dmv_auto_show": false,
					"is_author_artist": false,
					"is_pgc": false,
					"is_matched_metadata": false,
					"is_audio_url_with_cookie": false,
					"matched_pgc_sound": {
						"author": "Hatesonny",
						"title": "KILL BILL (FAST)",
						"mixed_title": "original sound - fbadvs (Contains music from: KILL BILL (FAST) - Hatesonny)",
						"mixed_author": "Contains music from: \"KILL BILL (FAST)\""
					},
					"matched_song": {
						"id": "6951967086843299841",
						"author": "Hatesonny",
						"title": "KILL BILL (FAST)",
						"h5_url": "",
						"cover_medium": {
							"uri": "tos-useast2a-v-2774\/98b497a2cb284669a05a5bcfec41d79d",
							"url_list": [
								"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/98b497a2cb284669a05a5bcfec41d79d~c5_200x200.jpeg"
							],
							"width": 720,
							"height": 720
						}
					},
					"video_duration": 15,
					"search_highlight": null
				},
				"cha_list": [
					{
						"cid": "79073378",
						"cha_name": "greenscreenvideo",
						"desc": "Try out our new #GreenScreenVideo Creative Effect! Just update TikTok, pick a video from your camera roll, stand in front of a plain background, and make the next TikTok masterpiece.",
						"schema": "aweme:\/\/aweme\/challenge\/detail?cid=79073378",
						"author": {
							"followers_detail": null,
							"platform_sync_info": null,
							"geofencing": null,
							"cover_url": null,
							"item_list": null,
							"type_label": null,
							"ad_cover_url": null,
							"relative_users": null,
							"cha_list": null,
							"need_points": null,
							"homepage_bottom_toast": null,
							"can_set_geofencing": null,
							"white_cover_url": null,
							"user_tags": null,
							"bold_fields": null,
							"search_highlight": null,
							"mutual_relation_avatars": null,
							"events": null
						},
						"user_count": 0,
						"share_info": {
							"share_url": "https:\/\/m.tiktok.com\/h5\/share\/tag\/79073378.html?name=greenscreenvideo&u_code=0&language=en&_d=dk4e43gkjcg74h&share_challenge_id=79073378&source=h5_m",
							"share_weibo_desc": "Check out #greenscreenvideo on TikTok!",
							"share_desc": "Check out #greenscreenvideo on TikTok!",
							"share_title": "It is a becoming a big trend on TikTok now! Click here: greenscreenvideo",
							"bool_persist": 0,
							"share_title_myself": "",
							"share_title_other": "",
							"share_signature_url": "",
							"share_signature_desc": "",
							"share_quote": "",
							"share_desc_info": "Check out #greenscreenvideo on TikTok!"
						},
						"connect_music": [],
						"type": 2,
						"sub_type": 0,
						"is_pgcshow": false,
						"collect_stat": 0,
						"is_challenge": 0,
						"view_count": 0,
						"is_commerce": false,
						"hashtag_profile": "musically-maliva-obj\/6cffd61f5cca26b357952679681bd693",
						"cha_attrs": null,
						"banner_list": null,
						"extra_attr": {
							"is_live": false
						},
						"show_items": null,
						"search_highlight": null
					}
				],
				"video": {
					"play_addr": {
						"uri": "v09044g40000c3phj7bc77ufog0s4a60",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/8c4ecb377adcc8b0b8fc338f47b89260\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/d56eeeca0a4c44158191550b5b1d5ee4\/?a=1233&br=2108&bt=1054&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZ2c1ZWU7ZWRoN2g2NWkzaGczMS1scjRfZ21gLS1kMTZzc182NGNfLmNhYi5fYGAvLjY6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/cce1af8eb16ffc6821e8fcdcc99b467a\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/d56eeeca0a4c44158191550b5b1d5ee4\/?a=1233&br=2108&bt=1054&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZ2c1ZWU7ZWRoN2g2NWkzaGczMS1scjRfZ21gLS1kMTZzc182NGNfLmNhYi5fYGAvLjY6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=e901f22c3ceb41eeadbf81bbbf27d9db"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044g40000c3phj7bc77ufog0s4a60_h264_540p_1079876",
						"data_size": 2065264,
						"file_hash": "b48affa4a291414ce853a1d46eb81118",
						"file_cs": "c:0-13701-a33f"
					},
					"cover": {
						"uri": "tos-maliva-p-0068\/c2f8198cac1f41d4bd04343dc10917b7",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c2f8198cac1f41d4bd04343dc10917b7?x-expires=1628708400&x-signature=wlr4cg4aPktzervF%2F4M5DAZ5HjE%3D"
						],
						"width": 720,
						"height": 720
					},
					"height": 1024,
					"width": 576,
					"dynamic_cover": {
						"uri": "tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552?x-expires=1628708400&x-signature=9au0uG6hRxPS20chve8x48c36c0%3D"
						],
						"width": 720,
						"height": 720
					},
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/34182c9f3f084c3baae07522c998f415_1626544552",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/34182c9f3f084c3baae07522c998f415_1626544552~tplv-tiktokx-360p.webp?x-expires=1628708400&x-signature=pC7zd7TzZgsJDQHB7B73B8McUCc%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/34182c9f3f084c3baae07522c998f415_1626544552~tplv-tiktokx-360p.jpeg?x-expires=1628708400&x-signature=psWfGayBB11I64FTEsfam4DZ4GM%3D"
						],
						"width": 720,
						"height": 720
					},
					"ratio": "540p",
					"download_addr": {
						"uri": "v09044g40000c3phj7bc77ufog0s4a60",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/ed260c253e224abad71a605d7aa20175\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/f40deaa1dd6242248d717e2689eaf8fd\/?a=1233&br=1934&bt=967&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApNDo1OzNkMztoN2g7NDs0M2czMS1scjRfZ21gLS1kMTZzc15hNi4yL14wYTMuY2A0M2M6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/7da75e6ed8ef9ba56c4076d08ff6a578\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/f40deaa1dd6242248d717e2689eaf8fd\/?a=1233&br=1934&bt=967&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApNDo1OzNkMztoN2g7NDs0M2czMS1scjRfZ21gLS1kMTZzc15hNi4yL14wYTMuY2A0M2M6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=4&source=SEARCH"
						],
						"width": 720,
						"height": 720,
						"data_size": 2377473
					},
					"has_watermark": true,
					"bit_rate": [
						{
							"gear_name": "normal_540_0",
							"quality_type": 20,
							"bit_rate": 1079876,
							"play_addr": {
								"uri": "v09044g40000c3phj7bc77ufog0s4a60",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/8c4ecb377adcc8b0b8fc338f47b89260\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/d56eeeca0a4c44158191550b5b1d5ee4\/?a=1233&br=2108&bt=1054&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZ2c1ZWU7ZWRoN2g2NWkzaGczMS1scjRfZ21gLS1kMTZzc182NGNfLmNhYi5fYGAvLjY6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/cce1af8eb16ffc6821e8fcdcc99b467a\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/d56eeeca0a4c44158191550b5b1d5ee4\/?a=1233&br=2108&bt=1054&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZ2c1ZWU7ZWRoN2g2NWkzaGczMS1scjRfZ21gLS1kMTZzc182NGNfLmNhYi5fYGAvLjY6Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=e901f22c3ceb41eeadbf81bbbf27d9db"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c3phj7bc77ufog0s4a60_h264_540p_1079876",
								"data_size": 2065264,
								"file_hash": "b48affa4a291414ce853a1d46eb81118",
								"file_cs": "c:0-13701-a33f"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						},
						{
							"gear_name": "lower_540_0",
							"quality_type": 24,
							"bit_rate": 683231,
							"play_addr": {
								"uri": "v09044g40000c3phj7bc77ufog0s4a60",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/d62a124f5725dc259d72d47d5ceadd8b\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/c13d247d795a4bfb829f6a2f610cfb52\/?a=1233&br=1334&bt=667&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=M2R2amk6ZjprNjMzNzczM0ApOWg8NmVmZWQ0Nzg1Z2c1NmczMS1scjRfZ21gLS1kMTZzczM1NC01L14zMTEyMzBhNWM6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/0ee44f7226b5b3fbc37cc63272d95af9\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/c13d247d795a4bfb829f6a2f610cfb52\/?a=1233&br=1334&bt=667&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=M2R2amk6ZjprNjMzNzczM0ApOWg8NmVmZWQ0Nzg1Z2c1NmczMS1scjRfZ21gLS1kMTZzczM1NC01L14zMTEyMzBhNWM6Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=3f28ddd326554414a6bac2b83097e866"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c3phj7bc77ufog0s4a60_h264_540p_683231",
								"data_size": 1306681,
								"file_hash": "e2f7d8c64d204042b79a0fdc1b3ff444",
								"file_cs": "c:0-13701-f382"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						},
						{
							"gear_name": "lowest_540_0",
							"quality_type": 25,
							"bit_rate": 528271,
							"play_addr": {
								"uri": "v09044g40000c3phj7bc77ufog0s4a60",
								"url_list": [
									"https:\/\/v19-us.tiktokcdn.com\/70e766fbc24c148a19191537a1b8478d\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/4e7725311ecd4b58ac70ad6019b6d203\/?a=1233&br=1030&bt=515&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=M2R2amk6ZjprNjMzNzczM0ApNDY8M2g7OmVmN2ZmNTw0OmczMS1scjRfZ21gLS1kMTZzc2BhX2IyXjA2MF4xYjViYmE6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/e223427d372e2bde89a4e336bbadb166\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/4e7725311ecd4b58ac70ad6019b6d203\/?a=1233&br=1030&bt=515&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=M2R2amk6ZjprNjMzNzczM0ApNDY8M2g7OmVmN2ZmNTw0OmczMS1scjRfZ21gLS1kMTZzc2BhX2IyXjA2MF4xYjViYmE6Yw%3D%3D&vl=&vr=",
									"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&is_play_url=1&source=PackSourceEnum_SEARCH&file_id=7d1e9e28cec44ac3b9738ae50e9b3d1c"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c3phj7bc77ufog0s4a60_h264_540p_528271",
								"data_size": 1010319,
								"file_hash": "8575b9689e4092fe67322457d7a26c73",
								"file_cs": "c:0-13701-44be"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						}
					],
					"duration": 15300,
					"download_suffix_logo_addr": {
						"uri": "v09044g40000c3phj7bc77ufog0s4a60",
						"url_list": [
							"https:\/\/v19-us.tiktokcdn.com\/6158b9475a01ac1665cc990674ded2cc\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/02251da716e649c49204948dc839f026\/?a=1233&br=2012&bt=1006&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZDRpN2g5NmU3NzdpNmY3OGczMS1scjRfZ21gLS1kMTZzc18tLWEuXjYuNGFgNjBjL2E6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/4f86652f88b12a6530168ae83ba68dfb\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/02251da716e649c49204948dc839f026\/?a=1233&br=2012&bt=1006&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgkjT3-I&l=20210811135508010191062197330D805B&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2R2amk6ZjprNjMzNzczM0ApZDRpN2g5NmU3NzdpNmY3OGczMS1scjRfZ21gLS1kMTZzc18tLWEuXjYuNGFgNjBjL2E6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_surprise&quality_type=4&source=SEARCH"
						],
						"width": 720,
						"height": 720,
						"data_size": 2334549
					},
					"has_download_suffix_logo_addr": true,
					"is_h265": 0,
					"cdn_url_expired": 0,
					"need_set_token": false,
					"CoverTsp": 0,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044g40000c3phj7bc77ufog0s4a60\",\"url_list\":[\"https:\/\/v19-us.tiktokcdn.com\/6158b9475a01ac1665cc990674ded2cc\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/02251da716e649c49204948dc839f026\/?a=1233\\u0026br=2012\\u0026bt=1006\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgkjT3-I\\u0026l=20210811135508010191062197330D805B\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=M2R2amk6ZjprNjMzNzczM0ApZDRpN2g5NmU3NzdpNmY3OGczMS1scjRfZ21gLS1kMTZzc18tLWEuXjYuNGFgNjBjL2E6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v39-us.tiktokcdn.com\/4f86652f88b12a6530168ae83ba68dfb\/61142b2b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/02251da716e649c49204948dc839f026\/?a=1233\\u0026br=2012\\u0026bt=1006\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgkjT3-I\\u0026l=20210811135508010191062197330D805B\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=M2R2amk6ZjprNjMzNzczM0ApZDRpN2g5NmU3NzdpNmY3OGczMS1scjRfZ21gLS1kMTZzc18tLWEuXjYuNGFgNjBjL2E6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c3phj7bc77ufog0s4a60\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_surprise\\u0026quality_type=4\\u0026source=SEARCH\"],\"width\":720,\"height\":720,\"data_size\":2334549}}",
					"is_callback": true,
					"tags": null,
					"big_thumbs": null,
					"is_bytevc1": 0,
					"meta": "{\"peak\":\"1\",\"loudness\":\"-9.6\"}",
					"ai_dynamic_cover": {
						"uri": "tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552?x-expires=1628708400&x-signature=9au0uG6hRxPS20chve8x48c36c0%3D"
						],
						"width": 720,
						"height": 720
					},
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c7f88464feaf4aea8f24381ef03554a3_1626544552?x-expires=1628708400&x-signature=9au0uG6hRxPS20chve8x48c36c0%3D"
						],
						"width": 720,
						"height": 720
					}
				},
				"share_url": "https:\/\/m.tiktok.com\/v\/6985955634940480773.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6985955634940480773&source=h5_m",
				"user_digged": 0,
				"statistics": {
					"aweme_id": "6985955634940480773",
					"comment_count": 315,
					"digg_count": 14914,
					"download_count": 726,
					"play_count": 356320,
					"share_count": 549,
					"forward_count": 0,
					"lose_count": 0,
					"lose_comment_count": 0,
					"whatsapp_share_count": 315
				},
				"status": {
					"aweme_id": "6985955634940480773",
					"is_delete": false,
					"allow_share": true,
					"allow_comment": true,
					"is_private": false,
					"with_goods": false,
					"private_status": 0,
					"in_reviewing": false,
					"reviewed": 1,
					"self_see": false,
					"is_prohibited": false,
					"download_status": 0,
					"review_result": {
						"review_status": 0
					}
				},
				"rate": 12,
				"text_extra": [
					{
						"start": 0,
						"end": 17,
						"type": 1,
						"hashtag_name": "greenscreenvideo",
						"hashtag_id": "79073378",
						"is_commerce": false
					},
					{
						"start": 34,
						"end": 41,
						"type": 1,
						"hashtag_name": "beauty",
						"hashtag_id": "5393",
						"is_commerce": false
					},
					{
						"start": 42,
						"end": 52,
						"type": 1,
						"hashtag_name": "beautiful",
						"hashtag_id": "5297",
						"is_commerce": false
					}
				],
				"is_top": 0,
				"label_top": {
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					],
					"width": 720,
					"height": 720
				},
				"share_info": {
					"share_url": "https:\/\/m.tiktok.com\/v\/6985955634940480773.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6985955634940480773&source=h5_m",
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out piaopiao34’s video! #TikTok > ",
					"share_desc": "Check out piaopiao34's video! #TikTok",
					"share_title": "Check out piaopiao34’s video! #TikTok > ",
					"bool_persist": 0,
					"share_title_myself": "",
					"share_title_other": "",
					"share_link_desc": "",
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_quote": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out piaopiao34’s video! #TikTok > "
				},
				"distance": "",
				"video_labels": [],
				"is_vr": false,
				"duration": 15300,
				"aweme_type": 0,
				"cmt_swt": false,
				"image_infos": null,
				"risk_infos": {
					"vote": false,
					"warn": false,
					"risk_sink": false,
					"type": 0,
					"content": ""
				},
				"is_relieve": false,
				"sort_label": "",
				"position": null,
				"uniqid_position": null,
				"author_user_id": 6985871004531524614,
				"bodydance_score": 0,
				"geofencing": [],
				"is_hash_tag": 1,
				"is_pgcshow": false,
				"region": "US",
				"video_text": [],
				"collect_stat": 0,
				"label_top_text": null,
				"stickers": "454747",
				"group_id": "6985955634940480773",
				"prevent_download": false,
				"nickname_position": null,
				"challenge_position": null,
				"item_comment_settings": 0,
				"with_promotional_music": false,
				"sticker_detail": {
					"id": "454747",
					"name": "Green Screen Video",
					"children": null,
					"owner_id": "",
					"tags": null,
					"sec_uid": "",
					"linked_anchors": null
				},
				"long_video": null,
				"item_duet": 0,
				"item_react": 0,
				"without_watermark": false,
				"desc_language": "en",
				"interaction_stickers": null,
				"misc_info": "{}",
				"origin_comment_ids": null,
				"commerce_config_data": null,
				"distribute_type": 1,
				"video_control": {
					"allow_download": true,
					"share_type": 1,
					"show_progress_bar": 0,
					"draft_progress_bar": 0,
					"allow_duet": true,
					"allow_react": true,
					"prevent_download_type": 0,
					"allow_dynamic_wallpaper": true,
					"timer_status": 1,
					"allow_music": true,
					"allow_stitch": true
				},
				"has_vs_entry": false,
				"commerce_info": {
					"auction_ad_invited": false,
					"with_comment_filter_words": false,
					"adv_promotable": false
				},
				"need_vs_entry": false,
				"is_preview": 0,
				"anchors": null,
				"hybrid_label": null,
				"geofencing_regions": null,
				"have_dashboard": false,
				"is_story": 0,
				"item_stitch": 0,
				"cover_labels": null,
				"mask_infos": [],
				"search_desc": "#greenscreenvideo l need new ones #Beauty #Beautiful",
				"search_highlight": [],
				"playlist_blocked": false,
				"green_screen_materials": null,
				"need_trim_step": false
			}
		],
		"has_more": 1,
		"cursor": 10,
		"extra": {
			"now": 1628690108000,
			"logid": "20210811135508010191062197330D805B",
			"fatal_item_ids": [],
			"search_request_id": ""
		},
		"log_pb": {
			"impr_id": "20210811135508010191062197330D805B"
		},
		"backtrace": "",
		"global_doodle_config": {
			"display_filter_bar": 1,
			"keyword": "beauty",
			"search_channel": "musically_video",
			"new_source": "switch_tab"
		}
	}
}
```
