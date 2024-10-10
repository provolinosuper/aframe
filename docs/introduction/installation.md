<!DOCTYPE html>
<html>
<head>
    <title>Esperienza AR con A-Frame</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://aframe.io/releases/1.2.0/aframe-ar.js"></script>
</head>
<body>
    <a-scene embedded arjs>
        <!-- Modello 3D -->
        <a-entity 
            gltf-model="url(C:\Users\utente\Downloads\modello_3d.glb)" 
            position="0 0 0" 
            scale="1 1 1">
        </a-entity>
        <a-marker-camera preset="hiro"></a-marker-camera>
    </a-scene>
</body>
</html>
