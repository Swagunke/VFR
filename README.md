# VFR
<style type="text/css">* {
  box-sizing: border-box;
}
html,
body {

}
body {

}
.carousel1 {
  position: relative;
  width: 600px;
  height: 400px;
  overflow: hidden;
  margin: 0 auto;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
}
.carousel1:hover .slide1:after,
.carousel1:hover .counter,
.carousel1:hover .slide1:before {
  opacity: 1;
}
.slide1 {
  float: right;
  position: absolute;
  z-index: 1;
  width: 600px;
  height: 400px;
  background-color: #eee;
  text-align: center;
  transition: opacity 0.4s;
  opacity: 1;
}
.slide1:before {
  content: attr(annot);
  display: block;
  position: absolute;
  left: 20px;
  bottom: 20px;
  color: rgba(255,255,255,0.9);
  font-size: 14px;
  font-weight: 300;
  z-index: 12;
  opacity: 0;
  transition: opacity 0.3s;
  text-shadow: 0 0 1px #000;
}
.slide1:after {
  content: attr(slide1);
  display: block;
  position: absolute;
  bottom: 0;
  transition: opacity 0.3s;
  width: 100%;
  height: 80px;
  opacity: 0;
  background-image: linear-gradient(transparent, rgba(0,0,0,0.5));
  text-align: left;
  text-indent: 549px;
  line-height: 101px;
  font-size: 13px;
  color: rgba(255,255,255,0.9);
  text-shadow: 0 0 1px #000;
}
.counter {
  position: absolute;
  bottom: 20px;
  right: 1px;
  height: 20px;
  width: 60px;
  z-index: 2;
  text-align: center;
  color: #fff;
  line-height: 21px;
  font-size: 13px;
  opacity: 0;
  transition: opacity 0.3s;
}
.faux-ui-facia {
  top: 0;
  right: 0;
  float: right;
  position: absolute;
  margin-top: 0;
  z-index: 9;
  height: 100%;
  width: 100%;
  opacity: 0;
  cursor: pointer;
}
.faux-ui-facia:checked {
  z-index: 8;
}
.faux-ui-facia:checked + .slide1 {
  opacity: 0;
}
.faux-ui-facia:checked:nth-child(1):checked {
  z-index: 9;
}
.faux-ui-facia:nth-child(1):checked {
  float: left;
  z-index: 9;
}
.faux-ui-facia:nth-child(1):checked + .slide1 {
  opacity: 1;
}
.faux-ui-facia:nth-child(1):checked ~ .faux-ui-facia {
  float: left;
  z-index: 8;
}
.faux-ui-facia:nth-child(1):checked ~ .faux-ui-facia + .slide1 {
  opacity: 0;
}
.faux-ui-facia:nth-child(1):checked ~ .faux-ui-facia:checked {
  z-index: 9;
}
.faux-ui-facia:nth-child(1):checked ~ .faux-ui-facia:checked + .slide1 {
  opacity: 1;
}
/* --- Intro text --- */
.intro {
  padding: 80px 0 60px 0;
  text-align: center;
  color: #fff;
  margin: auto;
  width: 800px;
}
.intro .intro__title {
  font-weight: 200;
  font-size: 32px;
  color: #fff;
}
.intro .intro__body {
  color: #fff;
  font-size: 16px;
  line-height: 24px;
  font-weight: 300;
  opacity: 0.48;
  padding: 0 160px;
  margin: 0;
}
</style>
<style type="text/css">
</style>
<div class="carousel1"><input class="faux-ui-facia" type="checkbox" />
<div annot="Produktion in Deutschland. 17. Jahrhundert (Quelle: VD17)" class="slide1" slide="3"><img alt="Slide 3" src="https://vfr.mww-forschung.de/documents/168626/169628/Chart3_1.jpg/498c09ba-8cc9-0d1b-7aa7-f59eba259623?t=1544435807850" /></div>
<input class="faux-ui-facia" type="checkbox" />
<div annot="Produktion in Europa. 16. Jahrhundert (Quelle: VD16, USTC)" class="slide1" slide="2"><img alt="Slide 2" src="https://vfr.mww-forschung.de/documents/168626/169628/Chart2_1.jpg/9a51342b-88b7-2cb2-aba7-122b94f350d2?t=1544435807403" /></div>
<input class="faux-ui-facia" type="checkbox" />
<div annot="Produktion in Europa. Inkunabelzeit (Quelle: GW, ISTC)" class="slide1" slide="1"><img alt="Slide 1" src="https://vfr.mww-forschung.de/documents/168626/169628/Chart1_1.jpg/eca4c8ca-1dae-0588-2f06-cc83f1e45a5a?t=1544435524419" /></div>
<input class="faux-ui-facia" type="checkbox" />
<div class="counter" count="3">/ 3</div>
</div>

<p>&nbsp;</p>

<p align="center">(zum Blättern auf die Abbildung klicken)</p>
