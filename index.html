<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🌎 Enciclopedia Animal</title>

<style>
*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:Arial,Helvetica,sans-serif;
    background:#07131b;
    color:white;
}

header{
    padding:35px 20px;
    text-align:center;
    background:linear-gradient(135deg,#087f5b,#123f68);
}

h1{
    margin:0;
    font-size:clamp(32px,7vw,60px);
}

header p{
    max-width:850px;
    margin:15px auto 20px;
    color:#d9f5e9;
}

#buscador{
    width:min(900px,95%);
    padding:16px 20px;
    border:none;
    border-radius:18px;
    font-size:17px;
    outline:none;
}

nav{
    display:flex;
    gap:8px;
    flex-wrap:wrap;
    justify-content:center;
    padding:15px;
    background:#091c26;
    position:sticky;
    top:0;
    z-index:10;
}

nav button{
    border:1px solid #315564;
    background:#102a36;
    color:white;
    padding:10px 14px;
    border-radius:999px;
    cursor:pointer;
}

nav button:hover,
nav button.activo{
    background:#1b6b58;
}

#contador{
    text-align:center;
    padding:18px;
    color:#bde8d7;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
    gap:20px;
    padding:20px;
    max-width:1450px;
    margin:auto;
}

.card{
    background:#10232c;
    border:1px solid #24434f;
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 8px 25px #0006;
    transition:.2s;
}

.card:hover{
    transform:translateY(-5px);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
    display:block;
    background:#183641;
}

.txt{
    padding:16px;
}

.txt h2{
    margin:0 0 7px;
    font-size:21px;
}

.cientifico{
    color:#9ed5c3;
    font-style:italic;
    font-size:14px;
}

.etiqueta{
    display:inline-block;
    margin-top:10px;
    padding:6px 10px;
    border-radius:10px;
    background:#1b4b59;
    font-size:12px;
}

.sonido{
    margin-top:13px;
    border:0;
    border-radius:12px;
    padding:10px 13px;
    background:#e6f5ef;
    color:#08221a;
    cursor:pointer;
    font-weight:bold;
}

.sonido:hover{
    background:#b9e9d8;
}

#vacio{
    text-align:center;
    padding:60px;
    color:#a8c6c0;
}

footer{
    text-align:center;
    padding:35px;
    color:#9ab8b2;
}
</style>
</head>

<body>

<header>

<h1>🌎 Enciclopedia Animal</h1>

<p>
Explora animales reales de todo el planeta:
mamíferos, aves, reptiles, anfibios, peces,
insectos, arácnidos, moluscos, crustáceos y más.
</p>

<input
id="buscador"
type="search"
placeholder="🔎 Busca un animal o nombre científico..."
>

</header>


<nav id="filtros"></nav>

<div id="contador"></div>

<main
class="grid"
id="lista">
</main>

<div id="vacio" hidden>
No encontré animales con esa búsqueda. 🧐
</div>


<footer>
🌎 Enciclopedia Animal — especies reales
</footer>


<script>

/* =====================================================
   ANIMALES REALES
   ===================================================== */

