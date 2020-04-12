# Fitness Camera

Turn your phone camera into a fitness tracker.

## Description

This is an Android application that uses human pose estimation with TensorFlow Lite to detect and count exercises using your phone's front-facing camera.

## Installation

Fitness Camera v0.1.0 is now available for Android!

[Click here to download and install the APK](https://github.com/miguelrochefort/fitness-camera/releases/download/v0.1.0/fitnesscamera-20200412T0154.apk)

*Note: All processing is done locally on your device. Nothing is ever sent to a server. In fact, the app doesn't even have permissions to access the Internet.*

## Demo

[See the full video on YouTube](https://www.youtube.com/watch?v=Jdan-ZHiL6I)

![](https://i.imgur.com/ej0EFiG.gif)

## Under the hood

[Google Colab notebook with human pose estimation data](https://colab.research.google.com/drive/1OHTsNyr3Ry_bSw8dT9s77BZsXHe7i8HR#scrollTo=uIbljMew7Wje)

![](https://i.imgur.com/PYanU09.png)

## Background

This was built in the context of [Pioneer's Hackathon](https://pioneer.app/hackathon).

Make sure to check-out my [Frontier post](https://frontier.pioneer.app/posts/135-fitness-camera) and leave a comment!

## Related work

* [Onyx](https://www.onyx.fit/)
* [Tempo](https://tempo.fit/product)
* [GymCam](https://www.cmu.edu/news/stories/archives/2019/september/gymcam.html)
* [Live Repetition Counting](https://www.cs.tau.ac.il/~wolf/papers/repcounticcv.pdf) [PDF]

## License

[Apache License 2.0](LICENSE)

## Acknowledgments

This is a fork of the [TensorFlow Examples](https://github.com/tensorflow/examples) repository.
