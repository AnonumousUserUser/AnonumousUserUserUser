<div align="center">


<h1>Dual-Camera Smooth Zoom on Mobile Phones</h1>

<h2>(a) Existing dual-camera zoom</h2>

<h3>
Existing dual-camera zoom. For zooming between Ultra-Wide-Angle (UW) and Wide-Angle (W) cameras (i.e., from ×0.6 to ×1.0), smartphones (e.g., Xiaomi, OPPO, and vivo) generally crop out the specific area from the UW image, and scale the image up to the dimensions of the original. When the zoom factor changes from 0.9 to 1.0, the lens has to switch from UW to W, where notable geometric content and image color jump happen in the preview.
</h3>

<table>
   <colgroup>
    <col style="width: 25%;">
    <col style="width: 25%;">
    <col style="width: 25%;">
    <col style="width: 25%;">
  </colgroup>
  <tr> 
     <td>
          <center>UW Image (x0.6)    </center>
    </td>
     <td>
          <center>UW Image (x0.9)</center>
    </td>
     <td>
          <center>Camera Swiching (x0.9->x1.0)</center>
    </td>
     <td>
          <center>W Image (x0.6)</center>
    </td>
  </tr>
  <tr>
    <td>
       <img src="./jumps/18/intro_18_uw.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./jumps/18/intro_18_uwc.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./jumps/18/uwc2w.gif" alt="Image 3" width="500"/>
    </td>
    <td>
      <img src="./jumps/18/intro_18_w.png" alt="Image 2" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./jumps/20/intro_20_uw.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./jumps/20/intro_20_uwc.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./jumps/20/uwc2w.gif" alt="Image 3" width="500"/>
    </td>
    <td>
      <img src="./jumps/20/intro_20_w.png" alt="Image 2" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./jumps/79/intro_79_uw.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./jumps/79/intro_79_uwc.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./jumps/79/uwc2w.gif" alt="Image 3" width="500"/>
    </td>
    <td>
      <img src="./jumps/79/intro_79_w.png" alt="Image 2" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./jumps/83/intro_83_uw.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./jumps/83/intro_83_uwc.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./jumps/83/uwc2w.gif" alt="Image 3" width="500"/>
    </td>
    <td>
      <img src="./jumps/83/intro_83_w.png" alt="Image 2" width="500"/>
    </td>
  </tr>
</table>


<h2>(b) Dual-camera Smooth Zoom</h2>

<h3>We introduce dual-camera smooth zoom (DCSZ) task, aiming to achieve a fluid zoom preview.
some smooth zoom sequences rendered from our ZoomGS are provided below.
</h3>
<table>

   <colgroup>
    <col style="width: 33%;">
    <col style="width: 33%;">
    <col style="width: 33%;">
  </colgroup>

  <tr> 
     <td>
          <center>UW Image (x0.6)</center>
    </td>
     <td>
          <center>W Image (x1.0)</center>
    </td>
     <td>
          <center>Dual-Camera Smooth Zoom (x0.6->x1.0)</center>
    </td>
  </tr>
  <tr>
    <td>
       <img src="./3DGS/01/0.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./3DGS/01/100.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./3DGS/01/gif.apng" alt="Image 3" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./3DGS/63/0.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./3DGS/63/100.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./3DGS/63/gif.apng" alt="Image 3" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./3DGS/85/0.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./3DGS/85/100.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./3DGS/85/gif.apng" alt="Image 3" width="500"/>
    </td>
  </tr>

  <tr>
    <td>
       <img src="./3DGS/64/0.png" alt="Image 1" width="500"/>
    </td>
    <td>
      <img src="./3DGS/64/100.png" alt="Image 2" width="500"/>
    </td>
    <td>
      <img src="./3DGS/64/gif.apng" alt="Image 3" width="500"/>
    </td>
  </tr>


</table>




