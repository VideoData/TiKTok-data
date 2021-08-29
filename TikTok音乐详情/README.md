#  TikTok音乐详情

# 联系方式：[点击主页查看](https://github.com/VideoData) 

#  请求Api：
```java
http://主机地址/tk/music/detail?token=xxx&music_id=6767362751674189825
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| music_id     | int     | 音乐id     |  


#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"similar_music_ids": null,
		"extra": {
			"now": 1629096867000,
			"fatal_item_ids": [],
			"logid": "202108160654270102451621295001CBDF"
		},
		"log_pb": {
			"impr_id": "202108160654270102451621295001CBDF"
		},
		"status_code": 0,
		"msg": "success",
		"music_info": {
			"share_info": {
				"share_desc": "Check out this song! Beauty Hurts #TikTok",
				"share_title": "Amazing! I just found a bunch of funny videos! #TikTok > Beauty Hurts",
				"bool_persist": 0,
				"share_title_myself": "",
				"share_signature_url": "",
				"share_quote": "",
				"share_url": "https:\/\/m.tiktok.com\/h5\/share\/music\/6767362751674189825.html?language=en&source=h5_m&u_code=dk4e43gkjcg74h&_d=dk4e43gkjcg74h&share_music_id=6767362751674189825",
				"share_weibo_desc": "Users all over the world are having fun making their own versions of the song Beauty Hurts on TikTok! Tap here >>",
				"share_desc_info": "Users all over the world are having fun making their own versions of the song Beauty Hurts on TikTok! Tap here >>",
				"share_title_other": "",
				"share_signature_desc": ""
			},
			"is_del_video": false,
			"cover_large": {
				"width": 720,
				"height": 720,
				"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
				"url_list": [
					"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
				]
			},
			"schema_url": "",
			"is_author_artist": true,
			"extra": "{\"beats\":{},\"schedule_search_time\":0,\"aed_music_dur\":25.23,\"is_ugc_mapping\":false,\"apple_song_id\":1469922665,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0}",
			"avatar_thumb": {
				"uri": "musically-maliva-obj\/1661181402174469",
				"url_list": [
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.webp?x-expires=1629180000&x-signature=T%2FbklGGnBRDXBK5QIkJe0v%2Fo%2BGI%3D",
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_100x100.jpeg?x-expires=1629180000&x-signature=XO0fuGQTQW0ohAuM%2FD0kTexR4%2FU%3D"
				],
				"width": 720,
				"height": 720
			},
			"tag_list": null,
			"binded_challenge_id": 0,
			"is_video_self_see": false,
			"strong_beat_url": {
				"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144",
				"url_list": [
					"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/b1b83db117de414aaca7b20ade251144"
				],
				"width": 720,
				"height": 720
			},
			"duration": 30,
			"user_count": 481284,
			"title": "Beauty Hurts",
			"is_audio_url_with_cookie": false,
			"search_highlight": null,
			"redirect": false,
			"author_position": null,
			"prevent_download": false,
			"is_commerce_music": false,
			"matched_song": {
				"id": "6767936495710898178",
				"author": "Jack Be",
				"title": "Beauty Hurts",
				"h5_url": "",
				"cover_medium": {
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
					],
					"width": 720,
					"height": 720,
					"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c"
				}
			},
			"album": "The Great Alone",
			"cover_medium": {
				"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
				"url_list": [
					"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
				],
				"width": 720,
				"height": 720
			},
			"status": 1,
			"preview_end_time": 0,
			"source_platform": 10033,
			"mid": "6767362751674189825",
			"external_song_info": [],
			"shoot_duration": 30,
			"reason_type": 0,
			"lyric_short_position": null,
			"video_duration": 60,
			"author_deleted": false,
			"avatar_large": {
				"width": 720,
				"height": 720,
				"uri": "musically-maliva-obj\/1661181402174469",
				"url_list": [
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.webp?x-expires=1629180000&x-signature=M%2FItDEuKJ1H%2BQ6sxHOlrXpRDpCU%3D",
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Dfb9r81SNemGtYzpJ2lzq8wyvpE%3D"
				]
			},
			"is_original_sound": false,
			"dmv_auto_show": false,
			"end_time": 0,
			"offline_desc": "",
			"mute_share": false,
			"id": 6767362751674189825,
			"is_original": false,
			"play_url": {
				"url_list": [
					"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157"
				],
				"width": 720,
				"height": 720,
				"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/0e9d897a8e7b4b00969a7de27f99b157"
			},
			"owner_nickname": "",
			"is_restricted": false,
			"avatar_medium": {
				"uri": "musically-maliva-obj\/1661181402174469",
				"url_list": [
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.webp?x-expires=1629180000&x-signature=wyJENE10PHT3nM4ndyJwAxgVmEU%3D",
					"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_720x720.jpeg?x-expires=1629180000&x-signature=Bq2yFMLaFZJCZzXHySDjUjUW8wA%3D"
				],
				"width": 720,
				"height": 720
			},
			"is_matched_metadata": false,
			"id_str": "6767362751674189825",
			"author": "Jack Be",
			"cover_hd": {
				"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
				"url_list": [
					"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
				],
				"width": 720,
				"height": 720
			},
			"start_time": 0,
			"preview_start_time": 15,
			"artists": [
				{
					"sec_uid": "MS4wLjABAAAAFXqk79mhB3jUiOV3CO30x1md6T44bx0CHdWUUs9Nb9BpaAnVFKFfzzJW4n-dEV-e",
					"nick_name": "JACK BE",
					"handle": "jackbethatsme",
					"avatar": {
						"uri": "musically-maliva-obj\/1661181402174469",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.webp?x-expires=1629180000&x-signature=fl4foczauisfE1zA6gKUGrkZkB8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1661181402174469~c5_168x168.jpeg?x-expires=1629180000&x-signature=mHqrUo%2FM8XRLH%2F0ce1oa8u%2FYeiU%3D"
						]
					},
					"is_verified": true,
					"enter_type": 2,
					"uid": "6564062791182581765"
				}
			],
			"owner_handle": "",
			"prevent_item_download_status": 0,
			"audition_duration": 30,
			"is_pgc": true,
			"cover_thumb": {
				"uri": "tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c",
				"url_list": [
					"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/c2be521aacf244cab643f8fbaaafdb0c.jpeg"
				],
				"width": 720,
				"height": 720
			},
			"position": null,
			"collect_stat": 0
		},
		"rec_list": [],
		"similar_music": []
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
