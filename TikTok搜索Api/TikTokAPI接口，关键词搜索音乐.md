
# TikTokAPI接口，关键词搜索音乐



**请求API：**
```http
http://主机地址/tk/search/music?token=xxx&keyword=beauty
```




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
		"music": [
			{
				"id": 263022615492288513,
				"id_str": "263022615492288513",
				"title": "What's On Your Face?",
				"author": "Beauty",
				"album": "comedy-170818-2",
				"cover_hd": {
					"uri": "tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_large": {
					"uri": "tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_medium": {
					"uri": "tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_thumb": {
					"uri": "tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"play_url": {
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/f4f842979f8e4a32a0f29060895b89a3",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/f4f842979f8e4a32a0f29060895b89a3"
					],
					"width": 720,
					"height": 720
				},
				"schema_url": "",
				"source_platform": 74,
				"start_time": 0,
				"end_time": 0,
				"duration": 8,
				"extra": "{\"has_edited\":0,\"reviewed\":0,\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0,\"is_ugc_mapping\":false}",
				"user_count": 263441,
				"position": null,
				"collect_stat": 0,
				"status": 1,
				"offline_desc": "",
				"owner_nickname": "",
				"is_original": false,
				"mid": "263022615492288513",
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
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/48c696e02aed41f1a9b35b770a1c7386",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/48c696e02aed41f1a9b35b770a1c7386"
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
				"audition_duration": 8,
				"shoot_duration": 8,
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
					"id": "6750888637291841538",
					"author": "Beauty",
					"title": "What's On Your Face?",
					"h5_url": "",
					"cover_medium": {
						"uri": "tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/b8775f803fa04e6fa00b2fbb981a7d8b.jpeg"
						],
						"width": 720,
						"height": 720
					}
				},
				"video_duration": 6000,
				"search_music_name": "What's On Your Face?",
				"search_music_desc": "Beauty",
				"search_highlight": null
			},
			{
				"id": 6767362751674189825,
				"id_str": "6767362751674189825",
				"title": "Beauty Hurts",
				"author": "Jack Be",
				"album": "The Great Alone",
				"cover_hd": {
					"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_large": {
					"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_medium": {
					"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_thumb": {
					"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
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
				"schema_url": "",
				"source_platform": 10033,
				"start_time": 0,
				"end_time": 0,
				"duration": 30,
				"extra": "{\"aed_music_dur\":25.23,\"is_ugc_mapping\":false,\"apple_song_id\":1469922665,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0}",
				"user_count": 480994,
				"position": null,
				"collect_stat": 0,
				"status": 1,
				"offline_desc": "",
				"owner_nickname": "",
				"is_original": false,
				"mid": "6767362751674189825",
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
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144"
					],
					"width": 720,
					"height": 720
				},
				"unshelve_countries": null,
				"prevent_item_download_status": 0,
				"external_song_info": [],
				"avatar_thumb": {
					"uri": "musically-maliva-obj\/1661181402174469",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.webp?x-expires=1628845200&x-signature=o5IYYPTs4zZ1d6NtQipdbEV%2BxHA%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.jpeg?x-expires=1628845200&x-signature=Hz6L7edIfv%2BY0q9tXRd1o1Gi1BA%3D"
					],
					"width": 720,
					"height": 720
				},
				"avatar_medium": {
					"uri": "musically-maliva-obj\/1661181402174469",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.webp?x-expires=1628845200&x-signature=2eSdr2EfXBYFLoIqbfdGAO3QW8o%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.jpeg?x-expires=1628845200&x-signature=ij5Xm%2F4x4PYqp1WFMCv%2BaTe8sNY%3D"
					],
					"width": 720,
					"height": 720
				},
				"avatar_large": {
					"uri": "musically-maliva-obj\/1661181402174469",
					"url_list": [
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.webp?x-expires=1628845200&x-signature=OkbjAwBCSt5uAsNwVCXqXpPwTH8%3D",
						"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.jpeg?x-expires=1628845200&x-signature=FUn9oIAbr4YLDzIdrsIr%2B0tOD6A%3D"
					],
					"width": 720,
					"height": 720
				},
				"preview_start_time": 15,
				"preview_end_time": 0,
				"is_commerce_music": false,
				"is_original_sound": false,
				"audition_duration": 30,
				"shoot_duration": 30,
				"reason_type": 0,
				"artists": [
					{
						"uid": "6564062791182581765",
						"sec_uid": "MS4wLjABAAAAFXqk79mhB3jUiOV3CO30x1md6T44bx0CHdWUUs9Nb9BpaAnVFKFfzzJW4n-dEV-e",
						"nick_name": "JACK BE",
						"handle": "jackbethatsme",
						"avatar": {
							"uri": "musically-maliva-obj\/1661181402174469",
							"url_list": [
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.webp?x-expires=1628845200&x-signature=vacm9nYdcKhUfBmp9BvGeRkdsmE%3D",
								"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.jpeg?x-expires=1628845200&x-signature=RIJS026ZZCh1Q0EYdbtCSymINfA%3D"
							]
						},
						"is_verified": true,
						"enter_type": 2
					}
				],
				"lyric_short_position": null,
				"mute_share": false,
				"tag_list": [
					{
						"tag_title": "Popular",
						"tag_title_color": "#FF3B5C",
						"tag_color": "#FFF2F5",
						"tag_title_dark_color": "#FF3B5C",
						"tag_dark_color": "#621B29"
					}
				],
				"dmv_auto_show": false,
				"is_author_artist": true,
				"is_pgc": true,
				"is_matched_metadata": false,
				"is_audio_url_with_cookie": false,
				"matched_song": {
					"id": "6767936495710898178",
					"author": "Jack Be",
					"title": "Beauty Hurts",
					"h5_url": "",
					"cover_medium": {
						"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
						],
						"width": 720,
						"height": 720
					}
				},
				"video_duration": 60,
				"search_music_name": "Beauty Hurts",
				"search_music_desc": "Jack Be",
				"search_highlight": null
			},
			{
				"id": 6876664680262158338,
				"id_str": "6876664680262158338",
				"title": "Grown Up",
				"author": "Beauty",
				"album": "Grown Up",
				"cover_hd": {
					"uri": "tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_large": {
					"uri": "tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_medium": {
					"uri": "tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_thumb": {
					"uri": "tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"play_url": {
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/61ef0ab1024442aa9561b8f4ec71f53d",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/61ef0ab1024442aa9561b8f4ec71f53d"
					],
					"width": 720,
					"height": 720
				},
				"schema_url": "",
				"source_platform": 10033,
				"start_time": 0,
				"end_time": 0,
				"duration": 60,
				"extra": "{\"review_unshelve_reason\":0,\"beats\":{},\"schedule_search_time\":0,\"aed_music_dur\":50.49,\"is_ugc_mapping\":false,\"apple_song_id\":1319661867,\"has_edited\":0,\"reviewed\":0}",
				"user_count": 1076,
				"position": null,
				"collect_stat": 0,
				"status": 1,
				"offline_desc": "",
				"owner_nickname": "",
				"is_original": false,
				"mid": "6876664680262158338",
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
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/cdae1723af6946e4b716ef344fed17bf",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/cdae1723af6946e4b716ef344fed17bf"
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
					"id": "6876664678437619714",
					"author": "Beauty",
					"title": "Grown Up",
					"h5_url": "",
					"cover_medium": {
						"uri": "tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/078dc89ad9f249a091b83c1e6d79db08.jpeg"
						],
						"width": 720,
						"height": 720
					}
				},
				"video_duration": 60,
				"search_music_name": "Grown Up",
				"search_music_desc": "Beauty",
				"search_highlight": null
			},
			{
				"id": 243229923124133888,
				"id_str": "243229923124133888",
				"title": "Beauty",
				"author": "Charlie Mariano & Gregor Huebner & Richie Beirach & Veit Huebner",
				"album": "Beauty",
				"cover_hd": {
					"uri": "tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_large": {
					"uri": "tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_medium": {
					"uri": "tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"cover_thumb": {
					"uri": "tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1.jpeg"
					],
					"width": 720,
					"height": 720
				},
				"play_url": {
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/a2de4e75a21549f3bc5f8a17ad418a48",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/a2de4e75a21549f3bc5f8a17ad418a48"
					],
					"width": 720,
					"height": 720
				},
				"schema_url": "",
				"source_platform": 71,
				"start_time": 0,
				"end_time": 0,
				"duration": 30,
				"extra": "{\"schedule_search_time\":0,\"is_ugc_mapping\":false,\"apple_song_id\":341850360,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{}}",
				"user_count": 933,
				"position": null,
				"collect_stat": 0,
				"status": 1,
				"offline_desc": "",
				"owner_nickname": "",
				"is_original": false,
				"mid": "243229923124133888",
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
					"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/953bb94a9c51424b81bb3ddba36a2698",
					"url_list": [
						"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/953bb94a9c51424b81bb3ddba36a2698"
					],
					"width": 720,
					"height": 720
				},
				"unshelve_countries": null,
				"prevent_item_download_status": 0,
				"external_song_info": [],
				"preview_start_time": 90.1,
				"preview_end_time": 0,
				"is_commerce_music": false,
				"is_original_sound": false,
				"audition_duration": 30,
				"shoot_duration": 30,
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
					"id": "6723135662456834049",
					"author": "Charlie Mariano & Gregor Huebner & Richie Beirach & Veit Huebner",
					"title": "Beauty",
					"h5_url": "",
					"cover_medium": {
						"uri": "tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/134d0a108f5a413fa6a8be4a10f7b2c1.jpeg"
						],
						"width": 720,
						"height": 720
					}
				},
				"video_duration": 60,
				"search_music_name": "Beauty",
				"search_music_desc": "Charlie Mariano & Gregor Huebner & Richie Beirach & Veit Huebner",
				"search_highlight": null
			}
		],
		"has_more": 1,
		"cursor": 20,
		"qc": "",
		"ad_info": [],
		"music_info_list": [],
		"extra": {
			"now": 1628759897000,
			"logid": "202108120918160102450772500F216C65",
			"fatal_item_ids": [],
			"search_request_id": ""
		},
		"log_pb": {
			"impr_id": "202108120918160102450772500F216C65"
		},
		"global_doodle_config": {
			"display_filter_bar": 0,
			"keyword": "beauty",
			"search_channel": "musically_music",
			"new_source": ""
		}
	}
}
```
