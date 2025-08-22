<p>
    <span style="font-size:22px;"><strong>Local Service Guide (Demo Download)&nbsp;</strong></span><br>
    <br>
    Do you want to join the group chat? If you would like to join the [API Developers] group (for developers only; non-developers will be removed), or the [Custom Script Development] group, please click here to contact customer service, and we will arrange for you to join the group!&nbsp;<br>
    <br>
    Kind reminder: Please select the appropriate group according to your needs to ensure the relevance and quality of the communication.&nbsp;<br>
    <br>
    <span style="font-size:22px;"><strong>Introduction&nbsp;</strong></span><br>
    <br>
    Call the local API to operate the app to open, configure the proxy, etc., to help users realize the automatic script function.&nbsp;<br>
    <br>
    <span style="font-size:22px;"><strong>JavaScript demo&nbsp;</strong></span><br>
    <br>
    Note: The request data is only for demo, for details, please refer to the API document.&nbsp;<br>
    <br>
    <a target="_blank" rel="noopener noreferrer" href="https://doc.bitbrowser.net/api-docs/local-service-guide-demo-download"><span style="color:hsl(210, 75%, 60%);"><strong><u>Learn more</u></strong></span></a><br>
    <br>
    <span style="font-size:22px;"><strong>Python demo&nbsp;</strong></span><br>
    <br>
    Note: The request data is only for demo, for details, please refer to the API document.&nbsp;<br>
    <br>
    <a target="_blank" rel="noopener noreferrer" href="https://doc.bitbrowser.net/api-docs/local-service-guide-demo-download"><span style="color:hsl(210,75%,60%);"><strong><u>Learn more</u></strong></span></a><br>
    <br>
    <span style="font-size:22px;"><strong>Postman debug demo, import to use&nbsp;</strong></span><br>
    <br>
    <a target="_blank" rel="noopener noreferrer" href="https://doc.bitbrowser.net/api-docs/local-service-guide-demo-download"><span style="color:hsl(210,75%,60%);"><strong><u>Learn more</u></strong></span></a><br>
    <br>
    <span style="font-size:22px;"><strong>Service Introduction&nbsp;</strong></span><br>
    <br>
    Support the use of browser functions via Local API to help users run their own automation scripts.&nbsp;<br>
    <br>
    <span style="font-size:18px;"><strong>How to use&nbsp;</strong></span><br>
    1.Install and log in to BitBrowser.&nbsp;<br>
    2.To Settings, find Local API url and port.&nbsp;<br>
    3.Download and run demo.&nbsp;<br>
    <br>
    <span style="font-size:22px;"><strong>Interface instructions&nbsp;</strong></span><br>
    <br>
    Request method is post, and the parameter passing method is responseBody.&nbsp;<br>
    The interface returns a json object, success is true and the operation is successful. If there is any returned data, it will be appended to the data object&nbsp;<br>
    When the interface returns success as false, it means that the business failed, which may be due to program reasons or parameter verification, etc., and the failure information will be appended to msg&nbsp;<br>
    <br>
    <strong>// success example</strong><br>
    <strong>{</strong><br>
    <strong>&nbsp;success: true,</strong><br>
    <strong>&nbsp;data: {</strong><br>
    <strong>&nbsp; &nbsp;id: '2c9c29a28sdd33dds8026f78e380142',</strong><br>
    <strong>&nbsp; &nbsp;groupName: 'name'</strong><br>
    <strong>&nbsp;}</strong><br>
    <strong>}</strong>
</p>
<p>
    <strong>// failed example</strong><br>
    <strong>{ success: false, msg: 'Id is required' }</strong><br>
    <br>
    &nbsp;
</p>
<figure class="image">
    <img alt="1755853923594.jpg" src="https://img-website.bitbrowser.net/uploads/1755853923594_11ef0add81.jpg" srcset="https://img-website.bitbrowser.net/uploads/thumbnail_1755853923594_11ef0add81.jpg 210w, https://img-website.bitbrowser.net/uploads/small_1755853923594_11ef0add81.jpg 500w, https://img-website.bitbrowser.net/uploads/medium_1755853923594_11ef0add81.jpg 750w, https://img-website.bitbrowser.net/uploads/large_1755853923594_11ef0add81.jpg 1000w" sizes="100vw" width="1000">
</figure>
