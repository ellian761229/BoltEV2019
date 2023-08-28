# 양민님, 태하님 버전을 기반으로 longitudinal control 부분을 
# 제 상황에 맞게 튜닝하여 만든 구형볼트용 0814 마지막 버전입니다.
# 항상 전방을 주시하시고 안전 운전에 만전을 기해주시기 바랍니다.
# 이 버전의 원위치는 
# https://github.com/sunnyc-op/openpilot/tree/bolt_0814_eon
# 오픈파일럿 비전문가^^;;  DS5AJD 분주한호랑이 백



--------------------------------<아래 내용은 comma2_Eon-final 버전 내용임>---------------------------------------

### 0.8.14부터 @neokii님의 HKG향 코드를 기반으로 하고있습니다. 항상 감사드립니다.
### pedal 사용자의 경우 옵션에서 켜주셔야합니다 꼭.



- hanabi95(@hanabi95) 님의 작업에서 safety 밑 can 관련 내용을 기본으로 하고 있습니다. 항상 감사드립니다.
- lat_icon_image, thanks to @Hammie K 
- screenrecorder, thanks to neokii

ALL existing Bolt ports, as well as most GM giraffes,GM harnesses and GM Pedals, pedal firmware changes, panda code changes are derived from the original port created by Jason Shuler

### 문의사항은 오카방 혹은 이슈 생성으로 주십시오. 감사합니다.
working tested : BoltEV premier 2017, 2018, 2019
rkjnice@gmail.com

---
# for only  BoltEV + Comma3 Openpilot forks
### if you're using comma2 or Eon(Lepro, .. ), please use  comma2_Eon-final branch.
### if you're unfamilier with git manifulation, do use "develop" or "release" branch. it will be get updated as stable as. (maybe .. )
### from 0.8.14, many codes from Hyundai-kia fork from @neokii, thx for @neokii
### ir you want using CommaPedal with this fork, you have to use "metric unit system" and turn on "CommaPedal" in toggles. AND  you must drive in "L" gear at BOLT.

ALL existing Bolt ports, as well as most GM giraffes,GM harnesses and GM Pedals, pedal firmware changes, panda code changes are derived from the original port created by Jason Shuler

any issues are welcomes.
working tested : BoltEV premier 2017, 2018, 2019

[Wanna be a Donator ?](https://jc01rho.com/donation/) [![wanna be a Donator?](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://jc01rho.com/donation/)

## use this fork AT YOUR OWN RISK :)
