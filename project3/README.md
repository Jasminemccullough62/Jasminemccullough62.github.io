<!DOCTYPE HTML>
<html>
<head>
  <title>Music Player</title>
  <style>
     body {
      background: url('images/background.jpeg'); 
    }

    #cp {
      width: 600px;           
      margin: 100px auto;    
      text-align: center;   
    }

    #cp button {
      margin: 5px; 
      padding: 10px; 
      font-size: 16px; 
      cursor: pointer; 
    }

    button {
      background-color: red; 
      padding: 10px;           
      font-size: 16px;         
      border: none;            
      width: 100px;            
      color: white;           
      cursor: pointer;         
    }

    #message {
      font-weight: bold; 
      color: white; 
      margin-top: 90px; 
    }
  </style>

  <script src="//code.jquery.com/jquery.min.js"></script>
  <script src="app.js"></script>

</head>
<body>
  <!-- Control Panel will go here -->
  <div id="cp">
    <button id="play">Play</button>       
    <button id="stop">Stop</button>       
    <button id="pause">Pause</button>     
    <button id="mute">Mute</button>       
    <button id="unmute">Unmute</button>   
    <button id="volumeUp">Volume Up</button>   
    <button id="volumeDown">Volume Down</button> 

    <p id="message">Waiting</p>
  </div>
  <!-- Audio player will go here -->
  <audio id="player">
  <source src="music/song1.mp3" type="audio/mpeg">
  </audio>

</body>
</html>
