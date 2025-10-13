#  OpenCV for Georegistration

Study for the OpenCV theories.   Read, Manipulate & Analyze Img

---

## Idea & Workflow

### 1. OpenCV — *Pixel Puzzle Alignment*
- Load **two images**:  
  - **Raw image** (to be aligned)  
  - **Reference image** (already aligned)  
- Detect and extract **keypoints & features**  
- Match corresponding features between the two images  
- Compute the **mathematical transformation** (homography)  
- Warp the raw image so its pixels line up with the reference  
- ➡️ *Think of it like moving puzzle pieces until they snap into place*  

---

### 2. GDAL — *Geospatial Grounding*
- Works at the **map level** rather than pixel matching  
- Uses the **reference image’s coordinates & projection**  
- Aligns and “stamps” the raw image with correct geospatial info  
- Outputs a **GeoTIFF** with map coordinates  
- ➡️ *Like writing an address on a letter so it belongs on the map*  

---

## ⚡ Combined Approach
- **OpenCV**: Handles the **pixel-level alignment**  
- **GDAL**: Anchors the aligned image into the **real-world map system**  

**Result →** A properly georeferenced GeoTIFF ready for GIS workflows.  
