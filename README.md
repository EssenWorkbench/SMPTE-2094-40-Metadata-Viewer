# SMPTE-2094-40-Metadata-Viewer

This is a modification version of the hevcesbrowser project to show the embedded SMPTE.20904-40 dynamic metadata within HEVC element stream.
In order to utilize this tool, you need to extract the HEVC element stream from container.
for example ) ./ffmpeg -i your_input_file.mp4 -vcodec copy -an desired_video_file.h265
