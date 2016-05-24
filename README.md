Mock Codec
==========

Mock implementations of the Alfalfa coder/decoder, built with ffmpeg.

   * `import`: convert arbitrary input on stdin
     	       to raw video (yuv4mpegpipe) on stdout

     Example: `./import <example.vp8 >example.y4m`

   * `encode`: convert raw video (yuv4mpegpipe) on stdin
     	       to VP8 on stdout

     Example: `./encode <example.y4m >example-compressed.vp8`

   * `decode`: convert VP8 video on stdin
     	       to raw video (yuv4mpegpipe) on stdout

     (Similar to `import`, but requires the input to be in VP8 IVF format.)

     Example: `./decode <example.vp8 >example.y4m`

   * `watch`:  play raw video (yuv4mpegpipe) from stdin on X display

     Example: `./watch <example.y4m`

   * `example.vp8`: sample VP8 (IVF) file for testing
