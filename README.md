`
ffmpeg -f lavfi -i color=size=640x480:duration=5:rate=25:color=blue -i ~/Downloads/01-White-Noise-10min.mp3 -vf "drawtext=fontfile=~/Downloads/ConsolaR.ttf:fontsize=30:fontcolor=white:x=(w-text_w)/2:y=(h-text_h)/2:text='video6'" -c:a copy -shortest video6.mp4
`
