<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla Periódica en AR.js</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://cdn.rawgit.com/jeromeetienne/ar.js/1.7.2/aframe/build/aframe-ar.min.js"></script>
</head>
<body style="margin: 0; overflow: hidden;">
    <a-scene embedded arjs>
        <!-- Definir marcador (puedes cambiar "hiro" por otro personalizado) -->
        <a-marker preset="hiro">
            <!-- Modelo 3D -->
            <a-entity position="0 0 0" scale="0.5 0.5 0.5" 
                      gltf-model="https://cdn.jsdelivr.net/gh/KhronosGroup/glTF-Sample-Models/2.0/Duck/glTF/Duck.gltf">
            </a-entity>
        </a-marker>
        <a-entity camera></a-entity>
    </a-scene>
</body>
</html>
