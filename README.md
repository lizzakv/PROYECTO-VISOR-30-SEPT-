<!DOCTYPE html>
<html>
<section class="webdesigntuts-workshop">
	<form action="" method="">		    
		<input type="search" placeholder="Search...">		    	
		<button>Search</button>
		<input type="button" value="Imprime esta página" onclick="window.print()">
		<input type="button" value="Parques Botanicos" onclick="window.search()">
		<input type="button" value="Aguas termales" onclick="window.search()">
		<input type="button" value="Marca lo nuestro" onclick="window.search()">
		<input type="button" value="Mas que turismo" onclick="window.search()">
		<input type="button" value="Diversidad" onclick="window.search()">
		<input type="button" value="Contactanos" onclick="window.search()">
		<input type="button" value="Informacion" onclick="window.search()">
		
	</form>
	</section>
	<p><b><font size = "5", color = "purple">CLASE PROGRAMACION APLICADA A LOS SISTEMAS DE INFORMACION GEOGRAFICA (CTE 524)</font></b>, <br><font size = 5, color = "purple"></font></br>EN CENTROAMERICA HONDURAS</br></p><br></br>
	
	<marquee color = "purple"  BEHAVIOR=ALTERNATE>BIENVENIDO A MI VISOR WEB SITIOS DE RECREACION PARQUES TURISTICOS DE HONDURAS </marquee>
	
	<font marquee size = "5", color = "blue", >PARQUES TURISTICOS DE HONDURAS </marquee></font><br></br>
	
	<img src = "https://www.bosquesdelmundo.org/files/International.forestsoftheworld.org/Kort/St%C3%B8rre/Hon.esp.1187x768.jpg" width="200" height="200"/><img src = "http://faces.unah.edu.hn/astro/laafvirtual/theme/splash/pix/logoFaces_sinfondo_peq.png" width="200" height="200"/><img src = "https://www.unah.edu.hn/themes/portalunah/assets/images/logo-unah.png" width="200" height="200"/><img src = "https://escuelapce.com/wp-content/uploads/2019/05/LogoAlcala.jpg" width="200" height="200"/><img src = "https://www.underconsideration.com/brandnew/archives/honduras_logo_detail.png" width="200" height="200"/><img src = "https://www.flagsonline.it/uploads/2016-6-6/420-272/honduras.jpg" width="200" height="200"/>
	
	
	<br><font face="Comic Sans MS">Maestría en Gestión y Ordenamiento Territorial MOGT5/Universidad Nacional Autónoma de Honduras (UNAH)</font><br></br>
	<br>
	
		<head>
		<meta charset="utf-8"/>
		<title>Honduras Geoserver</title>
				
		<!--Leaflet-->
		<link rel="stylesheet" href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css"
		integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ=="
		crossorigin=""/>
  
		<script src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"
		integrity="sha512-GffPMF3RvMeYyc1LWMHtK8EbPv0iNZ8/oTtHPx9/cc2ILxQ+u905qIwdpULaqDkyBKgOaB57QTMg7ztg8Jm2Og=="
		crossorigin="">
		
		 
		</script>
		
		<!--Comentario: Agregar ESRIMaps-->
		<script src="https://unpkg.com/esri-leaflet@2.3.0/dist/esri-leaflet.js"
		integrity="sha512-1tScwpjXwwnm6tTva0l0/ZgM3rYNbdyMj5q6RSQMbNX6EUMhYDE3pMRGZaT41zHEvLoWEK7qFEJmZDOoDMU7/Q=="
		crossorigin=""></script>
		
		
		<!--Plugins de Leaflet-->
		<!--MiniMap-->
		<link rel="stylesheet" href="Control.MiniMap.css" />
		<script src="Control.MiniMap.js" type= "text/javascript">
		</script>
	
		<!--Mouse Position-->
		<link rel="stylesheet" href="L.Control.MousePosition.css" />
		<script src="L.Control.MousePosition.js" type= "text/javascript">
		</script>
		
		<!--Full screen-->
		<link rel='stylesheet' href='leaflet.fullscreen.css'  />
		<script src='Leaflet.fullscreen.js'></script>
		
		<!--Map center-->
		<link rel="stylesheet" href="leaflet.viewcenter.css" />
		<script src="leaflet.viewcenter.js"></script>
		<script src="Leaflet.MakiMarkers.js"></script>
		
		
		<link rel="stylesheet" href="https://unpkg.com/leaflet@1.3.1/dist/leaflet.css" 
		integrity="sha512-Rksm5RenBEKSKFjgI3a41vrjkw4EVPlJ3+OiI65vTjIdo9brlAacEuKOiQ5OFh7cOI1bkDwLqdLw3Zg0cRJAAQ==" 
		crossorigin=""/>
		
		</head>
	
		</div> <!-- end container -->
		<div id="map" style="width: 1452px; height: 768px;"></div>
		<div class='space-bottom'></div>
        <div id='map' class='col12 row10'></div>
		
		<body background="paisajes-de-primavera-para-fondo-de-pantalla.jpg" bgcolor="#C8FE2E">
		
		<marquee scrolldelay= "200" direction = "down" collamount= "10" height = "250px"><center>
		
		<img src = "https://www.bosquesdelmundo.org/files/International.forestsoftheworld.org/Kort/St%C3%B8rre/Hon.Terri.NDD.1187x768.jpg" width="200" height="200"/></br>
		<img src = "https://hondudiario.com/wp-content/uploads/2018/02/parque-cusuco.jpg" width="200" height="200"/>
		<img src = "http://c.asstatic.com/images/872666_634349392064688750-1.jpg" width="200" height="200"/>
		<img src = "https://www.vuelaviajes.com/wp-content/2013/04/honduras-parque-nacional-trifinio.jpg" width="200" height="200"/>
		<img src = "https://diarioroatan.com/wp-content/uploads/2018/02/10922859_1396316560669398_7497515118347627234_n.jpg" width="200" height="200"/>
		<img src = "https://www.espaciohonduras.net/images/honduras/articulos/areasprotegidas/Parques_Nacional_marino/Parques_Nacional_marino.jpg" width="200" height="200"/>
		<img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Parque_Nacional_Monta%C3%B1a_de_Comayagua%2C_PANACOMA._Honduras.jpg/1200px-Parque_Nacional_Monta%C3%B1a_de_Comayagua%2C_PANACOMA._Honduras.jpg" width="200" height="200"/>
		
			
		<script>
	
		var osm = L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', 
		{attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors,<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>', 
		id: 'mapbox.satellite', 
		accessToken:'pk.eyJ1IjoibGl6YS1rYWZhdGkyMDE5IiwiYSI6ImNrMDV0ejdxOTAwY3IzYm90azl5bWFwYm4ifQ.-f3pA2idzqzRASVWgoQZvg',
		maxZoom: 15,
		minZoom: 7,
		keyboard: true
		})
		
			
		var osm2 = L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}', 
		{attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors,<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="https://www.mapbox.com/">Mapbox</a>', 
		id: 'mapbox.light', 
		accessToken:'pk.eyJ1IjoibGl6YS1rYWZhdGkyMDE5IiwiYSI6ImNrMDV0ejdxOTAwY3IzYm90azl5bWFwYm4ifQ.-f3pA2idzqzRASVWgoQZvg',
		maxZoom: 15,
		minZoom: 4,
		keyboard: true
		
		});
		
		<!-----------------Ecosistemas------------------------------------>
		var cuencas = L.tileLayer.wms("http://localhost:8080/geoserver/new/wms?service=WMS", {
		layers: "new:subcuencas",
		format: 'image/png',
		transparent: true,
		version: '1.1.0',
		attribution: "Sistema nacional de informacion Territorial- Honduras, 2015"
		});
		
		var capasOverlay = {
		
		"Cuencas": cuencas,
			};
		
		
		var fuscionecosistema = L.layerGroup([cuencas]);
		
		var mapa = L.map('map',{
		center: [14.083025, -87.191330],
		zoom:7,
		layers: osm,
		zoomControl: false,
		fullscreenControl: {pseudoFullscreen: false, position: 'topright'
		},
		maxBounds: [[14.085190, -87.186297],[14.080877, -87.195965]]
		});
		
		<!--Comentario: marcadores de L.icon-->
		var icono1 = L.icon({
		iconUrl: 'parque_arqueologico_copan-1-810x540.png',
		iconSize: [50, 70],
		});
		var marker1= L.marker([14.849725, -89.146783], {icon: icono1}).addTo(mapa);
		marker1.bindPopup("COPAN RUINAS");
		
		var icono2 = L.icon({
		iconUrl: 'https://diarioroatan.com/wp-content/uploads/2018/02/Jeannette-Kawas-parque-nacional-honduras-1.jpg',
		iconSize: [50, 70],
		});
		var marker2= L.marker([15.146207, -84.663616], {icon: icono1}).addTo(mapa);
		marker2.bindPopup("GRACIAS A DIOS");
		
		var icono3 = L.icon({
		iconUrl: 'areas-protegidas-de-honduras-1-638.png',
		iconSize: [50, 70],
		});
		var marker3= L.marker([14.294536, -85.783882], {icon: icono1}).addTo(mapa);
		marker3.bindPopup("OLANCHO");
		
		var icono4 = L.icon({
		iconUrl: 'z4.jpeg',
		iconSize: [50, 70],
		});
		var marker4= L.marker([ 14.978971, -86.625919], {icon: icono1}).addTo(mapa);
		marker4.bindPopup("OLANCHO");
		
		var hn = L.tileLayer.wms("http://localhost:8080/geoserver/opengeo/wms?service=WMS", {
		layers: "opengeo:departamentos",
		format: 'image/png',
		transparent: true,
		version: '1.3.0',
		attribution: "Departamentos Honduras, COPECO - oficial"
		});
		
		var ESRI = L.esri.basemapLayer('NationalGeographic');
		
		var ESRI_topo = L.esri.basemapLayer('Terrain');
	
		var ESRI_2 = L.esri.basemapLayer('Physical');
		
		var ESRI_3 = L.esri.basemapLayer('Streets');
		
		
		var capasBase = {
		
			"Capa 1": osm,
			"Capa 2": osm2,
			"Capa 3": hn,
			"Esri - Imagery": ESRI_2,
			"Esri - Topografico": ESRI_topo,
			"Esri - National Geopraphic Liza": ESRI,
			};
			
		var capasOverlay = {
		
			"Capa 1": osm,
			"Capa 2": osm2,
			};
						
		new L.control.layers(capasBase, capasOverlay,{collapsed:false}).addTo(mapa);
		
		L.MakiMarkers.accessToken = "pk.eyJ1IjoibGl6YS1rYWZhdGkyMDE5IiwiYSI6ImNrMDV0ejdxOTAwY3IzYm90azl5bWFwYm4ifQ.-f3pA2idzqzRASVWgoQZvg";
			
			
		var plazacentral = L.marker([15.581156, -84.976338]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("PARQUE NATIONAL RIO PLATANO");
		
		var plazacentral = L.marker([14.322302, -87.614631]);
		mapa.addLayer(plazacentral);
		plazacentral.bindPopup("PARQUE LA PAZ, LA PAZ");
		
		var sta = L.marker([14.078036, -87.196194]);
		mapa.addLayer(sta);
		sta.bindPopup("PARQUE MIRAMONTES");
		
		var inl = L.marker([14.332939, -85.522645]);
		mapa.addLayer(inl);
		inl.bindPopup("PATUCA NATIONAL PARK");
		
		var inl = L.marker([14.245598, -87.122336]);
		mapa.addLayer(inl);
		inl.bindPopup("PARK LA TIGRA");
		
		var inl = L.marker([14.139559, -87.040670]);
		mapa.addLayer(inl);
		inl.bindPopup("OBRERO PARK");
		
		var inl = L.marker([15.545581, -88.305142]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK CUSUCO");
		
		var inl = L.marker([15.244159, -88.007603]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK EL OCOTE");
		
		var inl = L.marker([14.819942, -87.876171]);
		mapa.addLayer(inl);
		inl.bindPopup("CERRO AZUL MEAMBAR NATIONAL PARK ");
		
		var inl = L.marker([14.821156, -87.887831]);
		mapa.addLayer(inl);
		inl.bindPopup("CELAQUE NATIONAL PARK");
		
		var inl = L.marker([14.526022, -87.493871]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK MONTAÑA DE COMAYAGUA");
		
		var inl = L.marker([13.909223, -87.252517]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK LOS ENCUENTROS");
		
		var inl = L.marker([14.284619, -87.404487]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK AURORA");
		
		var inl = L.marker([14.767710,-88.893316]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK COPAN");
		
		var inl = L.marker([14.422183, -87.609575]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK VILLAMAR");
		
		var inl = L.marker([14.071167, -87.282987]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK NACIONES UNIDAS");
		
		var inl = L.marker([14.828663, -88.187393]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK MONTAÑA DE SANTA BARBARA");
		
		var inl = L.marker([15.445466, -87.942913]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK ZIZIMA ECO WATER PARK");
		
		var inl = L.marker([15.740916, -87.455982]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK LANCETILLA");
		
		var inl = L.marker([15.618948, -86.862183]);
		mapa.addLayer(inl);
		inl.bindPopup("NATIONAL PARK PICO BONITO");
		
		var inl = L.marker([14.871674, -87.982476]);
		mapa.addLayer(inl);
		inl.bindPopup("LAGO DE YOJOA");
		
		new L.Control.Zoom({ position: 'topright'}).addTo(mapa);
		
		var miniMap = new L.Control.MiniMap(osm2,{ toggleDisplay: true, position: 'bottomright' }).addTo(mapa);
		var MousePosition = new L.control.mousePosition(osm).addTo(mapa);
		var escala = L.control.scale().addTo(mapa);
		var viewCenter = new L.Control.ViewCenter(mapa);
			mapa.addControl(viewCenter);
			
				
	</script>
	
	</body>
	
	<p><i><strong><font size="4", color="green">Estudiante: Liza Mariel Kafati Vasquez</font></strong></i></P>
	<font face="Comic Sans MS">Maestría en Gestión y Ordenamiento Territorial MOGT5/Universidad Nacional Autónoma de Honduras (UNAH)</font>
</html>