const animales = [

/* ================= MAMÍFEROS ================= */

{
nombre:"León",
cientifico:"Panthera leo",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Lion_waiting_in_Namibia.jpg"
},

{
nombre:"Tigre",
cientifico:"Panthera tigris",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Tiger_in_Ranthambhore.jpg"
},

{
nombre:"Jaguar",
cientifico:"Panthera onca",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Jaguar.jpg"
},

{
nombre:"Leopardo",
cientifico:"Panthera pardus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Leopard_africa.jpg"
},

{
nombre:"Guepardo",
cientifico:"Acinonyx jubatus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Cheetah4.jpg"
},

{
nombre:"Puma",
cientifico:"Puma concolor",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Puma_concolor.jpg"
},

{
nombre:"Lobo gris",
cientifico:"Canis lupus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Canis_lupus_laying.jpg"
},

{
nombre:"Zorro rojo",
cientifico:"Vulpes vulpes",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Vulpes_vulpes_ssp_fulvus.jpg"
},

{
nombre:"Oso polar",
cientifico:"Ursus maritimus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Polar_Bear_2004-11-15.jpg"
},

{
nombre:"Oso pardo",
cientifico:"Ursus arctos",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Grizzly_Bear.jpg"
},

{
nombre:"Panda gigante",
cientifico:"Ailuropoda melanoleuca",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Giant_Panda_001.jpg"
},

{
nombre:"Koala",
cientifico:"Phascolarctos cinereus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Koala_climbing_tree.jpg"
},

{
nombre:"Canguro rojo",
cientifico:"Osphranter rufus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Red_kangaroo_-_melbourne_zoo.jpg"
},

{
nombre:"Elefante africano",
cientifico:"Loxodonta africana",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/African_Bush_Elephant.jpg"
},

{
nombre:"Elefante asiático",
cientifico:"Elephas maximus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Asian_elephant.jpg"
},

{
nombre:"Jirafa",
cientifico:"Giraffa camelopardalis",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Giraffe_standing.jpg"
},

{
nombre:"Cebra de llanura",
cientifico:"Equus quagga",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Plains_Zebra_Equus_quagga.jpg"
},

{
nombre:"Rinoceronte blanco",
cientifico:"Ceratotherium simum",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/White_Rhinoceros.jpg"
},

{
nombre:"Hipopótamo",
cientifico:"Hippopotamus amphibius",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Hippo_water.jpg"
},

{
nombre:"Gorila occidental",
cientifico:"Gorilla gorilla",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Gorilla_gorilla_gorilla8.jpg"
},

{
nombre:"Chimpancé común",
cientifico:"Pan troglodytes",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Pan_troglodytes.jpg"
},

{
nombre:"Orangután de Borneo",
cientifico:"Pongo pygmaeus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Orangutan_Pongo_pygmaeus.jpg"
},

{
nombre:"Delfín mular",
cientifico:"Tursiops truncatus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Tursiops_truncatus_01.jpg"
},

{
nombre:"Orca",
cientifico:"Orcinus orca",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Orca_pod.jpg"
},

{
nombre:"Ballena azul",
cientifico:"Balaenoptera musculus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Blue_whale.jpg"
},

{
nombre:"Cachalote",
cientifico:"Physeter macrocephalus",
grupo:"Mamífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Sperm_whale.jpg"
},

/* ================= AVES ================= */

{
nombre:"Águila real",
cientifico:"Aquila chrysaetos",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Aquila_chrysaetos.jpg"
},

{
nombre:"Halcón peregrino",
cientifico:"Falco peregrinus",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Falco_peregrinus.jpg"
},

{
nombre:"Búho real",
cientifico:"Bubo bubo",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Bubo_bubo.jpg"
},

{
nombre:"Lechuza común",
cientifico:"Tyto alba",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Tyto_alba_-flying-8.jpg"
},

{
nombre:"Cóndor andino",
cientifico:"Vultur gryphus",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Vultur_gryphus_-Chile-8.jpg"
},

{
nombre:"Flamenco común",
cientifico:"Phoenicopterus roseus",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Greater_Flamingo.jpg"
},

{
nombre:"Pingüino emperador",
cientifico:"Aptenodytes forsteri",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Emperor_Penguin_Manchot_empereur.jpg"
},

{
nombre:"Avestruz",
cientifico:"Struthio camelus",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Struthio_camelus.jpg"
},

{
nombre:"Tucán toco",
cientifico:"Ramphastos toco",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Ramphastos_toco_-Brazil-8.jpg"
},

{
nombre:"Guacamayo azul y amarillo",
cientifico:"Ara ararauna",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Ara_ararauna.jpg"
},

{
nombre:"Pavo real",
cientifico:"Pavo cristatus",
grupo:"Ave",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Peacock_Plumage.jpg"
},

/* ================= REPTILES ================= */

{
nombre:"Cocodrilo del Nilo",
cientifico:"Crocodylus niloticus",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Nile_crocodile.jpg"
},

{
nombre:"Cocodrilo americano",
cientifico:"Crocodylus acutus",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Crocodylus_acutus.jpg"
},

{
nombre:"Dragón de Komodo",
cientifico:"Varanus komodoensis",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Komodo_dragon.jpg"
},

{
nombre:"Iguana verde",
cientifico:"Iguana iguana",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Iguana_iguana.jpg"
},

{
nombre:"Camaleón velado",
cientifico:"Chamaeleo calyptratus",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Chamaeleo_calyptratus.jpg"
},

{
nombre:"Tortuga verde",
cientifico:"Chelonia mydas",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Green_turtle.jpg"
},

{
nombre:"Tortuga laúd",
cientifico:"Dermochelys coriacea",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Leatherback_turtle.jpg"
},

{
nombre:"Pitón reticulada",
cientifico:"Malayopython reticulatus",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Reticulated_python.jpg"
},

{
nombre:"Cobra real",
cientifico:"Ophiophagus hannah",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Ophiophagus_hannah.jpg"
},

{
nombre:"Serpiente de cascabel diamante occidental",
cientifico:"Crotalus atrox",
grupo:"Reptil",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Crotalus_atrox.jpg"
},

/* ================= ANFIBIOS ================= */

{
nombre:"Ajolote",
cientifico:"Ambystoma mexicanum",
grupo:"Anfibio",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Axolotl.jpg"
},

{
nombre:"Rana de ojos rojos",
cientifico:"Agalychnis callidryas",
grupo:"Anfibio",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Agalychnis_callidryas.jpg"
},

{
nombre:"Rana toro americana",
cientifico:"Lithobates catesbeianus",
grupo:"Anfibio",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Lithobates_catesbeianus.jpg"
},

{
nombre:"Salamandra de fuego",
cientifico:"Salamandra salamandra",
grupo:"Anfibio",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Salamandra_salamandra.jpg"
},

{
nombre:"Sapo de caña",
cientifico:"Rhinella marina",
grupo:"Anfibio",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Rhinella_marina.jpg"
},

/* ================= PECES ================= */

{
nombre:"Gran tiburón blanco",
cientifico:"Carcharodon carcharias",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Great_white_shark.jpg"
},

{
nombre:"Tiburón ballena",
cientifico:"Rhincodon typus",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Whale_shark.jpg"
},

{
nombre:"Pez payaso común",
cientifico:"Amphiprion ocellaris",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Amphiprion_ocellaris.jpg"
},

{
nombre:"Caballito de mar común",
cientifico:"Hippocampus hippocampus",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Hippocampus_hippocampus.jpg"
},

{
nombre:"Pez globo japonés",
cientifico:"Takifugu rubripes",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Takifugu_rubripes.jpg"
},

{
nombre:"Atún rojo del Atlántico",
cientifico:"Thunnus thynnus",
grupo:"Pez",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Thunnus_thynnus.jpg"
},

/* ================= INSECTOS ================= */

{
nombre:"Mariposa monarca",
cientifico:"Danaus plexippus",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Monarch_Butterfly_Danaus_plexippus.jpg"
},

{
nombre:"Abeja occidental",
cientifico:"Apis mellifera",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Apis_mellifera.jpg"
},

{
nombre:"Hormiga cortadora de hojas",
cientifico:"Atta cephalotes",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Atta_cephalotes.jpg"
},

{
nombre:"Libélula emperador",
cientifico:"Anax imperator",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Anax_imperator.jpg"
},

{
nombre:"Mantis religiosa",
cientifico:"Mantis religiosa",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Mantis_religiosa.jpg"
},

{
nombre:"Escarabajo rinoceronte europeo",
cientifico:"Oryctes nasicornis",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Oryctes_nasicornis.jpg"
},

{
nombre:"Mariquita de siete puntos",
cientifico:"Coccinella septempunctata",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Coccinella_septempunctata.jpg"
},

{
nombre:"Saltamontes egipcio",
cientifico:"Anacridium aegyptium",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Anacridium_aegyptium.jpg"
},

{
nombre:"Cigarra periódica",
cientifico:"Magicicada septendecim",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Magicicada_septendecim.jpg"
},

{
nombre:"Mosquito común",
cientifico:"Culex pipiens",
grupo:"Insecto",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Culex_pipiens.jpg"
},

/* ================= ARÁCNIDOS ================= */

{
nombre:"Tarántula de rodillas rojas mexicana",
cientifico:"Brachypelma hamorii",
grupo:"Arácnido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Brachypelma_hamorii.jpg"
},

{
nombre:"Escorpión amarillo",
cientifico:"Buthus occitanus",
grupo:"Arácnido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Buthus_occitanus.jpg"
},

{
nombre:"Araña de jardín europea",
cientifico:"Araneus diadematus",
grupo:"Arácnido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Araneus_diadematus.jpg"
},

{
nombre:"Araña saltarina cebra",
cientifico:"Salticus scenicus",
grupo:"Arácnido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Salticus_scenicus.jpg"
},

/* ================= MOLUSCOS ================= */

{
nombre:"Pulpo común",
cientifico:"Octopus vulgaris",
grupo:"Molusco",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Octopus_vulgaris.jpg"
},

{
nombre:"Calamar gigante",
cientifico:"Architeuthis dux",
grupo:"Molusco",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Architeuthis_dux.jpg"
},

{
nombre:"Nautilo común",
cientifico:"Nautilus pompilius",
grupo:"Molusco",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Nautilus_pompilius.jpg"
},

{
nombre:"Caracol de jardín",
cientifico:"Cornu aspersum",
grupo:"Molusco",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Cornu_aspersum.jpg"
},

/* ================= CRUSTÁCEOS ================= */

{
nombre:"Cangrejo de la costa",
cientifico:"Carcinus maenas",
grupo:"Crustáceo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Carcinus_maenas.jpg"
},

{
nombre:"Langosta americana",
cientifico:"Homarus americanus",
grupo:"Crustáceo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Homarus_americanus.jpg"
},

{
nombre:"Camarón mantis pavo real",
cientifico:"Odontodactylus scyllarus",
grupo:"Crustáceo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Odontodactylus_scyllarus.jpg"
},

{
nombre:"Cangrejo araña japonés",
cientifico:"Macrocheira kaempferi",
grupo:"Crustáceo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Macrocheira_kaempferi.jpg"
},

/* ================= EQUINODERMOS ================= */

{
nombre:"Estrella de mar común",
cientifico:"Asterias rubens",
grupo:"Equinodermo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Asterias_rubens.jpg"
},

{
nombre:"Erizo de mar común",
cientifico:"Paracentrotus lividus",
grupo:"Equinodermo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Paracentrotus_lividus.jpg"
},

{
nombre:"Pepino de mar",
cientifico:"Holothuria tubulosa",
grupo:"Equinodermo",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Holothuria_tubulosa.jpg"
},

/* ================= CNIDARIOS ================= */

{
nombre:"Medusa luna",
cientifico:"Aurelia aurita",
grupo:"Cnidario",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Aurelia_aurita.jpg"
},

{
nombre:"Anémona de mar común",
cientifico:"Actinia equina",
grupo:"Cnidario",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Actinia_equina.jpg"
},

{
nombre:"Coral cuerno de alce",
cientifico:"Acropora palmata",
grupo:"Cnidario",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Acropora_palmata.jpg"
},

/* ================= ANÉLIDOS ================= */

{
nombre:"Lombriz de tierra común",
cientifico:"Lumbricus terrestris",
grupo:"Anélido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Lumbricus_terrestris.jpg"
},

{
nombre:"Sanguijuela medicinal",
cientifico:"Hirudo medicinalis",
grupo:"Anélido",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Hirudo_medicinalis.jpg"
},

/* ================= PORÍFEROS ================= */

{
nombre:"Esponja de barril gigante",
cientifico:"Xestospongia muta",
grupo:"Porífero",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Xestospongia_muta.jpg"
},

/* ================= TARDÍGRADOS ================= */

{
nombre:"Tardígrado",
cientifico:"Hypsibius exemplaris",
grupo:"Tardígrado",
imagen:"https://commons.wikimedia.org/wiki/Special:FilePath/Tardigrade.jpg"
}

];


