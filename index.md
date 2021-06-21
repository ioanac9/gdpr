Student: Constantinescu Ioana <br>

<script> document.cookie = "session: GDPR";
  document.cookie = "collecting data...";
  function alertCookie() { alert(document.cookie); } </script>
 <button onclick="alertCookie()">Show cookies</button>
 <br><br>
 
 <script> document.cookie = "test1=Hello";
  document.cookie = "test2=World";
  const cookieValue = document.cookie
  .split('; ')
  .find(row => row.startsWith('test2='))
  .split('=')[1];
   function alertCookieValue() {
     alert(cookieValue);}</script>
 <button onclick="alertCookieValue()">Show cookie value</button>
 
 <script>
  function doOnce() {
  if (!document.cookie.split('; ').find(row => row.startsWith('doSomethingOnlyOnce'))) {
    alert("Do something here!");
    document.cookie = "doSomethingOnlyOnce=true; expires=Fri, 31 Dec 9999 23:59:59 GMT";
  }} </script>
<button onclick="doOnce()">Only do something once</button>

<script>
function resetOnce() {
  document.cookie = "doSomethingOnlyOnce=; expires=Thu, 01 Jan 1970 00:00:00 GMT";}</script>
 <button onclick="resetOnce()">Reset only once cookie</button> 

<a href='https://didatec-my.sharepoint.com/:w:/r/personal/constantinescu_ge_io_utcluj_didatec_ro/_layouts/15/Doc.aspx?sourcedoc=%7B3B1D8511-284A-4B5A-9428-51F10D17108A%7D&file=DPIA_CI.docx&action=default&mobileredirect=true&ct=1624308515409&wdOrigin=OFFICECOM-WEB.MAIN.OTHER&cid=8153d7f5-bfec-4cd9-9220-60ff9354c80a'> DPIA</a>

