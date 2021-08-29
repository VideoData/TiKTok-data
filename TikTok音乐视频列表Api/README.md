
#  TikTok音乐视频列表Api

# 联系方式：[点击主页查看](https://github.com/VideoData) 

#  请求Api：
```java
http://主机地址/tk/music/videos?token=xxx&music_id=6767362751674189825&cursor=0
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| ch_id     | int     | string	话题id     | 



#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"has_more": 1,
		"status_code": 0,
		"rid": "2021081606562501024516814053021F71",
		"extra": {
			"now": 1629096986000,
			"fatal_item_ids": [],
			"logid": "2021081606562501024516814053021F71"
		},
		"log_pb": {
			"impr_id": "2021081606562501024516814053021F71"
		},
		"aweme_list": [
			{
				"label_top_text": null,
				"prevent_download": false,
				"user_digged": 0,
				"author_user_id": 6564062791182581765,
				"geofencing": [],
				"geofencing_regions": null,
				"need_trim_step": false,
				"duration": 13651,
				"aweme_type": 0,
				"cmt_swt": false,
				"distribute_type": 1,
				"is_story": 0,
				"cha_list": null,
				"label_top": {
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					],
					"width": 720,
					"height": 720
				},
				"misc_info": "{}",
				"playlist_blocked": false,
				"with_promotional_music": false,
				"long_video": null,
				"uniqid_position": null,
				"bodydance_score": 0,
				"group_id": "6901762673936059654",
				"item_react": 0,
				"interaction_stickers": null,
				"author": {
					"avatar_uri": "musically-maliva-obj\/1661181402174469",
					"user_mode": 1,
					"cv_level": "",
					"need_points": null,
					"qa_status": 0,
					"shield_digg_notice": 0,
					"user_canceled": false,
					"enterprise_verify_reason": "",
					"google_account": "",
					"share_qrcode_uri": "",
					"special_lock": 1,
					"has_facebook_token": false,
					"reflow_page_uid": 0,
					"total_favorited": 0,
					"reflow_page_gid": 0,
					"events": null,
					"nickname": "JACK BE",
					"follower_count": 0,
					"twitter_name": "",
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.webp?x-expires=1629180000&x-signature=fl4foczauisfE1zA6gKUGrkZkB8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.jpeg?x-expires=1629180000&x-signature=mHqrUo%2FM8XRLH%2F0ce1oa8u%2FYeiU%3D"
						],
						"width": 720,
						"height": 720
					},
					"user_tags": null,
					"ins_id": "jackbethatsme",
					"download_prompt_ts": 0,
					"search_highlight": null,
					"bold_fields": null,
					"avatar_larger": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.webp?x-expires=1629180000&x-signature=M%2FItDEuKJ1H%2BQ6sxHOlrXpRDpCU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Dfb9r81SNemGtYzpJ2lzq8wyvpE%3D"
						],
						"width": 720,
						"height": 720
					},
					"follow_status": 0,
					"language": "en",
					"sec_uid": "MS4wLjABAAAAFXqk79mhB3jUiOV3CO30x1md6T44bx0CHdWUUs9Nb9BpaAnVFKFfzzJW4n-dEV-e",
					"unique_id": "jackbethatsme",
					"need_recommend": 0,
					"show_image_bubble": false,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"with_fusion_shop_entry": false,
					"avatar_medium": {
						"height": 720,
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.webp?x-expires=1629180000&x-signature=wyJENE10PHT3nM4ndyJwAxgVmEU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.jpeg?x-expires=1629180000&x-signature=Bq2yFMLaFZJCZzXHySDjUjUW8wA%3D"
						],
						"width": 720
					},
					"shield_follow_notice": 0,
					"react_setting": 0,
					"is_star": false,
					"comment_filter_status": 0,
					"has_youtube_token": false,
					"follower_status": 0,
					"bind_phone": "",
					"youtube_expire_time": 0,
					"share_info": {
						"share_title_myself": "",
						"share_title_other": "",
						"share_desc_info": "",
						"share_url": "",
						"share_weibo_desc": "",
						"share_desc": "",
						"share_title": "",
						"share_qrcode_url": {
							"width": 720,
							"height": 720,
							"uri": "",
							"url_list": []
						}
					},
					"signature": "Naturally Pink-Haired Musician\nCEO of Replying\nLIVEs for Charity\n⬇️MUSIC⬇️",
					"is_discipline_member": false,
					"twitter_id": "",
					"has_email": false,
					"status": 1,
					"comment_setting": 0,
					"live_commerce": false,
					"cha_list": null,
					"unique_id_modify_time": 1629096985,
					"secret": 0,
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
					"verify_info": "",
					"platform_sync_info": null,
					"prevent_download": false,
					"youtube_channel_title": "Jack Be",
					"homepage_bottom_toast": null,
					"aweme_count": 0,
					"type_label": null,
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_300x300.webp?x-expires=1629180000&x-signature=3oGOX7yb%2FU0Nj6HIyp%2FkWHMa6t0%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_300x300.jpeg?x-expires=1629180000&x-signature=W2RYO6Fg1xhltqPV3HVfCOF3BtU%3D"
						],
						"width": 720,
						"height": 720
					},
					"stitch_setting": 0,
					"item_list": null,
					"avatar_thumb": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.webp?x-expires=1629180000&x-signature=T%2FbklGGnBRDXBK5QIkJe0v%2Fo%2BGI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.jpeg?x-expires=1629180000&x-signature=XO0fuGQTQW0ohAuM%2FD0kTexR4%2FU%3D"
						],
						"width": 720,
						"height": 720
					},
					"shield_comment_notice": 0,
					"with_shop_entry": false,
					"accept_private_policy": false,
					"is_phone_binded": false,
					"user_period": 0,
					"apple_account": 0,
					"commerce_user_level": 0,
					"verification_type": 1,
					"mutual_relation_avatars": null,
					"birthday": "1900-01-01",
					"room_id": 0,
					"live_agreement_time": 0,
					"ad_cover_url": null,
					"favoriting_count": 0,
					"is_ad_fake": false,
					"account_region": "",
					"download_setting": 0,
					"has_insights": false,
					"following_count": 0,
					"has_twitter_token": false,
					"create_time": 0,
					"can_set_geofencing": null,
					"live_verify": 0,
					"has_orders": false,
					"geofencing": [],
					"hide_search": false,
					"followers_detail": null,
					"tw_expire_time": 0,
					"live_agreement": 0,
					"youtube_channel_id": "UCZisidnwN6MnaXPWEPYd1vw",
					"gender": 0,
					"custom_verify": "Verified account",
					"fb_expire_time": 0,
					"with_commerce_entry": false,
					"region": "US",
					"short_id": "0",
					"relative_users": null,
					"user_rate": 1,
					"is_block": false,
					"white_cover_url": null,
					"uid": "6564062791182581765",
					"authority_status": 0,
					"duet_setting": 0
				},
				"text_extra": [],
				"image_infos": null,
				"search_highlight": null,
				"origin_comment_ids": null,
				"commerce_info": {
					"with_comment_filter_words": false,
					"adv_promotable": false,
					"auction_ad_invited": false
				},
				"anchors": null,
				"position": null,
				"desc_language": "en",
				"has_vs_entry": false,
				"hybrid_label": null,
				"music": {
					"id_str": "6767362751674189825",
					"author_deleted": false,
					"preview_end_time": 0,
					"audition_duration": 30,
					"is_video_self_see": false,
					"start_time": 0,
					"owner_handle": "",
					"shoot_duration": 30,
					"is_author_artist": true,
					"title": "Beauty Hurts",
					"extra": "{\"schedule_search_time\":0,\"aed_music_dur\":25.23,\"is_ugc_mapping\":false,\"apple_song_id\":1469922665,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{}}",
					"position": null,
					"status": 1,
					"mid": "6767362751674189825",
					"is_pgc": true,
					"is_audio_url_with_cookie": false,
					"author": "Jack Be",
					"collect_stat": 0,
					"is_del_video": false,
					"dmv_auto_show": false,
					"cover_large": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"is_original_sound": false,
					"cover_medium": {
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c"
					},
					"artists": [],
					"schema_url": "",
					"is_matched_metadata": false,
					"album": "The Great Alone",
					"end_time": 0,
					"prevent_download": false,
					"is_commerce_music": false,
					"mute_share": false,
					"cover_thumb": {
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c"
					},
					"owner_nickname": "",
					"redirect": false,
					"duration": 30,
					"binded_challenge_id": 0,
					"search_highlight": null,
					"is_original": false,
					"prevent_item_download_status": 0,
					"lyric_short_position": null,
					"author_position": null,
					"reason_type": 0,
					"tag_list": null,
					"matched_song": {
						"title": "Beauty Hurts",
						"h5_url": "",
						"cover_medium": {
							"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
							],
							"width": 720,
							"height": 720
						},
						"id": "6767936495710898178",
						"author": "Jack Be"
					},
					"play_url": {
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157"
						],
						"width": 720,
						"height": 720,
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157"
					},
					"source_platform": 10033,
					"user_count": 0,
					"offline_desc": "",
					"strong_beat_url": {
						"height": 720,
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144",
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144"
						],
						"width": 720
					},
					"preview_start_time": 15,
					"video_duration": 60,
					"id": 6767362751674189825,
					"cover_hd": {
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c"
					},
					"is_restricted": false,
					"external_song_info": []
				},
				"risk_infos": {
					"type": 0,
					"content": "",
					"vote": false,
					"warn": false,
					"risk_sink": false
				},
				"is_relieve": false,
				"collect_stat": 0,
				"is_preview": 0,
				"commerce_config_data": null,
				"video_labels": [],
				"is_vr": false,
				"is_hash_tag": 1,
				"item_duet": 0,
				"rate": 12,
				"is_top": 0,
				"sort_label": "",
				"cover_labels": null,
				"create_time": 1606941884,
				"is_pgcshow": false,
				"have_dashboard": false,
				"nickname_position": null,
				"without_watermark": false,
				"statistics": {
					"download_count": 1174,
					"share_count": 2522,
					"forward_count": 0,
					"lose_count": 0,
					"whatsapp_share_count": 199,
					"aweme_id": "6901762673936059654",
					"comment_count": 23778,
					"digg_count": 131857,
					"play_count": 878424,
					"lose_comment_count": 0
				},
				"share_info": {
					"bool_persist": 0,
					"share_title_myself": "",
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_url": "https:\/\/m.tiktok.com\/v\/6901762673936059654.html?u_code=dk4e43gkjcg74h&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6901762673936059654&source=h5_m",
					"share_desc": "Check out JACK BE's video! #TikTok",
					"share_title": "Check out JACK BE’s video! #TikTok > ",
					"share_title_other": "",
					"share_link_desc": "",
					"share_quote": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out JACK BE’s video! #TikTok > ",
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out JACK BE’s video! #TikTok > "
				},
				"video_text": [],
				"challenge_position": null,
				"item_comment_settings": 0,
				"desc": "SO I HEARD THIS RUMOR ABOUT THE PERFECT TIKTOK... 😱",
				"region": "US",
				"item_stitch": 0,
				"is_ads": false,
				"video_control": {
					"draft_progress_bar": 0,
					"allow_duet": true,
					"allow_react": true,
					"prevent_download_type": 0,
					"allow_dynamic_wallpaper": true,
					"timer_status": 1,
					"allow_download": true,
					"show_progress_bar": 0,
					"allow_music": true,
					"allow_stitch": true,
					"share_type": 1
				},
				"mask_infos": [],
				"green_screen_materials": null,
				"video": {
					"cdn_url_expired": 0,
					"need_set_token": false,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044a10000bv3vpdnpdca3m33p6h5g\",\"url_list\":[\"https:\/\/v39-us.tiktokcdn.com\/c10c4a8e7ee9cbe5f26452394e509d7b\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233\\u0026br=2310\\u0026bt=1155\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgksT3-I\\u0026l=2021081606562501024516814053021F71\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v16m-us.tiktokcdn.com\/061acc51591a8ab3865d00eeea882b84\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233\\u0026br=2310\\u0026bt=1155\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgksT3-I\\u0026l=2021081606562501024516814053021F71\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_m_suffix\\u0026quality_type=4\\u0026source=MUSIC_AWEME\"],\"width\":720,\"height\":720,\"data_size\":2449432}}",
					"is_callback": true,
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886?x-expires=1629115200&x-signature=fnc87FJSFcWcztv2Lx64o0jmWEk%3D"
						],
						"width": 720,
						"height": 720
					},
					"play_addr": {
						"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/fd042ce9bbade452c1a6b83a60e704c8\/611a6086\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/0d758fdcc47f4903a3753b2623797703\/?a=1233&br=2484&bt=1242&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApPDtmaTU0Zjs1N2Y1MzM7NWcyMzBqXmFrbTBfLS1eMTZzcy81NS80Ni5fYC01MDYvMC86Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/0cfd3c63abc3f0fc292c985b17647527\/611a6086\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/0d758fdcc47f4903a3753b2623797703\/?a=1233&br=2484&bt=1242&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApPDtmaTU0Zjs1N2Y1MzM7NWcyMzBqXmFrbTBfLS1eMTZzcy81NS80Ni5fYC01MDYvMC86Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=2283020923c8402c8bc11927f2c88892"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044a10000bv3vpdnpdca3m33p6h5g_h264_540p_1272136",
						"data_size": 2170742,
						"file_hash": "e136cf2306367dd282218e8aeadd172c",
						"file_cs": "c:0-12404-912b"
					},
					"ratio": "540p",
					"bit_rate": [
						{
							"quality_type": 20,
							"bit_rate": 1272136,
							"play_addr": {
								"width": 720,
								"height": 720,
								"url_key": "v09044a10000bv3vpdnpdca3m33p6h5g_h264_540p_1272136",
								"data_size": 2170742,
								"file_hash": "e136cf2306367dd282218e8aeadd172c",
								"file_cs": "c:0-12404-912b",
								"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/fd042ce9bbade452c1a6b83a60e704c8\/611a6086\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/0d758fdcc47f4903a3753b2623797703\/?a=1233&br=2484&bt=1242&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApPDtmaTU0Zjs1N2Y1MzM7NWcyMzBqXmFrbTBfLS1eMTZzcy81NS80Ni5fYC01MDYvMC86Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/0cfd3c63abc3f0fc292c985b17647527\/611a6086\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/0d758fdcc47f4903a3753b2623797703\/?a=1233&br=2484&bt=1242&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApPDtmaTU0Zjs1N2Y1MzM7NWcyMzBqXmFrbTBfLS1eMTZzcy81NS80Ni5fYC01MDYvMC86Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=2283020923c8402c8bc11927f2c88892"
								]
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "normal_540_0"
						},
						{
							"play_addr": {
								"url_key": "v09044a10000bv3vpdnpdca3m33p6h5g_h264_540p_709443",
								"data_size": 1210577,
								"file_hash": "4896e4e19116e08fa611bb8238fc6325",
								"file_cs": "c:0-12404-bd00",
								"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/ce35da0e07450a46522e9da7963ac33a\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/585f1ca3460f45b4a00cb48d2dd166f1\/?a=1233&br=1384&bt=692&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amtzNjZmc2d5eTMzNDczM0ApOzs2NGk1OmQzNzZpNTpkZ2cyMzBqXmFrbTBfLS1eMTZzczNfMy0wYy4uMWBhXmM2MWM6Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/4dc648b2f2f4710a623129cf2f694667\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/585f1ca3460f45b4a00cb48d2dd166f1\/?a=1233&br=1384&bt=692&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=amtzNjZmc2d5eTMzNDczM0ApOzs2NGk1OmQzNzZpNTpkZ2cyMzBqXmFrbTBfLS1eMTZzczNfMy0wYy4uMWBhXmM2MWM6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=dfa4792ffa3d4c04a1712ff310368b86"
								],
								"width": 720,
								"height": 720
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lower_540_0",
							"quality_type": 24,
							"bit_rate": 709443
						},
						{
							"play_addr": {
								"data_size": 892790,
								"file_hash": "403f17a46575789cbec2276e4f8a61ea",
								"file_cs": "c:0-12404-43e9",
								"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/7e24afeec511e489e2f6f9e1f4a7a445\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/36844f71505f409cb380e8997ce75e19\/?a=1233&br=1020&bt=510&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amtzNjZmc2d5eTMzNDczM0ApOzVnPDlkOzxmN2g3aWloaGcyMzBqXmFrbTBfLS1eMTZzczMzNTMxXjMxYjM1NTU1LTI6Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/c3ea101efb37c507b57fbba42c743315\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/36844f71505f409cb380e8997ce75e19\/?a=1233&br=1020&bt=510&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=amtzNjZmc2d5eTMzNDczM0ApOzVnPDlkOzxmN2g3aWloaGcyMzBqXmFrbTBfLS1eMTZzczMzNTMxXjMxYjM1NTU1LTI6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=e5e0f8f848e846ce9486aa6496d82686"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044a10000bv3vpdnpdca3m33p6h5g_h264_540p_523208"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lowest_540_0",
							"quality_type": 25,
							"bit_rate": 523208
						}
					],
					"has_download_suffix_logo_addr": true,
					"is_h265": 0,
					"big_thumbs": null,
					"dynamic_cover": {
						"height": 720,
						"uri": "tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886?x-expires=1629115200&x-signature=fnc87FJSFcWcztv2Lx64o0jmWEk%3D"
						],
						"width": 720
					},
					"origin_cover": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/54755824136b4cc0a9fa6d4ee47728f5_1606941885",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/54755824136b4cc0a9fa6d4ee47728f5_1606941885~tplv-tiktokx-360p.webp?x-expires=1629115200&x-signature=8em9DDXNktshqBY8TxO6A1aqmgI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/54755824136b4cc0a9fa6d4ee47728f5_1606941885~tplv-tiktokx-360p.jpeg?x-expires=1629115200&x-signature=jF8Q87XNbiin5hsjIhZQee0r974%3D"
						]
					},
					"has_watermark": true,
					"is_bytevc1": 0,
					"ai_dynamic_cover": {
						"height": 720,
						"uri": "tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/76b4c010b16d4a74a6f34ba14ef86de1_1606941886?x-expires=1629115200&x-signature=fnc87FJSFcWcztv2Lx64o0jmWEk%3D"
						],
						"width": 720
					},
					"cover": {
						"uri": "tos-maliva-p-0068\/db9d611f187e4a88a66a40be7f78636e",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/db9d611f187e4a88a66a40be7f78636e~c5_300x400.webp?x-expires=1629115200&x-signature=saCAHr7LVtK6K4UKZm8YXDs8v88%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/db9d611f187e4a88a66a40be7f78636e~c5_300x400.jpeg?x-expires=1629115200&x-signature=WQEJqqzwo6h35LpXvfkZzXOkymU%3D"
						],
						"width": 720,
						"height": 720
					},
					"width": 576,
					"duration": 13651,
					"tags": null,
					"height": 1024,
					"download_addr": {
						"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/c10c4a8e7ee9cbe5f26452394e509d7b\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233&br=2310&bt=1155&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/061acc51591a8ab3865d00eeea882b84\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233&br=2310&bt=1155&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_m_suffix&quality_type=4&source=MUSIC_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 2449432
					},
					"download_suffix_logo_addr": {
						"uri": "v09044a10000bv3vpdnpdca3m33p6h5g",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/c10c4a8e7ee9cbe5f26452394e509d7b\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233&br=2310&bt=1155&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/061acc51591a8ab3865d00eeea882b84\/611a6086\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/f892ddf22203496a824db3199a559ed4\/?a=1233&br=2310&bt=1155&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=amtzNjZmc2d5eTMzNDczM0ApOzM2ZjpoOzs3NzY6NGY7O2cyMzBqXmFrbTBfLS1eMTZzc2E1LTI0YS9fYzVeMF4uXjI6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044a10000bv3vpdnpdca3m33p6h5g&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_m_suffix&quality_type=4&source=MUSIC_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 2449432
					}
				},
				"status": {
					"with_goods": false,
					"private_status": 0,
					"in_reviewing": false,
					"is_prohibited": false,
					"review_result": {
						"review_status": 0
					},
					"allow_comment": true,
					"is_delete": false,
					"allow_share": true,
					"is_private": false,
					"reviewed": 1,
					"self_see": false,
					"download_status": 0,
					"aweme_id": "6901762673936059654"
				},
				"distance": "",
				"aweme_id": "6901762673936059654",
				"share_url": "https:\/\/m.tiktok.com\/v\/6901762673936059654.html?u_code=dk4e43gkjcg74h&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6901762673936059654&source=h5_m",
				"need_vs_entry": false
			},
			{
				"item_react": 0,
				"duration": 12351,
				"cmt_swt": false,
				"label_top_text": null,
				"music": {
					"preview_end_time": 0,
					"is_original_sound": false,
					"search_highlight": null,
					"binded_challenge_id": 0,
					"cover_large": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157",
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157"
						],
						"width": 720,
						"height": 720
					},
					"is_original": false,
					"cover_hd": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"prevent_download": false,
					"is_commerce_music": false,
					"schema_url": "",
					"end_time": 0,
					"strong_beat_url": {
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144",
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144"
						],
						"width": 720,
						"height": 720
					},
					"author": "Jack Be",
					"cover_medium": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"prevent_item_download_status": 0,
					"album": "The Great Alone",
					"is_audio_url_with_cookie": false,
					"owner_handle": "",
					"tag_list": null,
					"redirect": false,
					"author_deleted": false,
					"is_video_self_see": false,
					"artists": [],
					"lyric_short_position": null,
					"is_restricted": false,
					"external_song_info": [],
					"is_matched_metadata": false,
					"id": 6767362751674189825,
					"cover_thumb": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"duration": 30,
					"position": null,
					"owner_nickname": "",
					"reason_type": 0,
					"is_pgc": true,
					"id_str": "6767362751674189825",
					"collect_stat": 0,
					"video_duration": 60,
					"title": "Beauty Hurts",
					"extra": "{\"schedule_search_time\":0,\"aed_music_dur\":25.23,\"is_ugc_mapping\":false,\"apple_song_id\":1469922665,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{}}",
					"status": 1,
					"shoot_duration": 30,
					"is_author_artist": true,
					"matched_song": {
						"cover_medium": {
							"width": 720,
							"height": 720,
							"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
							]
						},
						"id": "6767936495710898178",
						"author": "Jack Be",
						"title": "Beauty Hurts",
						"h5_url": ""
					},
					"start_time": 0,
					"source_platform": 10033,
					"author_position": null,
					"preview_start_time": 15,
					"audition_duration": 30,
					"mute_share": false,
					"offline_desc": "",
					"is_del_video": false,
					"user_count": 0,
					"dmv_auto_show": false,
					"mid": "6767362751674189825"
				},
				"text_extra": [
					{
						"end": 24,
						"user_id": "6799404844744016902",
						"type": 0,
						"sec_uid": "MS4wLjABAAAAK7gOUTKQLyne8PBfMcTReJ_uUBYLwmAMwEyv5PMkyLhwi2lOuPg4g5PJ72G3OkKL",
						"sub_type": 2,
						"start": 9
					}
				],
				"distribute_type": 1,
				"region": "US",
				"collect_stat": 0,
				"sticker_detail": {
					"owner_id": "",
					"tags": null,
					"sec_uid": "",
					"linked_anchors": null,
					"id": "454747",
					"name": "Green Screen Video",
					"children": null
				},
				"without_watermark": false,
				"commerce_config_data": null,
				"video": {
					"duration": 12351,
					"is_h265": 0,
					"width": 576,
					"download_addr": {
						"uri": "v09044g40000c30g7ika8rifonb861e0",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/9a976204f7afd3b373545acf12b3837b\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233&br=3046&bt=1523&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/4ac57917218950f102cbaa08e3ff4d99\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233&br=3046&bt=1523&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=4&source=MUSIC_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 3169701
					},
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165?x-expires=1629115200&x-signature=DhHotrmmBhNS%2FXUS8i1QkCIIwWM%3D"
						],
						"width": 720,
						"height": 720
					},
					"cdn_url_expired": 0,
					"meta": "{\"loudness\":\"-9.3\",\"peak\":\"1\"}",
					"bit_rate": [
						{
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "normal_540_0",
							"quality_type": 20,
							"bit_rate": 1891999,
							"play_addr": {
								"file_cs": "c:0-11374-84de",
								"uri": "v09044g40000c30g7ika8rifonb861e0",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/6da195bb2f63b3101048aa4cd826ed51\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/e225d19b94c44fbf9e80ecc9af7079c0\/?a=1233&br=3694&bt=1847&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApO2c0Zmc8N2Q1N2lkaTZmZWdiM19sZjVoNC1gLS1kMTZzczQvNTIzXzM1YjBiLTYzNTM6Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/3d29b93d4ee524efe2fbcee2f3a1572b\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/e225d19b94c44fbf9e80ecc9af7079c0\/?a=1233&br=3694&bt=1847&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApO2c0Zmc8N2Q1N2lkaTZmZWdiM19sZjVoNC1gLS1kMTZzczQvNTIzXzM1YjBiLTYzNTM6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=b6c836f9a0fe432ea8469bd6c518d287"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c30g7ika8rifonb861e0_h264_540p_1891999",
								"data_size": 2921010,
								"file_hash": "801554ef770e97aa745ee9c65feac359"
							},
							"is_h265": 0
						},
						{
							"quality_type": 24,
							"bit_rate": 1050089,
							"play_addr": {
								"height": 720,
								"url_key": "v09044g40000c30g7ika8rifonb861e0_h264_540p_1050089",
								"data_size": 1621207,
								"file_hash": "9ec9e019a15364f9cf825db4e8a97940",
								"file_cs": "c:0-11374-1fa6",
								"uri": "v09044g40000c30g7ika8rifonb861e0",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/63f2ae7b249b93d00f66b451f200a5a6\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/f2e5028cf0ef48aeb83c05402bdc4e98\/?a=1233&br=2050&bt=1025&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=MzQ7cWl1ZGxqNjMzNzczM0ApZTs3OGg6ZDszNzo0NDs8PGdiM19sZjVoNC1gLS1kMTZzczMzYTE2YjBfNTE0Xy81YjI6Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/aa13a949fb6c8c6caf51e997551cb864\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/f2e5028cf0ef48aeb83c05402bdc4e98\/?a=1233&br=2050&bt=1025&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=MzQ7cWl1ZGxqNjMzNzczM0ApZTs3OGg6ZDszNzo0NDs8PGdiM19sZjVoNC1gLS1kMTZzczMzYTE2YjBfNTE0Xy81YjI6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=959e88121b7744088ba37ee9544d86b6"
								],
								"width": 720
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lower_540_0"
						},
						{
							"bit_rate": 685026,
							"play_addr": {
								"data_size": 1057596,
								"file_hash": "e8dea51b440ffc4da25f11c8632bac21",
								"file_cs": "c:0-11374-5f57",
								"uri": "v09044g40000c30g7ika8rifonb861e0",
								"url_list": [
									"https:\/\/v39-us.tiktokcdn.com\/a68ea20622c57f2d9a734b3ea8c32d69\/611a6085\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/be75361f019e459fb9b4d8dd097db15d\/?a=1233&br=1336&bt=668&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=MzQ7cWl1ZGxqNjMzNzczM0ApNTozZjc1OTw3N2U4ODNkPGdiM19sZjVoNC1gLS1kMTZzczFhMzE2NS1fLTJeXjNiLzE6Yw%3D%3D&vl=&vr=",
									"https:\/\/v16m-us.tiktokcdn.com\/37afc561ae5922d882ab7e4f6a88e62a\/611a6085\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/be75361f019e459fb9b4d8dd097db15d\/?a=1233&br=1336&bt=668&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=MzQ7cWl1ZGxqNjMzNzczM0ApNTozZjc1OTw3N2U4ODNkPGdiM19sZjVoNC1gLS1kMTZzczFhMzE2NS1fLTJeXjNiLzE6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=94a20e565aba45409b602849c4067d24"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c30g7ika8rifonb861e0_h264_540p_685026"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lowest_540_0",
							"quality_type": 25
						}
					],
					"download_suffix_logo_addr": {
						"uri": "v09044g40000c30g7ika8rifonb861e0",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/9a976204f7afd3b373545acf12b3837b\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233&br=3046&bt=1523&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/4ac57917218950f102cbaa08e3ff4d99\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233&br=3046&bt=1523&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=4&source=MUSIC_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 3169701
					},
					"has_download_suffix_logo_addr": true,
					"need_set_token": false,
					"tags": null,
					"is_bytevc1": 0,
					"dynamic_cover": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165?x-expires=1629115200&x-signature=DhHotrmmBhNS%2FXUS8i1QkCIIwWM%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165"
					},
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/63764a04b4e94a759066764422f0758a_1623262166",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/63764a04b4e94a759066764422f0758a_1623262166~tplv-tiktokx-360p.webp?x-expires=1629115200&x-signature=j3vpkHGaQ17tD5l4PjtI3xTXP2k%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/63764a04b4e94a759066764422f0758a_1623262166~tplv-tiktokx-360p.jpeg?x-expires=1629115200&x-signature=6GbLlNQPvNsYrvVc%2F8RK8QIYs0s%3D"
						],
						"width": 720,
						"height": 720
					},
					"height": 1024,
					"ratio": "540p",
					"has_watermark": true,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044g40000c30g7ika8rifonb861e0\",\"url_list\":[\"https:\/\/v39-us.tiktokcdn.com\/9a976204f7afd3b373545acf12b3837b\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233\\u0026br=3046\\u0026bt=1523\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgksT3-I\\u0026l=2021081606562501024516814053021F71\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v16m-us.tiktokcdn.com\/4ac57917218950f102cbaa08e3ff4d99\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/d3f304b17f924534b703f34a4a3c6152\/?a=1233\\u0026br=3046\\u0026bt=1523\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=wZ~ROFGgksT3-I\\u0026l=2021081606562501024516814053021F71\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=MzQ7cWl1ZGxqNjMzNzczM0ApaTgzNGVlM2QzNzg4ODlnNmdiM19sZjVoNC1gLS1kMTZzcy4yYDVhLTYvMy4uXy8zLV86Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_end\\u0026quality_type=4\\u0026source=MUSIC_AWEME\"],\"width\":720,\"height\":720,\"data_size\":3169701}}",
					"is_callback": true,
					"big_thumbs": null,
					"play_addr": {
						"file_hash": "801554ef770e97aa745ee9c65feac359",
						"file_cs": "c:0-11374-84de",
						"uri": "v09044g40000c30g7ika8rifonb861e0",
						"url_list": [
							"https:\/\/v39-us.tiktokcdn.com\/6da195bb2f63b3101048aa4cd826ed51\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/e225d19b94c44fbf9e80ecc9af7079c0\/?a=1233&br=3694&bt=1847&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApO2c0Zmc8N2Q1N2lkaTZmZWdiM19sZjVoNC1gLS1kMTZzczQvNTIzXzM1YjBiLTYzNTM6Yw%3D%3D&vl=&vr=",
							"https:\/\/v16m-us.tiktokcdn.com\/3d29b93d4ee524efe2fbcee2f3a1572b\/611a6085\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/e225d19b94c44fbf9e80ecc9af7079c0\/?a=1233&br=3694&bt=1847&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=wZ~ROFGgksT3-I&l=2021081606562501024516814053021F71&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=MzQ7cWl1ZGxqNjMzNzczM0ApO2c0Zmc8N2Q1N2lkaTZmZWdiM19sZjVoNC1gLS1kMTZzczQvNTIzXzM1YjBiLTYzNTM6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c30g7ika8rifonb861e0&line=0&is_play_url=1&source=PackSourceEnum_MUSIC_AWEME&file_id=b6c836f9a0fe432ea8469bd6c518d287"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044g40000c30g7ika8rifonb861e0_h264_540p_1891999",
						"data_size": 2921010
					},
					"cover": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/2114b6c77f344ea9af0abcfb81bc5ec3",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/2114b6c77f344ea9af0abcfb81bc5ec3~c5_300x400.webp?x-expires=1629115200&x-signature=c0Rd8y7KnxDntoGbLQkG0ggYGo0%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/2114b6c77f344ea9af0abcfb81bc5ec3~c5_300x400.jpeg?x-expires=1629115200&x-signature=ho3tr2NnfgYk6svGf0xE57cv21Q%3D"
						]
					},
					"ai_dynamic_cover": {
						"uri": "tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/6ec4c218e5b145008ed573bdda2c42f1_1623262165?x-expires=1629115200&x-signature=DhHotrmmBhNS%2FXUS8i1QkCIIwWM%3D"
						],
						"width": 720,
						"height": 720
					}
				},
				"is_ads": false,
				"bodydance_score": 0,
				"cha_list": null,
				"share_info": {
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out JACK BE’s video! #TikTok > ",
					"share_desc": "Check out JACK BE's video! #TikTok",
					"bool_persist": 0,
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out JACK BE’s video! #TikTok > ",
					"share_url": "https:\/\/m.tiktok.com\/v\/6971857887962418437.html?u_code=dk4e43gkjcg74h&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6971857887962418437&source=h5_m",
					"share_title": "Check out JACK BE’s video! #TikTok > ",
					"share_title_myself": "",
					"share_title_other": "",
					"share_link_desc": "",
					"share_quote": ""
				},
				"with_promotional_music": false,
				"is_vr": false,
				"misc_info": "{}",
				"anchors": null,
				"have_dashboard": false,
				"aweme_id": "6971857887962418437",
				"author": {
					"follow_status": 0,
					"followers_detail": null,
					"platform_sync_info": null,
					"react_setting": 0,
					"nickname": "JACK BE",
					"unique_id": "jackbethatsme",
					"shield_digg_notice": 0,
					"has_insights": false,
					"live_agreement": 0,
					"bind_phone": "",
					"is_ad_fake": false,
					"show_image_bubble": false,
					"reflow_page_gid": 0,
					"favoriting_count": 0,
					"verification_type": 1,
					"can_set_geofencing": null,
					"room_id": 0,
					"account_region": "",
					"cha_list": null,
					"enterprise_verify_reason": "",
					"apple_account": 0,
					"twitter_name": "",
					"white_cover_url": null,
					"uid": "6564062791182581765",
					"custom_verify": "Verified account",
					"commerce_user_level": 0,
					"with_fusion_shop_entry": false,
					"qa_status": 0,
					"search_highlight": null,
					"events": null,
					"special_lock": 1,
					"prevent_download": false,
					"youtube_channel_id": "UCZisidnwN6MnaXPWEPYd1vw",
					"create_time": 0,
					"following_count": 0,
					"shield_follow_notice": 0,
					"tw_expire_time": 0,
					"user_rate": 1,
					"comment_setting": 0,
					"avatar_thumb": {
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.webp?x-expires=1629180000&x-signature=T%2FbklGGnBRDXBK5QIkJe0v%2Fo%2BGI%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.jpeg?x-expires=1629180000&x-signature=XO0fuGQTQW0ohAuM%2FD0kTexR4%2FU%3D"
						]
					},
					"secret": 0,
					"live_commerce": false,
					"total_favorited": 0,
					"has_facebook_token": false,
					"user_period": 0,
					"signature": "Naturally Pink-Haired Musician\nCEO of Replying\nLIVEs for Charity\n⬇️MUSIC⬇️",
					"birthday": "1900-01-01",
					"is_block": false,
					"video_icon": {
						"width": 720,
						"height": 720,
						"uri": "",
						"url_list": []
					},
					"item_list": null,
					"type_label": null,
					"aweme_count": 0,
					"youtube_expire_time": 0,
					"reflow_page_uid": 0,
					"bold_fields": null,
					"youtube_channel_title": "Jack Be",
					"twitter_id": "",
					"follower_status": 0,
					"download_setting": 0,
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
					"geofencing": [],
					"ins_id": "jackbethatsme",
					"user_canceled": false,
					"avatar_uri": "musically-maliva-obj\/1661181402174469",
					"short_id": "0",
					"has_orders": false,
					"is_phone_binded": false,
					"verify_info": "",
					"duet_setting": 0,
					"has_youtube_token": false,
					"user_tags": null,
					"unique_id_modify_time": 1629096985,
					"gender": 0,
					"with_commerce_entry": false,
					"share_qrcode_uri": "",
					"cv_level": "",
					"user_mode": 1,
					"hide_search": false,
					"share_info": {
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
						"share_url": "",
						"share_weibo_desc": "",
						"share_desc": ""
					},
					"status": 1,
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.webp?x-expires=1629180000&x-signature=fl4foczauisfE1zA6gKUGrkZkB8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.jpeg?x-expires=1629180000&x-signature=mHqrUo%2FM8XRLH%2F0ce1oa8u%2FYeiU%3D"
						],
						"width": 720,
						"height": 720
					},
					"homepage_bottom_toast": null,
					"avatar_larger": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.webp?x-expires=1629180000&x-signature=M%2FItDEuKJ1H%2BQ6sxHOlrXpRDpCU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Dfb9r81SNemGtYzpJ2lzq8wyvpE%3D"
						],
						"width": 720,
						"height": 720
					},
					"avatar_medium": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.webp?x-expires=1629180000&x-signature=wyJENE10PHT3nM4ndyJwAxgVmEU%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.jpeg?x-expires=1629180000&x-signature=Bq2yFMLaFZJCZzXHySDjUjUW8wA%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/1661181402174469"
					},
					"language": "en",
					"comment_filter_status": 0,
					"relative_users": null,
					"need_points": null,
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_300x300.webp?x-expires=1629180000&x-signature=3oGOX7yb%2FU0Nj6HIyp%2FkWHMa6t0%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_300x300.jpeg?x-expires=1629180000&x-signature=W2RYO6Fg1xhltqPV3HVfCOF3BtU%3D"
						],
						"width": 720,
						"height": 720
					},
					"need_recommend": 0,
					"has_twitter_token": false,
					"google_account": "",
					"live_agreement_time": 0,
					"download_prompt_ts": 0,
					"is_star": false,
					"fb_expire_time": 0,
					"with_shop_entry": false,
					"has_email": false,
					"follower_count": 0,
					"shield_comment_notice": 0,
					"region": "US",
					"is_discipline_member": false,
					"ad_cover_url": null,
					"sec_uid": "MS4wLjABAAAAFXqk79mhB3jUiOV3CO30x1md6T44bx0CHdWUUs9Nb9BpaAnVFKFfzzJW4n-dEV-e",
					"accept_private_policy": false,
					"live_verify": 0,
					"authority_status": 0,
					"mutual_relation_avatars": null,
					"stitch_setting": 0
				},
				"video_labels": [],
				"group_id": "6971857887962418437",
				"challenge_position": null,
				"create_time": 1623262162,
				"risk_infos": {
					"warn": false,
					"risk_sink": false,
					"type": 0,
					"content": "",
					"vote": false
				},
				"commerce_info": {
					"with_comment_filter_words": false,
					"adv_promotable": false,
					"auction_ad_invited": false
				},
				"is_top": 0,
				"author_user_id": 6564062791182581765,
				"long_video": null,
				"item_duet": 0,
				"need_vs_entry": false,
				"desc": "Reply to @roxymendoza484 Why did I put my fans on a billboard? Well…",
				"statistics": {
					"play_count": 1543037,
					"share_count": 569,
					"forward_count": 0,
					"lose_count": 0,
					"lose_comment_count": 0,
					"comment_count": 81362,
					"download_count": 131,
					"whatsapp_share_count": 13,
					"aweme_id": "6971857887962418437",
					"digg_count": 129587
				},
				"status": {
					"download_status": 0,
					"allow_share": true,
					"with_goods": false,
					"in_reviewing": false,
					"reviewed": 1,
					"self_see": false,
					"is_prohibited": false,
					"aweme_id": "6971857887962418437",
					"is_delete": false,
					"allow_comment": true,
					"is_private": false,
					"private_status": 0,
					"review_result": {
						"review_status": 0
					}
				},
				"is_story": 0,
				"stickers": "454747",
				"search_highlight": null,
				"playlist_blocked": false,
				"item_stitch": 0,
				"share_url": "https:\/\/m.tiktok.com\/v\/6971857887962418437.html?u_code=dk4e43gkjcg74h&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6971857887962418437&source=h5_m",
				"image_infos": null,
				"sort_label": "",
				"green_screen_materials": null,
				"is_relieve": false,
				"uniqid_position": null,
				"geofencing_regions": null,
				"item_comment_settings": 0,
				"desc_language": "en",
				"position": null,
				"video_text": [],
				"prevent_download": false,
				"has_vs_entry": false,
				"mask_infos": [],
				"need_trim_step": false,
				"rate": 12,
				"distance": "",
				"video_control": {
					"share_type": 1,
					"allow_dynamic_wallpaper": true,
					"allow_music": true,
					"timer_status": 1,
					"allow_stitch": true,
					"allow_download": true,
					"show_progress_bar": 0,
					"draft_progress_bar": 0,
					"allow_duet": true,
					"allow_react": true,
					"prevent_download_type": 0
				},
				"video_reply_info": {
					"aweme_id": 6970369828687219974,
					"comment_id": 6970377870577517317,
					"alias_comment_id": 6971856442202817286
				},
				"cover_labels": null,
				"aweme_type": 0,
				"geofencing": [],
				"is_hash_tag": 1,
				"interaction_stickers": [
					{
						"track_info": "[{\"x\":0.3387,\"end_time\":12166.6667,\"p\":null,\"y\":0.183,\"h\":0.0847,\"isRatioCoord\":false,\"start_time\":0,\"r\":0,\"w\":0.5943,\"s\":1}]",
						"attr": "",
						"type": 4,
						"index": 6
					}
				],
				"user_digged": 0,
				"label_top": {
					"width": 720,
					"height": 720,
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					]
				},
				"nickname_position": null,
				"hybrid_label": null,
				"is_pgcshow": false,
				"origin_comment_ids": null,
				"is_preview": 0
			}
		],
		"cursor": 56
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
