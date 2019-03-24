# Oneplus Vendor
<p>Here is a fork from TheMuppets.</p>
Steps for adding it:
<ul>
<li>Initialize the kitchen with <code>source/envsetup.sh</code></li>
<li>Prepare the device with <code>breakfast [device]</code>. Should result in a error.</li>
<li>Go to <code>.repo/local_manifests/</code> and open <code>roomservice.xml</code></li>
<li>Add the line <code>&lt;project depth="1" name="koboldo81/proprietary_vendor_oneplus" path="vendor/oneplus" /&gt;</code> defore the xml closing.</li>
<li>Make a <code>repo sync</code></li>
<li>Enter the <code>breakfast [device]</code> again.</li>
</ul>

<p>Happy cooking!</p>
