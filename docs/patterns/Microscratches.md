# Micro scratches

An OSL shader that generates texture to make swirly micro scratch look by controlling the anisotropy and roughness.
Adapted from the shader by [cuckon](https://github.com/cuckon/scratched) with some more sensible names for the output parameters

## Parameters

### Density
Controls the heaviness of the scratches. Higher density will result in more scratches which takes longer to generate.

### roughness
Higher values will make the swirl longer along it's direction

#### default 
Roughness of the area that without scratches

#### min 
Will give each scratch a radom value which is greater then min

#### max 
Will give each scratch a radom value which is less then max


### anisotropy
Higher values will enlarge the swirl radius. Anisotropy is usually only noticable at higher roughness values

#### default 
Anisotropy of the area that without scratches

#### min 
Will give each scratch a radom value which is greater then min

#### max 
Will give each scratch a radom value which is less then max

### offset
Offsets the rotation off scratches. Can be used to achive effects like radiant or spiral scraches.

### width
Width of the scratches, in UV space. Usually 0.001 is a good place to start.
