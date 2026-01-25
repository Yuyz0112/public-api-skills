# stream Schemas

158 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [stream_accessRules](stream-accessRules.md) | object | Defines rules for fine-grained control over conten |
| [stream_account_identifier](stream-account-identifier.md) | primitive | The account identifier tag. |
| [stream_addAudioTrackResponse](stream-addAudioTrackResponse.md) | allOf |  |
| [stream_additionalAudio](stream-additionalAudio.md) | object |  |
| [stream_allowedOrigins](stream-allowedOrigins.md) | array | Lists the origins allowed to display the video. En |
| [stream_api-response-common](stream-api-response-common.md) | object |  |
| [stream_api-response-common-failure](stream-api-response-common-failure.md) | object |  |
| [stream_api-response-single](stream-api-response-single.md) | allOf |  |
| [stream_asc](stream-asc.md) | primitive | Lists videos in ascending order of creation. |
| [stream_audio_default](stream-audio-default.md) | primitive | Denotes whether the audio track will be played by  |
| [stream_audio_identifier](stream-audio-identifier.md) | primitive | The unique identifier for an additional audio trac |
| [stream_audio_label](stream-audio-label.md) | primitive | A string to uniquely identify the track amongst ot |
| [stream_audio_state](stream-audio-state.md) | enum | Specifies the processing status of the video. |
| [stream_caption_basic_upload](stream-caption-basic-upload.md) | object |  |
| [stream_caption_status](stream-caption-status.md) | enum | The status of a generated caption. |
| [stream_captions](stream-captions.md) | object |  |
| [stream_clipResponseSingle](stream-clipResponseSingle.md) | allOf |  |
| [stream_clipped_from_video_uid](stream-clipped-from-video-uid.md) | primitive | The unique video identifier (UID). |
| [stream_clipping](stream-clipping.md) | object |  |
| [stream_clipping_created](stream-clipping-created.md) | primitive | The date and time the clip was created. |
| [stream_copyAudioTrack](stream-copyAudioTrack.md) | object |  |
| [stream_create_input_request](stream-create-input-request.md) | object |  |
| [stream_create_output_request](stream-create-output-request.md) | object |  |
| [stream_created](stream-created.md) | primitive | The date and time the media item was created. |
| [stream_creator](stream-creator.md) | primitive | A user-defined identifier for the media creator. |
| [stream_deleted_response](stream-deleted-response.md) | allOf |  |
| [stream_direct_upload_request](stream-direct-upload-request.md) | object |  |
| [stream_direct_upload_response](stream-direct-upload-response.md) | allOf |  |
| [stream_direct_user](stream-direct-user.md) | primitive | Provisions a URL to let your end users upload vide |
| [stream_download_percent_complete](stream-download-percent-complete.md) | primitive | Indicates the progress as a percentage between 0 a |
| [stream_download_status](stream-download-status.md) | enum | The status of a generated download. |
| [stream_download_type](stream-download-type.md) | enum | The type of downloads available are: `default`, `a |
| [stream_download_url](stream-download-url.md) | primitive | The URL to access the generated download. |
| [stream_downloadedFrom](stream-downloadedFrom.md) | primitive | The source URL for a downloaded image. If the wate |
| [stream_downloads](stream-downloads.md) | object |  |
| [stream_downloads_response](stream-downloads-response.md) | allOf |  |
| [stream_downloads_response_single](stream-downloads-response-single.md) | allOf |  |
| [stream_duration](stream-duration.md) | primitive | The duration of the video in seconds. A value of ` |
| [stream_editAudioTrack](stream-editAudioTrack.md) | object |  |
| [stream_end](stream-end.md) | primitive | Lists videos created before the specified date. |
| [stream_end_time_seconds](stream-end-time-seconds.md) | primitive | Specifies the end time for the video clip in secon |
| [stream_errorReasonCode](stream-errorReasonCode.md) | primitive | Specifies why the video failed to encode. This fie |
| [stream_errorReasonText](stream-errorReasonText.md) | primitive | Specifies why the video failed to encode using a h |
| [stream_generated_caption](stream-generated-caption.md) | primitive | Whether the caption was generated via AI. |
| [stream_height](stream-height.md) | primitive | The height of the image in pixels. |
| [stream_identifier](stream-identifier.md) | primitive | A Cloudflare-generated unique identifier for a med |
| [stream_include_counts](stream-include-counts.md) | primitive | Includes the total number of videos associated wit |
| [stream_input](stream-input.md) | object |  |
| [stream_input_rtmps](stream-input-rtmps.md) | object | Details for streaming to an live input using RTMPS |
| [stream_input_rtmps_stream_key](stream-input-rtmps-stream-key.md) | primitive | The secret key to use when streaming via RTMPS to  |
| [stream_input_rtmps_url](stream-input-rtmps-url.md) | primitive | The RTMPS URL you provide to the broadcaster, whic |
| [stream_input_srt](stream-input-srt.md) | object | Details for streaming to a live input using SRT. |
| [stream_input_srt_stream_id](stream-input-srt-stream-id.md) | primitive | The identifier of the live input to use when strea |
| [stream_input_srt_stream_passphrase](stream-input-srt-stream-passphrase.md) | primitive | The secret key to use when streaming via SRT to a  |
| [stream_input_srt_url](stream-input-srt-url.md) | primitive | The SRT URL you provide to the broadcaster, which  |
| [stream_input_webrtc](stream-input-webrtc.md) | object | Details for streaming to a live input using WebRTC |
| [stream_input_webrtc_url](stream-input-webrtc-url.md) | primitive | The WebRTC URL you provide to the broadcaster, whi |
| [stream_jwk](stream-jwk.md) | primitive | The signing key in JWK format. |
| [stream_key_generation_response](stream-key-generation-response.md) | allOf |  |
| [stream_key_response_collection](stream-key-response-collection.md) | allOf |  |
| [stream_keys](stream-keys.md) | object |  |
| [stream_label](stream-label.md) | primitive | The language label displayed in the native languag |
| [stream_language](stream-language.md) | primitive | The language tag in BCP 47 format. |
| [stream_language_response_collection](stream-language-response-collection.md) | allOf |  |
| [stream_language_response_single](stream-language-response-single.md) | allOf |  |
| [stream_listAudioTrackResponse](stream-listAudioTrackResponse.md) | allOf |  |
| [stream_liveInput](stream-liveInput.md) | primitive | The live input ID used to upload a video with Stre |
| [stream_live_input](stream-live-input.md) | object | Details about a live input. |
| [stream_live_input_created](stream-live-input-created.md) | primitive | The date and time the live input was created. |
| [stream_live_input_default_creator](stream-live-input-default-creator.md) | primitive | Sets the creator ID asssociated with this live inp |
| [stream_live_input_identifier](stream-live-input-identifier.md) | primitive | A unique identifier for a live input. |
| [stream_live_input_metadata](stream-live-input-metadata.md) | object | A user modifiable key-value store used to referenc |
| [stream_live_input_modified](stream-live-input-modified.md) | primitive | The date and time the live input was last modified |
| [stream_live_input_object_without_url](stream-live-input-object-without-url.md) | object |  |
| [stream_live_input_recording_allowedOrigins](stream-live-input-recording-allowedOrigins.md) | array | Lists the origins allowed to display videos create |
| [stream_live_input_recording_deletion](stream-live-input-recording-deletion.md) | primitive | Indicates the number of days after which the live  |
| [stream_live_input_recording_hideLiveViewerCount](stream-live-input-recording-hideLiveViewerCount.md) | primitive | Disables reporting the number of live viewers when |
| [stream_live_input_recording_mode](stream-live-input-recording-mode.md) | enum | Specifies the recording behavior for the live inpu |
| [stream_live_input_recording_requireSignedURLs](stream-live-input-recording-requireSignedURLs.md) | primitive | Indicates if a video using the live input has the  |
| [stream_live_input_recording_settings](stream-live-input-recording-settings.md) | object | Records the input to a Cloudflare Stream video. Be |
| [stream_live_input_recording_timeoutSeconds](stream-live-input-recording-timeoutSeconds.md) | primitive | Determines the amount of time a live input configu |
| [stream_live_input_response_collection](stream-live-input-response-collection.md) | allOf |  |
| [stream_live_input_response_single](stream-live-input-response-single.md) | allOf |  |
| [stream_live_input_status](stream-live-input-status.md) | enum | The connection status of a live input. |
| [stream_maxDurationSeconds](stream-maxDurationSeconds.md) | primitive | The maximum duration in seconds for a video upload |
| [stream_media_metadata](stream-media-metadata.md) | object | A user modifiable key-value store used to referenc |
| [stream_media_state](stream-media-state.md) | enum | Specifies the processing status for all quality le |
| [stream_media_status](stream-media-status.md) | object | Specifies a detailed status for a video. If the `s |
| [stream_messages](stream-messages.md) | array |  |
| [stream_modified](stream-modified.md) | primitive | The date and time the media item was last modified |
| [stream_name](stream-name.md) | primitive | A short description of the watermark profile. |
| [stream_notificationUrl](stream-notificationUrl.md) | primitive | The URL where webhooks will be sent. |
| [stream_oneTimeUploadExpiry](stream-oneTimeUploadExpiry.md) | primitive | The date and time when the video upload URL is no  |
| [stream_opacity](stream-opacity.md) | primitive | The translucency of the image. A value of `0.0` ma |
| [stream_output](stream-output.md) | object |  |
| [stream_output_enabled](stream-output-enabled.md) | primitive | When enabled, live video streamed to the associate |
| [stream_output_identifier](stream-output-identifier.md) | primitive | A unique identifier for the output. |
| [stream_output_response_collection](stream-output-response-collection.md) | allOf |  |
| [stream_output_response_single](stream-output-response-single.md) | allOf |  |
| [stream_output_streamKey](stream-output-streamKey.md) | primitive | The streamKey used to authenticate against an outp |
| [stream_output_url](stream-output-url.md) | primitive | The URL an output uses to restream. |
| [stream_padding](stream-padding.md) | primitive | The whitespace between the adjacent edges (determi |
| [stream_pctComplete](stream-pctComplete.md) | primitive | Indicates the progress as a percentage between 0 a |
| [stream_pem](stream-pem.md) | primitive | The signing key in PEM format. |
| [stream_playback](stream-playback.md) | object |  |
| [stream_playback_rtmps](stream-playback-rtmps.md) | object | Details for playback from an live input using RTMP |
| [stream_playback_rtmps_stream_key](stream-playback-rtmps-stream-key.md) | primitive | The secret key to use for playback via RTMPS. |
| [stream_playback_rtmps_url](stream-playback-rtmps-url.md) | primitive | The URL used to play live video over RTMPS. |
| [stream_playback_srt](stream-playback-srt.md) | object | Details for playback from an live input using SRT. |
| [stream_playback_srt_stream_id](stream-playback-srt-stream-id.md) | primitive | The identifier of the live input to use for playba |
| [stream_playback_srt_stream_passphrase](stream-playback-srt-stream-passphrase.md) | primitive | The secret key to use for playback via SRT. |
| [stream_playback_srt_url](stream-playback-srt-url.md) | primitive | The URL used to play live video over SRT. |
| [stream_playback_webrtc](stream-playback-webrtc.md) | object | Details for playback from a live input using WebRT |
| [stream_playback_webrtc_url](stream-playback-webrtc-url.md) | primitive | The URL used to play live video over WebRTC. |
| [stream_position](stream-position.md) | primitive | The location of the image. Valid positions are: `u |
| [stream_preview](stream-preview.md) | primitive | The video's preview page URI. This field is omitte |
| [stream_readyToStream](stream-readyToStream.md) | primitive | Indicates whether the video is playable. The field |
| [stream_readyToStreamAt](stream-readyToStreamAt.md) | primitive | Indicates the time at which the video became playa |
| [stream_requireSignedURLs](stream-requireSignedURLs.md) | primitive | Indicates whether the video can be a accessed usin |
| [stream_scale](stream-scale.md) | primitive | The size of the image relative to the overall size |
| [stream_scheduledDeletion](stream-scheduledDeletion.md) | primitive | Indicates the date and time at which the video wil |
| [stream_schemas-identifier](stream-schemas-identifier.md) | primitive | Identifier. |
| [stream_search](stream-search.md) | primitive | Provides a partial word match of the `name` key in |
| [stream_signed_token_request](stream-signed-token-request.md) | object |  |
| [stream_signed_token_response](stream-signed-token-response.md) | allOf |  |
| [stream_signing_key_created](stream-signing-key-created.md) | primitive | The date and time a signing key was created. |
| [stream_size](stream-size.md) | primitive | The size of the media item in bytes. |
| [stream_start](stream-start.md) | primitive | Lists videos created after the specified date. |
| [stream_start_time_seconds](stream-start-time-seconds.md) | primitive | Specifies the start time for the video clip in sec |
| [stream_storage_use_response](stream-storage-use-response.md) | allOf |  |
| [stream_thumbnailTimestampPct](stream-thumbnailTimestampPct.md) | primitive | The timestamp for a thumbnail image calculated as  |
| [stream_thumbnail_url](stream-thumbnail-url.md) | primitive | The media item's thumbnail URI. This field is omit |
| [stream_tus_resumable](stream-tus-resumable.md) | enum | Specifies the TUS protocol version. This value mus |
| [stream_type](stream-type.md) | primitive | Specifies whether the video is `vod` or `live`. |
| [stream_update_input_request](stream-update-input-request.md) | object |  |
| [stream_update_output_request](stream-update-output-request.md) | object |  |
| [stream_upload_length](stream-upload-length.md) | primitive | Indicates the size of the entire upload in bytes.  |
| [stream_upload_metadata](stream-upload-metadata.md) | primitive | Comma-separated key-value pairs following the TUS  |
| [stream_uploaded](stream-uploaded.md) | primitive | The date and time the media item was uploaded. |
| [stream_videoClipStandard](stream-videoClipStandard.md) | object |  |
| [stream_video_copy_request](stream-video-copy-request.md) | object |  |
| [stream_video_name](stream-video-name.md) | primitive | Provides a fast, exact string match on the `name`  |
| [stream_video_response_collection](stream-video-response-collection.md) | allOf |  |
| [stream_video_response_single](stream-video-response-single.md) | allOf |  |
| [stream_video_update](stream-video-update.md) | object |  |
| [stream_videos](stream-videos.md) | object |  |
| [stream_watermarkAtUpload](stream-watermarkAtUpload.md) | object |  |
| [stream_watermark_at_upload](stream-watermark-at-upload.md) | object |  |
| [stream_watermark_basic_upload](stream-watermark-basic-upload.md) | object |  |
| [stream_watermark_created](stream-watermark-created.md) | primitive | The date and a time a watermark profile was create |
| [stream_watermark_identifier](stream-watermark-identifier.md) | primitive | The unique identifier for a watermark profile. |
| [stream_watermark_response_collection](stream-watermark-response-collection.md) | allOf |  |
| [stream_watermark_response_single](stream-watermark-response-single.md) | allOf |  |
| [stream_watermark_size](stream-watermark-size.md) | primitive | The size of the image in bytes. |
| [stream_watermarks](stream-watermarks.md) | object |  |
| [stream_webhook_request](stream-webhook-request.md) | object |  |
| [stream_webhook_response_single](stream-webhook-response-single.md) | allOf |  |
| [stream_width](stream-width.md) | primitive | The width of the image in pixels. |
