#  TikTok话题视频列表

# 联系方式：[点击主页查看](https://github.com/VideoData) 

#  请求Api：
```java
http://主机地址/tk/challenge/videos?token=xxx&ch_id=2087230&cursor=0
```
#  请求方式：
```java
Get
```

#  参数 
| 参数名      | 类型     | 说明     |
| ---------- | :-----------:  | :-----------: |
| token     | string     | 接口授权码     |
| ch_id     | string     | 话题id     | 


#  部分返回示例：
```
{
	"code": 200,
	"msg": "成功",
	"data": {
		"rid": "202108160650570102451442254101B342",
		"extra": {
			"logid": "202108160650570102451442254101B342",
			"now": 1629096658000,
			"fatal_item_ids": []
		},
		"log_pb": {
			"impr_id": "202108160650570102451442254101B342"
		},
		"aweme_list": [
			{
				"commerce_info": {
					"auction_ad_invited": false,
					"with_comment_filter_words": false,
					"adv_promotable": false
				},
				"is_story": 0,
				"item_stitch": 0,
				"playlist_blocked": false,
				"is_hash_tag": 1,
				"desc_language": "en",
				"bodydance_score": 0,
				"group_id": "6864614389329284357",
				"challenge_position": null,
				"item_comment_settings": 0,
				"long_video": null,
				"cover_labels": null,
				"video": {
					"bit_rate": [
						{
							"gear_name": "normal_540_0",
							"quality_type": 20,
							"bit_rate": 1620672,
							"play_addr": {
								"url_key": "v090446f0000bt204qq25p6o1evio10g_h264_540p_1620672",
								"data_size": 5804439,
								"file_hash": "6fba8a1572943626a85bd6fb084cc6fa",
								"file_cs": "c:0-32490-d979",
								"uri": "v090446f0000bt204qq25p6o1evio10g",
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/1fe052c09a3c4b0384c593bea21ef1d1\/?VExpiration=1629118286&VSignature=ac22a5475a747f8b49e53c8679f217b4&a=1233&br=3164&bt=1582&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApOTU8NTo2aGRmN2UzNDM0OGctbHMuMzJuMS9fLS0zMTZzcy0zMDM0Ni02NDUzL15eMzI6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/1acc94251ac053269c68ea7004a51448\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/1fe052c09a3c4b0384c593bea21ef1d1\/?a=1233&br=3164&bt=1582&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApOTU8NTo2aGRmN2UzNDM0OGctbHMuMzJuMS9fLS0zMTZzcy0zMDM0Ni02NDUzL15eMzI6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=55160a1a02b648c7a9e0397726932660"
								],
								"width": 720,
								"height": 720
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						},
						{
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lower_540_0",
							"quality_type": 24,
							"bit_rate": 896738,
							"play_addr": {
								"url_key": "v090446f0000bt204qq25p6o1evio10g_h264_540p_896738",
								"data_size": 3211668,
								"file_hash": "690ab34223ab6bfe9df8ba1bc71a5522",
								"file_cs": "c:0-32490-b692",
								"uri": "v090446f0000bt204qq25p6o1evio10g",
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/d0a0f2e379f14bbf9d2dd88fe943a6d7\/?VExpiration=1629118286&VSignature=76e1b7af880264c723e0974f702712df&a=1233&br=1750&bt=875&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=ajRsaHJzNXQzdzMzaTczM0ApZTVoPDg2ZmU3N2c6Zzs5NGctbHMuMzJuMS9fLS0zMTZzcy8yY2MyYmIwNi81NjZiYWE6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/236ed22bff9ca3d7479dcbfb526dadbb\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/d0a0f2e379f14bbf9d2dd88fe943a6d7\/?a=1233&br=1750&bt=875&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=ajRsaHJzNXQzdzMzaTczM0ApZTVoPDg2ZmU3N2c6Zzs5NGctbHMuMzJuMS9fLS0zMTZzcy8yY2MyYmIwNi81NjZiYWE6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=1d6d8ed979d84249b3ce3e559fef25b2"
								],
								"width": 720,
								"height": 720
							}
						},
						{
							"gear_name": "lowest_540_0",
							"quality_type": 25,
							"bit_rate": 648874,
							"play_addr": {
								"url_key": "v090446f0000bt204qq25p6o1evio10g_h264_540p_648874",
								"data_size": 2323945,
								"file_hash": "4046105d776551d223a2e4565d413be6",
								"file_cs": "c:0-32490-dda3",
								"uri": "v090446f0000bt204qq25p6o1evio10g",
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/da451f9c003a4d82a0d845142f4656db\/?VExpiration=1629118286&VSignature=e95cee2f6cdef2648d4c8c7fbb927af6&a=1233&br=1266&bt=633&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=ajRsaHJzNXQzdzMzaTczM0ApNmdoOTpoM2U2N2czOTlkM2ctbHMuMzJuMS9fLS0zMTZzczJgMF8zXzBjLzVjYzVeNi86Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/9305bd71bed5f41acb1be31015fe0275\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/da451f9c003a4d82a0d845142f4656db\/?a=1233&br=1266&bt=633&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=ajRsaHJzNXQzdzMzaTczM0ApNmdoOTpoM2U2N2czOTlkM2ctbHMuMzJuMS9fLS0zMTZzczJgMF8zXzBjLzVjYzVeNi86Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=02a96a680fdf4832bf03eb766be3dc35"
								],
								"width": 720,
								"height": 720
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null
						}
					],
					"is_h265": 0,
					"cdn_url_expired": 0,
					"need_set_token": false,
					"is_callback": true,
					"big_thumbs": null,
					"cover": {
						"uri": "tos-maliva-p-0068\/10b3199e85f84ad28c0792ac8d6d0692_1598292596",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/10b3199e85f84ad28c0792ac8d6d0692_1598292596?x-expires=1629115200&x-signature=xdfq9SCwfhn5oeSSBjasERRgqMc%3D"
						],
						"width": 720,
						"height": 720
					},
					"ratio": "540p",
					"duration": 28652,
					"download_suffix_logo_addr": {
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?VExpiration=1629118286&VSignature=92e511ad91d63eabd73546b63c7e4eee&a=1233&br=3062&bt=1531&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/a814e1e7ec209688bcd5f0358ff88e80\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?a=1233&br=3062&bt=1531&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_m_suffix&quality_type=4&source=CHALLENGE_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 6206838,
						"uri": "v090446f0000bt204qq25p6o1evio10g"
					},
					"ai_dynamic_cover": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595?x-expires=1629115200&x-signature=8S%2Fcr%2FWUhBlBELY5EmSM%2BNSpI9Q%3D"
						]
					},
					"play_addr": {
						"width": 720,
						"height": 720,
						"url_key": "v090446f0000bt204qq25p6o1evio10g_h264_540p_1620672",
						"data_size": 5804439,
						"file_hash": "6fba8a1572943626a85bd6fb084cc6fa",
						"file_cs": "c:0-32490-d979",
						"uri": "v090446f0000bt204qq25p6o1evio10g",
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/1fe052c09a3c4b0384c593bea21ef1d1\/?VExpiration=1629118286&VSignature=ac22a5475a747f8b49e53c8679f217b4&a=1233&br=3164&bt=1582&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApOTU8NTo2aGRmN2UzNDM0OGctbHMuMzJuMS9fLS0zMTZzcy0zMDM0Ni02NDUzL15eMzI6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/1acc94251ac053269c68ea7004a51448\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c003\/1fe052c09a3c4b0384c593bea21ef1d1\/?a=1233&br=3164&bt=1582&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApOTU8NTo2aGRmN2UzNDM0OGctbHMuMzJuMS9fLS0zMTZzcy0zMDM0Ni02NDUzL15eMzI6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=55160a1a02b648c7a9e0397726932660"
						]
					},
					"dynamic_cover": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595?x-expires=1629115200&x-signature=8S%2Fcr%2FWUhBlBELY5EmSM%2BNSpI9Q%3D"
						]
					},
					"has_watermark": true,
					"tags": null,
					"width": 576,
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/eee69284f4174dd99bf3d75657685af3_1598292595",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/eee69284f4174dd99bf3d75657685af3_1598292595~tplv-tiktokx-360p.webp?x-expires=1629115200&x-signature=ePBUJG27KlAT0YVnJ51VNBtryT4%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/eee69284f4174dd99bf3d75657685af3_1598292595~tplv-tiktokx-360p.jpeg?x-expires=1629115200&x-signature=M001sOlHww8joJYyttwD3jj687U%3D"
						],
						"width": 720,
						"height": 720
					},
					"has_download_suffix_logo_addr": true,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v090446f0000bt204qq25p6o1evio10g\",\"url_list\":[\"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?VExpiration=1629118286\\u0026VSignature=92e511ad91d63eabd73546b63c7e4eee\\u0026a=1233\\u0026br=3062\\u0026bt=1531\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=uDl.cgJzInzEN3stB_M\\u0026l=202108160650570102451442254101B342\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v39-us.tiktokcdn.com\/a814e1e7ec209688bcd5f0358ff88e80\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?a=1233\\u0026br=3062\\u0026bt=1531\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=uDl.cgJzInzEN3stB_M\\u0026l=202108160650570102451442254101B342\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_m_suffix\\u0026quality_type=4\\u0026source=CHALLENGE_AWEME\"],\"width\":720,\"height\":720,\"data_size\":6206838}}",
					"is_bytevc1": 0,
					"ai_dynamic_cover_bak": {
						"uri": "tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/obj\/tos-maliva-p-0068\/ef6f600a18b346d386e3889a5b610271_1598292595?x-expires=1629115200&x-signature=8S%2Fcr%2FWUhBlBELY5EmSM%2BNSpI9Q%3D"
						],
						"width": 720,
						"height": 720
					},
					"height": 1024,
					"download_addr": {
						"data_size": 6206838,
						"uri": "v090446f0000bt204qq25p6o1evio10g",
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?VExpiration=1629118286&VSignature=92e511ad91d63eabd73546b63c7e4eee&a=1233&br=3062&bt=1531&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/a814e1e7ec209688bcd5f0358ff88e80\/611a5f4e\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/67459cceea1d4abfbf12e65364409938\/?a=1233&br=3062&bt=1531&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajRsaHJzNXQzdzMzaTczM0ApaGk0OzpoN2Q1Nzc8ZjxlNWctbHMuMzJuMS9fLS0zMTZzc18vXjEuXzFjYjY0MTJgXmA6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v090446f0000bt204qq25p6o1evio10g&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_m_suffix&quality_type=4&source=CHALLENGE_AWEME"
						],
						"width": 720,
						"height": 720
					}
				},
				"is_vr": false,
				"is_relieve": false,
				"collect_stat": 0,
				"video_control": {
					"share_type": 1,
					"draft_progress_bar": 0,
					"allow_duet": true,
					"timer_status": 1,
					"allow_music": true,
					"allow_stitch": true,
					"allow_download": true,
					"allow_react": true,
					"prevent_download_type": 0,
					"allow_dynamic_wallpaper": true,
					"show_progress_bar": 0
				},
				"need_trim_step": false,
				"is_top": 0,
				"aweme_type": 0,
				"item_duet": 0,
				"has_vs_entry": false,
				"user_digged": 0,
				"uniqid_position": null,
				"distance": "",
				"video_text": [],
				"anchors": null,
				"music": {
					"external_song_info": [],
					"is_pgc": true,
					"album": "BeVerly Hills BoYfRiEnd",
					"prevent_item_download_status": 0,
					"binded_challenge_id": 0,
					"cover_medium": {
						"height": 720,
						"uri": "tos-alisg-v-2774\/723882a314894ae283671d854c1fda17",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/723882a314894ae283671d854c1fda17.jpeg"
						],
						"width": 720
					},
					"collect_stat": 0,
					"is_commerce_music": false,
					"tag_list": null,
					"is_author_artist": true,
					"author": "Claire Rosinkranz",
					"cover_large": {
						"uri": "tos-alisg-v-2774\/723882a314894ae283671d854c1fda17",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/720x720\/tos-alisg-v-2774\/723882a314894ae283671d854c1fda17.jpeg"
						],
						"width": 720,
						"height": 720
					},
					"status": 1,
					"is_original_sound": false,
					"id_str": "6835837996332222466",
					"duration": 60,
					"audition_duration": 45,
					"artists": [],
					"is_matched_metadata": false,
					"schema_url": "",
					"redirect": false,
					"prevent_download": false,
					"preview_start_time": 0,
					"dmv_auto_show": false,
					"extra": "{\"is_ugc_mapping\":false,\"apple_song_id\":1527786138,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{\"merged_beats\":\"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/d68fb2b33afe499580a930a01b986382\",\"audio_effect_onset\":\"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/137b434593654d4e91f0cdddcbb1adfa\",\"beats_tracker\":\"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/9323b85161644d118742d037be00bc81\",\"energy_trace\":\"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/cfb788118dfc486e938762b68fb0d31e\"},\"schedule_search_time\":0,\"aed_music_dur\":58.23}",
					"mid": "6835837996332222466",
					"is_original": false,
					"unshelve_countries": null,
					"reason_type": 0,
					"video_duration": 60,
					"offline_desc": "",
					"owner_nickname": "",
					"mute_share": false,
					"is_audio_url_with_cookie": false,
					"cover_hd": {
						"height": 720,
						"uri": "tos-alisg-v-2774\/723882a314894ae283671d854c1fda17",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/1080x1080\/tos-alisg-v-2774\/723882a314894ae283671d854c1fda17.jpeg"
						],
						"width": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/85505d4f6c154cbfa7f49cd6dd0c98d6",
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-ve-2774\/85505d4f6c154cbfa7f49cd6dd0c98d6"
						],
						"width": 720,
						"height": 720
					},
					"is_video_self_see": false,
					"shoot_duration": 45,
					"lyric_short_position": null,
					"id": 6835837996332222466,
					"search_highlight": null,
					"is_del_video": false,
					"owner_handle": "",
					"position": null,
					"is_restricted": false,
					"start_time": 0,
					"end_time": 0,
					"preview_end_time": 0,
					"source_platform": 10033,
					"author_position": null,
					"cover_thumb": {
						"width": 720,
						"height": 720,
						"uri": "tos-alisg-v-2774\/723882a314894ae283671d854c1fda17",
						"url_list": [
							"https:\/\/p16-sg.tiktokcdn.com\/aweme\/100x100\/tos-alisg-v-2774\/723882a314894ae283671d854c1fda17.jpeg"
						]
					},
					"strong_beat_url": {
						"width": 720,
						"height": 720,
						"uri": "https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/906a404e42e94ac8b8f21800efda08f7",
						"url_list": [
							"https:\/\/sf16-ies-music-sg.tiktokcdn.com\/obj\/tos-alisg-v-2774\/906a404e42e94ac8b8f21800efda08f7"
						]
					},
					"title": "Backyard Boy",
					"user_count": 0,
					"author_deleted": false,
					"matched_song": {
						"id": "6860911336985987074",
						"author": "Claire Rosinkranz",
						"title": "Backyard Boy",
						"h5_url": "",
						"cover_medium": {
							"uri": "tos-alisg-v-2774\/723882a314894ae283671d854c1fda17",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/aweme\/200x200\/tos-alisg-v-2774\/723882a314894ae283671d854c1fda17.jpeg"
							],
							"width": 720,
							"height": 720
						}
					}
				},
				"label_top": {
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					],
					"width": 720,
					"height": 720
				},
				"hybrid_label": null,
				"text_extra": [
					{
						"user_id": "6620022469750063110",
						"type": 0,
						"sec_uid": "MS4wLjABAAAA87ZtTDaP67ladRmqxDlC0uyrSdBwqzo4NDAiLlyU3vxfgsNq-CgiKAW5QQFvgNGr",
						"start": 74,
						"end": 88
					},
					{
						"start": 33,
						"end": 40,
						"type": 1,
						"hashtag_name": "diving",
						"hashtag_id": "7967",
						"is_commerce": false
					},
					{
						"hashtag_name": "waitforthegreats",
						"hashtag_id": "1675566909876229",
						"is_commerce": false,
						"start": 41,
						"end": 58,
						"type": 1
					},
					{
						"end": 68,
						"type": 1,
						"hashtag_name": "olympian",
						"hashtag_id": "2087230",
						"is_commerce": false,
						"start": 59
					}
				],
				"is_pgcshow": false,
				"region": "US",
				"nickname_position": null,
				"share_info": {
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out Steele Johnson’s video! #TikTok > ",
					"share_title": "Check out Steele Johnson’s video! #TikTok > ",
					"bool_persist": 0,
					"share_quote": "",
					"share_link_desc": "",
					"share_signature_url": "",
					"share_signature_desc": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out Steele Johnson’s video! #TikTok > ",
					"share_url": "https:\/\/m.tiktok.com\/v\/6864614389329284357.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6864614389329284357&source=h5_m",
					"share_desc": "Check out Steele Johnson's video! #TikTok",
					"share_title_myself": "",
					"share_title_other": ""
				},
				"video_labels": [],
				"share_url": "https:\/\/m.tiktok.com\/v\/6864614389329284357.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6864614389329284357&source=h5_m",
				"status": {
					"is_delete": false,
					"is_private": false,
					"download_status": 0,
					"with_goods": false,
					"private_status": 0,
					"in_reviewing": false,
					"reviewed": 1,
					"self_see": false,
					"aweme_id": "6864614389329284357",
					"allow_share": true,
					"allow_comment": true,
					"is_prohibited": false,
					"review_result": {
						"review_status": 0
					}
				},
				"image_infos": null,
				"sort_label": "",
				"interaction_stickers": null,
				"origin_comment_ids": null,
				"desc": "Roast my form in the comments 😤 #diving #WaitForTheGreats #olympian (🎥: @jordan.rzepka)",
				"cha_list": [
					{
						"banner_list": null,
						"extra_attr": {
							"is_live": false
						},
						"show_items": null,
						"search_highlight": null,
						"cha_name": "diving",
						"author": {
							"cover_url": null,
							"type_label": null,
							"relative_users": null,
							"need_points": null,
							"item_list": null,
							"ad_cover_url": null,
							"cha_list": null,
							"homepage_bottom_toast": null,
							"can_set_geofencing": null,
							"bold_fields": null,
							"mutual_relation_avatars": null,
							"events": null,
							"followers_detail": null,
							"platform_sync_info": null,
							"geofencing": null,
							"white_cover_url": null,
							"user_tags": null,
							"search_highlight": null
						},
						"is_pgcshow": false,
						"is_challenge": 0,
						"cid": "7967",
						"user_count": 0,
						"collect_stat": 0,
						"is_commerce": false,
						"hashtag_profile": "",
						"cha_attrs": null,
						"share_info": {
							"bool_persist": 0,
							"share_signature_url": "",
							"share_signature_desc": "",
							"share_quote": "",
							"share_desc_info": "Check out #diving on TikTok!",
							"share_url": "https:\/\/m.tiktok.com\/h5\/share\/tag\/7967.html?name=diving&u_code=0&language=en&_d=dk4e43gkjcg74h&share_challenge_id=7967&source=h5_m",
							"share_weibo_desc": "Check out #diving on TikTok!",
							"share_desc": "Check out #diving on TikTok!",
							"share_title": "It is a becoming a big trend on TikTok now! Click here: diving",
							"share_title_myself": "",
							"share_title_other": ""
						},
						"connect_music": [],
						"type": 1,
						"view_count": 0,
						"desc": "",
						"schema": "aweme:\/\/aweme\/challenge\/detail?cid=7967",
						"sub_type": 0
					}
				],
				"label_top_text": null,
				"commerce_config_data": null,
				"need_vs_entry": false,
				"aweme_id": "6864614389329284357",
				"position": null,
				"author": {
					"avatar_medium": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_720x720.webp?x-expires=1629180000&x-signature=WCDe7PluWp0JhUNrnzblH9%2FDL40%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_720x720.jpeg?x-expires=1629180000&x-signature=UAfwMa4QgWaZPI7fX7Vdq%2F7t0j4%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/1660021377926150"
					},
					"twitter_name": "",
					"duet_setting": 0,
					"download_setting": 0,
					"follower_count": 0,
					"show_image_bubble": false,
					"download_prompt_ts": 0,
					"need_points": null,
					"hide_search": false,
					"comment_setting": 0,
					"bold_fields": null,
					"nickname": "Steele Johnson",
					"following_count": 0,
					"is_block": false,
					"bind_phone": "",
					"room_id": 0,
					"shield_digg_notice": 0,
					"youtube_channel_id": "UC-ppQdO9AyYoXW5EP0gsdIw",
					"item_list": null,
					"authority_status": 0,
					"geofencing": [],
					"with_fusion_shop_entry": false,
					"user_canceled": false,
					"is_star": false,
					"video_icon": {
						"uri": "",
						"url_list": [],
						"width": 720,
						"height": 720
					},
					"create_time": 0,
					"sec_uid": "MS4wLjABAAAAJJudLKZPoDjgXI_0q1wQqRwYkNQ8_J4GPDXijOoPi9KsCGPZKe3mmo2h62WOOGxs",
					"follow_status": 0,
					"type_label": null,
					"comment_filter_status": 0,
					"events": null,
					"relative_users": null,
					"signature": "Olympic Silver Medalist\nOn the road to recovery 🤕",
					"shield_follow_notice": 0,
					"shield_comment_notice": 0,
					"live_agreement": 0,
					"avatar_uri": "musically-maliva-obj\/1660021377926150",
					"follower_status": 0,
					"user_period": 0,
					"mutual_relation_avatars": null,
					"special_lock": 1,
					"ins_id": "steele_johnson",
					"avatar_300x300": {
						"uri": "musically-maliva-obj\/1660021377926150",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_300x300.webp?x-expires=1629180000&x-signature=wilNxYJr0GwrCobw0dgVvdrCn4A%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_300x300.jpeg?x-expires=1629180000&x-signature=f0bQbIAy1iQ%2FFRI%2BgNstCj7OshE%3D"
						],
						"width": 720,
						"height": 720
					},
					"need_recommend": 0,
					"youtube_expire_time": 0,
					"is_phone_binded": false,
					"reflow_page_gid": 0,
					"with_commerce_entry": false,
					"unique_id": "steele_johnson",
					"has_orders": false,
					"prevent_download": false,
					"apple_account": 0,
					"live_agreement_time": 0,
					"platform_sync_info": null,
					"twitter_id": "",
					"share_qrcode_uri": "",
					"is_ad_fake": false,
					"ad_cover_url": null,
					"white_cover_url": null,
					"uid": "6718109734736348166",
					"avatar_larger": {
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/1660021377926150",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_1080x1080.webp?x-expires=1629180000&x-signature=I506SeAvQ4b1YgyleDkFZPU74ug%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=i7C%2BCQ3H2%2Fw7CTawvp%2By08APYtg%3D"
						]
					},
					"unique_id_modify_time": 1629096658,
					"user_rate": 17,
					"birthday": "1900-01-01",
					"tw_expire_time": 0,
					"enterprise_verify_reason": "",
					"region": "US",
					"google_account": "",
					"commerce_user_level": 0,
					"reflow_page_uid": 0,
					"short_id": "0",
					"youtube_channel_title": "Steele Johnson",
					"status": 1,
					"stitch_setting": 0,
					"avatar_thumb": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_100x100.webp?x-expires=1629180000&x-signature=56PaRtztF%2FuUEa8Mru%2BbMnQ3mqc%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_100x100.jpeg?x-expires=1629180000&x-signature=Ex56vt5M4WWrJ0SZ8CPBP03yUOw%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "musically-maliva-obj\/1660021377926150"
					},
					"has_facebook_token": false,
					"fb_expire_time": 0,
					"with_shop_entry": false,
					"avatar_168x168": {
						"uri": "musically-maliva-obj\/1660021377926150",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_168x168.webp?x-expires=1629180000&x-signature=qyEKZC2rduNrUddy6wxMn%2F7cyW8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/musically-maliva-obj\/1660021377926150~c5_168x168.jpeg?x-expires=1629180000&x-signature=XqXObhtSPRPlnr5Y65leS0SjLbg%3D"
						],
						"width": 720,
						"height": 720
					},
					"has_youtube_token": false,
					"language": "en",
					"verification_type": 1,
					"is_discipline_member": false,
					"aweme_count": 0,
					"total_favorited": 0,
					"secret": 0,
					"accept_private_policy": false,
					"favoriting_count": 0,
					"custom_verify": "Verified account",
					"has_twitter_token": false,
					"followers_detail": null,
					"live_verify": 0,
					"has_insights": false,
					"user_mode": 1,
					"cv_level": "",
					"qa_status": 1,
					"homepage_bottom_toast": null,
					"gender": 0,
					"has_email": false,
					"react_setting": 0,
					"user_tags": null,
					"verify_info": "",
					"cover_url": [
						{
							"width": 720,
							"height": 720,
							"uri": "tiktok-obj\/1613727517271041",
							"url_list": [
								"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1613727517271041"
							]
						}
					],
					"can_set_geofencing": null,
					"cha_list": null,
					"share_info": {
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
						"share_url": "",
						"share_weibo_desc": ""
					},
					"live_commerce": false,
					"account_region": "",
					"search_highlight": null
				},
				"distribute_type": 1,
				"cmt_swt": false,
				"item_react": 0,
				"have_dashboard": false,
				"create_time": 1598292592,
				"without_watermark": false,
				"geofencing_regions": null,
				"mask_infos": [],
				"search_highlight": null,
				"duration": 28652,
				"author_user_id": 6718109734736348166,
				"with_promotional_music": false,
				"misc_info": "{}",
				"rate": 12,
				"prevent_download": false,
				"geofencing": [],
				"is_preview": 0,
				"green_screen_materials": null,
				"statistics": {
					"comment_count": 1269,
					"lose_comment_count": 0,
					"aweme_id": "6864614389329284357",
					"download_count": 293,
					"play_count": 4163152,
					"share_count": 725,
					"forward_count": 0,
					"lose_count": 0,
					"whatsapp_share_count": 73,
					"digg_count": 353011
				},
				"risk_infos": {
					"content": "",
					"vote": false,
					"warn": false,
					"risk_sink": false,
					"type": 0
				}
			},
			{
				"video_labels": [],
				"sort_label": "",
				"group_id": "6992456889573379334",
				"is_top": 0,
				"geofencing": [],
				"label_top_text": null,
				"commerce_info": {
					"auction_ad_invited": false,
					"with_comment_filter_words": false,
					"adv_promotable": false
				},
				"search_highlight": null,
				"aweme_id": "6992456889573379334",
				"position": null,
				"green_screen_materials": null,
				"desc": "I am convinced that Tokyo has the most cicadas in the world #tokyo2020 #olympictiktok #Olympian",
				"create_time": 1628058242,
				"statistics": {
					"download_count": 137,
					"play_count": 1823449,
					"forward_count": 0,
					"lose_comment_count": 0,
					"aweme_id": "6992456889573379334",
					"comment_count": 1626,
					"digg_count": 319879,
					"share_count": 932,
					"lose_count": 0,
					"whatsapp_share_count": 74
				},
				"video_control": {
					"share_type": 1,
					"allow_duet": true,
					"timer_status": 1,
					"allow_stitch": true,
					"allow_music": true,
					"allow_download": true,
					"show_progress_bar": 0,
					"draft_progress_bar": 0,
					"allow_react": true,
					"prevent_download_type": 0,
					"allow_dynamic_wallpaper": true
				},
				"cover_labels": null,
				"author": {
					"custom_verify": "Verified account",
					"secret": 0,
					"youtube_channel_title": "",
					"avatar_300x300": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_300x300.webp?x-expires=1629180000&x-signature=6T8c52XA9eNfNRkyATfBI6mV2c8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_300x300.jpeg?x-expires=1629180000&x-signature=mPLPgLUwyIbUmcfRtg8aAw9Ip30%3D"
						]
					},
					"live_commerce": false,
					"total_favorited": 0,
					"has_youtube_token": false,
					"with_fusion_shop_entry": false,
					"qa_status": 0,
					"has_twitter_token": false,
					"is_discipline_member": false,
					"comment_setting": 0,
					"live_agreement_time": 0,
					"reflow_page_gid": 0,
					"account_region": "",
					"has_orders": false,
					"avatar_thumb": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.webp?x-expires=1629180000&x-signature=8ULORe51PbSlejAis8nqquniZzk%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.jpeg?x-expires=1629180000&x-signature=BSNMKyVjA3iAO8TDqH7Z%2BXmpIIk%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590"
					},
					"hide_search": false,
					"unique_id": "raydinc",
					"shield_comment_notice": 0,
					"is_ad_fake": false,
					"gender": 0,
					"signature": "2021 Tokyo Discus Olympian🥏🇺🇸\nPB:64.41(211’4”ft)\nSupport my journey below❤️⬇️",
					"following_count": 0,
					"ins_id": "raydinc",
					"need_points": null,
					"nickname": "Rachel Dincoff",
					"user_rate": 1,
					"cv_level": "",
					"has_facebook_token": false,
					"live_verify": 0,
					"shield_follow_notice": 0,
					"platform_sync_info": null,
					"google_account": "",
					"accept_private_policy": false,
					"type_label": null,
					"share_info": {
						"share_title_other": "",
						"share_desc_info": "",
						"share_url": "",
						"share_weibo_desc": "",
						"share_desc": "",
						"share_title": "",
						"share_qrcode_url": {
							"height": 720,
							"uri": "",
							"url_list": [],
							"width": 720
						},
						"share_title_myself": ""
					},
					"duet_setting": 0,
					"has_insights": false,
					"user_tags": null,
					"user_period": 0,
					"avatar_medium": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.webp?x-expires=1629180000&x-signature=USI5loehnhFCcw5bYvOUWUyo%2F%2F8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.jpeg?x-expires=1629180000&x-signature=thnXEWnd2ygoAfUHNjE%2Ff705NK8%3D"
						],
						"width": 720,
						"height": 720
					},
					"youtube_expire_time": 0,
					"enterprise_verify_reason": "",
					"user_canceled": false,
					"follower_status": 0,
					"react_setting": 0,
					"follower_count": 0,
					"is_block": false,
					"avatar_168x168": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_168x168.webp?x-expires=1629180000&x-signature=L3zvax0uBg5WQcRt8DUMjyI0w90%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_168x168.jpeg?x-expires=1629180000&x-signature=kpoysOfgm%2FqU0CQT%2BnAcwvKYtdw%3D"
						],
						"width": 720,
						"height": 720
					},
					"sec_uid": "MS4wLjABAAAArS6V5L2xZf0--VWv4pEjGEMgkAjPuCOmwLSn6_-kiL64SkiLkwPwtqetZWkYse-G",
					"can_set_geofencing": null,
					"verification_type": 1,
					"white_cover_url": null,
					"authority_status": 0,
					"geofencing": [],
					"video_icon": {
						"width": 720,
						"height": 720,
						"uri": "",
						"url_list": []
					},
					"bold_fields": null,
					"live_agreement": 0,
					"status": 1,
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
					"homepage_bottom_toast": null,
					"search_highlight": null,
					"follow_status": 0,
					"prevent_download": false,
					"download_prompt_ts": 0,
					"show_image_bubble": false,
					"twitter_id": "",
					"item_list": null,
					"share_qrcode_uri": "",
					"favoriting_count": 0,
					"verify_info": "",
					"region": "US",
					"youtube_channel_id": "",
					"twitter_name": "",
					"need_recommend": 0,
					"create_time": 0,
					"is_star": false,
					"reflow_page_uid": 0,
					"mutual_relation_avatars": null,
					"shield_digg_notice": 0,
					"with_commerce_entry": false,
					"followers_detail": null,
					"with_shop_entry": false,
					"relative_users": null,
					"events": null,
					"avatar_larger": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.webp?x-expires=1629180000&x-signature=TOlSCn7jad%2BYpEm9t5pJ6zmSXXg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Jzby8bpp4u2ziG5jLRA1wzBo6uQ%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590"
					},
					"birthday": "1900-01-01",
					"aweme_count": 0,
					"fb_expire_time": 0,
					"unique_id_modify_time": 1629096658,
					"cha_list": null,
					"stitch_setting": 0,
					"uid": "6895578589849879558",
					"short_id": "0",
					"tw_expire_time": 0,
					"room_id": 0,
					"is_phone_binded": false,
					"ad_cover_url": null,
					"language": "en",
					"comment_filter_status": 0,
					"bind_phone": "",
					"commerce_user_level": 0,
					"apple_account": 0,
					"has_email": false,
					"special_lock": 1,
					"avatar_uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
					"user_mode": 1
				},
				"music": {
					"avatar_thumb": {
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.webp?x-expires=1629180000&x-signature=8ULORe51PbSlejAis8nqquniZzk%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.jpeg?x-expires=1629180000&x-signature=BSNMKyVjA3iAO8TDqH7Z%2BXmpIIk%3D"
						],
						"width": 720
					},
					"is_original_sound": true,
					"collect_stat": 0,
					"shoot_duration": 9,
					"artists": [],
					"prevent_item_download_status": 0,
					"is_matched_metadata": false,
					"cover_hd": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.webp?x-expires=1629180000&x-signature=TOlSCn7jad%2BYpEm9t5pJ6zmSXXg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Jzby8bpp4u2ziG5jLRA1wzBo6uQ%3D"
						],
						"width": 720,
						"height": 720
					},
					"owner_id": "6895578589849879558",
					"is_original": false,
					"cover_thumb": {
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.webp?x-expires=1629180000&x-signature=8ULORe51PbSlejAis8nqquniZzk%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_100x100.jpeg?x-expires=1629180000&x-signature=BSNMKyVjA3iAO8TDqH7Z%2BXmpIIk%3D"
						],
						"width": 720
					},
					"end_time": 0,
					"is_commerce_music": true,
					"mute_share": false,
					"search_highlight": null,
					"start_time": 0,
					"cover_medium": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.webp?x-expires=1629180000&x-signature=USI5loehnhFCcw5bYvOUWUyo%2F%2F8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.jpeg?x-expires=1629180000&x-signature=thnXEWnd2ygoAfUHNjE%2Ff705NK8%3D"
						],
						"width": 720,
						"height": 720
					},
					"play_url": {
						"uri": "https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/musically-maliva-obj\/6992456705481247493.mp3",
						"url_list": [
							"https:\/\/sf16-ies-music-va.tiktokcdn.com\/obj\/musically-maliva-obj\/6992456705481247493.mp3"
						],
						"width": 720,
						"height": 720
					},
					"extra": "{\"schedule_search_time\":0,\"is_ugc_mapping\":false,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{}}",
					"status": 1,
					"mid": "6992456477512567557",
					"binded_challenge_id": 0,
					"is_video_self_see": false,
					"author": "Rachel Dincoff",
					"video_duration": 9,
					"preview_start_time": 0,
					"author_position": null,
					"is_author_artist": false,
					"author_deleted": false,
					"source_platform": 72,
					"duration": 9,
					"lyric_short_position": null,
					"id": 6992456477512567557,
					"album": "",
					"schema_url": "",
					"position": null,
					"owner_nickname": "Rachel Dincoff",
					"redirect": false,
					"is_restricted": false,
					"unshelve_countries": null,
					"id_str": "6992456477512567557",
					"audition_duration": 9,
					"external_song_info": [],
					"sec_uid": "MS4wLjABAAAArS6V5L2xZf0--VWv4pEjGEMgkAjPuCOmwLSn6_-kiL64SkiLkwPwtqetZWkYse-G",
					"is_pgc": false,
					"cover_large": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.webp?x-expires=1629180000&x-signature=TOlSCn7jad%2BYpEm9t5pJ6zmSXXg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Jzby8bpp4u2ziG5jLRA1wzBo6uQ%3D"
						],
						"width": 720,
						"height": 720
					},
					"is_del_video": false,
					"prevent_download": false,
					"title": "original sound - raydinc",
					"reason_type": 0,
					"offline_desc": "",
					"avatar_large": {
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.webp?x-expires=1629180000&x-signature=TOlSCn7jad%2BYpEm9t5pJ6zmSXXg%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_1080x1080.jpeg?x-expires=1629180000&x-signature=Jzby8bpp4u2ziG5jLRA1wzBo6uQ%3D"
						],
						"width": 720,
						"height": 720
					},
					"preview_end_time": 0,
					"dmv_auto_show": false,
					"user_count": 0,
					"avatar_medium": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.webp?x-expires=1629180000&x-signature=USI5loehnhFCcw5bYvOUWUyo%2F%2F8%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-avt-0068\/e6037da46788e4fdbde6208a743bc590~c5_720x720.jpeg?x-expires=1629180000&x-signature=thnXEWnd2ygoAfUHNjE%2Ff705NK8%3D"
						]
					},
					"tag_list": null,
					"is_audio_url_with_cookie": false,
					"owner_handle": "raydinc"
				},
				"status": {
					"allow_comment": true,
					"is_private": false,
					"private_status": 0,
					"download_status": 0,
					"review_result": {
						"review_status": 0
					},
					"self_see": false,
					"is_prohibited": false,
					"aweme_id": "6992456889573379334",
					"is_delete": false,
					"allow_share": true,
					"with_goods": false,
					"in_reviewing": false,
					"reviewed": 1
				},
				"label_top": {
					"uri": "tiktok-obj\/1598708589477025.PNG",
					"url_list": [
						"https:\/\/p16-sg.tiktokcdn.com\/obj\/tiktok-obj\/1598708589477025.PNG"
					],
					"width": 720,
					"height": 720
				},
				"distance": "",
				"bodydance_score": 0,
				"has_vs_entry": false,
				"item_stitch": 0,
				"cmt_swt": false,
				"desc_language": "en",
				"distribute_type": 1,
				"need_trim_step": false,
				"long_video": null,
				"interaction_stickers": null,
				"misc_info": "{}",
				"playlist_blocked": false,
				"cha_list": [
					{
						"type": 2,
						"sub_type": 0,
						"view_count": 0,
						"hashtag_profile": "tiktok-obj\/70a95c8380ad2ad152796a42063dfa80",
						"cha_attrs": null,
						"banner_list": null,
						"extra_attr": {
							"is_live": false
						},
						"desc": "",
						"search_highlight": null,
						"show_items": null,
						"author": {
							"relative_users": null,
							"need_points": null,
							"bold_fields": null,
							"search_highlight": null,
							"geofencing": null,
							"cover_url": null,
							"ad_cover_url": null,
							"cha_list": null,
							"user_tags": null,
							"mutual_relation_avatars": null,
							"type_label": null,
							"can_set_geofencing": null,
							"white_cover_url": null,
							"events": null,
							"followers_detail": null,
							"platform_sync_info": null,
							"item_list": null,
							"homepage_bottom_toast": null
						},
						"user_count": 0,
						"share_info": {
							"share_quote": "",
							"share_desc_info": "Check out #tokyo2020 on TikTok!",
							"share_desc": "Check out #tokyo2020 on TikTok!",
							"share_title": "It is a becoming a big trend on TikTok now! Click here: tokyo2020",
							"share_title_myself": "",
							"share_title_other": "",
							"share_signature_desc": "",
							"share_url": "https:\/\/m.tiktok.com\/h5\/share\/tag\/20356237.html?name=tokyo2020&u_code=0&language=en&_d=dk4e43gkjcg74h&share_challenge_id=20356237&source=h5_m",
							"share_weibo_desc": "Check out #tokyo2020 on TikTok!",
							"bool_persist": 0,
							"share_signature_url": ""
						},
						"connect_music": [],
						"is_commerce": false,
						"schema": "aweme:\/\/aweme\/challenge\/detail?cid=20356237",
						"cid": "20356237",
						"is_pgcshow": false,
						"collect_stat": 0,
						"is_challenge": 0,
						"cha_name": "Tokyo2020"
					}
				],
				"rate": 12,
				"image_infos": null,
				"author_user_id": 6895578589849879558,
				"item_duet": 0,
				"need_vs_entry": false,
				"hybrid_label": null,
				"video": {
					"cover": {
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/17302072fa08406e865d34d74aa27f8d_1628058244",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/17302072fa08406e865d34d74aa27f8d_1628058244~tplv-dmt-logom:tos-maliva-p-0000\/f83c477d9123469dbed7c43b9a16d35e.image?x-expires=1629115200&x-signature=38Q1hPW1vQfRHaXAq25RUwg7FIw%3D"
						]
					},
					"has_watermark": true,
					"is_bytevc1": 0,
					"ai_dynamic_cover_bak": {
						"height": 720,
						"uri": "tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243~tplv-dmt-logom:tos-maliva-p-0000\/f83c477d9123469dbed7c43b9a16d35e.image?x-expires=1629115200&x-signature=%2FJxbiuyaIGMCeXu3Su9BZpOYy6Q%3D"
						],
						"width": 720
					},
					"meta": "{\"peak\":\"1\",\"loudness\":\"-13.2\"}",
					"ai_dynamic_cover": {
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243~tplv-dmt-logom:tos-maliva-p-0000\/f83c477d9123469dbed7c43b9a16d35e.image?x-expires=1629115200&x-signature=%2FJxbiuyaIGMCeXu3Su9BZpOYy6Q%3D"
						],
						"width": 720,
						"height": 720,
						"uri": "tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243"
					},
					"dynamic_cover": {
						"uri": "tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/b4261688223444558cce9bc0309159c8_1628058243~tplv-dmt-logom:tos-maliva-p-0000\/f83c477d9123469dbed7c43b9a16d35e.image?x-expires=1629115200&x-signature=%2FJxbiuyaIGMCeXu3Su9BZpOYy6Q%3D"
						],
						"width": 720,
						"height": 720
					},
					"origin_cover": {
						"uri": "tos-maliva-p-0068\/d4250c0f66ec43ee9454dd556c8daf24_1628058243",
						"url_list": [
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/d4250c0f66ec43ee9454dd556c8daf24_1628058243~tplv-tiktokx-360p.webp?x-expires=1629115200&x-signature=k%2FPLWVFwZt4WOrJy5x29kwKfb4U%3D",
							"https:\/\/p16-sign-va.tiktokcdn.com\/tos-maliva-p-0068\/d4250c0f66ec43ee9454dd556c8daf24_1628058243~tplv-tiktokx-360p.jpeg?x-expires=1629115200&x-signature=i7%2Fdf7Z25Td2fEaLYZ7UGZ5sC40%3D"
						],
						"width": 720,
						"height": 720
					},
					"ratio": "540p",
					"download_addr": {
						"uri": "v09044g40000c4530trc77ubrlsgaur0",
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/f4c86e89b9d34f8ca465704e150bfc18\/?VExpiration=1629118267&VSignature=51b18bb97ef3da30c8f0d128ad1a1e96&a=1233&br=2578&bt=1289&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApM2Y8ODQzPDxnNzdlPDVnaGdvXnBvcjRvLTJgLS1kMTZzczEzM2MyYTQxYDU1NGNeLzQ6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/2342ccffe82c6781103533641471a5d7\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/f4c86e89b9d34f8ca465704e150bfc18\/?a=1233&br=2578&bt=1289&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApM2Y8ODQzPDxnNzdlPDVnaGdvXnBvcjRvLTJgLS1kMTZzczEzM2MyYTQxYDU1NGNeLzQ6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_end&quality_type=4&source=CHALLENGE_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 2280802
					},
					"tags": null,
					"has_download_suffix_logo_addr": true,
					"misc_download_addrs": "{\"suffix_scene\":{\"uri\":\"v09044g40000c4530trc77ubrlsgaur0\",\"url_list\":[\"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/47f507c4d0a54d9181341a0bbe4afcbd\/?VExpiration=1629118267\\u0026VSignature=ae89e62a2542a665be60dc80d28c37f3\\u0026a=1233\\u0026br=2746\\u0026bt=1373\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=uDl.cgJzInzEN3stB_M\\u0026l=202108160650570102451442254101B342\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=M3hqb2U6Znc2NzMzNzczM0ApaDk0ZGhlZmU8NzQ8N2k4NWdvXnBvcjRvLTJgLS1kMTZzczMzMjNfNTEuYGE1MWI0YTU6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/v39-us.tiktokcdn.com\/44cc3f88fd75555151d13c52352a3dbd\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/47f507c4d0a54d9181341a0bbe4afcbd\/?a=1233\\u0026br=2746\\u0026bt=1373\\u0026cd=0%7C0%7C0\\u0026ch=0\\u0026cr=0\\u0026cs=0\\u0026cv=1\\u0026dr=0\\u0026ds=3\\u0026er=\\u0026ft=uDl.cgJzInzEN3stB_M\\u0026l=202108160650570102451442254101B342\\u0026lr=all\\u0026mime_type=video_mp4\\u0026net=0\\u0026pl=0\\u0026qs=0\\u0026rc=M3hqb2U6Znc2NzMzNzczM0ApaDk0ZGhlZmU8NzQ8N2k4NWdvXnBvcjRvLTJgLS1kMTZzczMzMjNfNTEuYGE1MWI0YTU6Yw%3D%3D\\u0026vl=\\u0026vr=\",\"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0\\u0026line=0\\u0026ratio=540p\\u0026watermark=1\\u0026media_type=4\\u0026vr_type=0\\u0026improve_bitrate=0\\u0026logo_name=tiktok_surprise\\u0026quality_type=4\\u0026source=CHALLENGE_AWEME\"],\"width\":720,\"height\":720,\"data_size\":2238146}}",
					"is_callback": true,
					"play_addr": {
						"height": 720,
						"url_key": "v09044g40000c4530trc77ubrlsgaur0_h264_540p_1637595",
						"data_size": 2029186,
						"file_hash": "e7fffb7e99ce41e8b1c0e154708d68e3",
						"file_cs": "c:0-9390-9cd4",
						"uri": "v09044g40000c4530trc77ubrlsgaur0",
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/cbb34695ea7441ada22591199f726783\/?VExpiration=1629118267&VSignature=325fe1e1590f63c1ad16af2feae8eb2a&a=1233&br=3198&bt=1599&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApOWg7Zmc5N2RkN2k4Ojo2OGdvXnBvcjRvLTJgLS1kMTZzc2AuMzNgMGMvNF41Yi1iYDY6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/eb09e400d05efc5e77659df6a55d5d28\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/cbb34695ea7441ada22591199f726783\/?a=1233&br=3198&bt=1599&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApOWg7Zmc5N2RkN2k4Ojo2OGdvXnBvcjRvLTJgLS1kMTZzc2AuMzNgMGMvNF41Yi1iYDY6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=593c7e705ef84aa7a24f63dcc686e16c"
						],
						"width": 720
					},
					"height": 1024,
					"width": 576,
					"duration": 9913,
					"download_suffix_logo_addr": {
						"url_list": [
							"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/47f507c4d0a54d9181341a0bbe4afcbd\/?VExpiration=1629118267&VSignature=ae89e62a2542a665be60dc80d28c37f3&a=1233&br=2746&bt=1373&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApaDk0ZGhlZmU8NzQ8N2k4NWdvXnBvcjRvLTJgLS1kMTZzczMzMjNfNTEuYGE1MWI0YTU6Yw%3D%3D&vl=&vr=",
							"https:\/\/v39-us.tiktokcdn.com\/44cc3f88fd75555151d13c52352a3dbd\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c004\/47f507c4d0a54d9181341a0bbe4afcbd\/?a=1233&br=2746&bt=1373&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=3&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApaDk0ZGhlZmU8NzQ8N2k4NWdvXnBvcjRvLTJgLS1kMTZzczMzMjNfNTEuYGE1MWI0YTU6Yw%3D%3D&vl=&vr=",
							"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&ratio=540p&watermark=1&media_type=4&vr_type=0&improve_bitrate=0&logo_name=tiktok_surprise&quality_type=4&source=CHALLENGE_AWEME"
						],
						"width": 720,
						"height": 720,
						"data_size": 2238146,
						"uri": "v09044g40000c4530trc77ubrlsgaur0"
					},
					"big_thumbs": null,
					"bit_rate": [
						{
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "normal_540_0",
							"quality_type": 20,
							"bit_rate": 1637595,
							"play_addr": {
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/cbb34695ea7441ada22591199f726783\/?VExpiration=1629118267&VSignature=325fe1e1590f63c1ad16af2feae8eb2a&a=1233&br=3198&bt=1599&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApOWg7Zmc5N2RkN2k4Ojo2OGdvXnBvcjRvLTJgLS1kMTZzc2AuMzNgMGMvNF41Yi1iYDY6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/eb09e400d05efc5e77659df6a55d5d28\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-pve-0068\/cbb34695ea7441ada22591199f726783\/?a=1233&br=3198&bt=1599&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=M3hqb2U6Znc2NzMzNzczM0ApOWg7Zmc5N2RkN2k4Ojo2OGdvXnBvcjRvLTJgLS1kMTZzc2AuMzNgMGMvNF41Yi1iYDY6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=593c7e705ef84aa7a24f63dcc686e16c"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c4530trc77ubrlsgaur0_h264_540p_1637595",
								"data_size": 2029186,
								"file_hash": "e7fffb7e99ce41e8b1c0e154708d68e3",
								"file_cs": "c:0-9390-9cd4",
								"uri": "v09044g40000c4530trc77ubrlsgaur0"
							}
						},
						{
							"quality_type": 24,
							"bit_rate": 890649,
							"play_addr": {
								"url_key": "v09044g40000c4530trc77ubrlsgaur0_h264_540p_890649",
								"data_size": 1103626,
								"file_hash": "bb83ae750e87f05ced92e03af9cd856a",
								"file_cs": "c:0-9390-4cf0",
								"uri": "v09044g40000c4530trc77ubrlsgaur0",
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/50f366d98a5e4497b200c8773e297040\/?VExpiration=1629118267&VSignature=46b7de55397edd1d30becc801878c7a4&a=1233&br=1738&bt=869&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=M3hqb2U6Znc2NzMzNzczM0ApMzY4PDo4NjtoN2c0NzY7ZmdvXnBvcjRvLTJgLS1kMTZzczJgYjJjYmM2YGE0XmI2YzU6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/cffd40a788f3ac41b2a65de588bd6cbd\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c002\/50f366d98a5e4497b200c8773e297040\/?a=1233&br=1738&bt=869&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=M3hqb2U6Znc2NzMzNzczM0ApMzY4PDo4NjtoN2c0NzY7ZmdvXnBvcjRvLTJgLS1kMTZzczJgYjJjYmM2YGE0XmI2YzU6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=c88f394e1ad74dec893f5e7f955e3c05"
								],
								"width": 720,
								"height": 720
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lower_540_0"
						},
						{
							"play_addr": {
								"file_cs": "c:0-9390-4e14",
								"uri": "v09044g40000c4530trc77ubrlsgaur0",
								"url_list": [
									"https:\/\/v21-us.tiktokcdn.com\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/9350419ff38e4139834a7d6fb5894680\/?VExpiration=1629118267&VSignature=675d6aef3d255d0a83ee42399140e9fe&a=1233&br=1246&bt=623&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=M3hqb2U6Znc2NzMzNzczM0ApNDlnM2U1O2U4N2RnaGU4NmdvXnBvcjRvLTJgLS1kMTZzc2MvYF9iMmEtYmFeNjM2NDU6Yw%3D%3D&vl=&vr=",
									"https:\/\/v39-us.tiktokcdn.com\/50b92a6c6c375c70814500f91328351f\/611a5f3b\/video\/tos\/useast2a\/tos-useast2a-ve-0068c001\/9350419ff38e4139834a7d6fb5894680\/?a=1233&br=1246&bt=623&cd=0%7C0%7C0&ch=0&cr=0&cs=0&cv=1&dr=0&ds=6&er=&ft=uDl.cgJzInzEN3stB_M&l=202108160650570102451442254101B342&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=M3hqb2U6Znc2NzMzNzczM0ApNDlnM2U1O2U4N2RnaGU4NmdvXnBvcjRvLTJgLS1kMTZzc2MvYF9iMmEtYmFeNjM2NDU6Yw%3D%3D&vl=&vr=",
									"https:\/\/api-h2.tiktokv.com\/aweme\/v1\/play\/?video_id=v09044g40000c4530trc77ubrlsgaur0&line=0&is_play_url=1&source=PackSourceEnum_CHALLENGE_AWEME&file_id=3857b9e6d9aa4d5eb08d25be0bdc621f"
								],
								"width": 720,
								"height": 720,
								"url_key": "v09044g40000c4530trc77ubrlsgaur0_h264_540p_638282",
								"data_size": 790912,
								"file_hash": "6792e4258690e0ef8ff719656cc12261"
							},
							"is_h265": 0,
							"is_bytevc1": 0,
							"dub_infos": null,
							"gear_name": "lowest_540_0",
							"quality_type": 25,
							"bit_rate": 638282
						}
					],
					"is_h265": 0,
					"cdn_url_expired": 0,
					"need_set_token": false
				},
				"region": "US",
				"video_text": [],
				"nickname_position": null,
				"without_watermark": false,
				"origin_comment_ids": null,
				"anchors": null,
				"prevent_download": false,
				"share_info": {
					"share_url": "https:\/\/m.tiktok.com\/v\/6992456889573379334.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6992456889573379334&source=h5_m",
					"share_desc": "Check out Rachel Dincoff's video! #TikTok",
					"bool_persist": 0,
					"share_link_desc": "",
					"share_signature_desc": "",
					"share_weibo_desc": "TikTok: Make Every Second CountCheck out Rachel Dincoff’s video! #TikTok > ",
					"share_title": "Check out Rachel Dincoff’s video! #TikTok > ",
					"share_title_myself": "",
					"share_title_other": "",
					"share_signature_url": "",
					"share_quote": "",
					"share_desc_info": "TikTok: Make Every Second CountCheck out Rachel Dincoff’s video! #TikTok > "
				},
				"aweme_type": 0,
				"is_pgcshow": false,
				"text_extra": [
					{
						"hashtag_name": "tokyo2020",
						"hashtag_id": "20356237",
						"is_commerce": false,
						"start": 60,
						"end": 70,
						"type": 1
					},
					{
						"start": 71,
						"end": 85,
						"type": 1,
						"hashtag_name": "olympictiktok",
						"hashtag_id": "1704741461248006",
						"is_commerce": false
					},
					{
						"start": 86,
						"end": 95,
						"type": 1,
						"hashtag_name": "olympian",
						"hashtag_id": "2087230",
						"is_commerce": false
					}
				],
				"is_relieve": false,
				"item_comment_settings": 0,
				"with_promotional_music": false,
				"commerce_config_data": null,
				"share_url": "https:\/\/m.tiktok.com\/v\/6992456889573379334.html?u_code=0&preview_pb=0&language=en&_d=dk4e43gkjcg74h&share_item_id=6992456889573379334&source=h5_m",
				"duration": 9913,
				"risk_infos": {
					"risk_sink": false,
					"type": 0,
					"content": "",
					"vote": false,
					"warn": false
				},
				"uniqid_position": null,
				"is_hash_tag": 1,
				"collect_stat": 0,
				"challenge_position": null,
				"is_preview": 0,
				"have_dashboard": false,
				"is_story": 0,
				"mask_infos": [],
				"user_digged": 0,
				"is_vr": false,
				"item_react": 0,
				"geofencing_regions": null
			}
		],
		"cursor": 40,
		"has_more": 1,
		"status_code": 0
	}
}
```



#  免责声明
    有任何问题可交流学习  
    请勿使用本服务于商用  
    请勿使用本服务大量抓取  
    若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
    本人纯粹技术爱好，若侵犯贵公司的权益，请告知
