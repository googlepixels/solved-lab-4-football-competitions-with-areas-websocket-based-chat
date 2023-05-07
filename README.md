Download Link: https://assignmentchef.com/product/solved-lab-4-football-competitions-with-areas-websocket-based-chat
<br>
<h1>1.    Football competitions (with areas)</h1>

Modify the previous football tournament app to first show all available areas of the competitions (you can get them from this api: <a href="http://api.football-data.org/v2/areas">http://api.football-data.org/v2/areas</a>)

When user clicks one of the areas app will open other activity which will show a list of available competitions from that selected area. This API was already used in the previous assignment: <a href="http://api.football-data.org/v2/competitions?areas=2072">http://api.football-data.org/v2/competitions?areas=2072</a>

You should have two activities (one for areas and one for competitions) in your application.

Please follow good object oriented principles in your app design (architecture).

<h1>2.    WebSocket based chat</h1>

Create a chat application with web socket.

There are several libraries which you could use, I chose this one: <a href="https://github.com/TooTallNate/Java-WebSocket">https://github.com/TooTallNate/Java-WebSocket</a>

Client example (please note that this example has been made for standard (desktop) java. You need to modify it a bit to make it work on Android.

<a href="https://github.com/TooTallNate/Java-WebSocket/wiki#client-example">https://github.com/TooTallNate/Java-WebSocket/ </a><a href="https://github.com/TooTallNate/Java-WebSocket/wiki#client-example">wiki#client-example</a>

The chat server waits for your messages in this address:

<strong>ws://obscure-waters-98157.herokuapp.com</strong>