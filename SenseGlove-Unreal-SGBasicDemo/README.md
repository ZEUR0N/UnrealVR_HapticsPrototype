# SGBasicDemo

A basic Blueprint demo demonstrating basic functionality such as grab/release, touch with buzz and force-feedback, etc using [the SenseGlove Unreal Engine Plugin](https://www.unrealengine.com/marketplace/en-US/product/the-senseglove-unreal-engine-plugin).

## Compability

This demo was created with Unreal Engine 5.2 and requires [the SenseGlove Unreal Engine Plugin >= 1.4.0](https://dev.azure.com/SenseGlove/_git/SenseGlove-Unreal/tags).

## Video Tutorial

There is [a video tutorial on how to create this demo from scratch](https://www.youtube.com/watch?v=jN4VcfXVrTA) available on [the SenseGlove Youtube channel](https://www.youtube.com/@senseglove4021). Also, there is a relevant short video on [how to check the required plugin version](https://www.youtube.com/watch?v=iF0JU2kpNhw) that you might want to check out.

## How to checkout

There are a few video tutorials available on how to set up the  [the SenseGlove Unreal Engine Plugin](https://www.unrealengine.com/marketplace/en-US/product/the-senseglove-unreal-engine-plugin) either through Epic's Marketplace or Microsoft Azure DevOps repositories. You may want to checkout those video and avoid the instructions below. Otherwise, continue reading.

Here are the video tutorials:

- [Plugin installation guide for Microsoft Windows](https://www.youtube.com/watch?v=QqWeRHNceqY&t=10s)
- [C++ & Blueprint examples for Microsoft Windows](https://www.youtube.com/watch?v=qRaNOc3OHqU)
- [Plugin and examples installation guide for GNU/Linux](https://www.youtube.com/watch?v=1T7LAGp3e6I)

This repository tracks [the official SenseGlove API for Unreal Engine](https://dev.azure.com/SenseGlove/SenseGlove-Unreal) as a Git submodule. It also relies on Git LFS for tracking binary assets. Thus, in order to to clone this repository you need either have a version of Git with support for those features, or you can always use the 'kebab' (three vertical dots) menu next to the clone button, in order to download the whole repository including LFS objects as a unified zip file.

__IMPORTANT NOTE__: This repository relies on Git LFS for storing binary blobs (e.g. third-party libraries). Sadly, there is a known issue with Microsoft Azure public LFS repositories that requires credential for LFS checkouts on https (LFS ssh checkouts are not supported at all). Unless, you are part of SenseGlove organization on Microsoft Azure there is no easy way to fully clone this repository using Git. Thus, the best way to download this repository is to use the 'kebab' (three vertical dots) menu next to the clone button, in order to download the whole repository including LFS objects as a unified zip file. You'll also have to either install the underlying [SenseGlove Plugin for Unreal Engine](https://dev.azure.com/SenseGlove/_git/SenseGlove-Unreal) into your engine installation, or download it manually, and extract it to the Plugins folder in the current project.

In case you are a member of SenseGlove organization on Azure DevOps, in order to check out the complete source code and assets, and also the underlying [SenseGlove Plugin for Unreal Engine](https://dev.azure.com/SenseGlove/_git/SenseGlove-Unreal), use the following instructions:

```
git clone --recursive --jobs 16 https://SenseGlove@dev.azure.com/SenseGlove/SenseGlove-Unreal-SGBasicDemo/_git/SenseGlove-Unreal-SGBasicDemo SGBasicDemo
```

## License

```
MIT License

Copyright (c) 2020 - 2023 SenseGlove

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
