function ShowBlock(target){
	document.getElementById(target).style.display='block';
}

function HideBlock(target){
	document.getElementById(target).style.display='none';
}

function Opacity(target){
	var alfa=0.0;
	document.getElementById(target).style.display='block';

	while (alfa<1.0)
		{alfa+=0.001;
		document.getElementById(target).style.opacity=alfa;}
}

function Darkness(){
	document.getElementById('dark').style.opacity=0.6;
	document.getElementById('dark').style.display='block';
}

function Galery(img){
	document.getElementById('login').style.display='none';
	var image=document.getElementById(img);
	var clone=image.cloneNode(true);
	clone.style.zIndex=10;
	clone.style.position='fixed';
	clone.style.top='10%';
	clone.style.left='15%';
	clone.style.width='925px';
	clone.style.margin='0px';
	clone.id="clone";
	document.body.appendChild(clone);
}

function ExitGal(tipo){
	document.getElementById('darkbot').style.display='none';
	document.getElementById('dark').style.opacity=0;
	document.getElementById('dark').style.display='none';

	if (tipo==true)
	{var clone=document.getElementById('clone');
	clone.remove();}
}

function Lights(target){
	var lights=false
	
	if (lights==false){
		document.getElementByTagName(target).style.zIndex=10;
		document.getElementById('dark').style.opacity=0.6;
		document.getElementById('dark').style.display='block';
		document.getElementById('darkbot').style.display='none';
		lights=true;
	}

	else{
		document.getElementByTagName(target).style.zIndex=0;
		document.getElementById('dark').style.opacity=0;
		document.getElementById('dark').style.display='none';
		document.getElementById('darkbot').style.display='none';
		lights=false;
	}
}