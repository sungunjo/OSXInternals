---
description: launchd
---

# CH.7 The Alpha and the Omega

Mac, i-Device 의 전원을 켜면 boot loader\(OS X: EFI, iOS: iBoot\)가 kernel을 찾아 시작한다. 그러나 kernel은 단지 service provider일 뿐 실제 application은 아니다. user mode application은 file, multimedia 및 user interaction이 풍부한 친숙한 user environment를 제공하기 위해 kernel primitive를 구축하여 system 상에서 실제 작업을 수행하는 application 이다.

이 모든 것은 **launchd** 로부터 시작된다.



## LAUNCHD

**launchd** 는 다른 UN\*X system들이 **init** 이라고 부르는 system call의 OS X 및 iOS version이다.   
이름은 다르지만 일반적 idea는 동일하다. user mode에서 시작된 첫 번째 process 이므로 system의 다른 모든 process를 직, 간접적으로 시작해야 한다.   
또한 init과는 다르게 OS X 및 iOS 특유의 기능도 추가되었다.



### Starting launchd

작성중...



## GUI SHELLS



## XPC



