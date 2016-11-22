init();
function init(){
	if(!document.addEventListener){
	    window.open('../浏览器/index.html','_self')
	    return
	}
/************个人菜单*****/
var navigationBox=document.getElementsByClassName('navigation-box')[0];
var phone=document.getElementsByClassName('phone')[0];
var phoneIndouce=document.getElementsByClassName('phone-indouce')[0];
var notebook=document.getElementsByClassName('notebook')[0];
var notebookIndouce=document.getElementsByClassName('notebook-indouce')[0];
var table=document.getElementsByClassName('table')[0];
var tableIndouce=document.getElementsByClassName('table-indouce')[0];
var mainboard=document.getElementsByClassName('mainboard')[0];
var mainboardIndouce=document.getElementsByClassName('mainboard-indouce')[0];
var displaycard=document.getElementsByClassName('display-card')[0];
var displaycardIndouce=document.getElementsByClassName('display-card-indouce')[0];
var smart=document.getElementsByClassName('smart')[0];
var smartIndouce=document.getElementsByClassName('smart-indouce')[0];
var desktop=document.getElementsByClassName('desktop')[0];
var desktopIndouce=document.getElementsByClassName('desktop-indouce')[0];
var LCD=document.getElementsByClassName('LCD')[0];
var LCDIndouce=document.getElementsByClassName('LCD-indouce')[0];
var network=document.getElementsByClassName('network')[0];
var networkIndouce=document.getElementsByClassName('network-indouce')[0];
var media=document.getElementsByClassName('media')[0];
var mediaIndouce=document.getElementsByClassName('media-indouce')[0];
var car=document.getElementsByClassName('car')[0];
var carIndouce=document.getElementsByClassName('car-indouce')[0];
var access=document.getElementsByClassName('access')[0];
var accessIndouce=document.getElementsByClassName('access-indouce')[0];
var game=document.getElementsByClassName('game')[0];
var gameIndouce=document.getElementsByClassName('game-indouce')[0];
function dis(obj,obj1){
	obj.onmouseover=function(){
	obj1.style.display="block";
	}
	obj.onmouseout=function(){
	obj1.style.display="none";
	}
}
dis(phone,phoneIndouce);
dis(notebook,notebookIndouce);
dis(table,tableIndouce);
dis(mainboard,mainboardIndouce);
dis(displaycard,displaycardIndouce);
dis(smart,smartIndouce);
dis(desktop,desktopIndouce);
dis(LCD,LCDIndouce);
dis(network,networkIndouce);
dis(media,mediaIndouce);
dis(car,carIndouce);
dis(access,accessIndouce);
dis(game,gameIndouce);
var presonBox=document.getElementsByClassName('preson-box')[0];
var presonBigBox=document.getElementsByClassName('preson-big-box')[0];
var line1=document.getElementsByClassName('line1')[0];
var perClick=false;
presonBigBox.onmouseover = function(){
	if(perClick || hotClick || hasClick || serClick){
		presonBox.style.display="block";
	}	
	line1.style.display="block";
	line1.style.cssText="-webkit-transform:translate(57px,0px) ;-ms-transform:translate(57px,0px) ;-moz-transform:translate(57px,0px) ;translate(57px,0px);";
	line1.style.width="113px";
}
presonBigBox.onclick=function(){
	presonBox.style.display="block";
	perClick=true;
}
presonBigBox.onmouseleave=function(){
	line1.style.cssText="-webkit-transform:translate(-1000px,0px) ;-ms-transform:translate(-1000px,0px) ;-moz-transform:translate(-1000px,0px) ;translate(-1000px,0px);";
	line1.style.width="20px";
	presonBigBox.onmouseleave=function(){
		presonBox.style.display="none";
	}
}
/****************line1*****/
line1.style.display="none";
/********hot*****/
var imgBlack1=document.getElementsByClassName('big-img')[0];
var word1=document.getElementsByClassName('big-img-txt')[0];
var imgBox1=document.getElementsByClassName('hot-box-left-big')[0];
var imgBlack2=document.getElementsByClassName('left-small-left-img')[0];
var word2=document.getElementsByClassName('left-small-left-img-txt')[0];
var imgBox2=document.getElementsByClassName('left-small-left')[0];
var imgBlack3=document.getElementsByClassName('left-small-right-img')[0];
var word3=document.getElementsByClassName('left-small-right-img-txt')[0];
var imgBox3=document.getElementsByClassName('left-small-right')[0];
var imgBlack4=document.getElementsByClassName('hot-box-left-top-img')[0];
var word4=document.getElementsByClassName('hot-box-left-top-img-txt')[0];
var imgBox4=document.getElementsByClassName('hot-box-right-left-top')[0];
var imgBlack5=document.getElementsByClassName('hot-box-left-center-img')[0];
var word5=document.getElementsByClassName('hot-box-left-center-img-txt')[0];
var imgBox5=document.getElementsByClassName('hot-box-right-left-center')[0];
var imgBlack6=document.getElementsByClassName('hot-box-left-down-img')[0];
var word6=document.getElementsByClassName('hot-box-left-down-img-txt')[0];
var imgBox6=document.getElementsByClassName('hot-box-right-left-down')[0];
var imgBlack7=document.getElementsByClassName('hot-box-right-top-img')[0];
var word7=document.getElementsByClassName('hot-box-right-top-img-txt')[0];
var imgBox7=document.getElementsByClassName('hot-box-right-right-top')[0];
var imgBlack8=document.getElementsByClassName('hot-box-right-center-img')[0];
var word8=document.getElementsByClassName('hot-box-right-center-img-txt')[0];
var imgBox8=document.getElementsByClassName('hot-box-right-right-center')[0];
var imgBlack9=document.getElementsByClassName('hot-box-right-down-img')[0];
var word9=document.getElementsByClassName('hot-box-right-down-img-txt')[0];
var imgBox9=document.getElementsByClassName('hot-box-right-right-down')[0];
function black(box,blackBox,word){
	box.onmouseover=function(){
		blackBox.style.display="block";
		word.style.color="#00A8FF";
	}
	box.onmouseout=function(){
		blackBox.style.display="none";
		word.style.color="#333";
	}	
}
black(imgBox1,imgBlack1,word1);
black(imgBox2,imgBlack2,word2);
black(imgBox3,imgBlack3,word3);
black(imgBox4,imgBlack4,word4);
black(imgBox5,imgBlack5,word5);
black(imgBox6,imgBlack6,word6);
black(imgBox7,imgBlack7,word7);
black(imgBox8,imgBlack8,word8);
black(imgBox9,imgBlack9,word9);

var hotBox=document.getElementsByClassName('hot-box')[0];
var hotBigBox=document.getElementsByClassName('hot-big-box')[0];
var hotClick=false;
hotBigBox.onmouseover=function(){
		if(perClick || hotClick || hasClick || serClick){
			hotBox.style.display="block";
		}
	line1.style.display="block";
	line1.style.cssText="-webkit-transform:translate(230px,0px) ;-ms-transform:translate(230px,0px) ;-moz-transform:translate(230px,0px) ;translate(230px,0px);";
	line1.style.width="63px";
}	
hotBigBox.onclick=function(){
	hotBox.style.display="block";
	hotClick=true;
}
hotBigBox.onmouseleave=function(){
	line1.style.cssText="-webkit-transform:translate(-1000px,0px) ;-ms-transform:translate(-1000px,0px) ;-moz-transform:translate(-1000px,0px) ;translate(-1000px,0px);";
	line1.style.width="20px";
	hotBigBox.onmouseleave=function(){
		hotBox.style.display="none";
	}
}
/***********商用产品****/
var product=document.getElementsByClassName('product')[0];
var productIndouce=document.getElementsByClassName('product-indouce')[0];
dis(product,productIndouce);
var compay=document.getElementsByClassName('compay')[0];
var compayIndouce=document.getElementsByClassName('compay-indouce')[0];
dis(compay,compayIndouce);
var method=document.getElementsByClassName('method')[0];
var methodIndouce=document.getElementsByClassName('method-indouce')[0];
dis(method,methodIndouce);
var yong=document.getElementsByClassName('yong')[0];
var yongIndouce=document.getElementsByClassName('yong-indouce')[0];
dis(yong,yongIndouce);

var productTitle=document.getElementsByClassName('product-title')[0];

var commercialBox=document.getElementsByClassName('commercial-box')[0];
var commercialBigBox=document.getElementsByClassName('commercial-big-box')[0];
var hasClick = false;
commercialBigBox.onmouseover = function(){
	if(perClick || hotClick || hasClick || serClick){
		commercialBox.style.display="block";
	}
	line1.style.display="block";
	line1.style.cssText="-webkit-transform:translate(353px,0px) ;-ms-transform:translate(353px,0px) ;-moz-transform:translate(353px,0px) ;translate(353px,0px);";
	line1.style.width="63px";
}
commercialBigBox.onclick=function(){
	commercialBox.style.display="block";
	hasClick = true;
}
commercialBigBox.onmouseleave=function(){
	line1.style.cssText="-webkit-transform:translate(-1000px,0px) ;-ms-transform:translate(-1000px,0px) ;-moz-transform:translate(-1000px,0px) ;translate(-1000px,0px);";
	line1.style.width="20px";
	commercialBigBox.onmouseleave=function(){
		commercialBox.style.display="none";
	}
}
/***********serve****/
var serveBox=document.getElementsByClassName('serve-box')[0];
var serveBigBox=document.getElementsByClassName('serve-big-box')[0];
var serClick=false;
serveBigBox.onmouseover=function(){
	if(perClick || hotClick || hasClick || serClick){
		serveBox.style.display="block";
	}
	line1.style.display="block";
	line1.style.cssText="-webkit-transform:translate(476px,0px) ;-ms-transform:translate(476px,0px) ;-moz-transform:translate(476px,0px) ;translate(476px,0px);";
	line1.style.width="63px";
}

serveBigBox.onclick=function(){
	serveBox.style.display="block";
	serClick=true;
	}
serveBigBox.onmouseleave=function(){
	line1.style.cssText="-webkit-transform:translate(-1000px,0px) ;-ms-transform:translate(-1000px,0px) ;-moz-transform:translate(-1000px,0px) ;translate(-1000px,0px);";
	line1.style.width="20px";
	serveBigBox.onmouseleave=function(){
		serveBox.style.display="none";
	}
}
var officialBigBox=document.getElementsByClassName('official-big-box')[0];
officialBigBox.onmouseover=function(){
	line1.style.display="block";
	line1.style.cssText="-webkit-transform:translate(600px,0px) ;-ms-transform:translate(600px,0px) ;-moz-transform:translate(600px,0px) ;translate(600px,0px);";
	line1.style.width="100px";
}
officialBigBox.onmouseleave=function(){
	line1.style.cssText="-webkit-transform:translate(-1000px,0px) ;-ms-transform:translate(-1000px,0px) ;-moz-transform:translate(-1000px,0px) ;translate(-1000px,0px);";
	line1.style.width="20px";
}
/********banner****/
var peopelBannerLeft=document.getElementsByClassName('people-banner-left')[0];
var peopleBannerLeftBlack=document.getElementsByClassName('people-banner-left-black')[0];
black1(peopelBannerLeft,peopleBannerLeftBlack);

var peopelBannerRight=document.getElementsByClassName('people-banner-right')[0];
var peopleBannerRightBlack=document.getElementsByClassName('people-banner-right-black')[0];
black1(peopelBannerRight,peopleBannerRightBlack)
function black1(box,blackBox){
	box.onmouseover=function(){
		blackBox.style.display="block";
	}
	box.onmouseout=function(){
		blackBox.style.display="none";
	}	
}

}


