https://unix.stackexchange.com/questions/28803/how-can-i-reduce-a-videos-size-with-ffmpeg
ffmpeg -i input.mkv -vf "scale=iw/2:ih/2" half_the_frame_size.mkv
ffmpeg -i input.mkv -vf "scale=iw/3:ih/3" a_third_the_frame_size.mkv
ffmpeg -i input.mkv -vf "scale=iw/4:ih/4" a_fourth_the_frame_size.mkv
