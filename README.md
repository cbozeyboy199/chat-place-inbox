# chat-place-inbox 
<button onclick="window.location.href='https://cbozeyboy199.github.io/chat-place/'">back to chat</button>

from cbozey: <button onclick="window.location.href='https://cbozeyboy199.github.io'">open</button>

      </div>
      <div class="description noborders">
        <span>Profile URL address</span><br/>
        <div class="fluid">
          <input type="button" id="addSenderInfo" class="link noborders right" value="Load data"/>
          <div style="overflow: hidden;">
            <input type="text" id="senderId" class="long-input"  placeholder="http://www.facebook.com/example"/>
          </div>
        </div>
          <p class="divider">or fill in the following fields&hellip;</p>
          <span>Name</span><br/>
          <input type="text" id="senderName" placeholder="Anonymous"  class="short-input"/>
          <br/>
          <span>Image URL address</span><br/>
          <input type="text" id="senderImg"  class="long-input" />
        </div>
        <div class="description noborders">
          <span>Message from <span id="senderNameSpan2">&hellip;</span></span>
          <div style="width: 100%; overflow: hidden;">
          <div style="width: 32px;margin-top:1px; float: left;">
            <img id="profilePic" height='32' width='32' src="img/pic.jpg"/>
          </div>
          <div style="margin-left: 40px;">
            <textarea  id="senderMsg" placeholder="Write a message&hellip;"></textarea><br/>
            <input type="button" id="addSenderMsg" class="link noborders" value="Send message"/>
            <div class="right">
                <input type="checkbox" id="sendOnReturn" checked="true"/><label for="sendOnReturn" id="sendOnReturnLbl">Send message when pressing <b>Enter</b></label>
            </div>
          </div>
        </div>
      </div>
      <div>
      <div id="chatWindow" class="left">
        <div id="titleBar">
          <div id="titlebarButtonWrapper" class="right"><a id="addFriends" class="button"></a><a id="openCam" class="button"></a><a id="openConfig" class="button2"></a><a id="closeWindow" class="button"></a></div>
          <div class="titlebarTextWrapper"><img id="status" src="img/pixel.gif" width="1" height="1" class="online"/><span id="senderNameSpan" >Anonymous</span></div>
        </div>
        <div id="conversation">
          <hr id="conversationSpacer"/>
        </div>
        <div id="footerWrapper">
          <div class="right"><a id="takePic"></a><a id="addSmiley"></a></div>
          <div id="textArea"><textarea id="msgBox"></textarea></div>
        </div>
      </div>
      <div class="description noborders right" style="overflow:hidden;width:197px;height:256px;">
        <input type="checkbox" id="blurCheck"/><label for="blurCheck">Blur name and image</label><hr/>
        <span>Status</span><br/>
        <label><input type="radio" name="statusRadio" value="0"/>Offline</label><br/>
        <label><input type="radio" name="statusRadio" value="1" checked>Online</label><br/>
        <label><input type="radio" name="statusRadio" value="2">Mobile</label><br/>
        <span>Date</span><br/>
        <div class="fluid">
          <input type="button" id="addDateStamp" class="link noborders right" value="+"/>
          <div style="overflow: hidden;">
            <input type="text" id="dateStamp" placeholder="32 february 00.01.02" class="long-input"/>
          </div>
        </div>
      </div>
      </div>
      <div style="clear:both;color:rgb(137, 143, 158);font-size:12px;">I am not affiliated with Facebook Inc. nor do I take responsibility for any reaction caused by a simulated conversation. Have fun, experiment, or prank your friends, just be kindhearted.</div>
      <div style="margin-top:14px;display:block;text-align:center;"><div class="fb-like" data-href="https://chatsimulator.com" data-layout="button_count" data-action="like" data-show-faces="true" data-share="true"></div>
      </div>
      </div>
  </body>
</html>
