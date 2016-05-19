# Css3-Animation
This animation is create by full html and css3 property
html code


<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>Animation-name</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	
	<div class="mommy">
		<div class="daddy"><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
		</div>
	</div>

	
</body>
</html>

style sheet

body {
  margin: 0;
  display: flex;
  height: 100vh;
  overflow: hidden;
  background: black;
}

.mommy {
  width: 800px;
  height: 800px;
  position: relative;
  perspective: 1280px;
   -webkit-animation: round 20s infinite; /* Chrome, Safari, Opera */ 
    animation: round 30s infinite;
    animation-direction:alternate-reverse;
    margin-left:30px;
}

.daddy {
   width: 800px;
  height: 800px;
}

span {
  display: inline-block;
  position: absolute;
  top: 50%;
  left: 20%;
}

span:before {
  content: "";
  width: 6px;
  height: 6px;
  display: inline-block;
  position: absolute;
  top: calc(50% - 2px);
  left: calc(50% - 2px);
  background: currentColor;
  color: inherit;
  border-radius: 50%;
  /* animation: invertRotate 25s infinite linear, scale4s infinite linear; */
  box-shadow: 0 0 2px white;
}

.mommy span:nth-child(1) {
  transform: translate3d(2.41129px, 1.01948px, 249.98629px);
  color: #ff0500;
    animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}

