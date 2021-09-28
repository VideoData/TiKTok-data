

# TikTok Api：用户视频列表




### 请求Api


```http
http://主机地址/tk/user/videos?token=xxx&uid=6889508286968038405
```


### 请求方式


```http
GET
```



### 参数
**​**


| 参数名 | 必选 | 类型 | 说明 |
| --- | --- | --- | --- |
| token | 是 | string | 接口授权码 |
| uid | 是 | int | 用户uid，[点击查看获取方法](https://www.yuque.com/books/share/d37ad7e7-95b0-4535-ad74-2cb5f639e99f/opsoz9) |
| cursor | 否 | int | 翻页游标，根据结果返回的max_cursor传入作为下一页翻页参数，初始为0 |




### 返回示例


```json

{
	"code": 200,
	"msg": "成功",
	"data": {
		"status_code": 0,
		"min_cursor": 1627618258000,
		"max_cursor": 1611080207000,
		"has_more": 1,
		"aweme_list": [
			{
				"aweme_id": "6990567184082701573",
				"desc": "Summer in bora bora #borabora #frenchpolynesia #Summer #girl #model #modelface #summervibes #travel #swim #nature #vacation #vibes",
				"create_time": 1627618258,
				"author": {
					"uid": "6889508286968038405",
					"short_id": "0",
					"nickname": "Anastasiya Chorna421",
					"signature": "Ukrainian living in LA\nInstagram: anastazia_a",
					"follow_status": 0,
					"is_block": false,
					"custom_verify": "",
					"unique_id": "anastasiyachorna3",
					"room_id": 0,
					"authority_status": 0,
					"verify_info": "",
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
					"original_musician": {
						"music_count": 0,
						"music_used_count": 0,
						"digg_count": 0
					},
					"enterprise_verify_reason": "",
					"is_ad_fake": false,
					"followers_detail": null,
					"region": "US",
					"commerce_user_level": 0,
					"is_discipline_member": false,
					"secret": 0,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"follower_status": 0,
					"language": "en",
					"is_star": false,
					"ad_cover_url": null,
					"relative_users": null,
					"cha_list": null,
					"sec_uid": "MS4wLjABAAAAOHufjkHYbBubBEklfzAEFmf2IBzaShuPxcQE-PTek2e6sEZhMoZYp2gZt7f5Gx1D",
					"prevent_download": false,
					"comment_setting": 0,
					"duet_setting": 3,
					"download_setting": 0,
					"comment_filter_status": 0,
					"stitch_setting": 0,
					"qa_status": 0
				},
				"music": {
					"id": 6948086714175621121,
					"id_str": "6948086714175621121",
					"title": "Kiss Me More (feat. SZA)",
					"author": "Doja Cat",
					"album": "Kiss Me More (feat. SZA)",
					"cover_hd": {
						"uri": "tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab~c5_1080x1080.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_large": {
						"uri": "tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab~c5_720x720.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_medium": {
						"uri": "tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab~c5_200x200.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"cover_thumb": {
						"uri": "tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab",
						"url_list": [
							"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab~c5_100x100.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-ve-2774\/f1f6bf6824524697b2dc98413034a263",
						"url_list": [
							"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-ve-2774\/f1f6bf6824524697b2dc98413034a263"
						],
						"width": 720,
						"height": 720
					},
					"schema_url": "",
					"source_platform": 10033,
					"start_time": 0,
					"end_time": 0,
					"duration": 30,
					"extra": "{\"aed_music_dur\":30.01,\"is_ugc_mapping\":false,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{\"energy_trace\":\"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/4c3f4f0c3e2b4f23b5cec5c06e46fa1d\",\"merged_beats\":\"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/dfc1597f36dd4f89adcf684b51d2f855\",\"audio_effect_onset\":\"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/4b35203787ea4abd865450b10b961f8a\",\"beats_tracker\":\"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/tos-useast2a-v-2774\/24b15d84a262466cb7bd616f77bda019\"},\"schedule_search_time\":0}",
					"user_count": 0,
					"position": null,
					"collect_stat": 0,
					"status": 1,
					"offline_desc": "",
					"owner_nickname": "",
					"is_original": false,
					"mid": "6948086714175621121",
					"binded_challenge_id": 0,
					"redirect": false,
					"is_restricted": false,
					"author_deleted": false,
					"is_del_video": false,
					"is_video_self_see": false,
					"owner_handle": "",
					"author_position": null,
					"prevent_download": false,
					"prevent_item_download_status": 0,
					"external_song_info": [],
					"preview_start_time": 48,
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
					"is_author_artist": true,
					"is_pgc": true,
					"is_matched_metadata": false,
					"is_audio_url_with_cookie": false,
					"matched_song": {
						"id": "6948086711708551169",
						"author": "Doja Cat",
						"title": "Kiss Me More (feat. SZA)",
						"h5_url": "",
						"cover_medium": {
							"uri": "tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab",
							"url_list": [
								"https:\/\/p16-amd-va.tiktokcdn.com\/img\/tos-useast2a-v-2774\/c4426113bbf84627a6f3df8b291110ab~c5_200x200.jpeg"
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
						"cid": "4366790",
						"cha_name": "borabora",
						"desc": "",
						"schema": "aweme:\/\/aweme\/challenge\/detail?cid=4366790",
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
							"share_url": "https:\/\/t.tiktok.com\/i18n\/share\/challenge\/4366790?name=borabora&u_code=0&language=en&_d=dkaelj00i9i32i&share_challenge_id=4366790&source=h5_t",
							"share_weibo_desc": "Check out #borabora on TikTok!",
							"share_desc": "Check out #borabora on TikTok!",
							"share_title": "It is a becoming a big trend on TikTok now! Click here: borabora",
							"bool_persist": 0,
							"share_title_myself": "",
							"share_title_other": "",
							"share_signature_url": "",
							"share_signature_desc": "",
							"share_quote": "",
							"share_desc_info": "Check out #borabora on TikTok!"
						},
						"connect_music": [],
						"type": 1,
						"sub_type": 0,
						"is_pgcshow": false,
						"collect_stat": 0,
						"is_challenge": 0,
						"view_count": 0,
						"is_commerce": false,
						"hashtag_profile": "",
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
						"uri": "v09044g40000c41nlvrc77u591t79ad0",
						"url_list": [
							"https:\/\/v16m.tiktokcdn.com\/5e7701848d055346b2181914d9d4d7d0\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/0ab9b89edad04559bd751cd15c8c7524\/?a=1233&br=3726&bt=1863&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNzw8O2lnPDs0N2hoODtoZ2dhNnE2cjRvaS5gLS1kMTZzczNiLjRhYmE2My8vXmBgYTA6Yw%3D%3D&vl=&vr=",
							"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/0ab9b89edad04559bd751cd15c8c7524\/?VExpiration=1630055133&VSignature=Uh0mzyXeHWxMiCNeMnsJlQ&a=1233&br=3726&bt=1863&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNzw8O2lnPDs0N2hoODtoZ2dhNnE2cjRvaS5gLS1kMTZzczNiLjRhYmE2My8vXmBgYTA6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&is_play_url=1&source=PackSourceEnum_PUBLISH&file_id=d3ed8c5ceae24216899ddefd87919e46"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044g40000c41nlvrc77u591t79ad0_h264_540p_1908478",
						"data_size": 1378637,
						"file_hash": "1f92e55973725239933c9d641c4d5b08",
						"file_cs": "c:0-5878-3584"
					},
					"cover": {
						"uri": "tos-maliva-p-0068\/49b3e289c2b648dd91c4312d66f216ca",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/49b3e289c2b648dd91c4312d66f216ca~c5_300x400.jpeg?x-expires=1630054800&x-signature=RgNDzu8nUgFq8ZQ7bRt352zIXVA%3D"
						],
						"width": 720,
						"height": 720
					},
					"height": 1024,
					"width": 576,
					"dynamic_cover": {
						"uri": "tos-maliva-p-0068\/902dccdcdd594989b3193b269b25073e_1627618260",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/902dccdcdd594989b3193b269b25073e_1627618260?x-expires=1630054800&x-signature=NgaU17PhpLkjCFksL3mJnY5G5SI%3D"
						],
						"width": 720,
						"height": 720
					},
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/aeddcf8ae6074c81adb0e9c6fced89cd_1627618260",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/aeddcf8ae6074c81adb0e9c6fced89cd_1627618260~tplv-tiktokx-360p.webp?x-expires=1630054800&x-signature=xkAuXb2wmqcaS1fOJ6HaXcFTJR0%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/aeddcf8ae6074c81adb0e9c6fced89cd_1627618260~tplv-tiktokx-360p.jpeg?x-expires=1630054800&x-signature=B7gpDNj9%2BQhHwW%2FfTU97Fjbzlz0%3D"
						],
						"width": 720,
						"height": 720
					},
					"ratio": "540p",
					"download_addr": {
						"uri": "v09044g40000c41nlvrc77u591t79ad0",
						"url_list": [
							"https:\/\/v16m.tiktokcdn.com\/a43790967bb7d95eb002811b65fd2eae\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=",
							"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?VExpiration=1630055133&VSignature=klPYYdnn9N2wYqctALpWJQ&a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=11&source=PUBLISH"
						],
						"width": 720,
						"height": 720,
						"data_size": 1564854
					},
					"has_watermark": true,
					"duration": 5779,
					"download_suffix_logo_addr": {
						"uri": "v09044g40000c41nlvrc77u591t79ad0",
						"url_list": [
							"https:\/\/v16m.tiktokcdn.com\/a43790967bb7d95eb002811b65fd2eae\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=",
							"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?VExpiration=1630055133&VSignature=klPYYdnn9N2wYqctALpWJQ&a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=11&source=PUBLISH"
						],
						"width": 720,
						"height": 720,
						"data_size": 1564854
					},
					"has_download_suffix_logo_addr": true,
					"play_addr_265": {
						"uri": "v09044g40000c41nlvrc77u591t79ad0",
						"url_list": [
							"https:\/\/v16m.tiktokcdn.com\/88bfd77a2b98e3e24feb001f9b904c67\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/59fe3b46798e4802adb6c5141c641e29\/?a=1233&br=2074&bt=1037&cd=0%7C0%7C0&ch=0&cr=3&cs=2&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=11&rc=M2Q6NDg6ZnlxNzMzNzczM0ApZmk8NDdkaDs1N2lmODNmNmdhNnE2cjRvaS5gLS1kMTZzc2MtMjM2Ni8yYTU0M2JgYmM6Yw%3D%3D&vl=&vr=",
							"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/59fe3b46798e4802adb6c5141c641e29\/?VExpiration=1630055133&VSignature=2Ib2ZNhFW7spc_IOOnpqbQ&a=1233&br=2074&bt=1037&cd=0%7C0%7C0&ch=0&cr=3&cs=2&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=11&rc=M2Q6NDg6ZnlxNzMzNzczM0ApZmk8NDdkaDs1N2lmODNmNmdhNnE2cjRvaS5gLS1kMTZzc2MtMjM2Ni8yYTU0M2JgYmM6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&is_play_url=1&source=PackSourceEnum_PUBLISH&file_id=3fce0c5ec6f7482d85e2a9491695f0cf"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044g40000c41nlvrc77u591t79ad0_bytevc1_540p_1062672",
						"data_size": 767648,
						"file_hash": "32f1b9c6128336af3ad0f5fdcc1de952",
						"file_cs": "c:0-6108-0dd4"
					},
					"is_h265": 0,
					"play_addr_h264": {
						"uri": "v09044g40000c41nlvrc77u591t79ad0",
						"url_list": [
							"https:\/\/v16m.tiktokcdn.com\/5e7701848d055346b2181914d9d4d7d0\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/0ab9b89edad04559bd751cd15c8c7524\/?a=1233&br=3726&bt=1863&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNzw8O2lnPDs0N2hoODtoZ2dhNnE2cjRvaS5gLS1kMTZzczNiLjRhYmE2My8vXmBgYTA6Yw%3D%3D&vl=&vr=",
							"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/0ab9b89edad04559bd751cd15c8c7524\/?VExpiration=1630055133&VSignature=Uh0mzyXeHWxMiCNeMnsJlQ&a=1233&br=3726&bt=1863&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=6&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNzw8O2lnPDs0N2hoODtoZ2dhNnE2cjRvaS5gLS1kMTZzczNiLjRhYmE2My8vXmBgYTA6Yw%3D%3D&vl=&vr=",
							"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&is_play_url=1&source=PackSourceEnum_PUBLISH&file_id=d3ed8c5ceae24216899ddefd87919e46"
						],
						"width": 720,
						"height": 720,
						"url_key": "v09044g40000c41nlvrc77u591t79ad0_h264_540p_1908478",
						"data_size": 1378637,
						"file_hash": "1f92e55973725239933c9d641c4d5b08",
						"file_cs": "c:0-5878-3584"
					},
					"cdn_url_expired": 0,
					"animated_cover": {
						"uri": "tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260?x-expires=1630054800&x-signature=7mAqM%2BLN8JbvErKxt3sFiqGIIAQ%3D"
						]
					},
					"need_set_token": false,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044g40000c41nlvrc77u591t79ad0\",\"url_list\":[\"https:\/\/v16m.tiktokcdn.com\/a43790967bb7d95eb002811b65fd2eae\/6128aadd\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=\",\"https:\/\/v58.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/a0322fe402f24601a82b18368513dcaa\/?VExpiration=1630055133&VSignature=klPYYdnn9N2wYqctALpWJQ&a=1233&br=2524&bt=1262&cd=0%7C0%7C0&ch=0&cr=3&cs=0&cv=1&dr=0&ds=3&er=&ft=Umo5i_MKaDp-Inz&l=20210827030528010189074225112233E2&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M2Q6NDg6ZnlxNzMzNzczM0ApNmVoZWY7NjxkNzg0Njo1OWdhNnE2cjRvaS5gLS1kMTZzczZgMmJeNDMwLmI1MjEtXzU6Yw%3D%3D&vl=&vr=\",\"https:\/\/api16-normal-c-useast1a.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c41nlvrc77u591t79ad0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=11&source=PUBLISH\"],\"width\":720,\"height\":720,\"data_size\":1564854}}",
					"is_callback": true,
					"tags": null,
					"big_thumbs": null,
					"is_bytevc1": 0,
					"meta": "{\"loudness\":\"-7.8\",\"peak\":\"1\"}",
					"ai_dynamic_cover": {
						"uri": "tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260?x-expires=1630054800&x-signature=7mAqM%2BLN8JbvErKxt3sFiqGIIAQ%3D"
						]
					},
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/c82eb648da9d45a5ba55e087dce0ed58_1627618260?x-expires=1630054800&x-signature=7mAqM%2BLN8JbvErKxt3sFiqGIIAQ%3D"
						]
					}
				},
				"share_url": "https:\/\/t.tiktok.com\/i18n\/share\/video\/6990567184082701573\/?region=KR&mid=6948086714175621121&u_code=0&preview_pb=0&language=en&_d=dkaelj00i9i32i&share_item_id=6990567184082701573&source=h5_t",
				"user_digged": 0,
				"statistics": {
					"aweme_id": "6990567184082701573",
					"comment_count": 11,
					"digg_count": 453,
					"download_count": 11,
					"play_count": 5040,
					"share_count": 3,
					"forward_count": 0,
					"lose_count": 0,
					"lose_comment_count": 0,
					"whatsapp_share_count": 0
				},
				"status": {
					"aweme_id": "6990567184082701573",
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
						"start": 20,
						"end": 29,
						"type": 1,
						"hashtag_name": "borabora",
						"hashtag_id": "4366790",
						"is_commerce": false
					},
					{
						"start": 30,
						"end": 46,
						"type": 1,
						"hashtag_name": "frenchpolynesia",
						"hashtag_id": "4366792",
						"is_commerce": false
					},
					{
						"start": 47,
						"end": 54,
						"type": 1,
						"hashtag_name": "summer",
						"hashtag_id": "4100",
						"is_commerce": false
					},
					{
						"start": 55,
						"end": 60,
						"type": 1,
						"hashtag_name": "girl",
						"hashtag_id": "5932",
						"is_commerce": false
					},
					{
						"start": 61,
						"end": 67,
						"type": 1,
						"hashtag_name": "model",
						"hashtag_id": "4361",
						"is_commerce": false
					},
					{
						"start": 68,
						"end": 78,
						"type": 1,
						"hashtag_name": "modelface",
						"hashtag_id": "371290",
						"is_commerce": false
					},
					{
						"start": 79,
						"end": 91,
						"type": 1,
						"hashtag_name": "summervibes",
						"hashtag_id": "45070",
						"is_commerce": false
					},
					{
						"start": 92,
						"end": 99,
						"type": 1,
						"hashtag_name": "travel",
						"hashtag_id": "7884",
						"is_commerce": false
					},
					{
						"start": 100,
						"end": 105,
						"type": 1,
						"hashtag_name": "swim",
						"hashtag_id": "9181",
						"is_commerce": false
					},
					{
						"start": 106,
						"end": 113,
						"type": 1,
						"hashtag_name": "nature",
						"hashtag_id": "5399",
						"is_commerce": false
					},
					{
						"start": 114,
						"end": 123,
						"type": 1,
						"hashtag_name": "vacation",
						"hashtag_id": "5608",
						"is_commerce": false
					},
					{
						"start": 124,
						"end": 130,
						"type": 1,
						"hashtag_name": "vibes",
						"hashtag_id": "10800",
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
					"share_url": "https:\/\/t.tiktok.com\/i18n\/share\/video\/6990567184082701573\/?region=KR&mid=6948086714175621121&u_code=0&preview_pb=0&language=en&_d=dkaelj00i9i32i&share_item_id=6990567184082701573&source=h5_t",
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out Anastasiya Chorna421’s video! #TikTok > ",
					"share_desc": "Check out Anastasiya Chorna421's video! #TikTok",
					"share_title": "Check out Anastasiya Chorna421’s video! #TikTok > ",
					"bool_persist": 0,
					"share_title_myself": "",
					"share_title_other": "",
					"share_link_desc": "",
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_quote": "",
					"whatsapp_desc": "Download TikTok and watch more fun videos:",
					"share_desc_info": "TikTok: Make Every Second CountCheck out Anastasiya Chorna421’s video! #TikTok > "
				},
				"distance": "",
				"video_labels": [],
				"is_vr": false,
				"duration": 5779,
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
				"author_user_id": 6889508286968038405,
				"bodydance_score": 0,
				"geofencing": [],
				"is_hash_tag": 1,
				"is_pgcshow": false,
				"region": "US",
				"video_text": [],
				"collect_stat": 0,
				"label_top_text": null,
				"group_id": "6990567184082701573",
				"prevent_download": false,
				"nickname_position": null,
				"challenge_position": null,
				"item_comment_settings": 0,
				"with_promotional_music": false,
				"long_video": null,
				"item_duet": 1,
				"item_react": 1,
				"without_watermark": false,
				"desc_language": "de",
				"interaction_stickers": null,
				"misc_info": "{}",
				"origin_comment_ids": null,
				"commerce_config_data": null,
				"distribute_type": 1,
				"video_control": {
					"allow_download": false,
					"share_type": 0,
					"show_progress_bar": 0,
					"draft_progress_bar": 0,
					"allow_duet": true,
					"allow_react": true,
					"prevent_download_type": 2,
					"allow_dynamic_wallpaper": false,
					"timer_status": 1,
					"allow_music": true,
					"allow_stitch": false
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
				"item_stitch": 1,
				"cover_labels": null,
				"mask_infos": [],
				"playlist_blocked": false,
				"green_screen_materials": null,
				"need_trim_step": false
			}
		],
		"extra": {
			"now": 1630033528000,
			"logid": "20210827030528010189074225112233E2",
			"fatal_item_ids": []
		},
		"log_pb": {
			"impr_id": "20210827030528010189074225112233E2"
		}
	}
}
```
