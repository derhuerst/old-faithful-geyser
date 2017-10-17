# old-faithful-geyser

**A testing dataset containing waiting times between eruptions of the [Old Faithful Geyser](https://en.wikipedia.org/wiki/Old_Faithful).**

> Waiting time between eruptions and the duration of the eruption
for the Old Faithful geyser in Yellowstone National Park, Wyoming,
USA.
> A data frame with 272 observations on 2 variables.

– [*Old Faithful Geyser Data*](http://www.stat.cmu.edu/~larry/all-of-statistics/=data/faithful.dat)

[![npm version](https://img.shields.io/npm/v/old-faithful-geyser.svg)](https://www.npmjs.com/package/old-faithful-geyser)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/old-faithful-geyser.svg)
[![chat on gitter](https://badges.gitter.im/derhuerst.svg)](https://gitter.im/derhuerst)


## Installing

```shell
npm install old-faithful-geyser
```


## Usage

```js
const faithful = require('old-faithful-geyser')

console.log(faithful[10])
```

```
{
	d: 1.833, // duration of the eruption, in minutes
	w: 54 // waiting time to the next eruption, in minutes
}
```


## Source

[Azzalini, A. and Bowman, A. W. (1990). A look at some data on the
     Old Faithful geyser. Applied Statistics 39, 357-365.](2)

[source]: http://faculty.business.utsa.edu/manderso/R-examples/Geyser/Azzalini%20and%20Bowman,%20A%20look%20at%20some%20data%20on%20the%20Old%20Faithful%20geyser%20(JRSS-C,%201990).pdf
