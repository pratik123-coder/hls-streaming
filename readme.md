ffmpeg -i sample.mp4 -codec:v libx264 -codec:a aac -hls_time 10 -hls_playlist_type vod -hls_segment_filename outputs/segment%03d.ts -start_number 0 outputs/index.m3u8

run this command in docker deamon