.mommy span:nth-child(2) {
    transform: translate3d(17.41129px, -7.98052px, 291.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(3) {
    transform: translate3d(11.41129px, -16.98052px, 256.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}

.mommy span:nth-child(4) {
    transform: translate3d(17.41129px, -25.98052px, 266.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(5) {
    transform: translate3d(20.41129px, -34.98052px, 266.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(6) {
    transform: translate3d(25.41129px, -43.98052px, 272.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(7) {
    transform: translate3d(32.41129px, -51.98052px, 287.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(8) {
    transform: translate3d(36.41129px, -60.98052px, 287.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(9) {
    transform: translate3d(47.41129px, -65.98052px, 320.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(10) {
    transform: translate3d(50.41129px, -75.98052px, 316.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(11) {
    transform: translate3d(53.41129px, -85.98052px, 312.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(12) {
    transform: translate3d(56.41129px, -95.98052px, 308.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(13) {
    transform: translate3d(62.41129px, -85.98052px, 308.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(14) {
    transform: translate3d(62.41129px, -85.98052px, 308.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(14) {
    transform: translate3d(62.41129px, -77.98052px, 300.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(15) {
    transform: translate3d(62.41129px, -69.98052px, 279.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(16) {
    transform: translate3d(59.41129px, -61.98052px, 241.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(17) {
    transform: translate3d(62.41129px, -50.98052px, 237.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(18) {
    transform: translate3d(68.41129px, -38.98052px, 257.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(19) {
    transform: translate3d(64.41129px, -29.98052px, 205.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(20) {
    transform: translate3d(69.41129px, -18.98052px, 205.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(21) {
    transform: translate3d(71.41129px, -9.98052px, 196.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(22) {
    transform: translate3d(74.41129px, -3.98052px, 175.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(23) {
    transform: translate3d(81.41129px, -8.98052px, 163.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}
.mommy span:nth-child(24) {
    transform: translate3d(81.41129px, -8.98052px, 163.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(25) {
    transform: translate3d(85.41129px, -17.98052px, 143.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}
.mommy span:nth-child(26) {
    transform: translate3d(7.41129px, -56.98052px, 148.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(27) {
    transform: translate3d(7.41129px, -56.98052px, 148.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(28) {
    transform: translate3d(16.41129px, -61.98052px, 148.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(29) {
    transform: translate3d(18.41129px, -65.98052px, 107.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(30) {
    transform: translate3d(29.41129px, -61.98052px, 107.98629px);
    color: #ff0500;
       animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(31) {
    transform: translate3d(34.41129px, -54.98052px, 92.98629px);
    color: #ff0500;
       animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}


.mommy span:nth-child(32) {
    transform: translate3d(-191.58871px, -80.98052px, 91.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}

.mommy span:nth-child(33) {
    transform: translate3d(-186.58871px, -71.98052px, 91.98629px);
    color: #ff0500;
    animation-name: movemycontent;
    animation-duration:4s;
    animation-iteration-count: infinite;
    animation-direction: alternate-reverse;
}
.mommy span:nth-child(34) {
    transform: translate3d(-181.58871px, -59.98052px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(35) {
    transform: translate3d(-178.58871px, -48.98052px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(36) {
    transform: translate3d(-172.58871px, -34.98052px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(37) {
    transform: translate3d(-166.58871px, -20.98052px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(38) {
    transform: translate3d(-161.58871px, -4.98052px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(39) {
    transform: translate3d(-156.58871px, 10.01948px, 84.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}
.mommy span:nth-child(40) {
    transform: translate3d(-141.58871px, 22.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(41) {
    transform: translate3d(-125.58871px, 28.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(42) {
    transform: translate3d(-108.58871px, 29.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(43) {
    transform: translate3d(-90.58871px, 29.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(44) {
    transform: translate3d(-72.58871px, 29.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(45) {
    transform: translate3d(-55.58871px, 29.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
      
}
.mommy span:nth-child(46) {
    transform: translate3d(-36.58871px, 30.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(47) {
    transform: translate3d(-19.58871px, 30.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(48) {
    transform: translate3d(-4.58871px, 30.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(49) {
    transform: translate3d(11.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(50) {
    transform: translate3d(26.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(51) {
    transform: translate3d(42.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(52) {
    transform: translate3d(59.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(53) {
    transform: translate3d(77.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(54) {
    transform: translate3d(94.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(55) {
    transform: translate3d(111.41129px, 30.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(56) {
    transform: translate3d(126.41129px, 27.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(57) {
    transform: translate3d(141.41129px, 21.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(58) {
    transform: translate3d(154.41129px, 14.01948px, 93.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(59) {
    transform: translate3d(168.41129px, 0.01948px, 93.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}
.mommy span:nth-child(59) {
    transform: translate3d(164.41129px, 2.01948px, 114.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(60) {
    transform: translate3d(164.41129px, 2.01948px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(61) {
    transform: translate3d(172.41129px, -9.98052px, 114.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}

.mommy span:nth-child(62) {
    transform: translate3d(180.41129px, -21.98052px, 114.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(63) {
    transform: translate3d(185.41129px, -32.98052px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(64) {
    transform: translate3d(190.41129px, -45.98052px, 114.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(65) {
    transform: translate3d(194.41129px, -58.98052px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(66) {
    transform: translate3d(194.41129px, -58.98052px, 114.98629px);
    color: #ff0500;
          animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(67) {
    transform: translate3d(198.41129px, -70.98052px, 114.98629px);
    color: #ff0500;
         animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(68) {
    transform: translate3d(202.41129px, -79.98052px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(69) {
    transform: translate3d(209.41129px, -87.98052px, 114.98629px);
    color: #ff0500;
         animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(70) {
    transform: translate3d(222.41129px, -89.98052px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(71) {
    transform: translate3d(232.41129px, -83.98052px, 114.98629px);
    color: #ff0500;
         animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(72) {
    transform: translate3d(239.41129px, -74.98052px, 114.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(73) {
    transform: translate3d(243.41129px, -63.98052px, 114.98629px);
    color: #ff0500;
         animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(74) {
    transform: translate3d(-198.58871px, -85.98052px, 91.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(75) {
    transform: translate3d(-208.58871px, -87.98052px, 91.98629px);
    color: #ff0500;
         animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(76) {
    transform: translate3d(-219.58871px, -82.98052px, 91.98629px);
    color: #ff0500;
        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(77) {
    transform: translate3d(-228.58871px, -72.98052px, 91.98629px);
    color: #ff0500;
        animation-name: movemycontent;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction: alternate-reverse;
}
.mommy span:nth-child(78) {
    transform: translate3d(-232.58871px, -58.98052px, 91.98629px);
    color: #ff0500;

        animation-name: movemycontent2;
  animation-duration:4s; 
  animation-iteration-count: infinite;
  animation-direction:alternate-reverse;
}

@-webkit-keyframes round {
    0%   {
    top: 5%;
    left: 0px; 
      }

    100% {
      top: 5%; 
      left:50%;
      animation-delay:2s;
    }
}

@-webkit-keyframes movemycontent {
  0% {
    color:green;
  }

  50% {
   color:blue;

  }
 
  100% {
  color:white;
  -webkit-transform: scale(2, 2);
     -moz-transform: scale(2, 2);
      -ms-transform: scale(2, 2);
       -o-transform: scale(2, 2);
          transform: scale(2, 2);


  }
}

@-webkit-keyframes movemycontent2 {
  0% {
    color:white;
  }
  
  50% {
   color:red;
}

  100% {
  color:yellow;
   -webkit-transform: scale(2, 2);
     -moz-transform: scale(2, 2);
      -ms-transform: scale(2, 2);
       -o-transform: scale(2, 2);
          transform: scale(2, 2);

  }
}
