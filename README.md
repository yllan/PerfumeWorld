# Perfume World Viewer

![My house](https://yllan.github.io/PerfumeWorld/docs/my_house.png)

**Perfume World Viewer** display the buildings in [http://perfume-world.jp/](http://perfume-world.jp/). Unlike the offical website, it use WebGL instead of the painfully slow Adobe Flash. 

## Usage
---

Add the address of house after URL `http://yllan.github.io/PerfumeWorld/#`. For example:

* [http://yllan.github.io/PerfumeWorld/#2-2-8](https://yllan.github.io/PerfumeWorld/#2-2-8)
* [http://yllan.github.io/PerfumeWorld/#2-4-3](http://yllan.github.io/PerfumeWorld/#2-4-3)
* [http://yllan.github.io/PerfumeWorld/#2-4-9](http://yllan.github.io/PerfumeWorld/#2-4-9)

## Data Synchronization
---
I run a cronjob to fetch the house data from [https://api.perfume-world.jp](https://api.perfume-world.jp) hourly. That is, changes you made on the official website may take at most an hour to be reflected on Perfume World Viewer.

## Contribution
---
You can check my note: [analysis of Perfume World](https://yllan.hackpad.com/Analysis-of-perfume-world.jp-HZVCB1S3M2h) to know more about how the official website works. Pull requests are welcome.


## Credits
---
* Yung-Luen Lan ([@yllan](https://twitter.com/yllan))
* Lighting Adjustment: mifan ([@mifanbang](https://twitter.com/mifanbang))
* All data and contents from the [official website](http://perfume-world.jp) are owned by AMUSE and Universal Music. 

## License
---
Perfume World Viewer is available under the MIT license. See the LICENSE file for more info.