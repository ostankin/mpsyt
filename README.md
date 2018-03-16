This Docker image extends [`rothgar/mpsyt`](https://hub.docker.com/r/rothgar/mpsyt/) by including `youtube-dl` package, which fixes most of the problems with playback of large videos (see [Sorry, this track is not available" for everything](https://github.com/mps-youtube/mps-youtube/issues/690)).

Run with:
```
docker run --device /dev/snd -it --rm --name mpsyt ostankin/mpsyt
```

For more details see the page of the original project, [`mps-youtube`](https://github.com/mps-youtube/mps-youtube).
