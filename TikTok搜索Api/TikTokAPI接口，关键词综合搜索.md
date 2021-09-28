
# TikTokAPI接口，关键词综合搜索

**请求API：**
```http
http://主机地址/tk/search/general?token=xxx&keyword=beauty
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



**​**

**返回示例**
```json
{
	"code": 200,
	"msg": "成功",
	"data": {
		"status_code": 0,
		"data": [
			{
				"type": 1,
				"aweme_info": {
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
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_1080x1080.webp?x-expires=1628776800&x-signature=tJCOHm2jmOQVRv8L7aUnQGINbDU%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_1080x1080.jpeg?x-expires=1628776800&x-signature=t3RFyJX2sJq5qpNmlLn1I6GNGZs%3D"
							],
							"width": 720,
							"height": 720
						},
						"avatar_thumb": {
							"uri": "musically-maliva-obj\/1660653234929669",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_100x100.webp?x-expires=1628776800&x-signature=NJcJ7QOlJPfrWGYjLSxIGkn0ee4%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_100x100.jpeg?x-expires=1628776800&x-signature=FXTga7M9Pvo00TIFpnVCnDjeoCY%3D"
							],
							"width": 720,
							"height": 720
						},
						"avatar_medium": {
							"uri": "musically-maliva-obj\/1660653234929669",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_720x720.webp?x-expires=1628776800&x-signature=1H6MZDfmQ%2BVQxfJR7lxrULc1ToQ%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_720x720.jpeg?x-expires=1628776800&x-signature=UHGg6VQ33xkP9MxLaelbvOyxlLA%3D"
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
						"unique_id_modify_time": 1628691960,
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
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_168x168.webp?x-expires=1628776800&x-signature=p1BUjYIXOLIGyh0K%2FYq0rrCD%2FN8%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_168x168.jpeg?x-expires=1628776800&x-signature=ERcgoZr3TbZ93zJ8rL7ZfWjSA%2FM%3D"
							],
							"width": 720,
							"height": 720
						},
						"avatar_300x300": {
							"uri": "musically-maliva-obj\/1660653234929669",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_300x300.webp?x-expires=1628776800&x-signature=pwbZDwCUDmECcUxh6bbMt%2B5sAsA%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660653234929669~c5_300x300.jpeg?x-expires=1628776800&x-signature=RueSAbVRiHjSwiWJQsNEilhY5J0%3D"
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
						"extra": "{\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0,\"aed_music_dur\":60,\"is_ugc_mapping\":false,\"has_edited\":0,\"reviewed\":1}",
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
								"https:\/\/v39-us.tiktokcdn.com\/45fe2e38f2a53ba6a9926f518d735729\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
								"https:\/\/v19-us.tiktokcdn.com\/2f57367590f777fa217d385ababf8098\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
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
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/5e923a4960ea449096013333739ca8d7?x-expires=1628712000&x-signature=hFGksY%2FvzOVr4pmXcyo8w74Jrm0%3D"
							],
							"width": 720,
							"height": 720
						},
						"height": 1024,
						"width": 576,
						"dynamic_cover": {
							"uri": "tos-maliva-p-0068\/6c2b5c4c45804ec5982ad68996010cb1_1614035577",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/6c2b5c4c45804ec5982ad68996010cb1_1614035577?x-expires=1628712000&x-signature=6LdiUWmWEV3K3PQd7K36hWuUngs%3D"
							],
							"width": 720,
							"height": 720
						},
						"origin_cover": {
							"uri": "tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577~tplv-tiktokx-360p.webp?x-expires=1628712000&x-signature=XKU0mtz6YAqJkEP3LappvSlVEpo%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/28eaa93d8aad42048221693380afe536_1614035577~tplv-tiktokx-360p.jpeg?x-expires=1628712000&x-signature=LyVEblB7K67wbBdOJms3J2cpSXA%3D"
							],
							"width": 720,
							"height": 720
						},
						"ratio": "540p",
						"download_addr": {
							"uri": "v09044fb0000c0q3kp2hjeqih4hvvdcg",
							"url_list": [
								"https:\/\/v39-us.tiktokcdn.com\/c0338a203cc3365e4088ad0cbfae8b1e\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
								"https:\/\/v19-us.tiktokcdn.com\/962c8b0f987a9d761bbaacebf7af5cbe\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
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
										"https:\/\/v39-us.tiktokcdn.com\/45fe2e38f2a53ba6a9926f518d735729\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
										"https:\/\/v19-us.tiktokcdn.com\/2f57367590f777fa217d385ababf8098\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/90891a382b5d4583a9657575238e81b4\/?a=1233&br=3212&bt=1606&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApZGg8NmhpOWQ1N2c4PDVoaWdgc2VlbmcvaG5gLS1jMTZzczQxYzEyLTJiNjM1LjVgNi46Yw%3D%3D&vl=&vr=",
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
										"https:\/\/v39-us.tiktokcdn.com\/231323e6af0172d163d9330c12bd32b7\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/9694b36ba53b4d37847a6eaddd0d2aee\/?a=1233&br=1772&bt=886&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amd5N2xoa3M2MzMzZTczM0ApZzdlODtnaTxoNzw1NzQ0ZGdgc2VlbmcvaG5gLS1jMTZzc2JjXjNgY2FhMV40LTE0M2E6Yw%3D%3D&vl=&vr=",
										"https:\/\/v19-us.tiktokcdn.com\/43572b0208429ef42443c4d435d8511e\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/9694b36ba53b4d37847a6eaddd0d2aee\/?a=1233&br=1772&bt=886&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amd5N2xoa3M2MzMzZTczM0ApZzdlODtnaTxoNzw1NzQ0ZGdgc2VlbmcvaG5gLS1jMTZzc2JjXjNgY2FhMV40LTE0M2E6Yw%3D%3D&vl=&vr=",
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
										"https:\/\/v39-us.tiktokcdn.com\/3a61d83c0c91a4d2cb2a0aa441561a9c\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/1b7e8ff131f14b239c8147b992dbe071\/?a=1233&br=1274&bt=637&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amd5N2xoa3M2MzMzZTczM0ApOjMzOzs6Nzw7Nzk5PDo7Nmdgc2VlbmcvaG5gLS1jMTZzc2IzYS5fMzViMzUzLzUuM146Yw%3D%3D&vl=&vr=",
										"https:\/\/v19-us.tiktokcdn.com\/f1f6e053c46d1b5a20d9f90753135c2d\/61143272\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/1b7e8ff131f14b239c8147b992dbe071\/?a=1233&br=1274&bt=637&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amd5N2xoa3M2MzMzZTczM0ApOjMzOzs6Nzw7Nzk5PDo7Nmdgc2VlbmcvaG5gLS1jMTZzc2IzYS5fMzViMzUzLzUuM146Yw%3D%3D&vl=&vr=",
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
								"https:\/\/v39-us.tiktokcdn.com\/c0338a203cc3365e4088ad0cbfae8b1e\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
								"https:\/\/v19-us.tiktokcdn.com\/962c8b0f987a9d761bbaacebf7af5cbe\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233&br=3446&bt=1723&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=.C~1KIFh7jDWH5xXqtSwuo&l=202108111426000101902192221E0FFE6C&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D&vl=&vr=",
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
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd?x-expires=1628712000&x-signature=g%2BFU7cqjJrGGDbmkkhS1PqRpKk0%3D"
							],
							"width": 720,
							"height": 720
						},
						"CoverTsp": 0,
						"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044fb0000c0q3kp2hjeqih4hvvdcg\",\"url_list\":[\"https:\/\/v39-us.tiktokcdn.com\/c0338a203cc3365e4088ad0cbfae8b1e\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233\\u0026br=3446\\u0026bt=1723\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=.C~1KIFh7jDWH5xXqtSwuo\\u0026l=202108111426000101902192221E0FFE6C\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v19-us.tiktokcdn.com\/962c8b0f987a9d761bbaacebf7af5cbe\/61143272\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/acc9725b4c5d417d9f590576ecb0387f\/?a=1233\\u0026br=3446\\u0026bt=1723\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=.C~1KIFh7jDWH5xXqtSwuo\\u0026l=202108111426000101902192221E0FFE6C\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amd5N2xoa3M2MzMzZTczM0ApNmZmNzlkZTxlN2VlNjYzZWdgc2VlbmcvaG5gLS1jMTZzczFhYF4yMDA0MGBgNF8vYy06Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044fb0000c0q3kp2hjeqih4hvvdcg\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_amazing\\u0026quality_type=4\\u0026source=SEARCH\"],\"width\":720,\"height\":720,\"data_size\":5933361}}",
						"is_callback": true,
						"tags": null,
						"big_thumbs": null,
						"is_bytevc1": 0,
						"ai_static_cover": {
							"uri": "tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/64d90a15c2edfa666337308b0f8aaffd?x-expires=1628712000&x-signature=g%2BFU7cqjJrGGDbmkkhS1PqRpKk0%3D"
							],
							"width": 720,
							"height": 720
						},
						"ai_dynamic_cover": {
							"uri": "tos-maliva-p-0068\/d5090965f3f34ebdb7aa5582c18bb487",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/d5090965f3f34ebdb7aa5582c18bb487?x-expires=1628712000&x-signature=kBH%2BOAIRIy2g6uzNpMdxsraG9g8%3D"
							],
							"width": 720,
							"height": 720
						},
						"ai_dynamic_cover_bak": {
							"uri": "tos-maliva-p-0068\/cdffdd3546fa454587fff788cbd247a4",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/cdffdd3546fa454587fff788cbd247a4?x-expires=1628712000&x-signature=B8JE299TnZ%2FdnyzYshXtDPCQ2Hk%3D"
							],
							"width": 720,
							"height": 720
						}
					},
					"share_url": "https:\/\/m.tiktok.com\/v\/6932229950720216325.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6932229950720216325&source=h5_m",
					"user_digged": 0,
					"statistics": {
						"aweme_id": "6932229950720216325",
						"comment_count": 21994,
						"digg_count": 1256647,
						"download_count": 20546,
						"play_count": 16510209,
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
				}
			}
		],
		"qc": "",
		"cursor": 10,
		"has_more": 1,
		"ad_info": [],
		"extra": {
			"now": 1628691960000,
			"logid": "202108111426000101902192221E0FFE6C",
			"fatal_item_ids": [],
			"search_request_id": ""
		},
		"log_pb": {
			"impr_id": "202108111426000101902192221E0FFE6C"
		},
		"guide_search_words": null,
		"global_doodle_config": {
			"display_filter_bar": 1,
			"keyword": "beauty",
			"search_channel": "musically_general",
			"new_source": "switch_tab"
		},
		"backtrace": ""
	}
}

```
