<h1>Pallycon
<a href="https://pallycon.com/">
   <img width="24" height="24" src="https://img.icons8.com/fluency/48/link.png" alt="link"/>
</a>
</h1>
<div style="display:flex;flex-direction:row;width:'100%';justify-content:space-between">
   <a href="https://pollycon-drm.vercel.app/">Demo</a>
   <a href="https://login.pallycon.com/?lang=en&_gl=1*juee59*_ga*MTI1NTQxMjQ2My4xNzE5MTE5NTMx*_ga_1J5K0D1B1Z*MTcxOTE1NTYxMi40LjEuMTcxOTE1NjA2Ni42MC4wLjA.">Login portal</a>
   <a href="https://console.pallycon.com/drm/setting">DRM settings </a>
   <a href="https://github.com/inka-pallycon/html5-player-drm-samples">Sample Codes for HTML5 </a>
</div>


<hr />

<h1>To Donwload Packager For Conversion of File</h1>
<a href="https://github.com/inka-pallycon/pallycon-drm-cli-packager">Packager Reference</a>
Command After downloading packager :
<code>PallyConPackager --enc_token YOUR-KMS-TOKEN-VALUE --content_id test-content-1 --dash -i ./input/test-content-1.mp4 -o ./output/test-content-1</code>
<ul>
    <li>YOUR-KMS-TOKEN-VALUE : get from DRM settings section</li>
    <li>i : Profide input file</li>
    <li>o : Output file</li>
</ul>

<h1>To generate token for communication</h1>
<a href="https://sample.pallycon.com/customdata/#createToken">Token Generation</a>
<ul>
    <li>SITE ID, SITE Key, ACCESS Key from DRM settings section</li>
    <li>DRM Type : Widevine , PlayReady</li>
    <li>USER ID : Add User ID</li>
    <li>Response Format : Default original only</li>
    <li>Key Rotation : Default false</li>
    <li>Token Rule : Set to empty object{}</li>
</ul>
<p>Note : To maintain token available for longer duration change token duration to max 999,999,999 or according need</p>



