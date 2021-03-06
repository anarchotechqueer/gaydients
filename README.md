# gaydients
gaydients is a collection of lgbtqiap+ gradients made with css. they help make the web gay. free and always will be.

view examples at [gaydients.lgbt](https://gaydients.lgbt)

## installation

install with npm:

```shell
npm install gaydients --save
```

install with yarn:

```shell
yarn add gaydients
```

## getting started
there's a few ways to use gaydients, depending on your use case.

if you're using any of the css-in-js flavors, the best way is to just import the styles as an object:

```JSX
import gaydients from 'gaydients';
```

this gives you access to each of values ready for you to use:
```JSX
{
  prideFlag: ...
  prideGradient: ...
  transFlag: ...
  transGradient: ...
  enbyFlag: ...
  enbyGradient: ...
  genderqueerFlag: ...
  genderqueerGradient: ...
  aceFlag: ...
  aceGradient: ...
  pansexualFlag: ...
  pansexualGradient: ...
  aroFlag: ...
  aroGradient: ...
  agenderFlag: ...
  agenderGradient: ...
  intersexFlag: ...
  intersexGradient: ...
  bisexualFlag: ...
  bisexualGradient: ...
  rainbowFlag: ...
  rainbowGradient: ...
  blackTransFlag: ...
  blackTransGradient: ...
  genderfluidFlag: ...
  genderfluidGradient: ...
}
```

you can also just import the ones you need:
```JSX
import {transFlag, enbyFlag} from 'gaydients';
```

## classes
there's also convenient classes you can use for default flags and gradients.

just import the sass:
```scss
@import "~gaydients/gaydients.scss";
```

| class name | description |
| ------ | ------ |
| .gaydient-pride-flag | pride flag background |
| .gaydient-pride-gradient | pride gradient background |
| .gaydient-trans-flag | trans flag background |
| .gaydient-trans-gradient | trans gradient background |
| .gaydient-enby-flag | enby flag background |
| .gaydient-enby-gradient | enby gradient background |
| .gaydient-genderqueer-flag | genderqueer flag background |
| .gaydient-genderqueer-gradient | genderqueer gradient background |
| .gaydient-ace-flag | ace flag background |
| .gaydient-ace-gradient | ace gradient background |
| .gaydient-rainbow-flag | pansexual flag background |
| .gaydient-pansexual-gradient | pansexual gradient background |
| .gaydient-aro-flag | aro flag background |
| .gaydient-aro-gradient | aro gradient background |
| .gaydient-agender-flag | agender flag background |
| .gaydient-agender-gradient | agender gradient background |
| .gaydient-intersex-flag | intersex flag background |
| .gaydient-intersex-gradient | intersex gradient background |
| .gaydient-bisexual-flag | bisexual flag background |
| .gaydient-bisexual-gradient | bisexual gradient background |
| .gaydient-rainbow-flag | rainbow flag background |
| .gaydient-rainbow-gradient | rainbow gradient background |
| .gaydient-black-trans-flag | Black trans flag background |
| .gaydient-black-trans-gradient | Black trans gradient background |
| .gaydient-genderfluid-flag | genderfluid flag background |
| .gaydient-genderfluid-gradient | genderfluid gradient background |

you can also set change the `.gaydient` class prefix by setting `$gaydients-class-prefix` to whatever you want.


## documentation
below are the available functions to build out flags.

### gaydient-pride
function used to generate pride flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $black | #000000 | black portion | hex |
| $brown | #72501E | purple portion | hex |
| $red | #ff0018 | red portion | hex |
| $orange | #ffa52c | orange portion | hex |
| $yellow | #ffff41 | yellow portion | hex |
| $green  | #008018 | green portion | hex |
| $blue | #0000f9 | blue portion | hex |
| $purple | #86007d | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-pride-black: ...
$gaydients-pride-brown: ...
$gaydients-pride-red: ...
$gaydients-pride-orange: ...
$gaydients-pride-yellow: ...
$gaydients-pride-green: ...
$gaydients-pride-blue: ...
$gaydients-pride-purple: ...
$gaydients-pride-opacity: ...
$gaydients-pride-degrees: ...
$gaydients-pride-chunk: ...
```

### gaydient-trans
function used to generate trans flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $blue | #55cdfc | blue portion | hex |
| $pink | #f7a8b8 | pink portion | hex |
| $white | #fff | white portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-trans-blue: ...
$gaydients-trans-pink: ...
$gaydients-trans-white: ...
$gaydients-trans-opacity: ...
$gaydients-trans-degrees: ...
$gaydients-trans-chunk: ...
```

### gaydient-enby
function used to generate non-binary flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $yellow | #fff433 | yellow portion | hex |
| $white | #fff | white portion | hex |
| $purple | #9b59d0 | purple portion | hex |
| $black | #000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-enby-yellow: ...
$gaydients-enby-white: ...
$gaydients-enby-purple: ...
$gaydients-enby-black: ...
$gaydients-enby-opacity: ...
$gaydients-enby-degrees: ...
$gaydients-enby-chunk: ...
```

### gaydient-genderqueer
function used to generate genderqueer flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $lavender | #b77fdd | lavendar portion | hex |
| $white | #fff | white portion | hex |
| $green | #48821e | green portion | hex |
| $black | #000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-genderqueer-lavender: ...
$gaydients-genderqueer-white: ...
$gaydients-genderqueer-green: ...
$gaydients-genderqueer-opacity: ...
$gaydients-genderqueer-degrees: ...
$gaydients-genderqueer-chunk: ...
```

### gaydient-ace
function used to generate ace flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $black | #000 | black portion | hex |
| $grey | #a4a4a4 | grey portion | hex |
| $white | #fff | white portion | hex |
| $purple | #810081 | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-ace-black: ...
$gaydients-ace-grey: ...
$gaydients-ace-white: ...
$gaydients-ace-purple: ...
$gaydients-ace-opacity: ...
$gaydients-ace-degrees: ...
$gaydients-ace-chunk: ...
```

### gaydient-pansexual
function used to generate pansexual flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $pink | #ff1b8d | pink portion | hex |
| $yellow | #ffda00 | yellow portion | hex |
| $blue | #1bb3ff | blue portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-pansexual-pink: ...
$gaydients-pansexual-yellow: ...
$gaydients-pansexual-blue: ...
$gaydients-pansexual-opacity: ...
$gaydients-pansexual-degrees: ...
$gaydients-pansexual-chunk: ...
```

### gaydient-aro
function used to generate aro flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $green | #3aa63f | green portion | hex |
| $lightgreen | #a8d47a | light green portion | hex |
| $white | #ffffff | white portion | hex |
| $grey | #aaaaaa | grey portion | hex |
| $black | #000000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-aro-green: ...
$gaydients-aro-lightgreen: ...
$gaydients-aro-white: ...
$gaydients-aro-grey: ...
$gaydients-aro-black: ...
$gaydients-aro-opacity: ...
$gaydients-aro-degrees: ...
$gaydients-aro-chunk: ...
```

### gaydient-agender
function used to generate agender flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $black | #000000 | black portion | hex |
| $white | #a8d47a | white green portion | hex |
| $grey | #a4a4a4 | grey portion | hex |
| $purple | #810081 | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-agender-black: ...
$gaydients-agender-grey: ...
$gaydients-agender-white: ...
$gaydients-agender-green: ...
$gaydients-agender-opacity: ...
$gaydients-agender-degrees: ...
$gaydients-agender-chunk: ...
```

### gaydient-intersex
function used to generate intersex flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $yellow | #ffda00 | yellow portion | hex |
| $purple | #7a00ac | purple green portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |
| $flag | true | determines whether to render a flag or gradient | bool |

these defaults are set through the following variables:
```scss
$gaydients-intersex-yellow: ...
$gaydients-intersex-purple: ...
$gaydients-intersex-opacity: ...
$gaydients-intersex-degrees: ...
$gaydients-intersex-chunk: ...
$gaydients-intersex-flag: ...
```

### gaydient-bisexual
function used to generate bisexual flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $pink | #d60270 | pink portion | hex |
| $purple | #9b4f96 | purple green portion | hex |
| $blue | #0038a8 | blue portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

```scss
$gaydients-bisexual-pink: ...
$gaydients-bisexual-purple: ...
$gaydients-bisexual-blue: ...
$gaydients-bisexual-opacity: ...
$gaydients-bisexual-degrees: ...
$gaydients-bisexual-chunk: ...
```

### gaydient-rainbow
function used to generate rainbow flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $red | #ff0018 | red portion | hex |
| $orange | #ffa52c | orange portion | hex |
| $yellow | #ffff41 | yellow portion | hex |
| $green  | #008018 | green portion | hex |
| $blue | #0000f9 | blue portion | hex |
| $purple | #86007d | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-rainbow-red: ...
$gaydients-rainbow-orange: ...
$gaydients-rainbow-yellow: ...
$gaydients-rainbow-green: ...
$gaydients-rainbow-blue: ...
$gaydients-rainbow-purple: ...
$gaydients-rainbow-opacity: ...
$gaydients-rainbow-degrees: ...
$gaydients-rainbow-chunk: ...
```

### gaydient-black-trans
function used to generate black trans flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $blue | #55cdfc | blue portion | hex |
| $pink | #f7a8b8 | pink portion | hex |
| $black | #000000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-black-trans-blue: ...
$gaydients-black-trans-pink: ...
$gaydients-black-trans-black: ...
$gaydients-black-trans-opacity: ...
$gaydients-black-trans-degrees: ...
$gaydients-black-trans-chunk: ...
```

### gaydient-genderfluid
function used to generate genderfluid flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $pink | #FD74A0 | pink portion | hex |
| $white | #FFFFFF | pink portion | hex |
| $purple | #BE17D7 | black portion | hex |
| $black | #000000 | black portion | hex |
| $blue | #313DBB | blue portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

these defaults are set through the following variables:
```scss
$gaydients-genderfluid-pink: ...
$gaydients-genderfluid-white: ...
$gaydients-genderfluid-purple: ...
$gaydients-genderfluid-black: ...
$gaydients-genderfluid-blue: ...
$gaydients-genderfluid-opacity: ...
$gaydients-genderfluid-degrees: ...
$gaydients-genderfluid-chunk: ...
```

## notes
customizing the gradients for your exact specifications probably involves using both the sass to use the built-in functions and importing your custom values to js for best practices.

## contributing
there's lots of flags missing! please submit pull requests for new flags, or issues to request specific flags.

## license
this is licensed under [GNU GPLv3](https://github.com/anarchotechqueer/gaydients/blob/main/LICENSE)

## change log
| version | change |
| ------ | ------ |
| 1.0.4 | add genderqueer flag. |
| 1.0.3 | add missing classes.  |
| 1.0.2 | add pride flag. add Black trans flag. |
| 1.0.1 | create file for variables. make all default values variables. |


## shout out
shout out to the person who owns [gaydients.com](https://gaydients.com/). i ran across this after building this trying to get a domain name.
