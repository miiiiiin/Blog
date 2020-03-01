---
title: iOS 13 background에서의 User Location Update 해결기
date: 2020-02-14 13:02:09
category: development
draft: false
---


iOS 13 background에서의 User Location Update


iOS 13이 발표된지 몇 달 지나서 조금 늦었지만 디바이스 위치 업데이트가 필요한 앱을 만들면서 알게된 위치 권한 정책, 그리고 대응 방법에 대해 정리해보려고 합니다.

iOS 13부터는 사용자의 개인정보를 보다 투명하고 직접적으로 관리할 수 있게끔 바뀌었습니다. 추가 정보는 작년도 WWDC 영상에서 확인해보실 수 있습니다! https://developer.apple.com/videos/play/wwdc2019/705/


기존의 위치 권한 상태에서 크게 바뀐 부분은 바로 Temporary Authorization이 추가되었다는 점이네요.
