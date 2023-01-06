Tambahkan jQuery di <head>
<head>
    ...
    <script src="http://code.jquery.com/jquery-2.2.1.min.js"></script>
</head>

Tambahkan atribut onload 
<body onload="Load()">

Buat div dengan id (spt. Load)
<div id="Load">
    <h1>Loading...</h1>
</div>

Tambahkan z-index di style
<style>
    #Load {
        z-index:1000;
        background:rgba(255,255,255,0.9);
    }
</style>

Buat <script> di ujung <body>
  ...
    <script>

    </script>
</body>

Atau dengan file,
...
    <script src="load.js"></script>
</body>

Isi dengan script yang sudah saya berikan pada "load.js"

Selesai
