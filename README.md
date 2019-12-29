![Image](/pic/shyshark_banner.png)
# ShyShark 🦈
ShyShark is Swipeable card stack view like Tinder.
I tried to implement it simply. You can easily fix this.

## What's New in 0.0.1? :tada:
- [Release] Release ShyShark :tada:

## Result Screen

| Project Name | Result Screen   |
|:---------:|---|
| Sample  |  <img src="/pic/sample.gif"> |

## How to Use

### Gradle

Preparing

#### attribute

|      Attribute Name        | Description                               |       Default Value      |
|:--------------------------:|-------------------------------------------|:------------------------:|
|       swipeableFlag        | Swipeable direction                       | LEFT, RIGHT, TOP, BOTTOM |
|        preloadCount        | Preloaded item count                      |             3            |
|          scaleGap          | Scale gap per item                        |            0.1f          |
|        dragThrashold       | Trashold value passed by drag             |            0.4f          |
|       defaultElevation     | z-axis value                              |             0f           |
|     restoreScaleAnimationDuration    | Card restore animation duration |            200L          |
|     autoDraggingAnimationDuration    | Animation duration automatically dragged |   200L          |

*defaultElevation : If the view itself has an elevation value, it will have that value as default.
If the elevation value of the view itself is larger than the setting value, the setting value is ignored.*

# Contribute
Welcome any contributions.

# License

    Copyright 2020 Sabujak-Sabujak

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
