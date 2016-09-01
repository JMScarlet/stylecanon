.tabsa {
  position: relative;
  width: 409px;
  height: 410px;
  padding: 20px;
  background: #fff;
  border-top: 10px solid #000;
  border-bottom: 10px solid #000;
}

.taba {
  float: left;
}

.taba label {
  display: block;
  width: 20px;
  padding: 5px;
  position: relative;
  margin-right: 1px;
  background: #3d7eb0;
  text-align: center;
  font-family: 'Yantramanav', sans-serif;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-size: 8px;
  line-height: 100%;
  color: #ffffff;
  top: 10px;
  left: 107px;
}

.taba [type=radio] {
  display: none;
}

.contenta {
  width: 389px;
  height: 360px;
  position: absolute;
  top: 50px;
  bottom: 0px;
  left: 20px;
  right: 0px;
  background: white;
  padding: 10px;
  color: #3d7eb0;
  opacity: 0; 
 -webkit-transform: scale(0); 
-o-transform: scale(0); 
-moz-transform: scale(0);
 -webkit-transition-duration: .8s; 
-moz-transition-duration: .8s; 
-o-transition-duration: .8s;
}

[type=radio]:checked ~ label {
  background: #3d7eb0;
  border-bottom: 0px solid white;
  color: #fff;
  z-index: 2;
}

[type=radio]:checked ~ label ~ .contenta {
  z-index: 1;
opacity: 1; 
 -webkit-transform: scale(1); 
-o-transform: scale(1); 
-moz-transform: scale(1);
}

.rc-frov {
  width: 379px;
  height: 350px;
  position: relative;
  overflow: hidden;
}

.rcfrhv {
  position: relative;
  left: 0px;
  top: 0px;
  background-color: rgba(0, 0, 0, 0.7);
  transition-: 0.6s all ease-in-out;
  -webkit-transition: 0.6s all ease-in-out;
  -moz-transition: 0.6s all ease-in-out;
  -o-transition: 0.6s all ease-in-out;
  -ms-transition: 0.6s all ease-in-out;
  opacity: 0.0;
}

.rc-frov:hover .rcfrhv {
  margin-top: -350px;
  opacity: 1.0;
}

.rc-frincont {
  width: 379px;
  height: 350px;
  padding: 4px;
  border: 1px solid #ddd;
  background: #fff;
}

.rc-frhvcont {
  width: 339px;
  height: 310px;
  padding: 20px;
}

.rc-frtx-nm {
  width: 319px;
  height: 13px;
  padding: 10px;
  background: #3d7eb0;
  margin-top: 277px;
  text-align: right;
  font-family: 'Yantramanav', sans-serif;
  font-size: 10px;
  letter-spacing: 0px;
  color: #eaeaea;
  line-height: 100%;
  overflow: hidden;
}

.rc-frtx-br {
  border-right: 1px solid #eaeaea;
  border-bottom: 1px solid #eaeaea;
  padding-right: 5px;
  padding-bottom: 2px;
}

.rc-ov {
  width: 200px;
  height: 350px;
  position: relative;
  overflow: hidden;
}

.rchv {
  position: relative;
  left: 0px;
  top: 0px;
  background-color: rgba(0, 0, 0, 0.7);
  transition-: 0.6s all ease-in-out;
  -webkit-transition: 0.6s all ease-in-out;
  -moz-transition: 0.6s all ease-in-out;
  -o-transition: 0.6s all ease-in-out;
  -ms-transition: 0.6s all ease-in-out;
  opacity: 0.0;
}

.rc-ov:hover .rchv {
  margin-top: -350px;
  opacity: 1.0;
}

.rc-tx-ov2 ::-webkit-scrollbar {
  width: 5px;
  background: #4b4b4b;
}

.rc-tx-ov2  ::-webkit-scrollbar-thumb {
  background: #4b4b4b;
}

.rc-tx-ov2 ::-webkit-scrollbar-corner {
  background: #4b4b4b;
}

.rc-cont {
  width: 389px;
  background: #fff;
  padding: 20px;
}

.rc-incont {
  width: 200px;
  height: 350px;
  padding: 3px;
  border: 1px solid #ddd;
  background: #fff;
}

.rc-hvcont {
  width: 160px;
  height: 310px;
  padding: 20px;
}

.rc-tx-nm {
  width: 134px;
  height: 13px;
  padding: 10px;
  background: #3d7eb0;
  margin-top: 277px;
  text-align: right;
  font-family: 'Yantramanav', sans-serif;
  font-size: 10px;
  letter-spacing: 0px;
  color: #eaeaea;
  line-height: 100%;
  overflow: hidden;
}

.rc-tx-br {
  border-right: 1px solid #eaeaea;
  border-bottom: 1px solid #eaeaea;
  padding-right: 5px;
  padding-bottom: 2px;
}

.rc-tx-sub {
  width: 168px;
  padding: 5px;
  background: #3d7eb0;
  text-align: right;
  font-family: 'Yantramanav', sans-serif;
  font-size: 8px;
  letter-spacing: 1px;
  color: #eaeaea;
  line-height: 100%;
  margin-left: 3px;
}

.rc-tx-ov2 {
  width: 150px;
  height: 312px;
  padding: 13px;
  border: 1px solid #ddd;
  background: #fff;
  margin-left: 3px;
  text-align: justify;
  font-family: Tahoma;
  font-size: 10px;
  line-height: 110%;
  color: #333;
}

.rc-tx-ovf2 {
  height: 312px;
  overflow: auto;
  padding-right: 5px;
}
