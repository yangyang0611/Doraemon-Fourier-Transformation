# Fourier Transformation using FFT

## Motivation
Since FFT can only do a one-shot graphic, we decide to try making more complex graphics. In this project we choose Doraemon as target.

![](https://imgur.com/uLGUolL.jpg)

#### One-shot graphic
![](https://imgur.com/QPMZH8X.jpg)

#### Complex graphic -- **TARGET**
![](https://imgur.com/dAeO9YK.jpg)

## Algorithm
![](https://imgur.com/m9fqFyb.jpg)

## Requirements
Before start, you need to install Image Processing Toolbox from Matlab add-ons columns.

## 
## Effect of Parameters
We try to modify parameters with different drop and interpolationM and it leads to different graphic.

### 1. Drop
#### Drop: 1
![](https://imgur.com/qoxZbRO.jpg)

#### Drop: 5 
![](https://imgur.com/ptJFG6i.jpg)

#### Drop: 30 
![](https://imgur.com/Ki4cfU2.jpg)

#### Drop: 50 
![](https://imgur.com/LaYk2c9.jpg)

### 2. interpolationM
#### interpolationM: 1 
![](https://imgur.com/cA02w0I.jpg)

#### interpolationM: 3
![](https://imgur.com/TnYKVxD.jpg)

### 3. Pixel Distance
![](https://imgur.com/xMI0J3P.gif)
![](https://imgur.com/VimTIB9.gif)

## Results
#### Original <br>
![](https://imgur.com/dAeO9YK.jpg)

#### Drawn <br>
![](https://imgur.com/1k6E2q9.jpg)

#### drop: 10
![](https://imgur.com/Keg1G5q.jpg)
![](https://imgur.com/48f4yS3.jpg)

#### drop: 20
![](https://imgur.com/i6FpbWS.jpg)
![](https://imgur.com/6eYYR2L.jpg)
![](https://imgur.com/OSF8pYk.jpg)

#### drop: 30
![](https://imgur.com/mGubRro.jpg)
![](https://imgur.com/LVWEaGJ.jpg)
![](https://imgur.com/U0nHNbF.jpg)
![](https://imgur.com/fm8jpnE.jpg)

#### drop: 50
![](https://imgur.com/r7hM3vX.jpg)
![](https://imgur.com/laIjKin.jpg)

#### interpolationM: 1
![](https://imgur.com/xqsigvj.jpg)
![](https://imgur.com/zkjaP2h.jpg)
![](https://imgur.com/zkjaP2h.jpg)
![](https://imgur.com/J6kECiT.jpg)

## Dicussion and Improvements
1. Draw graphic and arrow at the same time will slow down the computer
2. Better to use Python than C as we can call written functions from Python's library
3. Modifying of parameters takes time

![](https://imgur.com/TKMF5Hql.jpg)
