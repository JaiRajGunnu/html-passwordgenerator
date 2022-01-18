# html-passwordgenerator

 <span style="font-family: Fredoka One; font-size: medium;"><span style="color: red;"><info class="desc"></info><b>How to do</b></span>
</span><hr style="background-color: red; border-width: 0px; color: grey; height: 2px;" />
<h5 style="text-align: left;margin-top:10px"><span style="font-family: Fredoka One; font-weight: none;">Drag the bar to set the length of the password and select whether it should contain numbers or special characters. And finally, click on the generate password to generate it.</span></h5>

<div class="password-generator">
  <div class="head">
    <div class="title">
      Password
    </div>
  <div>
    </div>   
      <div class="pass">
    <textarea class="password" id="htmlText"></textarea>
        </div>

  </div>
  
  <div class="length">
    <div class="title">
      Length: <span>10</span>
    </div>
    <div class="input">
      <input id="password-length" max="20" type="range" value="10" />
    </div>
  </div>

  
  <div class="settings">
    <div class="title">
      Settings
    </div>
    <div class="list">
      <div class="item">
        <input id="setting-number" type="checkbox" />
        <label>Number</label>
      </div>
      <div class="item">
        <input id="setting-specialchar" type="checkbox" />
        <label>Special Characters</label>
      </div>
    </div>
  </div>
  <button id="generate-password">Generate Password</button>
  
     <center> <htmlbtn onclick="copyHTML()" title="Copy to clipboard">Copy<y class="copy" style="font-weight: 600; padding-left: 7px; padding-top: 2.5px;" title="Copy to clipboard"></y></htmlbtn> </center>
 

  </div>

<center>
<span style="font-size: x-small;">
Passwords will not be stored on our server. <br />Read our <a href="https://epgsk.blogspot.com/p/you-can-use-our-services-in-variety-of.html"> <u>Privacy Policy</u> </a> here.</span>
</center>