/* =====================================================
   CATEGORÍAS
   ===================================================== */

const grupos=[
"Todos",
...new Set(animales.map(a=>a.grupo))
];

let filtro="Todos";

const filtros=document.getElementById("filtros");

grupos.forEach(grupo=>{

    const boton=document.createElement("button");

    boton.textContent=grupo;

    if(grupo==="Todos"){
        boton.classList.add("activo");
    }

    boton.onclick=()=>{

        filtro=grupo;

        document
        .querySelectorAll("nav button")
        .forEach(b=>b.classList.remove("activo"));

        boton.classList.add("activo");

        mostrarAnimales();
    };

    filtros.appendChild(boton);

});


/* =====================================================
   SONIDO
   ===================================================== */

function escuchar(nombre){

    if(!("speechSynthesis" in window)){
        alert("Tu navegador no tiene síntesis de voz.");
        return;
    }

    speechSynthesis.cancel();

    const voz=new SpeechSynthesisUtterance(nombre);

    voz.lang="es-MX";
    voz.rate=0.9;
    voz.pitch=1;

    speechSynthesis.speak(voz);
}


/* =====================================================
   MOSTRAR ANIMALES
   ===================================================== */

function mostrarAnimales(){

    const texto=
        document
        .getElementById("buscador")
        .value
        .toLowerCase()
        .trim();

    const lista=document.getElementById("lista");

    lista.innerHTML="";

    const encontrados=animales.filter(animal=>{

        const coincideGrupo=
            filtro==="Todos" ||
            animal.grupo===filtro;

        const contenido=
            (
                animal.nombre+
                " "+
                animal.cientifico+
                " "+
                animal.grupo
            ).toLowerCase();

        const coincideBusqueda=
            !texto ||
            contenido.includes(texto);

        return coincideGrupo && coincideBusqueda;

    });


    document.getElementById("contador").textContent=
        `🐾 ${encontrados.length} animales mostrados de ${animales.length} especies reales`;


    document.getElementById("vacio").hidden=
        encontrados.length!==0;


    encontrados.forEach(animal=>{

        const tarjeta=document.createElement("article");

        tarjeta.className="card";

        tarjeta.innerHTML=`

            <img
                loading="lazy"
                src="${animal.imagen}"
                alt="${animal.nombre}"
                onerror="this.style.display='none'"
            >

            <div class="txt">

                <h2>${animal.nombre}</h2>

                <div class="cientifico">
                    ${animal.cientifico}
                </div>

                <span class="etiqueta">
                    ${animal.grupo}
                </span>

                <br>

                <button
                    class="sonido"
                    onclick="escuchar('${animal.nombre.replace(/'/g,"\\'")}')"
                >
                    🔊 Escuchar nombre
                </button>

            </div>
        `;

        lista.appendChild(tarjeta);

    });

}


/* =====================================================
   BUSCADOR
   ===================================================== */

document
.getElementById("buscador")
.addEventListener(
    "input",
    mostrarAnimales
);


/* INICIAR */

mostrarAnimales();

</script>

</body>
</html>
