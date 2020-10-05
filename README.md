# scss-base

## 광범위하게 사용가능한 scss base 제작

!프로젝트에 적용할 때, 세세한 조정 필수!

### base

```
  -base
    =reset custom...
    기본적인 reset 추가
  -helper
    =common class
    자주쓰이는 class 추가
  -typo
    =font-face...
    폰트 설정과 관련된 부분 추가
    자주 쓰는 폰트들 추가
    쓰이지 않는 폰트 및 폰트페이스 삭제해서 사용
```

### component

```
  -component styles
    =card, list, input, animation...
    비슷한 상태로 쓰이는 button 추가
    비슷한 상태로 쓰이는 form 추가
```

### layout

```
  -layout styles
    haeder, footer, l-~...
    layout.scss 추가
    header.scss 추가(fixed되는 큰 틀만 추가)
      header-wrap 안쪽의 header가 픽스드되는 구조로,
      header 안으로 contents가 자리잡음.
    이외의 레이아웃은 프로젝트별 상이하기에 추가하지 않음
```

### page

```
  -page contant styles
    =main, cs, auth, enroll, mypage...
    프로젝트별 상이하기때문에 추가하지 않음
```

### utility

```
  -variable
  -mixin
  -function
  자주 쓰이는 상태를 추가하고, 프로젝트별 쓰이지 않는 부분을 삭제하여 사용
```

### vendor

```
  -output styles
    =reset, normalise, slick, swiper...
    프로젝트별 적용할 부분이 다르므로 추가하지 않음
```
